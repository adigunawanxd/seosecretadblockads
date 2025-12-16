# AdBlock Guide for CMS/Website Frameworks and Blogs
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
3. Selesai

Jangan khawatir karena pemanggilan Javascript eksternal. Script javascript ini terhosting di GitHub dan pastinya aman dan cepat hanya untuk sekedar antiadblock.


# AdBlock Guide for CMS/Website Frameworks and Blogs
## EN Versi English
### AdBlock for CMS/Website Frameworks and Blogs

AdBlock is a browser extension that prevents ads from appearing. The main purpose of installing AdBlock is usually to allow visitors to read articles comfortably without being interrupted by ads. For AdSense publishers and blog owners, this can be a problem because one of the main sources of income for bloggers comes from advertisements. If ads do not display, no revenue is generated. Therefore, it is necessary to implement a method to prevent AdBlock from blocking ads. This repository explains how to install an anti-AdBlock script on your blog. A notification will appear for visitors, asking them to disable the AdBlock extension.

## AdBlock Features
1. Displays a notification to disable various adblockers (Adblock, Adblock Plus, Ublock Origin, etc.)
2. Supports AdSense and all other advertising networks
3. Professional design with a complete guide to disabling AdBlock
4. Multi-language support according to the language of the device accessing the website/blog
5. AdBlock deactivation warnings use the user's device language
6. AdBlock popup appears after 5 seconds of user scrolling (safe for search engine crawl bots)

## Guide to Installing AdBlock Protection
1. Place this code before the `</body>` tag of your website or blog.  
2. Example:
   ```html
   <!--Adblock JS-->
   <script src="link" async></script>
   </body>
3. Done

Do not worry about loading external JavaScript. This JavaScript script is hosted on GitHub and is safe and fast, intended solely for anti-AdBlock purposes.
