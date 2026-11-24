# SmallCap Executor

Canal oficial de descarga de **SmallCap Executor**, de SMALLCAP MARKET SYSTEMS LLC.

## Descargar

La última versión está en **[Releases](../../releases/latest)**.

Descarga `CENTINELA-win64.zip`, descomprímelo en una carpeta de tu usuario y
ejecuta `CENTINELA.exe` desde ahí. El mismo programa sirve a CENTINELA y a
LUMBRE: se muestra con el nombre de tu producto al activar la licencia.

## Manual de LUMBRE

Junto al programa, en cada Release, viene **`Manual-LUMBRE.pdf`**: descarga,
instalación, activación de la licencia, Set & Forget, cada ventana, Telegram y
solución de problemas, con las pantallas reales.

- PDF: [manual/Manual-LUMBRE.pdf](manual/Manual-LUMBRE.pdf)
- En texto, para leerlo aquí o dárselo a tu asistente de IA:
  [manual/MANUAL-LUMBRE.md](manual/MANUAL-LUMBRE.md)

Puedes entregarle el manual a ChatGPT, Claude o el asistente que uses y pedirle
que te guíe paso a paso. El capítulo 15 trae sus instrucciones.

## Necesitas una licencia

El programa se descarga completo, pero **sin una licencia válida no opera**.
La clave llega por correo al comprar. Sin ella, la aplicación arranca en su
modo más limitado y no ejecuta ninguna estrategia.

Para comprar: [mariomaldonado.com](https://mariomaldonado.com/smallcap-executor/)

## Aviso de Windows

El programa todavía no está firmado con un certificado de código, así que
Windows puede mostrar una advertencia de SmartScreen la primera vez. Es
esperado. Puedes verificar que el archivo es el nuestro comparando su SHA-256
con el publicado en cada Release.

```powershell
(Get-FileHash .\CENTINELA-win64.zip -Algorithm SHA256).Hash
```

## Advertencia de riesgo

Operar en los mercados financieros implica riesgo de pérdida. Este software es
una herramienta de ejecución: no es asesoría de inversión y no garantiza
resultados. Los rendimientos pasados no predicen rendimientos futuros. Los
términos completos se muestran y deben aceptarse dentro de la aplicación.

## Soporte

info@mariomaldonado.com

---

Este repositorio contiene únicamente los binarios publicados. El código fuente
no es público.
