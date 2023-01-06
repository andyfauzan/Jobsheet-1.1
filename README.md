# ESP32_WirelessSensorNet

ESP-NOW adalah protokol yang dikembangkan oleh Espressif, yang memungkinkan banyak perangkat untuk berkomunikasi satu sama lain tanpa menggunakan Wi-Fi. Protokol ini mirip dengan konektivitas nirkabel 2.4GHz berdaya rendah. Pendifinisian alamat (MAC Address) pada masing-masing ESP32 diperlukan pada awal konfigurasi. Setelah konfigurasi alamat selesai dilakukan, jaringan peer-to-peer akan terbentuk dan perangkat tidak perlu melakukan handshaking kembali ketika akan berkomunikasi. Hal ini memunjukkan bahwa setelah perangkat ESP32 saling terpasang satu sama lain, koneksi akan tetap ada. Dengan kata lain, jika tiba-tiba salah satu ESP32 kehilangan daya atau diatur ulang, ketika restart, secara otomatis akan terhubung ke pasangan ESP32 yang telah terdefinisi alamatnya untuk melanjutkan komunikasi.<br />
ESP-NOW mempunyai fitur sebagai berikut.<br />
a) Komunikasi unicast yang terenkripsi maupun tidak terenkripsi. <br />
b) Perpaduan komunikasi data yang terenkripsi maupun yang tidak terenkripsi pada perangkat yang berada pada topologi peer-to-peer. <br />
c) Payload (ukuran) data yang dapat dikirm mencapai 250 byte.<br />
d) Terdapat fungsi callback yang dapat menginformasikan data berhasil terkirim maupun gagal dikirim.<br />
Selain itu, ESP-NOW mempunyai batasan sebagai berikut.<br />
a) Jumlah maksimal perangkat yang dapat berkomunikasi dalam mode station dengan data terenkripsi adalah 10 unit (6 dalam mode SoftAP atau SoftAP+Station). <br />
b) Untuk komunikasi tidak terenkripsi, jumlah maksimal perangkat adalah 20 unit, termasuk dengan yang terenkripsi. <br />
ESP-NOW mempunyai 2 tipe jaringan, yaitu One-Way Communication dan Two-Way Communication. One-Way Communication terbagi menjadi Point-to-Point, One-to-Many Communication dan Many-to-One Communication. Sementara Two-Way Communication terbagi menjadi Point-to-Point dan Mesh Communication.

**ALAT DAN BAHAN**
1) ESP32
2) Breadboard
3) Kabel jumper
4) Resistor 10K Ohm

**HASIL**

1) Praktikum 2-A

https://user-images.githubusercontent.com/122078276/210953786-bb436bea-6d0f-49df-b769-a03f4a497f61.mp4

2) Praktikum 2-B-sender

https://user-images.githubusercontent.com/122078276/210953918-d99380d9-0e49-406f-ab66-1c4119ce0563.mp4

3) Praktikum 2-C-sender-Poin A mati 1 atas

https://user-images.githubusercontent.com/122078276/210953995-4d6cda6d-5e98-48cb-a427-3b15d2eefd71.mp4

4) Praktikum-2-C-Sender-poin a mati 1 tambah 1 yang disuruh nambah sekelas

https://user-images.githubusercontent.com/122078276/210954051-02d777f3-c65f-47d0-88b2-368f42c1b08e.mp4

5) Praktikum-2-C-Sender-poin a success semua

https://user-images.githubusercontent.com/122078276/210954304-76564d5f-f488-4ba7-8985-c487deef02f7.mp4

6) Praktikum-2-C-Sender-poin b

https://user-images.githubusercontent.com/122078276/210954318-94034006-a889-4698-8e7b-9e97d11b7c12.mp4

7) Praktikum-2-D-Sender

https://user-images.githubusercontent.com/122078276/210955149-5c3c6d2f-974b-4af4-9abc-6057eb1af040.mp4

8) praktikum-2-E-1

https://user-images.githubusercontent.com/122078276/210955266-ca095106-22d2-44ee-9927-374d8292613b.mp4

9) praktikum-2-E-2

https://user-images.githubusercontent.com/122078276/210955349-de843483-94cd-4fb3-a10e-edb4b86e2cd6.mp4










