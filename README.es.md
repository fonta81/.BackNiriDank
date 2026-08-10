# .BackNiriDank

[English Version](README.md)

Configuración personal para el compositor de Wayland [Niri](https://github.com/YaLTeR/niri).

## Estructura del Proyecto
Esta configuración utiliza un enfoque modular, dividiendo varias configuraciones en archivos específicos dentro del directorio `dms/`. El archivo principal `config.kdl` importa estos componentes para mantener la configuración organizada y fácil de mantener.

### Módulos Incluidos
- `dms/colors.kdl`
- `dms/layout.kdl`
- `dms/alttab.kdl`
- `dms/binds.kdl`
- `dms/outputs.kdl`
- `dms/cursor.kdl`
- `dms/windowrules.kdl`

## Créditos
Este proyecto utiliza la estructura modular y el enfoque de gestión de configuración inspirado en **Dank Material Shell (DMS)**. Un agradecimiento especial al proyecto Dank Material Shell por el framework y los principios de diseño que permiten esta configuración modular.

## Instalación
Asegúrate de tener Niri instalado. Copia el contenido de este repositorio a tu directorio `~/.config/niri/`.

```bash
cp -r . /home/tu_nombre_de_usuario/.config/niri/
```
