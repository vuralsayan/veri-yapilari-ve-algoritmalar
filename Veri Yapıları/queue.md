## Queue
- ***Queue (Kuyruk), FIFO (First in First out) (İlk giren ilk çıkar)*** prensibine dayanan, girişlerde ve çıkışlarda belirli bir kurala göre çalışan yapıdır. Stack de verdiğimiz örneği kuyruğa göre uyarlayalım. Biz örnekte altı kapalı bir koli kutusunu düşünmüştük. Şimdi o koli kutusunun altı yırtılmış. Sonuç olarak ne oluyor? İlk giren ilk çıkmış oluyor.

- Queue (Kuyruk)'da eleman eklemesi yaparken **Enqueue** methodunu kullanıyoruz. Eleman silerken ise **Dequeue** methodunu kullanıyoruz. <br>

Diğer bir örnek olarak sinema girişinde bekleyen insanların oluşturduğu sırayı ele alabiliriz. Bu sırayı ilk oluşturan kişi sıradan ilk çıkacaktır, sıraya sonradan giren kişi ise sıradan en son çıkacaktır.  <br>

Enqueue kullandığımızda sıraya en baştan eleman eklenir, Dequeue kullandığımızda ise sıranın en sonundan eleman çıkar. <br> (soldan sağa baktığımız bir bilet sırası | | | | | | | |)