**PERTEMUAN 6**

**CREATE POINTS**

**LATAR BELAKANG MASALAH**

**       ** Data Vektor adalah suatu data yang mendeskripsikan bentuk bumi dengan detail dan tertata. Data vektor dapat digambarkan dengan point, polygon, polyline. Kali ini akan membahas tentang point.

**PEMBAHASAN**

        Point merukan bentuk dari suatu vektor yang digambarkan dengan bentuk titik. Titik atau point mewakili koordinat x dan y untuk menunjukkan suatu lokasi dengan detail.

        **Write Point**

        w = shapeType

        w.field (&#39;Kota&#39;,&#39;C&#39;,&#39;30&#39;)

        w.field (&#39;Medan&#39;,&#39;Rini&#39;)

        w.record (&#39;Medan&#39;,&#39;Rini&#39;)

        w.point(10,10,0,0)

w.save(&#39;kota.shp&#39;)

exit()

**Edit Point**

e = shapefile.Editor(shapefile=&quot;shapefile/test/point.shp&quot;)

e.point(0,0,10,2)

e.record(&quot;Appended&quot;,&quot;Point&quot;)

e.save(&quot;shapefile/test,point&quot;)

        **Delete Record**

        e.delete(1)

        **Read Point**

        sf = shape

        sf.records()

        sf.record(0)

        sf.record(1)

        sf.shapes()[0].point







**PENUTUP**

**       ** Kesimpulan:

Point merukan bentuk dari suatu vektor yang digambarkan dengan bentuk titik. Titik atau point mewakili koordinat x dan y untuk menunjukkan suatu lokasi dengan detail.

Saran:

Pembaca diharapkan mencari refenrensi lainnya tentang create point untuk menambah pengetahuan yang lebih mendalam tentang cara create point yang lebih spesifik



Nama         : Indah Marini Rizky Sihombing

NPM                : 1144041

Kelas                : 3C

Prodi                : D4 Teknik Informatika

Kampus        : Politeknik Pos Indonesia



Link github:

Link referensi:

[http://seeevil13.blogspot.co.id/2015/03/tutorial-dasar-arcgis-cara-membuat.html](http://seeevil13.blogspot.co.id/2015/03/tutorial-dasar-arcgis-cara-membuat.html)

Link plagiarisme:

[https://drive.google.com/open?id=0Bz4dM019IgweNzVrUGRyeDRLTzQ](https://drive.google.com/open?id=0Bz4dM019IgweNzVrUGRyeDRLTzQ)

[https://drive.google.com/open?id=0Bz4dM019IgweUk02Vnc5MjFfQU0](https://drive.google.com/open?id=0Bz4dM019IgweUk02Vnc5MjFfQU0)