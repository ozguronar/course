# Merge Sort
## Proje 2

> [16,21,11,8,12,22] -> Merge sort

1. Dizi öncelikle ikiye ayrılır

[16,21,11] -- [8,12,22]

2. Oluşan üçlü diziler tekrar yarılanır.

[16] -- [21,11] <--> [8] -- [12,22]

3. Tekrar bölme işlemi yapılır ve elemanların tek kalması sağlanır.

[16] -- [21] -- [11] <--> [8] -- [12] -- [22]

4. Elemanların birleştirme işlemi başlatılır.

[16] -- [11,21] <--> [8] -- [12,22]

5. Tekrar birleştirme ve sıralama yapılır.

[11,16,21] <--> [8,12,22]

6. Diziler sıralanarak birleştirilir.

[8,11,12,16,21,22]

***
> Big O gösterimi

O (n.logn)
