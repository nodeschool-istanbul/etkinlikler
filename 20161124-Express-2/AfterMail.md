Merhabalar,

27 ekim perşembe günü NodeSchool olarak düzenlediğimiz Express #2 atölyesine geldiğiniz için çok teşekkür ederiz.
Bazı bilgileri hatırlatmak adına sizlere bu mesajı gönderiyoruz.  
Bu mesajın tamamını https://github.com/nodeschool-istanbul/etkinlikler/blob/master/20161124-Express-2/AfterMail.md adresinde bulabilirsiniz.

## Etkinlik Serisi
Etkinlikte ve duyurularda da belirttiğimiz gibi bu etkinlik birkaç atölyelik bir seriden oluşacaktır.
Amacımız, serinin sonunda Node.js üzerinde başta Express.js olmak üzere belli başlı temel modülleri kullanarak bir web sitesi, web uygulaması ve API geliştirebilecek kadar Node.js ve Express bilmeniz.

## Etkinlikte işlediğimiz konuların özeti
* Geçen haftanın özeti
* Express'in diğer framework'lerden farkı
* Express'te Middlewareler, route'lar, controller'lar
  * Middleware için `app.use` veya HTTP-verbs/methods için `app.get`, `app.post`, `app.put` vs..
  * Middleware ve controller'ın `request`, `response`, `next` ve `error` parametreleri
  * Middleware'deki bir bağlantının `response.end()`, `response.render()` veya `response.redirect()` ile sonlandırılması
  
* Nunjucks template engine, 
* Modüler uygulama
  * Requre ve module exports
  app i bölmek route ve middlewa
  render ı bölmek
* bower ve statik ve bootstrap
* login post ve verify ı
* cookie ve session 

## Geri Bildirim
Her etkinlikte gelen artı ve eksiklerimize dikkat ediyor ve kendimizi geliştirmek istiyoruz. Bu sebeple etkinlikle ilgili her yorumunuz bizim için çok önemli.
Yorumlarınızı bize en hızlı Meetup grubumuz (http://www.meetup.com/nodeschool-istanbul/events/235075212/) üzerinden mesaj atarak iletebilirsiniz.

## Katılım
Salonumuzun kapasitesi 150 kişilik olduğu için Meetup üzerinden 200 kişilik yer açmıştık. Katılımdan bir saat önce tüm başvurular dolmuştu. İlk etkinliğimize 120 nin üzerinde katılımcının geldiğini söylemekten mutluluk duyarız.
Bundan sonraki etkinlikleri de bir aksilik olmazsa aynı yerde yapmayı planlıyoruz.

## Düzeltme
Sunum sırasında `''` ile `null` un aynı olduğunu söylemiştik. Sonradan bunun eksik olduğunun farkına vardık.
Aslında Javascript'te bu iki değeri de boolean türüne çevirdiğimizde aynı cevabı alacağımızı söylemek istedik.
Bunu da Node komut satırında (REPL) veya herhangi bir javascript dosyasında
```js
console.log(null == '') // false
console.log(!null) // true
console.log(!'') // true
console.log(!'' == !null) // true
console.log(!!'' == !!null) // true
```
yazarak görebiliriz. Yine bonus olarak
```js
console.log(0 == '') // true
console.log(undefined == null) // true
```
olduğunu görebiliriz. Doğru (strict) bir karşılaştırma yapmamız için `===` operatörünü kullanmalıyız.

## Sunumda kullandığımız/paylaştığımız sayfalar:
- NPM: Node.js modülleri resmi sitesi: https://www.npmjs.com/
- NodeJs modüllerini aramak için kullandığımız sitelerden biri: http://www.npmsearch.com/
- Programlama dillerinin modül sayıları karşılaştırması: http://www.modulecounts.com/
- Node.js Frameworkleri listesi: https://node.ist/docs/nodejs-frameworks
- Node.js Şablon motorları listesi: https://node.ist/docs/nodejs-template-engines
- Express.js kendi sitesi: http://expressjs.com/
- Express.js'de route lar: http://expressjs.com/en/guide/routing.html
- Express.js'in NPM'deki paket sayfası: https://www.npmjs.com/package/express
- Kullandığımız şablon motoru Mozilla Nunjucks'ın sitesi: https://mozilla.github.io/nunjucks/

## Bir sonraki etkinlik
Express 102 kod adıyla hitap edebileceğimiz 2. etkinliğimiz ilkinden tam iki hafta sonra, aynı yerde ve aynı saatte olacaktır.
Bu haftasonu meetup üzerinden etkinliğimizi açıp duyurumuzu yapmayı planlıyoruz.

Konu listesini aşağıdaki gibi planlıyoruz (güncellenebilir)
- HTTP methodları için Express'i kullanmak
- Basit bir form eklemek ve veri POST etmek
- Bower ile Express kullanımı
- repsonse.render ile sayfaya parametre göndermek
- Nunjucks şablon motoruna giriş, layout'lar, partial'lar, filter'lar ve konfigürasyon
- Belli başlı express middleware'leri

Not: İlk etkinlikte Node.js kurulumu, hazırlığı yaptığımız ve temelini anlattığımız için, bir sonraki etkinliğe gelecek katılımcıların aşağıdaki uygulamaları kurulu bir şekilde gelmelerini bekliyoruz:
- Git (Windows için zorunlu)
- Node.js > 4
- Text editor (Sublime Text, Atom Editor, Visual Studio code, Webstorm, vb)

