# Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması<br>
Worst case: Aradığımız sayının sonda olmasız<br>
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

---
## Çözüm
Verilen dizinin [22, 27, 16, 2, 18, 6] Insertion Sort'a göre sıralama aşamaları şu şekildedir:

İlk aşamada, listenin ikinci elemanı olan 27'yi alırız ve ilk eleman olan 22 ile karşılaştırırız. 22'den büyük olduğu için yerlerini değiştirmeyiz ve liste şu şekilde olur: [22, 27, 16, 2, 18, 6].

Sıradaki eleman 16'dır. Bu elemanı sıralanmış kısmın içindeki doğru konumuna yerleştirmek için sıralanmış kısmı soldan sağa tararız. 22'den küçük olduğu için 22'nin soluna yerleştiririz. Liste şu şekilde olur: [16, 22, 27, 2, 18, 6].

Sonraki eleman 2'dir. Bu elemanı sıralanmış kısmın içindeki doğru konumuna yerleştirmek için sıralanmış kısmı tararız. 2, 16'dan küçük olduğu için 16'nın soluna yerleştiririz. Liste şu şekilde olur: [2, 16, 22, 27, 18, 6].

Ardından, 18 elemanını doğru konumuna yerleştirmek için sıralanmış kısmı tararız. 18, 22'den küçük olduğu için 22'nin soluna yerleştiririz. Liste şu şekilde olur: [2, 16, 18, 22, 27, 6].

Son olarak, 6 elemanını doğru konumuna yerleştirmek için sıralanmış kısmı tararız. 6, 16'dan küçük olduğu için 16'nın soluna yerleştiririz. Son olarak liste bu şekilde olur [2, 6, 16, 18, 22, 27].

Big-O gösterimine gelince, Insertion Sort'un ortalama ve en kötü durum karmaşıklığı O(n^2) şeklindedir.

18 sayısı, sıralanmış dizinin tam olarak ortasında bulunmaktadır. Dolayısıyla, Average Case olarak kabul edilir.

--- 
Verilen dizinin [7, 3, 5, 8, 2, 9, 4, 15, 6] Selection Sort'a göre ilk 4 adımı şu şekildedir:

Adım 1: En küçük elemanı bulup ilk elemanla yer değiştirme

Dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]
En küçük eleman 2'dir. 2, ilk eleman olan 7 ile yer değiştirir.
Yeni dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]
Adım 2: En küçük elemanı bulup ikinci elemanla yer değiştirme

Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]
En küçük eleman 3'tür. 3, ikinci eleman olan 3 ile yer değiştirir (yer değişimi yapılmaz).
Yeni dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]
Adım 3: En küçük elemanı bulup üçüncü elemanla yer değiştirme

Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]
En küçük eleman 4'tür. 4, üçüncü eleman olan 5 ile yer değiştirir.
Yeni dizi: [2, 3, 4, 8, 7, 9, 5, 15, 6]
Adım 4: En küçük elemanı bulup dördüncü elemanla yer değiştirme

Dizi: [2, 3, 4, 8, 7, 9, 5, 15, 6]
En küçük eleman 5'tir. 5, dördüncü eleman olan 8 ile yer değiştirir.
Yeni dizi: [2, 3, 4, 5, 7, 9, 8, 15, 6]
Bu şekilde ilk 4 adım gerçekleştirilerek Selection Sort algoritmasıyla dizi adım adım sıralanır.