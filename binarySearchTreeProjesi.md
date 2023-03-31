# Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


# Çözüm
1. Root 7.
2. Root en başa yazıp roottan büyük olanları sağına, küçük olanları soluna yazarak ağaç yapısını oluşturuyoruz. 

```
                        7
                     /     \
                   5         8
                  / \         \
                 1   6          9     
               /   \           
             0      3 
                  /   \
                 2     4

```
