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

![Vercel4](./img/vercel-4.png)

### 5. Setelah berhasil masuk ke dashboard, silahkan buka github untuk cek konektivitas Github to Vercel

![Vercel5](./img/cloud-5.png)

### 6. Pada bagian kanan di bawah _About_ akan ada link yang menandakan bahwa Github sudah berhasil deploy ke vercel dan auto deploy jika ada perubahan pada coding

![Github1](./img/vercel-5.png)<br><br><br><br>

# **Langkah membuat Domain di Hostinger**

### 1. Buka website hostinger.com, ketik nama domain yang diinginkan pada kolom **Cek Domain**, lalu pilih nama akhir untuk website kita

![hostinger1](./img/1-hostinger.png)

### 2. Jika sudah memasukkan nama domain yang diinginkan, maka dilanjutkan untuk memilih paket, klik **tambah ke cart**

![hostinger2](./img/hostinger-1.png)

### 3. Dilanjutkan untuk melakukan pembayaran

![hostinger3](./img/hostinger-2.png)

### 4. Pilih jenis pembayaran, sebagai contoh kita akan memilih pembayaran melalui QRIS

![hostinger4](./img/hostinger-3.png)

### 5. Cek kembali detailnya sebelum melakukan pembayaran, jika sudah sesuai maka klik **Lanjutkan dengan QRIS**

![hostinger5](./img/5-hostinger.png)

### 6. Lanjutkan dengan melakukan scan QR Code

![hostinger6](./img/6-hostinger.png)

### 7. Jika sudah melakukan pembayaran maka akan diarahkan untuk menyelesaikan registrasi domain, silahkan pilih preferensi **Personal** atau **Company** sesuai dengan kebutuhan. Lalu klik **Next Step**

![hostinger7](./img/7-hostinger.png)

### 8. Dilanjutkan mengisi detail kontak seperti :

- Nama lengkap
- email
- Alamat lengkap
- Nomer telepon
- Klik _**Continue**_
  ![hostinger8](./img/8-hostinger.png)

### 9. Klik **Skip** di bagian bawah jika tidak ingin menambahkan plan/fitur. Selamat Anda berhasil mendaftarkan nama domain. Selanjutnya hubungkan domain dengan DNS menggunakan cloudflare

![hostinger9](./img/9.1-hostinger.png)<br><br><br><br>

# **Connect custom domain and DNS**

### 1. Buka website **cloudflare.com** lalu pilih **sign up** atau **log in** dengan mengisi email dan password

![cloud1](./img/1-cloudflare.png)

### 2. Jika sudah berhasil **sign up** maka dianjutkan tahap berikut :

- tulis nama domain custom yang sudah dibuat sebelumnya (pada website hostinger) pada kolom yang tersedia
- klik **Continue**
  ![cloud2](./img/cloud-3.png)

### 3. Pada tampilan berikut, pilih kolom **Free** dan klik **Continue**

![cloud3](./img/cloud-4.png)

### 4. Jika sudah masuk pada halaman berikut, maka silahkan buka kembali vercel untuk copy beberapa elemen untuk diedit

![cloud3](./img/cloud-4.1.png)

### 5. Buka halaman vercel dan klik **Domain** di kanan atas

![cloud4](./img/cloud-5.png)

### 6. isi nama domain custom yang sudah dibuat pada kolom yang tersedia dan klik **Add**

![cloud5](./img/cloud-6.png)

### 7. Pilih pada bagian atas yang direkomendasikan oleh vercel, lalu klik **Add**

![cloud6](./img/cloud-7.png)

### 8. Jika sudah tampil halaman berikut maka Klik edit untuk copy #A (Type, Name, Value) & #CNAME (Type, Name, Value)

![cloud7](./img/cloud-8.png)

### 9. Buka kembali cloudflare & sesuaikan #A & #CNAME sesuai dengan vercel lalu klik **Continue** (tunggu prosesnya kurang lebih 24 jam)

![cloud8](./img/cloud-9.png)

### 10. Buka kembali vercel dan jika sudah ada tanda **Valid Configuration** pada sisi centang biru maka domain custom sudah berhasil dihubungkan dengan DNS. Klik Domain custom yang ada maka akan langsung terhubung ke tampilan website

![cloud8](./img/cloud%209-1.png)

### 11. **CONGRATS**

![cloud9](./img/cloud-10.png)
