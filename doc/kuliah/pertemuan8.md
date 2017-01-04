RESUME PERTEMUAN 8 GIS – KONFIGURASI  MAP PROXY

KONFIGURASI  MAP PROXY

1.  Latar Belakang

Untuk mengkomputasi hasi gambar dan mapserver agar bisa di reduksi dengan menggunakan MAP PROXY.

Map server merupakan aplikasi pemetaan GIS yang dioperasikan oleh sistem operasi seperti linux dan windows yang bersifat opensource yang berfungsi untuk menbaca data graphic.

2. Pembahasan

Pengertian MapProxy

Map server merupakan aplikasi pemetaan GIS yang dioperasikan oleh sistem operasi seperti linux dan windows yang bersifat opensource yang berfungsi untuk menbaca data graphic.

Cara install MapProxy

- --Ketikkan &quot;#istall python-pip dan python-dev&quot;
- --Lalu &quot;#pip install mapproxy&quot;
- --Setelah itu ketikkan &quot;#install Vwsqi&quot;
- --Tunggu hingga proses selesai.

Konfigurasi MapProxy

Ada dua file konfigurasi yang digunakan oleh MapProxy.

mappproxy.yaml

Ini adalah konfigurasi utama MapProxy. Ini mengkonfigurasi semua aspek server: Yang server harus dimulai, di mana berasal data dari, apa yang harus di-cache.

seed.yaml

File ini adalah konfigurasi untuk alat mapproxy-benih. Lihat penyemaian dokumentasi untuk informasi lebih lanjut.

Konfigurasi ini menggunakan format YAML. Wikipedia berisi pengenalan yang baik untuk YAML. Konfigurasi MapProxy dikelompokkan menjadi beberapa bagian, masing-masing mengkonfigurasi aspek yang berbeda dari MapProxy. Ini adalah bagian berikut:

•        GLOBALS: Internal dari MapProxy dan nilai-nilai default yang digunakan dalam bagian konfigurasi lainnya.

•        Layanan: Layanan MapProxy penawaran, misalnya WMS atau TMS.

•        sumber: Tentukan mana MapProxy dapat mengambil data baru.

•        cache: Konfigurasi cache internal.

•        lapisan: Konfigurasi lapisan yang MapProxy menawarkan. Setiap lapisan dapat terdiri dari beberapa sumber dan cache.

•        grid: Tentukan grid yang menggunakan MapProxy untuk menyelaraskan gambar cache.

Urutan bagian tidak penting, sehingga Anda dapat mengatur dengan cara Anda.

Untuk membuat satu set baru file konfigurasi untuk MapProxy panggilan:

mapproxy-util create -t base-config mymapproxy

Ini akan membuat direktori mymapproxy dengan contoh konfigurasi minimal (mapproxy.yaml dan seed.yaml) dan dua file konfigurasi contoh lengkap (full\_example.yaml dan full\_seed\_example.yaml).

Lihat dokumentasi konfigurasi untuk informasi lebih lanjut. Dengan konfigurasi default data cache akan ditempatkan di subdirektori cache\_data.

Untuk memulai server tes:

cd mymapproxy

mapproxy-util serve-develop mapproxy.yaml

Sudah ada lapisan tes dikonfigurasi yang mendapatkan data dari Omniscale OpenStreetMap WMS. Jangan ragu untuk menggunakan layanan ini untuk pengujian.

MapProxy dilengkapi dengan layanan demo yang berisi daftar WMS semua dikonfigurasi dan lapisan TMS. Anda dapat mengakses layanan yang di http: // localhost: 8080 / demo /.

3. Penutup

Kesimpulan

Map server merupakan aplikasi pemetaan GIS yang dioperasikan oleh sistem operasi seperti linux dan windows yang bersifat opensource yang berfungsi untuk menbaca data graphic.

Saran

Agar pembaca mencari referensi lain untuk menambah pengetahuan pembaca.

        NAMA        : INDAH MARINI RIZKY SIHOMBING

        NPM                : 1144041

        KELAS        : 3C

        PRODI        : D4 TEKNIK INFORMATIKA

        KAMPUS        : POLITEKNIK POS INDONESIA

LINK GITHUB

LINK REFERENSI

[https://www.nginx.com/resources/admin-guide/mail-proxy/](https://www.nginx.com/resources/admin-guide/mail-proxy/)

LINK PLAGIARISME