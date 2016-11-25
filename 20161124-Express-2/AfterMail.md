Merhabalar,

24 kasım perşembe günü [NodeSchool Istanbul](http://nodeschool.ist/) olarak düzenlediğimiz Express #2 atölyesine geldiğiniz için çok teşekkür ederiz. Sizlere bazı bilgileri hatırlatmak adına bu mesajı gönderiyoruz.

Bu mesajın tamamını https://github.com/nodeschool-istanbul/etkinlikler/blob/master/20161124-Express-2/AfterMail.md adresinde bulabilirsiniz.

## Etkinlik Serisi

Etkinlikte ve duyurularda da belirttiğimiz gibi bu etkinlik birkaç atölyelik bir seriden oluşacaktır.
Amacımız, serinin sonunda Node.js üzerinde başta Express.js olmak üzere belli başlı temel modülleri kullanarak bir web sitesi, web uygulaması ve API geliştirebilecek kadar Node.js ve Express bilmeniz.

## Katılım

Salonumuzun kapasitesi 150 kişilik olduğu için Meetup üzerinden 200 kişilik yer açmıştık. Meetup üzerinden **105** kişi geleceğini bildirmişti. Etkinliğimize **40**ın üzerinde kişinin geldiğini söylemekten mutluluk duyarız.

Etkinlik saatinde aynı zamanda maç olduğu için etkinliğimize katılamayanlar oldu. Gelecekteki etkinliklerimizi planlarken bunu da göz önünde bulunduracağız :)

## Etkinlikte işlediğimiz konuların özeti

* Geçen haftanın özeti
* Express'in diğer framework'lerden farkı
* Express'te middlewareler, route'lar, controller'lar
 * Middleware için `app.use` veya HTTP-verbs/methods için `app.get`, `app.post`, `app.put` vs..
 * Middleware ve controller'ın `request`, `response`, `next` ve `error` parametreleri
 * Middleware'e gelen bir isteğin `response.end()`, `response.render()` veya `response.redirect()` ile sonlandırılması
 * Node.js'te server-side uygulama akış şeması
 * Middleware sırası
* Nunjucks template engine
 * Uygulamaya middleware olarak ekleme
 * **Template**, **Layout** ve **Partial/Component** kavramı
 * `{% extend "..." %}` ve `{% include "..." %}` ile layout ve partial kullanımı, `{% block ... %}...{% endblock %}` kavramı
* Node.js modüllerini çağırmak (`require`), modül haline getirmek (`module.exports`) ve `path` ile relative/full path kavramı
* Uygulamayı bölmek
 * `app.js`'deki *middleware* ve **route**'ları ayırmak
 * `/lib/render.js` ile render'ı merkezileştirmek
* Bower ve bootstrap
 * Projeye `bower init` ile Bower eklemek
 * `bower install --save bootstrap` ile bootstrap kurulumu
 * `.gitignore` dosyasına `bower_components` klasörünü eklemek
 * Layout dosyasına bootstrap javascript ve css'lerini eklemek
 * `app.use(express.static())` middleware'inin eklenmesi ve `bower_components` klasörünün yayınlanması
* Cookie ve session
 * Login ve loginPost sayfalarının, controller ve template'lerinin oluşturulması
 * Cookie ve session'ların çalışma mantığı ve eklenmesi
 * Body Parser ile form bilgilerinin alınması

## Sunumda kullandığımız/paylaştığımız sayfalar:

- Node.js Frameworkleri listesi: https://node.ist/docs/nodejs-frameworks
- Kullandığımız şablon motoru Mozilla Nunjucks'ın sitesi: https://mozilla.github.io/nunjucks/
- `cookie-parser` modülü: https://github.com/expressjs/cookie-parser
- `express-session` modülü: https://github.com/expressjs/session
- `body-parser` modülü: https://github.com/expressjs/body-parser
- `express.static()` metodu: https://expressjs.com/en/starter/static-files.html   
- İştakip uygulaması adresi: https://github.com/nodeschool-istanbul/istakip

## Etkinlik materyalleri

* Etkinlikte yazdığımız örnek uygulamayı https://github.com/nodeschool-istanbul/express-2 adresinde bulabilirsiniz.
* Etkinliğin başında kullandığımız sunumu https://github.com/nodeschool-istanbul/etkinlikler/tree/master/20161124-Express-2 adresinde bulabilirsiniz.

## Etkinlik fotoğrafları ve videosu

Henüz bir video-kayıt ekipmanımız olmadığı için etkinliğin kaydını yapamıyoruz. Eğer sizde kayıp ekipmanı varsa bizimle iletişime geçerek yardım edebilirsiniz.

Çektiğimiz fotoğrafları [Meetup sayfamız](https://www.meetup.com/nodeschool-istanbul/events/235619166/) a yükleyeceğiz. Sizin de çektiğiniz fotoğraf ve videoları buraya yüklerseniz çok mutlu oluruz.

## Geri Bildirim

Her etkinlikte gelen artı ve eksiklerimize dikkat ediyor ve kendimizi geliştirmek istiyoruz. Bu sebeple etkinlikle ilgili her yorumunuz bizim için çok önemli.
Yorumlarınızı bize en hızlı şekilde etkinliğimizin [Meetup sayfası](https://www.meetup.com/nodeschool-istanbul/events/235619166/) üzerinden mesaj atarak iletebilirsiniz.

## Bir sonraki etkinlik

Express #3 etkinliğimizi aynı yerde, 2 hafta sonra yapmayı planlıyoruz. Yer ve tarih kesinleşince Meetup üzerinden duyuru yapacağız.

Anlatmayı planladığımız konular şunlardır:
- Redis kurulumu ve Node.js'te kullanma
 - Session'ları Redis'te tutmak
- MongoDB kurulumu
 - ODM kavramı, Mongoose ODM modülü ve Mongo modülü ile karşılaştırma
 - Şema ve model kavramları
 - Uygulama modelimizi oluşturmak
- Kayıt ol ekranı eklenmesi
- Giriş yap ekranının MongoDB'ye bağlanması
- MongoDB Relation'ları
