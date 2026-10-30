# HelidoDownloaderFalconiPC

Distribución oficial de **Falconi para PC** (Windows 10 y 11): el chat con el agente de la familia.

## Lo único que hay que bajar

**[InstalarFalconi.exe](https://github.com/h3l1d0/HelidoDownloaderFalconiPC/releases/latest/download/InstalarFalconi.exe)** (~60 KB)

Es un lanzador chiquito: baja el instalador completo (`FalconiSetup-<versión>.exe`, ~260 MB), verifica que sea el publicado (sha256 contra `api.trademer.com/falconi/update-manifest?platform=windows`), lo ejecuta y, si algo falla, vuelve a intentar desde cero. Tiene un botón **«Reportar un problema»** que le manda los registros a Cesar.

### Windows va a desconfiar (no está firmado)

1. Al abrirlo puede salir **«Windows protegió su PC»** (SmartScreen): tocá **«Más información»** y después **«Ejecutar de todas formas»**.
2. Después Windows pide permiso de administrador (una sola vez): tocá **«Sí»**.

El instalador grande lo baja el lanzador, así que no vuelve a aparecer el aviso de SmartScreen.

## Releases

Cada release `pc-<versión>` trae los dos archivos: `InstalarFalconi.exe` y `FalconiSetup-<versión>.exe`. El enlace de arriba siempre apunta a la última.
