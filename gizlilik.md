---
title: Nerola Gizlilik Politikası
---

# Nerola Gizlilik Politikası

[English version](./privacy)

Yürürlük tarihi: 15 Eylül 2026
Veri sorumlusu: Tolga Sayan (bireysel geliştirici; App Store satıcı adı)
İletişim: tolgasayan@icloud.com

Nerola, cevapların yazılarak verildiği bir İngilizce kelime oyunudur. Bu politika, Nerola iOS uygulamasını kullanırken hangi verilerin nasıl işlendiğini açıklar. Tek başınıza oynamak için hesap açmanız, ad veya e-posta vermeniz gerekmez. İsteğe bağlı arkadaş yarışında görünen bir ad seçersiniz; takma ad yeterlidir.

## 1. Cihazınızda kalan veriler
Aşağıdaki yarış özellikleri dışında şu veriler cihazınızda saklanır:
- uygulama dili, seviye seçimi ve kurulum tamamlandı bilgisi,
- tur geçmişi, puanlar, öğrenme listesi, tekrar kelimeleri ve rozetler,
- sözlük yer imleri, telaffuz lehçesi (ABD/İngiltere) ve yavaş okuma tercihi,
- günlük yeni tur hakkının kullanım kaydı.
Uygulamayı sildiğinizde bu veriler cihazınızdan silinir. Yedekleme ayarlarınız açıksa Apple'ın cihaz yedeklemesine dahil olabilir; bu yedekleme Apple'ın koşullarına tabidir.

## 2. Yazılı cevaplar
Cevaplarınızı klavyeyle harf boşluklarına yazarsınız. Nerola yazdığınız kelimeleri cihazınızda değerlendirir. Uygulama mikrofon veya konuşma tanıma izni istemez, mikrofonu açmaz ve tanıma amacıyla ses göndermez. Tek kişilik turlardaki yazılı cevaplar yerel tur geçmişinizde kalır. Arkadaş yarışındaki cevaplar ayrıca aşağıda açıklanan yarış hizmetine gönderilir; cevaplar analiz hizmetine gönderilmez. iOS'un veya yüklediğiniz klavyenin sunduğu özellikler, ilgili sağlayıcının ayarlarına ve gizlilik politikasına tabidir.

### İsteğe bağlı arkadaş yarışı
İki kişilik oda oluşturduğunuzda veya odaya katıldığınızda seçtiğiniz ad, odaya özel rastgele erişim bilgisi, seviye, içerik sürümü, gönderdiğiniz cevaplar ve yarış olayları Cloudflare üzerinde çalışan yarış hizmetimize iletilir. Hizmet erişim bilgisinin özetini saklar, cevapları değerlendirir ve geçen süreyi hesaplar. Oda arkadaşınız adınızı ve hazır durumunuzu görür; iki taraf bitirince veya süre dolunca puanlar ve cevap ayrıntıları iki oyuncuya açılır. Rehbere, telefon numarasına veya mikrofona erişilmez. Davet iOS paylaşım ekranıyla iletilir; seçtiğiniz mesajlaşma uygulaması kendi politikasına göre çalışır.

Oda kayıtları oluşturulduktan sonra en geç 24 saatte silinir; başlamayan odalar 15 dakikada kapanır. Kendi öğrenme geçmişiniz cihazınızda kalır. Hizmet kötüye kullanımı sınırlamak için istek IP adresini işler; IP adresi oda kaydında saklanmaz. Cloudflare da hizmeti sunmak ve korumak için ağ isteklerini işler. Bkz. [Cloudflare gizlilik politikası](https://www.cloudflare.com/privacypolicy/). Odanın süresi dolmadan silinmesini istemek için oda koduyla bize ulaşabilirsiniz.

### İsteğe bağlı Game Center yarışmaları
Game Center kullanırsanız günlük yarışma puanı Apple'a gönderilir ve Game Center oyuncu kimliğinizle ilişkilendirilir. Sıralamadaki görünürlüğünüz Game Center ayarlarınıza bağlıdır. Tek tek yazılı cevaplar Game Center'a gönderilmez.

## 3. Telaffuz sesleri
Sözlükteki telaffuz sesleri cihazınızın kendi seslendirme motoruyla üretilir; bunun için ağ bağlantısı kullanılmaz.

## 4. Satın almalar ve Nerola Plus
Nerola Plus'ı satın alırsanız ödeme Apple App Store üzerinden yapılır; kart bilgileriniz bize ulaşmaz. Satın alma ve Plus erişim durumunu yönetmek için iki hizmet sağlayıcı kullanırız:
- RevenueCat: satın alma kaydınızı ve Plus erişim durumunuzu tutar.
- Superwall: Nerola Plus teklif ekranını gösterir.
Bu sağlayıcılara, uygulama kurulumunda üretilen rastgele bir kimlik (ad veya e-posta içermez) iletilir. Bu kimlik aynı kurulumda kalıcıdır; uygulamayı silip yeniden kurduğunuzda yenisi üretilir. Satın alma geçmişiniz bu kimliğe bağlıdır.
SDK veri işlemesi yalnız satın alma yaptıktan sonra başlamaz. Mevcut yapıda RevenueCat, public anahtarı yapılandırılmışsa uygulama açılışında başlatılır ve erişim durumu sorgulanır. Superwall ise satış özelliği ve anahtarları etkin olduğunda başlatılır; teklif ekranını gören ücretsiz kullanıcıların verilerini de işleyebilir.
Sağlayıcıların SDK'ları çalışmak için ayrıca şu verileri işler:
- RevenueCat: App Store satın alma makbuzu ve Plus erişim durumu, uygulama sürümü, cihaz platformu ve işletim sistemi sürümü. RevenueCat bu verileri satın alma doğrulaması ve kendi panelindeki toplu istatistikler için işler; reklam kimliği (IDFA) toplanmaz.
- Superwall: teklif ekranını hangi cihazlara göstereceğine karar vermek ve teklif ekranı istatistiklerini tutmak için cihaz özellikleri (Apple'ın uygulama satıcısına özgü cihaz kimliği, cihaz modeli, işletim sistemi sürümü, dil ve bölge, saat dilimi, uygulama sürümü ve kurulum tarihi, ağ türü, düşük güç modu, açık/koyu görünüm), teklif ekranıyla etkileşimler (görüntüleme, kapatma, satın alma denemesi) ve Plus erişim durumu. Superwall, isteğin geldiği IP adresinden yaklaşık ülke/bölge/şehir çıkarabilir; bu bilgi hassas konum değildir ve uygulama konum izni istemez.
Mevcut uygulama entegrasyonu bu verileri reklam amacıyla veya Apple'ın tanımındaki uygulamalar arası izleme için kullanmaz. Sağlayıcıların işlemesi için: [RevenueCat gizlilik politikası](https://www.revenuecat.com/privacy) ve [veri işleme eki](https://www.revenuecat.com/dpa); [Superwall gizlilik politikası](https://superwall.com/legal/privacy-policy) ve [veri işleme eki](https://superwall.com/legal/dpa). Sağlayıcılar bu verileri kendi politikalarındaki sürelerle saklar; satın alma kaydınızın silinmesini isterseniz 7. bölümdeki adrese yazın, talebi sağlayıcılara iletiriz.
Ücretsiz sürümde sözlük, telaffuz dinleme, öğrenme listesi ve rozetler herkes için açıktır; Plus yalnız günlük yeni tur sınırını kaldırır.

## 5. Reklam, izleme ve analitik
Nerola reklam göstermez, reklam ağlarıyla veri paylaşmaz ve sizi uygulamalar veya web siteleri arasında izlemez (Apple'ın "izleme" tanımı anlamında). Uygulamanın kendi kullanım analitiği veya çökme raporlama hizmeti yoktur: oyun içi davranışınız, cevaplarınız veya sesiniz hiçbir analitik servise gönderilmez. Bunun tek istisnası 4. bölümdeki satın alma sağlayıcılarıdır: satın alma ve teklif ekranı verileri, App Store gizlilik beyanında "Analitik" amacıyla da bildirilir, çünkü sağlayıcılar bunlardan toplu istatistik üretir. Yeni bir analitik veya çökme hizmeti eklenirse bu politika güncellenir ve uygulama içinde duyurulur.

## 6. Çocuklar
Nerola genel kitleye yöneliktir ve 13 yaşın altındaki çocuklara yönelik tasarlanmamıştır. Uygulama e-posta veya konum istemez. İsteğe bağlı arkadaş yarışında görünen bir ad istenir. 4. bölümdeki rastgele kimliğin bir çocuğa ait olduğunu düşünüyorsanız 7. bölümdeki adrese yazın; kaydı sildiririz.

## 7. Haklarınız
Uygulama kişisel verilerinizi bir hesapla ilişkilendirmediği için "cihazınızdaki verileri silme" işlemini uygulamayı silerek kendiniz yapabilirsiniz. Satın alma kaydınızla ilgili talepler (erişim, silme) için tolgasayan@icloud.com adresine rastgele kimliğinizle başvurabilirsiniz; uygulama bu kimliği şu an ekranda göstermediği için başvurunuza satın alma tarihini ve elinizdeki App Store makbuz bilgilerini ekleyin. Kaydı bu bilgilerle eşleştirmeye çalışırız; eşleştirme her durumda mümkün olmayabilir, sonucu size bildiririz. Bu politika 6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK) kapsamında hazırlanmıştır; Avrupa Ekonomik Alanı veya Birleşik Krallık'ta bulunuyorsanız GDPR/UK GDPR kapsamındaki erişim, düzeltme, silme ve itiraz haklarınızı da aynı adres üzerinden kullanabilirsiniz.

## 8. Değişiklikler
Politika değiştiğinde yürürlük tarihi güncellenir; önemli değişiklikler uygulama içinde bildirilir.

## 9. Bu web sitesi
Bu sayfalar GitHub Pages üzerinde barındırılır. GitHub, güvenlik amacıyla ziyaretçi IP adreslerini kaydedebilir; bu işleme uygulamadan bağımsızdır ve [GitHub'ın gizlilik bildirimine](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement) tabidir. Bu sitede çerez veya analitik kullanılmaz.
