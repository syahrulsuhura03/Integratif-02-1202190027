NAMA : SYAHRUL SUHURA

NIM : 1202190027



TUBES INTEGRATIF PHASE 2



1. Pertama, ubah nama DB_DATABASE di env sesuai dengan nama yang database yang sudah di buat di php my admin



![1](TUBES INTEGRATIF/1.png)

![2](TUBES INTEGRATIF/2.png)

2. Buat file RssController.php dan NewsController.php di App/Http/Controllers

```markdown
php artisan make:controller RSSController
php artisan make:controller NewsController
```





3. jalankan Migration dan seeding 

```markdown
php artisan migrate:fresh
php artisan migrate --seed
```





4. setelah sukses edit file di NewsController.php

![4](TUBES INTEGRATIF/4.png)



5. jika sudah, tambahkan route di web.php

![5](TUBES INTEGRATIF/5.png)

6. cek databasey di php my admin sudah ter-update atau belum

![6](TUBES INTEGRATIF/6.png)

![7](TUBES INTEGRATIF/7.png)

7. terakhir cek RSS sudah berhasil atau belum

![8](TUBES INTEGRATIF/8.png)