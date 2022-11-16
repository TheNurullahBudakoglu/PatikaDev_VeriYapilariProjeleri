# **PatikaDev_VeriYapilariProjeleri**
www.patika.dev sitesinde veri yapıları eğitimleri için verilmiş proje ödevidir.

# Selection Sort Projesi
### Soru 1-) [22,27,16,2,18,6] -> Insertion Sort
### Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

[22|,27,16,2,18,6]  &emsp;&emsp;sol taraf sıralı, çizgi sağa kaydırılır <br />
[22,27|,16,2,18,6]  &emsp;&emsp;sol taraf sıralı, çizgi sağa kaydırılır <br />
[22,27,16|,2,18,6]  &emsp;&emsp;16 27 yer değiştirir <br />
[22,16,27|,2,18,6]  &emsp;&emsp;22 16 yer değiştirir <br />
[16,22,27|,2,18,6]  &emsp;&emsp;sol taraf sıralı, çizgi sağa kaydırılır <br />
[16,22,27,2|,18,6]  &emsp;&emsp;2 27 yer değiştirir <br />
[16,22,2,27|,18,6]  &emsp;&emsp;2 22 yer değiştirir <br />
[16,2,22,27|,18,6]  &emsp;&emsp;2 16 yer değiştirir <br />
[2,16,22,27|,18,6]  &emsp;&emsp;sol taraf sıralı, çizgi sağa kaydırılır <br />
[2,16,22,27,18|,6]  &emsp;&emsp;18 27 yer değiştirir <br />
[2,16,22,18,27|,6]  &emsp;&emsp;18 22 yer değiştirir <br />
[2,16,18,22,27|,6]  &emsp;&emsp;sol taraf sıralı, çizgi sağa kaydırılır <br />
[2,16,18,22,27,6|]  &emsp;&emsp;6 27 yer değiştirir <br />
[2,16,18,22,6,27|]  &emsp;&emsp;6 22 yer değiştirir <br />
[2,16,18,6,22,27|]  &emsp;&emsp;6 18 yer değiştirir <br />
[2,16,6,18,22,27|]  &emsp;&emsp;6 16 yer değiştirir <br />
[2,6,16,18,22,27|]  &emsp;&emsp;sol taraf sıralı ve dizi sonu işlem tamamlanır <br />



### Soru 2-) Big-O gösterimini yazınız.

**Cevap : O(n^2)**

### Soru 3-) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız




- **Average case: Aradığımız sayının ortada olması**
- **Worst case: Aradığımız sayının sonda olması**
- **Best case: Aradığımız sayının dizinin en başında olması.**

Cevap: 18 sayısı ortada olan iki sayıdan biri olduğu için Average Case kapsarken,diğerlerini kapsamaz.

### Soru 4-) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[ [7,3,5,8,2,9,4,15,6] ] <br />
[ 2,[3,5,8,7,9,4,15,6] ] <br />
[ 2,3,[4,8,7,9,5,15,6] ] <br />
[ 2,3,4,[5,7,9,8,15,6] ]<br />
[ 2,3,4,5,[7,9,8,15,6] ]<br />

# Merge Sort Projesi

### Soru 1-) [16,21,11,8,12,22] -> Merge Sort
- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
[16,21,11,8,12,22] <br />
[16,21,11] &emsp;&emsp; [8,12,22] <br />
[16,21]&emsp;&emsp; [11]&emsp;&emsp; [8,12]&emsp;&emsp; [22] <br />
[11,16,21] &emsp;&emsp;[8,12,22] <br />
[8,11,12,16,21,22] <br />

- Big-O gösterimini yazınız. <br />
Cevap : O ( n log (n) ) <br />
# Binary Search Tree Projesi

### Soru 1-) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
### Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

![test](https://github.com/TheNurullahBudakoglu/PatikaDev_VeriYapilariProjeleri/blob/main/BinarySearchTree.png?raw=true)
