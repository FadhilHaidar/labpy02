# Latihan 3: Buat program python untuk kasus berikut:

## Kasus 1: Program Pemesanan Tiket Bioskop

Buat program yang menghitung harga tiket bioskop. Tiket reguler berharga Rp50.000,
sedangkan tiket VIP berharga Rp100.000. Jika user memiliki kartu member, mereka
mendapatkan diskon 20% dari harga tiket. Program ini harus meminta tipe tiket dan status
member dari user, lalu menghitung total harga yang harus dibayar.

1. Flowchart:
   
![Flowchart (7)](https://github.com/user-attachments/assets/db353fb8-5e6e-475c-895c-7dc3ad1c7529)

2. Program Python:

   Menggunakan If Else:
   
   ![image](https://github.com/user-attachments/assets/53e75f7a-b2d6-4e6b-87b6-49e38ba2b0f8)

   Menggunakan operator ternary:
   
   ![image](https://github.com/user-attachments/assets/f980e1e0-cec4-4f12-bb46-b8d3e9480d11)


3. Algoritma:

    - Tampilkan pilihan kepada pengguna untuk menentukan tipe tiket (Reguler atau VIP).
   
    - Minta pengguna memasukkan status keanggotaan (member atau bukan member).
   
    - Tetapkan harga tiket dasar:

        Jika tipe tiket adalah Reguler, harganya adalah Rp50.000.
      
        Jika tipe tiket adalah VIP, harganya adalah Rp100.000.
   
    - Cek status keanggotaan pengguna:
   
        Jika pengguna adalah member, berikan diskon 20%.
       
        Jika tidak, harga tetap tanpa diskon.
   
    - Tampilkan total harga yang harus dibayar.
  
4. output:

   - Harga tiket Reguler dengan member
     
     ![image](https://github.com/user-attachments/assets/a458a9c2-6515-4c5b-8327-3fe7751707c0)

   - Harga tiket Reguler tanpa member
     
     ![image](https://github.com/user-attachments/assets/ed959933-ea5a-42c4-b485-25e6b1a6362a)

   - Harga tiket VIP dengan member
     
     ![image](https://github.com/user-attachments/assets/8932ec22-aee0-4022-a367-a9cb97c16dac)

   - Harga tiket VIP tanpa member
     
   - ![image](https://github.com/user-attachments/assets/07d100bc-d89b-498f-b91e-b0e272015d95)

## Kasus 2: Program Kalkulator Sederhana

Buat program kalkulator yang menerima dua angka dan satu operator aritmatika dari
pengguna (penjumlahan, pengurangan, perkalian, atau pembagian). Program akan
menghitung hasil sesuai dengan operator yang dipilih.

1. Flowchart:

![Flowchart (6)](https://github.com/user-attachments/assets/e559b6e9-6646-4c0f-ad78-d591b071a8fd)

2. Program Python:

![image](https://github.com/user-attachments/assets/86b0115d-2def-49ee-b5b7-87636b6f5b84)


3. Algoritma:

    - Pengguna memasukkan dua angka.

    - pengguna memilih operator aritmatika (+, -, *, atau /).

    - Periksa operator:
   
        Jika operator adalah +, hitung penjumlahan.
    
        Jika operator adalah -, hitung pengurangan.
       
        Jika operator adalah *, hitung perkalian.
       
        Jika operator adalah /, hitung pembagian (cek juga agar tidak membagi dengan 0).
   
    - Tampilkan hasil perhitungan (Jika operator tidak valid, tampilkan pesan kesalahan)
   

4. output:

   Penjumlahan:
   
   ![image](https://github.com/user-attachments/assets/ed0e1648-6edc-4247-8b53-02d1f404ddec)
   
   Pengurangan:
   
   ![image](https://github.com/user-attachments/assets/7de86f9c-92aa-4a27-924c-af1f155e4681)
   
   Perkalian:
   
   ![image](https://github.com/user-attachments/assets/957440d0-1bbc-4283-ba42-7bb73755aff8)

   Pembagian:
   
   ![image](https://github.com/user-attachments/assets/506d1823-7004-42d8-85ed-4148d50f5f21)

   Pembagian (Nol):
   
   ![image](https://github.com/user-attachments/assets/60d0aaaf-0993-48af-812f-9d603b2e88b1)
