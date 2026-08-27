# Ambo de Trabajo — landing page

Sitio en vivo: **https://nahuelinhojrs.github.io/ambo-de-trabajo-landing/**

Es un único archivo `index.html` (sin frameworks, sin build, sin costo de hosting). Cualquier cambio que se suba a la rama `main` se publica solo en el sitio en vivo, en general en menos de un minuto.

Este repositorio es tuyo (cuenta `NahuelinhoJrs`) y no tiene restricciones de rama: podés editarlo directamente vos, desde donde prefieras.

## Opción 1 — Editar directo en GitHub, desde el navegador (sin instalar nada)

1. Entrá a [index.html en GitHub](https://github.com/NahuelinhoJrs/ambo-de-trabajo-landing/blob/main/index.html).
2. Tocá el ícono del lápiz (arriba a la derecha del archivo) para editarlo.
3. Hacé el cambio, bajá al final de la página y tocá **Commit changes...** → **Commit directly to the main branch**.
4. Esperá un minuto y refrescá el sitio en vivo.

Para subir o cambiar una foto: entrá a la carpeta [img/](https://github.com/NahuelinhoJrs/ambo-de-trabajo-landing/tree/main/img), botón **Add file → Upload files**, arrastrá la imagen con el nombre exacto que pide `img/LEEME.txt` (por ejemplo `hero.jpg`) y confirmá el commit.

## Opción 2 — Editar desde tu computadora

```bash
git clone https://github.com/NahuelinhoJrs/ambo-de-trabajo-landing.git
cd ambo-de-trabajo-landing
# editá index.html o agregá fotos en img/
git add .
git commit -m "Actualizo la landing"
git push
```

Necesitás tener Git instalado y estar logueado con tu cuenta de GitHub (`gh auth login`, o que Git te pida usuario/contraseña o token la primera vez que hagas push).

## Pendiente de completar

- Buscá `[INSTAGRAM]` en `index.html` y reemplazalo por el usuario de Instagram.
- Fotos `img/prueba-comun.jpg` y `img/prueba-antimanchas.jpg` (comparación real con lavandina — ver `img/LEEME.txt`). Mientras no estén, esa sección muestra un recuadro gris con el nombre del archivo esperado, no un ícono roto.
- `img/modelo-5.jpg` (verde quirúrgico) y `img/modelo-6.jpg` (bordó) son la misma prenda recoloreada digitalmente a partir de la foto azul marino, no fotos reales de esos colores — están para completar la grilla mientras tanto. Reemplazalas por fotos reales cuando las tengas.

## Datos ya cargados

- Marca: Ambo de trabajo - venta directa de Fabrica
- WhatsApp: +54 9 11 6005 4924 (todos los botones de la página apuntan ahí, con mensaje distinto según la sección)
- Mail: Panambyventas@gmail.com (link "mailto:" en Contacto y footer — ver nota abajo)
- Zona: Provincia de Buenos Aires y CABA, con envíos a todo el país

## Sobre el mail: no hay formulario que envíe datos solo

La página no tiene backend ni servidor propio (por eso es gratis de mantener). El botón
"Escribir un mail" y el mail del footer son links `mailto:`: al tocarlos, se abre la app de
correo del propio visitante (Gmail, Outlook, etc.) con el destinatario y el asunto ya
completados, pero **el mail lo termina de escribir y enviar la persona que visita la página**,
no un formulario que mande algo automáticamente. Si en algún momento se quiere un formulario
real que llegue solo a Panambyventas@gmail.com sin que el visitante use su propio correo, se
puede sumar con Formspree (plan gratis) en un rato, sin tocar el resto del sitio.
