## 2.1 Original code of broadcast chat  
Cara menjalankan server: `Cargo run --bin server`  
Cara menjalankan client: `Cargo run --bin client`  


Server
![](./img/sever.png)

client 1
![](./img/client1.png)

client 2
![](./img/client2.png)

client 3
![](./img/client3.png)

Ketika server dijalankan, server akan menunggu koneksi dari client. Saat sebuah client dijalankan, client tersebut akan terhubung ke server. Lalu, jika salah satu client mengirimkan pesan, pesan tersebut akan diterima oleh server dan dibroadcast ke client lain yang terhubung ke server.