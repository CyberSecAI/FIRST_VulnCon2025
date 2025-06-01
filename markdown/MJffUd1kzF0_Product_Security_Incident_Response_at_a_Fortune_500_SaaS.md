# Product Security Incident Response at a Fortune 500 SaaS

**Video URL:** [https://www.youtube.com/watch?v=MJffUd1kzF0](https://www.youtube.com/watch?v=MJffUd1kzF0)
**Video ID:** MJffUd1kzF0

---

SUMMARY
Garrett membahas tantangan dan peluang unik yang dihadapi tim tanggap darurat produk (PERT) di perusahaan perangkat lunak sebagai layanan (SaaS).

IDEAS
* Penyerang dapat dengan mudah menemukan dan mengakses infrastruktur yang dihosting untuk pelanggan.
* Peneliti dapat dengan cepat menemukan kerentanan web dasar dalam perangkat lunak SaaS.
* Taruhannya lebih tinggi untuk kerentanan SaaS karena vektor serangan yang umum.
* Persyaratan masuk dan keluar pelanggan dapat membatasi opsi mitigasi.
* Pelanggan mungkin terkejut mengetahui bahwa vendor tidak memiliki visibilitas ke dalam data mereka.
* Menempatkan firewall web di depan layanan SaaS dapat merusak beberapa pelanggan.
* Waktu aktif pelanggan sangat bervariasi, sehingga sulit untuk menyeimbangkan keamanan dan ketersediaan.
* Pembatasan laju dapat memengaruhi pekerjaan otomatis pelanggan dan penyedia hosting.
* Pengungkapan kerentanan SaaS dapat dianggap noise jika pelanggan tidak perlu mengambil tindakan.
* Pelanggan mungkin menunggu alat manajemen mereka untuk menandai masalah sebelum menambal.
* Embargo kompleks dan berpotensi tidak mungkin dilakukan dengan ribuan pelanggan.
* Perubahan yang melanggar dapat memengaruhi vendor, aplikasi, dan kode khusus pelanggan.
* Vendor mungkin perlu memperbaiki file yang dimiliki dan dimodifikasi pelanggan.
* Vendor SaaS mungkin perlu menengahi perselisihan penyalahgunaan antara pelanggan dan penyedia internet.
* Vendor mungkin perlu menawarkan opsi yang kurang aman untuk mengakomodasi kasus penggunaan bisnis.
* Merek vendor masih terpengaruh meskipun pelanggan salah mengonfigurasi perangkat lunak.
* Kegagalan komunikasi dapat terjadi karena informasi kontak yang kedaluwarsa atau kurangnya kontak cadangan.
* Tim keamanan dan pemeliharaan pelanggan mungkin tidak selaras mengenai penambalan.
* Mitra implementasi mungkin tidak memperhatikan saran keamanan vendor.
* Aktor jahat atau kode yang ditulis dengan buruk dapat menyalahgunakan fitur SaaS yang canggih.
* Penyedia yang dihosting bertanggung jawab atas produk mereka dan infrastruktur pendukungnya.
* Perusahaan yang dihosting mungkin masih perlu menangani kerentanan dalam perangkat lunak di tempat.
* Memblokir kemampuan pelanggan untuk kembali ke versi yang rentan adalah keputusan yang sulit.
* Pelanggan mungkin memerlukan waktu pengujian yang signifikan sebelum menerapkan tambalan.
* Vendor mungkin perlu memaksakan perubahan pada instans pelanggan dalam kasus yang mendesak.
* Melakukan hal di atas dapat menciptakan preseden negatif di mana pelanggan mengharapkan vendor untuk selalu menambal untuk mereka.
* Memperbaiki kerentanan dapat berdampak negatif pada ketersediaan dan menyebabkan kredit pelanggan.

INSIGHTS
* Keamanan SaaS menghadirkan tantangan unik karena aksesibilitas, taruhan yang lebih tinggi, dan persyaratan pelanggan.
* Vendor SaaS harus menyeimbangkan keamanan, ketersediaan, dan kebutuhan untuk menghindari gangguan pelanggan.
* Pengungkapan kerentanan SaaS memerlukan pertimbangan yang cermat tentang tindakan pelanggan dan potensi noise.
* Perubahan yang melanggar dapat memiliki konsekuensi yang luas di seluruh ekosistem SaaS.
* Vendor SaaS harus secara proaktif mengatasi kegagalan komunikasi dan memastikan penyelarasan antara tim.
* Penyalahgunaan fitur dan sumber daya merupakan perhatian utama bagi penyedia yang dihosting.
* Vendor SaaS bertanggung jawab atas seluruh tumpukan perangkat lunak, termasuk infrastruktur pendukung.
* Memblokir rollback ke versi yang rentan dan memaksakan pembaruan memerlukan pertimbangan yang cermat.
* Vendor SaaS harus mempertimbangkan potensi preseden negatif dan dampak pada ketersediaan saat memperbaiki kerentanan.
* Tim PERT di lingkungan SaaS memiliki peran yang diperluas dan memerlukan keahlian yang beragam.

QUOTES
* "Taruhannya lebih tinggi karena dengan CVSS, setiap kali saya menjalankan kalkulator untuk membicarakan kerentanan atau masalah dengan vektor serangan CP, secara konsisten adalah jaringan, yang merupakan yang tertinggi untuk input itu." - Garrett
* "Anda mungkin mengatakan, 'Hei, berikan beberapa batasan laju padanya.' Tetapi Anda akan terkejut, seperti 90-95% pelanggan Anda mungkin hanya mengakses perangkat lunak Anda seolah-olah mereka adalah manusia." - Garrett
* "Dalam opini publik, ketika pelanggan itu dilanggar, merek Andalah yang muncul di berita, sayangnya." - Garrett
* "Jadi, Anda mendapatkan tanggung jawab untuk menjadi wasit antara apa yang dilakukan perangkat lunak pelanggan dan mungkin terlalu sering membayar beberapa layanan internet eksternal." - Garrett
* "Jadi, Anda tidak bisa begitu saja duduk dan berkata, 'Hei, kami akan memperbaiki masalah ini. Tidak ada yang akan pernah tahu bahwa itu adalah masalah.'" - Garrett
* "Anda mungkin dapat mencoba menilai berapa banyak perangkat lunak di sisi pelanggan yang Anda yakin dapat Anda perbaiki sendiri." - Garrett
* "Anda mungkin seperti, 'Baiklah, ini layak untuk dipercepat seberapa cepat kami memperbaiki ini jauh sebelum SLA teknik normal Anda.'" - Garrett
* "Jadi, jika Anda seperti, 'Hei, kami memperbaiki masalah kritis dalam 15 hari,' tetapi saya melihat apa yang tampak seperti banyak aktivitas pemindaian." - Garrett
* "Jadi, pasti pikirkan itu sedikit." - Garrett

HABITS
* Mempelajari tren cloud dan keamanan.
* Mencari pengalaman di berbagai perusahaan teknologi.
* Mengembangkan keahlian dalam pengembangan aplikasi web dan penelitian keamanan.
* Berpartisipasi dalam program hadiah dan inisiatif yang bertanggung jawab.
* Mengejar pendidikan berkelanjutan, seperti gelar MBA.
* Terlibat dalam kegiatan pencarian dan penyelamatan.
* Menganalisis model tanggung jawab bersama.
* Meninjau dan merevisi kebijakan CV.
* Meneliti praktik perusahaan teknologi besar lainnya.
* Memprediksi CVE mana yang akan menyebabkan pertanyaan pelanggan.
* Berpartisipasi dalam SIG PERT dan membantu membentuk kerangka kerja di sekitar keamanan SaaS.

FACTS
* Perusahaan SaaS menghadapi tantangan dan peluang unik dalam tanggap darurat produk.
* Infrastruktur yang dihosting untuk pelanggan SaaS dapat dengan mudah ditemukan dan diakses oleh penyerang.
* Peneliti dapat dengan cepat menemukan kerentanan web dasar dalam perangkat lunak SaaS.
* Kerentanan SaaS sering kali memiliki vektor serangan CP, yang mengarah pada skor keparahan yang lebih tinggi.
* Vendor SaaS mungkin tidak memiliki visibilitas ke dalam data pelanggan karena masalah kewajiban.
* Menempatkan firewall web di depan layanan SaaS dapat merusak fungsionalitas untuk beberapa pelanggan.
* Pelanggan SaaS memiliki waktu aktif yang sangat bervariasi, sehingga sulit untuk menyeimbangkan keamanan dan ketersediaan.
* Pembatasan laju dapat memengaruhi pekerjaan otomatis pelanggan dan penyedia hosting.
* Beberapa pelanggan mungkin menunggu alat manajemen mereka untuk menandai kerentanan sebelum menambal.
* Embargo kompleks dan berpotensi tidak mungkin dilakukan dengan ribuan pelanggan SaaS.
* Aktor jahat atau kode yang ditulis dengan buruk dapat menyalahgunakan fitur SaaS yang canggih.
* Penyedia yang dihosting bertanggung jawab atas produk mereka dan infrastruktur pendukungnya.
* Perusahaan yang dihosting mungkin masih perlu menangani kerentanan dalam perangkat lunak di tempat.

REFERENCES
* Fortune 500
* ServiceNow
* PERT
* CNA
* first.org
* Octa
* Invincia
* G contractors
* CVSS
* Shared responsibility model
* Web Application Firewalls
* Rate limiting
* CDE
* CVE
* Embargo
* Honeypots
* Demo environments
* Remediation SLAs
* Tomcat vulnerability
* MoveIt vulnerability
* PERT sig
* Services framework

ONE-SENTENCE TAKEAWAY
Pahami tantangan dan peluang unik dari keamanan SaaS untuk membangun dan memelihara program PERT yang efektif.

RECOMMENDATIONS
* Prioritaskan perbaikan berdasarkan potensi dampak dan aktivitas pemindaian yang diamati.
* Pertimbangkan dengan cermat implikasi dari pengungkapan kerentanan dan potensi noise.
* Berkomunikasi secara proaktif dengan pelanggan tentang masalah keamanan dan mitigasi.
* Berkolaborasi dengan tim pemeliharaan dan keamanan pelanggan untuk memastikan penyelarasan.
* Didik mitra implementasi tentang praktik keamanan terbaik dan saran vendor.
* Terapkan mekanisme untuk mencegah penyalahgunaan fitur dan sumber daya SaaS.
* Pertahankan keahlian di seluruh tumpukan perangkat lunak, termasuk infrastruktur pendukung.
* Tetapkan kebijakan yang jelas untuk memblokir rollback dan memaksakan pembaruan.
* Pertimbangkan potensi preseden negatif dan dampak pada ketersediaan saat memperbaiki kerentanan.
* Berpartisipasilah dalam komunitas keamanan dan berkontribusi pada kerangka kerja seperti kerangka kerja layanan PERT.
