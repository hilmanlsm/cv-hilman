# Portfolio Hilman Lesmana — HTML / CSS

## Isi folder
- `index.html` — versi tampilan Canva melalui iframe (memerlukan internet dan izin embed dari Canva). Menggunakan URL embed Canva yang pernah diberikan untuk CV Hilman. Desain Canva tetap disajikan dari server Canva, bukan salinan HTML lokal.
- `editable.html` — halaman HTML/CSS/JS mandiri yang bisa diubah dan dihosting sendiri. **Ini desain alternatif, tidak dijamin identik dengan desain Canva**, sebab sumber halaman tidak mengungkap struktur visual atau asetnya.
- `assets/css/style.css` — seluruh gaya halaman.
- `assets/js/main.js` — menu mobile dan footer tahun.
- `assets/images/` — tempat menyimpan foto asli. Tersedia placeholder SVG, bukan foto pribadi.

## Pasang foto
Salin foto profil ke `assets/images/profile.jpg`, lalu pada `editable.html` ubah `src="assets/images/profile-placeholder.svg"` menjadi `src="assets/images/profile.jpg"`.

## Ubah isi
Buka `editable.html` dengan editor kode, ganti teks bio, keahlian, proyek dan alamat email `email-anda@example.com` dengan data terverifikasi.

## Menjalankan
Buka `index.html` (versi Canva) atau `editable.html` (versi mandiri) di browser. Untuk hosting Nginx, unggah seluruh isi folder ini ke direktori root HTML situs. Kalau ingin halaman mandiri sebagai default, ubah nama `editable.html` menjadi `index.html` setelah memindahkan / menghapus index lama.

## Catatan penting
- Link asal yang diminta: https://fernandaputraperdana.my.canva.site/hilmanlesmana
- Link iframe di `index.html`: https://www.canva.com/design/DAHagHme87k/EmE3_hI5CFxbkOvPA0lpsw/view?embed
- Link iframe didasarkan pada kode embed CV Canva yang tersedia dari konteks sebelumnya; belum bisa dipastikan masih merupakan desain yang sama dengan URL situs asal.
- Untuk replikasi 1:1 secara mandiri, diperlukan screenshot desktop dan mobile serta aset asli dari Canva. Jangan menyatakan file ini sebagai ekstraksi atau duplikasi pixel-perfect dari desain asli.
