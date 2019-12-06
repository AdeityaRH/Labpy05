#Membuat program nilai mahasiswa yang memiliki menu pilihan:

1.Langkah pertama buat dictionary dengan syntax Daftar={}.

2.Kedua gunakan while True untuk mengulang semua data yang akan diinput nantinya.

3.Ketiga masukkan Data(berupa huruf) pilihan untuk memilih sebuah menu nantinya,dengan syntax c = input().

4.Keempat dengan membuat menu quit if c.lower() == 'q': ,gunanya untuk membuat pilihan menu q yang memiliki fungsi quit (menghenti program) dengan mengkombinasikannya dengan Break.

5.Kelima buat sebuah menu menggunakan elif c.lower() == 'l': ,gunanya untuk membuat pilihan menu l yang memiliki fungsi untuk menampilkan list dari data yang sudah diinput.

6.Keenam buat sebuah list yang nantinya akan menjadi isi dari dictionary yang kita buat,dan list tersebut terdiri dari beberapa input-tan,input-tan tersebut terdiri dari Nama,Nim,Nilai Tugas,UTS dan UAS.

7.Ketujuh buat sebuah menu edit,gunanya ini akan mengedit sebuah data yang ada pada list yang tadi kita buat.dengan menggunakan syntax elif c lower == 'e'.

8.Kedelapan buat sebuah menu hapus,gunanya untuk menghapus data nilai mahasiswa yang ada pada dictionary.Dengan menggunakan syntax elif c lower == 'h' dan dengan menghapus key(NIM) yang ada pada dictionary. 

9.Kesembilan buat sebuah menu cari,gunanya untuk mencari data nilai mahasiswa yang sudah kita input sebelumnya.Dengan syntax elif c lower == 'c'. 

10.Terakhir kita masukkan sebuah snyatx else: untuk akhiran sebuah program kita tersebut.

#Keterangan:

1.Keys pada program ini adalah Nim. 

2.Values pada program ini adalah Nama, tugas, uas, uts, dan Nilai.

#Flowchart:

#Output:

1.Add:

![Screenshot_20191206-232424~2](https://user-images.githubusercontent.com/56975779/70339985-78d10200-1882-11ea-9ab0-2f3fb3a3d8a6.png)

2.List:

![Screenshot_20191206-232736~3](https://user-images.githubusercontent.com/56975779/70340108-bdf53400-1882-11ea-9ff3-214aa28b357a.png)

3.Search:

![Screenshot_20191206-234108~2](https://user-images.githubusercontent.com/56975779/70340428-5c819500-1883-11ea-84a6-fb56acbee9b1.png)

4.Edit:

![Screenshot_20191206-232619~2](https://user-images.githubusercontent.com/56975779/70340193-e41ad400-1882-11ea-8184-690853dfd335.png)

5.Hapus/Delete:

![Screenshot_20191206-232703~2](https://user-images.githubusercontent.com/56975779/70340328-2fcd7d80-1883-11ea-9fbc-03f43089998c.png)

6.Quit:

![Screenshot_20191206-232736~2](https://user-images.githubusercontent.com/56975779/70340533-89ce4300-1883-11ea-8f2a-15782db369ac.png)
