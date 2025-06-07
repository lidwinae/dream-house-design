# House Catalog App

Aplikasi web yang dibangun untuk memenuhi kebutuhan akan sistem katalog aplikasi berbasis web yang membantu untuk menjelajah dan mengelola desain rumah ini bernama Dream House Design. Aplikasi web ini dibagi menjadi tiga orang peran pengguna yakni:

User biasa yang dapat menjelajahi katalog desain rumah yang telah disetujui dan dipublikasikan pada aplikasi.

Designer yang dapat mengunggah file desain rumah melalui aplikasi web yang disimpan dalam shared folder samba.

Admin yang melakukan moderasi desain rumah yang telah diunggah oleh desainer dengan mengakses folder samba, lalu memverifikasi kualitas dan kelayakan desain tersebut, dilanjutkan dengan mengunggah desain rumah ke aplikasi web untuk dipublikasikan dan dilihat oleh user biasa.


## 📊 Topologi Komunikasi

Berikut adalah ilustrasi topologi komunikasi antar layanan dalam aplikasi ini:


![image](https://github.com/lidwinae/dream-house-design/blob/main/diagram/Topologi%20Komunikasi%202.png) 

## 📦 Service Ports

- Frontend : 3000
- Backend  : 5001
- Database : 3306
- Samba    : 139, 445

## 🚀 Cara Deploy

```bash
docker compose up --build -d
