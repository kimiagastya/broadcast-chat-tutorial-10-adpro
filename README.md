# Reflection
## Original Code of Broadcast Chat<br>
![Original Code of Broadcast Chat](img/Ori_code.png)
<br>
Untuk menjalankan program sesuai dengan ketentuan soal (1 server dan 3 client), saya membuka 4 windows terminal dan menjalankan perintah `cargo run --bin server` pada satu terminal dan menjalankan perintah `cargo run --bin client` pada 3 terminal lainnya. Ketika saya mengetik suatu teks pada client, maka server akan menerima pesan tersebut dan di-broadcast ke semua client (termasuk client pengirim pesan tersebut). Proses yang sama juga terjadi ketika client lain mengirimkan teks ke server.