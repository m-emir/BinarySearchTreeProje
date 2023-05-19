# BinarySearchTreeProje

# Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Burada dizinin ilk elemanı olan 7 rakamını root (kök) olup

1)7 root
2)5 rakamı 7'den küçük sola,
3)1 rakamı 7-5'den küçük olduğundan 5'in soluna,
4)8 rakamı 7'den gbüyük olup 7'nin sağına,
5)3 rakamı 7-5-1'den büyük olup 1'in soluna,
6)6 rakamı 7-5'den büyük olup 5',n sağına,
7)0 rakamı 7-5-1'den küçük olup 1'in sağına,
8)9 rakamı 7-8'den büyük olup 8'in sağına,
9)4 rakamı 7-5-1-3'den büyük olup 3'ün sağına,
10)2 rakamı 7-5-1-3'den küçük olup 3'ün soluna yerleştirilir.

           7   
          / \
         /   \
        5     8   
       / \     \
      /   \     \
     1     6     9 
    / \   
   /   \ 
  0     3  
       / \
      2   4  
