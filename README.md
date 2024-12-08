## Realtime Chat App with Firebase
Bu proje, Firebase kullanarak gerçek zamanlı sohbet uygulaması geliştirmeyi amaçlamaktadır. Kullanıcılar anında mesajlaşabilir, sohbet geçmişini görebilir ve farklı odalarda konuşmalar yapabilirler. Firebase, kullanıcı kimlik doğrulama ve veritabanı işlemleri için kullanılmıştır.

## Özellikler
- Gerçek Zamanlı Sohbet: Firebase Realtime Database kullanılarak kullanıcılar arasındaki mesajlar anında senkronize edilir.
- Kullanıcı Kimlik Doğrulama: Firebase Authentication ile kullanıcılar güvenli bir şekilde giriş yapabilir.
- Sohbet Odaları: Kullanıcılar farklı sohbet odalarına katılabilir ve odalar arası geçiş yapabilir.
- Sohbet Geçmişi: Her kullanıcı, sohbet geçmişini görebilir ve önceki mesajlara erişebilir.

## Teknolojiler

Frontend: HTML, CSS, JavaScript
Backend: Firebase Realtime Database, Firebase Authentication

## Başlarken Gereksinimler
Node.js yüklü olmalı.
Firebase hesabı oluşturulmalı ve proje başlatılmalıdır.

## Projeyi Çalıştırma
Bu repository'yi bilgisayarınıza klonlayın:

```bash
git clone https://github.com/sumeyycakir/React-Chat-App-Project-With-Firebase.git
```
Gerekli bağımlılıkları yükleyin:

```bash
npm install
```

## Firebase Konfigürasyonu 
Firebase projenizi oluşturduktan sonra, Firebase Authentication ve Realtime Database'i etkinleştirmeniz gerekir.
Firebase Console üzerinden proje ayarlarınızı alabilir ve bu ayarları firebaseConfig.js dosyasına ekleyebilirsiniz.
Firebase projenizi kurarak, Firebase config bilgilerinizi firebaseConfig.js dosyasına ekleyin.

const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-auth-domain",
  databaseURL: "your-database-url",
  projectId: "your-project-id",
  storageBucket: "your-storage-bucket",
  messagingSenderId: "your-sender-id",
  appId: "your-app-id",
};

## Uygulamayı başlatın:

```bash
cd src
npm run dev
```


