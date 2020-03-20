---
draft: false
date: 2020-03-13T04:21:27+07:00
title: "Malam jumat menjelang subuh"
slug: mala-juma-psotingan-tes

tags:
    - Python -curhat

categories:
    - Pemrograman -bukanlah


image: https://www.lombokfoss.com/img/format/format-flashdisk-linux.png
thumbnail: https://www.lombokfoss.com/img/format/format-flashdisk-linux.png
---
Kabar gembira bagi para front-end developer, Bootstrap 4 kini sudah
dirilis versi Beta-nya.

Artinya sebentar lagi akan memasuki versi final.
Sebenarnya saya berencana ingin mencobanya setelah mencapai versi final
atau stabil.

Namun, kerena penasaran… jadinya ya dicoba aja sekarang <img draggable="false" class="emoji" alt="😄" src="/img/icon/twemoji/1f604.svg">.</p>

<p>Pada percobaan ini saya akan membuat sebuah template halaman
web sederhana dan hasil akhirnya akan saya bagikan 
<strong>gratis</strong>.</p>

Mungkin nanti bisa dikembangkan untuk template blog
<a href="/topik/hugo/">Hugo</a>, Wordpress, dan Blogger.

Saya juga berencana menjadikan hasil percobaan ini sebagai
referensi untuk <a href="/petanikode-bootstrap4/">pengembangan template Petani Kode selanjutnya</a>.</p>

Tulisan ini bukan tutorial, tapi hanya <em>sharing</em> saja. Bisa dibilang semacam review setelah menggunakan Bootstrap 4
versi beta.

Selamat menikmati…

<h2 id="apa-yang-baru-di-bootstrap-4">Apa yang Baru di Bootstrap 4?</h2>

Banyak hal baru yang hadir di Bootstrap 4, diantaranya:
<ul><li>Sekarang Boostrap menggunakan <a href="/topik/sass">Sass</a>, sebelumnya mengggunakan Less.</li>
<li>Layout-nya sekarang menggunakan Flexbox.</li>
<li>Penambahan komponen <em>Cards</em> untuk menggantikan <em>wells</em>, 
<em>thumbnails</em>, dan <em>panels</em>.</li>
<li>Mem-forked Normalize.css untuk membuat modul CSS baru bernama Reboot 
untuk HTML reset.</li>
<li>Opsi kostumisasi baru menggunakan variabel Sass.</li>
<li>Menghentikan dukungan untuk versi browser jadul seperti IE8 dan IE9 
serta menggunakan unit rem sebagai satuan ukuran komponen.</li>
<li>Penulisan ulang plugin JavaScript menggunakan ES6 untuk memanfaatkan 
peningkatan yang diberikan padanya.</li>
<li>Meningkatkan auto-placement untuk tooltip, popover, dan dropdown berkat pustaka bernama Popper.js.</li><li>Tampilan Dokumentasi yang telah didesain ulang dan ditulis ulang menggunakan Markdown.</li><li>Kotak pencarian baru.</li><li>Build tools baru menggunakan npm.</li><li>dan masih banyak lagi…</li></ul><p><em>(sumber: <a href="https://www.codepolitan.com/bootstrap-4-beta-resmi-dirilis-598e9df6678ce" target="_blank">Codepolitan</a>)</em></p><p>Kendala saya saat mencoba:</p><p>Belum hapal nama-nama class di Bootstrap 4, kadang ada yang baru dan ada juga yang masih
dipertahankan.</p>

Solusinya, sering-sering baca dokumentasi dan coba-coba.
<h3>Instalasi Bootstrap 4 ke Proyek</h3>
Instalasi yang saya maksudkan adalah menambahkan Bootstrap pada proyek web kita.</p><p>Ada beberapa cara yang bisa dilakukan, ada yang tradisional dan ada yang modern.</p><p><strong>Cara tradisional</strong>:</p><ol><li>Download Bootstrap;</li><li>Ekstrak;</li><li>Copas ke direktori proyek.</li></ol><p><strong>Cara modern menggunakan <em>tools depedency management</em></strong>:</p><p>Menggunakan npm:</p><div class="highlight"><pre style="color:#f8f8f2;background-color:#282a36;-moz-tab-size:4;-o-tab-size:4;tab-size:4"><code class="language-bash" data-lang="bash">npm install bootstrap@4.0.0-beta
</code></pre></div><p>Menggunakan gem:</p><div class="highlight"><pre style="color:#f8f8f2;background-color:#282a36;-moz-tab-size:4;-o-tab-size:4;tab-size:4"><code class="language-bash" data-lang="bash">gem install bootstrap -v 4.0.0.alpha6
</code></pre></div><p>Menggunakan bower:</p><div class="highlight"><pre style="color:#f8f8f2;background-color:#282a36;-moz-tab-size:4;-o-tab-size:4;tab-size:4"><code class="language-bash" data-lang="bash">bower install bootstrap#v4.0.0-beta
</code></pre></div><p>Menggunakan Composer:</p><div class="highlight"><pre style="color:#f8f8f2;background-color:#282a36;-moz-tab-size:4;-o-tab-size:4;tab-size:4"><code class="language-bash" data-lang="bash">composer require twbs/bootstrap:4.0.0-beta
</code></pre></div><p>Menggunakan NuGet:</p><div class="highlight"><pre style="color:#f8f8f2;background-color:#282a36;-moz-tab-size:4;-o-tab-size:4;tab-size:4"><code class="language-bash" data-lang="bash">Install-Package bootstrap -Pre
</code></pre></div><p><strong>Menggunakan CDN</strong>:</p><p>Buat kamu yang ingin menggunakan Bootstrap pada Blogger atau pada website
tanpa hosting, bisa menggunakan link CDN.</p>