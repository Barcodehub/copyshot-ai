# CopyShot AI

Toma una foto de un texto o pregunta, lo lee con OCR y envía el
contenido a la IA que elijas (DeepSeek, Claude u OpenAI) para obtener
una respuesta en streaming — directo desde tu teléfono Android.

Este repositorio publica únicamente los **releases** (el APK listo para
instalar). El código fuente se desarrolla en un repositorio privado.

## Descargar

Ve a la pestaña [Releases](../../releases) de este repositorio y
descarga el `app-release.apk` de la versión más reciente.

Android bloqueará la instalación por defecto (viene de fuera de Google
Play); tendrás que permitir "Instalar apps desconocidas" para el
navegador o gestor de archivos que uses.

## Primeros pasos tras instalar

1. Abre la app y concede el permiso de cámara.
2. Toca el ícono ⚙ (Ajustes), elige un proveedor de IA (DeepSeek,
   Claude u OpenAI) y pega tu propia API key de ese proveedor.
3. Apunta la cámara a un texto o pregunta y presiona "Capturar".

## Seguridad

- La app **no incluye ninguna API key**. Cada usuario usa la suya
  propia, que se guarda cifrada en el dispositivo (Android Keystore)
  y nunca sale de ahí salvo para llamar directo a la API del proveedor
  elegido.
- No hay backend ni servidor intermedio: la app llama directo a la API
  de IA que configures.
