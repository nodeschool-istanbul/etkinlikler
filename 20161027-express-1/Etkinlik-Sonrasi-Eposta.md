Merhabalar,

27 ekim perşembe günü NodeSchool olarak düzenlediğimiz Express #1 atölyesine geldiğiniz için çok teşekkür ederiz.
Bazı bilgileri hatırlatmak adına sizlere bu mesajı gönderiyoruz.

## Etkinlik konusu
Etkinlikte ve duyurularda da belirttiğimiz gibi bu etkinlik birkaç atölyelik bir seriden oluşacaktır.
Amacımız, serinin sonunda Node.js üzerinde başta Express.js olmak üzere belli başlı temel modülleri kullanarak bir web sitesi, web uygulaması ve API geliştirebecek olmanız.
Katıldığınız bu etkinlik için ExpressJs 101 diyebiliriz. Amacımız Node.js ve Express'in çalışma temellerini açıklamaktı.

Her etkinlikte gelen artı ve eksiklerimize dikkat ediyor ve kendimizi geliştirmek istiyoruz. Bu sebeple etkinlikle ilgili her yorumunuz bizim için çok önemli.
Yorumlarınızı bize en hızlı Meetup grubumuz (http://www.meetup.com/nodeschool-istanbul/events/235075212/) üzerinden mesaj atarak iletebilirsiniz.

## Katılım
Yaklaşık 150 kişilik salon kontejyanımız olduğu için Meetup üzerinden 200 kişilik yer açmıştık. İlk etkinliğimize 120 nin üzerinde katılımcının geldiğini söylemekten mutluluk duyarız.
Bundan sonraki etkinlikleri de bir aksilik olmazsa aynı yerde yapmayı planlıyoruz.

## DÜzeltme
Sunum sırasında '' ile null'un aynı olduğunu söylemiştik. Sonradan bunun eksik olduğuna karar verdik.
Aslında Javascript'te bu iki değeri de boolean türüne çevirdiğimizde aynı cevabı alacağımızı söylemek istedik.
Bunu da Node komut satırında (REPL) veya herhangi bir javascript dosyasında:
```js
console.log(!null) // true
console.log(!'') // true
console.log(!'' == !null) // true
olarak görebiliriz.

## Sunumda kullandığımız/paylaştığımız sayfalar:
- NPM: Node.js modülleri resmi sitesi: https://www.npmjs.com/
- Programlama dillerinin modül sayıları karşılaştırması: http://www.modulecounts.com/
- Node.js Frameworkleri: https://node.ist/docs/nodejs-frameworks
- Node.js Şablon motorları: https://node.ist/docs/nodejs-template-engines
- Express.js kendi sitesi: http://expressjs.com/
- Express.js'de route lar: http://expressjs.com/en/guide/routing.html

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

Not: İlk etkinlikte Node.js kurulumu, hazırlığı yaptığımız ve temelini anlattığımız için, bir sonraki etkinliğie gelecek katılımcıların:
- Git (Windows için zorunlu)
- Node.js > 4
- Text editor (Sublime Text, Atom Editor, Visual Studio code, Webstorm, vb)
uygulamaları hazır bir şekilde gelmelerini bekliyoruz.

[1]: 
