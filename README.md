# latihan1
etelah membuka git bash, masukan nama user dan email untuk merekam 
author yang melakukan perubahan di saat git sudah digunakan seperti ini
‘git config — — global user.name “(nama)”’
‘git config — — global user.email “(email)”’
'/c/Users/ASUS/Pictures/Screenshots/Screenshot (1).png'
Lalu buat git repository di folder baru Anda dengan perintah ‘git init’

Keberhasilan pembuatan repository dapat dilihat di git bashnya atau 
dengan melihat munculnya folder hidden bernama ‘.git ’ di folder 
repository Anda

Selanjutnya, buat file README.txt di folder Anda dan beri perintah
‘git[spasi]status’ di git bash. Akan ada tulisan berwarna merah yang 
menandakan ada perubahan file di folder Anda bernama README.txt. Untuk 
menyelesaikan ini, Anda harus memberi perintah 
‘git[spasi]add[spasi][Nama_file]’ atau ‘git[spasi]add[spasi].’ Pilih 
salah satu.

(Merah) Menambah salah satu file
(Hijau) Untuk menambah semua file

Setelah itu, tulisannya akan berubah berwarna hijau dengan tambahan ‘new 
file:’
Lalu commit perubahan yang telah Anda add dengan perintah 
‘git[spasi]commit’
'/c/Users/ASUS/Pictures/Screenshots/Screenshot (2).png'
Saat Anda memberi perintah ‘git commit’ maka tampilan commit akan 
seperti yang di samping. Selain ‘git[spasi]commit’ Anda bisa memberi 
perintah dengan ‘git[spasi]commit[spasi]-m [spasi]”[keterangan commit]”’
ex:git commit -m ‘Penambahan File README.txt’.
Anda harus menambahkan keterangan perubahan (tanda merah). Kalimat yang 
berawal pagar(#) tidak akan menjadi keterangan, karena itu hanya 
komentar atau untuk membantu Anda apa yang akan dilakukan saat Anda 
mengcommit suatu perubahan.

Setelah Anda mengcommit, akan muncul detail perubahan di commit.

Saat diberi perintah ‘git status’ akan bertuliskan seperti yang 
disamping. Menandakan file Anda sudah aman. Dan untuk melihat riwayat 
perubahan yang Anda lakukan, Anda bisa memberi perintah ‘git[spasi]log’



