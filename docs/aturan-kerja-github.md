# ATURAN KERJA GITHUB KELOMPOK 4

## 1. Tujuan

Dokumen ini dibuat sebagai pedoman kerja seluruh anggota Kelompok 4 dalam mengembangkan proyek **Sistem Informasi Mikrokredensial** menggunakan GitHub.

Dengan adanya aturan ini, setiap anggota diharapkan dapat bekerja secara teratur, saling membantu, dan menghindari kesalahan saat mengelola repository kelompok.

## 2. Aturan Umum

1. Setiap anggota wajib menggunakan akun GitHub masing-masing.
2. Setiap anggota harus memahami struktur folder repository kelompok.
3. Sebelum mulai mengerjakan tugas, anggota harus memastikan perubahan terbaru sudah diperoleh.
4. Setiap perubahan pekerjaan harus disimpan menggunakan Git Commit.
5. Hasil pekerjaan harus dikirim ke repository melalui Git Push.
6. Setiap anggota wajib berkomunikasi apabila mengalami kendala.
7. Dilarang mengubah atau menghapus pekerjaan anggota lain tanpa koordinasi terlebih dahulu.

## 3. Alur Pengerjaan Tugas

Pengerjaan tugas dilakukan dengan urutan berikut:

### A. Mengambil Perubahan Terbaru (Pull)

Sebelum mulai bekerja, anggota harus mengambil perubahan terbaru dari repository utama agar pekerjaan yang dilakukan menggunakan versi terbaru.

### B. Membuat Branch

Setiap anggota membuat branch baru untuk mengerjakan tugas tertentu.

Branch digunakan agar pekerjaan tidak langsung mengubah branch utama (`main`).

Contoh nama branch:

- `docs/pendataan-anggota`
- `feat/backend-login`
- `feat/frontend-dashboard`
- `fix/backend-validasi`

### C. Mengerjakan Tugas

1. Kerjakan tugas sesuai bagian dan tanggung jawab masing-masing.
2. Simpan hasil pekerjaan pada folder yang sesuai.
3. Pastikan perubahan tidak mengganggu bagian lain.
4. Apabila mengalami kendala, segera komunikasikan kepada anggota kelompok.

### D. Melakukan Commit

Setiap perubahan harus disimpan menggunakan Git Commit.

Sesuai instruksi dosen, format penulisan commit adalah:

`<tipe>(<bagian>): <ringkasan perubahan>`

Jenis commit yang digunakan:

- `feat`: Menambahkan fitur atau pekerjaan baru.
- `fix`: Memperbaiki kesalahan atau bug.
- `docs`: Menambahkan atau memperbarui dokumentasi.
- `test`: Menambahkan atau memperbarui pengujian.

Contoh penulisan commit:

```text
feat(backend): tambah fitur login
fix(backend): perbaiki validasi login
docs(kelompok-01): perbarui laporan proyek
test(frontend-web): tambah bukti pengujian
```

Ketentuan commit:

1. Gunakan kalimat singkat dan jelas.
2. Satu commit sebaiknya berisi satu perubahan yang terfokus.
3. Hindari menggunakan pesan commit seperti `update`, `coba`, atau `perbaikan` tanpa penjelasan.

### E. Melakukan Push

Setelah melakukan commit, anggota harus mengirimkan perubahan ke GitHub menggunakan Git Push.

Perubahan akan tersimpan pada branch masing-masing dan belum langsung masuk ke branch utama.

### F. Membuat Pull Request (PR)

Setelah pekerjaan selesai dan berhasil di-push, anggota wajib membuat Pull Request (PR).

Pull Request digunakan untuk mengajukan perubahan dari branch masing-masing agar dapat diperiksa sebelum digabungkan ke branch utama.

Setiap Pull Request harus memuat:

1. Judul yang menjelaskan pekerjaan.
2. Ringkasan perubahan yang dilakukan.
3. Bukti hasil pekerjaan jika diperlukan.
4. Informasi mengenai bagian yang dikerjakan.

### G. Review dan Merge

1. Setiap Pull Request harus diperiksa oleh anggota lain sebelum digabungkan.
2. Reviewer memberikan masukan apabila ditemukan kesalahan.
3. Pembuat Pull Request wajib memperbaiki perubahan apabila terdapat masukan.
4. Setelah proses pemeriksaan selesai dan perubahan dinyatakan sesuai, Pull Request dapat digabungkan (Merge) ke branch utama.
5. Jangan melakukan Merge sebelum proses review selesai.

## 4. Pembagian Tanggung Jawab

Setiap anggota bertanggung jawab terhadap bagian pekerjaan yang telah disepakati bersama.

Pembagian tugas dapat disesuaikan dengan kebutuhan pengembangan proyek.

Anggota kelompok juga wajib saling membantu apabila ada anggota yang mengalami kesulitan.

## 5. Penggunaan GitHub Issue

GitHub Issue digunakan untuk mencatat kendala atau masalah yang ditemukan selama pengerjaan proyek.

Apabila mengalami kendala, anggota harus mencatat:

1. Judul masalah.
2. Penjelasan masalah.
3. Langkah-langkah untuk menemukan masalah.
4. Bukti berupa screenshot atau informasi pendukung.
5. Upaya yang sudah dilakukan untuk mengatasi masalah.

Jika masalah sudah berhasil diperbaiki, cantumkan tautan commit atau Pull Request yang menyelesaikannya sebelum Issue ditutup.

Apabila tidak ada kendala, anggota tidak wajib membuat Issue.

## 6. Aturan Keamanan Repository

Seluruh anggota wajib menjaga keamanan repository dengan mengikuti ketentuan berikut:

1. Dilarang mengunggah password atau kata sandi.
2. Dilarang mengunggah token akses atau API Key.
3. Dilarang mengunggah file `.env` yang berisi informasi rahasia.
4. Dilarang mengunggah folder dependency yang tidak diperlukan.
5. Pastikan file yang diunggah tidak mengandung informasi pribadi atau data rahasia.
6. Periksa kembali perubahan sebelum melakukan commit dan push.

## 7. Pengumpulan Tugas

Setiap pengerjaan tugas harus memiliki bukti dan tautan yang dapat diperiksa.

Tautan yang dikumpulkan meliputi:

1. URL repository GitHub.
2. URL folder tugas yang dikerjakan.
3. URL Pull Request.
4. URL GitHub Issue apabila terdapat kendala.

Untuk tugas individu, setiap anggota tetap mengerjakan dan mengumpulkan tugas melalui repository masing-masing sesuai instruksi dosen.

Untuk tugas kelompok, seluruh anggota berkontribusi melalui repository kelompok dengan menggunakan alur branch, commit, push, Pull Request, dan review.

## 8. Komunikasi dan Jadwal Kerja

1. Setiap anggota wajib memberikan informasi mengenai perkembangan pekerjaannya.
2. Apabila belum dapat menyelesaikan tugas sesuai waktu yang disepakati, anggota harus memberi kabar kepada kelompok.
3. Diskusikan masalah teknis bersama sebelum mengambil keputusan yang dapat memengaruhi pekerjaan anggota lain.
4. Jadwal kerja kelompok dilaksanakan setiap Sabtu malam Minggu.
5. Waktu pelaksanaan menyesuaikan kesepakatan seluruh anggota kelompok.

## 9. Penutup

Aturan kerja ini dibuat untuk menjadi pedoman bersama seluruh anggota Kelompok 4 dalam mengembangkan Sistem Informasi Mikrokredensial.

Setiap anggota diharapkan dapat mengikuti aturan yang telah disepakati agar proses pengerjaan tugas berjalan dengan tertib, terstruktur, dan dapat dipertanggungjawabkan.
