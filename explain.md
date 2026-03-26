# Dokumentasi Proyek

-- Snake Game
Alur: pemain menggerakkan ular menggunakan Arrow Keys atau WASD untuk memakan makanan di arena. Setiap makanan dimakan, skor bertambah +10 dan kecepatan meningkat. Game over terjadi saat ular menabrak dinding atau tubuhnya sendiri.
- Fungsi: entertainment game berbasis HTML Canvas
- Akses: buka file `games/snake.html` langsung di browser
- Fitur: skor, high score (localStorage), kontrol mobile, speed up bertahap
- **Pengaturan**: klik ikon gear untuk mengatur kecepatan ular (5 level) dan jumlah buah (1-10) yang muncul di arena secara bersamaan

-- Page Chess Game
Alur: dua pemain bergiliran menggerakkan bidak catur di papan 8x8. Klik untuk memilih bidak, klik tujuan untuk bergerak. Game over saat checkmate atau stalemate.
- Fungsi: entertainment game catur berbasis HTML Canvas
- Akses: buka file `games/chess/index.html` langsung di browser
- Fitur: semua bidak catur (King, Queen, Rook, Bishop, Knight, Pawn), validasi gerakan sah, deteksi check/checkmate/stalemate, castling (kingside & queenside), en passant, pawn promotion (modal dialog), undo move (Ctrl+Z), move notation list, captured pieces display, turn indicator, last move highlight, king-in-check highlight, coordinate labels
