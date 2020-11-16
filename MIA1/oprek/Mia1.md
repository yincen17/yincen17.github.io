# PANDUAN ROOTING , UBL DAN PASANG TWRP MIA1 (TISSOT)

### Simak step by step dibawah!

> 
>

## **I.Cara Membuka Bootloader (Unlock Bootloader)**



1. Download Minimal Adb & Fastboot tools / Platfrom Tools (Cukup pilih satu saja!)

   Setelah didownload  Ekstrak file tersebut lalu buka CMD/Powershell/Terminal

   | TOOLS                        |       DOWNLOAD LINK        |
   | :--------------------------- | :------------------------: |
   | Minimal Adb & Platfrom Tools | [Download](www.google.com) |
   | Platfrom Tools Windows       | [Download](www.google.com) |
   | Platfrom Tools Linux         | [Download](www.google.com) |

2. Buka ‘Developer options’ 

   Buka Settings >  About Phone > pencet Build number 5x) di Mi A1 anda dan aktifkan ‘USB  debugging’, ‘OEM Unlock’.

   

3. Sambungkan hp anda ke pc!

4. Pada CMD/Powershell/Terminal Massukan Perintah dibawah!

   ```
   adb devices
   ```

   lalu pada hp sobat akan muncul prompt deblugging , centang dan izinkan

5. Masuk ke Fastboot Mode ada 2 cara yaitu:

   Melalui Perintah Adb

   ```
   adb reboot bootloader
   ```

   Atau

   Jika Menggunakan Tombol tekan dan tahan secara bersamaan  tombol power dan volume -  sampai muncul logo MI

6. Jika hp anda sudah masuk ke mode fastboot / bootloadermasukan perintah dibawah!

   ```
   fastboot oem unlock
   ```

   hp anda akan restart otomatis jika hp anda tidak restart otomatis masukkan perintah berikut

   ```
   fastboot reboot
   ```


7. Selamat hp anda telah berhasil di buka bootloadernya



## II. Cara Ngeroot / Rooting



|           BAHAN            |       DOWNLOAD LINK        |
| :------------------------: | :------------------------: |
| Cosmic Dan's Bootonly Twrp | [Download](www.google.com) |
|   Magisk Installer 20.4    | [Download](www.google.com) |

2. Download bahan diatas , lalu ekstrak  file Twrp bootonly dan pindahkan file hasil ekstrak ke dalam folder minimal adb / platfrom tools , pindahkan file magisk installer 20.4 ke sdcard / internal hp sobat

3. Masuk ke Fastboot Mode ada 2 cara yaitu:

   Melalui Perintah Adb (Hubungkan hp anda ke pc , pastikan usb deblugging telah di izinkan)

   ```
   adb reboot bootloader
   ```

​		Jika Menggunakan Tombol tekan dan tahan secara bersamaan  tombol power dan volume -  sampai 		muncul logo MI lalu lepaskan

4. jika hp sudah berada di mode fastboot / bootloader masukan perintah dibawah

   ```
   fastboot boot recovery.img
   ```

   hp anda akan masuk ke twrp yang di hotboot

5. Pada twrp  flash file  magisk installer 20.4

6. Setelah Proses flashing  magisk selesai reboot system

7. selamat hp sobat telah rooted

   

## III.Cara Pasang Twrp Recovery



|            BAHAN            |       DOWNLOAD LINK        |
| :-------------------------: | :------------------------: |
| Cosmic Dan's Bootonly Twrp  | [Download](www.google.com) |
| Cosmic Dan's Twrp installer | [Download](www.google.com) |
|    Magisk Installer 20.4    | [Download](www.google.com) |


1. Download bahan diatas ekstrak  file Twrp bootonly dan pindahkan file hasil ekstrak ke dalam folder minimal adb / platfrom tools , pindahkan file magisk installer 20.4 dan cosmic twrp installer  ke sdcard / internal hp sobat

2. Masuk ke Fastboot Mode ada 2 cara yaitu:

   Melalui Perintah Adb (Hubungkan hp anda ke pc , pastikan usb deblugging telah di izinkan)

   ```
   adb reboot bootloader
   ```

   Jika Menggunakan Tombol tekan dan tahan secara bersamaan  tombol power dan volume -  sampai muncul logo MI lalu lepaskan

   

4. jika hp sudah berada di mode fastboot / bootloader masukan perintah dibawah

   ```
   fastboot boot recovery.img
   ```

   Hp anda akan otomatis masuk ke twrp yang di hotboot

11. Pada twrp  flash file  twrp installer 

12. Lalu flash magisk installer

13. Setelah Proses flashing   selesai reboot system

14. Selamat hp sobat telah rooted dan terpasang twrp




## Semoga Sukses

