# Acurast Template HTML

# 📄 Cara Mengganti Teks di Portofolio

Halo! 🎉
Ini adalah panduan singkat untuk mengganti teks pada portofolio **tanpa harus mengerti HTML**.

---

## 🔧 Bagian yang Bisa Diganti

Buka [index.html](https://github.com/cryptofinderid/AcurastTemplateHTML/blob/main/index.html) dan copy semua kode ke teks editor yang biasa kamu gunakan.

Di dalam file `index.html`, ada bagian **script kecil di bagian paling bawah** seperti ini:

```html
<script>
  (function(){
    const data = {
      nama: 'Fuad',
      hobi: ['Pengembangan Web','Membaca & Menulis','Fotografi Konsep'],
      cita: 'Menjadi pengembang web berpengaruh yang membangun produk digital yang memecahkan masalah nyata dan menginspirasi tim.'
    };

    document.getElementById('nama').textContent = data.nama;
    const chipsEl = document.getElementById('hobi').querySelector('.chips');
    chipsEl.innerHTML = data.hobi.map(h => `<span class="chip">${h}</span>`).join('');
    document.getElementById('cita').textContent = data.cita;
  })();
</script>
```

---

## ✍️ Cara Mengganti Teks

1. **Nama**

   * Cari bagian:

     ```js
     nama: 'Fuad',
     ```
   * Ganti `Fuad` dengan nama Anda.
     Contoh:

     ```js
     nama: 'Budi Santoso',
     ```

2. **Hobi**

   * Cari bagian:

     ```js
     hobi: ['Pengembangan Web','Membaca & Menulis','Fotografi Konsep'],
     ```
   * Ubah isi daftar sesuai hobi Anda.
     Contoh:

     ```js
     hobi: ['Mendaki Gunung','Bermain Musik','Ngopi Santai'],
     ```

3. **Cita-cita**

   * Cari bagian:

     ```js
     cita: 'Menjadi pengembang web berpengaruh ...',
     ```
   * Ganti teks di dalam tanda `'...'` dengan cita-cita Anda.
     Contoh:

     ```js
     cita: 'Ingin menjadi musisi profesional dan membuka sekolah musik.',
     ```

---

## 🚀 Selesai!
