# Binary-Search-Tree
www.patika.dev binary search tree projesi

##Proje 3

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Yukarıda ki dizinin root elemanı ortada bulunan 6 sayısı olsun. Dizinin başından başlayıp elemanların 6'dan küçük mü yoksa büyük mü olduğunu sormaya başlayalım.

7, 6'dan büyük olduğu için sağa yazılmalı.

    6
       \
          7
          
5, 6'dan küçük olduğu için sola yerleştiriyoruz.

          6
        /   \
       5     7
1, 6'dan küçük sola yerleştirilmeli. Ayrıca 5'ten de küçük olduğu için 5'in de soluna yazılacak.

          6
        /   \
       5     7
     /
    1
8, 6'dan ve 7'den büyük. Bu sebeple sağa yazılmalı.

          6
        /   \
       5     7
     /        \
    1          8
3, 6'dan ve 5'ten küçük fakat 1'den büyük. 1'in sağına yerleştirilmeli.

          6
        /   \
       5     7
     /        \
    1          8
      \
        3
        
0 elemanı dizide ki en küçük eleman. 6'dan 5'ten ve 1'den küçük olduğu için 1'in soluna yazılmalıdır.

          6
        /   \
       5     7
     /        \
    1          8
   /  \
  0     3
  
9 elemanı 6, 7 ve 8'den büyük. 8'in sağına yerleştirilmeli.

          6
        /   \
       5     7
     /        \
    1          8
   /  \         \
  0     3        9
4; 6'dan ve 5'ten küçük, 1'den ve 3'ten büyüktür. 3'ün sağına yazılmalıdır.

          6
        /   \
       5     7
     /        \
    1          8
   /  \         \
  0     3        9
         \
          4 
 2, 6 ve 5'ten küçük, 1'den büyük ve yine 3'ten küçüktür. 3'ün solunda yer almalıdır.

          6
        /   \
       5     7
     /        \
    1          8
   /  \         \
  0     3        9
       /  \
      2    4  
