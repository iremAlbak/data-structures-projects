# Selection/İnsertion Sort
**Soru 1)**
```
[22,27,16,2,18,6]
```
**a)** Yukarı verilen dizinin insertion sort türüne göre aşamalarını yazınız.
 ```
[22, 27, 16, 2, 18, 6] (Başlangıç)
[22, 27, 16, 2, 18, 6] (22 sabit, geri kalanı sıralanacak)
[16, 22, 27, 2, 18, 6] (16, 22'den küçük olduğu için yer değiştirme)
[2, 16, 22, 27, 18, 6] (2, 16'dan küçük olduğu için yer değiştirme)
[2, 16, 18, 22, 27, 6] (18, 22'den küçük olduğu için yer değiştirme)
[2, 6, 16, 18, 22, 27] (Son hali, dizi sıralanmıştır)
 ```

**b)** Big-O gösterimini yazınız.
```
Big-O gösterimi: O(n^2)
```

**c)** Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
```
1. Average Case: Aranan sayının ortada olması
2. Worst Case: Aranan sayının sonda olması
3. Best Case: Aranan sayının dizinin en başında olması
```
```
Answer c)
    Average Case
```

**Soru 2)**
```
[7,3,5,8,2,9,4,15,6]
```
dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
``` 
[2,3,5,8,7,9,4,15,6] (Başlangıç, en küçük elemanı bulup ilk sıraya yerleştiririz)
[2,3,5,8,7,9,4,15,6] (3, en küçük ikinci eleman olduğu için değişiklik yapmayız)
[2,3,4,8,7,9,5,15,6] (4, en küçük üçüncü eleman olduğu için ikinci sıraya yerleştirilir)
[2,3,4,5,7,9,8,15,6] (5, en küçük dördüncü eleman olduğu için üçüncü sıraya yerleştirilir)
```
# Merge Sort

**Soru 1)** 
```
[16,21,11,8,12,22]
```
**a)** Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
```
Answer a) 
[16,21,11,8,12,22] (Başlangıç)
[16,21,11], [8,12,22] (Dizi ikiye bölündü)
[16,21], [11], [8,12], [22] (Her alt dizi ikiye bölündü)
[16], [21], [11], [8], [12], [22] (Tek elemanlı alt diziler sıralandı)
[16,21], [8,11], [12,22] (Birleştirme aşaması)
[8,11,16,21], [12,22] (Birleştirme aşaması)
[8,11,12,16,21,22] (Sonuç)
```

**b)** Big-O gösterimini yazınız.

```
Answer b)
    O(nlogn)
```
# Binary Search Tree
```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
```
**a)** Yukarıda verilen dizinin Binary-Search-Tree aşamalarını yazınız.

```
Answer a)
           7
          / \
         5   8
        / \   \
       1   6   9
      / \     /
     0   3   9
        / \
       2   4

```
