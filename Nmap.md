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

    nmap [hostname atau IP]
Contoh: nmap 192.168.1.1
Perintah ini memindai host atau IP address tertentu untuk memeriksa port yang terbuka dan layanan yang berjalan.
Pemindaian Semua Port:

    nmap -p- [IP]
Contoh: nmap -p- 192.168.1.1
Perintah ini memindai semua port dari 1 hingga 65535.
Pemindaian Port Spesifik:

    nmap -p [nomor port] [IP]
Contoh: nmap -p 80 192.168.1.1
Memindai port tertentu pada host.
Pemindaian Cepat (Quick Scan):

    nmap -T4 [IP]
Contoh: nmap -T4 192.168.1.1
Pemindaian cepat dengan mengurangi waktu tunggu antara pemindaian.
Deteksi Sistem Operasi:

    nmap -O [IP]
Contoh: nmap -O 192.168.1.1
Mendeteksi sistem operasi host target.
Deteksi Versi Layanan:

    nmap -sV [IP]
Contoh: nmap -sV 192.168.1.1
Mengidentifikasi versi layanan yang berjalan di setiap port terbuka.
Pemindaian Stealth (TCP SYN Scan):

    nmap -sS [IP]
Contoh: nmap -sS 192.168.1.1
Pemindaian yang lebih "stealth" dengan mengirimkan paket SYN untuk menghindari deteksi firewall.
Pemindaian UDP:

    nmap -sU [IP]
Contoh: nmap -sU 192.168.1.1
Memindai port UDP yang terbuka.
Traceroute:

    nmap --traceroute [IP]
Contoh: nmap --traceroute 192.168.1.1
Menampilkan jalur yang dilalui oleh paket untuk mencapai host target.


       
