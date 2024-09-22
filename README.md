# dibimbing-belajar-github

## Penjelasan Assignment

1. Buat Repository di GitHub.
***Login ke GitHub dan buat repository baru dengan nama dibimbing-belajar-github.***
- Masuk ke akun GitHub.
- Klik New Repository.
- Isi nama repository: dibimbing-belajar-github.
- Pilih visibilitas (public atau private).
- Klik Create Repository.

2. Clone Repository ke Lokal
- Setelah repository dibuat, copy URL repository.
- Buka terminal atau command prompt.
- Jalankan perintah berikut untuk clone repository:
*git clone <URL_repository>*
- Note: Ganti <URL_repository> dengan URL repository yang sudah disalin.

3. Buat File Python untuk Membaca CSV
- Masuk ke direktori repository di komputer: *cd dibimbing-belajar-github*
- Buat file Python bernama read_csv.py yang berisi function untuk membaca file CSV
- Simpan file read_csv.py

4. Buat Branch Baru
- Buat branch baru dengan format feature/<nama_branch>. Contoh, jika nama branch adalah read-csv:
*git checkout -b feature/read-csv*

5. Commit dan Push File
- Tambahkan file read_csv.py ke staging area: *git add read_csv.py*
- Commit perubahan: *git commit -m "Add function to read CSV file"*
- Push branch ke GitHub: *git push origin feature/read-csv*

6. Buat Pull Request di GitHub
- Buka repository di GitHub.
- Akan ada notifikasi tentang branch baru. Klik Compare & Pull Request.
- Isi deskripsi Pull Request dan klik Create Pull Request.

7. Pull Remote Master/Main Branch ke Lokal
- Pindah ke Branch master/main di Lokal: Kita harus berada di branch master/main di lokal sebelum menarik perubahan dari remote. Jalankan perintah berikut untuk memastikan kita berada di branch master/main:
*git checkout main*  #Jika default branch adalah 'main'
- Menarik Perubahan dari Remote (GitHub): Setelah berada di branch master/main, jalankan perintah berikut untuk menarik (pull) perubahan dari remote repository: *git pull origin main*  #Jika branch default adalah 'main'
- Verifikasi Pull: Setelah menjalankan perintah git pull, kita bisa memverifikasi apakah pull sudah berhasil dengan melihat log commit atau mengecek apakah file yang di-merge dari PR sudah ada di lokal.
- Jalankan git log untuk melihat commit terbaru: *git log --oneline*
- Pastikan commit hasil merge dari PR sudah ada di log ini.





