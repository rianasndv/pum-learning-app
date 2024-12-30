# Learning Tech - Aplikasi Mobile Pembelajaran

**Learning Tech** adalah aplikasi mobile yang dirancang untuk mendukung proses pembelajaran mandiri bagi mahasiswa Program Studi Manajemen Informatika di Politeknik Negeri Lampung (Polinela). 
Aplikasi ini menyediakan akses ke materi pembelajaran seperti video dan artikel yang dapat diakses kapan saja dan di mana saja. Dengan Learning Tech, 
mahasiswa dapat belajar dengan lebih fleksibel sesuai kebutuhan mereka.

---

**Fitur Utama Aplikasi**
1. **Video Pembelajaran**  
   - Mahasiswa dapat mengakses berbagai video pembelajaran yang telah disediakan oleh creator untuk mendukung materi kuliah.

2. **Artikel Edukatif**  
   - Mahasiswa dapat membaca artikel yang relevan dengan materi pembelajaran, memberikan wawasan tambahan di luar kelas.

3. **Riwayat Akses (History)**  
   - Menampilkan daftar video dan artikel yang telah diakses mahasiswa untuk memudahkan proses belajar dan mengulang materi.

4. **Manajemen Pengguna**  
   - Admin dapat mengelola pengguna aplikasi (creator dan mahasiswa), termasuk menambah, mengubah, atau menghapus pengguna.

---

**Role dan Hak Akses Pengguna**
1. **Admin**  
   - Mengelola data pengguna (students dan creator).
   - Tidak memiliki akses ke materi pembelajaran (video dan artikel).

2. **Creator**  
   - Menambahkan, mengedit, dan menghapus konten pembelajaran berupa video dan artikel.
   - Tidak dapat mengakses manajemen pengguna.

3. **Students**  
   - Mengakses video dan artikel yang telah tersedia.
   - Tidak memiliki akses untuk mengelola konten atau pengguna lain.

---

**Teknologi yang Digunakan**
- **Frontend**:  
  - **Java Native**: untuk membangun antarmuka pengguna yang intuitif dan ramah pengguna.  

- **Backend**:  
  - **Firebase**: digunakan sebagai backend server untuk autentikasi pengguna, manajemen data, dan penyimpanan konten (video dan artikel).

---

**Fitur Keamanan**
- Sistem otentikasi yang aman menggunakan Firebase Authentication.
- Pembatasan akses berdasarkan role (Admin, Creator, Students).
- Data yang disimpan di Firebase Realtime Database atau Firestore dilindungi dengan aturan akses berbasis role.

