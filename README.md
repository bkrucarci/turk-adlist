## bkrucarci turk-adlist
Açıklama:       Türkçe sitelerde reklamları, rahatsız edici öğeleri engellemek için reklam sunucuları listesi ve reklam engelleme listeleri  
Explanation:    Ad servers list and annoying elements blocking list to block ads and annoying elements on Turkish sites

## Neden bu listeyi oluşturdum?

Asıl amaç reklam engelleme konusunda bir farkındalık oluşturmaktır. Reklamları engellemek sadece görsel olarak değil, güvenlik ve gizlilik anlamında da sizi gözetir.
Reklamlar ve reklam ağları çoğunlukla zararlı yazılım yaymak için kullanılıyor. Reklamları engelleyerek gerçek içeriğe ulaşırken gizliliğinizi koruyun ve zararlı yazılımları cihazınızdan uzak tutun.

![İnternet Kullanıcısını Bezdiren Sebepler](https://user-images.githubusercontent.com/15933805/146762673-930e2959-ece2-4788-9c89-a3b29dd5fbf5.jpg)

Birçok reklam engelleme listesi mevcut olsada Türkçe içerikli siteler ve reklamverenleri engelleyen filtre olmadığı için bu filtreyi oluşturmak istedim. Tek başına bu liste tüm reklamları engelleyemez. Zaten öyle bir amacımız yok! Yalnızca Türkçe içerikli sitelerdeki reklamları engellemek için kullanın. Tek başına hiçbir filtre veya host ile tüm reklamları engelleyemezsiniz. Uzun zamandır geliştirilen listelerle birlikte kullanıldığında daha etkin bir sonuç alabilirsiniz. Aşağıdaki başlıklarda nasıl kullanacağınızı öğrenebilirsiniz.

## Reklamları Nasıl Engelleyebilirim?

### İnternet Tarayıcıları

İnternet tarayıcıları için birçok reklam engelleme eklentisi mevcut. Bu aşamada benim filtremden daha güçlü olan ve Türkçe filtresi olan [AdGuard Reklam Engelleyici Eklentisini](https://adguard.com/tr/adguard-browser-extension/overview.html) kullanmanızı tavsiye ederim. AdGuard'ın diğer uygulamalarının aksine tarayıcı eklentisi açık kaynak kodlu ve ücretsizdir. Tüm popüler tarayıcılar ile uyumludur. (Chrome - Firefox - Opera - Safari - Edge - Yandex - vb.)

- Yukarıdaki bağlantıya ilerleyin ve kullandığınız internet tarayıcısının simgesine tıklayın.
- Tıkladıktan sonra hemen altında ortaya çıkan "İNDİR" butonuna tıklayın.
- Tarayıcınızın eklenti mağazasından AdGuard eklentisini tarayıcınıza ekleyin ve kurulumun bitmesini bekleyin.
- Eklenti kurulduktan sonra eklentinin ayarlar bölümüne gidin,
  + AdGuard Temel Filtresi,
  + AdGuard İzleme Koruması Filtresi,
  + AdGuard Sosyal Medya Filtresi,
  + AdGuard Can Sıkıcı Öğeler Filtresi,
  + AdGuard Türkçe Filtresini etkinleştirin.
  + Ayrıca benim oluşturduğum [deneysel filtreyi](https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/filters/turkish_generic_content_blocker.txt) de "Özel" filtre kısmına ekleyerek kullanabilirsiniz.
  + Filtreleri güncelle butonuna basın ve güle güle kullanın.

---
### Windows
- https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts adresinden listenin tamamını kopyalayın.
- Bilgisayarınızda C:\Windows\System32\drivers\etc konumuna ilerleyin ve hosts dosyasını bulun.
- hosts dosyasını notepad ile açarak listeyi buraya yapıştırın ve kaydedip çıkın.
- Bilgisayarınızı yeniden başlatın.

---
### MacOS
- https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts adresinden listenin tamamını kopyalayın.
- Terminali açın.
- `$ sudo nano /etc/hosts` komutunu çalıştırın.
- Listeyi dosyanın sonuna yapıştırın
- Control + O tuşlarına basın ve sonrasın enter tuşuna basın.
- Command + X tuşuyla çıkış yapın.
- `$ sudo cat /etc/hosts` komutunu çalıştırdığınızda listeyi görüyorsanız doğru yapmışsınızdır.
- Çalışmadığı durumda `$ sudo dscacheutil -flushcache` komutuyla host veritabınını yenileyebilirsiniz.

NOT: Listemizin hosts yapısı nedeniyle tüm reklamları engelleyemeyecektir. Böyle bir amacımız yok. Amacımız tarayıcımıza ve ağımıza binen reklam yükünü elimizden geldikçe azaltmak ve sayfaların daha hızlı yüklenmesini sağlamaktır. Sadece 3. taraflardan gelen reklamları engelleyebiliriz ve aslında birçok durumda bu filtreleme yöntemi yeterli olur. Ancak internet tarayıcınızda reklam engelleyici kullanarak etkin bir şekilde element filtrelemesi de yapabilirsiniz.

---
### Android 

### Android için AdGuard (ÜCRETLİ)

Android için AdGuard yazılımı bu konuda en iyisi denilebilir. Ücretli (Premium) sürümde birçok filtre kullanma imkanı size sunuyor ve daha gelişmiş bir reklam engelleme teknolojisi kullanıyor. Dediğim gibi bu uygulama ücretlidir ve [Google reklam politikalarının işine gelmedeği için Google Play'den kaldırılmıştır](https://adguard.com/en/blog/google-removes-adguard-android-app-google-play.html).
+ [Android için AdGuard](https://adguard.com/tr/adguard-android/overview.html)
+ Kurulum ve kullanımı kolaydır, ROOT gerektirmez.
+ 7 gün boyunca ücretsiz bir şekilde tam sürümü deneyebilirsiniz.
+ Ayarlardan istediğiniz filtreleri (yukarıdaki filtrelerin aynılarını) etkinleştirebilirsiniz.
+ Filtreleme yöntemini "Yüksek Kaliteli" yapın.
+ HTTPS kullanan reklam ağlarını ve uygulama içi reklamları (Oyun reklamları vb) engelleyebilir.

---

**NOT: AdGuard Android uygulaması, YouTube üzerindeki reklamları engelleyemez! Şu an piyasada hiçbir reklam engelleme uygulaması, YouTube'un resmi mobil uygulamalarındaki reklamları engelleyemez! Tekrar okuyun!**

---
### Telefonda-Tablette YouTube Reklamları Nasıl Engellenir?

Yukarıda yazdığım gibi resmi uygulamayı kullanarak reklamsız YouTube deneyimi mümkün değil. 3. parti uygulamalar ile ancak mümkün olmaktadır.

+ iOS üzerinde reklamsız YouTube için bir seçenek yok! [AdGuard İçerik Engelleyici](https://adguard.com/tr/adguard-ios/overview.html) ile birlikte Safari üzerinden YouTube açarsanız reklamları engelleyebilirsiniz.
+ Android üzerinde ise "modlanmış" uygulamalar aracılığı ile reklamsız YouTube deneyimi elde edebilirsiniz. Modlanmış uygulamalar Google Play Store üzerinden indirilemez. Bu uygulamalar market dışından olduğu için özel izinler ile tüm riskleri alarak kullanabilirsiniz.

Alternatif "Modlu" Android YouTube Uygulamaları

+ [YouTube Vanced](https://vancedapp.com/) uygulaması ücretsizdir ancak açık kaynaklı değildir. Çok daha kapsamlı özellikler sunmaktadır. Google Hesabınızla giriş yapabilirsiniz. "Micro G" modülü üzerinden Google hesabınıza erişerek, reklamsız birebir resmi YouTube uygulamasının deneyemini "reklamsız" elde edebilirsiniz.
+ [NewPipe](https://github.com/TeamNewPipe/NewPipe/#readme) özgür ve ücretsiz bir programdır. Herhangi bir Google Hesabı, Google API olmadan video izlyebilir ve indirebilirsiniz. NewPipe uygulamasını arkaplanda kapanmadan çalıştırabilirsiniz.

---
### DNS66 (Ücretsiz - Cihaz 'ROOTSUZ' ise)

Telefonunuzda root işlemi yapmak biraz zor ve riskli olabilir. Telefonunuzu garanti kapsamı dışına çıkarabilir. Telefonunuz root edilmemiş ise aşağıdaki adımlarla reklamları engelleyebilirsiniz.

- [DNS66](https://github.com/julian-klode/dns66/releases) uygulamasını (.apk uzantılı dosyayı) indirin.
- Bilinmeyen kaynaklar uyarısına izin verin. Uygulamayı telefonunuza ve ya tabletinize kurun.
- Uygulamayı açın, alt bölümde "Domain Filters" sekmesine dokunun.
- Sağ alt taraftaki "+" artı ikonuna dokunun ve aşağıdaki değerleri yazın.
- Title: bkrucarci turk adlist
- Location: https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts
- Action: Deny
- Sağ üstten "Save" diyerek bu ayarları kaydedin. Yukarıdaki yenile butonuna dokunarak güncellemeleri indirin.
- Start/Stop menüsüne geçin ve ekrana uzunca dokunun ve filtrelemeyi etkinleştirin.
- Eğer bildirim alanında anahtar işareti görüyorsanız, filtrelerimiz etkindir. Reklamsız gezinebilirsiniz.

### AdAway (Ücretsiz - Cihaz 'ROOTLU' ise)

Yukarıdaki DNS66 uygulamasını telefonunuz rootlu olsa bile kullanabilirsiniz. Ancak root erişim izniniz varsa telefonun kendi "hosts" dosyasını değiştirmek çok daha mantıklıdır çünkü batarya ve RAM tasarrufu sağlar.
Kök erişim (root) izniniz varsa AdAway uygulamasını kullanabilirsiniz. Host dosyaları ile reklam engelleyen ücretsiz bir uygulamadır.

- AdAway uygulamasını [buradan](https://github.com/AdAway/AdAway/releases) indirin.
- Uygulamayı telefonunuza veya tabletinize kurun.
- Uygulamayı açın ve uygulama menüsünden "Host kaynakları" sekmesini açın.
- Sağ üst köşedeki '+' işaretine dokunun. Bir bağlantı girmeniz istenecektir.
- https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts adresini kopyalayıp bu kısma yapıştırın ve ekleyin.
- Ana menüye dönün güncellemeleri denetleyip, uygulayın. Cihazınızı yeniden başlatın.

---
### Uyarı - Disclaimer
Bu makaledeki uygulamaların gizlilik sözleşmelerini okuyunuz. Eğer ne yaptığınızı bilmiyorsanız bu işlemlerden uzak durun. Her cihazın yapısı farklıdır, oluşabilecek sorunlardan makale editörü sorumlu tutulamaz! Bu makaleyi kopyalayabilir, istediğiniz gibi düzenleyip yeniden paylaşabilirsiniz.
