# Materi Penjangkauan Tor 2019-2020

# 1. TOR UNTUK PRiVASI

### Privasi adalah hak asasi manusia

Seperti kebanyakan kita, Aleisha menghabiskan sebagian besar waktunya berhubungan secara daring dengan teman-teman, berbagi di media sosial, dan menjelajahi web.

Namun akhir-akhir ini, ia memperhatikan bahwa iklan-iklan yang terkait pencarian yang ia lakukan sebelumnya mengikutinya dalam jaringan.

Ini terasa sangat invasif sampai ia melakukan beberapa riset pada iklan daring dan mempelajari bahwa bukan hanya para pengiklan yang melacaknya namun juga PJI (Penyedia Jasa Internet), perusahaan analitik, platform media sosial, dan sebagainya.

Aleisha memutuskan ia ingin mencari dan menggunakan perangkat lunak yang tidak mengumpulkan datanya, tidak melacaknya, dan tidak memberitahukan layanan lain tentang segala hal yang privat tentangnya.

Ia pergi ke sebuah pelatihan privasi di sebuah ruangretas (hackerspace) lokal dan belajar tentang **Tor Browser**, satu-satunya peramban web yang memungkinkannya untuk meramban secara anonim.

---

# 2.TOR UNTUK FEMINIS

### Masa depan adalah feminis siber

Fernanda menjalankan sebuah kolektif perempuan yang fokus pada hak-hak reproduksi di Brazil, di mana aborsi adalah ilegal.

Fernanda dan koleganya membangun sebuah situs web yang memberikan informasi mengenai akses terhadap aborsi, alat kontrasepsi dan sumber-sumber lainnya untuk orang yang sedang mencari informasi tentang reproduksi.

Bila situs web ini terhubung kembali ke mereka, mereka bisa ditahan--atau lebih buruk lagi.

Untuk melindungi diri mereka, Fernanda dan koleganya membuat situs web tersebut menggunakan **layanan onion** Tor. Layanan onion tidak hanya melindungi dari terungkapnya mereka sebagai operator dari peladen situs web tersebut tapi juga membantu melindungi pengunjung situs web mereka dengan mensyaratkan penggunaan Tor Browser.

Faktanya, Fernanda menggunakan **Tor Browser** untuk segala aktivitas penjelajahan webnya untuk berada di sisi yang aman.

Dia juga menggunakan aplikasi yang menggunakan jaringan Tor yang disebut **OnionShare** untuk mengirimkan berkas kepada aktifis lainnya secara aman dan privat.

### Aktivis hak reproduksi seperti Fernanda berjuang untuk kebebasan dasar, dan Tor membantu menggerakan perlawanan mereka.

---

# 3. TOR UNTUK HAK ASASI MANUSIA

### Air adalah kehidupan

Jelani tinggal di sebuah desa kecil yang dilewati sungai besar.

Sungai ini telah menyediakan air untuk komunitasnya sejak zaman nenek moyangnya.

Namun hari ini, sungai Jelani terancam oleh perusahaan multinasional kuat yang melakukan pengeboran minyak di wilayah tersebut.

Firma keamanan privat yang dibayar oleh perusahaan ini, menggunakan mekanisme pengawasan yang kuat untuk memantau aktivitas daring Jelani dan tetangganya di desa yang melakukan pengorganisiran untuk melindungi sungai sakral mereka.

Jelani menggunakan **Tor Browser** untuk mencegah perusahaan ini mengamati dia saat mengunjungi situs web untuk perlindungan hak asasi internasional dan bantuan hukum dan menulis blog tentang gerakan perlawanan di desanya.

Dia juga menggunakan **OnionShare** dan **SecureDrop** untuk mengirimkan dokument secara aman kepada jurnalis-jurnalis yang membantu mengekspos pelanggaran hak asasi manusia ini.

Semua perangkat lunak ini menggunakan Tor untuk membantu melindungi privasi Jelani.

### Aktivis hak asasi manusia seperti Jelani berjuang untuk keadilan di komunitas mereka, dan Tor membantu menggerakan perlawanan mereka.

---

# 4. TOR UNTUK ANTI SENSOR

### Bangun jembatan bukan tembok

Jean bepergian untuk pertama kalinya ke sebuah negara yang jauh dari keluarganya.

Setelah tiba di hotel, dia membuka laptopnya.

Dia sangat lelah saat pesan "Koneksi habis" pertama kali muncul pada peramban webnya, dia pikir itu berasal dari kesalahannya sendiri.

Namun saat mencoba lagi dan lagi, dia menyadari bahwa penyedia surel, situs web berita, dan banyak aplikasi yang tidak tersedia.

Dia telah mendengar bahwa negara ini menyensor internet dan bertanya-tanya apakah itu yang terjadi.
Bagaimana dia dapat menghubungi keluarganya dari balik tembok yang tidak bisa ditembus?
Setelah dia melakukan beberapa kali pencarian web, dia menemukan sebuah forum dan membaca tentang VPN, layanan privat yang memungkinkan Anda untuk terhubung ke sebuah jaringan lain tanpa sensor.

Jean menghabiskan waktu setengah jam mencoba untuk mencari tahu manakah VPN murah yang terbaik.

Dia memilih satu dan tampak bekerja untuk sesaat, namun setelah lima menit sambungannya putus dan VPN tersebut tidak mau terhubung lagi.

Jean terus membaca untuk mencari opsi lain dan mempelajari tentang Tor Browser dan bagaimana itu bisa mengelakkan sensor.

Dia menemukan situs bayangan resmi untuk mengunduh progamnya.

Saat dia membuka **Tor Browser**, dia mengikuti anjuran untuk pengguna yang disensor dan terhubung ke sebuah bridge yang memungkinkan dia mengakses internet lagi.

Dengan Tor Browser, Jean dapat meramban secara bebas dan privat dan menghubungi keluarganya.

### Pengguna yang disensor di seluruh dunia mengandalkan Tor Browser untuk cara yang bebas, stabil, dan tanpa sensor dalam mengakses internet.

---

# 5. Bagian Bersama

## Apa itu Tor?

Tor adalah perangkat lunak gratis dan sebuah jaringan terbuka yang membantu melindungi Anda dari pelacakan, pengawasan, dan penyensoran daring.
Tor dibuat secara gratis oleh sebuah organisasi nirlaba 501(c)3 berbasis di Amerika Serikat bernama Tor Project.

Cara paling mudah menggunakan Tor adalah Tor Browser.
Saat Anda menggunakan Tor Browser, tidak ada seorangpun yang dapat melihat situs web apa yang Anda kunjungi atau dari mana Anda berasal.

Other applications, like SecureDrop and OnionShare, use Tor to protect their users against surveillance and censorship.


## 6. How does Tor work?

Amal wants to visit Bekele’s website privately, so she opens Tor Browser.

Tor Browser selects a random circuit of three relays, which are computers all over the world configured to route traffic over the Tor network.

Tor Browser then encrypts her website request three times and sends it to the first Tor relay in her circuit.

The first relay removes the first encryption layer but doesn't learn that the destination is Bekele’s website.

The first relay learns only the next location in the circuit, which is the second relay.

The second relay removes another encryption layer and forwards the web page request to the third relay.

The third relay removes the last encryption layer and forwards the web page request to its destination, Bekele’s website, but it doesn't know the request comes from Amal.

Bekele doesn't know that the website request came from Amal unless she tells him so.

## 7. Who uses Tor? 

People all over the world use Tor to protect their privacy and access the web freely.

Tor helps protect journalists, human rights defenders, domestic violence victims, academic researchers, and anyone experiencing tracking, censorship, or surveillance. 

## 6. Why trust Tor?

Tor is designed for privacy. We don’t know who our users are, and we don't keep logs of user activity.

Tor relay operators cannot reveal the true identity of Tor users.

Continual peer review of Tor's source code by academic and open source communities ensures that there are no backdoors in Tor, and our social contract promises that we will never backdoor Tor. 

## 7. Join the Tor community

Tor is made possible by a diverse set of users, developers, relay operators, and advocates from around the world.

We need your help to make Tor more usable and secure for people everywhere.

You can volunteer with Tor by writing code, running a relay, creating documentation, offering user support, or telling people in your community about Tor.

The Tor community is governed by a code of conduct, and we outline our set of promises to the community in our social contract. 

Learn more about Tor by visiting our website, our wiki, finding us on IRC, joining one of our mailing lists, or signing up for Tor News at newsletter.torproject.org.


## 8. Download Tor

Tor for Desktop
torproject.org/download

TOR ON MOBILE
### Android 
Tor Browser for Android is available from GooglePlay.

### iOS
Onion Browser, developed by M. Tigas, is the only browser we recommend for iOS.

