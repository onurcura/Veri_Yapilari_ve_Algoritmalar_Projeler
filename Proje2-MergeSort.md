# Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort
* 1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* 2.Big-O gösterimini yazınız.
---
## 1. Merge Sort Türüne Göre Aşamalar
### 1. Aşama
* [16,21,11,8,12,22] dizini ortadan 2 parçaya bölünür.

`[16,21,11]   [,8,12,22]`
### 2. Aşama
* [16,21,11], [8,12,22] dizinleri tekrar 2 şer parçaya bölünür.

`[16]  [21,11]   [8,12]   [22]`
### 3. Aşama
* Tek elemanlı kalan parçalar aynı kalır. [21,11] [8,12] dizinleri 2 parçaya bölünür.

`[16]  [21]   [11]   [8]   [12]   [22]`
### 4. Aşama
* Oluşan indexler birleştirilmeye başlanır.
* Birleştirilirken yine gruplar halinde, fakat bu sefer kıyaslamalar yapılarak birleştirilir.
* 11<21, 8<12

`[16]  [11,21]   [8,12]   [22]`
### 5. Aşama
* Soldaki üçlü grupta [16]  , [11,21] ile kıyaslanır. 16>11, 16<21
* Sağdaki üçlü grupta [8,12] , [22] ile kıyaslanır. 8<22 , 12<22
* Gruplar şu şekilde oluşur:

`[11,16,21][8,12,22]`
### 6. Aşama
* Bu aşamada üçlü gruplar dizilerin en soldaki elemanlarından başlanarak kıyaslanır.
* 11 ile 8 kıyaslanır. 11>8 olduğu için 8 en başa geçer.
* 11 ile 12 kıyaslanır. 11<12 olduğu için 8'den sonra 11 gelir.
* 16 ile 12 kıyaslanır. 16>12 olduğu için 11'den sonra 12 gelir.
* 16 ile 22 kıyaslanır. 16<22 olduğu için 12'den sonra 16 gelir.
* 21 ile 22 kıyaslanır. 21<22 olduğu için 22 son elemandır, 16'dan sonra da 21 gelir.
* İşlem tamamlanmıştır ve sonuç olarak şu dizin elde edilir:

`[8,11,12,16,21,22]`
## 2. Big-O Gösterimini Yazınız

 `O(n.logn)`

---
[Patika.Dev](https://www.patika.dev/tr)
