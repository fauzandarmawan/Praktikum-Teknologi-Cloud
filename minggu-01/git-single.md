Instalasi Git 

Bagian ini merupakan seri tulisan tentang Git. Silahkan ke README.md untuk memahami gambaran garis besar materi-materi yang dituliskan.
Git tersedia untuk berbagai sistem operasi. Precompiled binaries bisa diperoleh di halaman dowbload Git untuk 3 sistem operasi utama: Linux, Mac OS X, dan Windows. Git bisa menggunakan antarmuka grafis (GUI) maupun CLI (command line interface). Pada materi ini, kita akan banyak menggunakan antarmuka CLI melalui shell (Linux / Mac OS X) atau command prompt / PowerShell di Windows. Setelah instalasi, periksa keberhasilan instalasi dengan menggunakan:

![1](https://user-images.githubusercontent.com/99378514/155460971-777fb229-b7f3-4750-8d8b-5c6076f2814b.jpg)

Jika muncul versi (tergantung versi yang terinstall), maka kita bisa mulai menggunakan Git.


Windows

Sebelum install Git di Windows, anda harus sudah mempunyai editor teks yang didukung oleh Windws. Editor yang bisa dipilih banyak, tetapi disarankan menggunakan Notepad++ atau Visual Studion Code atau Vim. Keberadaan editor teks ini akan menentukan keberhasilan instalasi (lihat langkah 5).
 
1. Setelah download Git, double click pada file yang di-download. Akan dimunculkan lisensi. Klik Next untuk lanjut.
![2](https://user-images.githubusercontent.com/99378514/155463569-058c5932-5481-4f91-bcff-f83b6599d243.jpg)

2. Pilih komponen. Tidak perlu diubah-ubah, sesuai dengan default saja. Klik pada Next.
![3](https://user-images.githubusercontent.com/99378514/155463784-1d805a2e-ccb4-4414-881e-d6451763ca90.jpg)



3. Pilih next
![4](https://user-images.githubusercontent.com/99378514/155463884-eb013980-f266-470b-956e-63da1e2af012.jpg)

4. Untuk opsi ekstra, pilih serta aktifkan 1 dan 2.
![5](https://user-images.githubusercontent.com/99378514/155464016-00e01061-e14a-486d-b39f-ff681d6432eb.jpg)

5. Pilih Install
![6](https://user-images.githubusercontent.com/99378514/155464156-b9b43b17-c645-41f8-8ede-19d94b554b5a.jpg)

6. Setelah itu proses instalasi akan dilakukan.
![7](https://user-images.githubusercontent.com/99378514/155464241-9636a0c4-9990-4e56-80cd-6e66c225ce59.jpg)

7. Jika selesai akan muncul dialog pemberitahuan. Klik pada Finish.
![8](https://user-images.githubusercontent.com/99378514/155464327-2dc7e8c7-3480-4303-8050-a2dd9fea773d.jpg)


Konfigurasi Git

Bagian ini merupakan seri tulisan tentang Git. Silahkan ke README.md untuk memahami gambaran garis besar materi-materi yang dituliskan.
Secara minimal, user harus memberitahu Git tentang username serta email yang digunakan setiap kali terjadi perubahan pada repo Git. Username serta email ini yang akan dimasukkan oleh Git ke catatan perubahan di repo. Di sistem operasi Linux atau sejanis (UNIX), konfigurasi ini nantinya akan disimpan di $HOME/.gitconfig. Untuk sistem operasi Windows, konfigurasi ini akan disimpan di C:\Document and Settings\NamaUser dengan nama file .gitconfig. Secara minimal, ada 2 hal yang perlu dikonfigurasi yaitu username dan email. Gunakan perintah berikut:

![9](https://user-images.githubusercontent.com/99378514/155464565-68c7e87d-18f9-4952-b74e-3956b41f3102.jpg)

Isian di atas harus disesuaikan dengan nama serta email yang digunakan untuk mendaftar di GitHub. Untuk melihat konfigurasi yang sudah ada:

![10](https://user-images.githubusercontent.com/99378514/155464619-32dbe558-c092-4684-8b47-c06fe45cdd2b.jpg)

Langkah ini cukup dilakukan sekali saja, kecuali jika ingin melakukan perubahan nama dan email.
