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
