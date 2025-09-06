# MindSweeper Web

App Store'da yayınlanan MindSweeper uygulaması için gerekli olan `app-ads.txt` dosyasını barındıran basit website.

## 🚀 Özellikler

- **App-ads.txt Desteği**: Google AdMob reklam kimliği doğrulaması
- **Modern Tasarım**: Responsive ve kullanıcı dostu arayüz
- **Vercel Uyumlu**: Kolayca Vercel'de yayınlanabilir
- **SEO Optimized**: Arama motorları için optimize edilmiş

## 📁 Dosya Yapısı

```
mindsweeperweb/
├── index.html          # Ana sayfa
├── styles.css          # CSS stilleri
├── app-ads.txt         # Reklam kimliği dosyası
├── package.json        # NPM konfigürasyonu
├── vercel.json         # Vercel konfigürasyonu
└── README.md           # Bu dosya
```

## 🔧 Kurulum ve Yayınlama

### 1. Vercel CLI ile Yayınlama

```bash
# Vercel CLI'yi yükleyin (eğer yüklü değilse)
npm install -g vercel

# Proje dizinine gidin
cd mindsweeperweb

# Vercel'e deploy edin
vercel

# Production'a deploy edin
vercel --prod
```

### 2. Vercel Dashboard ile Yayınlama

1. [Vercel Dashboard](https://vercel.com/dashboard)'a gidin
2. "New Project" butonuna tıklayın
3. GitHub repository'nizi bağlayın veya dosyaları yükleyin
4. Deploy butonuna tıklayın

## 📱 App-ads.txt Dosyası

Bu website, aşağıdaki reklam kimliği bilgilerini içerir:

```
google.com, pub-7748234607727707, DIRECT, f08c47fec0942fa0
```

Bu dosya `https://yourdomain.com/app-ads.txt` adresinden erişilebilir olacaktır.

## 🎨 Özelleştirme

### Renkleri Değiştirme

`styles.css` dosyasındaki CSS değişkenlerini düzenleyerek renkleri özelleştirebilirsiniz:

```css
/* Ana gradient renkleri */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### İçerik Güncelleme

`index.html` dosyasını düzenleyerek:
- Uygulama adını değiştirin
- Açıklamaları güncelleyin
- App Store linkini ekleyin

### App-ads.txt Güncelleme

`app-ads.txt` dosyasını düzenleyerek reklam kimliği bilgilerinizi güncelleyin.

## 🔍 SEO ve Performans

- **Meta Tags**: Otomatik olarak eklenmiş
- **Responsive Design**: Tüm cihazlarda uyumlu
- **Fast Loading**: Optimize edilmiş CSS ve HTML
- **Google Fonts**: Hızlı yüklenen fontlar

## 📞 Destek

Herhangi bir sorunuz için:
- GitHub Issues kullanın
- Vercel dokümantasyonunu inceleyin

## 📄 Lisans

MIT License - Detaylar için LICENSE dosyasına bakın.

---

**Not**: Bu website, App Store'da yayınlanan uygulamanızın reklam kimliği doğrulaması için gerekli olan `app-ads.txt` dosyasını barındırmak amacıyla oluşturulmuştur.
