# Cara Install MariaDB Linux Mint
### 1. Masuk ke mode root dengan syntax berikut lalu masukkan password:
```
sudo su
```
### 2. Ketik syntax berikut untuk update system linux:
```
apt update
```

```
apt upgrade
```
### 3. Selanjutnya ketik syntax:
```
apt install mariadb-server
```
### 4. Ketik "Y" Untuk menyetujui
### 5. Lalu Ketik syntax berikut untuk memulai sistem MariaDB:
```
systemctl start mariadb
```
### 6. Selanjutnya pastikan layanan MariaDB dimulai setiap kali sistem boot dengan syntax:
```
systemctl enable mariadb
```
### 7. Untuk cek status MariaDB ketik:
```
systemctl status mariadb
```
### 8. Untuk meningkatkan keamanan instalasi server pada MariaDB ketik syntax:
```
mysql_secure_installation
```
Jika terdapat pilihan "Y"/"N", pilih "N" 2x. Terakhir pilih "Y" 4x. MariaDB akhirnya siap dijalankan!
