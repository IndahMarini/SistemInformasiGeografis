PERTEMUAN 4

RETRIVE DATA GEOSPASIAL


1 .Latar Belakang

        Dalam mempelajari tentang data geospasial tentunya kita akan menemukan yang dinamakan dengan titik koordinat dimana kita mempelajari tentang bentuk bumi. Tentu saja dimana ada data pasti ada yang dinamakan dengan manipulasi data baik itu dalam bentuk data itu sendiri atu record-record didalamnya seperti file shp dan dbf.

2. Pembahasan

Retrive data geospasial merupakan suatu langkah maupun trik yang dilakukan untuk melihat data maupun record file shp dan dbf.

SHP merupakan file yang menyimpan suatu data geometri didalam shapefile. Beberapa data yang terdapat didalam shp:

1. BBOX atau yang disebut juga _Boundary Box_ yang merupakan batas suatu koordinat pada suatu peta
2. POINT merupakan bentuk titik titik yang membentuk suatu koordinat
3. SHAPETYPE merupakan bentuk dari suatu nomor yang sudah memenuhi standar dari data geometri yaitu 1 adalah poin, 2 adalah polygon, 3 adalah polyline.

DBF merupakan suatu file yang bertugas menyimpan file yang didalamnya terdapat data atribut.

- Cara membaca jumlah data geometri menggunakan pyhton:

&gt;&gt; import shapefile

&gt;&gt; sf = shapefile.Reader(&quot;namafile.shp&quot;)

&gt;&gt; sf.shapes()

&gt;&gt; a = sf.shapes()

&gt;&gt; len(a)

- Cara membaca data DBF

&gt;&gt; import shapefile

&gt;&gt; sf.records()

&gt;&gt; sf.records(n)

3.Penutup

Kesimpulan:

Retrive data geospasial merupakan suatu langkah maupun trik yang dilakukan untuk melihat data maupun record file shp dan dbf

Saran:

Sebaiknya mencari bebeapa referensi tentang retrive data geospasial untuk menambah ilmu anda

Nama        : Indah Marini Rizky Sihombing

NPM        : 1144041

Prodi        : D4 Teknik Informatika

Kelas`        : 3C

Politeknik Pos Indonesia

Link github:

Link referensi: [http://www.cifor.org/publications/pdf\_files/Books/SIGeografis/SIG-part-2.pdf](http://www.cifor.org/publications/pdf_files/Books/SIGeografis/SIG-part-2.pdf)

Link plagiarisme:

1. [https://drive.google.com/open?id=0Bz4dM019IgweWm55dkxlV3NFTU0](https://drive.google.com/open?id=0Bz4dM019IgweWm55dkxlV3NFTU0)
2. [https://drive.google.com/open?id=0Bz4dM019IgweRXV0YlBOcTUzUW8](https://drive.google.com/open?id=0Bz4dM019IgweRXV0YlBOcTUzUW8)