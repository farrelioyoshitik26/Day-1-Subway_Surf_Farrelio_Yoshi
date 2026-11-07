# Day-1-Subway_Surf_Farrelio_Yoshi
Nama      : Farrelio Yoshi
Kelompok  : 11 Subway Surf

Deskripsi:
Repository ini berisi dokumentasi workshop "From AI to GitHub:
Building with AI, Managing Change with GitHub".

Tujuan:
Mendokumentasikan materi, catatan, dan hasil praktik workshop.

Rangkuman Materi:
Prompt Engineering
- Prompt adalah instruksi atau masukan kepada AI untuk mendapatkan hasil tertentu.
- Prompt engineering adalah cara merancang instruksi agar jawaban AI tepat, relevan, dan layak digunakan.
- Konteks adalah kunci: prompt yang spesifik menghasilkan hasil lebih baik.
- Struktur prompt yang baik: Role, Task, Context, Format.
- Manfaat: performa AI meningkat, bias berkurang, hasil lebih terkontrol, pengalaman lebih baik.

Git dan GitHub
- Git adalah version control system yang melacak siapa, kapan, dan apa yang diubah pada file (dibuat Linus Torvalds, 2005).
- GitHub adalah platform online untuk menyimpan repository Git dan berkolaborasi.

Git Workflow
- Working directory: salinan proyek yang sedang dikerjakan.
- Staging area: menampung perubahan yang akan masuk ke commit berikutnya.
- Git directory (repository): tempat Git menyimpan metadata dan database proyek.
- Alur: working directory > git add > staging area > git commit > repository.

Command Penting
- git init: memulai repository baru
- git add .: memindahkan file ke staging area
- git commit -m "pesan": menyimpan perubahan ke repository
- git remote add origin <url>: menghubungkan repo lokal dengan GitHub
- git push origin main: mengirim perubahan ke GitHub
- git pull origin main: mengambil dan menggabungkan perubahan dari GitHub
- git clone "url": menyalin repository dari GitHub.

Setup
- Install Git, cek dengan git --version.
- Set identitas dengan git config --global user.name dan user.email.
- Install VS Code, cek dengan code --version.
- Buat SSH key dengan ssh-keygen -t ed25519, tambahkan public key ke GitHub.
- Verifikasi koneksi dengan ssh -T git@github.com.
