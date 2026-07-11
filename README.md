# Pengenalan Python

Python adalah bahasa pemrograman tingkat tinggi
yang dibuat oleh Guido van Rossum dan pertama kali dirilis pada tahun 1991
Python terkenal karena sintaksnya yang sederhana dan mudah dipahami,
mirip dengan bahasa Inggris
https://www.python.org/

## Karakteristik Python

- **Mudah dipelajari**: Sintaks yang bersih dan sederhana  
- **Interpreted language**: Tidak perlu dikompilasi terlebih dahulu  
- **Cross-platform**: Berjalan di Windows, Mac, Linux  
- **Open source**: Gratis dan bebas digunakan  
- **Versatile**: Bisa digunakan untuk berbagai keperluan  

## Kegunaan Python

- **Web Development**: Django, Flask  
- **Data Science & Analytics**: Pandas, NumPy, Matplotlib  
- **Machine Learning**: TensorFlow, scikit-learn  
- **Automation/Scripting**: Otomatisasi tugas-tugas repetitif  
- **Desktop Applications**: Tkinter, PyQt  
- **Game Development**: Pygame  

## Kelebihan Python

- **Sintaks yang mudah dipahami**  
- **Library yang sangat banyak**  
- **Komunitas yang besar dan aktif**  
- **Pengembangan yang cepat**  
- **Multiplatform** (bisa berjalan di banyak sistem operasi)  

## Kekurangan Python

- **Kecepatan eksekusi lebih lambat** dibanding bahasa compiled (C, C++, Java, Golang, dan lain-lain)  
- **Konsumsi memori lebih besar**  
- **Tidak ideal untuk mobile development**  

## Instalasi Python

- [Download Python](https://www.python.org/downloads/)  
- Gunakan terminal / shell / command prompt, ketik:  
  ```bash
  python --version

# CMD Wajib

![CMD](img/cmd-priority.png)

# 🔧 Sifat Variabel: Dinamis vs Statis

## 📌 Definisi

### Variabel Statis (Static Typing)

Variabel yang **tipe datanya ditentukan saat deklarasi** dan **tidak bisa berubah** sepanjang program berjalan. Tipe dicek saat **compile-time** (sebelum program dijalankan).

```java
int umur = 20;      // tipe int, hanya bisa menyimpan integer
umur = "dua puluh"; // ❌ ERROR! Tidak bisa diubah ke String
```

### Variabel Dinamis (Dynamic Typing)

Variabel yang **tipe datanya ditentukan saat runtime (saat program berjalan)** dan **bisa berubah-ubah sesuai nilai yang diberikan**.

```python 
umur = 20           # tipe int
umur = "dua puluh"  # ✅ BERHASIL! Sekarang jadi String
```

## Hubungan Keduanya

```
┌─────────────────────────────────────────┐
│           SEMUA VARIABEL                │
│  ┌─────────────┐    ┌─────────────┐   │
│  │   STATIS    │    │   DINAMIS   │   │
│  │  (Compile)  │    │  (Runtime)  │   │
│  └─────────────┘    └─────────────┘   │
│         │                  │            │
│         └──────┬─────────┘            │
│                ▼                      │
│      SAMA-SAMA MENYIMPAN DATA         │
│      SAMA-SAMA BISA DIUBAH NILAINYA   │
│      (kalau statis: nilai sesuai tipe)│
└─────────────────────────────────────────┘
```

```
┌─────────────────────────────────────────────────────────────┐
│                    BAHASA PEMROGRAMAN                        │
│  ┌─────────────────┐  ┌─────────────────┐  ┌────────────┐ │
│  │     STATIS      │  │     DINAMIS     │  │   HYBRID   │ │
│  │   (Compile)     │  │   (Runtime)     │  │  (Keduanya)│ │
│  ├─────────────────┤  ├─────────────────┤  ├────────────┤ │
│  │ • Java          │  │ • Python        │  │ • TypeScript│ │
│  │ • C / C++       │  │ • JavaScript    │  │ • Kotlin   │ │
│  │ • C#            │  │ • Ruby          │  │ • Dart     │ │
│  │ • Rust          │  │ • PHP           │  │ • Python 3+│ │
│  │ • Go            │  │ • Lua           │  │            │ │
│  │ • Swift         │  │                 │  │            │ │
│  └─────────────────┘  └─────────────────┘  └────────────┘ │
│         │                    │                    │         │
│    Aman & Cepat         Fleksibel & Cepat     Terbaik     │
│    tapi ketat           tapi riskan           keduanya?    │
└─────────────────────────────────────────────────────────────┘
```

