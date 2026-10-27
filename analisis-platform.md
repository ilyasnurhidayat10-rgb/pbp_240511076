# Analisis Komparatif Platform

## Tabel Analisis Platform

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| Bahasa utama | HTML, CSS, JavaScript/TypeScript | Bergantung teknologi: C#, Java, C++, Swift, JavaScript, dll. | Kotlin/Java (Android), Swift (iOS), atau Dart/JavaScript untuk lintas platform |
| Arsitektur | Client–server; browser berkomunikasi dengan server melalui HTTP/HTTPS dan dapat memakai API. | Aplikasi berjalan di sistem operasi komputer; dapat memakai arsitektur berlapis dan mengakses layanan lokal/jaringan. | Aplikasi berjalan pada perangkat mobile; dapat memakai layanan perangkat dan berkomunikasi dengan server/API. |
| Cara distribusi | Di-host pada server; pengguna mengakses melalui URL di browser. | Installer atau paket aplikasi melalui situs pengembang, toko aplikasi, atau pengelola paket. | Google Play, Apple App Store, distribusi enterprise, atau pemasangan paket aplikasi yang didukung. |
| Keunggulan | Mudah diakses lintas perangkat tanpa instalasi tradisional; pembaruan terpusat; jangkauan luas. | Dapat terintegrasi dengan sistem operasi dan periferal; dapat mendukung kerja offline; pengalaman aplikasi khusus desktop. | Memanfaatkan kamera, GPS, sensor, notifikasi, dan fitur perangkat; mudah digunakan saat bepergian. |
| Keterbatasan | Bergantung pada browser dan jaringan untuk banyak fitur; akses perangkat dibatasi oleh izin dan kemampuan browser. | Perlu memperhatikan perbedaan OS/arsitektur; distribusi dan pembaruan dapat lebih rumit; pemasangan diperlukan. | Sumber daya layar/baterai terbatas; fragmentasi perangkat/OS; proses publikasi dan izin toko aplikasi. |
| Contoh aplikasi | Google Docs versi web, Gmail web, Wikipedia | Visual Studio Code, LibreOffice, VLC Media Player | WhatsApp mobile, Google Maps, aplikasi mobile banking |

## Refleksi

Platform yang paling menarik untuk saya pelajari adalah platform mobile. Menurut saya, aplikasi mobile dekat dengan aktivitas sehari-hari dan dapat memanfaatkan fitur perangkat seperti kamera, GPS, sensor, serta notifikasi. Saya juga ingin memahami bagaimana aplikasi dirancang agar tetap nyaman digunakan pada ukuran layar dan spesifikasi perangkat yang berbeda. Walaupun begitu, platform web dan desktop juga penting karena masing-masing memiliki kebutuhan dan kelebihan tersendiri.

Tantangan terbesar saat menyiapkan environment pengembangan adalah memastikan semua tools terpasang dengan benar dan dapat dikenali melalui terminal. Contohnya, perintah Git, Node.js, NPM, atau Java bisa gagal dijalankan apabila instalasi belum selesai atau PATH belum dikonfigurasi dengan tepat. Selain itu, Android Studio membutuhkan ruang penyimpanan yang cukup besar dan mungkin memerlukan waktu untuk mengunduh komponen tambahan.

Untuk mengatasi tantangan tersebut, saya akan mengikuti dokumentasi resmi setiap tools, memeriksa versi melalui terminal setelah instalasi, dan membaca pesan error dengan teliti. Jika masalah berkaitan dengan PATH, saya akan memeriksa konfigurasi environment variable lalu membuka ulang terminal. Saya juga akan menginstal Android Studio ketika perangkat dan koneksi internet memungkinkan. Terakhir, saya akan menyimpan proses kerja, file analisis, dan perubahan proyek ke GitHub agar tugas terdokumentasi dengan rapi.

## Referensi
- MDN Web Docs — Introduction to the web. https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website
- Microsoft Learn — Desktop Guide (Windows apps). https://learn.microsoft.com/en-us/windows/apps/
- Android Developers — Build your first app. https://developer.android.com/get-started
- Apple Developer — App Store. https://developer.apple.com/app-store/

## Checklist setup dan dokumentasi

- [ ] Install Git, Node.js + NPM, Visual Studio Code, dan Java JDK.
- [ ] Install Android Studio atau tuliskan kendala jika belum dapat dipasang.
- [ ] Jalankan `git --version`, `node --version`, `npm --version`, dan `java -version`; simpan screenshot asli.
- [ ] Buat repository GitHub bernama `pbp-[NIM]` dan clone ke komputer.
- [ ] Simpan file ini sebagai `analisis-platform.md` di dalam repository.
- [ ] Commit dan push file ke GitHub.
- [ ] Buat laporan PDF final dengan identitas, screenshot asli, tabel, refleksi, dan link repository.
