## Hash Table
### Hash Function / Hash Table 
- **Indexleme** <br>
Arraylerde 0 bazlı bir indexleme vardır. Bazı programlama dillerin 1 bazlı indexlemeler olsa da genel olarak 0 bazlı indexleme kullanılır.

<img src="https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/hash-table/figures/Indexleme.png" alt="indexleme" width="500" height="280"> <br>

- **Hash Function / Hash Table** <br>
Hash Table, key value prensibine dayanan bir array kümesidir. Key olarak çağırdığınız elemanın değerini (value) yansıtır. <br>

Hash Table yerine dizileri kullanabilirdik. Fakat her ürünü ve fiyatını tek tek aramak istemediğimiz için hash table kullanıyoruz. Peki bu süreç nasıl işliyor? Hemen bir örnek yapalım. Örneğimiz bir kuru yemiş dükkanından gelecek.

<img src="https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/hash-table/figures/%C3%B6rnek-ilk-k%C4%B1s%C4%B1m.png" alt="indexleme" width="500" height="280"> <br>

Bu kısımda ilk olarak bulunan ürün sayımız kadar değeri olan bir Array oluşturduk.

Daha sonra hash fonksiyonundan ürünleri geçirerek index değerlerine ulaştık.

<img src="https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/hash-table/figures/%C3%B6rnek-ikinci-k%C4%B1s%C4%B1m.png" alt="indexleme" width="500" height="280"> <br>

Şifrelendiği için artık her badem keyi gönderildiğinde 85TL, fıstık keyi gönderildiğinde ise 69 sonucu verecektir.

Özetle, elimizde var olan verileri bir fonksiyondan geçirip indexliyoruz. Bu fonksiyona ***Hash Function***, bu fonksiyon ile birleştiğimiz dizi yapısına ise ***Hash Table*** diyoruz.
