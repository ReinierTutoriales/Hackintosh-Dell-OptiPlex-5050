# Hackintosh-Dell-OptiPlex-5050
Repositorio EFI Hackintosh  Dell Dell OptiPlex 5050

<img src="https://your-image-url.type](https://github.com/ReinierTutoriales/Hackintosh-Dell-OptiPlex-5050/blob/main/IMG/Dell%20OptiPlex%205050.png" width="100" height="100">

![macOS Sonoma](IMG/1.png)

![macOS Sonoma](IMG/2.png)
[![Static Badge](https://img.shields.io/badge/macOS-Sonoma-blue)](https://www.reiniertutoriales.com/isos-raw-macos/)
[![Static Badge](https://img.shields.io/badge/OpenCore-1.0.0-green)](https://github.com/dortania/build-repo/releases/download/OpenCorePkg-58f57a3/OpenCore-1.0.0-RELEASE.zip)

[![](https://img.shields.io/badge/YouTube-informational?style=for-the-badge&logo=telegram&logoColor=white&color=FF0000)](https://youtube.com/c/ReinierTutoriales)
[![](https://img.shields.io/badge/PayPal-informational?style=for-the-badge&logo=paypal&logoColor=white&color=003087)](https://www.paypal.com/paypalme/ReinierTutoriales)
[![](https://img.shields.io/badge/-Telegram-informational?style=for-the-badge&logo=telegram&logoColor=white&color=0088cc)](https://t.me/ReinierTutoriales)
[![](https://img.shields.io/badge/-Twitter-informational?style=for-the-badge&logo=twitter&logoColor=white&color=00aced)](https://twitter.com/ReinierTutorial)
[![](https://img.shields.io/badge/-Facebook-informational?style=for-the-badge&logo=facebook&logoColor=white&color=3b5998)](https://www.facebook.com/ReinierTutoriales)
[![](https://img.shields.io/badge/-Instagram-informational?style=for-the-badge&logo=instagram&logoColor=white&color=C13584)](https://www.instagram.com/reiniertutoriales/)
[![](https://img.shields.io/badge/-Discord-informational?style=for-the-badge&logo=discord&logoColor=white&color=7289da)](https://discord.gg/pQcCDBMn)

</p>


[![Cómprame Café](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/reiniertutoriales) [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/paypalme/ReinierTutoriales) [![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/ReinierTutoriales)</a>
</p>

<hr>


| Especificaciones    | Detalles               |
| ------------------- |------------------------|
| Modelo              | DELL-OptiPlex-5050MT   |
| Procesador          | Intel Core i5-7500     |
| Memoria             | DDR4 16GB              |
| Disco Duro          | 256GB SSD              |
| Gráficos integrados | Intel Graphics HD630   |
| Códec de Audio      | Realtek ALC255         |
| Tarjeta de Red      | Intel i219V            |
| Tarjeta de WIFI     | Intel                  |

# Configuración del BIOS para elementos ocultos en BIOS
* Copie la carpeta EFI-shell a la unidad flash USB, cámbiele el nombre a EFI y luego inicie desde la unidad flash USB
* Establezca DVMT preasignado en 64 M:
  ***setup_var 0x795 0x02***
* Desactivar bloqueo CFG:
  ***setup_var 0x4ed 0x00***

# Configuración del BIOS
* General → Advanced Boot Options：***Desmarcar***
* System Configuration → SATA Operation: ***AHCI***
* System Configuration → Serial Port: ***Disabled***
* Secure Boot → Secure Boot Enable: ***Disabled***
* Power Management → Block Sleep → Block Sleep (S3 state) ***Controlar***
* Virtualization Support → VT for Direct I/O: ***Desmarcar***
