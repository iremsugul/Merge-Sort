## Insertion Sort

[22,27,16,2,18,6] -> Insertion Sort

## Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

O ana kadarki sıralı kısma 'I' koyalım.

- İlk Geçişte: 22 I 27 16 2 18 6
- İkinci Geçişte: 22 27 I 16 2 18 6
- Üçüncü Geçişte: 22 27 I 16 2 18 6 -> 22 16 27 I 2 18 6 -> 16 22 27 I 2 18 6
- Dördüncü Geçişte: 16 22 27 I 2 18 6 -> 16 22 2 27 I 18 6 -> 16 2 22 27 I 18 6 -> 2 16 22 27 I 18 6
- Beşinci Geçişte: 2 16 22 27 I 18 6 -> 2 16 22 18 27 I 6 -> 2 16 18 22 27 I 6
- Altıncı Geçişte: 2 16 18 22 27 I 6 -> 2 16 18 22 6 27 I -> 2 16 18 6 22 27 I -> 2 16 6 18 22 27 I -> 2 6 16 18 22 27 I


## Big-O gösterimini yazınız.

O(n^2)


- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Best Case: O(n)
Average Case: O(n^2)
Worst Case: O(n^2)

18 sayısı Average Case kapsamına girecektir.


## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1- [7|,3,5,8,2,9,4,15,6]
2- [3,7|,5,8,2,9,4,15,6]
3- [3,5,7|,8,2,9,4,15,6]
4- [3,5,7,8|,2,9,4,15,6]



[patika.dev](https://www.patika.dev/tr)


