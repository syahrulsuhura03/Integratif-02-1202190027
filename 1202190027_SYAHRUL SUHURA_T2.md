NAMA : SYAHRUL SUHURA

NIM : 1202190027



TUBES INTEGRATIF PHASE 2



1. Pertama, ubah nama DB_DATABASE di env sesuai dengan nama yang database yang sudah di buat di php my admin
![1](https://user-images.githubusercontent.com/93044506/175784036-fe0e298c-80b2-476f-8d86-933a6e31da81.png)
![2](https://user-images.githubusercontent.com/93044506/175784072-c7c1f17f-1e12-465e-8ac2-407d1251be59.png)



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

![4](https://user-images.githubusercontent.com/93044506/175784055-3a1e06fd-45d2-424a-b201-82d8f784437e.png)


5. jika sudah, tambahkan route di web.php

![5](https://user-images.githubusercontent.com/93044506/175784056-adfe6c05-c367-41ef-b94d-5b16fa78d537.png)

6. cek databasey di php my admin sudah ter-update atau belum
![6](https://user-images.githubusercontent.com/93044506/175784057-31cd3434-8384-4eac-8874-4d82be863830.png)

![7](https://user-images.githubusercontent.com/93044506/175784060-92a5dd63-1942-412b-9805-d76bb0885fa2.png)

7. terakhir cek RSS sudah berhasil atau belum



![8](https://user-images.githubusercontent.com/93044506/175784061-9d46b693-e2fb-4e7b-9479-a79447b3dbfd.png)
