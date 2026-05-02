# Taller de Costura Marbelly

Landing page móvil para compartir las cuentas bancarias del taller y copiar los números de cuenta sin espacios.

## Archivos

- `index.html`: página principal con las cuentas de pago.
- `qr.html`: página imprimible que genera un QR hacia `index.html` cuando el sitio está publicado.

## Publicación en GitHub Pages

1. Sube estos archivos a un repositorio de GitHub.
2. En GitHub, abre `Settings > Pages`.
3. En `Build and deployment`, selecciona `Deploy from a branch`.
4. Elige la rama `main` y la carpeta `/root`.
5. Guarda los cambios.

Cuando GitHub Pages publique el sitio, la URL principal será parecida a:

```text
https://TU_USUARIO.github.io/TU_REPOSITORIO/
```

El QR estará disponible en:

```text
https://TU_USUARIO.github.io/TU_REPOSITORIO/qr.html
```

Tambien puedes generar un QR hacia una URL exacta usando:

```text
https://TU_USUARIO.github.io/TU_REPOSITORIO/qr.html?url=https%3A%2F%2FTU_USUARIO.github.io%2FTU_REPOSITORIO%2F
```
