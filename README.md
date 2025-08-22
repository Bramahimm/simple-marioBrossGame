# MarioBross Java Game 🎮

Sebuah game sederhana bergaya **Mario** yang dibuat menggunakan **JavaFX**.  
Pemain bisa menggerakkan karakter Mario, melompat, menghindari rintangan (pipa/musuh), dan mendapatkan skor seiring berjalannya waktu.

---

## 📂 Struktur Project
src/
├── img/
│   ├── start.png 
│   ├── backgroundd.jpg 
│   ├── blok.jpg 
│   ├── awan.png 
│   ├── mario.png 
│   ├── pipa.png 
│   └── gameover.jpg 
├── MarioBross.java   # Entry point 
├── Pemain.java 
├── Musuh.java 
├── Block.java 
└── Karakter.java


---

## 🕹️ Fitur Utama
- **Main Menu** dengan tombol *Play* dan *Exit*.
- **Karakter Mario** bisa bergerak ke kiri/kanan (`A` dan `D`) dan melompat (`W`).
- **Musuh (pipa)** muncul secara berkala dan bergerak ke kiri.
- **Awan dan blok tanah** bergerak agar memberi kesan dunia yang hidup.
- **Sistem skor** yang bertambah otomatis.
- **Sistem nyawa** (Mario kebal sesaat setelah terkena musuh).
- **Game Over screen** dengan opsi *Restart* atau *Exit*.

---

## 🚀 Cara Menjalankan
1. **Pastikan Java dan JavaFX sudah terinstal**  
   - Java Development Kit (JDK) 11+  
   - JavaFX SDK sesuai versi JDK  

2. **Clone / salin project ini**  
   ```sh
   git clone https://github.com/Bramahimm/simple-marioBrossGame.git
   cd MarioBross/src

3. **How to run this project**  
   ```sh
   javac *.java
   java MarioBross.java