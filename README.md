## bkrcrc turk-adlist
Açıklama:       Türkçe sitelerde reklamları engellemek için reklam sunucuları listesi  
Explanation:    Ad servers list to block ads on Turkish websites (for use with hosts files)

## Neden bu listeyi oluşturdum?
Birçok reklam engelleme listesi mevcut olsada Türkçe içerikli siteler ve reklamverenleri engelleyen filtre olmadığı için bu filtreyi oluşturmak istedim. Tek başına bu liste tüm reklamları engelleyemez zaten öyle bir amacımız yok, yalnızca Türkçe içerikli sitelerdeki reklamları engellemek için kullanın. Tek başına hiçbir filtre ve ya host ile tüm reklamları engelleyemezsiniz. Uzun zamandır geliştirilen listelerle birlikte kullanıldığında daha etkin bir sonuç alabilirsiniz. Aşağıdaki başlıklarda nasıl kullanacağınızı öğrenebilirsiniz.

## Reklamları Nasıl Engelleyebilirim?

### İşlem Adımları - WINDOWS
- https://raw.githubusercontent.com/bkrcrc/turk-adlist/master/hosts adresinden listenin tamamını kopyalayın.
- Bilgisayarınızda C:\Windows\System32\drivers\etc konumuna ilerleyin ve hosts dosyasını bulun.
- hosts dosyasını notepad ile açarak listeyi buraya yapıştırın ve kaydedip çıkın.
- Bilgisayarınızı yeniden başlatın.

NOT: Listemiz tüm reklamları engelleyemeyecektir, diğer listeler ile birlikte kullanınız ya da tarayıcınızda reklam engelleyici kullanın. Önerdiğim engelleyici uBlock Origin eklentisidir. [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/), [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) ve [Opera](https://addons.opera.com/extensions/details/ublock/) tarayıcılarınıza ekleyerek kullanabilirsiniz.
Eklentiyi kurduktan sonra uBlock Origin ayarlarından "3. taraf süzgeçler > Özel" konumuna https://raw.githubusercontent.com/bkrcrc/turk-adlist/master/hosts adresini yapıştırın ve "Değişiklikleri Uygula" diyerek ayarları kapatın.

Artık tarayıcınızda reklamsız gezinebilirsiniz.

### İşlem Adımları - ANDROİD (Cihaz 'ROOTSUZ' ise)
Telefonunuzda root işlemi yapmak biraz zor ve riskli olabilir. Telefonunuzu garanti kapsamı dışına çıkarabilir. Bu gibi durumda aşağıdaki adımlarla reklamları engelleyebilirsiniz.

- [Adguard Android](https://adguard.com/apk) uygulamasını indirin.
- Uygulamayı telefonunuza ve ya tabletinize kurun. Tam sürüm için deneme talep edin, bu şekilde 14 gün boyunca tam sürümü ücretsiz kullabilirsiniz.
- Uygulamayı açın ve düğmeye dokunarak korumayı etkinleştirin.

NOT: Adguard Android ücretsiz olarak kullanılabilir ancak uygulamaların içindeki reklamları engelleme özelliği ücretlidir! Satın alabilecek gücünüz varsa mobil cihazlarda mevcut en iyi uygulamadır, beğenirseniz alabilirsiniz.
Eğer ücretsiz bir çözüm isterseniz [Seven Adclear](https://www.seven.com/android-adblocker-download.php) uygulamasını deneyebilirsiniz.

### İşlem Adımları - ANDROİD (Cihaz 'ROOTLU' ise)
Telefonunuzda kök erişim (root) izniniz varsa AdAway uygulamasını kullanabilirsiniz. Host dosyaları ile reklam engelleyen ücretsiz bir uygulamadır.

- AdAway uygulamasını [buradan](https://f-droid.org/repo/org.adaway_57.apk) indirin.
- Uygulamayı telefonunuza ve ya tabletinize kurun.
- Uygulamayı açın ve uygulama menüsünden "Host kaynakları" sekmesini açın.
- Sağ üst köşedeki '+' işaretine dokunun. Bir bağlantı girmeniz istenecektir.
- https://raw.githubusercontent.com/bkrcrc/turk-adlist/master/hosts adresini kopyalayıp bu kısma yapıştırın ve ekleyin.
- Ana menüye dönün güncellemeleri denetleyip, uygulayın. Cihazınızı yeniden başlatın.

## Uyarı - Disclaimer
Bu makaledeki uygulamaların gizlilik sözleşmelerini okuyunuz. Eğer ne yaptığınızı bilmiyorsanız bu işlemlerden uzak durun. Her cihazın yapısı farklıdır, oluşabilecek sorunlardan makale editörü sorumlu tutulamaz! Bu makaleyi kopyalayabilir, istediğiniz gibi düzenleyip yeniden paylaşabilirsiniz.
