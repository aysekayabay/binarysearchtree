# binarysearchtree
Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb. //solda daha küçük sağda daha büyük eleman bulunur.
7>5 root 7'dir. rootun solunda ondan küçük 5 elemanı bulunur.
  7
 /
5

+1

    7
   /
  5
 /
1

+8

    7
   / \
  5   8
 /
1

+3
    7
   / \
  5   8
 /
1
 \
  3
  
+6
    7
   / \
  5   8
 / \
1   6
 \
  3

+0

      7
     / \
    5   8
   / \
  1   6
 / \
0   3

+9

      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3

+4

      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
      
+2

      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
