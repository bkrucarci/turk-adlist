## bkrucarci turk-adlist
Açıklama:       Türkçe sitelerde reklamları engellemek için reklam sunucuları listesi  
Explanation:    Ad servers list to block ads on Turkish websites (for use with hosts files)

## Neden bu listeyi oluşturdum?

![İnternet Kullanıcısını Bezdiren Sebepler](https://vgy.me/icMIZ6.jpg)

Birçok reklam engelleme listesi mevcut olsada Türkçe içerikli siteler ve reklamverenleri engelleyen filtre olmadığı için bu filtreyi oluşturmak istedim. Tek başına bu liste tüm reklamları engelleyemez zaten öyle bir amacımız yok, yalnızca Türkçe içerikli sitelerdeki reklamları engellemek için kullanın. Tek başına hiçbir filtre veya host ile tüm reklamları engelleyemezsiniz. Uzun zamandır geliştirilen listelerle birlikte kullanıldığında daha etkin bir sonuç alabilirsiniz. Aşağıdaki başlıklarda nasıl kullanacağınızı öğrenebilirsiniz.

## Reklamları Nasıl Engelleyebilirim?

### WINDOWS
- https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts adresinden listenin tamamını kopyalayın.
- Bilgisayarınızda C:\Windows\System32\drivers\etc konumuna ilerleyin ve hosts dosyasını bulun.
- hosts dosyasını notepad ile açarak listeyi buraya yapıştırın ve kaydedip çıkın.
- Bilgisayarınızı yeniden başlatın.

NOT: Listemizin hosts yapısı nedeniyle tüm reklamları engelleyemeyecektir. Sadece 3. taraflardan gelen reklamları engelleyebiliriz ve aslında birçok durumda bu filtreleme yöntemi yeterli olur. Ancak internet tarayıcınızda reklam engelleyici kullanarak etkin bir şekilde element filtrelemesi de yapabilirsiniz.

### İNTERNET TARAYICILARI

İnternet tarayıcıları için birçok reklam engelleme eklentisi mevcut. Bu aşamada benim filtremden daha güçlü olan ve Türkçe filtresi olan [AdGuard Reklam Engelleyici Eklentisini](https://adguard.com/tr/adguard-browser-extension/overview.html) kullanmanızı tavsiye ederim. Tüm popüler tarayıcılar ile uyumludur. (Chrome - Firefox - Opera - Yandex - Edge - Safari)

- Yukarıdaki bağlantıya ilerleyin ve kullandığınız internet tarayıcısının simgesine tıklayın.
- Tıkladıktan sonra hemen altında ortaya çıkan "İNDİR" butonuna tıklayın.
- Tarayıcınızın eklenti mağazasından AdGuard eklentisini tarayıcınıza ekleyin ve kurulumun bitmesini bekleyin.
- Eklenti kurulduktan sonra eklentinin ayarlar bölümüne gidin,
  + İngilizce filtre,
  + Casus Engelleme filtresi,
  + Sosyal Medya filtresi,
  + Can Sıkıcı Öğeler filtresi,
  + Türkçe filtreyi etkinleştirin.
Filtreleri güncelle butonuna basın ve güle güle kullanın.

# ANDROİD (İşin Android kısmında ücretli ve ücretsiz 2 Seçeneğiniz Var!)
Ücretsiz yazılımlar genelde hosts seviyesinde reklam engelleyebilmekte ve çoğu zaman uygulamalarda reklamları engelleyememektedir!

## Android için AdGuard (ÜCRETLİ)
Android için AdGuard yazılımı bu konuda en iyisi denilebilir. Ücretli (Premium) sürümde birçok filtre kullanma imkanı size sunuyor ve daha gelişmiş bir reklam engelleme teknolojisi kullanıyor. Dediğim gibi bu uygulama ücretlidir ve [Google reklam politikalarının işine gelmedeği için Google Play'den kaldırılmıştır](https://blog.adguard.com/en/google-removes-adguard-android-app-google-play/).
+ [Android için AdGuard](https://adguard.com/tr/adguard-android/overview.html)
+ Kurulum ve kullanımı kolaydır, ROOT gerektirmez.
+ 14 gün ücretsiz tam sürümü deneyebilirsiniz,
+ Ayarlardan istediğiniz filtreleri (yukarıdaki filtrelerin aynılarını) etkinleştirebilirsiniz.
+ Filtreleme yöntemini "Yüksek Kaliteli" yapın.
+ HTTPS kullanan reklam ağlarını ve uygulamaları (Youtube reklamları gibi) engelleyebilir.

### DNS66 (ÜCRETSİZ - Cihaz 'ROOTLU' değilse)

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

### AdAway (ÜCRETSİZ - Cihaz 'ROOTLU' ise)

Yukarıdaki DNS66 uygulamasını telefonunuz rootlu olsa bile kullanabilirsiniz. Ancak root erişim izniniz varsa telefonun kendi "hosts" dosyasını değiştirmek çok daha mantıklıdır çünkü batarya ve RAM tasarrufu sağlar.
Kök erişim (root) izniniz varsa AdAway uygulamasını kullanabilirsiniz. Host dosyaları ile reklam engelleyen ücretsiz bir uygulamadır.

- AdAway uygulamasını [buradan](https://f-droid.org/repo/org.adaway_60.apk) indirin.
- Uygulamayı telefonunuza veya tabletinize kurun.
- Uygulamayı açın ve uygulama menüsünden "Host kaynakları" sekmesini açın.
- Sağ üst köşedeki '+' işaretine dokunun. Bir bağlantı girmeniz istenecektir.
- https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts adresini kopyalayıp bu kısma yapıştırın ve ekleyin.
- Ana menüye dönün güncellemeleri denetleyip, uygulayın. Cihazınızı yeniden başlatın.
- Android için yukarıdaki sıraladığım adımları anlatan görsellere [buradan](http://bilenlerkabilesi.com/adaway-android-icin-en-iyi-reklam-engelleme-uygulamasi/) gözatabilirsiniz. Sadece yeni Host ekleme kısmında https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts adresini kullanın.

## Uyarı - Disclaimer
Bu makaledeki uygulamaların gizlilik sözleşmelerini okuyunuz. Eğer ne yaptığınızı bilmiyorsanız bu işlemlerden uzak durun. Her cihazın yapısı farklıdır, oluşabilecek sorunlardan makale editörü sorumlu tutulamaz! Bu makaleyi kopyalayabilir, istediğiniz gibi düzenleyip yeniden paylaşabilirsiniz.
