## bkrucarci turk-adlist
Açıklama:       Türkçe sitelerde reklamları, rahatsız edici öğeleri engellemek için reklam sunucuları listesi ve reklam engelleme listeleri  
Explanation:    Ad servers list and annoying elements blocking list to block ads and annoying elements on Turkish sites

## Neden bu listeyi oluşturdum?

Asıl amaç reklam engelleme konusunda bir farkındalık oluşturmaktır. Reklamları engellemek sadece görsel olarak değil, güvenlik ve gizlilik anlamında da sizi gözetir.
Reklamlar ve reklam ağları çoğunlukla zararlı yazılım yaymak için kullanılıyor. Reklamları engelleyerek gerçek içeriğe ulaşırken gizliliğinizi koruyun ve zararlı yazılımları cihazınızdan uzak tutun.

![İnternet Kullanıcısını Bezdiren Sebepler](https://user-images.githubusercontent.com/15933805/146762673-930e2959-ece2-4788-9c89-a3b29dd5fbf5.jpg)

Birçok reklam engelleme listesi mevcut olsada Türkçe içerikli siteler ve reklamverenleri engelleyen filtre olmadığı için bu filtreyi oluşturmak istedim. Tek başına bu liste tüm reklamları engelleyemez. Zaten öyle bir amacımız yok! Yalnızca Türkçe içerikli sitelerdeki reklamları engellemek için kullanın. Tek başına hiçbir filtre veya host ile tüm reklamları engelleyemezsiniz. Uzun zamandır geliştirilen listelerle birlikte kullanıldığında daha etkin bir sonuç alabilirsiniz.

Aşağıdaki başlıklarda herhangi bir platformda internetinizi reklamsız nasıl kullanırsınız anlatacağım.

## Reklamları Nasıl Engelleyebilirim?

### İnternet Tarayıcıları

İnternet tarayıcıları için birçok reklam engelleme eklentisi mevcut.

Bu aşamada sizlere Türkçe filtresi olan [AdGuard Reklam Engelleyici Eklentisini](https://adguard.com/tr/adguard-browser-extension/overview.html) kullanmanızı tavsiye ederim.

turk-adlist reklamları engellemek için yeterli olsa da sayfalarda reklamların bıraktığı boşlukları kapatabilmek, gizleyebilmek için "içerik engelleme" gereklidir. İçerik engelleme, host filtreleme ile mümkün değildir. Bu nedenle bir eklenti kullanmamız gereklidir. Sayfalardaki diğer içerikleri engelleme ve gizleme yeteneklerine AdGuard tarayıcı eklentisi ile sahip olabilirsinz.

AdGuard'ın tarayıcı eklentisi açık kaynak kodlu ve ücretsizdir.

Tüm popüler tarayıcılar ile uyumludur. (Chrome - Firefox - Opera - Safari - Edge - Yandex - vb.)

- Yukarıdaki bağlantıya ilerleyin ve kullandığınız internet tarayıcısının simgesine tıklayın.
- Tıkladıktan sonra hemen altında ortaya çıkan "İNDİR" butonuna tıklayın.
- Tarayıcınızın eklenti mağazasından AdGuard eklentisini tarayıcınıza ekleyin ve kurulumun bitmesini bekleyin.
- Eklenti kurulduktan sonra eklentinin ayarlar bölümüne gidin,
  + AdGuard Temel Filtresi,
  + AdGuard İzleme Koruması Filtresi,
  + AdGuard Sosyal Medya Filtresi,
  + AdGuard Can Sıkıcı Öğeler Filtresi,
  + AdGuard Türkçe Filtresini etkinleştirin.
  + Filtreleri güncelle butonuna basın ve güle güle kullanın.
   
  (UYARI! Reklamları engelleyeceğim derken ayarlarda gördüğünüz tüm filtreleri etkinleştirmeyin! Aynı işi yapan 3-4 filtreyi açmak bir fayda sağlamadığı gibi sayfaların açılış hızını yavaşlatacaktır. Optimum filtre kombinasyonu yukarıdaki gibidir.)

---
### TÜM PLATFORMLARDA DNS İLE REKLAM ENGELLEME

![](https://i.hizliresim.com/1ysnl6x.png)

Reklam engelleme için NextDNS uygulamasını öneriyorum. NextDNS üzerinde "bkrucarci turk-adlist" filtremizi, yapılandırmanızı hazırlarken "Gizlilik" sekmesinde görebilir, etkinleştirebilirsiniz. NextDNS ile internetinize bağlanan tüm cihazlarda etkin bir filtreleme yapabilirsiniz.

NextDNS sizi her türlü bilinen güvenlik tehdidinden korur, web sitelerinde ve uygulamalarda reklamları ve izleyicileri engeller. Tüm cihazlarınızda ve tüm ağlarda çocuklar için güvenli ve kontrol edilebilir bir internet deneyimi sağlar.

Nasıl kullanacağınızı öğrenmek istiyorsanız;

- [**NextDNS Kurulum Rehberi**](https://github.com/bkrucarci/turk-adlist/blob/master/NextDNS_Rehberi.md#nextdns-nedir-ne-i%C5%9Fe-yarar-neden-kullanmal%C4%B1y%C4%B1m)'ne gözatın

---

**NOT : YouTube 'resmi' mobil uygulamaları üzerinde reklamları engellemek teknik açıdan şu an mümkün değil! Şu an piyasada hiçbir reklam engelleme uygulaması, YouTube'un 'resmi' mobil uygulamalarındaki reklamları engelleyemez! Tekrar okuyun!**

**Şu an piyasada hiçbir reklam engelleme uygulaması, YouTube'un 'resmi' mobil uygulamalarındaki reklamları engelleyemez!**

(Bu teknoloji bir gün mümkün olduğunda bu klavuz güncellenecektir!)

---
### Telefonda-Tablette YouTube Reklamlarını Nasıl Engellenir?

Yukarıda yazdığım gibi resmi uygulamayı kullanarak reklamsız YouTube deneyimi mümkün değil. 3. parti uygulamalar ile ancak mümkün olmaktadır.

+ iOS üzerinde reklamsız YouTube için bir seçenek yok! [Safari için AdGuard](https://adguard.com/tr/adguard-ios/overview.html) uygulaması ile birlikte Safari üzerinden YouTube websitesini açarsanız reklamları engelleyebilirsiniz. Apple kısıtlamaları nedeniyle iPhone ve iPad üzerinde farklı bir şansınız bulunmuyor.
+ Android üzerinde iOS cihazlara oranla daha özgür olduğumuz için "modlanmış" uygulamalar aracılığı ile reklamsız YouTube deneyimi elde edebilirsiniz.
YouTube, Google'a ait bir platformdur. Gelirinin neredeyse tamamını reklamlardan elde eden Google kendi uygulama mağazasında YouTube reklamlarını engelleyebilen alternatiflerine izin vermemektedir.
Bu nedenle modlanmış uygulamalar Google Play Store üzerinden indirilemez.
Bu uygulamalar market dışından olduğu için "market dışından uygulama yüklemeye izin vererek" aşağıdaki uygulamaları kullanabilirsiniz.

#### "Modlanmış" Android YouTube Uygulamaları

+ [NewPipe](https://newpipe.net/) özgür ve ücretsiz bir uygulamadır. Herhangi bir Google Hesabı, Google API olmadan video izleyebilir ve indirebilirsiniz. NewPipe uygulamasını arkaplanda kapanmadan çalıştırabilirsiniz.
+ [SkyTube](https://skytube-app.com/) özgür ve ücretsiz bir uygulamadır. Herhangi bir Google Hesabı, Google API olmadan video izleyebilir hatta favori kanallarınızı takip edebilirsiniz. İstemediğiniz videoları engelleyebilirsiniz. Beğendiğiniz videolara yerimi ekleyerek daha sonra tekrar izleyebilirsiniz.
+ [LibreTube](https://github.com/libre-tube/LibreTube) LibreTube, şu anda beta olarak kullanılabilen geliştirilmesi devam eden açık kaynaklı özgür bir YouTube arayüzüdür. Reklamsız  YouTube görüntüleme deneyimi ve video indirme gibi temel özellikleri barındırır.
+ [YouTube Vanced](https://vancedapp.com/) uygulaması ücretsizdir ancak açık kaynaklı değildir. Çok daha kapsamlı özellikler sunmaktadır. Google Hesabınızla giriş yapabilirsiniz. "Micro G" modülü üzerinden Google hesabınıza erişerek, reklamsız birebir resmi YouTube uygulamasının deneyemini "reklamsız" elde edebilirsiniz.

(Not: Vanced uygulaması 13.03.2022 tarihinde Google'ın yasal yaptırımları sonucu "[geliştirilmesi durdurulmuştur.](https://twitter.com/YTVanced/status/1503052250268286980)" Bundan sonraki süreçte uygulama güncelleme almayacaktır. [NewPipe](https://newpipe.net/) veya diğer alternatifleri kullanmanızı tavsiye ederim.)

Dikkat! Bu önerdiğim uygulamalar dışındaki uygulamalardan kaçının. Yukarıda önerdiğim uygulamalar uzun zamandır geniş bir topluluk tarafından kullanılan, test edilen ve güvenilirliğini ispatlamış uygulamalardır. Reklam engellemek uğruna telefonunuza az bilinen, kim tarafından geliştirildiği belli olmayan uygulamaları kurmayın!
