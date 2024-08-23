# React Quiz App

Bu proje, [Berkant Kaya'nın](https://www.youtube.com/@BerkantKaya) YouTube kanalında yayınladığı video serisini izleyerek geliştirilmiş bir React Quiz uygulamasıdır. Uygulama, kullanıcıların çeşitli sorulara yanıt vererek puan toplayabileceği basit bir quiz arayüzü sağlar.

## İçindekiler
- [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
- [Kurulum](#kurulum)
- [Proje Yapısı](#proje-yapısı)
- [Ekran Görüntüleri](#ekran-görüntüleri)
- [Rapor](#rapor)

## Kullanılan Teknolojiler
- **React** - Kullanıcı arayüzü oluşturmak için.
- **CSS** - Stil ve düzenleme için.
- **JavaScript** - Mantık ve işlevsellik için.
- **Berkant Kaya'nın YouTube Serisi** - Projenin temelini oluşturmak için izlenen video serisi.

## Kurulum
Projeyi yerel olarak çalıştırmak için aşağıdaki adımları izleyin:

  git clone https://github.com/kullanici_adiniz/react-quizapp.git
  cd quizapp
  npm install
  npm start

## Proje Yapısı

  react-quizapp/
│
├── public/             # Genel dosyalar (index.html, favicon, vb.)
├── src/                # Uygulama kaynak kodları
│   ├── api/            # API ile ilgili dosyalar
│   │   └── api.js      # API bağlantıları ve işlevler
│   ├── components/     # React bileşenleri
│   │   ├── dropdown/   # Dropdown bileşenleri
│   │   │   ├── Dropdown.css
│   │   │   └── Dropdown.jsx
│   │   ├── modal/      # Modal bileşenleri
│   │   │   ├── Modal.css
│   │   │   └── Modal.jsx
│   │   └── questionCard/  # Soru kartı bileşenleri
│   │       ├── QuestionCard.css
│   │       └── QuestionCard.jsx
│   ├── pages/          # Sayfa bileşenleri
│   │   ├── introduce/  # Tanıtım sayfası bileşenleri
│   │   │   ├── Introduce.css
│   │   │   └── Introduce.jsx
│   │   └── quiz/       # Quiz sayfası bileşenleri
│   │       ├── Quiz.css
│   │       └── Quiz.jsx
│   ├── App.css         # Genel stil dosyası
│   ├── App.js          # Ana uygulama bileşeni
│   ├── index.css       # Genel stil dosyası
│   └── index.js        # Giriş noktası
│
├── .gitignore          # Git'i hariç tutulan dosyalar
├── package-lock.json   # Proje bağımlılıkları
├── package.json        # Proje bilgileri ve bağımlılıkları
└── README.md           # Proje açıklamaları (bu dosya)

## Ekran Görüntüleri

![Ekran Resmi 2024-08-23 15 02 50](https://github.com/user-attachments/assets/98332da0-9157-4ad0-ae14-81385963b0c2)
![Ekran Resmi 2024-08-23 15 03 17](https://github.com/user-attachments/assets/564715a6-ea8e-445d-9aff-2927bca7d8aa)
![Ekran Resmi 2024-08-23 15 03 41](https://github.com/user-attachments/assets/1b4409fa-b11d-4489-be2f-bd7c46d21425)

## Rapor
- 1. gün: Videonun baş kısmını izleyip react kurulumu ve pages sayfalarının işlevselliklerini ve css kısımlarını hallettim.
- 2. gün: Videonun devamındaki component kısımlarının kodlamasını hallettim. Commit işlemlerini halledip projemi github'a yükledim.


