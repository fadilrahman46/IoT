GPIO (General Purpose Input/Output) merupakan library yang digunakan untuk mengontrol GPIO Raspberry Pi menggunakan Python. 
GPIO merupakan pin atau tempat yang digunakan sebagai input dan output 
Fungsi pinMode berguna untuk mengkonfigurasikan nomor pin yang dipakai. 
pinMode(0, IN) berarti kita mengkonfigurasikan pin nomor 0 (D0) sebagai input. 
Sedangkan pinMode(1, Out) berarti kita mengkonfigurasikan pin nomor 1 (D1) sebagai output. 
Fungsi digitalRead berguna untuk membaca input pada pin yang ditentukan. 
digitalRead(0) berarti program membaca input pada pin 0 (D0). 
Fungsi digitalWrite berguna untuk menyetel nilai pada pin yang ditentukan (high atau low). 
Nilai ini akan terus ada, sampai nilai tersebut diubah lagi. 
