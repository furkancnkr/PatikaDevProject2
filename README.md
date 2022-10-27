# PatikaDev_Proje2
Merge Sort

[16,21,11,8,12,22]

# 1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2- Big-O gösterimini yazınız.

# 1- Merge Sort Aşamaları: # 

- Başlangıçta dizimizi ikiye bölüp, bölünen diziler tekrar bölünüyor. Tek eleman kalana kadar İşlem devam ediyor.

- Bölme işlemi bitikten sonra, tek elemanlı diziler ikili ikili birleştirilir. Sıralı dizi elde edinceye kadar bu işlem devam ediyor.

1.adım: [16,21,11,8,12,22]

2.adım: [16,21,11] - [8,12,22]

3.adım: [16] - [21,11] - [8,12] - [22]

4.adım: [16] - [21] - [11] - [8] - [12] - [22]

5.adım: [16] - [11,21] - [8,12] - [22]

6.adım: [11,16,21] - [8,12,22]

7.adım: [8,11,12,16,21,22]

# 2. Big-O gösterimini yazınız. #

Recursive bir fonksiyon olduğu için sürekli kendini çağırarak diziyi hep ikiye bölmektedir. Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından

Big-O gösterimi   O(n*(logn)) --> O(6*(log6))   olacaktır.

www.patika.dev
