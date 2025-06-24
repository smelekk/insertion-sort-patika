# insertion-sort-patika
# insertion-sort-patika
```
Proje 1
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
# Cevaplar 
```
1-)
­Insertion Sort algoritmasında en küçük olan en başa geliyor, en baştaki ile yer değiştiriyor.
1. Sıradan kontrol et, en küçük olanı bul, 
2. en küçük olan ile en baştakini değiştir,
3. son elamana gelene kadar yanındaki elaman ile devam et.
```
```
2-)
O(n^2)
```
```
3-)
Worst Case
Dizinin sıralanmış hali [2,3,4,5,6,7,8,9,15] olduğundan 18 sayısı dizinin en sonuna gelir.
```
# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1.adım:  [2*,3,5,8,7*,9,4,15,6]
2.adım:  [2,3*,5,8,7,9,4,15,6]
3.adım:  [2,3,4*,8,7,9,5*,15,6]
4.adım:  [2,3,4,5*,7,9,8*,15,6]
* En küçük olan baştaki ile yer değiştirdi.```

