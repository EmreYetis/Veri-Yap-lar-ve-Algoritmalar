# Veri-Yapilari-ve-Algoritmalar
Proje ödevleri https://app.patika.dev/godey


Insertion Sort Projesi;

[22,27,16,2,18,6]
Insertion Sort Aşamaları;
16,22,27,2,18,6
2,16,22,27,18,6
2,16,18,22,27,6
[2,6,16,18,22,27]
Big-O gösterimi;
O(n)
Time Complexity;
18 sayısı Average Case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort’a göre ilk 4 adımı;
[3,7,5,8,2,9,4,15,6] 	 1. adım
[3,5,7,8,2,9,4,15,6]  	2. adım
[2,3,5,7,8,9,4,15,6]  	3. adım
[2,3,4,5,7,8,9,15,6]  	4. adım

Merge Sort Projesi;

[16,21,11,8,12,22] Dizinin Merge Sort türüne göre aşamaları;
[16,21,11]		[8,12,22]	n/2
[16]  [21,11]		[8,12]  [22]	n/4
[16 ] [21]  [11]		[8]  [12]  [22]	n/8
[16]  [11,21]		[8,12]  [22]	
[11,16,21]		[8,12,22]
	[8,11,12,16,21,22]

Big-O gösterimi;
(2^x = n)
O(Logn); 

Binary Search Tree Projesi;

Root = 7'dir 5: 7 den küçük olduğu için sol tarafa yazıyorum 1: 7 den küçük olduğu için 5 ten sonra gelir 8: 7 den büyük olduğu için sağ tarafa yazılır 3: 7 den küçük olduğu için 1 den sonra 6: 7 den küçük olduğu için sol tarafa yazılır. 0: 7 den küçük olduğu için sol tarafa 1 e dallandırdım 9: 7 den büyük olduğu için sağ tarafa yazılır. 4: 7 den küçük olduğu için sol tarafa yazılır. 2: 7 den küçük olduğu için sol tarafa yazılır

  	      [7]
             /   \
            [5]  [8]
         /  /  \    \
       [1] [3] [6]  [9]
      /  \  \          
    [0]  [2] [4] 

