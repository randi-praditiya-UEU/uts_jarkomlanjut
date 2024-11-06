## RANDI PRADITIYA
## 20210801265
## TEKNIK INFORMATIKA
## UTS JARKOM

# Analisis Jaringan
### Topologi dan Koneksi:

-Terdiri dari tiga router (R1 KJ, R2 CR, R3 KHI) yang dihubungkan menggunakan IPIP Tunnel melalui jaringan publik 192.168.10.0/24. Setiap router memiliki segmen jaringan lokal dengan subnet 192.168.X.0/24.

### Segmentasi dengan VLAN:

- Setiap segmen lokal memiliki VLAN pada switch untuk memastikan segmentasi dan manajemen lalu lintas yang lebih aman dan terstruktur.

### Routing Statis:

- Setiap router menggunakan routing statis, yang cocok untuk jaringan kecil tetapi kurang fleksibel jika ada perubahan konfigurasi.

### Keamanan:

-IPIP Tunnel tanpa enkripsi membuat jaringan rentan. Dianjurkan untuk menggunakan IPsec untuk melindungi lalu lintas antar-router.

### Kesimpulan
- Efisien untuk Lingkungan Pendidikan: Topologi ini cocok untuk lab atau jaringan pendidikan skala kecil dengan segmentasi yang baik melalui VLAN.
- Keamanan Perlu Ditingkatkan: Penambahan enkripsi (IPsec) direkomendasikan jika jaringan terhubung ke internet publik.
- Keterbatasan Routing Statis: Routing statis mudah dikelola tetapi tidak fleksibel untuk pengembangan jaringan yang lebih besar.