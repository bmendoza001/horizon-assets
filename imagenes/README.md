# Imagenes publicas

Guarda aqui fondos, logos e imagenes decorativas para SAP Horizon.

Usa WebP para fotografias y SVG para logos. Usa nombres sin espacios y respeta mayusculas y minusculas.

GitHub Pages esta configurado desde la rama main y la raiz del repositorio:
https://bmendoza001.github.io/horizon-assets/

Ejemplo: al subir imagenes/fondo-sap-v1.webp, su URL sera:
https://bmendoza001.github.io/horizon-assets/imagenes/fondo-sap-v1.webp

En PRD.css:

```css
--hz-bg-image: url("https://bmendoza001.github.io/horizon-assets/imagenes/fondo-sap-v1.webp");
```

El archivo de ejemplo debe subirse antes de usar su URL. Despues de subir cambios, espera a que termine la publicacion de Pages. Para reemplazar una imagen, usar un nombre versionado evita mostrar una copia anterior desde la cache.

Este repositorio contiene solo recursos publicos. La captura original de SAP y el proyecto de vista previa permanecen en el espacio de trabajo local.