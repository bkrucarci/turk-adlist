## bkrucarci turk-adlist
Açıklama:       Türkçe sitelerde reklamları engellemek için reklam sunucuları listesi  
Explanation:    Ad servers list to block ads on Turkish websites (for use with hosts files)

## Neden bu listeyi oluşturdum?
Birçok reklam engelleme listesi mevcut olsada Türkçe içerikli siteler ve reklamverenleri engelleyen filtre olmadığı için bu filtreyi oluşturmak istedim. Tek başına bu liste tüm reklamları engelleyemez zaten öyle bir amacımız yok, yalnızca Türkçe içerikli sitelerdeki reklamları engellemek için kullanın. Tek başına hiçbir filtre ve ya host ile tüm reklamları engelleyemezsiniz. Uzun zamandır geliştirilen listelerle birlikte kullanıldığında daha etkin bir sonuç alabilirsiniz. Aşağıdaki başlıklarda nasıl kullanacağınızı öğrenebilirsiniz.

## Reklamları Nasıl Engelleyebilirim?

### İşlem Adımları - WINDOWS
- https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts adresinden listenin tamamını kopyalayın.
- Bilgisayarınızda C:\Windows\System32\drivers\etc konumuna ilerleyin ve hosts dosyasını bulun.
- hosts dosyasını notepad ile açarak listeyi buraya yapıştırın ve kaydedip çıkın.
- Bilgisayarınızı yeniden başlatın.

NOT: Listemizin hosts yapısı nedeniyle tüm reklamları engelleyemeyecektir. Sadece 3. taraflardan gelen reklamları engelleyebiliriz ve aslında birçok durumda bu filtreleme yöntemi yeterli olur. Ancak internet tarayıcınızda reklam engelleyici kullanarak etkin bir şekilde element filtrelemesi de yapabilirsiniz. 

  Önerdiğim engelleyici uBlock Origin eklentisidir. [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/), [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) ve [Opera](https://addons.opera.com/extensions/details/ublock/) tarayıcılarınıza ekleyerek kullanabilirsiniz.
  
  Eklentiyi kurduktan sonra uBlock Origin ayarlarından "3. taraf süzgeçler > Özel" konumuna https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts adresini yapıştırın ve "Değişiklikleri Uygula" diyerek ayarları kapatın.
  
  Sistem çapında reklam engellemek ve gizliliğinizi artırmak için, birçok faydalı özelliği barındıran ["Windows için AdGuard"](https://github.com/AdguardTeam/AdguardForWindows/releases) programını öneririm. Tüm tarayıcılar ile çalışır, her tarayıcıya eklenti kurmanız gerekmez. Windows içinde kurulu programlarınızda da (ör. Spotify) reklam ve takipçileri engeller.
  
### İşlem Adımları - ANDROİD (Cihaz 'ROOTSUZ' ise)
Telefonunuzda root işlemi yapmak biraz zor ve riskli olabilir. Telefonunuzu garanti kapsamı dışına çıkarabilir. Bu gibi durumda aşağıdaki adımlarla reklamları engelleyebilirsiniz.

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

### İşlem Adımları - ANDROİD (Cihaz 'ROOTLU' ise)
Telefonunuzda kök erişim (root) izniniz varsa AdAway uygulamasını kullanabilirsiniz. Host dosyaları ile reklam engelleyen ücretsiz bir uygulamadır.

- AdAway uygulamasını [buradan](https://f-droid.org/repo/org.adaway_60.apk) indirin.
- Uygulamayı telefonunuza ve ya tabletinize kurun.
- Uygulamayı açın ve uygulama menüsünden "Host kaynakları" sekmesini açın.
- Sağ üst köşedeki '+' işaretine dokunun. Bir bağlantı girmeniz istenecektir.
- https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts adresini kopyalayıp bu kısma yapıştırın ve ekleyin.
- Ana menüye dönün güncellemeleri denetleyip, uygulayın. Cihazınızı yeniden başlatın.
- Android için yukarıdaki sıraladığım adımları anlatan görsellere [buradan](https://bilenlerkabilesi.com/adaway-android-icin-en-iyi-reklam-engelleme-uygulamasi/) gözatabilirsiniz. Sadece yeni Host ekleme kısmında https://raw.githubusercontent.com/bkrucarci/turk-adlist/master/hosts adresini kullanın.

## Uyarı - Disclaimer
Bu makaledeki uygulamaların gizlilik sözleşmelerini okuyunuz. Eğer ne yaptığınızı bilmiyorsanız bu işlemlerden uzak durun. Her cihazın yapısı farklıdır, oluşabilecek sorunlardan makale editörü sorumlu tutulamaz! Bu makaleyi kopyalayabilir, istediğiniz gibi düzenleyip yeniden paylaşabilirsiniz.
