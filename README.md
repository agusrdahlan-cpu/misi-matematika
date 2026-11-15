# Misi Matematika

Aplikasi latihan Matematika berbentuk game untuk siswa SMA Alfa Centauri.
Satu file HTML, tanpa server. Progres tersimpan di perangkat masing-masing (localStorage).

## Menjalankan
Buka `index.html` di browser, atau aktifkan GitHub Pages (Settings, Pages, Deploy from a branch, `main`, `/ (root)`).

## Catatan
- Soal dibuat otomatis oleh kode. Kunci jawaban dihitung dari soal, tetapi belum ditinjau guru Matematika.
- Foto stiker tidak disertakan. Isi `PHOTO_STK` di `index.html` jika diperlukan dan sudah disetujui.

## Kirim progres ke guru (Microsoft Forms)
Setelah misi, siswa bisa menyalin ringkasan satu baris dan menempelkannya ke formulir (sukarela).
Formulir hanya perlu satu pertanyaan teks panjang bernama "Ringkasan progres".
Alamat formulir ada di konstanta `FORM_URL` di `index.html`.
Format ringkasan: `kode | kelas | topik | tingkat | benar | salah | XP`.
