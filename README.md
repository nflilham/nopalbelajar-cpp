# nopalbelajar-cpp

![C++](https://img.shields.io/badge/C%2B%2B-17-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Compiler](https://img.shields.io/badge/Compiler-MinGW--W64%20g%2B%2B-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-2EA44F?style=for-the-badge)

Repositori belajar mandiri bahasa **C++** (`nopalbelajar-cpp`) yang memisahkan eksperimen sintaks dasar dan latihan/mini-projek mandiri.

---

## Profil

| Keterangan | Informasi |
| :--- | :--- |
| **Nama** | Naufal Ilham Fauzan |
| **NIM** | 2502106 |
| **Kelas** | 3B |
| **Program Studi** | Pendidikan Multimedia |
| **Fakultas / Kamda** | Kampus UPI Di Cibiru |
| **Universitas** | Universitas Pendidikan Indonesia |

---

## Daftar Latihan

### `brainstorming/`

| No | Berkas | Ringkasan |
|:---:|:---|:---|
| `001` | [001_hello_world.cpp](./brainstorming/001_hello_world.cpp) | Program dasar mencetak teks multi-baris dengan `std::cout` |

### `projek_mandiri/`

Lihat panduan penamaan dan kompilasi di [projek_mandiri/README.md](./projek_mandiri/README.md).

---

## Struktur Direktori

```text
nopalbelajar-cpp/
├── brainstorming/                 # Eksperimen cepat dan latihan dasar (NNN_topik.cpp)
│   └── 001_hello_world.cpp        # Latihan output dasar C++
├── projek_mandiri/                # Latihan dan mini-projek mandiri
│   └── README.md                  # Panduan penamaan dan cara menjalankan latihan mandiri
├── .gitattributes                 # Pengaturan konsistensi akhir baris (LF/CRLF)
├── .gitignore                     # Pengecualian binary, cache, dan file coretan lokal
└── README.md                      # Dokumentasi utama repositori
```

> Berkas `brainstorming/000_brainstorming.cpp` dan seluruh hasil kompilasi (`*.exe`, `*.o`) sengaja diabaikan melalui `.gitignore`.

---

## Lingkungan & Standar Teknis

- **Sistem operasi & terminal:** Windows 11 (64-bit) menggunakan PowerShell
- **Compiler:** `g++` (MinGW-W64) dengan standar `-std=c++17 -Wall -Wextra`
- **Pustaka:** C++ Standard Library (`std::vector`, `std::string`, `std::map`, dll.) tanpa dependensi eksternal kecuali ditentukan

---

## Cara Menjalankan di PowerShell

Kloning repositori lalu kompilasi dan jalankan salah satu berkas C++:

```powershell
git clone https://github.com/nflilham/nopalbelajar-cpp.git
cd nopalbelajar-cpp
g++ -std=c++17 -Wall -Wextra brainstorming\001_hello_world.cpp -o 001_hello_world.exe
.\001_hello_world.exe
```
