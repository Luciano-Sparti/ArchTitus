# Scripts instaladores de Arch basado en ArchTitus 

README que contiene los pasos de instalación y configuración de Arch Linux completamente funcional que contiene un entorno de escritorio, todos los paquetes de soporte (red, bluetooth, audio, impresoras, etc.), junto con algunas aplicaciones y utilidades preferidas. Los scripts de shell en este repositorio permiten automatizar todo el proceso.

---
## Descargar Arch ISO

Descargar la imagen de Arch desde su página oficial: <https://archlinux.org/download/> y crear un disco USB booteable.

## Bootear Arch ISO

Insertar el USB e iniciar el sistema desde el Disco Extraible. Acto seguido, ejecutar:

```
pacman -Sy git
git clone https://github.com/Luciano-Sparti/ArchTitus
cd ArchTitus
./archtitus.sh
```

## Creditos

- Idea y trabajo original de ChrisTitusTech (https://github.com/ChrisTitusTech/ArchTitus).
- Original packages script was a post install cleanup script called ArchMatic located here: https://github.com/rickellis/ArchMatic
