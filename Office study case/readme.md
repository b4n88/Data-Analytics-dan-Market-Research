<h1 align ='center'>Analisa kebutuhan ATK kantor</h1>

Untuk gudang yang kecil, analisa kebutuhan ATK sangat diperlukan. Agar barang yang jarang digunakan tidak menumpuk dan menjadi beban. Barang yang sangat cepat habis, harus diutamakan dan bisa dilakukan negosiasi harga karena beli lebih cepat.

lantas? Bagaimana mengetahui barang yang sering digunakan dan tidak? 
Case ini dapat kita selesaikan dengan Clustering.

Cluster sendiri dibagi menjadi 4, untuk memudahkan mengingatnya kita namakan dengan **"Kuadran"** :
Parameternya adalah Murah & High Consume

- **Kuadran 1** adalan barang yang cepat habis, Harga Mahal
- **Kuadran 2** adalah barang yang cepat habis, harga murah
- **Kuadran 3** adalah barang yang lama habis, harga murah
- **Kuadran 4** adalah barang yang lama habis, harga mahal

Dengan bantuan fingsi excel sederhana : *=IF(AND(D2="HIGH",E2="HIGH"),"KUADRAN  1",IF(AND(D2="HIGH",E2="LOW"),"KUADRAN 2",IF(AND(D2="LOW",E2="LOW"),"KUADRAN  3","KUADRAN 4")))*
Dan menggunakan data median, kita bisa melakukan pengendalian barang.

Kuadran 1 & 2 prioritaskan, karena barang cepat habis, dengan mengetahui ini kita bisa membuat penawaran harga karena belanja dengan jumlah banyak.

hahahah Xie xie
