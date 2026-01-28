---
title: "{{< fa wrench size=2x >}} API ve veri yeniden kullanımı"
description: "6 soru"
lang: en-gb
order: 12
category-level: 0
icon: anahtar
---

{{< fa "anahtar" size=3x >}}

## Yüklenen fotoğraflar için uygun boyut konusunda dokümantasyonda herhangi bir öneri var mı?

Bu durum, ülkelere ve ağ bağlantısının yavaş veya pahalı olmasına bağlı olabilir. Genişliği veya yüksekliği 5000 pikselin üzerinde olan herhangi bir şey muhtemelen pek kullanışlı değildir. Ve eğer bir şekilde ağın yavaş olduğunu tespit edebilirseniz, 2000 piksellik bir görüntü bile harika olurdu (kesinlikle hiç görüntü olmamasından daha iyidir!).

---

## Barkodsuz gıdalar ne olacak peki?

Open Food Facts yalnızca paketlenmiş gıdalar hakkında bilgi içerir. Meyve ve sebzelerin (örneğin domates veya muz) ve diğer gıda ürünlerinin ortalama değerleri için resmi ulusal beslenme veritabanlarından birini kullanabilirsiniz.

**Not:** Aşağıdaki liste, en önemli ulusal gıda veritabanlarından bazılarını içermektedir. Listeye başka bir veritabanının da eklenmesi gerektiğini düşünüyorsanız, lütfen bizimle şu adresten iletişime geçin: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Ulusal Gıda Veritabanları Listesi**

-

**Avustralya** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belçika** - NUBEL - Belçika Gıda Bileşimi Verileri: [https://www.internubel.be](https://www.internubel.be/)

-

**Kanada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Çek Cumhuriyeti** - Ulusal Halk Sağlığı Enstitüsü Gıda Bileşimi Veritabanı: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Danimarka** - Danimarka Gıda Bileşimi Veritabanı: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estonya** - Estonya Gıda Bileşimi Veritabanı: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finlandiya** - Finlandiya Gıda Bileşimi Veritabanı - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Fransa** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Almanya** - Souci-Fachmann-Kraut Çevrimiçi Veritabanı: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) veya resmi Almanca Veritabanı: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **İtalya** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Hollanda** - Hollanda Gıda Bileşimi Veritabanı: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norveç** - Norveç Gıda Bileşim Tablosu 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polonya** - Gıda Bileşim Tabloları: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**İspanya** - İspanyol Gıda Bileşimi Veritabanı - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**İsviçre** - İsviçre Gıda Bileşimi Veritabanı: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Birleşik Krallık** - Gıdaların Bileşimi Entegre Veri Seti (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**ABD** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## API kullanarak belirli bir ürün adını arayabilir miyim?

Maalesef, API üzerinden yalnızca ürün adına göre ve hassas bir şekilde arama yapmak henüz kolay değil.

Arama sonuçlarını daha kesin hale getirmek için kategoriye göre filtre kullanmak faydalı olabilir.

---

## Projelerim için verilere nasıl erişebilirim/verileri nasıl toplayabilirim?

Open Food Facts'in ana sayfasında, ekranın sol üst köşesinde kaydırılabilir bir menü bulunmaktadır. Sayfanın en altında, tıklayabileceğiniz "gelişmiş arama" seçeneğini bulacaksınız. O halde, projeniz/projeleriniz için hangi kriterlerin en uygun olduğuna karar vermek size kalmış. Seçiminizi yaptıktan sonra, sayfanın en altındaki "Sonuçları indir" seçeneğine tıklayarak elde edilen sonuçları indirebilirsiniz.

Ayrıca şunlara da danışabilirsiniz:

- API dokümantasyonumuz:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Open Food Facts'in Kullanım Şartları:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- Verilerimiz hakkında:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## API'yi kullanmak için şartlar var mı?

API kullanımına ilişkin tüm belgeler [API dokümantasyon sayfasında](https://openfoodfacts.github.io/openfoodfacts-server/api/) bulunabilir, ancak işte kısa bir özet:

- Open Food Facts veritabanı, Açık Veritabanı Lisansı (ODbL) kapsamında açık veri olarak sunulmaktadır; yasal ayrıntılar için [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) adresine bakınız. İki koşul, atıf ve paylaşımlılıktır. Open Food Facts'ten elde edilen verileri diğer veritabanlarıyla birleştirirseniz, ODbL (Open Data License) gereği ortaya çıkan veritabanının da açık veri olarak yayınlanması gerekir. Bu aynı zamanda verileri yalnızca bu tür yeniden dağıtıma izin veren kaynaklarla birleştirebileceğiniz anlamına da gelir.

- Uygulamanızı tanımlamak için API çağrıları yaparken **her zaman** özel bir User-Agent kullanmalısınız.

- Her API uç noktası için hız sınırlamaları uygulanır.

---

## Geçmiş verilere nasıl erişebilirim?

Şu anda geçmişe ait veri dökümü (JSONL, MongoDB, CSV) hizmeti sunmuyoruz.

Ancak, bireysel ürünler için, API aracılığıyla veya ürün sayfasındaki revizyonlar seçeneğiyle ürün verilerinin önceki sürümlerine erişmek mümkündür.

Bir ürün her güncellendiğinde, yeni bir revizyon (1'den başlayarak artan rakamlı) oluşturulur.

Örneğin, bu ürünün ilk revizyonunu (=ilk ürün sürümünü) almak için şunu kullanın:

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

Benzer şekilde, rev parametresi API ile birlikte kullanılabilir:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

