# Tugas-Authentikasi-Web-Programming
Guide Instalasi:

1. Install project laravel dan buat database
2. Buat model, controller, dan migration untuk socialAccount
3. Lalu buat relation user dengan socialAccount di model
4. Lalu buat composer require laravel/ui:^3.4 --dev
5. Setelah itu lakukan php artisan ui bootstrap --auth
6. Kemudian npm install dan npm run dev secara bertahap (jika belum ada node js bisa dinstall dulu)
7. Setelah melakukan hal tersebut lakukan composer require laravel/socialite untuk mengintall library socialite
8. Lalu routing di web.php
9. Pada login.blade.php dan register.blade.php tambahkan button google dan facebook
10. Untuk reset password dapat dilakukan dengan membuat akun di mailtrap.io
11. Pada mailtrap.io ke menu Sandbox -> Set Up Inbox -> Integraions -> Laravel7+ dan tambahkan ke .env hasil dari mailtrap.io
12. Setelah melakukan semuanya tinggal di run dengan php artisan serve dan dapat dicoba untuk button google dan facebook
