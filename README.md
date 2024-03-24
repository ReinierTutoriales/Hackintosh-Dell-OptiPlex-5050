# Hackintosh-Dell-OptiPlex-5050
Repositorio EFI Hackintosh  Dell Dell OptiPlex 5050



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
