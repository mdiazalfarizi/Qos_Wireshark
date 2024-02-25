1. mencoban menjalankan data wireshark dengan wifi
   ![1](https://github.com/mdiazalfarizi/Qos_Wireshark/assets/126410884/78217b3a-ce2c-4130-ad25-2f52141ac4d8)

2. setelah membuka wifi buka aplikasi yang akan di jalankan selama 10 menit untuk mendapatkan data, setelah semua di lakukan stop aplikasi tersebut
   ![2](https://github.com/mdiazalfarizi/Qos_Wireshark/assets/126410884/acaf9dde-4f5c-42bd-a659-7bc218ea55ff)
   
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
   menghitung delay
   ![5](https://github.com/mdiazalfarizi/Qos_Wireshark/assets/126410884/50b26eec-e9e2-4cd4-b024-708247c824be)
   jadi didapatkan nilai dari data delay dan rata-rata delay sebagai berikut
   total delay= 1378.4232
   rata-rata delay= 0.0164558

6. JITTER
   ![6](https://github.com/mdiazalfarizi/Qos_Wireshark/assets/126410884/f40e4eae-2287-476e-81a6-14c38d3346b4)
   jadi, didapatkan hasil dari nilai jitter dan rata-sata jitter juga sebagai berikut:
   total jitter= 1381.5802
   rata-rata jitter= 0.0164935

   


   

















   

