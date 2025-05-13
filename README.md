# Menu Radial - Listado VPM

Este repositorio contiene el listado VPM para el paquete Menu Radial, que permite integrarlo con el VRChat Creator Companion (VCC).

## Uso

Para añadir este repositorio a tu VCC:

1. Abre el VRChat Creator Companion
2. Ve a "Configuración" > "Repositorios"
3. Haz clic en "Añadir Repositorio"
4. Añade la URL: `https://emerytheec.github.io/Menu_Radial_Listing/index.json`

Una vez añadido, podrás encontrar el paquete "Menu Radial" en la lista de paquetes disponibles para tus proyectos.

## Sobre Menu Radial

Menu Radial es un conjunto de herramientas para Unity diseñado específicamente para crear y gestionar menús radiales en avatares de VRChat. Permite configurar fácilmente cambios de objetos, iluminación y materiales que pueden ser controlados mediante parámetros en VRChat.

Para más información, visita el [repositorio principal](https://github.com/emerytheec/Menu_Radial).

## Configuración del repositorio

Para que este repositorio funcione correctamente como un listado VPM, asegúrate de:

1. Tener el archivo `source.json` configurado correctamente
2. Configurar GitHub Pages para publicar desde la rama main
3. Tener un flujo de trabajo de GitHub Actions que ejecute la acción `vrchat-community/package-list-action@v2`