# Insertion Sort Projesi
## Proje 1
### SORU : [22,27,16,2,18,6] -> Insertion Sort

---
-1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1. (2,27,16,22,18,6) birinci adım
2. (2,6,16,22,18,27) ikinci adım
3. (2,6,16,18,22,27) üçüncü adım ve son
---
-2. Big-O gösterimini yazınız.

     *O(n^2)
---
-3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

---
-4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

     (2,6,16,18,22,27) => 18 average case olur.
---

### SORU 2 : [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. (2,3,5,8,7,9,4,15,6) birinci adım
2. (2,3,4,8,7,9,5,15,6) ikinci adım
3. (2,3,4,5,7,9,8,15,6) üçüncü adım
4. (2,3,4,5,6,9,8,15,7) dördüncü adım
---
# Merge Sort Projesi
## Proje 2
### SORU : [16,21,11,8,12,22] -> Merge Sort

---
-1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
1.     [16,21,11,8,12,22] 
2.     [16,21,11]        [8,12,22] ikiye böldük
3.     [16,21] [11]      [8,12] [22] bölünen parçaları tekrar böldük
4.     [16] [21] [11]    [8] [12] [22] tekrar böldük ve her bir parça tek elemanlı oldu
5.     [16,21] [11]      [8,12] [22] küçük büyüklük kıyası yaparak birleştirdik
6.     [11,16,21]        [8,12,22] ikinci adımda ikiye bölünen elemanları kendi içerisinde sıraladık. 
7.     [8,11,12,16,21,22] altıncı adımda oluşan iki parçayı kıyaslayarak sıralamamızı tamamladık.
---

-2.Big-O gösterimini yazınız.

     O(n.logn)
---
# Binary Search Tree Projesi 
## Proje 3
### SORU : [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. (Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.)

---
1. Root 7'dir. Bu Köke göre ağacımızı oluşturmaya başlayabiliriz.
2.               7
                / \
               5   8
              / \   \
             1   6   9
            / \
           0   3
              / \
             2   4
---
