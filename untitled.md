# K-MEANS
Amac gozlemleri birbirlerine olan benzerliklerine gore kumelere ayirmaktir.
Kumeleme yontemlerinin amaci benzerlik matrislerini kullanarak,gozlemleri ya da degiskenleri kumelemeye calismaktir.
Olusturulmaya calisilan kumelrein kendi icinde homojen, birbirlerine gore heterojen olmas beklenir.

Adimlar;
-Kume sayisi belirlenir.
-Rastgele k merkez secilir.
-Her gozlem icin k merkezlere uzakliklar hesaplanir.
-Her gozlem en yakin oldugu merkeze yani kumeye atanir.
-Atama islemlerinden sonra olusan kumeler cin ekrar merkez hesabi yapilir.
-Bu islem belirlenen bir iterasyon adedince tekar edilir ve kume ici hata kareler toplamlarinin toplaminin minimum oldugu durumdaki gozlemlerin kumelenme yapisi nihai kumelenme olarak secilir.

Amac kume ici benzerlik maksimum, kumeler arasi benzemezlik de maksimum olmalidir.

# Hiyerarsik Kumeleme
Amac gozlemleri birbirlerine olan benzerliklerine gore alt kumelere ayirmaktir.
-Gozlemler daha fazla sayida alt kumeye ayrilmak isteniyorsa bu durumda hiyerarsik kumeleme yontemleri kullanilabilir.

KMeans yonteminde sadece belirli sayida kumeye ayrilibiyoruz.
Hiyerarsikte ise kume olusturup olusturulan kumeleri de kumelere ayirabiliriz.

# Temel Bilesen Analizi(PCA)
Temel fikir, cok degiskenli verinin ana ozellikleini daha az sayida degisken/bilesen ile temsil etmektir.

Diger ifade ile; kucuk miktarda bilgi kaybini goze alip degisken boyutunu azaltmak.