# Final-Project-Teori-Graf

| Name           | NRP        | Kelas     |
| ---            | ---        | ----------|
| Addien Zafriyan Al Akhsan | 5025241058 | D |
| Callista Fidelya Roba Gultom | 5025241086 | D |
| Raden Kurniawan Agung Fitrianto | 5025241104 | D |

## Cara Penggunaan Program
### Knight's Tour
- Drag & drop bidak kuda ke posisi yang diinginkan
- Pilih tipe tour (open & closed)
- Tekan tombol Start Calculation
- Hasilnya adalah sebuah path history dari tour tersebut
- Terdapat lima tombol yang dapat memutar perjalanan dari bidak kuda
- Juga terdapat settings untuk toggle garis path dan warna visited tiles

### Largest Monotonically Increasing Subsequence
- Input angka dengan dipisah oleh spasi
- Tekan tombol generate
- Output adalah sebuah list semua solusi dan visualisasi menggunakan tree




## Knight Tour 
Knight's Tour (atau Perjalanan Kuda) adalah sebuah teka-teki matematika klasik yang menggunakan papan catur dan satu bidak kuda (Knight).  

### Input
<img width="413" height="415" alt="image" src="https://github.com/user-attachments/assets/340d6129-6183-4cb3-b07b-f221e7605f81" />

- User mengklik salah satu kotak pada papan catur kosong di layar.
- Aplikasi akan menempatkan ikon Kuda (Knight) di kotak tersebut (misalnya di G2 seperti pada gambar yang kamu kirim).
- Ini menetapkan koordinat awal (x, y) atau (baris, kolom) dari mana algoritma harus mulai mencari jalan.
  
<img width="233" height="238" alt="image" src="https://github.com/user-attachments/assets/f19c8a13-d38a-4adf-9f25-969897dd159f" />

- User menekan tombol perintah, biasanya bertuliskan "Start", "Solve", atau "Run" (mungkin juga ada opsi untuk mengatur kecepatan animasi: Slow/Fast).
- Browser menjalankan algoritma (biasanya Backtracking yang dikombinasikan dengan Warnsdorff's Rule agar lebih cepat).
- Tombol mungkin berubah menjadi "Stop" atau dinonaktifkan sementara proses berjalan.


### Output

<img width="195" height="448" alt="image" src="https://github.com/user-attachments/assets/ae4c1825-c702-47cc-8b63-d3550b5db429" />
<img width="410" height="404" alt="image" src="https://github.com/user-attachments/assets/84cb7467-486a-4880-a5e8-818f1805db80" />

user melihat Kuda bergerak sendiri dari satu kotak ke kotak lain, meninggalkan garis jejak




## LMIS 
LMIS merupakan program yang dibuat untuk menyelesaikan suatu permasalahan yaitu mencari largest monotanically increasing subsequence dari suatu urutan bilangan. 

### Input 
<img width="296" height="251" alt="image" src="https://github.com/user-attachments/assets/53caef1f-044a-4d3b-9c8a-dd2138616dc0" />   

Pada program LMIS ini, ada beberapa input yang dapat dilakukan oleh user:
- Urutan bilangan yang akan dicari LMIS-nya. Bilangan akan dipisahkan dengan spasi. 
- Memulai program mencari LMIS bilangan yang telah dimasukkan sebelumnya dengan mempencet tombol 'Generate'
- Juga terdapat fungsi tambahan yang dapat menghilangkan edge yang menghubungkan antar dua node dalam tree hasil LMIS

### Output  
Pada program LMIS ini, ada beberapa output yang akan didapatkan dari input user sebelumnya:  
- Visualisasi tree pemetaan semua monotanically increasing subsequence dari suatu urutan bilangan yang telah diinputkan 
<img width="935" height="592" alt="image" src="https://github.com/user-attachments/assets/bbdda241-398e-46a8-9a9f-f4ced3c2d9d9" /> \  
- Hasil yang akan menunjukkan LMIS dari bilangan yang telah dinput sebelumnya, dengan berkemungkinan menunjukkan beberapa jawaban sesuai dengan urutan bilangannya  
<img width="238" height="232" alt="image" src="https://github.com/user-attachments/assets/f39b4306-ae5c-446a-94d3-278651e38865" />  \    
<img width="297" height="62" alt="image" src="https://github.com/user-attachments/assets/328c14b3-129e-4326-8a1e-12fb38b8ad41" />\
- Visuliasi tree pemetaan sebelumnya dengan edge yang tidak ditampilkan  
<img width="905" height="579" alt="image" src="https://github.com/user-attachments/assets/454560cd-097d-4354-b9f2-ada37bed920d" />

