## week-1-assignment

Cookie ve Session Storage ile set ve get işlemleri nasıl yapılır ? 
script.js dosyası içerisinde örneklerle açıklayınız.
<br>

<ins>**SessionStorage Örneği**</ins>

- Butona tıklanma sayısını sessionStorage'da tutar. 
- Butona tıklandıkça sessionStorage'daki değer senkron olarak değişir. Tarayıcı veya sekmeyi kapatınca sessionStorage'daki değerler silinir.

---

<ins>**Cookie Örneği**</ins> 
- İlk olarak, ziyaretçinin adını bir çerez değişkeninde saklayan bir fonksiyon oluşturuldu. <br>
- Daha sonra, belirtilen çerezin değerini döndüren bir fonksiyon oluşturuldu. <br>
- Son olarak, çerezin ayarlanıp ayarlanmadığını kontrol eden fonksiyon oluşturuldu.Eğer cookie ayarlanmamışsa alert ile isim bilgisi sorar, isim bilgisi girildikten sonra setCookie fonksiyonu çağrılır ve kullanıcı adı tanımlanır ve 365 gün boyunca veriler saklanır. <br>
- 365 gün veriler saklandığı için sayfa tekrar açıldığında alert ekranı "Welcome again **"name"**" şeklinde karşılar.
