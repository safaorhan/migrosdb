# migrosdb
Türkiye Geneli Migros, 5M Migros ve Macrocenter Veritabanı

10 Mayıs 2017'de oluşturulmuştur. 3 farklı websitesi scrape edilerek yaklaşık 8 saatlik bir uğraş sonucu ortaya konmuştur.

#### Özellikler

- Veritabanında 1600'den fazla mağaza kaydı mevcuttur.
- Kayıtların hemen hepsi için mağaza tipleri belirtilmiştir. (M, MM, MMM, 5M, MACROCENTER)
- Mağazaların hemen hepsinde enlem ve boylam değerleri bulunmaktadır. Konum bazlı Migros bulan bir app yapmayı düşünüyorsanız bu json dosyası hayat kurtarır.
- Ayrıca her mağazanın açık adresi de yer almaktadır.

#### Dosyalar
Tüm json dosyaları aynı kayıtları içermektedir.

- migros.json: Asıl kaynakta var olan haliyle, girintileme (indentation) yapılarak oluşturulmuştur.
- migros.min.json: migros.json dosyasının boşlukları temizlenerek küçültülmüş halidir.
- migros-trfix.json: migros.json dosyasının http://www.turkcekarakter.com/ sitesi kullanılarak encoding'i değiştirilmiş halidir.
- migros-trfix.min.json: migros-trfix.json dosyasının boşlukları temizlenerek küçültülmüş halidir.

#### Katılım

Hatalı olduğunu gördüğünüz, düşündüğünüz herhangi bir kayıt olursa issue açabilirsiniz.

Scraper'ların kodları çok dağınık olduğu için şimdilik yüklemedim. İlerde belki scraper'ı tek bir node app'i haline getirip github'a yükleyebilirim. Böylece istediğiniz zaman database'i güncelleyebilirsiniz. 

#### Lisans

MIT



