# **Proje 2**
`[16,21,11,8,12,22]` -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

----- 

## **Çözüm**
`Merge Sort` bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyor. Böldükten sonra sıralı bir şekilde bize sunuyor. 

1.  Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    1. Adım => `[16,21,11] [8,12,22]`

    2. Adım => `[16,21,11]` = > `[16]` `[21,11]` | `[8,12,22]` => `[8]` `[12,22]`

    3. Adım => `[16]` |  `[21,11]` => `[21]` `[11]` || `[8]` | `[12,22]` => `[12]` `[22]`

    4. Adım => `[16]` `[21]` `[11]` `[8]` `[12]` `[22]`

    5. Adım => `[16]` |  `[11,21]` || `[8]` | `[12,22]`

    6. Adım => `[11,16,21]` || `[8,12,22]`

    7. Adım => `[8,11,12,16,21,22]`

2. Big-O gösterimini yazınız.
    - Big-O gösterimi => `O(nlogn)`