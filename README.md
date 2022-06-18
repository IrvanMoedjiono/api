## Jwaban Interview PT. Global Sukses Solusi (RUN System)

Sebelumnya saya mohon maaf mengganggu waktu dari Pak Budi, Pak Tedi, dan Bu Cita. Terima kasih telah memberikan saya waktu dan kesempatan untuk menjawab pertanyaan pada saat interview pada hari Rabu, 15 Juni 2022. Berikut jawaban saya mengenai pertanyaan pada saat interview yang belum terjawab.

### Mengganti ip address pada konfigurasi reverse proxy nginx

- Buka file `sudo nano /etc/hosts` dan tambahkan ip-address dan nama host yang diinginkan seperti gambar di bawah ini.

<p align="center"><img src="pictures/1.png"></p>

- lalu ganti ip-address pada konfigurasi reverse proxy nginx dengan vhost yang sudah dibuat

<p align="center"><img src="pictures/2.png"></p>

### Automated Deployment with Jenkins

- Jenkins berjalan di port 8080 dan saya menggunakan domain `demo-dashboard1.runsystemdev.com` agar jenkins dapat mengakses https dan melakukan webhook ke repo, disini saya menggunakan repo GitHub.

- login dengan username dan password yang telah dibuat. username: irvan & pass: irvan

<p align="center"><img src="pictures/3.png"></p>

- Install plugin tambahan ssh agent dengan masuk ke manage jenkins > plugin manager > pilih menu available > cari ssh agent > lalu install ssh agent

<p align="center"><img src="pictures/4.png"></p>
