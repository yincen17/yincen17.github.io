# PANDUAN ROOTING , UBL DAN PASANG TWRP MIA1 (TISSOT)

### Simak step by step dibawah!

> ⚠️ Penting!
>
> Harap Backup data anda terlebih dahulu ke penyimpanan lain karna melakukan unlock bootloader akan menyebaban seluruh data anda hilang

## **I.Cara Membuka Bootloader (Unlock Bootloader)**



1. Download Minimal Adb & Fastboot tools / Platfrom Tools (Cukup pilih satu saja!)

   Setelah didownload  Ekstrak file tersebut lalu buka CMD/Powershell/Terminal

   |                TOOLS                 |                        DOWNLOAD LINK                         |
   | :----------------------------------: | :----------------------------------------------------------: |
   |     Minimal Adb & Platfrom Tools     | [Download](https://forum.xda-developers.com/showthread.php?t=2588979&page=169) |
   | Platfrom Tools Windows / Linux / Mac | [Download](https://developer.android.com/studio/releases/platform-tools?hl=id) |
   
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



|                           BAHAN                           |                        DOWNLOAD LINK                         |
| :-------------------------------------------------------: | :----------------------------------------------------------: |
| TWRP-fastboot_boot_only-3.2.1-with-Tissot-Manager-2.5.zip | [Download](https://github.com/CosmicDan-Android/android_device_xiaomi_tissot/releases/download/2.5/TWRP-fastboot_boot_only-3.2.1-with-Tissot-Manager-2.5.zip) |
|                     Magisk-v20.4.zip                      | [Download](https://github.com/topjohnwu/Magisk/releases/download/v20.4/Magisk-v20.4.zip) |

1. Download bahan diatas , lalu ekstrak  file TWRP-fastboot_boot_only-3.2.1-with-Tissot-Manager-2.5.zip  dan pindahkan file hasil ekstrak ke dalam folder minimal adb / platfrom tools , pindahkan file Magisk-v20.4.zip ke sdcard / internal hp sobat

2. Masuk ke Fastboot Mode ada 2 cara yaitu:

   Melalui Perintah Adb (Hubungkan hp anda ke pc , pastikan usb deblugging telah di izinkan)

   ```
   adb reboot bootloader
   ```
   Jika Menggunakan Tombol tekan dan tahan secara bersamaan  tombol power dan volume -  sampai 		muncul logo MI lalu lepaskan

3. jika hp sudah berada di mode fastboot / bootloader masukan perintah dibawah
   ```
   fastboot boot recovery.img
   ```
   hp anda akan masuk ke twrp yang di hotboot
   
4. Pada twrp  flash file Magisk-v20.4.zip

5. Setelah Proses flashing  magisk selesai reboot system

6. selamat hp sobat telah rooted

   

## III.Cara Pasang Twrp Recovery



|                           BAHAN                           |                        DOWNLOAD LINK                         |
| :-------------------------------------------------------: | :----------------------------------------------------------: |
| TWRP-fastboot_boot_only-3.2.1-with-Tissot-Manager-2.5.zip | [Download](https://github.com/CosmicDan-Android/android_device_xiaomi_tissot/releases/download/2.5/TWRP-fastboot_boot_only-3.2.1-with-Tissot-Manager-2.5.zip) |
|     TWRP-Installer-3.2.1-with-Tissot-Manager-2.5.zip      | [Download](https://github.com/CosmicDan-Android/android_device_xiaomi_tissot/releases/download/2.5/TWRP-Installer-3.2.1-with-Tissot-Manager-2.5.zip) |
|                     Magisk-v20.4.zip                      | [Download](https://github.com/topjohnwu/Magisk/releases/download/v20.4/Magisk-v20.4.zip) |


1. Download bahan diatas ekstrak  file TWRP-fastboot_boot_only-3.2.1-with-Tissot-Manager-2.5.zip dan pindahkan file hasil ekstrak ke dalam folder minimal adb / platfrom tools , pindahkan file Magisk-v20.4.zip dan TWRP-Installer-3.2.1-with-Tissot-Manager-2.5.zip ke sdcard / internal hp sobat

2. Masuk ke Fastboot Mode ada 2 cara yaitu:

   Melalui Perintah Adb (Hubungkan hp anda ke pc , pastikan usb deblugging telah di izinkan)

   ```
   adb reboot bootloader
   ```

   Jika Menggunakan Tombol tekan dan tahan secara bersamaan  tombol power dan volume -  sampai muncul logo MI lalu lepaskan

   

4. jika hp sudah berada di mode fastboot / bootloader masukan perintah dibawah

   ```
   fastboot boot boot-recovery.img
   ```

   Hp anda akan otomatis masuk ke twrp yang di hotboot

11. Pada twrp  flash file  TWRP-Installer-3.2.1-with-Tissot-Manager-2.5.zip

12. Lalu flash Magisk-v20.4.zip

13. Setelah Proses flashing   selesai reboot system

14. Selamat hp sobat telah rooted dan terpasang twrp




## Semoga Sukses

