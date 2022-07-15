# Binary Search Tree

- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1- Root: 7 

                        7


2- 5 < 7

                        7

                      /

                     5


3- 1 < 5 , 1 < 7
         
                        7

                      /

                     5

                   /

                  1


4- 8 > 7

 
                        7

                      /   \

                     5     8

                   /

                  1  


5- 3 > 1 , 3 < 5, 3 < 7

                        7

                      /   \

                     5     8

                   /

                  1  
       
                   \
 
                    3 


6- 6 < 7, 6 > 5

                        7

                      /   \

                     5     8

                   /   \

                  1     6
       
                   \
 
                    3 


7- - 0 hepsinden küçüktür


                        7

                      /   \

                     5     8

                   /

                  1  
       
                /   \
 
               0     3 



8- 9 > 7, 9 > 8

                       7

                      /   \

                     5     8

                   /         \

                  1           9
       
                /   \
 
               0     3 


9- 4 < 5 , 4 < 7, 4 > 1, 4 > 3

  

                        7

                      /   \

                     5     8

                   /

                  1  
       
                /   \
 
               0     3 
                 
                       \
      
                        4

10- 2 < 7, 2 < 5, 2 < 3, 2 > 1


                        7

                      /   \

                     5     8

                   /

                  1  
       
                /   \
 
               0     3 
                 
                   /    \
      
                  2      4


[patika.dev](https://www.patika.dev/tr)








                 



