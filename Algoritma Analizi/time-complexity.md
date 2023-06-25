## Time Complexity

1. Worst Case: Vereceğimiz inputun algoritmamızı en yavaş (en fazla işlem yapacak)şekilde çalıştırdığı durum. Aradığımız kelimenin "z" harfiyle başlaması gibi.

2. Average Case : Genel olarak beklediğimiz durum.

3. Best Case: Vereceğimiz inputun algoritmamızı en hızlı şekilde çalıştırıdğı durum.


Algoritmanın verimli olabilmesi için belirli kurallar vardır.
- Örnek: Raflara kitap yerleştirmek.

- Kitapları, gelişigüzel raflara dağıtırsak aradığımız kitabı daha fazla zamanda bulabiliriz. Aslında bu bir **worst case'dir**. Kitapları filtrelememiz gerekir. Kalın olanları bir rafa, ince olanları bir rafa, küçük boyutta olanları bir rafa koyduğumuz zaman aradığımız şeyi daha rahat bulabiliriz. Algoritma, en kötü senaryoya ne kadar hazırsa, bizi o kadar memnun edebilir.

- Algoritmalar için genellikle sık kullanılan **average case'dir**. Kitapların bölümüne göre kaç tane olduğunu biliyorsak average case kullanabiliriz. En büyük rafı miktarı fazla olana ayırabiliriz. Input yoksa average zordur!!!!

- Bir diğer senaryomuz ise **best case'dir**. Beklediğimiz en iyi durum. Kitap örneğine devam edecek olursak, bütün kitapların ayrı raflarda olması, alfabeye göre sıralanması best case olarak ifade edilebilir. Çünkü aradığımızı rahatlıkla bulabiliyoruz.
