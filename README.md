# Cloudy Note: Aplikasi Catatan Mobile Berbasis Cloud

![Status](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-blue)
![Tech Stack](https://img.shields.io/badge/Stack-Flutter%20%2B%20Supabase-green)

**Cloudy Note** adalah aplikasi manajemen catatan (Note-Taking App) *cross-platform* yang dibangun menggunakan framework **Flutter**. Aplikasi ini memanfaatkan **Supabase** sebagai *Backend-as-a-Service (BaaS)* untuk menyediakan penyimpanan data real-time yang aman dan sistem autentikasi pengguna yang handal.

## 📱 Fitur Utama (Key Features)

### 1. Cloud Synchronization (Supabase)
* **Real-time Database:** Catatan tersimpan secara otomatis di cloud (PostgreSQL via Supabase), memungkinkan akses data yang aman dan persisten.
* **Instant Updates:** Perubahan data langsung ter-sinkronisasi antar sesi.

### 2. Keamanan & Autentikasi Tingkat Lanjut (Advanced Security)
* **Secure Auth Flow:** Implementasi sistem Login/Register menggunakan **Supabase Auth**.
* **Email Verification:** Mekanisme verifikasi email wajib untuk memastikan validitas pengguna dan mencegah akun spam (spam protection).
* **Token Management:** Menangani *user session* secara aman menggunakan JWT (JSON Web Token) dari Supabase.
* **Row Level Security (RLS):** Kebijakan keamanan database di mana data pengguna terisolasi secara kriptografis; pengguna A tidak akan pernah bisa membaca catatan milik pengguna B.

### 3. Modern UI/UX
* **Flutter Architecture:** Antarmuka yang responsif dan mulus (*smooth*) di perangkat Android.
* **CRUD Operations:** Membuat, membaca, mengedit, dan menghapus catatan dengan pengalaman pengguna yang intuitif.

## 🛠️ Teknologi & Arsitektur
* **Framework:** Flutter (Dart)
* **Backend:** Supabase (PostgreSQL)
* **Architecture:** MVVM (via Provider/Bloc) 
* **Auth:** Magic Link / Email & Password

## 🚀 Cara Menjalankan (Installation)
1. Clone repositori ini.
2. Jalankan `flutter pub get` untuk menginstall dependencies.
3. Konfigurasi kredensial Supabase (URL & Anon Key) pada file `.env`.
4. Jalankan `flutter run`.

---
**Muhammad Akbar Dwi Afandi**
*Backend & Mobile Developer | SMK Negeri 1 Lumajang*
