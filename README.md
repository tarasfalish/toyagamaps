TOYAGAMAPS

Toyagamaps merupakan proyek website pencatat konsumsi air minum dan pencarian lokasi pengisian air Toyagama di sekitar FMIPA Universitas Gadjah Mada. Proyek ini dikembangkan oleh tim dengan anggota sebagai berikut.

1. Amelia Heidi Setiawan                    (26/587244/PA/24746) — Ketua
2. Tara Safira Falish                       (26/576924/PA/24114)
3. Hana Sheril Eliasha Manullang            (26/581169/PA/24368) 
4. Aisyah Cahaya Larasati                   (26/584612/PA/24530)

## Deskripsi website dan fitur utama

Toyagamaps dibuat untuk membantu mahasiswa mencatat jumlah air putih yang diminum selama menjalani kegiatan sehari-hari, terutama ketika berada di kampus. Website ini juga menyediakan pencarian titik Toyagama agar pengguna lebih mudah menentukan tempat pengisian ulang air. 
Fitur utama yang terdapat dalam kode proyek meliputi:

1. Pencatatan air minum. Pengguna dapat memasukkan jumlah air dalam satuan mililiter, menggunakan tombol tambah cepat, dan menghapus catatan yang keliru.
2. Perhitungan target harian. Target dihitung dari berat badan, jenis kelamin, tingkat aktivitas, serta waktu bangun dan tidur yang dimasukkan pengguna.
3. Indikator kemajuan. Jumlah air yang tercatat ditampilkan melalui persentase dan ilustrasi air yang bertambah sesuai dengan target yang di capai.
4. Riwayat dan statistik. Tersedia tampilan mingguan, bulanan, dan tahunan, beserta rata-rata konsumsi dan jumlah hari ketika target tercapai. Terdapat pula indikator hari beruntun atau streak.
5. Pencarian Toyagama terdekat. Pengguna dapat mengizinkan akses lokasi perangkat, memilih posisi secara manual, atau menandai posisi pada peta. Titik Toyagama kemudian diurutkan berdasarkan perkiraan jaraknya.
6. Tautan rute Google Maps. Titik yang dipilih dapat dibuka di Google Maps untuk melihat rute berjalan kaki. Pengguna juga dapat mencatat air dari titik tersebut.
7. Pengingat minum. Interval pengingat dapat diatur setiap satu, dua, atau tiga jam selama halaman masih terbuka. Notifikasi browser akan memerlukan izin pengguna.
8. Pengaturan tampilan dan penyimpanan. Website menyediakan tema terang, gelap, dan otomatis. Profil, pengaturan, dan riwayat minum disimpan melalui localStorage pada browser.

## Teknologi yang digunakan

• HTML5, untuk menyusun struktur dasar halaman.
• CSS3, untuk mengatur warna, tata letak, animasi, serta penyesuaian tampilan pada ukuran layar yang berbeda.
• JavaScript, untuk menjalankan pencatatan, perhitungan target, statistik, pengaturan, dan interaksi peta.
• localStorage, untuk menyimpan data pada browser pengguna.
• Geolocation API, untuk memperoleh posisi perangkat setelah pengguna memberikan izin.
• Notification API, untuk menampilkan pengingat melalui notifikasi browser yang mendukungnya.
• SVG, untuk menampilkan ikon, ilustrasi air, grafik, dan peta skematis.
• Google Fonts, untuk memuat font Bricolage Grotesque dan Plus Jakarta Sans.
• Tautan Google Maps, untuk membuka rute menuju titik yang dipilih.
Proyek ini menggunakan HTML, CSS, dan JavaScript tanpa framework. Pada berkas yang disertakan belum terdapat backend maupun database server.

## Petunjuk cara menjalankan proyek

Buka tautan https://jojoo-hub.github.io/toyagamaps/

## Cara menggunakan website

Pengguna dapat memulai dengan mengisi fitur “Hitung Targetku” untuk menentukan perkiraan target konsumsi air harian. Pada bagian ini, pengguna perlu memasukkan jenis kelamin, berat badan, tingkat aktivitas, serta rutinitas sehari-hari yang meliputi frekuensi makan, waktu bangun, dan waktu tidur. Selanjutnya, pada bagian Kebiasaan, pengguna dapat mengatur volume air pada tombol cepat sesuai jumlah air yang biasanya diminum dalam satu kali pencatatan, serta menentukan interval pengingat minum.
Setiap selesai minum, pengguna dapat mencatat jumlah air yang dikonsumsi melalui fitur tracker air minum pada halaman utama. Catatan tersebut digunakan untuk memperbarui jumlah konsumsi air dan menampilkan kemajuan pencapaian target harian.
Apabila air di dalam botol sudah habis, pengguna dapat membuka fitur “Toyagama” untuk mencari lokasi pengisian ulang air terdekat. Pengguna dapat menentukan posisinya, kemudian memilih salah satu titik Toyagama yang ditampilkan. Setelah itu, pengguna dapat membuka tautan Google Maps yang tersedia untuk memperoleh petunjuk arah menuju lokasi tersebut.

## Tautan deployment

Tautan website yang digunakan sebagai salah satu referensi proyek adalah DrinkUp. Alamat yang sama juga digunakan sebagai acuan aplikasi dalam prompt pengembangan. Proyek dapat dijalankan secara online melalui petunjuk di atas.

## Penggunaan AI, template, starter code, dan sumber aset

Proyek ini menggunakan bantuan Claude AI dalam proses pembuatan website. Arahan yang diberikan mencakup tampilan biru muda, fitur pencatatan air minum, serta pencarian titik Toyagama di sekitar FMIPA UGM. Percakapan AI yang digunakan dapat dilihat melalui tautan Claude.
DrinkUp dicantumkan sebagai referensi konsep aplikasi pencatat air minum. Referensi tersebut menjadi dasar ide, sedangkan fitur pencarian Toyagama merupakan ide pengembangan yang ditambahkan pada proyek ini. 

## Petunjuk tambahan

Izinkan akses lokasi jika ingin menggunakan posisi perangkat. Apabila akses tersebut tidak tersedia, gunakan pilihan posisi manual atau tandai lokasi pada peta. Koneksi internet diperlukan untuk memuat Google Fonts dan membuka Google Maps. Menu Pengaturan juga menyediakan riwayat contoh untuk mencoba tampilan statistik.

## Keterbatasan proyek

Nama lokasi dan koordinatnya masih berupa perkiraan, sehingga perlu diperiksa langsung sebelum digunakan sebagai petunjuk di lapangan. Peta pada halaman merupakan peta skematis, sedangkan perkiraan jarak dihitung secara garis lurus dan waktu berjalan kaki hanya berupa estimasi. Data pengguna tersimpan pada browser yang digunakan, belum belum dapat sinkronisasi antarperangkat, dan dapat hilang apabila data browser dihapus. Pengingat hanya bekerja selama web terbuka. Target air minum merupakan perkiraan berdasarkan perhitungan umum, sehingga belum memperhitungkan kebutuhan setiap orang secara menyeluruh. Pencatatan masih dilakukan secara manual, sehingga ketepatan riwayat bergantung pada kedisplinan pengguna.
