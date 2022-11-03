# Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 
---

## 1. Verilen dizinin insertion sort türüne göre aşamaları

### 1. Aşama 
* Dizinin ilk elemanı sağındaki ikinci elemanla kıyaslanır. 22<27 olduğu için sıralama aynı kalır. 

` [22,27,16,2,18,6] `

### 2. Aşama
* İkinci eleman ve üçüncü eleman kıyaslanır. 27<16 olduğu için 16 ile 27 yer değiştirir. 
* Daha sonrasında 16 ile ilk eleman kıyaslanır, 16<22 olduğu için bu iki eleman da yer değiştirir. ++++++++++++++++++++++++++++++++

 `[16,22,27,2,18,6]` 
 

### 3. Aşama 
* Üçüncü eleman ile dördüncü eleman kıyaslanır. 27>2 olduğu için elemanlar yer değiştirir.
* Daha sonra 2, ikinci eleman olan 22 ile kıyaslanır. 2<22 olduğu için yer değiştirirler.
* Daha sonra 2, ilk eleman olan 16 ile kıyaslanır. 2<16 olduğu için yer değiştirirler. 

 `[2,16,22,27,18,6]`

### 4. Aşama
* Dördüncü eleman ile beşinci eleman kıyaslanır. 27>18 olduğu için elemanlar yer değiştirir.
* 18, üçüncü eleman ile kıyaslanır. 18<22 olduğu için elemanlar yer değiştirir.
* 18, ikinci eleman ile kıyaslanır. Halihazırda 16<18 olduğu için yer değiştirmezler.

`[2,16,18,22,27,6]`

### 5. Aşama
* Beşinci eleman ile altıncı eleman kıyaslanır. 27>6 olduğu için elemanlar yer değiştirir.
* 6, dördüncü eleman ile kıyaslanır. 6<22 olduğu için elemanlar yer değiştirir.
* 6, üçüncü eleman ile kıyaslanır. 6<18 olduğu için elemanlar yer değiştirir.
* 6, ikinci eleman ile kıyaslanır. 6<16 olduğu için elemanlar yer değiştirir.
* 6, birinci eleman ile kıyaslanır. 6>2 olduğu için elemanlar yer değiştirmez.

`[2,6,16,18,22,27]`

---
## 2. Big-O gösterimi
`Worst Case: O(n^2)`

`Avarage Case: O(n^2)`

`Best Case: O(n)`

---
## 3. Time Complexity

`Worst Case: [27,22,18,16,6,2]`

`Avarage Case: [6,16,22,2,18,27]`

`Best Case: [2,6,16,18,22,27]`

---
## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
* Sıralamanın ortasında bulunduğu için Average Case kapsamına girer.

---
## 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
1. [3,7,5,8,2,9,4,15,6]
2. [3,5,7,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]
4. [2,3,5,7,8,9,4,15,6]
```
---

* [Patika.dev](www.patika.dev)