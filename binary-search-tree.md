# Proje 3

```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
```
# Cevap

```
Solda roottan küçük sağda büyük değerler olur.
Yerleştirme:
1. Root: 7  
2. 5 → 7’nin soluna  
3. 1 → 5’in soluna  
4. 8 → 7’nin sağına  
5. 3 → 1’in sağına  
6. 6 → 5’in sağına  
7. 0 → 1’in soluna  
8. 9 → 8’in sağına  
9. 4 → 3’ün sağına  
10. 2 → 3’ün soluna
Ağaç:
Root: 7  
7’nin solunda 5, sağında 8 var.  
5’in solunda 1, sağında 6 var.  
1’in solunda 0, sağında 3 var.  
3’ün solunda 2, sağında 4 var.  
8’in sağında 9 var.
```
