# Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. <br>
Big-O gösterimini yazınız.

--- 

## Çözüm
Verilen dizinin [16, 21, 11, 8, 12, 22] Merge Sort'a göre sıralama aşamaları şu şekildedir :

İlk aşamada, diziyi ikiye böleriz: <br>
Sol yarı dizi: [16, 21, 11]<br>
Sağ yarı dizi: [8, 12, 22]

Her yarı diziyi tekrar ikiye böleriz:<br>
Sol yarı dizi: [16], [21, 11]<br>
Sağ yarı dizi: [8], [12, 22]

Daha küçük alt dizilere ayrılmış olan her bir parçayı sıralarız:<br>
Sol yarı dizi: [16], [11, 21]<br>
Sağ yarı dizi: [8], [12, 22]

Her dizi tek parça kalana kadar bölmeye devam ederiz:<br>
Sol yarı dizi: [16], [11], [21]<br>
Sağ yarı dizi: [8], [12], [22]

Kalan tek parçaları birleştiririz:<br>
Sol yarı dizi: [11, 16, 21]<br>
Sağ yarı dizi: [8, 12, 22]

Son olarak, iki birleştirilmiş alt diziyi birleştiririz:<br>
Sıralanmış dizi: [8, 11, 12, 16, 21, 22]<br>
Bu şekilde Merge Sort algoritmasıyla verilen dizi adım adım sıralanır.

Big-O gösterimine gelince, Merge Sort'un karmaşıklığı ***O(nlogn)*** şeklindedir. Merge Sort, en kötü durumda bile bu karmaşıklığa sahiptir.