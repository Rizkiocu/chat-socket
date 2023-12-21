#Menjalankan Aplikasi

- Pastikan Node.js telah diinstal pada sistem Anda.
- Pastikan npm (Node Package Manager) telah diinstal. Ini biasanya disertakan saat menginstal Node.js.

Langkah-langkah

1. Sisi Server (Node.js)
    -Buka terminal/command prompt dan navigasi ke direktori server:
        cd server
    -Install dependencies dengan menjalankan perintah:
        npm install
    -Jalankan server dengan perintah:
        npm start
    - Server akan berjalan di http://localhost:3001.
2. Sisi Klien (React)
    -Buka terminal/command prompt dan navigasi ke direktori klien:
        cd client
    -Install dependencies dengan menjalankan perintah:
        npm install
    -Jalankan aplikasi React dengan perintah:
        npm start
    -Aplikasi React akan berjalan di http://localhost:3000.
3. Penggunaan Aplikasi
    -Buka aplikasi di http://localhost:3000 pada browser.
    -Masukkan username dan kata sandi ruang untuk bergabung ke ruang obrolan (masukkan bebas saja tidak ada securitynya).
    -Tekan tombol "Join A Chat" untuk bergabung ke ruang obrolan.
    -Setelah masuk, Anda dapat mengirim dan menerima pesan secara real-time.
4. Struktur Proyek
        server/: Direktori server Node.js.
        client/: Direktori aplikasi React.
