# Mabit PRO-GE · Descargas

Versiones oficiales de **Mabit PRO-GE**, el Sistema Profesional de Gestión Empresarial: ventas, compras, stock,
caja, RRHH, facturación electrónica SIFEN y tienda online.

Este repositorio solo publica las versiones listas para instalar. El código fuente no está acá.

## Descargas directas

| Archivo | Para qué sirve | Enlace |
|---|---|---|
| `instalar-mabit.cmd` | Instala, actualiza o desinstala Mabit como servicio de Windows | <https://github.com/gabrielg13rojas/mabit-releases/releases/download/install/instalar-mabit.cmd> |
| `publicar-internet.cmd` | Publica Mabit en internet con Cloudflare Tunnel (o lo quita) | <https://github.com/gabrielg13rojas/mabit-releases/releases/download/install/publicar-internet.cmd> |

## Instalar en Windows

1. Instalá **Java 21** ([Eclipse Temurin](https://adoptium.net)) y **PostgreSQL**.
2. Descargá [`instalar-mabit.cmd`](https://github.com/gabrielg13rojas/mabit-releases/releases/download/install/instalar-mabit.cmd)
   y hacé doble clic (pide permiso de administrador).
3. Cargá los datos de la base: el instalador descarga la última versión, crea el servicio de Windows y abre
   Mabit en el navegador.

Mabit arranca solo con Windows. Cuando hay una versión nueva, avisa en la barra superior y se actualiza con un
clic; si la versión nueva no arranca, vuelve sola a la anterior.

## Publicar en internet

Con Mabit ya instalado, descargá
[`publicar-internet.cmd`](https://github.com/gabrielg13rojas/mabit-releases/releases/download/install/publicar-internet.cmd)
y hacé doble clic. Instala Cloudflare Tunnel, te pide iniciar sesión en Cloudflare una sola vez (en el navegador)
y deja Mabit publicado en la dirección que elijas, como servicio de Windows.

## Versiones

Cada versión está en [Releases](../../releases), con sus notas de cambios.

## Soporte

- 🌐 [mabit.com.py](https://mabit.com.py)
- 💬 WhatsApp: [+595 986 709035](https://wa.me/595986709035)

© Gabriel González Rojas · Mabit
