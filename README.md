# Microservices

## Kenapa Perlu Belajar Microservices ?
- Kekinian
- Ekosistem pendukung
- Banyak digunakan di tech company
- Sudah jadi pengetahuan wajib untuk senior engineer

## Arsitektur Monolith 
- Single deployment unit
- Dimana semua fitur dibuat dalam sebuah aplikasi besar

## Kelebihan Arsitektur Monolith
- Mudah di develop
- Mudah di deploy
- Mudah di test
- Mudah di scale

## Masalah di Arsitektur Monolith
- Mengintimidasi developer yang baru bergabung
- Scaling development dengan banyak developer agak menyulitkan
- Butuh kontrak panjang dengan teknologi yang digunakan (bahasa pemrograman, database, dan lain - lain)
- Scaling pada bagian tertentu tidak bisa dilakukan
- Running app monolith sangat berat

## Apa itu Arsitektur Microservices ?
- Aplikasi - aplikasi kecil yang saling bekerja sama
- Fokus mengerjakan satu pekerjaan dengan baik
- Independent, dapat di deploy dan diubah tanpa tergantung dengan aplikasi lain
- Setiap komponen pada sistem dibuat dalam service
- Komunikasi antar service biasanya melalui network call

## Kelebihan Arsitektur Microservices
- Mudah dimengerti, karena relative kecil ukuran service nya
- Lebih mudah di develop, di maintain, di test dan di deploy
- Lebih mudah bergonta - ganti teknologi
- Mudah di scale sesuai kebutuhan
- Bisa dikerjakan dalam tim - tim kecil

## Masalah di Arsitektur Microservices
- Distributed system
- Komunikasi antar service yang rawan error
- Testing interaksi antar service lebih sulit

## Seberapa Kecil Aplikasi Microservices ?
- Single responsibility
- Sekecil mungkin sehingga bisa dimengerti oleh satu orang
- Bisa dikerjakan sejumlah x developer

## Perbedaan Monolith dengan Microservices
### Monolith
- Simplicity
- Consistency
- Easy to refactor
### Microservices
- Partial deployment
- Availability
- Multiple platform
- Easy to scale

## Database per Service
- Decentralized database

## Kenapa Harus Database per Service ?
- Memastikan bahwa antar service tidak ketergantungan
- Tiap service bisa menggunakan aplikasi database sesuai dengan kebutuhan
- Service tidak perlu tahu kompleksitas internal database service lain

## Kapan Harus Shared Database ?
- Ketika melakukan transisi dari aplikasi Monolith ke Microservices
- Ketika bingung memecah data antar service
- Ketika dikejar waktu, sehingga tidak ada waktu untuk bikin API