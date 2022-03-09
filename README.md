# PatikaDevVeriYapilariVeAlgoritmaProjesi
Başlangıç Seviyesi .Net Core Patikası - Veri Yapıları ve Algoritmalar

<H3>Insertion Sort Projesi</H3>


[22,27,16,2,18,6] -> Insertion Sort
1.	Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6]
[2,22,27,16,18,6]
[2,6,22,27,16,18]
[2,6,16,22,27,18]
[2,6,16,18,22,27]
2.	Big-O gösterimini yazınız.
O (n2)
3.	Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.	Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Average case
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[2,7,3,5,8,9,4,15,6]
[2,3,7,5,8,9,4,15,6]
[2,3,4,7,5,8,9,15,6]
[2,3,4,5,7,8,9,15,6]

<H3>Merge Sort Projesi</H3>
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Başlangıç:[16,21,11,8,12,22]

Adım 1:[16,21,11]-[8,12,22]

Adım 2:[16,21]-[11]-[8,12,22]

Adım 3:[16]-[21]-[11]-[8,12,22]

Adım 4:[16,21]-[11]-[8,12,22]

Adım 5:[11,16,21]-[8,12,22]

Adım 6:[11,16,21]-[8,12]-[22]

Adım 7:[11,16,21]-[8]-[12]-[22]

Adım 8:[11,16,21]-[8,12]-[22]

Adım 9:[11,16,21]-[8,12,22]

Adım 10:[8,11,12,16,21,22]

Son:[8,11,12,16,21,22]

Big-O: O(nlogn)


<H3>Binary Search Tree Projesi</H3>

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
root = 7

              7
             / \
            5   8
           / \   \  
          1   6   9
         / \   
        0   3 
           / \
          2   4      
