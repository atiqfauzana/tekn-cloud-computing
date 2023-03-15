 ## Mengirimkan Pull Request
 Setiap kali melakukan perubahan, kirim perubahan tersebut. Pengiriman ini disebut dengan Pull Request. Pada posisi ini, kontributor bisa mengirimkan kontribusi dengan cara mengirimkan pull request (PR) ke upstream author. Secara umum, langkah-langkahnya adalah sebagai berikut:

Kontributor akan bekerja di repo lokal (create, update, delete isi)
Commit
Push ke repo kontributor
Kirimkan PR ke repo upstream author.
Upstream author me-review dan kemudian menyetujui (merge) ke master atau menolak PR.
Jika disetujui dan di-merge ke repo master dari upstream author, sinkronkan repo di komputer lokal dan repo GitHub kontributor.
Berikut ini adalah contoh pengiriman perubahan isi README.md dengan menambahkan kontributor.

Membuat Perubahan di Repo Lokal
Sebelum melakukan perubahan, pastikan:

Sudah ada koordinasi secara manual tentang perubahan-perubahan yang akan dilakukan.
Setelah melakukan perubahan-perubahan, pastikan bahwa isi repo lokal tersinkronisasi dengan repo dari upstream author.
Cara melakukan sinkronisasi:
 
  ![Mengirimkan_pull_Request](TC/Mengirimkan_pull_Request/g1.jpg)
 
 Lakukan perubahan-perubahan, setelah itu push ke origin (milik kontributor)
 
 
 ![Mengirimkan_pull_Request](TC/Mengirimkan_pull_Request/g2.jpg)
 
 Setelah itu, buka halaman Web dari repo kontributor https://github.com/bpdp/playground-1. Pada halaman tersebut akan ditampilkan isi yang kita push.
 
  ![Mengirimkan_pull_Request](TC/Mengirimkan_pull_Request/g3.jpg)
 
 Pilih Compare and pull request, kemudian isikan deskripsi PR dan klik pada Create pull request:
 
  ![Mengirimkan_pull_Request](TC/Mengirimkan_pull_Request/g4.jpg)
 
 Pada repo upstream author, muncul angka 1 (artinya jumlahnya 1) pada Pull requests di bagian atas.
Upstream author bisa menyetujui setelah melakukan review: klik pada Pull requests, akan muncul PR dengan message seperti yang ditulis oleh kontributor (Add: contributor). Klik pada PR tersebut, review kemudian klik Merge pull request diikuti dengan Confirm merge. Setelah itu, status akan berubah menjadi Merged.
Sinkronkan semua repo (lokal maupun GitHub kontributor)
 
 ![Mengirimkan_pull_Request](TC/Mengirimkan_pull_Request/g5.jpg)
 
 Konflik
Ada kemungkinan, jika satu orang mengirimkan PR untuk satu atau lebih file dan sementara itu ada lainnya juga yang mengirimkan PR pada satu atau lebih file yang sama, maka akan terjadi konflik karena ada satu atau lebih file yang sama yang di-edit dan akan di-merge. Jika sampai terjadi kasus seperti ini, maka upatream author harus menolak semua PR dan kemudian masing-masing kontributor diharapkan menyelesaikan secara manual (offline) kemudian memutuskan siapa yang akan mengirimkan PR.
 
