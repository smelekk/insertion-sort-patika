# Proje2
```
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

```
# cevap

```
Böl ve fethet yaklaşımıdır.
Diziyi sürekli ortadan ikiye böler
Daha sonra sıralayarak birleştirir
Rekürsif çalışır
```
```
[16, 21, 11, 8, 12, 22]
→ [16, 21, 11]     [8, 12, 22]
→ [16] [21, 11]    [8] [12, 22]
→ [16] [21] [11]   [8] [12] [22]

→ [16] [11, 21]    [8, 12, 22]
→ [11, 16, 21]     [8, 12, 22]
→ [8, 11, 12, 16, 21, 22]

```
# Big-O gösterimi
```
Merge sort her zaman nlogn performans gösterir -> O(nlogn)
```
