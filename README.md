# 🐝 Bee Backend

Bee Backend, bir satış (e-commerce) web uygulamasının sunucu tarafı bileşenidir.  
Proje Node.js / TypeScript ve NestJS kullanılarak geliştirilmiştir.

## Özellikler

- Ürün yönetimi (listeleme, ekleme, güncelleme, silme)
- Sipariş yönetimi
- Kullanıcı kimlik doğrulama & yetkilendirme
- API ile iletişim (REST)
- Test altyapısı (unit / e2e)
- Geliştirme ve üretim modları

## Teknolojiler

- **NestJS** — modüler, yapılandırılmış sunucu tarafı mimarisi
- **TypeScript** — statik tip kontrolü
- **Node.js**
- **Express / HTTP** (NestJS üzerinden)
- Testler için: **Jest**, **Supertest** (eğer varsa)
- Diğer yardımcı paketler: `class-validator`, `class-transformer` vb.

## Kurulum ve Çalıştırma

```bash
# Projeyi klonlayın
git clone https://github.com/enesekerr/bee-backend.git
cd bee-backend

# Bağımlılıkları yükleyin
npm install

# Geliştirme modu (hot reload)
npm run start:dev

# Prodüksiyon modu
npm run build
npm run start:prod

# Normal çalıştırma (development)
npm run start
```


# 🐝 Bee Backend

Bee Backend is the server-side component of an e-commerce web application.  
The project is developed using Node.js / TypeScript and NestJS.

## Features

- Product management (listing, adding, updating, deleting)
- Order management
- User authentication & authorization
- API communication (REST)
- Testing infrastructure (unit / e2e)
- Development and production modes

## Technologies

- **NestJS** — modular, structured server-side architecture
- **TypeScript** — static type checking
- **Node.js**
- **Express / HTTP** (via NestJS)
- For testing: **Jest**, **Supertest** (if applicable)
- Other helper packages: `class-validator`, `class-transformer`, etc.

## Installation & Running

```bash
# Clone the project
git clone https://github.com/enesekerr/bee-backend.git
cd bee-backend

# Install dependencies
npm install

# Development mode (hot reload)
npm run start:dev

# Production mode
npm run build
npm run start:prod

# Normal run (development)
npm run start
