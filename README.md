# Documentation Milestone 1 Dimas Adhi Pratama

<br>

## **1. Deploy Github Project to Netlify** [Click Here](#deploy-github-project-to-vercel)

## **2. Langkah Membuat Domain di Hostinger** [Click Here](#langkah-membuat-domain-di-hostinger)

## **3. Connect custom domain and DNS** [Click Here](#connect-custom-domain-and-dns)

<br>

### Link Deployment : [Netlify](https://dulcet-sable-378cd3.netlify.app/)

### Link Custom Domain : [Hostinger](https://www.inirumahsakit.shop/)

<br>

# **Deploy Github Project to Netlify**

### 1. Buka netlify.com, Klik **Log In** jika sudah pernah sign up sebelumnya, lalu sambungkan Github dengan Netlify

![Netlify1](./img/netlify-1.png)

### 2. Klik **Add New Site** dan pilih **Import an existing project**

![Netlify2](./img/netlify-2.png)

### 3. Pilih **Deploy with Github**

![Netlify3](./img/netlify-3.png)

### 4. Pilih Repo yang ada di Github dan pilih project yang akan dideploy

![Netlify4](./img/netlify-4.png)

### 5. Scroll ke bawah dan klik **Deploy**

![Netlify5](./img/netlify-5.png)

<br><br><br><br>

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

![cloud4](./img/cloudflare4.png)

### 5. Jika sudah tampil halaman berikut maka scroll ke bawah dan klik **Continue**

![cloud5](./img/cloudflare5.png)

### 6. Selanjutnya Klik **Continue** di bagian bawah dan copy 2 **Name server** ke website hostinger

![cloud6](./img/cloudflare6.png)

### 7. Buka kembali webiste Hostinger dan pilih **DNS/Nameservers** di sidebar kiri lalu klik **Change Nameservers**

![cloud7](./img/cloudflare7.png)

### 8. Pada menu **Select Nameservers** pilih **Change Nameservers**, lalu paste 2 **Nameservers** dari **Cloudflare** lalu klik **Save**

![cloud8](./img/cloudflare8.png)

### 9. Akan muncul **Pop Up** seperti halaman berikut dan klik **Close**, tunggu kurang lebih 24 jam agar website sudah dapat dipublish

![cloud9](./img/cloudflare9.png)

### 10. Jika sudah 24 jam maka cek kembali ke halaman **Cloudflare** klik menu Overview di sidebar kanan dan jika berhasil akan seperti tampilan berikut

![cloud10](./img/cloudflare10.png)

### 11. Jika domain sudah aktif maka kembali buka Netlify dan klik **Set up custom domain** pada nomer 2

![Netlify6](./img/netlify-6.png)

### 12. Pada kolom yang tersedia isi custom domain yang sudah berhasil dibuat lalu klik Verify

![Netlify7](./img/netlify-7.png)

### 13. Masuk ke halaman cloudflare dan klik **DNS** pada sidebar kiri dan klik edit pada kolom CNAME, paste CNAME dari Netlify, scroll ke bawah dan klik Save

![Netlify-8](./img/netlify-8.png)

### 14. Masuk kembali ke Netlify dan refresh page, jika sudah tampil seperti halaman berikut berarti sudah berhasil. CONGRATS!!!

![Netlify-9](./img/netlify-9.png)
