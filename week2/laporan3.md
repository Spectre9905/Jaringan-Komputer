# Laporan Praktikum Jaringan Komputer Modul 3
HTTP - Analisis HTTP Packet

# Tujuan Praktikum
1. Mahasiswa dapat menginvestigasi cara kerja protokol HTTP menggunakan Wireshark.

# Langkah-Langkah
1. Jalankan Aplikasi Wireshark dan pilih capture wifi
![](../assets/image/Modul1-2.png)
2. Lalu Buka URL: http://gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file3.html pada browser pastikan http dan muncul not secure seperti ini
![](../assets/image/Modul3-1.png)
3. Kembali ke wire shark dan ketik http pada bagian atas dan amati response nya
![](../assets/image/Modul3-2.png)
4. Lalu Buka URL: http://gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file4.html pada browser pastikan http
![](../assets/image/Modul3-3.png)
5. Perhatikan lagi response nya pada wireshark
![](../assets/image/Modul3-4.png)
6. Lalu Buka URL: http://gaia.cs.umass.edu/wireshark-labs/protected_pages/HTTP-wireshark-file5.html pada browser, akan muncul tampilan login seperti ini
![](../assets/image/Modul3-5.png)
7. Masukkan username wireshark-students dan password network

![](../assets/image/Modul3-6.png)

pastikan muncul seperti dibawah ini setelah sign in
![](../assets/image/Modul3-7.png)

8. Lihat lagi response nya di wireshark
![](../assets/image/Modul3-8.png)
disini kita bisa melihat username dan password dapat dicapture
