# Selection Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- Big-O gösterimini yazınız.

- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.



# Çözüm
---
1. Dizinin en küçük elemanı bulunur. [2]
2. [2] ile [22] yer değiştirilir. Dizinin yeni hali [2,27,16,22,18,6] olmuştur. 
3. Sonra dizinin 2. en küçük elemanı bulunur ve 2. sıradaki eleman ile yer değiştirlir. [2,6,22,18,27].
4. Aynı işlemler dizinin 3. elemanı için tekrar edilir. [2,6,18,22,27].
5. Dizi sıralanması bu şekildedir. [2,6,18,22,27].

---
* Big-O gösterimi  O(n^2).

---
* 18 sayısı "Average case" kapsamına girer.

---
* [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]
5. [2,3,4,5,6,7,8,15,9]
6. [2,3,4,5,6,7,8,9,15]





