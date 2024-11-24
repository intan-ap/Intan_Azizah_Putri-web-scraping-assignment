# Assignment Day 6 -  Web Scraping

Tujuan >>> Membuat program web scraping untuk mengekstrak data kursus atau sertifikasi di bidang Data Engineer dari situs web Coursera

Proses >>> Proses web scraping dilakukan menggunakan BeautifulSoup dengan langkah-langkah sebagai berikut:
1. Mengimpor library yang diperlukan
2. Mengirimkan permintaan HTTP ke URL target
3. Memparsing konten HTML dari respons yang diterima
4. Menemukan dan mengekstrak data yang relevan
5. Melakukan iterasi (looping) dan memproses data sesuai kebutuhan
6. Menampilkan data yang telah diekstrak dalam bentuk tabel untuk dianalisis lebih lanjut.

Hasil >>> Hasil dari proses scraping diekstrak dan disimpan dalam file CSV dengan nama "Coursera Data Engineer.csv". Data yang diambil mencakup informasi berikut:
1. Judul (Title)
2. Keterampilan yang Dipelajari (Skills)
3. Rating
4. Jumlah Ulasan (Reviews)
5. Tingkat Kesulitan (Level)
6. Jenis Produk (Product Type)
7. Durasi

Dengan proses ini, informasi dari kursus atau sertifikasi di bidang Data Engineer dapat diolah lebih lanjut untuk kebutuhan analisis data atau referensi pembelajaran.