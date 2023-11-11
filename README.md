# Home Assistant

### Instalacja na małym serwerze z atomem np: DELL WYSE
https://www.home-assistant.io/installation/

### Konwersja KVM (.qcow2) aby nie marnować czasu CPU na zabawy z proxmox 
Zwróć uwagę, że format QCOW2 jest skompresowany! Oznacza to, że obraz QCOW2 o pojemności 200 GB można przekonwertować na dysk twardy o pojemności 500 GB
_qemu-img convert -f haos_ova-11.1.qcow2 -O haos_ova-11.1.img /dev/sdb_


