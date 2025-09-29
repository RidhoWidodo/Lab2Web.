# Lab2Web.
*Nama : Muhammad Ridho Hafiedz*

*Nim :312410195*

*Kelas : TI.24 A2*

# Tugas 1

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS.   
   ```css
   body {
    font-family: 'Open Sans', sans-serif;
    background-color: #f0f0f0;
   }
   h1 {
    font-size: 28px;
    color: darkblue;
    text-transform: uppercase;
    letter-spacing: 2px;
   }
   p {
    color: #444;
    line-height: 1.6;
   }
   ```
   
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!   
   - `h1 { ... }` → berlaku untuk semua elemen `<h1>` di halaman.
   - `#intro h1 { ... }` → hanya berlaku untuk `<h1>` yang ada di dalam elemen dengan `id="intro"`.  
   *Contoh*
  ```css
     h1 { color: red; }
     #intro h1 { color: blue;}
```

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!   
   - Urutan prioritas: **Inline > Internal > Eksternal**.
   *Contoh*
```html
<head>
    <link rel="stylesheet" href="style.css">
    <style>
        p { color: green; }
    </style>
</head>
<body>
    <p style="color: red;">Teks Contoh</p>
</body>
```

4.  Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! `( <p id="paragraf-1" class="text-paragraf"> )`   
*Contoh*
```html
<p id="paragraf-1" class="text-paragraf">Teks Contoh</p>
```
```css
.text-paragraf { color: green; }
#paragraf-1 { color: blue; }
```
# Tugas2

# Tahap  1
<img width="1917" height="1078" alt="Image" src="https://github.com/user-attachments/assets/00b1245f-6181-49a3-aaac-06e8a1a67ab5" />

<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/c42dcaf8-3d8d-42dd-ac12-4078926a7516" />

# Tahap 2

<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/1c8fe460-8d60-4f0a-bae9-343c97865b6e" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/85de4614-2673-4eca-abde-ead2cd887469" />

# Tahap 3

<img width="1256" height="234" alt="Image" src="https://github.com/user-attachments/assets/be8066e2-2c75-4791-9f4e-239c614c20ea" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/abceb259-2c65-4f86-9d14-3bf31d69b2fd" />

# Tahap 4

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/057ee34c-77ac-4209-899d-cb7481d29814" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/b7d16d41-1781-4058-aa44-19db026c9d5b" />

# Tahap  5

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/b9101a95-99f8-4452-8d3f-6045a34b5683" />

<img width="1919" height="1078" alt="Image" src="https://github.com/user-attachments/assets/13454ac3-ea41-44c2-b009-2c9d2ec469a0" />
