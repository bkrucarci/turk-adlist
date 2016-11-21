## turk-adlist
Açıklama:       Türkçe sitelerde reklamları engellemek için reklam sunucuları listesi  
Explanation:    Ad servers list to block ads on Turkish websites (for use with hosts files)

## Neden bu listeyi oluşturdum?
Birçok reklam engelleme listesi mevcut olsada Türkçe içerikli siteler ve reklamverenleri engelleyen filtre olmadığı için bu filtreyi oluşturmak istedim. Tek başına bu liste tüm reklamları engelleyemez zaten öyle bir amacımız yok, yalnızca Türkçe içerikli sitelerdeki reklamları engellemek için kullanın. Diğer büyük listelerle birlikte kullanıldığında daha etkin bir sonuç alabilirsiniz.

## Reklamları Nasıl Engelleyebilirim?
Öncelikle Android telefonunuzda kök (root) erişim iznini almanız gerekmektedir.
Root işlemini yapmanız telefonunuzu garanti kapsamı dışına çıkarabilir! Eğer hala garantili bir telefonunuz varsa ve çok fazla teknik bilgi sahibi birisi değilseniz. [Adguard Android](https://adguard.com/apk) uygulamasını öneririm. Türkçe filtresi bulunmaktadır ve gayet başarılıdır.
Root işlemini nasıl yapacağınızı internetten öğrenin. (KingoRoot programını bilgisayarınıza indirip, yapabilirsiniz).  
Root işlemini yaptıysanız AdAway uygulaması artık host dosyanızı değiştirme iznine sahip olacaktır. 
Daha sonra AdAway uygulaması ile aşağıdaki işlem adımlarını uygulayın. [AdAway](https://adaway.org/) özgür ve açık kaynka kodlu, host dosyaları ile reklam engelleyen bir uygulamadır.
Eğer isterseniz bilgisayarınızda da bu listeyi kullanabilirsiniz.

## İşlem Adımları - WINDOWS
- https://raw.githubusercontent.com/bkrcrc/turk-adlist/master/hosts adresinden listenin tamamını kopyalayın.
- Bilgisayarınızda C:\Windows\System32\drivers\etc konumuna ilerleyin ve hosts dosyasını bulun.
- hosts dosyasını notepad ile açarak listeyi buraya yapıştırın ve kaydedip çıkın.
- Bilgisayarınızı yeniden başlatın.

NOT: Listemiz tüm reklamları engelleyemeyecektir, diğer listeler ile birlikte kullanınız ya da tarayıcınızda reklam engelleyici kullanın. Önerdiğim reklam engelleyici Adguard Reklam Engelleyici eklentisidir. [Firefox](https://addons.mozilla.org/en-US/firefox/addon/adguard-adblocker/), [Chrome](https://chrome.google.com/webstore/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg) ve [Opera](https://addons.opera.com/tr/extensions/details/adguard/) içinde kullanın.
Eklentiyi kurduktan sonra eklenti ayarlarından Sosyal Ağ Araçları, Casus Engelleme ve Annoyances filtrelerini etkinleştirin.

## İşlem Adımları - ANDROİD
- AdAway uygulamasını [buradan](https://f-droid.org/repo/org.adaway_57.apk) indirin.
- Uygulamayı telefonunuza ve ya tabletinize kurun.
- Uygulamayı açın ve uygulama menüsünden "Host kaynakları" sekmesini açın.
- Sağ üst köşedeki '+' işaretine dokunun. Bir bağlantı girmeniz istenecektir.
- https://raw.githubusercontent.com/bkrcrc/turk-adlist/master/hosts adresini kopyalayıp bu kısma yapıştırın ve ekleyin.
- Ana menüye dönün güncellemeri denetleyip, uygulayın. Cihazınızı yeniden başlatın.

Tebrikler! Artık Türkçe reklam verenler listemiz ile engellenecektir. 

## Lisans - License
License          : [Creative Commons Attribution-ShareAlike 3.0 Unported](https://creativecommons.org/licenses/by-sa/3.0/)
