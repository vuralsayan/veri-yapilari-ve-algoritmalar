## Hash Collision
Hash Function farklı iki değerden aynı sayı üretilirse bu duruma Collison (çarpışma) denir. Bu olay istediğimiz bir durum değildir. <br>

- Hash Function'lar bazen farklı durumlar için farklı sonuçlar üretemeyebilir. Örnek olarak araçları bir hash function dan geçirelim. Bu fonksiyonumuz son harflerine göre bir değer atıyor. Örneğin, motor ve tır için aynı değerleri ataması Collision'a neden oluyor.

- Collision sorunuyla az karşılaşabilmek için kaliteli bir Hash Function olmalı. Bu sayede verimli bir Hash Table elde etmiş oluyoruz.

- Çarpışma sayısı arttıkça aradığımız şeyi bulma hızı azalır.

Özet olarak hızlı bir Hash Table yaratabilmek için tasarladığımız Hash Funciton kaliteli olmalı yani oluşturduğumuz Hash Function'ın Collision'ı en az seviyede olmalı.
