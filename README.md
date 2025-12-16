# AdBlock Guide for CMS/Website Frameworks and Blogs

README ini berisi panduan dalam **dua bahasa**: Indonesia dan Inggris.

---

## 🇮🇩 Versi Indonesia

### Adblock untuk CMS/Framework Website dan Blog
AdBlock adalah ekstensi browser yang berfungsi mencegah iklan untuk muncul. Tujuan pemasangan AdBlock biasanya agar pengunjung bisa membaca artikel dengan nyaman tanpa perlu melihat iklan yang berseliweran. Bagi publisher AdSense dan pemilik blog, hal ini bisa menjadi masalah karena salah satu penghasilan utama sebagai bloger adalah dari iklan. Jika iklan tidak tampil, maka tidak ada penghasilan yang masuk. Karenanya perlu dilakukan satu cara untuk mencegar AdBlock menghalangi munculnya iklan. Pada repository ini akan dijelaskan cara memasang script anti AdBlock di blog. Nantinya akan tampil notifikasi kepada pengunjung untuk mematikan ekstensi AdBlock.

### Fitur Adblock
1. Memunculkan notifikasi untuk memonakifkan berbagai adblock (Adblock, Adblock Plus, Ublock Origin, dll)
2. Support Adsense dan semua jaringan periklanan lainnya
3. Desain profesional lengkap panduan mematikan adblock
4. Multi bahasa sesuai bahasa perangkat yang mengakses web/blog
5. Peringatan nonaktif adblock menggunakan bahasa perangkat pengguna
6. Popup adblock muncul setelah 5 detik pengguna melakukan scroll (aman untuk bot crawl mesin pencari)

### Panduan memasang AdBlock
1. Pasang kode ini sebelum `</body>` website / blog Anda  
2. Contoh:
   ```html
   <!--Adblock JS-->
   <script src="link" async></script>
   </body>
