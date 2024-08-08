# kode program
```dart
void main() {
  // Fungsi untuk menghitung rata-rata nilai siswa
  double hitungRataRata(List<int> nilaiSiswa) {
    if (nilaiSiswa.isEmpty) return 0.0;
    
    int totalNilai = 0;
    for (int nilai in nilaiSiswa) {
      totalNilai += nilai;
    }
    return totalNilai / nilaiSiswa.length;
  }

  // Fungsi untuk menentukan status kelulusan
  String cekKelulusan(double rataRata, double batasKelulusan) {
    return rataRata >= batasKelulusan ? "Lulus" : "Tidak Lulus";
  }

  // Closure untuk menentukan batas kelulusan berdasarkan mata pelajaran
  Function buatBatasKelulusan(String mataPelajaran) {
    double batasKelulusan;
    
    switch (mataPelajaran) {
      case "Matematika":
        batasKelulusan = 75.0;
        break;
      case "Bahasa Inggris":
        batasKelulusan = 70.0;
        break;
      default:
        batasKelulusan = 60.0;
    }
    
    return (List<int> nilai) => batasKelulusan;
  }

  // Daftar nilai siswa untuk beberapa mata pelajaran
  Map<String, List<int>> nilaiSiswa = {
    "Matematika": [80, 70, 90, 85],
    "Bahasa Inggris": [65, 72, 68, 75],
    "Ilmu Pengetahuan Alam": [55, 60, 65, 70],
  };

  // Menentukan hasil kelulusan untuk setiap mata pelajaran
  nilaiSiswa.forEach((mataPelajaran, nilai) {
    double rataRata = hitungRataRata(nilai);
    print("\nMata Pelajaran: $mataPelajaran");
    print("Nilai: $nilai");
    print("Rata-rata: ${rataRata.toStringAsFixed(2)}");

    // Menggunakan closure untuk mendapatkan batas kelulusan
    var batasKelulusanFungsi = buatBatasKelulusan(mataPelajaran);
    double batasKelulusanNilai = batasKelulusanFungsi(nilai);
    
    // Menentukan status kelulusan
    String statusKelulusan = cekKelulusan(rataRata, batasKelulusanNilai);
    print("Batas Kelulusan: ${batasKelulusanNilai.toStringAsFixed(2)}");
    print("Status: $statusKelulusan");
  });

  // Menggunakan anonymous function untuk menghitung jumlah nilai
  int jumlahNilai(List<int> nilaiList) {
    return nilaiList.reduce((a, b) => a + b);
  }

  print("\nMenggunakan anonymous function:");
  nilaiSiswa.forEach((mataPelajaran, nilai) {
    print("Mata Pelajaran: $mataPelajaran");
    print("Jumlah Nilai: ${jumlahNilai(nilai)}");
  });
}
```