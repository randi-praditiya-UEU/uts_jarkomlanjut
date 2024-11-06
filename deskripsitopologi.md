Berikut adalah deskripsi dari topologi jaringan pada gambar:

Router R1 KJ 

Terhubung ke sebuah komputer dengan IP 192.168.1.1/24 melalui interface Eth2.
Memiliki dua koneksi tambahan:
Eth4 ke Router R2 CR dengan IP 20.20.20.2.
Eth3 ke Router R3 KHI dengan IP 10.10.10.1.

Router R2 CR

Terhubung ke sebuah komputer dengan IP 192.168.2.1/24 melalui Eth2.
Memiliki dua koneksi ke router lain:
Eth3 dengan IP 20.20.20.1 yang terhubung ke Router R1 KJ.
Eth4 dengan IP 30.30.30.2 yang terhubung ke Router R3 KHI.

Router R3 KHI 

Terhubung ke sebuah komputer dengan IP 192.168.3.1/24 melalui Eth2.
Memiliki dua koneksi ke router lain:
Eth3 dengan IP 10.10.10.2 yang terhubung ke Router R1 KJ.
Eth4 dengan IP 30.30.30.1 yang terhubung ke Router R2 CR.