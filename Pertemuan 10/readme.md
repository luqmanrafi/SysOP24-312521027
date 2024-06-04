# Serial Queue
* Antrean pengiriman serial hanya melakukan satu tugas dalam satu waktu, sehingga berguna untuk menyinkronkan akses ke nilai atau sumber daya tertentu guna mencegah data race.\
![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/e56587c3-443f-47e0-aa17-415b16c902c1)

# Concurrent Queue
* memungkinkan banyak tugas dijalankan secara bersamaan. Meskipun tugas dimulai sesuai urutan penambahannya, tugas tersebut dapat diselesaikan dalam urutan berbeda, dijalankan pada thread berbeda yang dikelola oleh antrean pengiriman. Jumlah tugas yang berjalan secara bersamaan bergantung pada kondisi sistem.
![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/e6131f60-a256-4c03-9f6b-6a1da9ae7e90)
