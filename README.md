# Veri Yapilari ve Algoritmalar Kodluyoruz Patika.dev   

Bu repo [Kodluyoruz](Kodluyoruz.org) Veri Yapıları ve Algoritmalar eğitimi için hazırlamış olduğum repo. İçerisinde Veri Yapıları ve Algoritmalar projelerinin soru ve cevaplarını içeren bir adet README dosyası barındırıyor.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

| PROJELER |
|-----|
| [PROJE 1](https://github.com/Ramedeus/Veri_Yapilari_ve_Algoritmalar_Kodluyoruz_Patika.dev/blob/main/README.md#open_book-prorje-1--insertion-sort) - Insertion Sort |
| [PROJE 2](https://github.com/Ramedeus/Veri_Yapilari_ve_Algoritmalar_Kodluyoruz_Patika.dev/blob/main/README.md#open_book-prorje-2--merge-sort) - Merge Sort|
| [PROJE 3](https://github.com/Ramedeus/Veri_Yapilari_ve_Algoritmalar_Kodluyoruz_Patika.dev/blob/main/README.md#open_book-prorje-3--binary-search-tree) - Binary Search Tree|

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## :open_book: PRORJE 1	- Insertion Sort

### SORU :question:
**[22,27,16,2,18,6]** -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.   
- Big-O gösterimini yazınız.   
- Time Complexity: 
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.   
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

:interrobang: **[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

### :green_square: CEVAP

<details>
<summary>Kodu görmek için tıklayınız.</summary>
  
```java
- [22,27,16,2,18,6] -> Insertion Sort 

n1. [22,27,16,2,18,6]
n2. [2,27,16,22,18,6] 
n3. [2,6,16,22,18,27] 
n4. [2,6,16,18,22,27] 

- Big-O gösterimini yazınız.
 O(n²)
  
 - Time Complexity: 
 Avarage case: 16,18
 Worth case: 27
 Best case: 2
  
 - Average Case: 18 
  
 - [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 
 n1. [7,3,5,8,2,9,4,15,6] 
 n2. [2,3,5,8,7,9,4,15,6] 
 n3. [2,3,4,8,7,9,5,15,6] 
 n4. [2,3,4,5,7,9,8,15,6] 
```
</details>

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



## :open_book: PRORJE 2	- Merge Sort

### SORU :question:
**[16,21,11,8,12,22]** -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.  
- Big-O gösterimini yazınız.   

### :green_square: CEVAP

<details>
<summary>Kodu görmek için tıklayınız.</summary>
  
```java
    [16,21,11,8,12,22]
      |             |
 [16,21,11]      [8,12,22]
      |             |  
[16][21,11]      [8,12][22]
      |             |  
[16][21][11]     [8][12][22]   
      |             |  
[16] [11,21]     [8,12] [22]
      |             |  
 [11,16,21]      [8,12,22]
      |             |  
    [8,11,12,16,21,22]
     
    

Big-O gösterimi
n = 2^x
logn = x
O(nlogn) 
```
</details>

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



## :open_book: PRORJE 3	- Binary Search Tree

### SORU :question:
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

**Örnek**: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.  

### :green_square: CEVAP

<details>
<summary>Kodu görmek için tıklayınız.</summary>
  
```java
[0,1,2,3,4,5,6,7,8,9]
root değeri = 4 

                  4
                  |
    -----------------------------
    |                           |  
    2                           7
---------                   ---------
|       |                   |       |
1       3                   6       8
|                           |       |
0                           5       9
      

" 7 root değerinden büyüktür sağında yer alır "
" 2 root değerinden küçüktür solunda yer alır "
```
</details>

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
