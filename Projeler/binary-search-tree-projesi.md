# Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

---

## Çözüm
1. İlk eleman olan 7 yi root olarak alalım.
2. İkinci eleman 5, 7'den küçük olduğu için sol tarafa yazılır.
3. Üçüncü eleman 1, 5'den küçük olduğu için 5'in soluna yazılır.
4. Dördüncü eleman 8, 7'den büyük olduğu için 7'nin sağına yazılır.
5. Beşinci eleman 3, 5'den küçük ama 1'den büyük olduğu için 1'in sağına yazılır.
6. Altıncı eleman 6, 7'den küçük ama 5'den büyük olduğu için 5'in sağına yazılır.
7. Yedinci eleman 0, 1'den küçük olduğu için 1'in soluna yazılır.
8. Sekizinci eleman 9, 8'den büyük olduğu için 8'in sağına yazılır.
9. Dokuzuncu eleman 4, 3'ün sağına yazılır.
10. Onuncu eleman 2, 1'den büyük ama 3'den küçük olduğu için 3'ün soluna yazılır.

# Binary Search Tree

              7
             / \
            5   8
           / \   \
          1   6   9 
        / \   
       0   3  
          / \
         2   4  