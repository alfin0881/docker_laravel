# Baca Saya 
## Detail Skema 
Ini adalah skema docker compose yang bisa digunakan untuk menjalankan laravel. 
Beberapa program yang digunakan adalah:
- Apache
- PHP 8.2
- Laravel Versi 12
- MySQL 8.0

## Cara Menggunakan
1. Pastikan anda sudah menginstall docker dan docker-compose di komputer anda.
2. Download atau clone repository ini.
3. Buka terminal dan masuk ke direktori tempat anda menyimpan file ini.
4. Jalankan perintah berikut untuk membangun dan menjalankan container:
   ```bash
   docker-compose up -d
   ```
5. Setelah container berjalan, buka browser anda dan akses `http://localhost:(sesuaikan dengann port)` untuk melihat aplikasi Laravel yang sedang berjalan.
6. Jangan lupa untuk mengatur file `.env` sesuai dengan kebutuhan anda, terutama bagian database.
7. Command Penting !!!
   > Untuk Menjalankan projek :
      ```bash
      docker compose up -d
      ```
      
   > Build Ulang :
     ```bash
     docker compese up -d --build
     ```
     
   > Build image :
    ```bash
    docker compose build
    ```
    
   > Restart satu container :
      ```bash
      docker restart nama_project
      ```
      
   > Mematikan semua container :
      ```bash
      docker compose down
      ```
      
   > Cek Status :
      ```bash
      docker ps
      ```
      
   > Lihat Semua container :
      ```bash
      docker ps -a
      ```
      
   > Lihat log :
      ```bash
      docker logs -f nama_projek
      ```
      
   > Masuk container laravel :
      ```bash
      docker exec -it nama_projek bash
      ```
      
   > Keluar :
      ```bash
      exit
      ```

