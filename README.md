# pemulungonline
Banyak browser web tetap ada permintaan POST cleartext dalam memori jauh setelah permintaan dibuat. Ini dapat disalahgunakan untuk mencuri kata sandi cleartext dari memori setelah permintaan masuk.

Proyek (ini) menunjukkan ekstraksi kata sandi dari memori yang sedang berjalan di sistem Windows. Alat ini melakukan hal yang sama untuk sistem Linux. Regex yang dipilih langsung dari proyek-proyekproyek-proyekpute

#Contoh

`` `

Ditemukan chrome running, scanning ....
PID = 19789
PID = 19800
PID = 19801
PID = 19804
PID = 19853
PID = 19908
PID = 20329
PID = 21041
Ditemukan layanan Dropbox: ['login_email = somedudesemail% 40gmail.com & login_password = thisisasecretpassword & remember_me = Benar &', 'login_email = somedudesemail% 40gmail.com & login_password = thisisasecretpassword & remember_me = Benar &', 'login_email = somedudesemail% 40gmail.com & login_password = thisisasecretpassword & remember_me = Benar &']
Ditemukan kromium berjalan, memindai ....
PID = 17497
PID = 17531
PID = 18653
PID = 20757
PID = 27493
PID = 27502
PID = 27504
PID = 27565
PID = 27655
PID = 27683
Layanan Gmail yang ditemukan: [& Email = somedudesemail & Passwd = someOTHERsecretpassword & PersistentCookie = ']
Menjalankan firefox, memindai ....
PID = 3810
PID = 3872
`` `

##  Pertimbangan ekstra

Meskipun alat ini digunakan untuk mengekstrak parameter permintaan dari permintaan POST, karena Aplikasi Halaman Tunggal menjadi lebih populer, tetap variabel kata sandi akan tetap ada, karena pengembang tidak memodifikasinya. Layanan ini akan dapat dieksploitasi menggunakan metode simaliar ke metode yang menggunakan alatini
# Jangan pakai alat saya, gunakan yang ini ya.
# KHUSUS YG UDAH DEWASA AJA
