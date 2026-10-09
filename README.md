# MixQ V2 — Mixed-Use Development Quantifier

Aplikasi web statik untuk analisis konsep pembangunan bercampur. Buka `index.html` dalam pelayar moden. Tiada pemasangan atau sambungan internet diperlukan.

## Sambungan daripada V1
- Mod Horizontal, Vertical, Hybrid
- Komposisi tanah (6 kategori) berasingan daripada komposisi GFA (4 kategori)
- Pengiraan tanah boleh bina, jejak bangunan, GFA, NFA, nisbah plot
- Anggaran unit kediaman, premis komersial, ruang pejabat, unit industri, populasi dan parkir
- Perbandingan senario A/B/C
- Simpan/buka melalui localStorage, eksport JSON/CSV, cetak/PDF, import JSON V1/V2

## Andaian dan had
- Liputan tapak digunakan pada jumlah tanah kediaman + komersial/pejabat + industri; peruntukan jalan, kawasan lapang dan kemudahan tidak dikira sebagai tanah boleh bina.
- Semua bangunan berkongsi purata tingkat dan liputan; bilangan bangunan ialah metadata perancangan, tidak menggandakan GFA.
- Kadar parkir, keluasan unit dan kecekapan lantai ialah input andaian, bukan piawaian rasmi.
- Unit landed ialah input manual dan tidak dimasukkan ke dalam GFA bangunan; pengguna mesti mengesahkan kebolehlaksanaan komposisi tanah.
- Mod Vertical dan Horizontal memaparkan kalkulator bangunan sebagai simulasi; peraturan pembangunan khusus memerlukan semakan profesional.
- Aplikasi ini tidak mengesahkan pematuhan PBT, tidak mengira trafik atau kapasiti utiliti, dan tidak menyediakan kelulusan merancang.

## GitHub Pages
Muat naik kandungan folder `mixq-v2` ke akar repositori GitHub, kemudian aktifkan Pages daripada branch utama dan folder root.
