# 📱 ZooBLOCK! — App Store'a Yükleme Rehberi
## MacinCloud + Xcode ile Adım Adım

---

## 🖥️ ADIM 1 — MacinCloud'a Giriş

1. **https://www.macincloud.com** adresine git
2. "Managed Server" planını seç → En ucuz plan yeterli (~$1/saat)
3. Hesap oluştur ve ödeme yap
4. Sana e-posta ile **bağlantı linki** gelecek
5. Tarayıcıdan Mac'e bağlan (Chrome önerilir)

---

## 📁 ADIM 2 — Dosyaları Mac'e Aktar

1. MacinCloud penceresinde **Files** sekmesine tıkla
2. Sana verilen **ZooBLOCK_iOS.zip** dosyasını yükle
3. Mac masaüstüne çıkart:
   ```
   Çift tıkla → Masaüstüne çıkart
   ```

---

## ⚙️ ADIM 3 — Xcode'u Aç

1. MacinCloud'da Xcode zaten kurulu gelir
2. **Finder → Masaüstü → ZooBLOCK_iOS** klasörünü aç
3. `ZooBLOCK.xcodeproj` dosyasına **çift tıkla**
4. Xcode açılacak — ilk açılış 1-2 dk sürebilir

---

## 🔑 ADIM 4 — Apple Hesabını Bağla

1. Xcode menüsü → **Xcode → Settings → Accounts**
2. Sol alttaki **+** butonuna tıkla
3. **Apple ID** seç → Apple Developer e-posta ve şifreni gir
4. Hesabın listeye eklenecek ✅

---

## 🆔 ADIM 5 — Bundle ID Ayarla

1. Sol panelde `ZooBLOCK` projesine tıkla
2. **TARGETS → ZooBLOCK** seç
3. **Signing & Capabilities** sekmesine gel
4. **Team** kısmında kendi hesabını seç
5. **Bundle Identifier** kısmını düzenle:
   ```
   com.ADINSOYADINIZ.ZooBLOCK
   ```
   *(örn: com.ahmetyilmaz.ZooBLOCK)*
6. **Automatically manage signing** ✅ işaretli olsun

---

## 🏗️ ADIM 6 — Archive (Paket) Oluştur

1. Üst menüden hedefi **"Any iOS Device (arm64)"** olarak seç
   *(iPhone simülatörü değil, gerçek cihaz)*
2. Menüden: **Product → Archive**
3. Derleme başlayacak — 3-5 dakika sürer ⏳
4. Tamamlandığında **Organizer** penceresi açılır

---

## 🚀 ADIM 7 — App Store'a Gönder

1. Organizer'da yeni oluşan archive'ı seç
2. Sağdaki **"Distribute App"** butonuna tıkla
3. **"App Store Connect"** seç → Next
4. **"Upload"** seç → Next
5. Tüm seçenekler varsayılan bırak → Next → Next
6. **Upload** butonuna tıkla ✅
7. "Upload Successful" mesajını bekle 🎉

---

## 🌐 ADIM 8 — App Store Connect'te Tamamla

1. **https://appstoreconnect.apple.com** adresine git
2. **My Apps → +** butonuna tıkla → **New App**
3. Şu bilgileri gir:

| Alan | Değer |
|------|-------|
| Platform | iOS |
| Name | ZooBLOCK! |
| Primary Language | Turkish |
| Bundle ID | com.ADINSOYADINIZ.ZooBLOCK |
| SKU | zooblock001 |

4. **Create** → Uygulama oluşturuldu

---

## 📝 ADIM 9 — Uygulama Bilgilerini Doldur

### App Store Açıklaması (Türkçe):
```
ZooBLOCK!, sevimli hayvanları doğru yuvalarına 
yerleştirdiğin eğlenceli bir kaydırma bulmacası!

🦁 Orman, Okyanus, Çiftlik dünyaları
🧩 100'den fazla bölüm
⭐ Yıldız kazanarak ilerle
🎉 Her bölümde konfeti kutlaması

3 yaşından itibaren oynanabilir.
Reklam yok, uygulama içi satın alma yok.
```

### App Store Açıklaması (İngilizce):
```
ZooBLOCK! is a fun sliding puzzle game where you 
guide cute animals to their matching homes!

🦁 Forest, Ocean, and Farm worlds
🧩 100+ levels
⭐ Earn stars as you progress  
🎉 Celebrate with confetti every level

Suitable for ages 3+.
No ads, no in-app purchases.
```

### Anahtar Kelimeler:
```
çocuk oyunu, hayvan, bulmaca, kaydırma, puzzle, kids game, animal, slide
```

---

## 🖼️ ADIM 10 — Ekran Görüntüleri

App Store için ekran görüntüsü gerekli. MacinCloud'da:

1. iPhone simülatörünü aç: **Xcode → Open Simulator**
2. Oyunu çalıştır: **▶ Play** butonu
3. Simülatörde güzel bir ekran aç
4. **Cmd + S** ile ekran görüntüsü al
5. En az 3 farklı ekran görüntüsü al

Gerekli boyutlar:
- iPhone 6.7" (1290 x 2796) — zorunlu
- iPad 12.9" (2048 x 2732) — önerilir

---

## 👶 ADIM 11 — Yaş Derecelendirmesi

1. App Store Connect → **App Information**
2. **Age Rating** kısmında anketi doldur:
   - Tüm şiddet/yetişkin içerik sorularına: **None/No**
3. Sonuç: **4+** olarak ayarlanacak ✅

---

## 💰 ADIM 12 — Fiyatlandırma

1. **Pricing and Availability** sekmesi
2. **Price**: **Free** (Ücretsiz) seç
3. Tüm ülkelerde yayınla ✅

---

## ✅ ADIM 13 — Review'a Gönder

1. Tüm alanlar doldurulduğunda sağ üstte **"Submit for Review"** butonu aktif olur
2. Tıkla → Onayla
3. Apple incelemesi başlar: **1-3 iş günü** sürer
4. E-posta bildirimi gelecek

---

## 🎊 TEBRİKLER!

Oyunun App Store'da yayında! 🚀

---

## ❓ Sık Karşılaşılan Sorunlar

**"No account" hatası:** Xcode Settings'te Apple ID'yi tekrar ekle

**"Bundle ID conflict" hatası:** Bundle Identifier'ı değiştir, başka biri kullanıyor olabilir

**"Missing screenshot" hatası:** Tüm gerekli ekran boyutları için görüntü yüklediğinden emin ol

**Upload çok yavaş:** MacinCloud sunucusunun internet hızına bağlı, bekle

---

*Hazırlayan: Claude AI — Sorularınız için konuşmaya devam edin!*
