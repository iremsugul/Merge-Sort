
# Merge Sort

[16,21,11,8,12,22] -> Merge Sort

## Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

- Öncelikle diziyi ikiye böleriz:

 [16,21,11] ------- [8,12,22]

- Diziler en fazla iki eleman olacak şekilde tekrar ikiye bölme işlemi yapılır:

 [16,21] ---- [11] -------- [8,12] ---- [22]

- Oluşan diziler kendi içerisinde sıralanır:

 [16,21] ---- [11] -------- [8,12] ---- [22]

- Diziler aşamalı olarak uygun bir şekilde birleştirilir:

 [11,16,21] ------- [8,12,22]
 
  [8,11,12,16,21,22]




## Big-O gösterimini yazınız.

O(n*logn)

[patika.dev](https://www.patika.dev/tr)


