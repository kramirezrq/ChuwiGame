# ChuwiGame

Proyecto 2D desarrollado con Unity.

## Abrir el proyecto

1. Instala **Unity Hub**.
2. Desde Unity Hub, instala el editor **Unity 6000.6.2f1** (versión indicada en `ProjectSettings/ProjectVersion.txt`).
3. Clona este repositorio o descárgalo como ZIP y extráelo.
4. En Unity Hub, elige **Add / Añadir proyecto desde disco** y selecciona la carpeta raíz `ChuwiGame` (la que contiene `Assets`, `Packages` y `ProjectSettings`).
5. Abre el proyecto. Unity restaurará los paquetes indicados en `Packages/manifest.json` y generará los archivos de caché locales.
6. Abre `Assets/Scenes/SampleScene.unity` para revisar la escena incluida.

## Archivos versionados

- `Assets/`: escenas, sprites, configuraciones, archivos `.meta` y recursos del juego.
- `Packages/`: dependencias de Unity.
- `ProjectSettings/`: configuración del proyecto.
- `.gitignore`: reglas para no subir archivos temporales.

## Qué no debes subir

Las carpetas `Library/`, `Temp/`, `Logs/`, `Obj/` y `UserSettings/` se regeneran o son específicas del equipo y están excluidas por `.gitignore`. No se necesita compartir `Library/` para abrir el proyecto.

**Importante:** conserva los archivos `.meta` junto a sus recursos, pues Unity los utiliza para mantener las referencias. El contenido del repositorio fue revisado estructuralmente, pero la apertura y ejecución en Unity debe verificarse en el equipo del desarrollador.
