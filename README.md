# flutter_quiz_benar_salah
4522210143_Cinta Delia Yunus
## Tujuan Praktikum
Praktikum ini dirancang untuk memahami konsep pembuatan kuis interaktif dengan format true/false menggunakan Flutter. Fokus pembelajaran mencakup penerapan StatefulWidget, pengelolaan state aplikasi, serta pemanfaatan package eksternal seperti rflutter_alert untuk memberikan umpan balik visual. Mahasiswa juga dilatih dalam menggabungkan logika pemrograman dengan tampilan antarmuka secara responsif.
## Deskripsi Aplikasi
Aplikasi ini merupakan kuis edukatif interaktif yang mengangkat tema tokoh budaya Betawi, yaitu Benyamin Sueb. Pengguna diberikan pertanyaan dengan pilihan jawaban Benar atau Salah, dan aplikasi langsung memberikan umpan balik atas pilihan yang dipilih. Sistem mencatat jumlah jawaban benar dan salah secara otomatis, lalu menampilkan ringkasan skor dalam bentuk pop-up saat seluruh pertanyaan telah dijawab.
## Screenshot Emulator:
## Penjelasan Program
Aplikasi dibangun menggunakan framework Flutter dengan bahasa Dart, dan terdiri dari tiga file utama:
- main.dart – Menyusun antarmuka utama dan mengatur alur logika kuis.
- question.dart – Mendefinisikan model pertanyaan, mencakup teks pertanyaan dan jawaban benar.
- quiz_brain.dart – Mengelola kumpulan pertanyaan serta proses navigasi kuis (next question, reset, dll).
## Daftar Pertanyaan
Terdiri dari 13 pertanyaan seputar:
- Tokoh Benyamin Sueb.
- Budaya Betawi.
- Trivia tentang film, musik, dan karakter-karakter fiktif.
## Cara Menjalankan Aplikasi
flutter pub get flutter run
