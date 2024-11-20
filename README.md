# Patika-Akademi-Veri-Analizine-Giri-

Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Çözüm 2 
[16,21,11,8,12,22]     Veriyi her seferinde sağ ve soldan ikiye bölerek kümelendiriyoruz, kümeler tek verili olana dek devam ediyoruz.
[16,21,11]  [8,12,22]
[16,21]   [11]   [8,12] [22] 
[16] [21]  [11] [8] [12] [22]   Tekli kümeleri en soldan en küçük sayı olacak şekilde önce ikişerli, sonra üçerli, sonra dörderli ... şekilde tüm sayılar bir dizi oluşturana dek tekrar tekrar kümeliyoruz.
[16,21] [8,11] [12,22]
[8,11,16,21] [12,22]
[8,11,12,16,21,22]

/*
