# P7 - Modern UI Implementation (Material Design 3) 📱

Repository ini berisi source code untuk **Modul Praktikum #7 Mobile Programming 20251**. Project ini berfokus pada penerapan desain antarmuka modern menggunakan **Jetpack Compose** dan **Material Design 3**.

## 🎯 Topik Praktikum
**"Menerapkan Desain UI Modern"**
* **Dosen Pengampu:** Muhayat, M.IT
* **Topik:** Material Design 3, Theming, Custom Components, & Dark Mode.

---

## ✨ Fitur Utama

Aplikasi ini telah dimodernisasi dengan fitur-fitur berikut:

### 1. Desain UI Modern (Material 3) 🎨
* Menggunakan **Color Scheme Professional (Blue)** menggantikan warna default.
* Implementasi **Typography** dan **Shapes** (Rounded Corners) yang konsisten.
* Komponen UI kustom: `AppButton`, `AppTextField`, dan `AppCard`.

### 2. Struktur Navigasi Lengkap navigasi 🧭
Aplikasi memiliki 4 halaman utama yang saling terhubung:
* **Login Screen:** UI Login modern dengan akses cepat Biometric.
* **Home Screen:** Dashboard dengan card status dan aktivitas.
* **Profile Screen:** Halaman profil pengguna.
* **Settings Screen:** Pengaturan aplikasi.

### 3. Dark Mode & Light Mode bulan/matahari 
* Mendukung tema Gelap dan Terang secara native.
* Terdapat **Toggle Switch** di halaman Settings untuk mengubah tema secara manual (tanpa harus ubah settingan HP).

### 4. Fitur Keamanan (UI Simulation) 🔒
* **Biometric Login:** Tombol akses cepat fingerprint di halaman login.
* **Privacy Settings:** Toggle untuk App Lock dan Biometric Authentication di halaman Settings.

---

## 📸 Screenshots
![Screenshot_2026-01-05-04-19-25-445_id antasari p7_230104040207_pm](https://github.com/user-attachments/assets/aeee8374-52e0-4f93-841e-dd93ba35da14)
![Screenshot_2026-01-05-04-18-52-020_id antasari p7_230104040207_pm](https://github.com/user-attachments/assets/06dfceb7-e34f-446b-ad36-972e8f3f049f)
![Screenshot_2026-01-05-04-19-02-088_id antasari p7_230104040207_pm](https://github.com/user-attachments/assets/ae97c9ec-d403-4bd0-893d-de9c89da7dd8)
![Screenshot_2026-01-05-04-19-06-005_id antasari p7_230104040207_pm](https://github.com/user-attachments/assets/9f15cc51-5ceb-45ac-bbbe-1ac27d2967aa)
![Screenshot_2026-01-05-04-19-09-736_id antasari p7_230104040207_pm](https://github.com/user-attachments/assets/c588b010-677d-47d2-b3dc-f3c1a128cde1)
![Screenshot_2026-01-05-04-19-15-021_id antasari p7_230104040207_pm](https://github.com/user-attachments/assets/d5198156-e2b7-4f06-bb6d-8bee80f7e19d)
![Screenshot_2026-01-05-04-19-17-525_id antasari p7_230104040207_pm](https://github.com/user-attachments/assets/0ed281f6-f7ee-4fd0-add2-bab9896793e5)
![Screenshot_2026-01-05-04-19-19-012_id antasari p7_230104040207_pm](https://github.com/user-attachments/assets/b76394e1-1552-46bf-95dc-7b40585a9911)
![Screenshot_2026-01-05-04-19-20-408_id antasari p7_230104040207_pm](https://github.com/user-attachments/assets/474a9a9a-693e-4567-be0a-17f3de741217)

---

## 🛠️ Tech Stack

* **Language:** Kotlin
* **UI Toolkit:** Jetpack Compose (BOM 2024+)
* **Design System:** Material Design 3
* **Navigation:** AndroidX Navigation Compose
* **Icons:** Material Icons Extended

---

## 📂 Struktur Project

```text
id.antasari.p7_230104040207_pm
├── ui
│   ├── auth          # AuthViewModel, AuthUiState
│   ├── components    # Reusable (AppButton, AppTextField, AppCard)
│   ├── navigation    # AppNavHost (Nav Graph)
│   └── theme         # Color, Type, Shape, Theme (M3)
├── BiometricUtils.kt # Utility helper
├── HomeScreen.kt     # Halaman Dashboard
├── LoginScreen.kt    # Halaman Login
├── ProfileScreen.kt  # Halaman Profil
├── SettingsScreen.kt # Halaman Pengaturan
└── MainActivity.kt   # Entry Point
```

## 👤 Identitas Mahasiswa
* **Nama**: Lira Anggraini
* **NIM**: 230104040207
* **Kelas**: Mobile Programming TI23A
* **Kampus**: Universitas Islam Negeri Antasari Banjarmasin
---
