# Sıralama Algoritmaları

## Insertion Sort:

Verilen diziyi Insertion Sort algoritması kullanarak sıralamak için aşağıdaki adımları izleriz:

1. [22, 27, 16, 2, 18, 6]
2. [22, 27, 16, 2, 18, 6] -> [22, 27, 16, 2, 18, 6] (22 ve 27 zaten sıralı)
3. [16, 22, 27, 2, 18, 6] -> [16, 22, 27, 2, 18, 6] (16 ve 27 zaten sıralı)
4. [2, 16, 22, 27, 18, 6]
5. [2, 16, 18, 22, 27, 6]
6. [2, 6, 16, 18, 22, 27]

Time Complexity: O(n^2)

18 sayısı:
- Average case: O(n^2)
- Worst case: O(n^2)
- Best case: O(n)

## Selection Sort:

Verilen diziyi Selection Sort algoritması kullanarak sıralamak için aşağıdaki adımları izleriz:

1. [7, 3, 5, 8, 2, 9, 4, 15, 6]
2. [2, 3, 5, 8, 7, 9, 4, 15, 6]
3. [2, 3, 4, 8, 7, 9, 5, 15, 6]
4. [2, 3, 4, 5, 7, 9, 8, 15, 6]

Time Complexity: O(n^2)
