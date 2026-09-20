🤝 Contributing Guide

Terima kasih sudah tertarik untuk berkontribusi di Komunitas Pemula IT!

Project ini dibuat untuk belajar dan berkembang bersama. Jadi, jangan takut untuk berkontribusi walaupun kamu masih pemula.

---

🌱 Siapa yang Bisa Berkontribusi?

Siapa saja.

Kamu tidak harus:

- Senior developer
- Punya pengalaman kerja
- Menguasai banyak bahasa pemrograman

Yang penting mau belajar, berdiskusi, dan mengikuti aturan project.

---

🔎 Jenis Kontribusi

Kamu bisa berkontribusi melalui:

- 🐛 Bug Fix
- ✨ Feature
- 🎨 UI/UX
- 📚 Documentation
- 🧪 Testing
- 🔐 Security
- 💡 Ide dan Improvement
- 🔍 Code Review

---

🚀 Memulai Kontribusi

1. Fork Repository

Klik tombol Fork pada halaman repository.

2. Clone Repository

git clone https://github.com/KomunitasPemulaIT-ProPem/Project.git
cd Project

3. Buat Branch

Jangan langsung bekerja di branch "main".

Gunakan nama branch yang jelas:

git checkout -b feature/nama-fitur

Contoh:

git checkout -b feature/login-page

Untuk bug:

git checkout -b fix/navbar-mobile

Untuk dokumentasi:

git checkout -b docs/update-readme

---

💻 Kerjakan Perubahan

Kerjakan perubahan sesuai Issue atau diskusi yang sudah dibuat.

Usahakan perubahan tetap fokus pada satu tujuan.

Hindari menggabungkan banyak perubahan yang tidak berhubungan dalam satu Pull Request.

---

📝 Commit

Gunakan commit message yang jelas.

Contoh:

feat: add login page
fix: fix mobile navbar
docs: update installation guide
style: improve button layout
refactor: simplify authentication logic
test: add login validation test

Hindari commit seperti:

update
fix
coba
test
asdf

---

📤 Push

Setelah selesai:

git add .
git commit -m "feat: add login page"
git push origin feature/login-page

---

🔀 Pull Request

Setelah push, buat Pull Request menuju branch:

main

Jelaskan:

- Apa yang kamu ubah?
- Kenapa perubahan tersebut diperlukan?
- Issue mana yang berkaitan?
- Apakah sudah dilakukan testing?

Jika berkaitan dengan Issue, gunakan:

Closes #123

---

👀 Code Review

Pull Request akan direview oleh maintainer atau contributor lain.

Jika ada perubahan yang diminta, jangan khawatir.

Perbaiki branch yang sama kemudian push kembali:

git add .
git commit -m "fix: address review feedback"
git push

Pull Request akan otomatis diperbarui.

---

✅ Sebelum Membuat Pull Request

Pastikan:

- [ ] Kode dapat dijalankan
- [ ] Tidak ada error yang diketahui
- [ ] Sudah melakukan testing
- [ ] Tidak memasukkan password/API key
- [ ] Tidak memasukkan file pribadi
- [ ] Commit message jelas
- [ ] Pull Request menjelaskan perubahan
- [ ] Tidak mengubah bagian yang tidak berkaitan

---

🔐 Security

Jangan pernah memasukkan:

API Key
Password
Token
Private Key
Database Credential
.env
Data pribadi

Jika menemukan masalah keamanan yang serius, jangan dipublikasikan langsung sebagai Issue.

Hubungi maintainer project secara langsung.

---

❤️ Untuk Contributor Pemula

Kalau belum tahu harus mulai dari mana, cari Issue dengan label:

good first issue
beginner
help wanted
documentation

Kalau masih bingung, silakan bertanya.

Tidak ada pertanyaan yang terlalu sederhana untuk dipelajari bersama.
