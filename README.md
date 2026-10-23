# Praktikum 3 PBO: Access Modifier `protected` (CRUD Mahasiswa)

Proyek Java untuk praktikum Pemrograman Berorientasi Objek (PBO) tentang access modifier `protected`, dengan studi kasus CRUD Mahasiswa memakai `ArrayList`.

Logika CRUD hanya ditulis sekali di class induk. Dua class turunan, satu berbasis console dan satu berbasis GUI, memakainya dari package yang berbeda lewat `extends`.

## Struktur Proyek

```
Praktikum-3-PBO/
└── src/
    ├── induk/
    │   └── Mahasiswa.java       
    ├── anak/
    │   └── MahasiswaApp.java   
    └── gui/
        └── MahasiswaGUI.java    
```

## Cara Menjalankan

Butuh JDK 8 atau lebih baru. Jalankan perintah berikut dari folder utama proyek.

Kompilasi:

```bash
javac -d out src/induk/Mahasiswa.java src/anak/MahasiswaApp.java src/gui/MahasiswaGUI.java
```

Versi console:

```bash
java -cp out anak.MahasiswaApp
```

Versi GUI:

```bash
java -cp out gui.MahasiswaGUI
```

Proyek ini juga bisa dibuka di IDE (NetBeans, IntelliJ IDEA, Eclipse) dengan `src` sebagai source folder, lalu jalankan method `main` pada `MahasiswaApp` atau `MahasiswaGUI`.
