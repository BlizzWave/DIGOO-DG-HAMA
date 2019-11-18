# DIGOO-DG-HAMA


These are the flash dumps from the DIGOO DG-HAMA alarm system. <br>
https://www.mydigoo.com/pt/Digoo-DG-HAMA-All-Touch-Screen-Alexa-Version-433MHz-GSMandWIFI-DIY-Smart-Home-Security-Alarm-System-Kits-p-137.html

This is the same as <br>
http://www.pgstsecurity.com/Products/Smart_Home_Alarm_System/WIFI_GSM_3G_dual_network_alarm_system/3.html


I have done some crude reverese engineering and found out the following. <br>
The alarm has a GigaDevice GD32F107VCT6 (STM32 clone) with 256k of flash memory as its main processor. <br>
It's running Micrium μC/OS-III as its operating system. <br>
It uses a XMC XM25QH64AHIG with 8192k of memory for storage of sounds and bitmaps. <br>

Hopefully this can be helpful to someone. 


