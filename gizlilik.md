---
title: Harfio Gizlilik Politikası
---

# Harfio Gizlilik Politikası

[English version](./privacy)

Yürürlük tarihi: 15 Eylül 2026
Veri sorumlusu: Tolga Sayan (bireysel geliştirici; App Store satıcı adı)
İletişim: tolgasayan@icloud.com

Harfio, sesli İngilizce kelime oyunudur. Bu politika, Harfio iOS uygulamasını kullanırken hangi verilerin nasıl işlendiğini açıklar. Uygulamayı kullanmak için hesap açmanız, ad veya e-posta vermeniz gerekmez.

## 1. Cihazınızda kalan veriler
Aşağıdaki veriler yalnızca cihazınızda saklanır, tarafımıza veya başka bir sunucuya gönderilmez:
- uygulama dili, seviye seçimi ve kurulum tamamlandı bilgisi,
- tur geçmişi, puanlar, öğrenme listesi, tekrar kelimeleri ve rozetler,
- sözlük yer imleri, telaffuz lehçesi (ABD/İngiltere) ve yavaş okuma tercihi,
- günlük yeni tur hakkının kullanım kaydı.
Uygulamayı sildiğinizde bu veriler cihazınızdan silinir. Yedekleme ayarlarınız açıksa Apple'ın cihaz yedeklemesine dahil olabilir; bu yedekleme Apple'ın koşullarına tabidir.

## 2. Mikrofon ve konuşma tanıma
Cevaplarınızı sesle verirsiniz. Mikrofon yalnızca cevap verirken açılır ve ses, söylediğiniz kelimeyi anlamak için işlenir.
- iOS 26 ve sonrasında, cihazınız Apple'ın cihaz içi konuşma analizini destekliyorsa tanıma tamamen cihazınızda yapılır; ses cihazınızdan çıkmaz. Bunun için Apple'dan bir dil modeli indirilebilir; bu indirme ses içermez.
- Daha eski iOS sürümlerinde veya cihaz içi analiz desteklenmiyorsa Apple'ın konuşma tanıma çerçevesi kullanılır. Cihazınız cihaz içi tanımayı destekliyorsa uygulama bunu zorunlu kılar ve ses cihazınızdan çıkmaz; desteklemiyorsa ses, tanıma için Apple'ın sunucularına gönderilir ve Apple'ın gizlilik koşullarına göre işlenir (https://www.apple.com/legal/privacy/data/en/ask-siri-dictation/).
Harfio oyun sırasında ses kaydı saklamaz ve ses verisini bize ait bir sunucuya göndermez.
Mağaza sürümünde geliştirme amaçlı ses tanısı ekranı ve deneme aşamasındaki üçüncü taraf tanıma pilotu bulunmaz; bunlar yalnız geliştirici derlemelerinde vardır. Ses, yalnız cihazınızda ya da yukarıda açıklanan durumda Apple tarafından işlenir.

## 3. Telaffuz sesleri
Sözlükteki telaffuz sesleri cihazınızın kendi seslendirme motoruyla üretilir; bunun için ağ bağlantısı kullanılmaz.

## 4. Satın almalar ve Harfio Plus
Harfio Plus'ı satın alırsanız ödeme Apple App Store üzerinden yapılır; kart bilgileriniz bize ulaşmaz. Satın alma ve Plus erişim durumunu yönetmek için iki hizmet sağlayıcı kullanırız:
- RevenueCat: satın alma kaydınızı ve Plus erişim durumunuzu tutar.
- Superwall: Harfio Plus teklif ekranını gösterir.
Bu sağlayıcılara, uygulama kurulumunda üretilen rastgele bir kimlik (ad veya e-posta içermez) iletilir. Bu kimlik aynı kurulumda kalıcıdır; uygulamayı silip yeniden kurduğunuzda yenisi üretilir. Satın alma geçmişiniz bu kimliğe bağlıdır.
SDK veri işlemesi yalnız satın alma yaptıktan sonra başlamaz. Mevcut yapıda RevenueCat, public anahtarı yapılandırılmışsa uygulama açılışında başlatılır ve erişim durumu sorgulanır. Superwall ise satış özelliği ve anahtarları etkin olduğunda başlatılır; teklif ekranını gören ücretsiz kullanıcıların verilerini de işleyebilir.
Sağlayıcıların SDK'ları çalışmak için ayrıca şu verileri işler:
- RevenueCat: App Store satın alma makbuzu ve Plus erişim durumu, uygulama sürümü, cihaz platformu ve işletim sistemi sürümü. RevenueCat bu verileri satın alma doğrulaması ve kendi panelindeki toplu istatistikler için işler; reklam kimliği (IDFA) toplanmaz.
- Superwall: teklif ekranını hangi cihazlara göstereceğine karar vermek ve teklif ekranı istatistiklerini tutmak için cihaz özellikleri (Apple'ın uygulama satıcısına özgü cihaz kimliği, cihaz modeli, işletim sistemi sürümü, dil ve bölge, saat dilimi, uygulama sürümü ve kurulum tarihi, ağ türü, düşük güç modu, açık/koyu görünüm), teklif ekranıyla etkileşimler (görüntüleme, kapatma, satın alma denemesi) ve Plus erişim durumu. Superwall, isteğin geldiği IP adresinden yaklaşık ülke/bölge/şehir çıkarabilir; bu bilgi hassas konum değildir ve uygulama konum izni istemez.
Mevcut uygulama entegrasyonu bu verileri reklam amacıyla veya Apple'ın tanımındaki uygulamalar arası izleme için kullanmaz. Sağlayıcıların işlemesi için: [RevenueCat gizlilik politikası](https://www.revenuecat.com/privacy) ve [veri işleme eki](https://www.revenuecat.com/dpa); [Superwall gizlilik politikası](https://superwall.com/legal/privacy-policy) ve [veri işleme eki](https://superwall.com/legal/dpa). Sağlayıcılar bu verileri kendi politikalarındaki sürelerle saklar; satın alma kaydınızın silinmesini isterseniz 7. bölümdeki adrese yazın, talebi sağlayıcılara iletiriz.
Ücretsiz sürümde sözlük, telaffuz dinleme, öğrenme listesi ve rozetler herkes için açıktır; Plus yalnız günlük yeni tur sınırını kaldırır.

## 5. Reklam, izleme ve analitik
Harfio reklam göstermez, reklam ağlarıyla veri paylaşmaz ve sizi uygulamalar veya web siteleri arasında izlemez (Apple'ın "izleme" tanımı anlamında). Uygulamanın kendi kullanım analitiği veya çökme raporlama hizmeti yoktur: oyun içi davranışınız, cevaplarınız veya sesiniz hiçbir analitik servise gönderilmez. Bunun tek istisnası 4. bölümdeki satın alma sağlayıcılarıdır: satın alma ve teklif ekranı verileri, App Store gizlilik beyanında "Analitik" amacıyla da bildirilir, çünkü sağlayıcılar bunlardan toplu istatistik üretir. Yeni bir analitik veya çökme hizmeti eklenirse bu politika güncellenir ve uygulama içinde duyurulur.

## 6. Çocuklar
Harfio genel kitleye yöneliktir ve 13 yaşın altındaki çocuklara yönelik tasarlanmamıştır. Uygulama hesap, ad, e-posta veya konum istemez. 4. bölümdeki rastgele kimliğin bir çocuğa ait olduğunu düşünüyorsanız 7. bölümdeki adrese yazın; kaydı sildiririz.

## 7. Haklarınız
Uygulama kişisel verilerinizi bir hesapla ilişkilendirmediği için "cihazınızdaki verileri silme" işlemini uygulamayı silerek kendiniz yapabilirsiniz. Satın alma kaydınızla ilgili talepler (erişim, silme) için tolgasayan@icloud.com adresine rastgele kimliğinizle başvurabilirsiniz; uygulama bu kimliği şu an ekranda göstermediği için başvurunuza satın alma tarihini ve elinizdeki App Store makbuz bilgilerini ekleyin. Kaydı bu bilgilerle eşleştirmeye çalışırız; eşleştirme her durumda mümkün olmayabilir, sonucu size bildiririz. Bu politika 6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK) kapsamında hazırlanmıştır; Avrupa Ekonomik Alanı veya Birleşik Krallık'ta bulunuyorsanız GDPR/UK GDPR kapsamındaki erişim, düzeltme, silme ve itiraz haklarınızı da aynı adres üzerinden kullanabilirsiniz.

## 8. Değişiklikler
Politika değiştiğinde yürürlük tarihi güncellenir; önemli değişiklikler uygulama içinde bildirilir.

## 9. Bu web sitesi
Bu sayfalar GitHub Pages üzerinde barındırılır. GitHub, güvenlik amacıyla ziyaretçi IP adreslerini kaydedebilir; bu işleme uygulamadan bağımsızdır ve [GitHub'ın gizlilik bildirimine](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement) tabidir. Bu sitede çerez veya analitik kullanılmaz.
