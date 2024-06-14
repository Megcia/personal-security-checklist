
[![Harika](https://awesome.re/badge-flat2.svg)](https://github.com/zbetcheckin/Security_list)
[![PR'ler Welcome](https://img.shields.io/badge/PR'ler-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Lisans](https://img.shields.io/badge/LİSANS-CC_BY_4.0-00a2ff?&style=flat-square)](https://creativecommons.org/licenses/by/4.0/)
[![Katkıda Bulunanlar](https://img.shields.io/github/contributors/lissy93/personal-security-checklist?color=%23ffa900&style=flat-square)](https://github.com/Lissy93/personal-security-checklist/graphs/contributors)

<p align="center"><img src="https://i.ibb.co/rGQK71g/personal-security-checklist-6.png" /></p>

*<p align="center">Dijital güvenliğinizi ve gizliliğinizi korumanın ipuçlarını içeren özenle hazırlanmış bir kontrol listesi.</p>*

### İçindekiler

[<img src="https://i.ibb.co/XbyGTrP/1-authentication-2-36x36.png" width="28" height="28" /> Kimlik Doğrulama](#kimlik-doğrulama)<br>
[<img src="https://i.ibb.co/8KMrdbX/2-internet-36x36.png" width="28" height="28" /> Web'de Gezinme](#webde-gezinme)<br>
[<img src="https://i.ibb.co/7NrXW3L/5-email-36x36.png" width="28" height="28" /> E-posta](#e-posta)<br>
[<img src="https://i.ibb.co/DrWJBT9/13-messaging-36x36.png" width="28" height="28" /> Güvenli Mesajlaşma](#güvenli-mesajlaşma)<br>
[<img src="https://i.ibb.co/GFYyXMd/6-social-media-36x36.png" width="28" height="28" /> Sosyal Medya](#sosyal-medya)<br>
[<img src="https://i.ibb.co/0VTZQpH/3-networking-36x36.png" width="28" height="28" /> Ağlar](#ağlar)<br>
[<img src="https://i.ibb.co/F3WwqsV/7-phones-36x36.png" width="28" height="28" /> Mobil Cihazlar](#mobil-cihazlar)<br>
[<img src="https://i.ibb.co/ZftcgJq/8-computers-36x36.png" width="28" height="28" /> Kişisel Bilgisayarlar](#kişisel-bilgisayarlar)<br>
[<img src="https://i.ibb.co/b2S9372/9-smart-home-36x36.png" width="28" height="28" /> Akıllı Ev](#akıllı-ev)<br>
[<img src="https://i.ibb.co/4JTqL5y/12-finance-36x36.png" width="28" height="28" /> Kişisel Finans](#kişisel-finans)<br>
[<img src="https://i.ibb.co/KVPV1Lk/10-human-36x36.png" width="28" height="28" /> İnsan Faktörü](#duyarlı-bilgisayar)<br>
[<img src="https://i.ibb.co/9NbhBww/11-physical-36x36.png" width="28" height="28" /> Fiziksel Güvenlik](#fiziksel-güvenlik)<br>

Çok mu uzun? 🦒 O zaman [TLDR sürümüne](https://github.com/Lissy93/personal-security-checklist/blob/HEAD/articles/2_TLDR_Short_List.md) göz atın.

Gizliliğe saygı duyan yazılımların listesi için [Harika-Gizlilik](https://github.com/lissy93/awesome-privacy)'e göz atın.

Bu depodan bir ayna [codeberg.org/alicia/personal-security-checklist](https://codeberg.org/alicia/personal-security-checklist) mevcuttur.

---

<!-- checklist-start -->
## Kimlik Doğrulama

Verizon raporuna göre ([bu Verizon raporu](http://www.verizonenterprise.com/resources/reports/rp_dbir-2016-executive-summary_xg_en.pdf)), bildirilen veri ihlallerinin çoğu zayıf, varsayılan veya çalınan şifrelerin kullanımından kaynaklanmaktadır. Uzun, güçlü ve benzersiz şifreler kullanın, bunları güvenli bir şifre yöneticisinde yönetin, iki faktörlü kimlik doğrulamayı etkinleştirin, ihlalleri takip edin ve hesaplarınıza giriş yaparken dikkatli olun.

**Güvenlik** | **Öncelik** | **Ayrıntılar ve İpuçları**
--- | --- | ---
**Güçlü Şifre Kullanın** | Temel | Şifreniz çok kısa ise veya sözlük kelimeleri, yerler veya isimler içeriyorsa, bu kolayca kaba kuvvet saldırısıyla kırılabilir veya biri tarafından tahmin edilebilir. Güçlü bir şifre oluşturmanın en kolay yolu, uzun yapmaktır (12+ karakter)- bir 'parola cümlesi' kullanmayı düşünün, birçok kelimenin bir araya gelmesiyle oluşturulur. Alternatif olarak, uzun, güçlü rastgele şifre oluşturmak için bir şifre oluşturucu kullanabilirsiniz. Yaygın şifrelerin ne kadar hızlı kırılabileceğini görmek için [HowSecureIsMyPassword.net](https://howsecureismypassword.net)'i deneyin. Güçlü şifreler oluşturmak hakkında daha fazla bilgi için: [securityinabox.org](https://securityinabox.org/en/passwords/passwords-and-2fa/)
**Şifreleri Tekrar Kullanmayın** | Temel | Birisi bir şifreyi tekrar kullanırsa ve bu şifre kullandıkları bir site sızdırırsa, bir suçlu diğer hesaplarına izinsiz erişim sağlayabilir. Bu genellikle büyük ölçekli otomatik giriş istekleriyle yapılır ve "Credential Stuffing" olarak adlandırılır. Maalesef bu çok yaygındır, ancak korunması çok basittir- çevrimiçi hesaplarınızın her biri için farklı bir şifre kullanın.
**Güvenli Şifre Yöneticisi Kullanın** | Temel | Çoğu insan için yüzlerce güçlü ve benzersiz şifreyi hatırlamak neredeyse imkansız olacaktır. Şifre yöneticisi, giriş kimlik bilgilerinizi oluşturan, saklayan ve otomatik dolduran bir uygulamadır. Tüm şifreleriniz, 1 ana şifre karşısında şifrelenir (bu şifreyi hatırlamanız gerekir ve çok güçlü olmalıdır). Çoğu şifre yöneticisi, tarayıcı uzantıları ve mobil uygulamalarıyla gelir, bu nedenle hangi cihazda olursanız olun, şifreleriniz otomatik olarak doldurulabilir. İyi bir seçenek [Bitwarden](https://awesome-privacy.xyz/essentials/password-managers/bitwarden) veya [Önerilen Şifre Yöneticileri](https://awesome-privacy.xyz/essentials/password-managers) olarak gösterilebilir.
**Şifre Paylaşımından Kaçının** | Temel | Başka bir kişiyle bir hesaba erişim paylaşmanız gerekebilecek zamanlar olabilir, ancak genellikle bunu yapmaktan kaçının çünkü hesabın komprome olmasını kolaylaştırır. Bir şifre paylaşmanız gerekiyorsa örneğin bir ekip çalışmasında ortak bir hesapla çalışırken, bunu şifre yöneticisinin içine entegre edilmiş özellikler aracılığıyla yapmalısınız.
**2-Faktörlü Kimlik Doğrulamayı Etkinleştirin** | Temel | 2FA, giriş yapmak için bir şeyi bildiğiniz (bir şifre) ve bir şeye sahip olduğunuz (örneğin telefonunuzdaki bir kod) sağlamanız gereken yerdir. Bu, birinin şifrenizi (örneğin, phishing, kötü amaçlı yazılım veya bir veri ihlali yoluyla) aldığı durumda, hesabınıza giremeyeceği anlamına gelir. Başlamak çok kolaydır, telefonunuza [bir kimlik doğrulama uygulaması](https://github.com/Lissy93/awesome-privacy#2-factor-authentication) indirin ve ardından hesap güvenlik ayarlarına giderek 2FA'yı etkinleştirmek için adımları izleyin. Bir sonraki oturumunuzda yeni bir cihazda oturum açtığınızda, telefonunuzdaki uygulamada görünen kodu girmeniz istenecektir (internet olmadan çalışır ve kod genellikle her 30 saniyede bir değişir).
**Yedek Kodları Güvende Tutun** | Temel | Çoklu faktörlü kimlik doğrulamayı etkinleştirdiğinizde, 2FA yönteminiz kaybolduğunda, bozulduğunda veya kullanılamadığında kullanabileceğiniz birkaç kod verilir. Bu kodları kaybetmemek veya izinsiz erişimi önlemek için güvenli bir yerde saklayın. Bunları kağıt üzerinde veya diskte güvenli bir yerde (örneğin çevrimdışı depolama veya şifreli bir dosya/sürücü içinde) saklamalısınız. Bu kodları Şifre Yöneticinizde saklamayın, çünkü 2FA kaynakları ve şifreler ayrı tutulmalıdır.
**Sızıntı Bildirimlerine Kaydolun** | İsteğe Bağlı | Bir web sitesi önemli bir veri ihlali yaşadıktan sonra, sızan veriler genellikle internete düşer. Birkaç web sitesi, e-posta adresinizi aratarak sizin bunların listelerinde olup olmadığını kontrol etmenize izin verir. [Firefox Monitor](https://monitor.firefox.com), [Have I been pwned](https://haveibeenpwned.com) ve [DeHashed](https://dehashed.com), e-posta adresiniz yeni veri setlerinde görünürse sizi bilgilendirme konusunda izleme sağlar. Bu bilgiyi olabildiğince çabuk öğrenmek, etkilenen hesaplar için şifrelerinizi değiştirebilmeniz açısından faydalıdır. [Have I been pwned](https://awesome-privacy.xyz/security-tools/online-tools/have-i-been-pwned), alan genelinde bildirimler de sağlar, böylece herhangi bir e-posta adresi için uygundur (anonim yönlendirme için [gerekli olanların](https://github.com/Lissy93/awesome-privacy#anonymous-mail-forwarding) dışında).
**Şifrenizi/ PIN kodunuzu Korumaya Alın** | İsteğe Bağlı | Kamuya açık yerlerde şifrenizi yazarken, doğrudan bir CCTV kamerasının hattında olmadığınızdan ve omuzunuzun üstünden gören kimse olmadığından emin olun. Yazarken şifrenizi veya pin kodunuzu kapatın ve ekranda hiçbir düz metin şifresi göstermeyin.
**Kritik Şifreleri Düzenli Olarak Güncelleyin** | İsteğe Bağlı | Veritabanı sızıntıları ve ihlaller yaygındır ve muhtemelen şifrelerinizden bazıları zaten internet üzerinde bir yerlerde bulunmaktadır. Güvenlik açısından kritik hesapların şifrelerini zaman zaman güncellemek, bu durumu hafifletmeye yardımcı olabilir. Ancak, tüm şifreleriniz uzun, güçlü ve benzersizse, bunu çok sık yapmanıza gerek yoktur - yılda bir kez yeterli olacaktır.
**Tarayıcıda Şifrenizi Kaydetmeyin** | İsteğe Bağlı | Modern tarayıcılar genellikle giriş yaptığınızda kimlik bilgilerinizi kaydetme seçeneği sunar. Bunun yerine şifrelerinizi (ve otomatik doldurma işlevini) yönetmek için özel bir şifre yöneticisi kullanın. Tarayıcıda kaydedilen şifreler her zaman şifrelenmediği için hesaplarınıza erişim sağlanabilir.
**Başkasının Cihazında Oturum Açmaktan Kaçının** | İsteğe Bağlı | Başka birinin bilgisayarına oturum açmaktan kaçının, çünkü sistemlerinin temiz olup olmadığını asla bilemezsiniz. Kamu bilgisayarlarından özellikle kaçının, çünkü burada kötü amaçlı yazılım ve izleme daha yaygındır. Başka birinin cihazını kullanırken tarayıcının gizli/incognito modunda olduğundan emin olun (Ctrl+Shift+N / Cmd+Shift+N). Bu, tarayıcının kimlik bilgilerinizi, çerezlerinizi ve gezinti geçmişinizi kaydetmemesini sağlar.
**Şifre İpuçlarından Kaçının** | İsteğe Bağlı | Bazı siteler şifre ipuçları belirlemenize izin verir. İpucu sorulması zorunlu olduğunda rastgele cevaplar kullanın ve bunları şifre yöneticinize kaydedin (`İlk okulunuzun adı: 6D-02-8B-!a-E8-8F-81`).
**Çevrimiçi Güvenlik Sorularına Gerçek Cevap Vermeyin** | İsteğe Bağlı | Bir site güvenlik soruları (doğum yeri, anne kızlık soyadı, ilk araba vb.) soruyorsa gerçek cevaplar vermeyin. Bu bilgilerin çalınması online veya sosyal mühendislik yoluyla oldukça kolaydır. Bunun yerine hayali bir cevap oluşturun ve şifre yöneticinize kaydedin. Gerçek kelimeler kullanmak, rasgele karakterlerden daha iyidir.
**4 Haneli PIN Kullanmayın** | İsteğe Bağlı | Akıllı telefonunuzu veya bilgisayarınıza erişim için kısa bir PIN kullanmayın. Bunun yerine metin tabanlı bir şifre veya çok daha uzun bir PIN kullanın. Sayısal parolalar kolayca kırılabilir (4 haneli bir PIN'in 10.000 kombinasyonu varken, 4 karakterli bir alfa-numerik kodun 7,4 milyon kombinasyonu vardır).
**SMS Kullanımından Kaçının 2FA için** | İsteğe Bağlı | Çoklu faktör kimlik doğrulamayı etkinleştirirken, destekleniyorsa uygulama tabanlı kodlar veya donanım jetonları tercih edin. SMS, [SIM takası](https://www.maketecheasier.com/sim-card-hijacking) ve [sinyalizasyon saldırılarına](https://secure-voice.com/ss7_attacks) karşı hassastır. Ayrıca telefon numaranızın ne kadar güvenli bir şekilde saklanacağı veya başka hangi amaçlarla kullanılacağı garanti edilemez. Pratik bir bakış açısından, SMS yalnızca sinyal olduğunda çalışır ve yavaş olabilir. Bir web sitesi veya hizmet, kurtarma için bir SMS numarası kullanımını gerektiriyorsa, bu durumlar için sadece hesap kurtarma için kullanılan ikinci bir ön ödemeli telefon numarası satın almayı düşünün.
**PM'nizi OTP üretmek için kullanmaktan kaçının** | Gelişmiş | Birçok şifre yöneticisi aynı zamanda 2FA kodları üretebilir. Ancak, ana şifre yöneticinizi 2FA doğrulayıcısı olarak kullanmamak en iyisidir, çünkü bu durumda bir kez komprome edilirse tek bir başarısız nokta olabilir. Bunun yerine telefonunuzda veya dizüstü bilgisayarınızda özel bir [doğrulayıcı uygulama](https://github.com/Lissy93/awesome-privacy#2-factor-authentication) kullanın.
**Yüz Tanıma Kullanımından Kaçının** | Gelişmiş | Çoğu telefon ve dizüstü bilgisayar, kamerayı kullanarak yüz tanıma kimlik doğrulama özelliği sunar, bir görüntünüzü kaydedilmiş bir hash ile karşılaştırır. Çok pratik olabilir, ancak [aldatmanın](https://www.forbes.com/sites/jvchamary/2017/09/18/security-apple-face-id-iphone-x/) ve dijital fotoğraflar ile CCTV görüntülerinden yeniden yapmanın birçok yolu vardır. Şifrenizden farklı olarak, internet üzerinde yüzünüze ait fotoğraflar ve gözetim kameraları tarafından kaydedilen videolar olabilir.
**Keylogger'lara Dikkat Edin** | Gelişmiş | Bir [donanım keylogger](https://en.wikipedia.org/wiki/Hardware_keylogger), klavye ve USB bağlantısı arasına yerleştirilen fiziksel bir cihazdır, tüm tuş vuruşlarını yakalar ve bazen verileri uzak bir sunucuya aktarır. Bu, bir hacker'ın şifreler dahil her şeye erişmesini sağlar. Korunmanın en iyi yolu, PC'nizden uzak kaldıktan sonra USB bağlantınızı kontrol etmektir. Ayrıca, klavye kasasına yerleştirilmiş keylogger'ların varlığını kontrol edin ve işe kendi klavyenizi getirmeyi düşünün. Sanal klavyede yazılan veriler, panodan yapıştırılan veya şifre yöneticisi tarafından otomatik doldurulan veriler, donanım keylogger tarafından yakalanamaz.
**Donanım Jetonu Düşünün** | Gelişmiş | Bir U2F/ FIDO2 güvenlik anahtarı, çevrimiçi bir hizmete giriş yaparken kimliğinizi doğrulamak için takılan USB (veya NFC) bir cihazdır ve otantikatörden OTP girmek yerine kullanılır. [SoloKey](https://solokeys.com) ve [NitroKey](https://www.nitrokey.com) bu tür anahtarların örnekleridir. Tarayıcı doğrudan cihazla iletişim kurduğundan, hangi ana bilgisayarın kimlik doğrulama isteği yaptığını yanıltamaz, çünkü TLS sertifikası kontrol edilir. FIDO U2F jetonlarının güvenliği hakkında [bu yazı](https://security.stackexchange.com/a/71704) iyi bir açıklamadır. Tabii ki, fiziksel anahtarı güvenli bir yerde saklamak veya kişinizde tutmak önemlidir. Bazı çevrimiçi hesaplar, birden fazla 2FA yöntemi etkinleştirmenize izin verir.
**Çevrimdışı Şifre Yöneticisi Düşünün** | Gelişmiş | Artan güvenlik için, şifrelerinizi şifreli olarak saklayan çevrimdışı bir şifre yöneticisi size verileriniz üzerinde tam kontrol sağlar. [KeePass](https://awesome-privacy.xyz/essentials/password-managers/keepass) popüler bir seçimdir ve [eklentiler](https://[KeePass](https://awesome-privacy.xyz/essentials/password-managers/keepass).info/plugins.html) ve ek uyumluluk ve işlevsellik sağlayan topluluk sürümleri bulunmaktadır. Popüler istemciler arasında [KeePassXC](https://keepassxc.org) (masaüstü), [KeePassDX](https://www.keepassdx.com) (Android) ve [StrongBox](https://apps.apple.com/us/app/strongbox-password-safe/id897283731) (iOS) bulunmaktadır. Dezavantajı bazıları için biraz daha az kullanışlı olabilir ve yedeklemeyi ve güvenli bir şekilde saklamayı sizin yapmanız gerekebilir.
**Benzersiz Kullanıcı Adları Düşünün** | Gelişmiş | Her hesap için farklı şifreler kullanmak iyi bir ilk adımdır, ancak giriş yapmak için benzersiz bir kullanıcı adı, e-posta veya telefon numarası kullanırsanız, yetkisiz erişim kazanmaya çalışanlar için çok daha zor olacaktır. Birden fazla e-posta için en kolay yöntem, anonim posta yönlendirmesi için otomatik olarak oluşturulan takma adları kullanmaktır. Bu, [herhangi]@siteniz.com şeklinde gelen iletilerin posta kutunuza ulaşmasını sağlar, böylece her hesap için farklı bir e-posta kullanabilirsiniz (bkz. [Mail Alias Sağlayıcıları](https://github.com/Lissy93/awesome-privacy#anonymous-mail-forwarding)). Kullanıcı adları daha kolaydır, çünkü şifre yöneticinizi kullanarak bunları oluşturabilir, saklayabilir ve otomatik olarak doldurabilirsiniz. Sanal telefon numaraları VOIP sağlayıcınız aracılığıyla oluşturulabilir.

### Tavsiye Edilen Yazılımlar
- [Şifre Yöneticileri](https://github.com/Lissy93/awesome-privacy#password-managers)
- [İki Faktörlü Kimlik Doğrulama](https://github.com/Lissy93/awesome-privacy#2-factor-authentication)


## Web Tarama

İnternet üzerindeki çoğu web sitesi, genellikle kullanıcılarının davranışları ve tercihlerini anlamak için bir takip yöntemi kullanır. Bu veri oldukça detaylı olabilir ve şirketler, hükümetler ve fikri mülkiyet hırsızları için son derece değerlidir. Veri sızıntıları ve sızıntıları yaygındır ve kullanıcıların web etkinliklerini tanımlamak genellikle basit bir görevdir.

İzlemenin iki temel yöntemi vardır: durumlu (çerez tabanlı) ve durumsuz (parmak izi tabanlı). Çerezler, tarayıcınızda depolanan ve sizi tanımlamak için kullanılan benzersiz bir kimlikle küçük bilgilerdir. Tarayıcı parmak izi, kullanıcıları nereye giderlerse gitsinler tanımlamak ve izlemek için son derece doğru bir yöntemdir. Toplanan bilgiler oldukça kapsamlı olabilir ve genellikle tarayıcı ayrıntıları, işletim sistemi, ekran çözünürlüğü, desteklenen yazı tipleri, eklentiler, zaman dilimi, dil ve yazı tipi tercihleri ve hatta donanım yapılandırmalarını içerir.

Bu bölüm, tehditlerden daha iyi korunmak, çevrimiçi izlemeyi en aza indirmek ve gizliliği artırmak için atabileceğiniz adımları açıklar.

**Güvenlik** | **Öncelik** | **Detaylar ve İpuçları**
--- | --- | ---
**Reklamları Engelle** | Temel | Bir reklam engelleyici kullanmak, reklamların uyguladığı izleyicileri engelleyerek gizliliğinizi artırmanıza yardımcı olabilir. [uBlock Origin](https://awesome-privacy.xyz/networking/ad-blockers/ublock-origin), Raymond Hill tarafından geliştirilen çok verimli ve açık kaynaklı bir tarayıcı eklentisidir. Üçüncü taraf reklamlar bir web sayfasında görüntülendiğinde, sizi takip etme yeteneğine sahiptirler ve kişisel bilgilerinizi ve alışkanlıklarınızı toplayabilirler, bu bilgiler daha sonra satılabilir veya size daha hedeflenmiş reklamlar göstermek için kullanılabilir, ve bazı reklamlar sadece kötü amaçlı veya sahte. Reklamları engellemek ayrıca sayfaların daha hızlı yüklenmesini, daha az veri kullanılmasını ve daha düzenli bir deneyim sunulmasını sağlar.
**Web Sitesinin Güvenilir Olduğundan Emin Olun** | Temel | Açıkça duyulması gereken bir şey olabilir ancak herhangi bir çevrimiçi hesaba giriş yaparken, URL'nin doğru olduğundan emin olun. Sık ziyaret edilen siteleri yer imlerinizde saklamak, URL'nin kolayca bulunmasını sağlamanın iyi bir yoludur. Yeni web sitelerini ziyaret ederken, güvenli olmadığına dair yaygın işaretlere bakın: Tarayıcı uyarıları, yönlendirmeler, site içi istenmeyen postalama ve açılır pencereler. Şüpheliyseniz bir web sitesini kontrol etmek için araçlar kullanabilirsiniz, örneğin: [Virus Total](https://awesome-privacy.xyz/security-tools/online-tools/virus-total), [IsLegitSite](https://www.islegitsite.com), [Google Güvenli Tarama Durumu](https://transparencyreport.google.com/safe-browsing/search).
**Tarayıcı Zararlı Yazılımlarına Dikkat Edin** | Temel | Sisteminiz veya tarayıcınız, casus yazılımlar, madenciler, tarayıcı yönlendirmeleri, kötü amaçlı yönlendirmeler, reklam yazılımları vb. ile tehlikeye girebilir. Genellikle korunabilirsiniz: açılan pencereleri görmezden gelmek, tıkladığınıza dikkat etmek, tarayıcınız tehlikeli olabileceğini uyarırsa bir web sitesine devam etmemek. Tarayıcı zararlı yazılımlarının yaygın işaretleri arasında: varsayılan arama motoru veya ana sayfa değiştirilmiş, araç çubukları, tanıdık olmayan uzantılar veya simgeler, önemli ölçüde daha fazla reklam, hatalar ve normalden çok daha yavaş yüklenen sayfalar bulunur. Heimdal'ın bu makaleleri tarayıcı zararlı yazılımlarının [işaretlerini açıklar](https://heimdalsecurity.com/blog/warning-signs-operating-system-infected-malware), [tarayıcıların nasıl enfekte olduğunu anlatır](https://heimdalsecurity.com/blog/practical-online-protection-where-malware-hides) ve [tarayıcı zararlı yazılımlarını nasıl kaldıracağınızı açıklar](https://heimdalsecurity.com/blog/malware-removal).
**Gizliliği Önemseyen Bir Tarayıcı Kullanın** | Temel | [Firefox](https://awesome-privacy.xyz/essentials/browsers/firefox) (bazı ayarlamalarla) ve [Brave](https://awesome-privacy.xyz/essentials/browsers/brave-browser), güvenli ve gizliliği önemseyen tarayıcılardır. Her ikisi de hızlı, açık kaynaklı, kullanıcı dostu ve tüm büyük işletim sistemlerinde mevcuttur. Tarayıcınız çevrimiçi yaptığınız her şeye erişim sağlar, bu yüzden mümkünse Google Chrome, Edge ve Safari gibi (doğru yapılandırma olmadan) bu üç tarayıcıdan kaçının, çünkü hepsi kullanım verisi toplar, ana sunucuya bilgi gönderir ve yaygın izleme yapılmasına izin verir. Firefox, en iyi güvenliği sağlamak için bazı değişiklikler gerektirir, örneğin - [arkenfox](https://github.com/arkenfox/user.js/wiki) veya [12byte](https://12bytes.org/firefox-configuration-guide-for-privacy-freaks-and-performance-buffs/)'in kullanıcı.js yapılandırmaları. Daha fazlası için: [Gizlilik Tarayıcıları](https://github.com/Lissy93/awesome-privacy#browsers).
**Özel Bir Arama Motoru Kullanın** | Temel | Gizliliği koruyan, izleme yapmayan bir arama motoru kullanmak, arama terimlerinizin kaydedilmemesi veya sizin aleyhinize kullanılmaması riskini azaltacaktır. [DuckDuckGo](https://awesome-privacy.xyz/essentials/search-engines/duckduckgo) veya [Qwant](https://awesome-privacy.xyz/essentials/search-engines/qwant) gibi arama motorlarını düşünebilirsiniz. Google, son derece girişimsel [izleme politikaları](https://hackernoon.com/data-privacy-concerns-with-google-b946f2b7afea) uygulamakta ve [taraflı arama sonuçları](https://www.businessinsider.com/evidence-that-google-search-results-are-biased-2014-10) gösterme geçmişine sahiptir. Bu nedenle Google, Bing, Baidu, Yahoo ve Yandex gibi arama motorları, gizliliğinizi korumak isteyenler için uygun değildir. [Tarayıcınızın varsayılan arama motorunu](https://duckduckgo.com/install) gizliliği önemseyen bir arama motoruna güncellemek tavsiye edilir.
**Gereksiz Tarayıcı Eklentilerini Kaldırın** | Temel | Eklentiler tarayıcıda yaptığınız her şeyi görebilir, kaydedebilir veya değiştirebilir ve bazı masum görünümlü tarayıcı uygulamalarının kötü niyetli amaçları olabilir. Web siteleri yüklediğiniz eklentileri görebilir ve bunu parmak izinizi daha doğru bir şekilde belirlemek veya sizi izlemek için kullanabilir. Hem [Firefox](https://awesome-privacy.xyz/essentials/browsers/firefox) hem de Chrome web mağazaları, bir eklentinin yüklemeden önce hangi izinlere/erişim haklarına ihtiyaç duyduğunu kontrol etmenizi sağlar. İncelemeleri kontrol edin. Gerçekten ihtiyacınız olan eklentileri yükleyin ve uzun süredir kullanmadığınız eklentileri kaldırın.
**Tarayıcıyı Güncel Tutun** | Temel | Tarayıcı güvenlik açıkları sürekli olarak [keşfedilmekte](https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=browser) ve yamalanmaktadır, bu yüzden sıfır gün saldırısını önlemek için güncel tutmak önemlidir. [Tarayıcı sürümünüzü buradan kontrol edebilirsiniz](https://www.whatismybrowser.com/), veya güncelleme yapmak için [bu kılavuzu](https://www.whatismybrowser.com/guides/how-to-update-your-browser/) takip edebilirsiniz. Bazı tarayıcılar en son kararlı sürüme otomatik olarak güncellenecektir.
**HTTPS Kontrol Edin** | Temel | Eğer bilgilerinizi HTTPS olmayan bir web sitesine girerseniz, bu veriler şifrelenmeden taşınır ve dolayısıyla yakalayan herkes tarafından okunabilir. Herhangi bir veri HTTPS olmayan bir web sitesine girmeyin, ancak yeşil kilit size yanlış bir güvenlik hissi vermesin, bir web sitesinin SSL sertifikasına sahip olması, onun meşru veya güvenilir olduğu anlamına gelmez. [HTTPS-Everywhere](https://www.eff.org/https-everywhere) (EFF tarafından geliştirilmiştir) eskiden bir tarayıcı eklentisiydi ve otomatik olarak web sitelerinde HTTPS'yi etkinleştirirdi, ancak 2022 itibariyle kullanımdan kaldırılmıştır. Onların [duyuru makalesinde](https://www.eff.org/), EFF çoğu tarayıcının artık bu tür korumaları entegre ettiğini açıklamaktadır. Ayrıca, [Firefox](https://awesome-privacy.xyz/essentials/browsers/firefox), Chrome, Edge ve Safari tarayıcıları için HTTPS güvenli korumalarını etkinleştirmek için talimatlar sağlar.
**DNS-over-HTTPS Kullanın** | Temel | Geleneksel DNS herkesin görebileceği düz metin talepleri yapar. Araya giren kişilerin ve orta adam saldırılarıyla DNS verilerinin dinlenmesine ve manipüle edilmesine izin verir. DNS-over-HTTPS ise DNS çözümlemesini HTTPS protokolü üzerinden yapar, bu da sizin ve DNS çözümleyiciniz arasındaki verilerin şifrelenmesi anlamına gelir. Popüler bir seçenek [CloudFlare](https://awesome-privacy.xyz/networking/dns-providers/cloudflare)'in [1.1.1.1](https://awesome-privacy.xyz/security-tools/mobile-apps/1.1.1.1) servisidir veya sağlayıcıları karşılaştırabilirsiniz - bu tarayıcıda etkinleştirmesi basittir. DoH'ın kendi sorunları olduğunu unutmayın, çoğunlukla web filtreleme engellemektedir.
**Çoklu [Oturum](https://awesome-privacy.xyz/communication/encrypted-messaging/session) Konteynerleri** | Temel | Bölme, tarayıcınızda farklı alanları birbirinden ayırmak için gerçekten önemlidir. Örneğin, iş, genel gezinme, sosyal medya, online alışveriş vb. için farklı profiller kullanmak, veri aracılarının size geri izlemeler yapabileceği bağlantı sayısını azaltacaktır. Bu amaçla [Firefox Konteynerlerini](https://awesome-privacy.xyz/security-tools/browser-extensions/firefox-multi-account-containers) kullanabilirsiniz. Alternatif olarak, farklı görevler için farklı tarayıcılar kullanabilirsiniz ([Brave](https://awesome-privacy.xyz/essentials/browsers/brave-browser), [Firefox](https://awesome-privacy.xyz/essentials/browsers/firefox), [Tor](https://awesome-privacy.xyz/networking/mix-networks/tor) vb.).
**Gizli Mod Kullanın** | Temel | Başka birinin makinesini kullanırken, özel/gizli bir oturumda olduğunuzdan emin olun. Bu tarayıcı geçmişi, çerezler ve bazı verilerin kaydedilmesini önler, ancak tam koruma sağlamaz - yine de takip edilebilirsiniz.
**Tarayıcı Parmak İzi'nizi Anlayın** | Temel | Tarayıcı Parmak İzi, cihazınızın bilgilerine dayanarak sizi tanımlayan son derece doğru bir izleme yöntemidir. Parmak izinizi amiunique.org adresinde görebilirsiniz. Amaç, mümkün olduğunca benzersiz olmamaktır.
**Çerezleri Yönetin** | Temel | Çerezleri düzenli olarak temizlemek, web sitelerinin sizi takip etmesini azaltmanıza yardımcı olacak adımlardan biridir. Çerezler ayrıca oturum belirtecinizi de saklayabilir, bu da yakalandığında kimlik bilgileri olmadan hesaplarınıza erişime izin verebilir. Bu riski azaltmak için sık sık çerezleri temizlemelisiniz.
**Üçüncü Taraf Çerezleri Engelleme** | Temel | Üçüncü taraf çerezleri, ziyaret ettiğiniz web sitesi dışındaki bir web sitesi tarafından cihazınıza yerleştirilen çerezlerdir. Bu, üçüncü bir tarafın mevcut oturumunuzdan veri toplayabilmesi nedeniyle gizlilik riski oluşturur. Bu rehber, üçüncü taraf çerezlerini nasıl devre dışı bırakabileceğinizi açıklıyor ve bunun çalışıp çalışmadığını buradan kontrol edebilirsiniz.
**Üçüncü Taraf İzleyicileri Engelleme** | Temel | İzleyicileri engellemek, web sitelerinin, reklamverenlerin, analitiklerin ve daha fazlasının arka planda sizi takip etmesini engellemeye yardımcı olacaktır. [Privacy Badger](https://awesome-privacy.xyz/security-tools/browser-extensions/privacy-badger), [DuckDuckGo Privacy Essentials](https://awesome-privacy.xyz/security-tools/browser-extensions/privacy-essentials), [uBlock Origin](https://awesome-privacy.xyz/networking/ad-blockers/ublock-origin) ve uMatrix (gelişmiş) tüm önemli tarayıcılar için mevcut olan çok etkili, açık kaynaklı izleyici engelleyicileridir.
**Yönlendirmelere Dikkat Edin** | İsteğe Bağlı | Bazı yönlendirmeler zararsızken, diğerleri (Doğrulanmamış yönlendirmeler gibi) balık avı saldırılarında kullanılır, bu kötü amaçlı bir bağlantıyı meşru gibi gösterir. Bir yönlendirme URL'si hakkında emin değilseniz, RedirectDetective gibi bir araçla nereye yönlendirildiğini kontrol edebilirsiniz.
**Tarayıcınıza Giriş Yapmayın** | İsteğe Bağlı | Birçok tarayıcı, geçmişi, yer imlerini ve diğer tarama verilerini cihazlar arasında senkronize etmek için oturum açmanıza izin verir. Bununla birlikte, bu yalnızca daha fazla veri toplanmasına izin vermekle kalmaz, aynı zamanda kişisel bilgilere kötü niyetli bir aktörün ulaşabileceği başka bir yol da sağlar.
**Öngörü Servislerini Yasaklayın** | İsteğe Bağlı | Bazı tarayıcılar, gerçek zamanlı arama sonuçları veya URL otomatik doldurma gibi öngörü hizmetlerine izin verir. Bu etkinleştirildiğinde, her tuşa basışınızda veri Google'a (veya varsayılan arama motorunuza) gönderilir, enter tuşuna basmadan önce.
**Web Sayfaları İçin G Translate Kullanmayın** | İsteğe Bağlı | Yabancı dilde yazılmış bir web sayfasını ziyaret ettiğinizde, Google Translate uzantısını yüklemeniz istenebilir. Google'ın tüm verileri (giriş alanları dahil) topladığını, mevcut kullanıcı ayrıntıları ile birlikte göz önünde bulundurun. Bunun yerine tarayıcınıza bağlı olmayan bir çeviri hizmeti kullanın.
**Web Bildirimlerini Devre Dışı Bırakın** | İsteğe Bağlı | Tarayıcı bildirimleri, suçluların sizi bağlantılarına tıklamaya teşvik etmek için yaygın olarak kullandığı bir yöntemdir, çünkü kaynağı kolayca sahtekarlık yapılabilir. Buna dikkat edin ve tarayıcı bildirimlerini devre dışı bırakma talimatları için bu makaleye bakın.
**Otomatik İndirmeleri Devre Dışı Bırakın** | İsteğe Bağlı | Sürükle-bırak indirmeler, zararlı dosyaları kullanıcının cihazına indirmenin yaygın bir yoludur. Bu, otomatik dosya indirmelerini devre dışı bırakarak azaltılabilir ve beklenmedik şekilde dosya indirmenizi isteyen web sitelerine dikkat edilmelidir.
**Sensörlere Erişimi Engelle** | İsteğe Bağlı | Mobil web siteleri, cihaz sensörlerinize izin istemeden erişebilir. Bu izni bir kez tarayıcınıza verirseniz, tüm web siteleri bu yetenekleri izin veya bildirim olmaksızın kullanabilir.
**Konuma İzin Verme** | İsteğe Bağlı | Konum Servisleri, sitelerin deneyiminizi iyileştirmek için fiziksel konumunuzu istemesine izin verir. Bu ayarlarında devre dışı bırakılmalıdır. Yaklaşık konumunuzu belirleme diğer yöntemlerin hala bulunduğunu unutmayın.
**Kamera/Mikrofon Erişimini Engelle** | İsteğe Bağlı | Tarayıcı ayarlarını kontrol ederek, web sitelerinin web kamerası veya mikrofona erişim sağlamasını engelleyin. Ayrıca, web kamerası kapakları veya mikrofon blokerleri gibi fiziksel koruma yöntemlerini kullanmanız faydalı olabilir.
**Tarayıcıda Parola Kaydetmeyi Devre Dışı Bırakın** | İsteğe Bağlı | Tarayıcınızın kullanıcı adı ve parolaları saklamasına izin vermeyin. Bu bilgiler kolayca görüntülenebilir veya erişilebilir. Bunun yerine bir parola yöneticisi kullanın.
**Tarayıcı Otomatik Doldurmayı Devre Dışı Bırakın** | İsteğe Bağlı | Gizli veya kişisel bilgiler için otomatik doldurma özelliğini kapatın. Bu özellik, tarayıcınızın herhangi bir şekilde tehlikeye girmesi durumunda zararlı olabilir. Bunun yerine parola yöneticinizin Notlar özelliğini düşünebilirsiniz.
**Exfil Saldırısından Korunun** | İsteğe Bağlı | CSS Exfil saldırısı, yalnızca saf CSS ile kimlik bilgileri ve diğer hassas bilgilerin yakalanabileceği bir yöntemdir. [CSS Exfil Protection](https://awesome-privacy.xyz/security-tools/browser-extensions/css-exfil-protection) eklentisi ile korunabilirsiniz.
**ActiveX'i Devre Dışı Bırakın** | İsteğe Bağlı | ActiveX, Microsoft IE'ye yerleşik olan ve varsayılan olarak etkinleştirilmiş bir tarayıcı eklentisi API'sidir. Artık pek kullanılmıyor olsa da, eklentilere yoğun erişim izni verdiği için tehlikeli olabilir. Bu nedenle devre dışı bırakmanız önerilir.
**WebRTC'yi Devre Dışı Bırakın** | İsteğe Bağlı | WebRTC, tarayıcıdan yüksek kaliteli ses/video iletişimi ve kişiden kişiye dosya paylaşımı sağlar. Ancak gizlilik açığı oluşturabilir. Daha fazla bilgi için bu kılavuza göz atabilirsiniz.
**HTML5 Canvas Kimliğini Sahteleyin** | İsteğe Bağlı | Canvas Fingerprinting, web sitelerinin kullanıcıları çok hassas bir şekilde tanımlayıp izlemelerine olanak tanır. Canvas-Fingerprint-Blocker eklentisini kullanarak kimliğinizi sahteleyebilir veya [Tor](https://awesome-privacy.xyz/networking/mix-networks/tor) kullanabilirsiniz.
**Kullanıcı Ajanını Sahteleyin** | İsteğe Bağlı | Kullanıcı ajanı, web sitesine kullandığınız cihazı, tarayıcıyı ve sürümü bildirir. Kullanıcı ajanını zaman zaman değiştirmek, daha az benzersiz olmanın küçük bir adımıdır.
**DNT'yi Göz Ardı Edin** | İsteğe Bağlı | Do Not Track (DNT) özelliğini etkinleştirmenin çok sınırlı etkisi vardır, çünkü birçok web sitesi bunu saygı duymaz veya takip etmez. Nadiren kullanıldığı için imzanıza eklenerek sizi daha benzersiz hale getirebilir.
**HSTS Takibini Önleyin** | İsteğe Bağlı | HSTS, web sitelerini güvence altına almaya yardımcı olmak için tasarlandı, ancak gizlilik endişeleri, site işletmecilerinin süper çerezler yerleştirmelerine izin verdiği için ortaya çıkmıştır. Chromium tabanlı tarayıcılarda chrome://net-internals/#hsts adresini ziyaret ederek devre dışı bırakılabilir.
**Otomatik Tarayıcı Bağlantılarını Engelle** | İsteğe Bağlı | Tarayıcıyı kullanmadığınız zamanlarda bile, kullanım etkinliği, analizler ve teşhisler hakkında rapor vermek için ev arayabilir. Bunu biraz kapatmak isteyebilirsiniz, ayarlar aracılığıyla bu yapılabilir.
**1st-Party İzolasyonunu Etkinleştirin** | İsteğe Bağlı | [First Party Isolation](https://awesome-privacy.xyz/security-tools/browser-extensions/first-party-isolation) (Birinci Parti İzolasyonu), tüm tanımlayıcı kaynaklarının ve tarayıcı durumunun URL çubuğu etki alanı kullanılarak kapsanması anlamına gelir, bu takibi büyük ölçüde azaltabilir.
**URL'lerden Takip Parametrelerini Kaldırın** | Gelişmiş | Web siteleri genellikle tıkladığınız URL'lere ek GET parametreleri ekler, kaynak/önsezi gibi bilgileri belirlemek için. Bu izleme verilerini manuel olarak temizleyebilir veya [ClearURLs](https://awesome-privacy.xyz/security-tools/browser-extensions/clearurls) gibi bir eklenti kullanarak URL'lerden otomatik olarak kaldırabilirsiniz.
**İlk Başlangıç Güvenliği** | Gelişmiş | Bir web tarayıcısını yükledikten sonra ilk kez başlattığınızda (gizlilik ayarlarını yapılandırmadan önce), çoğu tarayıcı ev arama yapar. Bu nedenle, bir tarayıcıyı yükledikten sonra ilk olarak internet bağlantınızı devre dışı bırakmalı, daha sonra gizlilik seçeneklerini yapılandırmalısınız ve internet bağlantınızı tekrar etkinleştirmelisiniz.
**Tor Tarayıcısını Kullanın** | Gelişmiş | [Tor](https://awesome-privacy.xyz/networking/mix-networks/tor) Projesi, trafiğinizi birden fazla düğüm üzerinden şifreleyip yönlendirerek kullanıcıları dinlenmeye ve izlenmeye karşı koruyan bir tarayıcı sunar. Ana dezavantajları hız ve kullanıcı deneyimidir.
**JavaScript'i Devre Dışı Bırakın** | Gelişmiş | Birçok modern web uygulaması JavaScript tabanlı olduğundan, bunu devre dışı bırakmak gezinti deneyiminizi büyük ölçüde azaltacaktır. Ancak gerçekten sıkı bir gizlilik sağlamak istiyorsanız, saldırı yüzeyinizi gerçekten azaltacaktır.

### Tavsiye Edilen Yazılımlar
- [Gizlilik Odaklı Tarayıcılar](https://github.com/Lissy93/awesome-privacy#browsers)
- [Tarayıcı Eklentileri](https://github.com/Lissy93/awesome-privacy#browser-extensions)
- [Tarayıcı ve Yer İmleri Senkronizasyonu](https://github.com/Lissy93/awesome-privacy#browser-sync)


## E-posta

İlk e-postanın gönderilmesinin üzerinden neredeyse 50 yıl geçti, hala günlük hayatımızın önemli bir parçası ve yakın gelecekte de öyle olmaya devam edecek gibi görünüyor. Bu kadar güvendiğimiz bir altyapının temelde ne kadar güvensiz olduğu ise şaşırtıcı. E-posta ile ilgili dolandırıcılık [artışta](https://www.csoonline.com/article/3247670/email/email-security-in-2018.html), temel önlemleri almazsanız risk altında olabilirsiniz.

Eğer bir hacker e-postalarınıza erişirse, diğer hesaplarınızın (şifre sıfırlamaları aracılığıyla) tehlikeye girmesine yol açar, bu yüzden dijital güvenliğiniz için e-posta güvenliği çok önemlidir.

Ücretsiz e-posta hizmeti sunan büyük şirketler, kullanıcı gizliliğine saygı göstermedikleri için iyi bir üne sahip değiller: Gmail, kullanıcı e-postalarına [üçüncü taraflara tam erişim](https://www.wsj.com/articles/techs-dirty-secret-the-app-developers-sifting-through-your-gmail-1530544442) verdiği ve ayrıca [tüm alışverişlerinizi izlediği](https://www.cnbc.com/2019/05/17/google-gmail-tracks-purchase-history-how-to-delete-it.html) ortaya çıkarıldı. Yahoo da e-postaları [ABD istihbarat ajansları için](http://news.trust.org/item/20161004170601-99f8c) gerçek zamanlı taradı. Reklamverenlere [Yahoo ve AOL kullanıcılarının mesajlarına erişim](https://thenextweb.com/insider/2018/08/29/both-yahoo-and-aol-are-scanning-customer-emails-to-attract-advertisers) sağlandı, potansiyel müşterileri "bağlamsal satın alma sinyalleri ve geçmiş alımlarına göre tanımlamak ve segmentlemek" amacıyla.

**Güvenlik** | **Öncelik** | **Detaylar ve İpuçları**
--- | --- | ---
**Birden fazla e-posta adresi kullanın** | **Temel** | Güvenlikle ilgili iletişimler için farklı bir e-posta adresi kullanmayı düşünün. Bu bölümlendirme, veri ihlalinin neden olduğu zararı azaltabilir ve ayrıca kompromize edilmiş bir hesabı kurtarmayı kolaylaştırabilir.
**E-posta Adresinizi Özel Tutun** | **Temel** | Ana e-posta adresinizi genel olarak paylaşmayın, çünkü e-posta adresleri genellikle çoğu dolandırıcılık saldırısının başlangıç noktasıdır.
**Hesabınızı Güvende Tutun** | **Temel** | Uzun ve benzersiz bir şifre kullanın, iki faktörlü kimlik doğrulamayı etkinleştirin ve giriş yaparken dikkatli olun. E-posta hesabınız, bir saldırgan için diğer tüm çevrimiçi hesaplarınıza kolay bir giriş noktası sağlar.
**Uzaktan İçeriğin Otomatik Yüklenmesini Devre Dışı Bırakın** | **Temel** | E-posta mesajları, genellikle sunucudan otomatik olarak yüklenen resimler veya stil sayfaları gibi uzaktan içerik içerebilir. Bu özelliği devre dışı bırakmalısınız, çünkü IP adresinizi ve cihaz bilgilerinizi ortaya çıkarır ve sıklıkla takip amacıyla kullanılır. Daha fazla bilgi için [bu makaleyi](https://www.theverge.com/2019/7/3/20680903/email-pixel-trackers-how-to-stop-images-automatic-download) inceleyebilirsiniz.
**Düz Metin Kullanın** | **İsteğe Bağlı** | İnternet üzerindeki e-postaların iki ana türü vardır: düz metin ve HTML. Güvenlik ve gizlilik için düz metin mesajları güçlü bir şekilde tercih edilir, çünkü HTML mesajları genellikle bağlantılarda ve içe gömülü görüntülerde kimlik belirteçleri içerir, bu da kullanım ve kişisel veri toplanmasına neden olabilir. Ayrıca, e-posta istemcinizin HTML ayrıştırıcısını hedef alan uzaktan kod yürütme riskleri vardır, bu risk düz metin kullanıyorsanız söz konusu olmaz. Daha fazla bilgi ve e-posta sağlayıcınız için kurulum talimatları için [UsePlaintext.email](https://useplaintext.email/) adresine göz atabilirsiniz.
**E-posta Hesabınızı Üçüncü Taraf Uygulamalarla Bağlamayın** | **İsteğe Bağlı** | E-posta gelen kutunuza üçüncü taraf bir uygulamaya veya eklentiye tam erişim verirseniz, bu uygulama efektif olarak tüm e-postalarınıza ve içeriklerine engelsiz erişim sağlar, bu da önemli güvenlik ve gizlilik riskleri oluşturur.
**Hassas Verileri E-posta Yoluyla Paylaşmayın** | **İsteğe Bağlı** | E-postalar çok kolaylıkla ele geçirilebilir. Ayrıca, alıcınızın ortamının ne kadar güvenli olduğundan emin olamazsınız. Bu nedenle, şifrelenmemişse, e-posta ile hassas bilgi alışverişini güvenli kabul etmemelisiniz.
**Güvenli Bir E-posta Sağlayıcısına Geçmeyi Düşünün** | **İsteğe Bağlı** | [Forward Email](https://awesome-privacy.xyz/communication/encrypted-email/forward-email), [ProtonMail](https://awesome-privacy.xyz/communication/mail-forwarding/protonmail) ve [Tutanota](https://awesome-privacy.xyz/communication/encrypted-email/tuta) gibi güvenli ve saygın e-posta sağlayıcıları, uçtan uca şifreleme, tam gizlilik ve daha fazla güvenlik odaklı özellikler sunar. Tipik e-posta sağlayıcılarının aksine, tüm mesajlarınız şifreli olduğu için posta kutunuzu sadece siz okuyabilirsiniz.
**Akıllı Anahtar Kullanın** | **Gelişmiş** | OpenPGP ileri gizlilik korumasını desteklemez, bu da eğer sizin veya alıcının özel anahtarı çalınırsa, bu anahtarla şifrelenen tüm önceki mesajların ortaya çıkabileceği anlamına gelir. Bu nedenle, özel anahtarlarınızı güvende tutmak için büyük özen göstermelisiniz. Bunun bir yolu, mesajları imzalamak veya şifrelemek için USB Akıllı Anahtar kullanmaktır, bu sayede özel anahtarınız USB cihazından çıkmadan işlem yapabilirsiniz.
**E-posta Yönlendirme / Anonim İletim Kullanın** | **Gelişmiş** | E-posta yönlendirme, [my-domain.com](https://awesome-privacy.xyz/communication/encrypted-email/forward-email) gibi [herhangi bir şey]@ adresine gönderilen mesajların asıl gelen kutunuzda yer almasına izin verir. Bu size her hizmet için farklı, benzersiz bir e-posta adresi kullanma imkanı sağlar. Bu şekilde spam almaya başlarsanız, o aliase engelleyebilir ve hangi şirketin e-posta adresinizi sızdırdığını belirleyebilirsiniz.
**Alt Adresleme Kullanın** | **İsteğe Bağlı** | Alias kullanımının alternatifi olan alt adresleme, `+` simgesinden sonra gelen her şeyin posta iletimi sırasında atılması demektir. Bu size e-posta adresinizi paylaşan/ sızdıran kişiyi takip etme imkanı sağlar, ancak alias kullanımının aksine gerçek adresinizin açığa çıkmasını korumaz.
**Özel Alan Adı Kullanın** | **Gelişmiş** | Özel bir alan adı kullanmak, e-posta sağlayıcınız tarafından atanmış adreslere bağımlı olmadığınız anlamına gelir. Bu nedenle gelecekte sağlayıcınızı kolayca değiştirebilir ve hizmetin sonlandırılmasından endişe etmenize gerek kalmaz.
**Bir İstemciyle Senkronize Edin** | **Gelişmiş** | Plansız bir olay sırasında (örneğin, kesinti veya hesap kilitleme) geçici veya kalıcı olarak e-postalarınıza erişimi kaybetmemek için, Thunderbird IMAP üzerinden birden fazla hesaptan mesajları senkronize edebilir ve bunları birincil cihazınıza yerel olarak yedekleyebilir.
**E-posta İmzalarıyla Dikkatli Olun** | **Gelişmiş** | Mesajınızın alıcısının e-posta ortamının ne kadar güvenli olduğunu bilemezsiniz. Bazı uzantılar otomatik olarak mesajları tarar ve e-posta imzalarına dayalı olarak ayrıntılı bir kişi bilgi veritabanı oluşturur.
**Otomatik Yanıtlarla Dikkatli Olun** | **Gelişmiş** | Dışarıda olma otomatik yanıtları cevap vermede gecikme olacağını bildirmek için çok yararlıdır, ancak insanlar genellikle çok fazla bilgi ifşa eder - bu da sosyal mühendislik ve hedeflenen saldırılar için kullanılabilir.
**Doğru E-posta Protokolünü Seçin** | **Gelişmiş** | Güncellenmemiş protokollerden kaçının (IMAPv4 veya POPv3'ten aşağısı). Her ikisi de bilinen güvenlik açıklarına sahiptir ve güvenlik açısından güncel değildir.
**Kendi Sunucunuzu Barındırma** | **Gelişmiş** | Kendi e-posta sunucunuzu barındırmak, güvenli bir şekilde yapılandırmak için güçlü ağ bilgisi gerektirdiğinden, ileri düzey olmayan kullanıcılar için önerilmez.
**Her Zaman TLS Bağlantı Noktalarını Kullanın** | **Gelişmiş** | POP3, IMAP ve SMTP için standart TCP/IP bağlantı noktaları olarak SSL seçenekleri bulunmaktadır. Bunlar kullanımı kolaydır ve geniş destek gördüğünden, düz metin e-posta bağlantı noktaları yerine her zaman kullanılmalıdır.
**DNS Erişilebilirliği** | **Gelişmiş** | Kendi barındırdığınız e-posta sunucuları için, DNS sorunlarının erişilebilirliği etkilemesini önlemek için en az 2 MX kaydı kullanın. Birincil MX kaydı başarısız olduğunda yedek ve üçüncül MX kayıtları ile yedekliliği artırın.
**DDoS ve Kaba Kuvvet Saldırılarını Önleyin** | **Gelişmiş** | Kendi barındırdığınız e-posta sunucuları için (özellikle SMTP), toplam eşzamanlı bağlantı sayınızı ve maksimum bağlantı hızını sınırlayarak bot saldırı girişimlerinin etkisini azaltın.
**IP Kara Listesi Güncellemesi** | **Gelişmiş** | Kendi barındırdığınız e-posta sunucuları için, güncel bir yerel IP kara listesi ve spam URI gerçek zamanlı engelleme listeleri tutarak spam filtrelerini iyileştirin ve güvenliği sağlamlaştırın.

### Tavsiye Edilen Yazılımlar
- [Güvenli E-posta Sağlayıcıları](https://github.com/Lissy93/awesome-privacy#encrypted-email)
- [E-posta Yönlendirme](https://github.com/Lissy93/awesome-privacy#anonymous-mail-forwarding)
- [Ön Yapılandırılmış E-posta Sunucuları](https://github.com/Lissy93/awesome-privacy#pre-configured-mail-servers)
- [E-posta İstemcileri](https://github.com/Lissy93/awesome-privacy#email-clients)


## Mesajlaşma



**Güvenlik** | **Öncelik** | **Detaylar ve İpuçları**
--- | --- | ---
**Sadece Tamamen Uçtan Uca Şifreli Mesajlaşma Uygulamaları Kullanın** | Temel | Uçtan uca şifreleme, iletilerin cihazınızda şifrelendiği ve hedeflenen alıcıya ulaşana kadar şifrenin çözülmediği bir iletişim sistemidir. Bu, trafiği yakalayan herhangi bir aktörün ileti içeriğini okuyamayacağı anlamına gelir ve verilerin depolandığı merkezi sunuculara erişimi olan herhangi birinin de okuyamayacağı anlamına gelir.
**Sadece Açık Kaynak Kodlu Mesajlaşma Platformları Kullanın** | Temel | Kod açık kaynaklıysa, nitelikli herhangi biri tarafından bağımsız olarak incelenebilir ve denetlenebilir. Böylece arka kapılar, güvenlik açıkları veya diğer güvenlik sorunlarının olmadığından emin olunabilir.
**Güvenilir Bir Mesajlaşma Platformu Kullanın** | Temel | Şifreli bir mesajlaşma uygulaması seçerken, tamamen açık kaynaklı, stabil, aktif olarak bakımı yapılan ve mümkünse saygın geliştiriciler tarafından desteklenen bir uygulama olduğundan emin olun.
**Güvenlik Ayarlarını Kontrol Edin** | Temel | İletişim güvenliği ayarlarını etkinleştirin, bu ayarlar arasında kişi doğrulaması, güvenlik bildirimleri ve şifreleme bulunmaktadır. Okuma onayı, çevrimiçi durum ve yazma bildirimi gibi isteğe bağlı güvenlik dışı özellikleri devre dışı bırakın.
**Alıcınızın Ortamının Güvenli Olduğundan Emin Olun** | Temel | Sohbetiniz, en zayıf bağlantı kadar güvenli olabilir. Bir iletişim kanalına sızmanın genellikle en kolay yolu, en az korumaya sahip bireyi veya düğümü hedef almaktır.
**Bulut Hizmetlerini Devre Dışı Bırakın** | Temel | Bazı mobil mesajlaşma uygulamaları web veya masaüstü eşlik edici sunabilir. Bu, sadece saldırı yüzeyini artırmakla kalmaz, aynı zamanda birçok kritik güvenlik sorununa neden olmuştur ve bu nedenle mümkünse kaçınılmalıdır.
**Güvenli Grup Sohbetleri** | Temel | Bir grupta daha fazla katılımcı olduğunda, saldırı yüzeyi arttığı için tehlike oranı üssel olarak artar. Düzenli olarak tüm katılımcıların geçerli olduğunu kontrol edin.
**İletişim için Güvenli Bir Ortam Oluşturun** | Temel | Dijital iletişiminizin izlenebileceği veya ele geçirilebileceği birkaç aşama bulunmaktadır. Bunlar; sizin veya katılımcılarınızın cihazı, İSS'niz, ulusal ağ geçidi veya hükümet günlüğü, mesajlaşma sağlayıcısı ve sunucuları içerir.
**İletişim Planı Belirleyin** | İsteğe Bağlı | Belirli durumlarda, iletişim planı yapmak faydalı olabilir. Bu, birbirinizle güvenli bir şekilde iletişim kurmanın birincil ve yedek yöntemlerini içermelidir.
**Meta Verilerini Medyadan Kaldırın** | İsteğe Bağlı | Meta veriler, bir dosya veya işlemle ilişkilendirilmiş ek bilgiler veya "Veri Hakkında Veri"dir. Bir fotoğraf, ses kaydı, video veya belge gönderdiğinizde, istemediğiniz bilgileri açığa çıkarabilirsiniz.
**URL'leri Zararsız Hale Getirin** | İsteğe Bağlı | Çeşitli hizmetler aracılığıyla bağlantılar göndermek, kişisel bilgilerinizi istenmeyen bir şekilde ortaya çıkarabilir. Bu, bir küçük resim veya önizleme oluşturulduğunda istemci tarafında gerçekleştiği için olabilir.
**Alıcınızı Doğrulayın** | İsteğe Bağlı | Her zaman istenilen alıcıyla konuştuğunuzdan ve onların tehlikeye atılmadığından emin olun. Bunu yapmanın bir yolu, kişi doğrulamasını destekleyen bir uygulama kullanmaktır.
**Geçici Mesajları Etkinleştirin** | İsteğe Bağlı | Kendini imha eden mesajlar, iletilerin belirli bir süre sonra otomatik olarak silinmesine neden olan bir özelliktir. Bu, cihazınız kaybolursa, çalınırsa veya el konursa, bir düşmanın yalnızca en son iletişimlere erişimi olacağı anlamına gelir.
**SMS'ten Kaçının** | İsteğe Bağlı | SMS, pratik olabilir ancak güvenli değildir. İntersepsiyon, sim takası, manipülasyon ve kötü amaçlı yazılım gibi tehditlere karşı savunmasızdır.
**İzleyicilere Dikkat Edin** | İsteğe Bağlı | İzleyicilerle birlikte gelen mesajlaşma uygulamalarından kaçının, çünkü topladıkları ayrıntılı kullanım istatistikleri genellikle çok ihlal edici olabilir ve bazen kimliğinizi ve paylaşmayı amaçlamadığınız kişisel bilgilerinizi ortaya çıkarabilir.
**Yargı Alanını Dikkate Alın** | Gelişmiş | Organizasyonun merkezini ve verilerin barındırıldığı yargı alanlarını da dikkate almak önemlidir.
**Anonim Bir Platform Kullanın** | Gelişmiş | Hedef alınabileceğinizi düşünüyorsanız, telefon numarası veya başka herhangi bir kişisel tanımlayıcı bilgi gerektirmeyen anonim bir mesajlaşma platformunu tercih etmelisiniz.
**İleriye Dönük Gizliliğin Desteklendiğinden Emin Olun** | Gelişmiş | İleriye dönük gizliliği uygulayan bir platformu tercih edin. Bu, uygulamanızın her ileti için yeni bir şifreleme anahtarı oluşturduğu yerdir.
**Dağıtık Bir Platformu Düşünün** | Gelişmiş | Tüm verilerin merkezi bir sağlayıcı üzerinden geçmesi durumunda, veri ve meta verilerinizi onlara güvenmek zorundasınız. Arkada kapı olmadan sistem çalıştığını doğrulayamazsınız.

### Önerilen Yazılımlar
- [Güvenli Mesajlaşma Uygulamaları](https://github.com/Lissy93/awesome-privacy#encrypted-messaging)
- [Eşten Eşe Mesajlaşma Platformları](https://github.com/Lissy93/awesome-privacy#p2p-messaging)


## Sosyal Medya

İnternetin icadından bu yana çevrimiçi topluluklar var olmuş ve dünya çapında insanların bağlantı kurma, iletişim kurma ve paylaşma fırsatı bulmasını sağlamıştır. Bu ağlar, sosyal etkileşimi teşvik etmenin harika bir yoludur ve insanları bir araya getirirken, karanlık bir yanları da vardır - [Sosyal Ağ Hizmetleriyle İlgili Gizlilik Endişeleri](https://en.wikipedia.org/wiki/Privacy_concerns_with_social_networking_services) ciddi konular içermektedir ve bu sosyal ağ sitelerinin özel şirketlere ait olduğu ve bu şirketlerin gelirlerini bireyler hakkında veri toplayarak ve bu verileri genellikle üçüncü taraf reklamverenlere satış yaparak elde ettiği bilinmektedir.
Hesabınızı güvence altına alın, gizlilik ayarlarınızı kilit altına alın, ancak bunu yaptıktan sonra bile, bilerek veya bilmeyerek yüklenen tüm veriler etkili bir şekilde halka açıktır. Mümkünse, geleneksel sosyal medya ağlarını kullanmaktan kaçının.


**Güvenlik** | **Öncelik** | **Detaylar ve İpuçları**
--- | --- | ---
**Hesabınızı Güvence Altına Alın** | Temel | Sosyal medya profilleri çok sık çalınıyor veya ele geçiriliyor. Hesabınızı korumak için: benzersiz ve güçlü bir şifre kullanın ve 2 faktörlü kimlik doğrulamayı etkinleştirin.
**Gizlilik Ayarlarını Kontrol Edin** | Temel | Çoğu sosyal ağ size gizlilik ayarlarınızı kontrol etme imkanı tanır. Şu anda hangi verileri ve kime karşı hangi verileri açığa çıkardığınızdan emin olun.
**Tüm Etkileşimleri Kamuoyu Önünde Yapılan Gibi Düşünün** | Temel | Birçok sosyal ağda bir kullanıcının 'özel' içeriğini görüntülemenin hala birçok yöntemi bulunmaktadır. Bu nedenle, herhangi bir şey yüklerken, gönderirken veya yorum yaparken, "Bu tamamen kamuya açık olsaydı bunun benim için bir önemi olur muydu?" diye düşünün.
**Tüm Etkileşimleri Kalıcı Olarak Düşünün** | Temel | Neredeyse her gönderi, yorum, fotoğraf vb., bu verileri arşivleyen ve neredeyse sonsuza kadar indexlenebilir ve halka açık hale getiren bir dizi üçüncü taraf hizmeti tarafından sürekli olarak yedeklenmektedir.
**Çok Fazla Bilgi Açıklamayın** | Temel | Profil bilgileri, siber saldırganlar için kişiselleştirilmiş dolandırıcılık dolandırıcılığı yapmalarına yardımcı olan bilgi hazinesi oluşturur. Çok fazla ayrıntı paylaşmaktan kaçının (Doğum Tarihi, Memleket, Okul vb.).
**Ne Yüklediğinize Dikkat Edin** | Temel | Durum güncellemeleri, yorumlar, konum belirtmeleri ve medya, istemeden daha fazlasını açığa çıkarabilir. Bu özellikle arka planda gösterilen şeyleri gösterebilecek fotoğraflar ve videolar için geçerlidir.
**E-posta veya Telefon Numarası Paylaşmayın** | Temel | Gerçek e-posta adresinizi veya cep telefonu numaranızı paylaşmak, siber saldırganlara, trollere ve istenmeyen postalara karşı kullanabilecekleri daha fazla mühimmat sağlar ve ayrıca ayrı takma adlar, profiller veya veri noktalarının bağlantı kurulmasına izin verebilir.
**Gereksiz İzinler Vermeyin** | Temel | Popüler birçok sosyal ağ uygulaması varsayılan olarak kişilerinize, arama kaydınıza, konumunuza, mesaj geçmişinize vb. erişim izni isteyecektir. Bu erişime ihtiyaç duymuyorlarsa, izin vermeyin.
**3. Taraf Entegrasyonlarından Kaçının** | Temel | Sosyal Ağ girişi kullanarak hesap oluşturmaktan kaçının, artık kullanmadığınız sosyal uygulamalara erişimi iptal edin.
**Yerindeyken Coğrafi Veri Yayınlamaktan Kaçının** | Temel | Bir yerin konumunu açıklayan herhangi bir içerik paylaşmayı planlıyorsanız, o yeri terk edene kadar bekleyin. Bu, bir seyahatteyken, bir restoranda, kampüste, otel/tatil köyünde, kamu binasında veya havalimanında olduğunuzda özellikle önemlidir.
**Medya Yüklerken Meta Verileri Kaldırın** | İsteğe Bağlı | Çoğu akıllı telefon ve bazı kameralar, her fotoğrafa kapsamlı bir dizi ek veri (EXIF verileri olarak adlandırılır) otomatik olarak ekler. Bunları yüklemek öncesinde bu verileri kaldırın.
**Görüntü Maskesi Uygulayın** | Gelişmiş | Fawkes gibi araçlar, fotoğraflardaki yüzleri insanlar tarafından algılanamayan şekilde çok hafif ve hafifçe değiştirerek kullanılabilir, ancak yüz tanıma sistemlerinin belirli bir yüzü tanıyamamasını sağlar.
**Ev Çevresinde GPS Taklitini Düşünün** | Gelişmiş | Sosyal medyayı asla kullanmasanız bile, her zaman daha dikkatli olmayan başkaları olacaktır ve konumunuzu açıklayabilirler.
**Yanlış Bilgi Kullanımını Düşünün** | Gelişmiş | Sadece okumak istiyorsanız ve çok fazla gönderi yapmayı düşünmüyorsanız, takma bir isim ve yanlış iletişim bilgileri kullanmayı düşünün.
**Hiçbir sosyal medya hesabı bulundurmayın** | Gelişmiş | Sosyal medya temel olarak gizlilikten yoksundur, bu nedenle maksimum çevrimiçi güvenlik ve gizlilik için herhangi bir ana akım sosyal ağ kullanmaktan kaçının.

### Önerilen Yazılımlar
- [Alternatif Sosyal Medya](https://github.com/Lissy93/awesome-privacy#social-networks)
- [Alternatif Video Platformları](https://github.com/Lissy93/awesome-privacy#video-platforms)
- [Alternatif Blog Platformları](https://github.com/Lissy93/awesome-privacy#blogging-platforms)
- [Haber Okuyucuları ve Birleştirme](https://github.com/Lissy93/awesome-privacy#news-readers-and-aggregation)


## Ağlar

Bu bölüm, cihazlarınızı internete güvenli bir şekilde bağlamayı, yönlendiricinizi yapılandırmayı ve bir VPN kurmayı içerir.


**Güvenlik** | **Öncelik** | **Detaylar ve İpuçları**
--- | --- | ---
**VPN Kullanın** | Temel | Güvenilir, ücretli bir VPN kullanın. Bu, ziyaret ettiğiniz sitelerin gerçek IP'nizi kaydetmesini engelleyebilir, İSS'nizin toplayabileceği veri miktarını azaltabilir ve genel WiFi'de korumayı artırabilir.
**Yönlendirici Şifrenizi Değiştirin** | Temel | Yeni bir yönlendirici aldıktan sonra şifreyi değiştirin. Varsayılan yönlendirici şifreleri genelde herkese açıktır, bu da yakınlardaki herhangi bir kişinin bağlanabilmesi anlamına gelir.
**WPA2 ve Güçlü Bir Şifre Kullanın** | Temel | WiFi'ye bağlanmak için farklı kimlik doğrulama protokolleri bulunmaktadır. Şu anda, en güvenli seçenekler WPA2 ve (daha yeni yönlendiricilerde) WPA3'tür.
**Yönlendirici Yazılımını Güncel Tutun** | Temel | Üreticiler, güvenlik açıklarını düzeltmek, yeni standartları uygulamak ve bazen yönlendiricinizin performansını iyileştirmek için yazılım güncellemeleri yayınlamaktadır.
**Ağ Geneli VPN Uygulayın** | İsteğe Bağlı | VPN'yi yönlendiricinizde, güvenlik duvarınızda veya ev sunucunuzda yapılandırırsanız, tüm cihazlardan gelen trafiğinizi bireysel VPN uygulamalarına ihtiyaç duymadan şifreleyip yönlendirebilirsiniz.
**DNS Sızıntılarına Karşı Koruma Sağlayın** | İsteğe Bağlı | VPN kullanırken, yalnızca VPN sağlayıcınızın veya güvenli bir hizmetin DNS sunucusunu kullanmak son derece önemlidir.
**Güvenli Bir VPN Protokolü Kullanın** | İsteğe Bağlı | OpenVPN ve WireGuard, açık kaynaklı, hafif ve güvenli tünel protokolleridir. PPTP veya SSTP kullanmaktan kaçının.
**Güvenli DNS** | İsteğe Bağlı | DNS-over-HTTPS kullanın, bu, DNS çözümlemesinin HTTPS protokolü aracılığıyla gerçekleştirilmesini sağlar ve sizin ile DNS çözümleyiciniz arasındaki verileri şifreler.
**İSS'nizden Ücretsiz Yönlendiriciyi Kullanmaktan Kaçının** | İsteğe Bağlı | Genellikle, güvenlik güncellemesi almayan, güvensiz özel yazılımlı, ucuz bir şekilde Çin'de toplu üretilirler.
**MAC Adreslerini Beyaz Listeye Alın** | İsteğe Bağlı | Yönlendirici ayarlarınızda MAC adreslerini beyaz listeye alabilirsiniz, böylece bilinmeyen herhangi bir cihazın ağınıza hemen bağlanmasını engellersiniz, hatta kimlik bilgilerinizi biliyorlarsa bile.
**Yönlendiricinin Yerel IP Adresini Değiştirin** | İsteğe Bağlı | Web tarayıcınızda kötü niyetli bir betikin bir cross-site scripting açığından faydalanarak, bilinen güvenlik açıklarına sahip yönlendiricilere yerel IP adreslerinden erişebilir ve bunlarla oynayabilir.
**SSID'de Kişisel Bilgi Açıklamayın** | İsteğe Bağlı | Ağ adınızı güncellemelisiniz, sizi tanımlamayan bir SSID seçmelisiniz, daire numaranız/adresiniz gibi bilgileri içermemeli ve cihaz marka/modelini belirtmemelidir.
**Yönlendirici Listelemelerinden Vazgeçin** | İsteğe Bağlı | WiFi SSID'leri taranır, kaydedilir ve çeşitli web sitelerinde yayımlanır, bu bazıları için ciddi bir gizlilik endişesidir.
**SSID'nizi Gizleyin** | İsteğe Bağlı | Yönlendiricinizin Hizmet Seti Tanımlayıcısı sadece ağ adıdır. Görünmezse, daha az istismar alabilir.
**WPS'yi Devre Dışı Bırakın** | İsteğe Bağlı | Wi-Fi Protected Setup, uzun bir WiFi şifresi girmeden daha kolay bir bağlantı yöntemi sağlar, ancak WPS bir dizi ciddi güvenlik sorununu beraberinde getirir.
**UPnP'yi Devre Dışı Bırakın** | İsteğe Bağlı | Universal Plug and Play, uygulamaların yönlendiricinizde otomatik olarak bir bağlantı noktasını yönlendirmesine izin verir, ancak ciddi güvenlik sorunları geçmişi vardır.
**Misafirler için Misafir Ağı Kullanın** | İsteğe Bağlı | Misafirlere ana WiFi ağınıza erişim izni vermeyin, çünkü bu, misafirlerin ağdaki diğer cihazlarla etkileşimde bulunmasını sağlar.
**Yönlendiricinizin Varsayılan IP'sini Değiştirin** | İsteğe Bağlı | Yönlendirici yönetim panelinizin varsayılan IP adresini değiştirmek, yerel IP adreslerine hedeflenen kötü niyetli betikler için daha zor hale getirecektir.
**Yönlendiricinizde Kullanılmayan İşlemleri ve Servisleri Sonlandırın** | İsteğe Bağlı | Komut satırı erişimi sağlayan Telnet ve SSH gibi hizmetlerin internete açık olmaması ve gerçekten gerekli olmadıkları sürece yerel ağda da devre dışı bırakılması gerekmektedir.
**Açık Portlarınızı Kapatmayın** | İsteğe Bağlı | Gerekli olmayan açık portları yönlendiricinizde kapatın. Açık portlar, hackerlar için kolay bir giriş sağlar.
**Kullanılmayan Uzak Erişim Protokollerini Devre Dışı Bırakın** | İsteğe Bağlı | PING, Telnet, SSH, UPnP ve HNAP gibi protokoller etkinleştirildiğinde, yönlendiricinizin dünyanın her yerinden sorgulanmasına izin verirler.
**Bulut Tabanlı Yönetimi Devre Dışı Bırakın** | İsteğe Bağlı | Yönlendiricinizin yönetim panelini son derece dikkatli kullanmalısınız, çünkü bir saldırganın erişim sağlayabilmesi durumunda ciddi zararlar oluşabilir.
**Menşeyi Doğru Yönetin** | İsteğe Bağlı | Yönlendiricinizin menzilini maksimuma çıkarmak istemek yaygındır, ancak daha küçük bir dairede yaşıyorsanız, WiFi ağınızın karşı sokaktan alınabilmesi durumunda saldırı yüzeyiniz artar.
**Tüm Trafikleri [Tor](https://awesome-privacy.xyz/networking/mix-networks/tor) Üzerinden Yönlendirin** | Gelişmiş | VPN'lerin zayıflıkları vardır. Artan güvenlik için, tüm internet trafiğinizi [Tor](https://awesome-privacy.xyz/networking/mix-networks/tor) ağı üzerinden yönlendirin.
**Tüm Cihazlarda WiFi'yi Devre Dışı Bırakın** | Gelişmiş | Bile güvenli bir WiFi ağına bağlanmak, saldırı yüzeyinizi artırır. Ev WiFi'nizi devre dışı bırakın ve her cihazı Ethernet üzerinden bağlayın.

### Önerilen Yazılımlar
- [Sanal Özel Ağlar](https://github.com/Lissy93/awesome-privacy#virtual-private-networks)
- [Karışık Ağlar](https://github.com/Lissy93/awesome-privacy#mix-networks)
- [Yönlendirici Yazılımı](https://github.com/Lissy93/awesome-privacy#router-firmware)
- [Açık Kaynaklı Proxyler](https://github.com/Lissy93/awesome-privacy#proxies)
- [DNS Sağlayıcıları](https://github.com/Lissy93/awesome-privacy#dns)
- [Güvenlik Duvarları](https://github.com/Lissy93/awesome-privacy#firewalls)
- [Ağ Analiz Araçları](https://github.com/Lissy93/awesome-privacy#network-analysis)
- [Kendi Kendine Barındırılan Ağ Güvenlik Araçları](https://github.com/Lissy93/awesome-privacy#self-hosted-network-security)


## Mobil Cihazlar

Akıllı telefonlar birçok yaşam alanını devrim niteliğinde değiştirdi ve dünyayı parmaklarımızın ucuna getirdi. Birçoğumuz için akıllı telefonlar iletişim, eğlence ve bilgiye erişimde ana araçlarımızdır. Ancak, büyük bir kolaylık getirmelerine rağmen, ekranın arkasında pek de hoş olmayan şeyler var. 
Coğrafi izleme, her hareketimizi takip etmek için kullanılır ve bu veriye kimin sahip olduğu konusunda pek kontrolümüz yoktur - telefonunuz [GPS olmadan bile konumunuzu izleyebilir](https://gizmodo.com/how-to-track-a-cellphone-without-gps-or-consent-1821125371). Yıllar boyunca, telefonunuzun [mikrofonunun dinlenebileceğini](https://www.independent.co.uk/life-style/gadgets-and-tech/news/smartphone-apps-listening-privacy-alphonso-shazam-advertising-pool-3d-honey-quest-a8139451.html) ve [kameranın sizi izleyebileceğini](https://www.businessinsider.com/hackers-governments-smartphone-iphone-camera-wikileaks-cybersecurity-hack-privacy-webcam-2017-6) ortaya koyan birçok rapor ortaya çıktı - tüm bunlar bilginiz veya izniniz olmadan. Ve sonra, kötü niyetli uygulamalar, güvenlik yamalarının eksikliği ve potansiyel/olası arka kapılar var.
Akıllı telefon kullanmak, sizin hakkınızda birçok veri üretir - bilerek paylaştığınız bilgilerden, eylemlerinizden sessizce üretilen verilere kadar. Google, Microsoft, Apple ve Facebook'un bize ne kadar bildiğini görmek korkutucu olabilir - bazen en yakın akrabalarımızdan daha fazlasını biliyorlar. Verilerinizin neyi ortaya çıkaracağını anlamak, özellikle diğer verilerle birlikte olduğunda zor olabilir.
Bu veriler [sadece reklamcılık için değil](https://internethealthreport.org/2018/the-good-the-bad-and-the-ugly-sides-of-data-tracking/) - daha sık olarak, insanları finans, sigorta ve istihdam için değerlendirmek için kullanılır. Hedeflenmiş reklamlar, ince taneli gözetim için bile kullanılabilir (bkz. [ADINT](https://adint.cs.washington.edu)).
Daha fazla insan, [hükümetlerin akıllı telefon verilerimizi nasıl topladığı ve kullandığı](https://www.statista.com/statistics/373916/global-opinion-online-monitoring-government/) hakkında endişeli, ve haklı olarak, federal ajanslar sıklıkla Google'dan [verilerimizi talep eder](https://www.statista.com/statistics/273501/global-data-requests-from-google-by-federal-agencies-and-governments/), [Facebook'tan](https://www.statista.com/statistics/287845/global-data-requests-from-facebook-by-federal-agencies-and-governments/), Apple, Microsoft, Amazon ve diğer teknoloji şirketlerinden. Bazı durumlarda talepler toplu olarak yapılır ve belirli bir coğrafi bölgedeki herkes hakkında detaylı bilgi sağlar, [genellikle masum insanlar için](https://www.nytimes.com/interactive/2019/04/13/us/google-location-tracking-police.html). Ve bu, dünya çapındaki istihbarat ajanslarının engelsiz erişimine sahip olduğu tüm internet trafiğini içermez.


**Güvenlik** | **Öncelik** | **Detaylar ve İpuçları**
--- | --- | ---
**Cihazınızı Şifreleyin** | Temel | Verilerinizi fiziksel erişime karşı korumak için dosya şifrelemesi kullanın. Bu, cihazınız kaybolursa veya çalınırsa, verilerinize kimse erişemeyeceği anlamına gelir.
**Kullanılmayan Bağlantı Özelliklerini Kapatın** | Temel | WiFi, Bluetooth, NFC vb. gibi özellikleri kullanmadığınızda bu özellikleri kapatın. Bu özellikler, birçok yaygın tehdidi kullanır.
**Uygulama Sayısını Minimumda Tutun** | Temel | İhtiyacınız olmayan veya düzenli olarak kullanmadığınız uygulamaları kaldırın. Uygulamalar genellikle arka planda çalışır, cihazınızı yavaşlatır ve aynı zamanda veri toplar.
**Uygulama İzinleri** | Temel | Uygulamalara gerek duymadıkları izinleri vermeyin. Android için, [Bouncer](https://awesome-privacy.xyz/security-tools/mobile-apps/bouncer), geçici/tek kullanımlık izinler vermenizi sağlayan bir uygulamadır.
**Yalnızca Resmi Kaynaklardan Uygulama Yükleyin** | Temel | Apple App Store ve Google Play Store'daki uygulamalar taranır ve kriptografik olarak imzalanır, bu nedenle kötü amaçlı olma olasılıkları daha düşüktür.
**Telefon Şarj Tehditlerinden Sakının** | İsteğe Bağlı | Juice Jacking, hacker'ların kamuya açık şarj istasyonlarını kullanarak smartphone veya tabletinize kompromize USB bağlantı noktası aracılığıyla kötü amaçlı yazılım yüklemesi yapması durumudur.
**Mobil Operatör PIN'i Kurun** | Temel | SIM korsanlığı, bir hacker'ın mobil numaranızı kendi SIM kartlarına aktarmasını sağladığında gerçekleşir. Buna karşı korunmanın en kolay yolu, mobil sağlayıcınız aracılığıyla bir PIN kurmaktır.
**Arama Kimliği Listelemesini Devre Dışı Bırakın** | İsteğe Bağlı | Detaylarınızı gizli tutmak için, TrueCaller, CallApp, SyncMe ve Hiya gibi arama kimliği uygulamalarından numaranızı listeden çıkarabilirsiniz.
**Çevrimdışı Haritaları Kullanın** | İsteğe Bağlı | Veri sızıntılarını azaltmak için OsmAnd veya Organic Maps gibi çevrimdışı harita uygulamalarını kullanmayı düşünebilirsiniz.
**Kişiselleştirilmiş Reklamlardan Vazgeçin** | İsteğe Bağlı | Kişiselleştirilmiş reklamları görmeyi reddederek toplanan veri miktarını hafifçe azaltabilirsiniz.
**Çok Sayıda Giriş Denemesinden Sonra Silmeyi Etkinleştirin** | İsteğe Bağlı | Bir saldırganın pin'inizi kaba kuvvet saldırısıyla kırmaya çalışmasına karşı korunmak için cihazınızı çok sayıda başarısız giriş denemesinden sonra silmeye ayarlayın.
**İzleyicileri İzleyin** | İsteğe Bağlı | [εxodus](https://awesome-privacy.xyz/security-tools/online-tools/εxodus), herhangi bir uygulamayı arayabilmenize ve ona gömülü olan izleyicileri görebilmenize olanak tanıyan harika bir hizmettir.
**Mobil Güvenlik Duvarı Kullanın** | İsteğe Bağlı | Uygulamalardan gizlilik hassasiyeti taşıyan verilerin sızmasını önlemek için bir güvenlik duvarı uygulaması kurabilirsiniz.
**Arka Plan Etkinliğini Azaltın** | İsteğe Bağlı | Android için, SuperFreeze, uygulama başına tüm arka plan etkinliklerini tamamen dondurmanızı sağlar.
**Mobil Uygulamaları Sandbox'a Alın** | İsteğe Bağlı | [Island](https://awesome-privacy.xyz/security-tools/mobile-apps/island) ile, izin istekleri çok fazla olan uygulamaların özel verilerinize erişmesini önleyin.
**Tor Trafik** | Gelişmiş | [Orbot](https://awesome-privacy.xyz/security-tools/mobile-apps/orbot), sizi gözetimden ve kamuya açık WiFi tehditlerinden koruyacak sistem genelinde bir Tor bağlantısı sağlar.
**Özel Sanal Klavyelerden Kaçının** | İsteğe Bağlı | Cihazınızın varsayılan klavyesiyle devam etmeniz önerilir. Üçüncü taraf bir klavye uygulaması kullanmayı tercih ederseniz, güvenilir olduğundan emin olun.
**Cihazı Düzenli Olarak Yeniden Başlatın** | İsteğe Bağlı | Telefonunuzu haftada en az bir kez yeniden başlatmak, bellekte önbelleğe alınan uygulama durumunu temizler ve yeniden başlatmadan sonra daha düzgün çalışabilir.
**SMS Kullanmaktan Kaçının** | İsteğe Bağlı | 2FA kodları almak veya iletişim için SMS kullanılmamalıdır, bunun yerine [Signal](https://awesome-privacy.xyz/communication/encrypted-messaging/signal) gibi şifreli bir iletişim uygulaması kullanılmalıdır.
**Numaranızı Gizli Tutun** | İsteğe Bağlı | [MySudo](https://awesome-privacy.xyz/finance/virtual-credit-cards/mysudo), farklı kişiler veya gruplar için sanal telefon numaraları oluşturmanıza ve kullanmanıza olanak tanır. Bu, bölümlendirme için harikadır.
**Stalkerware'den Kaçının** | İsteğe Bağlı | Stalkerware, tanıdığınız biri tarafından doğrudan cihazınıza kurulan kötü amaçlı yazılımdır. Onu kurtulmanın en iyi yolu fabrika ayarlarına sıfırlamaktır.
**Özel Uygulama Yerine Tarayıcıyı Tercih Edin** | İsteğe Bağlı | Mümkünse, özel uygulamaları yüklemek yerine güvenli bir tarayıcı kullanarak sitelere erişmeyi düşünün.
**Özel ROM Kullanmayı Düşünün (Android)** | Gelişmiş | Cihaz üreticinizin çok fazla kişisel bilgi toplamasından endişe ediyorsanız, gizlilik odaklı özel bir ROM düşünün.

### Önerilen Yazılımlar
- [Güvenlik ve Gizlilik için Mobil Uygulamalar](https://github.com/Lissy93/awesome-privacy#mobile-apps)
- [Şifreli Mesajlaşma](https://github.com/Lissy93/awesome-privacy#encrypted-messaging)
- [Mobil İşletim Sistemleri](https://github.com/Lissy93/awesome-privacy#mobile-operating-systems)


## Kişisel Bilgisayarlar

Windows ve OS X kullanımı kolay ve kullanışlı olsa da, ikisi de güvenlik açısından uzaktır. İşletim sisteminiz, donanım ile uygulamalarınız arasındaki arayüzü sağlar, bu nedenle tehlikeye atıldığında ciddi sonuçları olabilir.


**Güvenlik** | **Öncelik** | **Detaylar ve İpuçları**
--- | --- | ---
**Sisteminizi Güncel Tutun** | Temel | Sistem güncellemeleri, güvenlik sorunları için düzeltmeleri/ yamaları içerir, performansı artırır ve bazen yeni özellikler ekler. Yeni güncellemeler sunulduğunda bunları yükleyin.
**Cihazınızı Şifreleyin** | Temel | Windows için BitLocker, MacOS için FileVault veya Linux için LUKS kullanarak tam disk şifrelemesi etkinleştirin. Bu, bilgisayarınız kaybolursa veya çalınırsa yetkisiz erişimi önler.
**Önemli Verileri Yedekleyin** | Temel | Şifreli yedeklerin tutulması, fidye yazılımı, hırsızlık veya hasar nedeniyle veri kaybını önler. Bulut dosyaları için [Cryptomator](https://awesome-privacy.xyz/security-tools/mobile-apps/cryptomator) veya USB sürücüler için [VeraCrypt](https://awesome-privacy.xyz/essentials/file-encryption/veracrypt) kullanmayı düşünün.
**Bilgisayarınıza USB Cihazları Takarken Dikkatli Olun** | Temel | USB cihazları ciddi tehditler oluşturabilir. USB cihazlarını güvenli bir şekilde kontrol etmek için CIRCLean ile bir USB dezenfektanı yapmayı düşünün.
**Ekran Kilidini Etkinleştirin** | Temel | Uzakta olduğunuzda bilgisayarınızı kilitleyin ve izinsiz erişimi önlemek için ekran koruyucudan veya uyku modundan geri dönüşte şifre gerektirecek şekilde ayarlayın.
**Cortana veya Siri'yi Devre Dışı Bırakın** | Temel | Sesle kontrol edilen yardımcılar, işlenmesi için geri gönderilen veriler nedeniyle gizlilik sorunlarına sahip olabilir. Bunların dinleme yeteneklerini devre dışı bırakın veya sınırlayın.
**Yüklü Uygulamalarınızı İnceleyin** | Temel | Maruziyetinizi azaltmak için yüklü uygulamaları minimumda tutun ve düzenli olarak uygulama önbelleklerini temizleyin.
**İzinleri Yönetin** | Temel | Hangi uygulamaların konumunuz, kamera, mikrofon, kişileriniz ve diğer hassas bilgilere erişimi olduğunu kontrol edin.
**Kullanım Verilerinin Buluta Gönderilmesini Yasaklayın** | Temel | Gizliliğinizi korumak için buluta gönderilen kullanım bilgileri veya geri bildirim miktarını sınırlayın.
**Hızlı Kilidi Kullanmaktan Kaçının** | Temel | Güvenliği artırmak için bilgisayarınızı kilitlemek için biyometrik veya kısa PIN'ler yerine güçlü bir şifre kullanın.
**Bilgisayarı Kapatın, Bekleme Moduna Almayın** | Temel | Özellikle diskiniz şifrelenmişse, cihazınızı kullanmadığınız zamanlarda kapatın ve verilerinizi güvende tutmak için kapatın.
**Bilgisayarınızı Microsoft veya Apple Hesabınızla Bağlamayın** | İsteğe Bağlı | Veri senkronizasyonu ve maruziyeti önlemek için yalnızca yerel bir hesap kullanın. Gizliliği tehlikeye atan senkronizasyon hizmetlerinden kaçının.
**Etkinleştirilmiş Paylaşım Hizmetlerini Kontrol Edin** | İsteğe Bağlı | Sık karşılaşılan tehdit kapılarını kapatmak için kullanmadığınız ağ paylaşım özelliklerini devre dışı bırakın.
**Yönetici Olmayan Görevler için Kök/Admin Hesabını Kullanmayın** | İsteğe Bağlı | Günlük görevler için yetkisiz bir kullanıcı hesabı kullanın ve güvenlik açıklarını azaltmak için yalnızca idari değişiklikler için izinleri yükseltin.
**Web Kamerası + Mikrofonu Engelle** | İsteğe Bağlı | Kullanılmadığında web kamerasını kapatın ve izinsiz ses kaydını engellemek için mikrofonu kapalı konuma getirin.
**Gizlilik Filtresi Kullanın** | İsteğe Bağlı | Kamu alanlarında ekran izleme ve hassas bilgilerin korunması için bir ekran gizlilik filtresi kullanın.
**Cihazı Fiziksel Olarak Güvence Altına Alın** | İsteğe Bağlı | Dizüstü bilgisayarınızı kamu alanlarda güvence altına almak için bir Kensington Kilidi kullanın ve yetkisiz fiziksel erişimi engellemek için port kilitlerini düşünün.
**Bilgisayarınızı Şarj Etmemeye Dikkat Edin** | İsteğe Bağlı | USB bağlantılarıyla ilişkilendirilen güvenlik risklerinden kaçınmak için bilgisayarınız yerine bir güç bankası veya AC duvar şarj cihazı kullanın.
**Wi-Fi'de Donanım Adresinizi Rastgeleleştirin** | İsteğe Bağlı | Farklı Wi-Fi ağları üzerinde izlenmeye karşı korunmak için MAC adresinizi değiştirin veya rastgeleleştirin.
**Bir Güvenlik Duvarı Kullanın** | İsteğe Bağlı | Belirli uygulamalar tarafından istenmeyen internet erişimini izlemek ve engellemek için bir güvenlik duvarı uygulaması kurun, uzaktan erişim saldırılarına ve gizlilik ihlallerine karşı koruma sağlar.
**Yazılım Keylogger'lara Karşı Korunun** | İsteğe Bağlı | Yazılım keylogger'ların tuş vuruşlarınızı kaydetmesini engellemek için tuş vuruşu şifreleme araçları kullanın.
**Klavye Bağlantısını Kontrol Edin** | İsteğe Bağlı | Kamuya açık veya tanıdık olmayan bilgisayarları kullanırken donanım keylogger'larına karşı dikkatli olun, klavye bağlantılarını kontrol ederek bunları tespit edin.
**Tuş Vuruşu Enjeksiyon Saldırılarını Önleyin** | İsteğe Bağlı | Uzakta olduğunuzda bilgisayarınızı kilitleyin ve tuş vuruşu enjeksiyon saldırılarına karşı koruma sağlamak için USBGuard veya benzeri araçları kullanmayı düşünün.
**Ücretsiz Ticari Antivirüs Kullanmayın** | İsteğe Bağlı | Dahili güvenlik araçlarına güvenin ve gizlilik ihlali ve veri toplama potansiyelleri nedeniyle ücretsiz antivirüs uygulamalarından kaçının.
**Rootkitler için Periyodik Kontrol Yapın** | Gelişmiş | Tam sistem kontrolü tehditlerini tespit etmek ve önlemek için düzenli olarak rootkitleri kontrol edin, [chkrootkit](https://awesome-privacy.xyz/operating-systems/linux-defenses/chkrootkit) gibi araçları kullanın.
**BIOS Başlangıç Parolası** | Gelişmiş | Önyükleme sırasında ek bir güvenlik katmanı eklemek için BIOS veya UEFI parolasını etkinleştirin, ancak sınırlamalarını bilin.
**Güvenlik Odaklı Bir İşletim Sistemi Kullanın** | Gelişmiş | Geliştirilmiş gizlilik ve güvenlik için Linux'a veya QubeOS veya [Tails](https://awesome-privacy.xyz/operating-systems/desktop-operating-systems/tails) gibi güvenlik odaklı bir dağıtıma geçmeyi düşünün.
**Sanal Makinelerden Yararlanın** | Gelişmiş | Riskli etkinlikler için veya şüpheli yazılımları test etmek için sanal makineleri kullanarak potansiyel tehditleri ana sistemden izole edin.
**Bölümlendirme Yapın** | Gelişmiş | Farklı programları ve veri kaynaklarını mümkün olduğunca birbirinden izole ederek potansiyel ihlallerin kapsamını sınırlayın.
**İstenmeyen Özellikleri Devre Dışı Bırakın (Windows)** | Gelişmiş | Arka planda çalışan gereksiz Windows "özelliklerini" ve hizmetlerini devre dışı bırakarak veri toplama ve kaynak kullanımını azaltın.
**Güvenli Önyükleme** | Gelişmiş | Önyükleyici ve diğer kritik yazılımlarınızı kötü amaçlı yazılımların değiştirmesini önlemek için Güvenli Önyükleme'nin etkin olduğundan emin olun.
**Güvenli SSH Erişimi** | Gelişmiş | SSH erişimini korumak için varsayılan bağlantı noktasını değiştirme, SSH anahtarları kullanma ve güvenlik duvarlarını yapılandırma gibi adımlar atın.
**Kullanılmayan Açık Bağlantı Noktalarını Kapatın** | Gelişmiş | Uzaktan saldırıları önlemek ve güvenliği artırmak için gerekli olmayan harici bağlantı noktalarında dinleyen hizmetleri kapatın.
**Zorunlu Erişim Kontrolü Uygulayın** | Gelişmiş | Bir sistem tehlikeye atıldığında yapılacak olan zararı sınırlamak için ayrıcalıklı erişimi sınırlandırın.
**Canary Token'ları Kullanın** | Gelişmiş | Dosyalarınıza veya e-postalarınıza izinsiz erişimi daha hızlı tespit etmek ve sızıntı hakkında bilgi toplamak için canary token'ları kullanın.

### Tavsiye Edilen Yazılımlar
- [Güvenli İşletim Sistemleri](https://github.com/Lissy93/awesome-privacy#desktop-operating-systems)
- [Linux Savunmaları](https://github.com/Lissy93/awesome-privacy#linux-defences)
- [Windows Savunmaları](https://github.com/Lissy93/awesome-privacy#windows-defences)
- [Mac OS Savunmaları](https://github.com/Lissy93/awesome-privacy#mac-os-defences)
- [Kötü Amaçlı Yazılım Karşıtı](https://github.com/Lissy93/awesome-privacy#anti-malware)
- [Güvenlik Duvarları](https://github.com/Lissy93/awesome-privacy#firewalls-1)
- [Dosya Şifreleme](https://github.com/Lissy93/awesome-privacy#file-encryption)


## Akıllı Ev

Ev asistanları (Google Home, Alexa ve Siri gibi) ve diğer internete bağlı cihazlar büyük miktarda kişisel veri toplarlar (ses örnekleri, konum verileri, ev detayları ve tüm etkileşimlerin günlükleri dahil). Ne toplandığı, nasıl depolandığı ve ne için kullanılacağı konusunda sınırlı kontrolünüz olduğu için, gizlilik ve güvenlik konusunda endişe duyan herkese tüketici akıllı ev ürünlerini önermek zordur.
Güvenlik ve Gizlilik: Piyasada evinizin güvenliğini artırmayı iddia eden birçok akıllı cihaz bulunmaktadır ve bunlar kullanımı kolay ve pratik olmalarıyla dikkat çekerler (Akıllı Hırsız Alarmı, İnternet Güvenlik Kameraları, Akıllı Kilitler ve Uzaktan Erişimli Kapı Zilleri gibi). Bu cihazlar güvenliği artırmak gibi görünebilir, ancak gizlilik açısından bir takas söz konusudur: büyük miktarda kişisel veri toplarlar ve bu verilerin nasıl depolanacağı veya kullanılacağı konusunda size kontrol bırakmazlar. Ayrıca, bu cihazların güvenliği de sorgulanabilir çünkü birçoğu (ve kullanılmaktadır) hacklenebilir, bu da bir saldırganın tespiti minimum çaba ile atlatabilmesine olanak tanır.
En gizliliği koruyan seçenek, evinizde "akıllı" internete bağlı cihazları kullanmamak ve internet bağlantısı gerektiren bir güvenlik cihazına güvenmemektir. Ancak, eğer kullanıyorsanız, ürünün risklerini tam olarak anlamak ve satın almadan önce ayarları düzenlemek önemlidir. Ardından, gizliliği ve güvenliği artırmak için ayarları yapılandırabilirsiniz. Aşağıdaki kontrol listesi, internete bağlı ev cihazlarıyla ilişkilendirilen riskleri azaltmaya yardımcı olacaktır.

**Güvenlik** | **Öncelik** | **Detaylar ve İpuçları**
--- | --- | ---
**Cihazları Marka/Model Belirtmeyecek Şekilde Yeniden Adlandırın** | Temel | Hedeflenmiş saldırıları engellemek için varsayılan cihaz isimlerini, marka veya model bilgisini gizleyecek şekilde genel bir şeye değiştirin.
**Mikrofon ve kamerayı kullanılmadığı zamanlarda devre dışı bırakın** | Temel | Kazara kayıtlara veya hedeflenmiş erişimlere karşı korunmak için akıllı cihazlardaki mikrofonları ve kameraları kapatmak için donanım anahtarları kullanın.
**Toplanan, depolanan ve iletilen verileri anlayın** | Temel | Satın almadan önce akıllı ev cihazlarının veri işleme uygulamaları hakkında araştırma yapın ve bu uygulamalardan rahatsız olmamak için uygunluğunu sağlayın, üçüncü taraflarla veri paylaşan cihazlardan kaçının.
**Gizlilik ayarlarını belirleyin ve üçüncü taraflarla veri paylaşımını reddedin** | Temel | Uygulama ayarlarını en sıkı gizlilik kontrollerine göre ayarlayın ve mümkün olduğunca üçüncü taraflarla veri paylaşımını reddedin.
**Akıllı ev cihazlarınızı gerçek kimliğinizle ilişkilendirmeyin** | Temel | Gizliliği korumak için anonim kullanıcı adları ve şifreleri kullanın, gizliliği korumak için sosyal medya veya diğer üçüncü taraf hizmetleri aracılığıyla kayıt olmayın veya oturum açmayın.
**Firmware güncel tutun** | Temel | Akıllı cihaz yazılımlarını düzenli olarak güncelleyerek güvenlik yamalarını ve iyileştirmeleri uygulayın.
**Ağınızı koruyun** | Temel | Ev WiFi ve ağınızı güvence altına alarak akıllı cihazlara izinsiz erişimi önleyin.
**Takılabilir cihazlardan kaçının** | İsteğe Bağlı | Takılabilir cihazların kapsamlı veri toplama yeteneklerini ve gizlilik açısından olası etkilerini düşünün.
**Evdeki kritik altyapıyı İnternet'e bağlamayın** | İsteğe Bağlı | İnternet bağlantılı termostatlar, alarm sistemleri ve dedektörlerin potansiyel olarak uzaktan erişim risklerini değerlendirin.
**Alexa/Google Home Risklerini Azaltın** | İsteğe Bağlı | [Mycroft](https://awesome-privacy.xyz/smart-home-and-iot/voice-assistants/mycroft) gibi gizlilik odaklı alternatifleri veya sesle çalışan asistanların beklemesini engellemek için Project Alias gibi çözümleri düşünün.
**Ev ağınızı yakından izleyin** | İsteğe Bağlı | FingBox gibi araçları veya yönlendirici özelliklerini kullanarak anormal ağ etkinliğini izleyin.
**İnternet erişimini mümkün olduğunca reddedin** | Gelişmiş | İnternete ihtiyaç duymayan cihazlar için internet erişimini engellemek için güvenlik duvarları kullanın ve işlemi yerel ağ kullanımına sınırlayın.
**Riskleri değerlendirin** | Gelişmiş | Tüm ev üyeleri için gizlilik sonuçlarını göz önünde bulundurun ve güvenlik ve gizlilik için cihaz ayarlarını, örneğin belirli zamanlarda cihazları devre dışı bırakarak, ayarlayın.

### Tavsiye Edilen Yazılımlar
- [Ev Otomasyonu](https://github.com/Lissy93/awesome-privacy#home-automation)
- [Yapay Zeka Ses Asistanları](https://github.com/Lissy93/awesome-privacy#ai-voice-assistants)


## Kişisel Finans

Kredi kartı dolandırıcılığı, kimlik hırsızlığının en yaygın formudur ([yalnızca 2017'de ABD'de 133.015 rapor](https://www.experian.com/blogs/ask-experian/identity-theft-statistics/) edilmiştir), ve toplamda 905 milyon dolarlık bir kayıp yaşanmıştır, bu önceki yıla göre %26 artıştır. Bir kişi başına düşen medyan kayıp miktarı 2017'de 429 dolardır. Kendinizi kurban olmaktan korumak için temel adımlar atmamız daha önemlidir.
Kredi kartları hakkında not: Kredi kartlarında bazı sahtekârlık işlemlerini tespit etmek ve durdurmak için teknolojik yöntemler bulunmaktadır. Büyük ödeme işlemcileri bunu uygular, kart sahiplerinden büyük miktarda veri toplayarak her bir kişinin harcama alışkanlıkları hakkında çok şey bilirler. Bu veri, sahtekârlığı tespit etmek için kullanılır, ancak aynı zamanda diğer veri aracılarına satılır. Dolayısıyla kredi kartları güvenlik açısından iyi olsa da, veri gizliliği açısından korkunçtur.

**Güvenlik** | **Öncelik** | **Detaylar ve İpuçları**
--- | --- | ---
**Dolandırıcılık Uyarılarına ve Kredi İzlemeye Kaydolun** | Temel | Şüpheli faaliyetlerden haberdar olmak için Experian, TransUnion veya Equifax aracılığıyla dolandırıcılık uyarılarını ve kredi izleme hizmetini etkinleştirin.
**Kredi Dondurması Uygulayın** | Temel | Experian, TransUnion ve Equifax aracılığıyla kredi dondurarak izinsiz kredi sorgularını önleyin.
**Sanal Kartlar Kullanın** | İsteğe Bağlı | Gerçek bankacılık bilgilerinizi korumak için çevrimiçi işlemler için sanal kart numaralarını kullanın. [Privacy.com](https://awesome-privacy.xyz/finance/virtual-credit-cards/privacy.com) ve [MySudo](https://awesome-privacy.xyz/finance/virtual-credit-cards/mysudo) gibi hizmetler bu özelliği sunar.
**Yerel İşlemler İçin Nakit Kullanın** | İsteğe Bağlı | Yerel ve günlük alışverişlerde finansal profil oluşturmayı önlemek için [Nakit](https://awesome-privacy.xyz/finance/other-payment-methods/cash) kullanın.
**Çevrimiçi İşlemler İçin Kripto Para Kullanın** | İsteğe Bağlı | Çevrimiçi işlemler için [Monero](https://awesome-privacy.xyz/finance/cryptocurrencies/monero) gibi gizliliğe odaklanmış kripto paraları tercih ederek anonimliği koruyun. Gizliliği sağlamak için kripto paraları dikkatli kullanın.
**Kripto Paraları Güvenli Bir Şekilde Saklayın** | Gelişmiş | Çevrimdışı cüzdan oluşturma, [Trezor](https://awesome-privacy.xyz/finance/crypto-wallets/trezor) veya [ColdCard](https://awesome-privacy.xyz/finance/crypto-wallets/coldcard) gibi donanım cüzdanları kullanarak kripto paraları güvenli bir şekilde saklayın veya [CryptoSteel](https://awesome-privacy.xyz/finance/crypto-wallets/cryptosteel) gibi uzun vadeli saklama çözümlerini düşünün.
**Kripto Para Satın Almayı Anonim Hale Getirin** | Gelişmiş | [LocalBitcoins](https://awesome-privacy.xyz/finance/crypto-exchanges/localbitcoins), [Bisq](https://awesome-privacy.xyz/finance/crypto-exchanges/bisq) veya Bitcoin ATM'leri gibi hizmetler aracılığıyla kimliğinizle ilişkilendirmeden kripto paralar satın alın.
**Kripto Paraları Karıştırın** | Gelişmiş | Bitcoin'i para birimine çevirmeden önce bir bitcoin karıştırıcısı veya CoinJoin kullanarak işlem izlerini gizleyin.
**Çevrimiçi Alışveriş İçin Takma Bilgiler Kullanın** | Gelişmiş | Çevrimiçi alışverişler için takma bilgiler, yönlendirilen e-posta adresleri, VOIP numaraları ve güvenli teslimat yöntemleri kullanarak kimliğinizi koruyun.
**Alternatif Teslimat Adresi Kullanın** | Gelişmiş | PO Box'lar, yönlendirme adresleri veya yerel teslimat noktaları gibi kişisel olmayan adreslere teslimat yapmayı tercih ederek alımlarınızı doğrudan sizinle ilişkilendirmeyin.

### Tavsiye Edilen Yazılımlar
- [Sanal Kredi Kartları](https://github.com/Lissy93/awesome-privacy#virtual-credit-cards)
- [Kripto Paralar](https://github.com/Lissy93/awesome-privacy#cryptocurrencies)
- [Kripto Cüzdanlar](https://github.com/Lissy93/awesome-privacy#crypto-wallets)
- [Kripto Borsaları](https://github.com/Lissy93/awesome-privacy#crypto-exchanges)
- [Diğer Ödeme Yöntemleri](https://github.com/Lissy93/awesome-privacy#other-payment-methods)
- [Bütçe Takip Araçları](https://github.com/Lissy93/awesome-privacy#budgeting-tools)


## İnsan Faktörü

Birçok veri ihlali, hack ve saldırı insan hatası nedeniyle gerçekleşir. Aşağıdaki liste, bunun size olmasını önlemek için almanız gereken adımları içerir. Bunların birçoğu genelde mantıklı olsa da, dikkate alınmaya değerdir.

**Güvenlik** | **Öncelik** | **Detaylar ve İpuçları**
--- | --- | ---
**Alıcıları Doğrulayın** | Temel | E-postalar kolayca sahte olabilir. Özellikle hassas işlemler için gönderenin kimliğini doğrulayın ve e-postalardaki bağlantılara tıklamak yerine URL'leri manuel olarak girin.
**Popup Bildirimlerine Güvenmeyin** | Temel | Sahte popuplar kötü niyetli kişiler tarafından kullanılabilir. Bir popup'ta herhangi bir bilgi girmeden önce URL'yi kontrol edin.
**Cihazı Gözetimsiz Bırakmayın** | Temel | Gözetimsiz bırakılan cihazlar güçlü şifrelerle bile tehlikeye atılabilir. Kaybolan cihazlar için Şimdi Bul gibi şifreleme ve uzaktan silme özelliklerini kullanın.
**Kameraların Kullanımını Engelleme** | Temel | Kamera kapakları ve mikrofon blokerleri kullanarak kameralara karşı korunun. Ev asistanlarını kullanmadığınız zamanlarda veya hassas konuları tartışmadığınız zamanlarda sessize alın.
**Omuz Sörfçülerinden Korunun** | Temel | Halka açık alanlarda ekranınızı okuyanları engellemek için dizüstü bilgisayarlar ve mobil cihazlarda gizlilik ekranları kullanın.
**Balık Avı Saldırılarını Tanıyın** | Temel | Balık avı girişimlerinden şüphelenin. URL'leri doğrulayın, alınan mesajların bağlamını kontrol edin ve 2FA gibi iyi güvenlik uygulamalarını kullanın ve şifreleri yeniden kullanmayın.
**Stalkerware'lere Dikkat Edin** | Temel | Arkadaşlar tarafından casusluk için yüklenen stalkerware'lere dikkat edin. Anormal pil kullanımı gibi işaretlere dikkat edin ve şüphelenilen durumlarda fabrika ayarlarına sıfırlama yapın.
**Güvenilir Kaynaklardan Güvenilir Yazılımlar Kurun** | Temel | Yazılımları yalnızca meşru kaynaklardan indirin ve dosyaları [Virus Total](https://awesome-privacy.xyz/security-tools/online-tools/virus-total) gibi araçlarla kontrol edin.
**Kişisel Verileri Güvenli Bir Şekilde Saklayın** | Temel | Cihazlarda veya bulutta bulunan tüm kişisel verilerin şifrelenmiş olduğundan emin olun, yetkisiz erişime karşı koruma sağlar.
**Belgelerde Kişisel Detayları Gizleyin** | Temel | Belgeleri paylaşırken, kişisel detayları opak dikdörtgenlerle gizleyerek bilgi sızıntısını önleyin.
**Bir Site'nin Güvende Olduğunu Varsaymayın, Sadece `HTTPS` olduğu için** | Temel | HTTPS bir web sitesinin meşruiyetini garanti etmez. URL'leri doğrulayın ve kişisel verilerle dikkatli olun.
**Online Ödemelerde Sanal Kartlar Kullanın** | İsteğe Bağlı | Bankacılık detaylarınızı korumak ve işlem risklerini sınırlamak için online ödemelerde sanal kartlar kullanın.
**Uygulama İzinlerini Gözden Geçirin** | İsteğe Bağlı | Düzenli olarak uygulama izinlerini gözden geçirin ve yönetin, hassas cihaz özelliklerine gereksiz erişimi önlemek için.
**Halka Açık Listelerden Çıkın** | İsteğe Bağlı | Kendinizi halka açık veritabanlarından ve pazarlama listelerinden çıkararak istenmeyen iletişimleri ve potansiyel riskleri azaltın.
**Veri Hizmetlerinden Opt-Out Yaparken Asla Ek PII Sağlamayın** | İsteğe Bağlı | Veri hizmetlerinden çıkarken daha fazla kişisel bilgi sağlamayın, daha fazla veri toplamaktan kaçının.
**Veri Paylaşımından Opt-Out Yapın** | İsteğe Bağlı | Birçok uygulama ve hizmet, veri paylaşım ayarlarını varsayılan olarak belirler. Verilerinizin üçüncü taraflarla paylaşılmasını önlemek için opt-out yapın.
**Sosyal Medya Gizliliğini İnceleyin ve Güncelleyin** | **İsteğe Bağlı** | Sosyal medya ayarlarınızı düzenli olarak kontrol edin ve güncelleyin, çünkü sık sık yapılan hüküm güncellemeleri gizlilik ayarlarınızı etkileyebilir.
**Bölütleme** | **Gelişmiş** | Dijital aktivitelerin farklı alanlarını ayırarak, bir ihlal durumunda veri maruziyetini sınırlayın.
**WhoIs Gizlilik Koruması** | **Gelişmiş** | Kişisel bilgilerinizi genel aramalardan korumak için alan adı kayıtları için WhoIs Gizlilik Koruması kullanın.
**Yönlendirme Adresi Kullanın** | **Gelişmiş** | Posta kutusu veya yönlendirme adresi kullanarak postalarınızda gerçek adresinizi saklayarak, gizlilik korumasına bir katman ekleyin.
**Anonim Ödeme Yöntemleri Kullanın** | **Gelişmiş** | Çevrimiçi tanımlanabilir bilgiler girmekten kaçınmak için kripto para gibi anonim ödeme yöntemlerini tercih edin.


## Fiziksel Güvenlik

Kamu kayıtları genellikle hassas kişisel veriler içerir (tam ad, doğum tarihi, telefon numarası, e-posta, adres, etnisite vb.) ve nüfus kayıtları, doğum/ölüm/evlilik belgeleri, seçmen kayıtları, pazarlama bilgileri, müşteri veritabanları, motorlu taşıt kayıtları, mesleki/iş lisansları ve tüm mahkeme dosyaları gibi çeşitli kaynaklardan toplanır. Bu hassas kişisel bilgilere [kolay ve yasal bir şekilde erişim](https://www.consumerreports.org/consumerist/its-creepy-but-not-illegal-for-this-website-to-provide-all-your-public-info-to-anyone/) mümkündür, bu durum [ciddi gizlilik endişeleri](https://privacyrights.org/resources/public-records-internet-privacy-dilemma) doğurur (kimlik hırsızlığı, kişisel güvenlik riskleri/takipçiler, itibarın zarar görmesi, dosya toplumları).

Kapalı Devre Televizyon Sistemi (CCTV), şirketlerin, bireylerin ve devletin hareketlerinizi takip ettiği başlıca yöntemlerden biridir. Londra, İngiltere'de bir ortalama insanın günlük olarak yaklaşık 500 kez kamera tarafından kaydedildiği bilinmektedir. Bu ağın büyümesi devam etmekte ve birçok şehirde yüz tanıma teknolojisinin kullanımı artmaktadır, bu da devletin görüntülerdeki kişilerin kimliğini gerçek zamanlı olarak bilmesini sağlar.
Güçlü kimlik doğrulama, şifrelenmiş cihazlar, güncellenmiş yazılım ve anonim web taraması, fiziksel olarak sizin, cihazlarınızın ve verilerinizin tehlikeye atılabileceği durumlarda çok az fayda sağlayabilir. Bu bölüm, fiziksel güvenlik için temel yöntemleri açıklamaktadır.

**Güvenlik** | **Öncelik** | **Detaylar ve İpuçları**
--- | --- | ---
**Hassas Belgeleri Yok Edin** | Temel | Kimlik hırsızlığına karşı koruma sağlamak ve gizliliği korumak için hassas belgeleri parçalayın veya sansüre edin.

**Kamu Kayıtlarından Çıkış Yapın** | Temel | Kişisel bilgilerinizi gösteren listelerden çıkmak için kişi arama web siteleri ile iletişime geçin. Michael Bazzell'ın Kişisel Veri Kaldırma Çalışma Kitabı gibi rehberlerden yararlanabilirsiniz.

**Belgelere Filigran Ekleyin** | Temel | Kişisel belgelerin dijital kopyalarına alıcının adı ve tarihi ile filigran ekleyerek ihlalin kaynağını takip edebilirsiniz.

**Gelen Aramalarda Bilgi Vermeyin** | Temel | Sadece başlattığınız aramalarda kişisel verilerinizi paylaşın ve alıcının telefon numarasını doğrulayın.

**Dikkatli Olun** | Temel | Çevrenizi dikkatlice gözlemleyin ve yeni ortamlarda olası riskleri değerlendirin.

**Güvenli Çevre** | Temel | Kişisel bilgileri barındıran lokasyonların fiziksel güvenliğini sağlayın, dış erişimi en aza indirin ve sızma tespit sistemleri kullanın.
**Fiziksel Güvenlik Önlemleri** | Temel | Kensington kilitleme cihazları, web kamerası kapakları ve gizlilik perdeleri gibi fiziksel güvenlik önlemleri kullanın.
**Cihazları Doğrudan Görüşten Uzak Tutun** | Temel | Cihazların dışarıdan görülmesini engelleyerek lazer ve hırsızlık risklerini azaltın.
**PIN'inizi Koruyun** | Temel | PIN girişinizi gözleyicilerden ve kameralardan koruyun ve dokunmatik ekranları kullanımdan sonra temizleyin.
**Skimmer Kontrolü Yapın** | Temel | ATM'leri ve kamu cihazlarını kullanmadan önce skimmer cihazları ve manipülasyon işaretlerini kontrol edin.
**Ev Adresinizi Koruyun** | İsteğe Bağlı | Ev adresinizi korumak için alternatif lokasyonlar, yönlendirme adresleri ve anonim ödeme yöntemleri kullanın.
**PIN Kullanın, Biyometri Kullanmayın** | Gelişmiş | Cihaz güvenliğinde yasal zorlama durumlarında biyometri yerine PIN kullanmayı tercih edin.
**CCTV Maruziyetini Azaltın** | Gelişmiş | Gözetimden kaçınmak için maskeler takın ve daha az kamera bulunan güzergahları tercih edin.
**Yüz Tanıma Karşıtı Giysiler** | Gelişmiş | Yüz tanıma teknolojisini aldatan desenlerde giysiler giyin.
**Gece Görüş Maruziyetini Azaltın** | Gelişmiş | Gece görüş kameralarını engellemek için IR ışık kaynakları veya yansıtıcı gözlükler kullanın.
**DNA'nızı Koruyun** | Gelişmiş | DNA'nızı miras siteleriyle paylaşmaktan kaçının ve DNA izlerini bırakmada dikkatli olun.



<!-- checklist-end -->

----

#### Etkileşimli bir sürüm var!
- [Dijital Savunma](https://digital-defense.io) - Detayları görüntüleyin, maddeleri kontrol edin ve ilerlemenizi takip edin

#### Diğer Harika Güvenlik Listeleri
- @sbilly/[harika-guvenlik](https://github.com/sbilly/awesome-security)
- @0x4D31/[harika-tehdit-tespiti](https://github.com/0x4D31/awesome-threat-detection)
- @hslatman/[harika-tehdit-istihbarati](https://github.com/hslatman/awesome-threat-intelligence)
- @PaulSec/[harika-guvenlik-konferanslari](https://github.com/PaulSec/awesome-sec-talks)
- @Lissy93/[harika-gizlilik](https://github.com/lissy93/awesime-privacy)
- @Zbetcheckin/[guvenlik_listesi](https://github.com/zbetcheckin/Security_list)
- Michael Horowitz / [savunmacomputingkontrol.com](https://defensivecomputingchecklist.com/)

[Daha Fazla Görüntüle](/4_Privacy_And_Security_Links.md#other-github-security-lists)

----
## Duyuru

*Önemli Duyuru : Bu metin tamamen GPT-3.5 tarafından çevrilmiştir ve tam anlamıyla gerçeği yansıtmamış olabilir. Yazım hataları kesinlikle bulunabilir, lütfen sadece rehber amaçlı olarak kendi kontrolünüzle kullanın.

## Notlar

*Ziyaretiniz için teşekkür ederiz, umarız burada yararlı bilgiler bulmuşsunuzdur :) Katkılarınızı bekliyoruz ve takdir ediyoruz - düzenleme önermek için [bir sorun açın](https://github.com/Lissy93/personal-security-checklist/issues/new/choose), veya [bir PR açın](https://github.com/Lissy93/personal-security-checklist/pull/new/master). Detaylar için: [`CONTRIBUTING.md`](/.github/CONTRIBUTING.md).*

*Not: Bu liste eksiksiz değildir ve sadece bir rehber olarak kabul edilmelidir.*

*Creative Commons, CC BY 4.0 lisansı altında lisanslanmıştır, © [Alicia Sykes](https://aliciasykes.com) 2020*

[![Attribution 4.0 International](https://licensebuttons.net/l/by/3.0/88x31.png)](/LICENSE.md)

---

Bu projenin sürekli gelişimine destek olmak için yardımcı olun 💖

[![Sponsor Lissy93 on GitHub](https://img.shields.io/badge/Sponsor_on_GitHub-Lissy93-%23ff4dda?style=for-the-badge&logo=githubsponsors&logoColor=ff4dda)](https://github.com/sponsors/Lissy93)

----

Found this helpful? Consider sharing it with others, to help them also improve their digital security 😇

[![Share on Twitter](https://img.shields.io/badge/Share-Twitter-17a2f3?style=for-the-badge&logo=Twitter)](http://twitter.com/share?text=Check%20out%20the%20Personal%20Cyber%20Security%20Checklist-%20an%20ultimate%20list%20of%20tips%20for%20protecting%20your%20digital%20security%20and%20privacy%20in%202020%2C%20with%20%40Lissy_Sykes%20%F0%9F%94%90%20%20%F0%9F%9A%80&url=https://github.com/Lissy93/personal-security-checklist)
[![Share on LinkedIn](https://img.shields.io/badge/Share-LinkedIn-0077b5?style=for-the-badge&logo=LinkedIn)](
http://www.linkedin.com/shareArticle?mini=true&url=https://github.com/Lissy93/personal-security-checklist&title=The%20Ultimate%20Personal%20Cyber%20Security%20Checklist&summary=%F0%9F%94%92%20A%20curated%20list%20of%20100%2B%20tips%20for%20protecting%20digital%20security%20and%20privacy%20in%202020&source=https://github.com/Lissy93)
[![Share on Facebook](https://img.shields.io/badge/Share-Facebook-4267b2?style=for-the-badge&logo=Facebook)](https://www.linkedin.com/shareArticle?mini=true&url=https%3A//github.com/Lissy93/personal-security-checklist&title=The%20Ultimate%20Personal%20Cyber%20Security%20Checklist&summary=%F0%9F%94%92%20A%20curated%20list%20of%20100%2B%20tips%20for%20protecting%20digital%20security%20and%20privacy%20in%202020&source=)
[![Share on Mastodon](https://img.shields.io/badge/Share-Mastodon-56a7e1?style=for-the-badge&logo=Mastodon)](https://mastodon.social/web/statuses/new?text=Check%20out%20the%20Ultimate%20Personal%20Cyber%20Security%20Checklist%20by%20%40Lissy93%20on%20%23GitHub%20%20%F0%9F%94%90%20%E2%9C%A8)

---

Get in touch 📬

[![Alicia Sykes on Twitter](https://img.shields.io/twitter/follow/Lissy_Sykes?style=social&logo=twitter)](https://twitter.com/Lissy_Sykes)
[![Alicia Sykes on GitHub](https://img.shields.io/github/followers/lissy93?label=Lissy93&style=social)](https://github.com/Lissy93)
[![Alicia Sykes on Mastodon](https://img.shields.io/mastodon/follow/1032965?domain=https%3A%2F%2Fmastodon.social)](https://mastodon.social/web/accounts/1032965)
[![Alicia Sykes on Keybase](https://img.shields.io/badge/aliciasykes--lightgrey?style=social&logo=Keybase)](https://keybase.io/aliciasykes)
[![Alicia Sykes's PGP](https://img.shields.io/badge/PGP--lightgrey?style=social&logo=Let%E2%80%99s%20Encrypt)](https://keybase.io/aliciasykes/pgp_keys.asc)
[![Alicia Sykes's Website](https://img.shields.io/badge/aliciasykes.com--lightgrey?style=social&logo=Tencent%20QQ)](https://aliciasykes.com)

---
