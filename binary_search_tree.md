# Binary Search Tree Adımları

Verilen dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

1. İlk eleman olan 7, root olarak eklenir.
7

2. 5, 7'den küçük olduğu için root'un soluna eklenir.

 7
/
5

3. 1, 7'den ve 5'ten küçük olduğu için 5'in soluna eklenir.

 7
/
5
/
1

4. 8, 7'den büyük olduğu için root'un sağına eklenir.

 7
/ \
5 8
/
1

5. 3, 7'den ve 5'ten küçük, 1'den büyük olduğu için 1'in sağına eklenir.

 7
/ \
5 8
/
1
\
3

6. 6, 7'den küçük ve 5'ten büyük olduğu için 5'in sağına eklenir.

 7
/ \
5 8
/\
1 6
\
3

7. 0, 7'den 5'ten 1'den küçük olduğu için 1'in soluna eklenir.

 7
/ \
5 8
/\
1 6
/\
0 3

8. 9, 7'den ve 8'den büyük olduğu için 8'in sağına eklenir.

 7
/ \
5 8
/\  \
1 6  9
/\
0 3

9. 4, 7'den ve 5'ten küçük, 1'den ve 3'ten büyük olduğu için 3'ün sağına eklenir.

 7
/ \
5 8
/\  \
1 6  9
/\
0 3
  \
  4

10. Son olarak 2, 7'den ve 5'ten küçük, 1'den büyük ve 3'ten küçük olduğu için 3'ün soluna eklenir.

  7
 / \
5   8
/ \   \
1   6   9
/\
0 3
  /\
  2 4