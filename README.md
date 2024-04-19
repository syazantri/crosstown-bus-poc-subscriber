# Reflection Tutorial 8 - Subscriber
Syazantri Salsabila - 2206029443 - AdvPro B

a. what is amqp? 
> AMQP itu singkatan dari Advanced Message Queuing Protocol, biasa digunakan untuk passing message antar aplikasi atau komponen secara asinkronus (menjadi message broker). Di dalam kode ini, amqp melakukan initialize listener , lalu memanggilnya (```listener.listen```) untuk me-listen message dan terus looping me-listen messagenya. <br>

<br>

b. what it means? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?  
> ```guest:guest@localhost:5672``` adalah sebuah string berformat URL yang digunakan sebagai spesifikasi detail connection untuk AMPQ yang digunakan. Lalu guest yang pertama maksudnya adalah username, sedangkan guest yang kedua maksudnya adalah password. Pada bagian```localhost:5672```, maksudnya adalah localhost sebagai hostname/ip address tempat AMPQ dijalankan, sedangkan 5672 merupakan port tempat AMPQ berkomunikasi (me-listen).