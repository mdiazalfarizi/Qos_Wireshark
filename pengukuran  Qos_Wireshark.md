![3](https://github.com/mdiazalfarizi/Qos_Wireshark/assets/126410884/605056c4-6a9d-4fc3-9c03-c3b882492857)1. mencoban menjalankan data wireshark dengan wifi
   ![1](https://github.com/mdiazalfarizi/Qos_Wireshark/assets/126410884/52bb8a9a-537f-4749-a004-a8efea4a751e)

2. stelah membukan wifi buka aplikasi yg akan di jalan kan selama 10 menit untuk mendapatkan data, setelah semua di lakukan stop data tersebut
   ![2](https://github.com/mdiazalfarizi/Qos_Wireshark/assets/126410884/6a6dcdce-63ea-4123-b987-8557914a0a27)

3. THROUGHPUT
   selanjutnya kita akan menghitung throughput
   ![3](https://github.com/mdiazalfarizi/Qos_Wireshark/assets/126410884/3b61c939-8cd4-4bd1-84c2-fe7f9b75ed71)
   analisi:
   jumlah bytes : time span= 81000183 bytes : 690.521 s
                           = 117302 bytes/s
                           = 117302 kb/s
                           = 117.302 x 8
                           = 938 kb/s

4. PACKET LOSS
   selanjutnya menghitung packet loss
   ![4](https://github.com/mdiazalfarizi/Qos_Wireshark/assets/126410884/a278578b-b653-427e-921c-6f0069d66265)
   analisis:
   paket diterima= paket dikirim - paket diterima
                 = 83766 - 959
                 = 82807
   paket loss= (((paket dikirim - paket diterima)/paket dikirim) x 100)
             = (((83766 - 82807)/83766)x100)
             = 114.5758661887694

5. DELAY
   

















   

