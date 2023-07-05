# Opside-node
---
layout: '~/layouts/MarkdownLayout.astro'
title: Installation Node
logo: https://mirror-media.imgix.net/publication-images/Hd912XuoV8ekUmD_THtHV.jpeg?h=346&w=346
network: Testnet
chain: pre-alpha-testnet
version: v1.1.1
---
# Guide Opside 

```
Untuk menjalankan opside dengan baik, disarankan memenuhi kebutuhan hardware sebagai berikut:
@@ -15,10 +8,10 @@ Untuk menjalankan opside dengan baik, disarankan memenuhi kebutuhan hardware seb
- Penyimpanan: SSD dengan ruang kosong minimal 500GB (kami merekomendasikan 2TB untuk mainnet)
```

###### Step 1 : Membuat Vps 
### Step 1 : Membuat Vps 
- Pertama buat vps menggunakan cloud yang biasa teman teman gunakan lalu pilih os **Ubuntu 20**

###### Step 2 : Menjalankan Auto Installer 
### Step 2 : Menjalankan Auto Installer 
- Copy semua command di bawah ini lalu pastekan ke vps kalian
```
wget -c https://pre-alpha-download.opside.network/testnet-auto-install-v2.tar.gz 
@@ -27,7 +20,7 @@ chmod +x -R ./testnet-auto-install-v2
cd ./testnet-auto-install-v2 
```

###### Step 3 : Menginstall Validator Clients
### Step 3 : Menginstall Validator Clients
```
./install-ubuntu-en-1.0.sh
```
@@ -41,7 +34,7 @@ cd ./testnet-auto-install-v2
<a href="https://ibb.co/BzKJTjy"><img src="https://i.ibb.co/w0rqpCS/image.png" alt="image" border="0"></a>
- Yang artinya bahwa penginstalan sudah selesai

###### Step 4 : Sebelum Melakukan Stake Validator Silahkan Cek Block Terlebih Dahulu
### Step 4 : Sebelum Melakukan Stake Validator Silahkan Cek Block Terlebih Dahulu
```
opside-chain/show-geth-log.sh
```
@@ -51,24 +44,25 @@ opside-chain/show-geth-log.sh
<a href="https://imgbb.com/"><img src="https://i.ibb.co/q0p2Fdw/image.png" alt="image" border="0"></a>
- Jika sudah sesuai maka teman teman bisa lanjut ke step berikutnya

###### Step 5 : Menjalankan Validator
### Step 5 : Menjalankan Validator
- Pertama teman teman masuk ke https://opside.network/validator
- Selanjutnya scrool kebawah lalu cari start staking
- Lalu tekan continue sampai ke upload deposit data
<a href="https://ibb.co/R96Qqm9"><img src="https://i.ibb.co/SPmVz8P/image.png" alt="image" border="0"></a>
- Jika sudah sampai seperti gambar di atas teman teman kembali ke vps untuk mengambil file json
- Masuk ke vps lalu lihat di sebelah kiri ada file pilih **testnet-auto-install-v2**
###### Masuk ke vps lalu lihat di sebelah kiri ada file pilih **testnet-auto-install-v2**
<a href="https://ibb.co/DCC8ntP"><img src="https://i.ibb.co/mqqX7Gr/image.png" alt="image" border="0"></a>
- Lalu masuk kedalam **validator_keys**
###### Lalu masuk kedalam **validator_keys**
<a href="https://imgbb.com/"><img src="https://i.ibb.co/WcVvxvc/image.png" alt="image" border="0"></a>
- Lalu tarik Deposit data ke deskop kalian
###### Lalu tarik Deposit data ke deskop kalian
<a href="https://imgbb.com/"><img src="https://i.ibb.co/2NV7Nb7/image.png" alt="image" border="0"></a><br />
- Lalu upload file data yang kita ambil dari vps ke 

###### Lalu upload file data yang kita ambil dari vps ke 
<a href="https://ibb.co/Km2WFvH"><img src="https://i.ibb.co/4J8pPrx/image.png" alt="image" border="0"></a>
- Lalu centang semua baru tekan continue
###### Lalu centang semua baru tekan continue
<a href="https://ibb.co/9cKT7Ry"><img src="https://i.ibb.co/WG8yLSB/image.png" alt="image" border="0"></a>
- Selanjutnya **connect wallet** lalu tekan confirm deposit baru tekan continue
###### Selanjutnya **connect wallet** lalu tekan confirm deposit baru tekan continue
<a href="https://ibb.co/vDDwKq0"><img src="https://i.ibb.co/d77WzM8/image.png" alt="image" border="0"></a>

###### Step 6 : Selesai 
### Step 6 : Selesai 
<a href="https://ibb.co/TTgfYgY"><img src="https://i.ibb.co/sPVfbVb/photo-6298480913390089415-w.jpg" alt="photo-6298480913390089415-w" border="0"></a>
