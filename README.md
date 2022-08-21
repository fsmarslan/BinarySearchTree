# Binary Search Tree

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları

Root=7
5 7'den küçük olduğu için soluna yazılır.
             7
        5        
1 7 ve 5'den küçük olduğu için soluna yazılır.
             7
        5
    1
8 7'den büyük olduğu için sağa yazılır.
             7
        5        8
    1
3 7 ve 5'den küçük 1'den büyük olduğu için 1'in sağına yazılır
             7
        5        8
    1
        3
6 7'den küçük 5'den büyük olduğu için 5'in sağına yazılır.
             7
        5        8
    1       6
        3
0 7,5 ve 1'den küçük olduğu için sola yazılır.
             7
        5        8
    1       6
0       3
9 7 ve 8'den büyük olduğu için sağa yazılır.
             7
        5        8
    1       6        9
0       3
4 7 ve 5'den küçük, 1 ve 3'den büyük olduğu için sağa yazılır.
             7
        5        8
    1       6        9
0       3
            4
2 7 ve 5'den küçük, 1'den büyük, 3'den küçük olduğu için sola yazılır.
             7
        5        8
    1       6        9
0       3
    2       4