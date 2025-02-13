# Laporan Praktikum 1

NIM : 2241720227 \
NAMA : MUHAMMAD IRSYAD DANY \
KELAS : TI - 3D

## 1.1 Praktikum 1

### 1.1.1 Praktikum Instalasi Git, VSCode, dan Node.JS

### Jawaban Pertanyaan Praktikum 1

1. - **Git** – Sistem kontrol versi yang digunakan untuk melacak perubahan dalam kode, memungkinkan kolaborasi tim, dan menyimpan proyek secara terorganisir di repositori seperti GitHub atau GitLab.
   - **VS Code** – Editor kode ringan dan powerful buatan Microsoft yang mendukung berbagai bahasa pemrograman, dilengkapi dengan fitur seperti debugging, terminal bawaan, serta ekstensi untuk meningkatkan produktivitas.
   - **Node.js** – Runtime environment untuk menjalankan JavaScript di luar browser, sering digunakan untuk membangun aplikasi backend, API, serta pengembangan server-side dengan performa tinggi.

## 1.2 Praktikum 2

### 1.2.1 Praktikum 2: Membuat Proyek Pertama React Menggunakan Next.js

### Jawaban Pertanyaan Praktikum 2

1. Berikut adalah penjelasan singkat mengenai istilah-istilah yang muncul saat membuat proyek baru dengan Next.js:

   - **TypeScript** – Superset dari JavaScript yang menambahkan tipe statis, membantu dalam pengembangan yang lebih terstruktur dan minim bug.
   - **ESLint** – Alat linter untuk JavaScript dan TypeScript yang membantu mendeteksi serta memperbaiki kesalahan sintaksis dan gaya penulisan kode sesuai standar yang ditentukan.
   - **Tailwind CSS** – Framework CSS berbasis utility-first yang memungkinkan styling cepat dengan kelas-kelas siap pakai tanpa perlu menulis banyak CSS kustom.
   - **App Router** – Sistem routing baru di Next.js (sejak v13) yang menggunakan pendekatan berbasis file dalam folder _app/_, mendukung fitur server components dan rendering yang lebih efisien.
   - **Import Alias** – Fitur yang memungkinkan penggunaan jalur import yang lebih ringkas dan mudah dibaca, biasanya dikonfigurasi di tsconfig.json atau jsconfig.json.
   - **Turbopack** – Bundler baru yang dikembangkan oleh Vercel sebagai penerus Webpack, dirancang untuk performa yang lebih cepat terutama dalam pengembangan Next.js.

2. Dalam proyek **Next.js**, beberapa folder dan file memiliki kegunaannya masing-masing. Folder **`.next`** berisi hasil build Next.js, **`node_modules`** menyimpan dependensi proyek, **`public`** digunakan untuk menyimpan aset statis seperti gambar dan ikon, sedangkan **`src/app`** adalah folder utama yang berisi halaman dan komponen aplikasi. Di dalamnya terdapat **`favicon.ico`** sebagai ikon tab browser, **`globals.css`** untuk styling global, **`layout.tsx`** sebagai komponen layout utama, dan **`page.tsx`** sebagai halaman utama (`/`). Beberapa file konfigurasi juga penting, seperti **`.gitignore`** untuk menentukan file yang diabaikan oleh Git, **`eslint.config.mjs`** untuk konfigurasi ESLint, **`next-env.d.ts`** sebagai dukungan TypeScript, serta **`next.config.js`** untuk pengaturan Next.js. **`package-lock.json`** dan **`package.json`** digunakan untuk mengelola dependensi, sementara **`postcss.config.js`** dan **`tailwind.config.ts`** berperan dalam konfigurasi Tailwind CSS. Terakhir, **`README.md`** berisi dokumentasi proyek dan **`tsconfig.json`** digunakan untuk konfigurasi TypeScript.

## 1.3 Praktikum 3

### 1.3.1 Praktikum 3: Menambahkan Komponen React (Button)

### Jawaban Pertanyaan Praktikum 3

1. Screenshoot

## 1.4 Praktikum 4

### 1.4.1 Praktikum 4: Menulis Markup dengan JSX

### Jawaban Pertanyaan Praktikum 4

1. Sintaks **`user.imageUrl`** digunakan untuk mengakses URL gambar profil pengguna dalam suatu objek **`user`**. Kegunaannya antara lain untuk menampilkan foto profil pengguna dalam elemen **`<img>`**, menyimpan serta mengambil data gambar pengguna dari database atau API, dan mempersonalisasi tampilan antarmuka, seperti menampilkan avatar di navbar atau bagian komentar. Penggunaan ini memastikan pengalaman pengguna yang lebih interaktif dan dinamis, terutama dalam aplikasi berbasis autentikasi. Namun, penting untuk memastikan bahwa objek **`user`** memiliki properti **`imageUrl`** agar tidak terjadi error saat digunakan.
