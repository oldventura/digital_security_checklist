# Dijital Güvenlik Kılavuzu
Dediğim hiçbir şeye kesin gözle bakmayın, araştırın, en sona kaynak bırakacağım. Uzun zamandır bu alandayım, en önemli bulduğum önerileri ve uyulması gereken önlemleri sıralıyorum.

1. Öncelikle **reddit**'e kaydolurken mail adresi vermenize gerek yok, direkt geçebiliyorsunuz. **reddit**'de mail adresi kullanmayın.
2. İster **reddit** olsun ister **Twitter**, **Facebook** kendi hakkınızda kişisel hiçbir bilgi vermeyin, daha iyisi herkese farklı bilgiler verin. Herkese yalan bilgiler verin, farklı kişilikler kullanın.
3. Sitelere, bağlandığınız ağlara güvenmiyorsanız bir **VPN** kullanın, fakat ücretsiz olanlardan sakının. Özellikle bu üçü en güvenlileri: **ivpn**, **Protonvpn**, **Mullvad VPN**.
4. **VPN** için ayırabileceğiniz paranız yoksa **tor** kullanabilirsiniz, fakat ikisi arasında net bir fark var; **Tor** sadece size anonimlik sağlar. **Tor** üzerinden kişisel bilgi verecek işlemler yaparsanız elinizde güvenlik namına hiçbir şey kalmaz. **Tor** da kullanırken tamamen sıradan işlemlerde bulunmalısınız, her seferinde yeni bir "**Identity**" kullanmalısınız **Tor Browser** içinde.
5. **Tor** dışında başka network'ler de mevcut, **i2p**'ye bakabilirsiniz, normal interneti araştırabileceğiniz **exit node**'ları var.
6. İnternetteki işlemleriniz için **Google** servislerinden tamamen uzaklaşın.
7. **Gmail** ve **Hotmail** gibi mail servisleri yerine **Protonmail** kullanabilirsiniz.
8. Kullandığınız cihazlarda biyometrik şifre kullanmayın, yani parmak izinizi kaldırın. Onun yerine rastgele sayılardan/karakterlerden oluşan bir parola kullanın. Sizi parmak izinizi vermeye zorlayabilirler ama aklınızdan bir bilgiyi koparmak ondan daha zor, kısaca şifreyi "unuttum" diyebilirsiniz.
9. Açık kaynak kodlu bir **Keyword Manager** kullanın. İnternette kullandığınız tüm servisler için random bir şifre kullanın. Bunun için "**Keepassxc**" adlı programı öneriyorum, offline çalışıyor ve açık kaynak kodlu. **Keepassxc** ile random şifre veya **passphrase** de üretebiliyorsunuz. 24 haneli "special characters" da içeren "alphanumeric" bir şifre gayet yeterli. Hiçbir servisiniz arasında şifreler bakımından bir benzerlik olmamalı. Bu "**Keepassxc**" deki şifreleri tutan veritabanı için kurulumun başında şifre  belirliyorsunuz, zaman zaman veritabanı yedeği almayı unutmayın. BitWarden'a da bakabilirsiniz. Ama genellikle veritabanını şifreli olsa da online bir ortamda (cloud servisleri gibi) saklamaktan sakının.
10. Ücretli veya ücretsiz ama kazanç planı belli olmayan programlar, servisler için açık kaynak kodlu alternatiflerini tercih edin. Bunları bulmak için bu siteyi kullanabilirsiniz: [https://alternativeto.net/](https://alternativeto.net/)
11. Mesaj uygulamanızı değiştirin; **Whatsapp**'dan sakının. Bunun yerine **Signal**'i, sonra **Session**'ı, **Jami**'yi, **Matrix** protokolü üzerinden çalışan **Element**'i ve Android kullanıyorsanız **Briar**'ı tercih edin. **Telegram** diyecekseniz eğer varsayılan olarak **end-to-end encryption** sağlamıyor, yanı konuştuğunuz kişiyle aranızda bir şifreleme varsayılan olarak kurulmuyor. **Telegram** kullanıyorsanız konuştuğunuz kişinin profiline girip "**Start Secret Chat**" demeniz lazım. Ama onun yerine yukarıda yazdığım alternatifleri kullanın. Bunlar dışında **OTP** kullanarak herhangi bir **XMPP** servisini de kullanabilirsiniz, bunun için **Pidgin** adında bir client var, her işe yarıyor ama bu konuda çok detaya girmeyeceğim şuan, yazının sonunda kaynak bırakacağım.
12. Web tarayıcısı olarak **Firefox** kullanın, nokta. Firefox içinde "**Privacy Badger**" ile "**uBlock Origin**" eklentilerini kullanın. **Adblocker**'lar sadece reklamları engellemiyor.
13. Arama motoru olarak **Google** dışında alternatifler kullanın. **Duckduckgo** var ama iyi sonuç vermiyor, onun yerine **Searx** adında bir program var, bu anonim bir şekilde arama kelimenizi tüm arama motorlarından geçirerek size sonuç sunuyor, yani **Searx**'ı kullanıp yine **Google** üzerinden sonuç alabilirsiniz. **Searx**'ı kendinizin kurması gerekmiyor, internette bu servisle çalışan siteler var, buradan bulabilirsiniz: [https://searx.space/](https://searx.space/)
14. Kullandığınız servislerin hangi ülke merkezli olduğuna çok dikkat edin, büyük ülkelerden sakının. Bu konuda "**The Fourteen Eyes**", "**Five Eyes**"ı araştırın.
15. Sitelerin **HTTPS** kullandığından emin olun, sadece **HTTP** kullanan sitelere bilgi vermekten sakının.
16. **DNS** trafiğinizi gizlemeye çalışın: [https://privacytools.io/providers/dns/#icanndns](https://privacytools.io/providers/dns/#icanndns)
17. Güvensiz bir işletim sistemi kullanmayın ve üzerine önlemler aldığınızdan emin olun. **Windows** kullanıyorsanız zaten başından patlamışsınız demek, niye böyle dediğime buradan bakabilirsiniz: [https://privacytools.io/operating-systems/](https://privacytools.io/operating-systems/)
18. **Windows** yerine **Linux** kullanın, geçmek çok zor değil, kendinize uyan bir dağıtım bulabilirsiniz, bir sürü farklı dağıtım var. Bunların hepsine bu siteden bakabilirsiniz: [https://distrowatch.com/](https://distrowatch.com/)
19. **Linux** için **Ubuntu** kullanmasanız daha iyi olur, bir sürü **bloatware** ile geliyor. Tübitak'ın geliştirdiği **Pardus**'u da kullanmasanız iyi olur ama bunun için bir neden veremem.
20. **Linux** için en temel **Debian**'ı kullanabilirsiniz. Ama normal bir kullanım için şu dağıtımlara bakın: **Arch Linux**, **Manjaro**, **Fedora**, **Alpine Linux**, **Mint**. Desktop Manager olarak **Gnome** size daha yakın gelecektir. Yeni başlayanlar **Fedora**, **Ubuntu** ve **Manjaro**'ya bakabilirler.
21. İşletim sistemiyle ilgili daha fazla güvenlik istiyorsanız **Tails**, **Qubes OS** ve **Whonix**'i araştırın.
22. **Android** yerine güvenlik merkezli custom rom kullanabilirsiniz; **GrapheneOS**, **CalyxOS**, **LineageOS**, **/e/ OS**, bunlardan birkaçı. Ama başka işletim sistemi kullansanız da **Google** servislerinden uzaklaşın, sadece **Google** uygulamaları demiyorum, Google servislerinden de. **Google** servisleri yerine **microG**'yi araştırın.
23. Telefonunuzda kullandığınız klavye yazılımına dikkat edin. Genellikle açık kaynak kodlu bir alternatifini kullanmanız daha iyidir. Çünkü klavye programları yazdığınız kelimeleri görebiliyor, hakkınızda bilgi toplayabiliyor, bir klavye programının neden İnternet erişimi olsun ki? Özellikle **Android** kullanıyorsanız "**AnySoftKeyboard**"a bakabilirsiniz.
24. **Google Playstore** yerine sadece açık kaynak kodlu uygulamaların yer aldığı "**F-Droid**"i kullanabilirsiniz. Arayacağını ve ihtiyacınız olan bir sürü program zaten orada.
25. Telefonunuzdan **Facebook**, **Instagram**, **LinkedIn** gibi uygulamaları kaldırın. **Android**'de de tamamen kaldırmak mümkün, bunun için **ADB** kullanmanız gerekebilir. Kısaca internette "**how to remove bloatware from android phone without rooting**" diye aratabilirsiniz. Bu siteye bakabilirsiniz: [https://www.xda-developers.com/uninstall-carrier-oem-bloatware-without-root-access/](https://www.xda-developers.com/uninstall-carrier-oem-bloatware-without-root-access/)
26. Saat diliminiz internette hangi ülkede yaşadığınız bilgisini verebilir. Olabildiğince tuhaf saatlerde interneti kullanın, yani baskın olan bir saat aralığınız olmasın.
27. Konuşma şeklinizi değiştirin arada, internette yazdıklarınızdan yazı tahlilleri yapılabiliyor. Türkçe için şuan böyle bir şey var mıdır bilmiyorum.
28. Güvenliğinizin açığa çıktığından eminseniz bağlı veya alakalı olan tüm hesapları derhal silin. En başından bir "**Total Wipedown**" planı hazırlanıyor, acil durum planı. Belki cihazlarınızdan da kurtulmanız gerekebilir, tehdit seviyenizi belirleyin.
29. İnternetteki servislerinizde hem aynı adı veya nickname'i kullanmayın, olabildiğince fazla farklı kimlik kullanın. Kolayca rastgele oluşturmak için buraya bakabilirsiniz: [https://www.fakenamegenerator.com/gen-random-us-gr.php](https://www.fakenamegenerator.com/gen-random-us-gr.php)
30. Konferans uygulamaları (**Zoom** gibi) için **Jitsi**'yi ([https://meet.jit.si/](https://meet.jit.si/)) veya **Jami**'yi kullanabilirsiniz. **Tox** da var ama hiç kullanmadım.
31. Cihazlarınızda güvenlik güncellemelerini yapın. Hala 4 sene öncesinden kalan bir işletim sistemi versiyonunu kullanmayın.
32. İki doğrulama korumayı kullanın (**2FA**), ama **SMS** üzerinden ve **Google** üzerinden çalışan alternatiflerden sakının. **Google Authenticator** kullanmayın mesela, onun yerine **Keepassxc**'ye de entegre edebiliyorsunuz **OTP**'yi (**One Time Password**), ayrıca **Aegis**'i de kullanabilirsiniz.
33. Email'ler genellikle güvenli değil, mail içeriğiniz kolayca okunabiliyor. **Thunderbird** adlı mail client'ını kullanıp içinde **PGP Manager** 'ı kullanabilirsiniz. **OpenPGP**'yi araştırın, kullanın.
34. Bilmediğiniz linklere tıklamayın, sahiden söylüyorum, bu önemli. Aşağıda yazdığım 2. aracı kullanarak lnklerin nereye gittiklerini inceleyebilirsiniz. Sadece bir linke tıklayarak tıklayan kişinin ip'sini, yaşadığı yeri, zaman dilimini, kullandığı browser'ı, işletim sistemini vs. bulunabiliyor. Dahası sadece bir link'e tıklayarak kameranızdan fotoğraf ve hatta sisteminizi ele geçiren **exploit**'ler koşulabiliyor. Bunları uydurmuyorum, yapması da çok kolay, bu araçları yazmayacaktım ama bilmeniz önlem almanız bakımından daha önemli. O nedenle araçlar kısmına ekledim.
35. Şifrenizin göründüğü bir ekran fotoğrafı aldığınızda şifre kısmını pixel'lemek (yani mozaiklemek) yeterli bir önlem değil. Mozaiklenen kısım geri çevrilebiliyor.
36. Bağımsız güvenlik blog'larını takip edin: [https://www.sentinelone.com/blog/](https://www.sentinelone.com/blog/)
37. Avrupa **veri gizliliğine** sanıldığı kadar **önem vermiyor**:
    1. [https://www.privateinternetaccess.com/blog/new-german-law-would-force-isps-to-allow-secret-service-to-install-trojans-on-user-devices/](https://www.privateinternetaccess.com/blog/new-german-law-would-force-isps-to-allow-secret-service-to-install-trojans-on-user-devices/)
    2. [https://www.theregister.com/2021/06/07/in\_brief\_security/](https://www.theregister.com/2021/06/07/in_brief_security/)
    3. [https://www.euractiv.com/section/digital/news/civil-society-tech-giants-oppose-germanys-state-trojans-plans/](https://www.euractiv.com/section/digital/news/civil-society-tech-giants-oppose-germanys-state-trojans-plans/)
    4. [https://www.deutschlandfunk.de/bundestag-beschliesst-staatstrojaner-geheimdienste-und.1939.de.html?drn:news\_id=1268308](https://www.deutschlandfunk.de/bundestag-beschliesst-staatstrojaner-geheimdienste-und.1939.de.html?drn:news_id=1268308)
42. Bunu söylememe umarım gerek yoktur ama **Tiktok** falan kullanıyorsanız telefonunuzu çöpe atın. Derhal **Tiktok**'u silin, arkadaşlarınıza da kullandırtmayın.
43. **Yandex** ile doğrulama olmadan anonim e-mail hesabı oluşturup bunu doğrulama kodları almak için kullanabilirsiniz.
44. Teker teker tüm cihazlara adblocker vs. kurmak yerine ağınıza bir **PiHole** kurmayı deneyebilirsiniz.
45. Firefox'da çerezler ile ilgili şu eklentilere bakabilirsiniz: **CookieAutoDelete** ve **ClearURLs**. Gerçi firefox ayarlarından browser'ı her kapattığınızda çerezleri otomatik silmesi için ayarlayabilirsiniz. **ClearURLs** eklentisi de URL'lerden tracking element'lerini kaldırmaya yarar.
46. Cihazınızda **Full disk encryption** yaptığınızdan emin olun. Windows'da bu **bitlocker** ile yapılıyor. OSX'de ise ayarlardan seçip şifreletebilirsiniz.
47. Linux'da **Flatpak** ile **Flathub**'dan uygulamaları kurarak **sandbox**'da çalıştırıp uygulamaları güvenlik açısından izole ettirebilirsiniz. Hem bu şekildeki uygulamaların kurumu da daha kolay olabiliyor.
48. Linux'da üst düzey güvenlik önlemleri için şu iki kaynağa bakabilirsiniz:
    1. https://www.reddit.com/r/linux/comments/ns7r7o/a_complete_yet_beginner_friendly_guide_on_how_to/
    2. https://github.com/trimstray/the-practical-linux-hardening-guide
49. Gerçekten bir antivirüs programı arıyorsanız **ClamAV**, **ClamTK** ve **Malwarebytes**'a bakın. Windows'da **Windows Defender** ile bu bahsettiklerimi kullanmanız yeterli olacaktır. Linux'da ayrıca **rkhunter** programını kullanabilirsiniz.

# KAYNAKLAR

1. [https://security-list.js.org/#/](https://security-list.js.org/#/)
2. [https://privacytools.io/](https://privacytools.io/)
3. [https://ssd.eff.org/en/](https://ssd.eff.org/en/)
4. [https://prism-break.org/en/](https://prism-break.org/en/)
5. [https://riseup.net/en](https://riseup.net/en)
6. [https://datadetoxkit.org/en/home/](https://datadetoxkit.org/en/home/) :D
7. [https://watchyourhack.com/](https://watchyourhack.com/)
8. [https://www.whonix.org/](https://www.whonix.org/)
9. [https://www.qubes-os.org/](https://www.qubes-os.org/)
10. [https://www.safetydetectives.com/best-vpns/#detailed](https://www.safetydetectives.com/best-vpns/#detailed)
11. [https://itsfoss.com/all-blog-posts/](https://itsfoss.com/all-blog-posts/)
12. [https://www.fosshub.com/](https://www.fosshub.com/)
13. [https://en.wikipedia.org/wiki/List\_of\_free\_and\_open-source\_software\_packages](https://en.wikipedia.org/wiki/List_of_free_and_open-source_software_packages)
14. [https://bbs.archlinux.org/](https://bbs.archlinux.org/)
15. [https://wiki.archlinux.org/](https://wiki.archlinux.org/)
16. [https://en.wikipedia.org/wiki/Warrant\_canary](https://en.wikipedia.org/wiki/Warrant_canary)
17. KAYNAKLARIN HOLY BIBLE'I: [https://github.com/sindresorhus/awesome](https://github.com/sindresorhus/awesome)

# ARAÇLAR

1. [https://reports.exodus-privacy.eu.org/en/](https://reports.exodus-privacy.eu.org/en/)
2. [https://redirectdetective.com/](https://redirectdetective.com/)
3. [https://www.virustotal.com/gui/](https://www.virustotal.com/gui/)
4. [https://www.islegitsite.com/](https://www.islegitsite.com/)
5. [https://github.com/allisonburtch/micjammer](https://github.com/allisonburtch/micjammer)
6. [https://osintframework.com/](https://osintframework.com/)
7. [https://start.me/p/L1rEYQ/osint4all](https://start.me/p/L1rEYQ/osint4all)
8. [https://amiunique.org/](https://amiunique.org/)
9. [https://ufile.io/](https://ufile.io/)
10. [https://iknowwhatyoudownload.com/en/peer/](https://iknowwhatyoudownload.com/en/peer/)
11. [https://thispersondoesnotexist.com/](https://thispersondoesnotexist.com/)
12. [https://urlscan.io/](https://urlscan.io/)
13. [https://www.zoomeye.org/](https://www.zoomeye.org/)
14. [https://alternativeto.net/](https://alternativeto.net/)
15. [https://letsencrypt.org/](https://letsencrypt.org/)
16. [https://haveibeenpwned.com/](https://haveibeenpwned.com/)
17. [https://grabify.link/](https://grabify.link/)
18. [https://github.com/hangetzzu/saycheese](https://github.com/hangetzzu/saycheese)

Sizin, benim, hiçbirimizin aklının eremeyeceği dahi acayip exploit'ler, bilgi sızdırma yöntemleri var. Kimsenin dediğini baştan doğru olarak kabul etmeyin, her zaman **ARAŞTIRIN**. Open-Source ve Linux toplulukları her zaman dostunuzdur.

&#x200B;

>**Şuan için aklıma gelenler bunlardı, daha yazmadığım bir sürü şey var. Yorumlarda dilediğinizi sorun, sorulara göre listeyi güncellemeye çalışacağım.**  
>  
>Yazılımda önlem alsanız bile "**Social-Engineering** denen bir kavram var, en zayıf halka insandır. Unutmayın, paranoyak olmanız takip edilmediğiniz anlamına gelmez.
