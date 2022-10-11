# Latihan membuat VCS
Nama: Alif Nur Fathlii Amarta 

Kelas: TI.22.A3 

NIM: 312210326


1. Pertama tama konfigurasi dengan cara masukan username dan email

![Konfigurasi](https://user-images.githubusercontent.com/115516820/195136379-e2e30161-46e0-48c0-ba1b-07e13864747e.jpg)

2. Pilih direktori yang aktif contoh nya c:/labs_pemograman1, klik kanan lalu pilih "git bash here"

![GitBashHere](https://user-images.githubusercontent.com/115516820/195137155-aa394398-bfea-417e-94df-04e9dbeedb94.jpg)

3. Buat direktori dengan perintah "mkdir" dan masuk ke direktori nya menggunakan perintah "cd" lalu gunakan perintah git init untuk membuat repository local  


![membuat direktori](https://user-images.githubusercontent.com/115516820/195139080-57fa1f2e-edb9-44c7-bdd5-1f2f4c082e44.jpg)

4. Lalu buat file readme menggunakan perintah "echo" (bisa juga menggunakan "git add (namafile)" )

![TambahkanReadme](https://user-images.githubusercontent.com/115516820/195140303-b496b847-9811-497a-adc8-5e33c3bbc333.jpg)

file README.md berhasil dibuat

cek status jika ada file baru dengan perintah "git status" 

![GitStatus](https://user-images.githubusercontent.com/115516820/195144155-f489f5ae-9991-4f45-aea0-386b51040949.jpg)

5. Gunakan perintah "nano" untuk mengubah suatu file 

![nano](https://user-images.githubusercontent.com/115516820/195141216-d1e0f142-1567-4907-a83d-7f2fda962cf9.jpg)

di dalamnya kosong dan isi contohnya "Latihan Menggunakan Git"

![nano2](https://user-images.githubusercontent.com/115516820/195141331-7be58600-9784-429d-8fd4-6ab936cddad5.jpg)

6. Gunakan perintah "git commit -m "komentar commit""  untuk menyimpan perubahan kedalam data base repository local

![GitCommit](https://user-images.githubusercontent.com/115516820/195140635-791505db-0c02-4a44-ad7d-349a0b18760b.jpg)


7. Buatlah repository server menggunakan GitHub (membuat akun terlebih dahulu) dengan cara klik ikon (+) lalu New Repository

![New Repository github](https://user-images.githubusercontent.com/115516820/195141698-be92bc1f-9d48-48bd-8e26-24d739261f1b.jpg)

Namai Repository contohnya "LatihanVCS"

![New Repository github2](https://user-images.githubusercontent.com/115516820/195146291-6376167c-baba-49f7-ac48-a625e9e9e2ab.jpg)


8. Kembali ke GitBash, lalu gunakan perintah git remote add origin (URL) untuk menambakan Remote Repository, Remote Repository adalah repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository agar diakses oleh banyak user.

![gitremote](https://user-images.githubusercontent.com/115516820/195147682-e5e073b4-7262-40d1-a9cd-d716d598ad4c.jpg)

9. Untuk mengirim perubahan repository local ke server gunakan perintah "git push -u origin master" biasanya akan dimintai akses menggunakan username dan password

![gitpush](https://user-images.githubusercontent.com/115516820/195149081-7f6e8bf4-139f-401e-91a1-c52337d987a7.jpg)

masukkan username dan password untuk konfirmasi

![konfirmasi](https://user-images.githubusercontent.com/115516820/195149189-91f80d7e-f039-4244-ad79-51657ecea3f6.jpg)

10. Cek repository nya di GitHub 

![penyelesaian](https://user-images.githubusercontent.com/115516820/195149370-a58311e7-2766-4aae-99b1-e853eece47e0.jpg)

Jika berhasil maka akan ada file yang ditambahkan di githubnya

11. Untuk menyalin Repository server gunakan perintah "git clone (url)" 

![clone](https://user-images.githubusercontent.com/115516820/195149973-07da207e-4159-4201-8327-033466918ad5.jpg)

Jika berhasil maka satu direktori nya secara muncul secara otomatis pada direktori yang tertuju




Itu saja yang bisa saya sampaikan jika ada kesalahan mohon dimaafkan
