* Penjadwalan preemptive digunakan ketika suatu proses beralih dari status berjalan ke status siap atau dari status menunggu ke status siap. Sumber daya (terutama siklus CPU) dialokasikan ke proses untuk jangka waktu terbatas dan kemudian diambil, dan proses ditempatkan kembali dalam antrian siap jika proses tersebut masih memiliki sisa waktu ledakan CPU.
  ![alt text](assets/preemptive.png)
* Penjadwalan Non-preemptive digunakan ketika suatu proses dihentikan, atau suatu proses beralih dari keadaan berjalan ke keadaan menunggu. Dalam penjadwalan ini, setelah sumber daya (siklus CPU) dialokasikan ke suatu proses, proses tersebut akan menahan CPU hingga dihentikan atau mencapai status menunggu.
  
![alt text](assets/nonpre.png)
