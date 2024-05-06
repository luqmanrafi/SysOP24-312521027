## Tugas 3
### SIKLUS CPU

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

