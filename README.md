# Documentation Milestone 1 Dimas Adhi Pratama

<br>

## **1. Deploy Github Project to Vercel** [Click Here](#deploy-github-project-to-vercel)

## **2. Langkah Membuat Domain di Hostinger** [Click Here](#langkah-membuat-domain-di-hostinger)

## **3. Connect custom domain and DNS** [Click Here](#connect-custom-domain-and-dns)

<br><br>

# **Deploy Github Project to Vercel**

### 1. Buka vercel.com, Klik **Add New** di bagian kanan & pilih Project

![Vercel1](./img/vercel1.png)

### 2. Dalam kolom search ketik nama project dan klik **import**

![Vercel2](./img/vercel2.png)

### 3. Klik Deploy di bagian bawah

![Vercel3](./img/vercel3.png)

### 4. Jika sudah berhasil, klik **Continue to Dashboard**

![Vercel4](./img/vercel4.png)

### 5. Setelah berhasil masuk ke dashboard, silahkan buka github untuk cek konektivitas Github to Vercel. Pada bagian kanan di bawah _About_ akan ada link yang menandakan bahwa Github sudah berhasil deploy ke vercel dan auto deploy jika ada perubahan pada coding

![Vercel5](./img/vercel5.png)<br><br><br><br>

# **Langkah membuat Domain di Hostinger**

### 1. Buka website hostinger.co.id dan Klik **Log In**. Jika sudah berhasil Log In maka pilih Tab **Domains** dan pilih **Get a New Domain**

![hostinger1](./img/hostinger1.png)

### 2. Jika sudah memasukkan nama domain yang diinginkan, maka dilanjutkan untuk memilih nama akhir domain, contoh pilih .shop dan klik search. Jika nama domain tersedia maka klik **Buy Now**

![hostinger2](./img/hostinger2.png)

### 3. Dilanjutkan untuk pemilihan paket pembayaran. Klik **Choose Payment Method**

![hostinger3](./img/hostinger3.png)

### 4. Pilih jenis pembayaran, sebagai contoh kita akan memilih pembayaran melalui QRIS.

![hostinger4](./img/hostinger4.png)

### 5. Jika sudah berhasil melakukan pembayaran maka klik continue dan selanjutnya hubungkan domain dengan DNS menggunakan cloudflare

![hostinger5](./img/hostinger5.png)

<br><br><br><br>

# **Connect custom domain and DNS**

### 1. Buka website **cloudflare.com** lalu pilih **sign up** atau **log in** dengan mengisi email dan password

![cloud1](./img/cloudflare1.png)

### 2. Jika sudah berhasil **sign up** maka pilih **Add Site** button

![cloud2](./img/cloudflare2.png)

### 3. Isi nama domain yang sudah dibuat pada kolom yang tersedia dan klik **Continue**

![cloud3](./img/cloudflare3.png)

### 4. Akan tampil pilihan paket lalu scroll ke bawah dan pilih \*Free** lalu klik **Continue\*\*

![cloud4](./img/cloudlflare4.png)

### 5. Jika sudah tampil halaman berikut maka scroll ke bawah dan klik **Continue**

![cloud5](./img/cloudflare5.png)

### 6. Selanjutnya copy 2 **Name server** ke website hostinger

![cloud6](./img/cloudflare6.png)

### 7. Buka kembali webiste Hostinger dan pilih **DNS/Nameservers** di sidebar kiri lalu klik **Change Nameservers**

![cloud7](./img/cloudflare7.png)

### 8. Pada menu **Select Nameservers** pilih **Change Nameservers**, lalu paste 2 **Nameservers** dari **Cloudflare** lalu klik **Save**

![cloud8](./img/cloudflare8.png)

### 9. Akan muncul **Pop Up** seperti halaman berikut dan klik **Close**, tunggu kurang lebih 24 jam agar website sudah dapat dipublish

![cloud9](./img/cloudflare9.png)
