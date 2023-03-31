# Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.

# Çözüm
1. Dizi ortasından ayırılır. [16,21,11] ve [8,12,22]
2. Kümeler kendi içinde 2 ye bölünür. [16,21] [11] ve [8,12] [22] şeklinde.
3. Tüm kümeler en küçük parçaya bölünene kadar bu işlem devam eder. [16] [21] [11] [8] [12] [22].
4. Bölme işlemleri tamamlandı. Sıra birleştirme işlemlerinde.
5. İki elemanlı diziler oluşturulur ve küçük olan sağa büyük olan sola yazılır. [16,21][8,11][12,22].
6. Soldaki diziden başlayarak karşılaştırma işlemleri yapılır. [8,11,16,21] [12,22] Şeklinde birleştirme yapılır. 
7. İki dizi karşılaştırılıp tek bir dizi haline getirilir. [8,11,12,16,21,22] şeklinde sıralanır.


Big-O gösterimi ise O(n.logn) şeklindedir.
