# House Catalog App

Aplikasi katalog desain rumah berbasis web dengan Docker, React, Express, MySQL, dan Samba.

## 📊 Topologi Komunikasi

Berikut adalah ilustrasi topologi komunikasi antar layanan dalam aplikasi ini:


![Topologi Komunikasi](diagram/topologi-komunikasi.png)

## 📦 Service Ports

- Frontend : 3000
- Backend  : 5001
- Database : 3306
- Samba    : 139, 445

## 🚀 Cara Deploy

```bash
docker compose up --build -d
