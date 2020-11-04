# Tugas 4 MySQL

### 1. Buatlah database permainan
```
CREATE DATABASE permainan;
```
### 2. Buatlah table sepakbola
```
CREATE TABLE sepakbola;
```
### 3. Buatlah struktur table sepakbola sebagai berikut:
```
CREATE TABLE sepakbola (id_pemain INT(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
nama_pemain VARCHAR(100) NOT NULL,
usia_pemain INT(2) NOT NULL,
posisi_pemain VARCHAR(50) NOT NULL);
```
### 4. Ubah nama tabel menjadi sepakbola_indonesia
```
RENAME TABLE sepakbola TO sepakbola_indonesia;
```
### 5. Hapus table sepakbola_indonesia dan database permainan
```
DROP DATABASE permainan;
```
