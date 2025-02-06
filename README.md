Script ini adalah pengunduh video & audio berbasis Termux menggunakan yt-dlp.

Fungsinya:

1. Menampilkan menu dengan daftar situs populer (YouTube, TikTok, Twitter, dll.).


2. Memungkinkan pengguna memilih situs lain dengan melihat daftar extractor dari yt-dlp.


3. Meminta URL video yang ingin diunduh.


4. Memungkinkan pemilihan format:

Video (bestvideo+bestaudio) → MP4.

Audio (bestaudio) → MP3.



5. Menggunakan yt-dlp untuk mengunduh dan menyimpan file ke ~/storage/downloads.



Kelebihan:

✅ Otomatis mendeteksi situs yang didukung.
✅ Mendukung banyak format (video & audio).
✅ Menggunakan warna di terminal dengan colorama.
✅ Menyimpan file langsung ke penyimpanan internal Termux.

Penginstalan Manual

termux-setup-storage
pkg update && pkg upgrade -y        
pkg install libexpat openssl python -y
pip install -U "yt-dlp[default]"     
pkg install ffmpeg -y            
pip install mutagen
pip install Colorama     





