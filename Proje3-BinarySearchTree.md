# Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

---
## Binary Search Tree Aşamalar
* [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinde root 7'dir ve dizideki elemanlar sırasıyla roottan kıyaslanmaya başlayarak kıyaslandığı elemandan büyükse sağına küçükse soluna yazılarak devam eder.
* İkini eleman olan 5 ile 7 kıyaslanır. 5<7 olduğu için 7'nin soluna yazılır.
```
                   7
                  /
                 5
```
* 1 ile 7 kıyaslanır. 1<7 olduğu için soldan devam eder.
* 1 ile 5 kıyaslanır. 1<5 olduğu için soldan devam eder.
 ```
                   7
                  /
                 5
                /
               1  
```
* 8 ile 7 kıyaslanır. 8>7 olduğu için sağa yazılır.
 ```
                   7
                  / \
                 5   8
                /
               1  
```
* 3 ile 7 kıyaslanır. 3<7 olduğu için sol tarafa ilerlenir.
* 3 ile 5 kıyaslanır. 3<5 olduğu için sol tarafa ilerlenir.
* 3 ile 1 kıyaslanır. 3>1 olduğu için sağ tarafa ilerlenir.
```
                   7
                  / \
                 5   8
                /
               1 
                \
                 3 
```
* 6 ile 7 kıyaslanır. 6<7 olduğu için sol tarafa ilerlenir.
* 6 ile 5 kıyaslanır. 6>5 olduğu için sağ tarafa ilerlenir.
```
                   7
                  / \
                 5   8
                / \
               1   6
                \
                 3 
```
* 0 ile 7 kıyaslanır. 0<7 olduğu için sol tarafa ilerlenir.
* 0 ile 5 kıyaslanır. 0<5 olduğu için sol tarafa ilerlenir.
* 0 ile 1 kıyaslanır. 0<1 olduğu için sol tarafa ilerlenir.
```
                   7
                  / \
                 5   8
                / \
               1   6
              / \
             0   3 
```
* 9 ile 7 kıyaslanır. 9>7 olduğu için sağ tarafa ilerlenir.
* 9 ile 8 kıyaslanır. 9>8 olduğu için sağ tarafa ilerlenir.
```
                   7
                  / \
                 5   8
                / \   \
               1   6   9
              / \
             0   3 
```
* 4 ile 7 kıyaslanır. 4<7 olduğu için sol tarafa ilerlenir.
* 4 ile 5 kıyaslanır. 4<5 olduğu için sol tarafa ilerlenir.
* 4 ile 1 kıyaslanır. 4>1 olduğu için sağ tarafa ilerlenir.
* 4 ile 3 kıyaslanır. 4>3 olduğu için sağ tarafa ilerlenir.
```
                   7
                  / \
                 5   8
                / \   \
               1   6   9
              / \
             0   3
                  \
                   4  
```
* 2 ile 7 kıyaslanır. 2<7 olduğu için sol tarafa ilerlenir.
* 2 ile 5 kıyaslanır. 2<5 olduğu için sol tarafa ilerlenir.
* 2 ile 1 kıyaslanır. 2>1 olduğu için sağ tarafa ilerlenir.
* 2 ile 3 kıyaslanır. 2<3 olduğu için sol tarafa ilerlenir.
* Son işlemden sonra ortaya çıkan Binary Search Tree aşşağıdaki gibidir.
```
                   7
                  / \
                 5   8
                / \   \
               1   6   9
              / \
             0   3
                / \
               2   4  
```
---
[Patika.Dev](https://www.patika.dev/tr)


            


