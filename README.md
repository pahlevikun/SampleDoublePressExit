# SampleDoublePressExit
Assalamualaikum, 
<br/>
Ini adalah contoh aplikasi sederhana, dimana disini kita akan membuat sebuah activity yang nantinya tidak akan langsung keluar setelah kita
menekan tombol back pada smartphone kita. Fungsinya untuk mencegah keluar dari aplikasi saat tombol back tidak sengaja tertekan,
teknik ini biasa disebut Double Press Exit.
</br></br></br>
Oke, sebelum masuk pembahasan, disini saya ingin memberikan sebuah contoh untuk teman-teman saya yang membutuhkan pencerahan dalam memulai
Android Programming, terutama teman-teman sekelas saya di IA12.
</br>Pada dasarnya, materi yang saya gunakan berasal dari : 
</br>https://www.udacity.com/course/android-development-for-beginners--ud837
</br></br></br>
Pada aplikasi ini kita hanya menggunakan sebuah layout, layout tersebut hanya berisi kodingan sederhana. Kodingan tersebutlah yang digunakan
untuk mencegah aplikasi keluar saat tombol back tidak sengaja tertekan. Disini kita menggunakan parameter waktu, waktu yang digunakan
dalam satuan mili detik, sehingga jika tombol back ditekan lagi selama kurun waktu 2 mili detik maka aplikasi akan menutup, jika tombol
back tidak ditekan sebanyak 2 kali dalam kurun waktu 2 mili deitk, maka aplikasi akan tetap berjalan seperti biasa.
</br></br></br>
Hasil Output untuk tampilan Activity-nya akan seperti berikut ini :
</br>![alt tag](http://i.imgur.com/i9z5KJI.png)

