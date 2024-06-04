# Siklus CPU
![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/3be325de-ff61-4ff8-a694-4a2906fa28e1)

PROGRAM COUNTER 0
- FETCH
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/a1d73f8d-f067-4456-b056-d5b6b50f1bf9)

- DECODE
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/fb129fec-f2b6-4a0e-9d1c-1f29a0ff1bf4)

- EXECUTE
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/0b979003-c876-4877-9921-75e3c0e367da)

PROGRAM COUNTER 1
- FETCH (Menjalankan perintah selanjutnya dari address,yaitu add 7)
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/4ec321d0-27ee-4945-bdef-6ca925276c22)

- DECODE
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/4abbba9d-000b-475e-a881-18d9344cba41)

- EXECUTE (Mengeksekusi address 1 yaitu add 7 yang dimasukkan ke accumulator. 1+1 = 2)
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/2e2aca22-869b-46bb-89b0-a78cc6fdbbcd)

PROGRAM COUNTER 2
- FETCH (Mengambil address 2 dengan instruksi Store 6)
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/d203e131-5e83-43fd-bfff-1b62d3f01ed6)

- DECODE
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/386ecccf-1b86-4690-a0bc-75b2d5b616ad)

- EXECUTE (Mengeksekusi instruksi Store 6, yaitu menyimpan di address 6)
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/e4160788-1fb4-428c-9102-4a332abc375e)

PROGRAM COUNTER 3
- FETCH (Mengeksekusi address 3,yaitu Jump ke address 1)
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/4537d27c-0b92-4e36-9dd6-472db839fc89)

- DECODE
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/416ef1cc-8048-4dee-8d2c-91bbae58e441)

- EXECUTE (kembali ke address 1. program akan terus berulang)
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/aadaa2ae-8934-4554-9a7d-72107e33f500)
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/e78209e3-b8e6-4b20-816a-f4d31eb215bc)

  # INSTALL DEBIAN
1. Pilih menu new, lalu beri nama Virtual machine
   ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/8c8528c5-ef81-4b5e-9c0e-a2db1159a6a5)

2. Pilih alokasi memori lalu next
   ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/4f6f10a4-7cb2-483e-9680-6b46bba4732e)
3. Alokasi virtual hard disk
   ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/e997e801-1ce9-43ef-94b5-10649eae0f8a)
4. Finish
   ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/5097019e-0f38-42f5-b811-f268711064b4)
5. Start debian, lalu pilih file iso debian
   ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/57fe5fb6-fb1a-4b3d-b27c-eb7b0f12af44)
6. Pilih install
   ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/3b40fba2-b83c-4583-870f-01c5b2613d72)
7. Pilih bahasa
   ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/a0bca4c8-5778-4bc3-b928-6a7e0abd3640)
8. Pilih lokasi
   ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/f6fef654-1fd4-4455-aa6c-8be5ad9017aa)
9. Pilih layout keyboard
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/462b19f4-a188-488a-965f-6b8c3d82fb23)
10. tunggu hingga proses selesai. lalu set nama host
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/c2309a87-8b5d-45a3-8e25-d45372ba9fa5)
11. atur domain
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/f32f6d57-c64b-4919-af2c-08de89e44ad0)
12. Mengatur password root
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/610dfb7e-583a-4a7a-8319-865e43a19547)
13. Mengatur nama lengkap
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/3b6d3d03-7982-4c88-b721-294fe69aa97e)
14. mengatur zona waktu
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/84b949f4-d029-444a-8457-ca0eb3d5b78e)
15. Mempartisi hard disk
  ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/2f00ff8e-8ea5-4d36-8420-df859afbeb87)
16. pilih semua berkas dalam satu partisi
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/31f68ecc-7037-4afc-be35-311e4fe522d0)
17. Tunggu proses selesai
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/e42ed1de-cb9d-4eb4-b6b7-236deb8f8ba7)
18. setelah itu, dapat mengatur pengelola paket
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/fc4676d2-3a59-4d98-8351-bf01d8a12b85)
19. Karena saya memilih tidak disemua proses, maka harus menunggu instalasi
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/3785b8cb-97f3-4b15-b8b0-b9d76729e233)
20. menyelesaikan instalasi
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/fd5a0a34-0714-4ec7-9546-4e5f052ad9e3)
21. debian berhasil terinstall
    ![image](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/ae8286a7-6fbe-4080-a5cb-0be9f6b26ffa)
    

# Set Up untuk Flops/iops
1. instalasi gcc

![WhatsApp Image 2024-03-18 at 22 56 51_f7aac175](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/d094d705-ac06-445f-8bb5-54015ca3e5fc)

2. instalasi git

![WhatsApp Image 2024-03-18 at 23 00 00_4fe2efc6](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/505bce0d-bdf4-4a48-9b21-ac408d19341a)

3. instalasi make

![WhatsApp Image 2024-03-18 at 23 11 26_759ef434](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/7cd3873e-fa87-47b9-aa7a-f6aec72c3864)


4. menjalankan ./iops64

![WhatsApp Image 2024-03-18 at 23 40 37_740c17e1](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/5ab63814-51c2-4589-9c4f-5c215be76b74)

![WhatsApp Image 2024-03-18 at 23 44 21_d6f78e31](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/e44ba26f-d54e-482f-bd96-e5a9ac3a5a42)

![WhatsApp Image 2024-03-18 at 23 45 56_745c5df4](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/7069de69-0b9b-49dc-8ec8-241e74b6fc1b)

![WhatsApp Image 2024-03-18 at 23 47 23_a0e69a40](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/43ba85ca-6542-4dd0-bcec-823d3210f69d)

![WhatsApp Image 2024-03-18 at 23 52 09_83b00ee5](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/1c46ab49-d15d-42d5-8421-0198b16b355f)



**5. menjalankan ./flops64**  

![WhatsApp Image 2024-03-18 at 23 53 46_f3dbb07a](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/45946d57-1ccf-4e74-8b65-c3ba06bea610)

![WhatsApp Image 2024-03-18 at 23 55 13_980f2c4b](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/27ed5f83-2ac7-4416-9dfe-55229c30db03)

![WhatsApp Image 2024-03-18 at 23 56 56_8a7572a7](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/d67adab7-8b2e-4c02-a327-517d10dc5fe0)

![WhatsApp Image 2024-03-18 at 23 58 23_10f68996](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/eb61d7f4-60b7-4474-926d-796fcfcc715d)

![WhatsApp Image 2024-03-19 at 00 00 00_608cfbf9](https://github.com/luqmanrafi/SysOP24-312521027/assets/70551637/75d85a0c-9271-4d9b-91a2-48a0e3567eaf)




  
