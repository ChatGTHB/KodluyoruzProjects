# Veri Yapıları ve Algoritmalar

## Proje 1

## Insertion/Selection Sort Projesi

**[22,27,16,2,18,6]** -> Insertion Sort

```
1.  [16, 22, 27, 2, 18, 6]  

2.  [2, 16, 22, 27, 18, 6]

3.  [2, 16, 18, 22, 27, 6] 

4.  [2, 6, 16, 18, 22, 27] -> Final
```

**Big-O Gösterimi**

```
O(n^2)
```

**Time complexity**

```
Average case: Aradığımız sayının ortada olması
```

**[7,3,5,8,2,9,4,15,6]** -> Selection Sort

```
1.  [2, 3, 5, 8, 7, 9, 4, 15, 6] 

2.  [2, 3, 5, 8, 7, 9, 4, 15, 6]

3.  [2, 3, 4, 8, 7, 9, 5, 15, 6]

4.  [2, 3, 4, 5, 7, 9, 8, 15, 6] 
```

---------

## Proje 2

## Merge Sort Projesi

**[16,21,11,8,12,22]** -> Merge Sort

```
1.  [16, 21, 11] [8, 12, 22]  

2.  [16] [21, 11] [8, 12] [22]

3.  [16] [21] [11] [8] [12] [22]

4.  [16] [11, 21] [8, 12] [22] 

5.  [11, 16, 21] [8, 12, 22]

6.  [8, 11, 12, 16, 21, 22] -> Final
```

**Big-O Gösterimi**

```
O(nlogn)
```

---

## Proje 3

## Binary-Search-Tree Projesi

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** ->  Binary-Search-Tree Aşamaları

* İlk olarak 7 rakamı **Kök Boğum(Root Node)** olarak alınır.
* 5, 1, 8, 3, 6, 0, 9, 4 ve 2 sırasıyla **Kök Boğum(Root Node)** olarak kabul ettiğimiz 7 ile karşılaştırılır. 7'den
  küçük olan rakamlar 7'nin solunda, büyük olan rakamlar ise sağında yer alacak şekilde aşamalar şekillenir. Buna göre :

1. İlk adım olarak; 5, 7'den küçük olduğundan 7'nin soluna alınır.
2. Sonraki rakam olan 1, 7'den küçük olduğundan 7'nin soluna alınır. Solda daha önce 5 bulunduğundan ve 1, 5'ten de
   küçük olduğundan 5'in de soluna alınır.
3. 8, 7'den büyük olduğundan 7'nin sağına alınır.
4. 3, 7'den küçük olduğundan 7'nin soluna ve önceki rakamlardan 1'den büyük olduğundan 1'in sağına alınır.
5. 6, 7'den küçük olduğundan 7'nin soluna ve önceki rakamlardan 5'ten büyük olduğundan 5'in sağına alınır.
6. 0, 7'den ve önceki rakamlardan olan 5 ve 1'den küçük olduğundan 7'nin ve devamında 1'in soluna alınır.
7. 9, 7'den ve önceki rakamlardan olan 8'den büyük olduğundan 7'nin ve devamında 8'in sağına alınır.
8. 4, 7'den küçük olduğundan 7'nin soluna ve önceki rakamlardan olan 3'ün sağına alınır.
9. 2, 7'den küçük olduğundan 7'nin soluna ve önceki rakamlardan olan 3'ün soluna alınır..

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** ->  Binary-Search-Tree Aşamaları

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






 