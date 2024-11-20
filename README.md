# Portofolio Dasar untuk Submission Proyek Deploy Aplikasi Profil  
Kelas Menjadi Google Cloud Engineer - Dicoding  

Proyek ini adalah aplikasi web statis yang digunakan untuk menampilkan profil sederhana. Aplikasi ini dideploy menggunakan Google App Engine sebagai bagian dari tugas pada kelas Google Cloud Engineer.  

---

## Struktur Proyek
Berikut adalah struktur dasar dari proyek ini:  
- **app.yaml**: File konfigurasi untuk aplikasi di App Engine.  
- **www/**: Direktori utama yang berisi semua file statis, seperti HTML, CSS, dan gambar.  
  - **css/**: Direktori untuk menyimpan file CSS.  
    - **style.css**: File stylesheet utama yang mengatur tampilan dan nuansa situs.  
  - **img/**: (Opsional) Direktori untuk menyimpan file gambar.  
  - **index.html**: File HTML utama untuk menampilkan konten situs.  

---

## Deskripsi Proyek
Proyek ini bertujuan untuk memberikan dasar pembuatan dan deployment aplikasi web statis menggunakan Google Cloud. Dengan struktur sederhana, aplikasi ini memberikan gambaran bagaimana memanfaatkan App Engine untuk hosting web.

---

## Langkah-Langkah
1. **Persiapan Konfigurasi**  
   - Atur file `app.yaml` dengan pengaturan yang sesuai.  

2. **Membuat App Engine**  
   - Buat App Engine di Google Cloud Console untuk project Anda.  

3. **Clone Repository**  
   - Clone repository ini ke code editor lokal Anda.  

4. **Deploy Aplikasi**  
   - Gunakan perintah berikut di terminal:  
     ```bash
     gcloud app deploy
     ```  

5. **Akses Aplikasi**  
   - Lihat aplikasi Anda di browser menggunakan perintah:  
     ```bash
     gcloud app browse
     ```  

---

## Tampilan Website saya
Berikut adalah tampilan aplikasi:  
![Tampilan Aplikasi](https://github.com/AbdulHafizd001/Proyek-Deploy-Aplikasi-Profile/blob/main/Documentation/Interface%20Web.png)  

