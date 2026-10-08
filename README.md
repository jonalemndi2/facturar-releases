# Facturar — Descargas

Instaladores de **Facturar**, sistema de facturación electrónica multi-empresa integrado con ARCA.

Este repositorio contiene sólo los instaladores publicados. El sistema instalado lo consulta para
avisar cuando hay una versión nueva.

## Descargar

**[Descargar la última versión](https://github.com/jonalemndi2/facturar-releases/releases/latest)**:
en *Assets* elegí el archivo `FacturarSetup-X.Y.Z.exe`.

## Instalar

1. Ejecutá `FacturarSetup-X.Y.Z.exe`. No hace falta ser administrador.
2. Si Windows muestra *"Windows protegió su PC"*: **Más información → Ejecutar de todas formas**.
3. Al terminar se abre Facturar en el navegador.

Requisitos: Windows 10 u 11 de 64 bits y conexión a Internet para emitir comprobantes.

## Actualizar

No hace falta descargar nada a mano: cuando hay una versión nueva, el botón **Sistema** del menú
muestra la etiqueta **Actualizar**. Tus datos no se modifican al actualizar.

## Verificar un instalador (opcional)

Cada versión publica un archivo `.sha256`. En PowerShell:

```powershell
Get-FileHash .\FacturarSetup-X.Y.Z.exe -Algorithm SHA256
```

El valor tiene que coincidir con el del archivo `.sha256`.

---

© Jonathan Alemandi. Software propietario: el uso requiere una licencia otorgada por el titular.
