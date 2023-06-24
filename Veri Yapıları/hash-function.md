## Hash Function
1. Hash function her seferinde aynı girdiye aynı sonucu vermeli.
2. Hash function farklı girdilere farklı çıktılar versin istiyoruz.
3. Hash function'ın çıktılarının sınırı array'in boyutunun sınırında olmalı.
4. Maalesef her seferinde farklı girdiler aynı sonuçlar doğurabiliyor, buna **Hash Collusion** denir.

Hash Function (Karma Fonksiyonu), karma fonksiyonu olabilmesi için bazı temel şartlar vardır.Bunlar;

* Gönderdiğimiz anahtarlar (keys) farklı olmasına rağmen bize aynı sonuçları veriyorsa bu bir hash function değildir.
* Fonksiyona gönderilen anahtarlar aynı fakat sonuç farklı ise hash function değildir.
* Hash Table için kullanılan dizinin boyutu verilen sonuçların sayısı kadar olmalı.