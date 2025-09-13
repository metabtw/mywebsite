# 🚀 CV Website - Muhammed Emin TAHTALI

Modern ve responsive tasarıma sahip kişisel CV websitesi. Next.js, React, TypeScript ve Tailwind CSS kullanılarak geliştirilmiştir.

## 📋 İçindekiler

- [Özellikler](#özellikler)
- [Teknolojiler](#teknolojiler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Proje Yapısı](#proje-yapısı)
- [Bileşenler](#bileşenler)
- [Deployment](#deployment)
- [Katkıda Bulunma](#katkıda-bulunma)

## ✨ Özellikler

- 🎨 **Modern UI/UX**: Gradient renkler ve animasyonlarla zenginleştirilmiş tasarım
- 📱 **Responsive Design**: Tüm cihazlarda mükemmel görünüm
- ⚡ **Hızlı Performans**: Next.js 15 ile optimize edilmiş
- 🌙 **Animasyonlar**: Framer Motion ile akıcı geçişler
- 📧 **İletişim Formu**: Doğrudan iletişim kurma imkanı
- 📄 **CV İndirme**: PDF formatında CV indirme özelliği
- 🔗 **Sosyal Medya Entegrasyonu**: GitHub, LinkedIn, Instagram bağlantıları
- 🎯 **SEO Optimized**: Arama motorları için optimize edilmiş

## 🛠 Teknolojiler

### Frontend
- **Next.js 15** - React framework
- **React 19** - UI kütüphanesi
- **TypeScript** - Type safety
- **Tailwind CSS 4** - Utility-first CSS framework

### UI Bileşenleri
- **Radix UI** - Accessible UI primitives
- **Lucide React** - İkon kütüphanesi
- **Framer Motion** - Animasyon kütüphanesi
- **Class Variance Authority** - Component variants

### Geliştirme Araçları
- **ESLint** - Code linting
- **PostCSS** - CSS processing
- **TypeScript** - Static type checking

## 🚀 Kurulum

### Gereksinimler
- Node.js 18+ 
- npm, yarn, pnpm veya bun

### Adımlar

1. **Projeyi klonlayın**
   ```bash
   git clone https://github.com/metabtw/cv-website.git
   cd cv-website
   ```

2. **Bağımlılıkları yükleyin**
   ```bash
   npm install
   # veya
   yarn install
   # veya
   pnpm install
   ```

3. **Geliştirme sunucusunu başlatın**
   ```bash
   npm run dev
   # veya
   yarn dev
   # veya
   pnpm dev
   ```

4. **Tarayıcıda açın**
   [http://localhost:3000](http://localhost:3000) adresine gidin

## 📖 Kullanım

### Geliştirme
```bash
npm run dev      # Geliştirme sunucusunu başlat
npm run build    # Production build oluştur
npm run start    # Production sunucusunu başlat
npm run lint     # Code linting
```

### Kişiselleştirme

1. **Kişisel Bilgiler**: `src/components/sections/` klasöründeki bileşenleri düzenleyin
2. **Profil Fotoğrafı**: `public/profile.jpg` dosyasını değiştirin
3. **CV Dosyası**: `public/cv.pdf` dosyasını güncelleyin
4. **İletişim Bilgileri**: `src/components/sections/contact.tsx` dosyasını düzenleyin

## 📁 Proje Yapısı

```
cv-website/
├── public/                 # Statik dosyalar
│   ├── cv.pdf             # CV dosyası
│   ├── profile.jpg        # Profil fotoğrafı
│   └── ...
├── src/
│   ├── app/               # Next.js App Router
│   │   ├── globals.css    # Global stiller
│   │   ├── layout.tsx     # Ana layout
│   │   └── page.tsx       # Ana sayfa
│   ├── components/
│   │   ├── sections/      # Sayfa bölümleri
│   │   │   ├── hero.tsx   # Hero bölümü
│   │   │   ├── about.tsx  # Hakkımda
│   │   │   ├── skills.tsx # Yetenekler
│   │   │   ├── experience.tsx # Deneyim
│   │   │   ├── education.tsx  # Eğitim
│   │   │   ├── projects.tsx   # Projeler
│   │   │   └── contact.tsx    # İletişim
│   │   └── ui/            # UI bileşenleri
│   │       ├── button.tsx
│   │       ├── card.tsx
│   │       ├── input.tsx
│   │       └── ...
│   └── lib/
│       └── utils.ts       # Yardımcı fonksiyonlar
├── components.json        # shadcn/ui config
├── tailwind.config.js     # Tailwind CSS config
├── tsconfig.json          # TypeScript config
└── package.json           # Proje bağımlılıkları
```

## 🧩 Bileşenler

### Ana Bölümler
- **Hero**: Giriş bölümü ve CTA butonları
- **About**: Kişisel tanıtım ve özgeçmiş
- **Skills**: Teknik yetenekler ve dil seviyeleri
- **Experience**: İş deneyimleri
- **Education**: Eğitim geçmişi
- **Projects**: Projeler ve portfolyo
- **Contact**: İletişim bilgileri ve sosyal medya

### UI Bileşenleri
- **Button**: Özelleştirilebilir buton bileşeni
- **Card**: İçerik kartları
- **Badge**: Etiket bileşeni
- **Progress**: İlerleme çubuğu
- **BackgroundRippleEffect**: Arka plan animasyon efekti

## 🌐 Deployment

### Vercel (Önerilen)
1. [Vercel](https://vercel.com) hesabınıza giriş yapın
2. GitHub repository'nizi bağlayın
3. Otomatik deployment başlayacak

### Netlify
1. `npm run build` komutu ile build alın
2. `out` klasörünü Netlify'a yükleyin

### Manuel Deployment
```bash
npm run build
npm run start
```

## 🤝 Katkıda Bulunma

1. Bu repository'yi fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## 📞 İletişim

- **Email**: tahtalime@gmail.com
- **LinkedIn**: [meta-64us43ku](https://www.linkedin.com/in/meta-64us43ku/)
- **GitHub**: [metabtw](https://github.com/metabtw)
- **Instagram**: [tahtalime](https://www.instagram.com/tahtalime/)

---

⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!
