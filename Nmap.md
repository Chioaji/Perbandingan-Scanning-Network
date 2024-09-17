# Nmap
Nmap (Network Mapper) adalah sebuah alat yang digunakan untuk pemindaian jaringan dan audit keamanan. Fungsi utama Nmap adalah untuk memetakan jaringan dengan mengidentifikasi host dan layanan yang aktif pada jaringan tersebut. Berikut adalah beberapa fungsi spesifik dari Nmap:

1. Pemindaian Port: Nmap dapat digunakan untuk memindai port yang terbuka di perangkat dalam jaringan. Ini membantu mengidentifikasi layanan apa saja yang berjalan pada perangkat tersebut.

2. Deteksi Sistem Operasi: Nmap dapat mendeteksi sistem operasi yang digunakan oleh perangkat di jaringan, termasuk versi sistem operasi yang spesifik.

3. Deteksi Layanan: Selain memindai port, Nmap juga bisa mengidentifikasi layanan yang berjalan di setiap port terbuka, seperti HTTP, FTP, atau SSH, dan menentukan versinya.

4. Pemindaian Jaringan: Nmap memungkinkan administrator jaringan untuk memetakan perangkat yang terhubung ke suatu jaringan, memberikan gambaran lengkap tentang infrastruktur jaringan.

5. Audit Keamanan: Nmap sering digunakan dalam uji penetrasi untuk mengidentifikasi potensi kerentanan dalam sistem jaringan, seperti port terbuka yang tidak semestinya, layanan yang tidak terproteksi, atau perangkat yang rentan terhadap serangan.

6. Pemindaian Host Aktif: Nmap dapat mendeteksi host yang aktif di dalam jaringan dan membedakannya dari yang tidak aktif.

7. Pemindaian Topologi Jaringan: Dengan fitur tambahan seperti traceroute, Nmap dapat digunakan untuk memetakan topologi fisik dan logis jaringan, membantu dalam analisis rute data yang digunakan.

### Pada Nmap juga memiliki beberapa command yang bisa kita gunakan untuk scanning network target

Pemindaian Host atau IP Address:

Perintah ini memindai host atau IP address tertentu untuk memeriksa port yang terbuka dan layanan yang berjalan.
Pemindaian Semua Port:

    nmap [target]
![nmap](https://github.com/user-attachments/assets/04f3a803-7233-4584-842c-62a64315c422)

Memindai port tertentu pada host.
Pemindaian Cepat (Quick Scan):

    map -p [nomor port] [target]

![-p](https://github.com/user-attachments/assets/d53fb319-4c68-4a6f-84fc-01a782d70b27)

Pemindaian cepat dengan mengurangi waktu tunggu antara pemindaian.
Deteksi Sistem Operasi:

    nmap -T4 [target]
    

![T4](https://github.com/user-attachments/assets/075aedea-80e8-4835-a52e-609010510965)

Mendeteksi sistem operasi host target.
Deteksi Versi Layanan:

    nmap -O [target]
![-o](https://github.com/user-attachments/assets/55121d6b-ad1b-4d5a-9eb7-2c07a0435fd8)


Mengidentifikasi versi layanan yang berjalan di setiap port terbuka.
Pemindaian Stealth (TCP SYN Scan):

    nmap -sV [target]
![-sV](https://github.com/user-attachments/assets/183f1215-cef3-4398-a7d7-f26476356ea2)


Ping scan untuk melihat apakah host aktif atau tidak.

    nmap -sP [target]
![-sP](https://github.com/user-attachments/assets/83c22965-24c7-481e-bbde-015c4d634995)


 
 Menampilkan Detail Tambahan (Verbose):
 Menampilkan lebih banyak informasi selama proses pemindaian.


    nmap -v [IP]
![-v](https://github.com/user-attachments/assets/9cbf59ea-e216-438d-96af-d75c106e3477)



       
