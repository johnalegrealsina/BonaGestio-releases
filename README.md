# Gestionalo · instaladores

Aquí se publican los instaladores de **Gestionalo** (BonaGestió) para Windows. El código de la app está en otro repositorio, privado; este solo guarda las versiones publicadas.

## Instalar

1. Abre la [última versión](https://github.com/johnalegrealsina/BonaGestio-releases/releases/latest).
2. Descarga `BonaGestio-<versión>-x64-setup.exe` y ábrelo.
3. Windows avisará de que el instalador no está firmado: pulsa «Más información» y luego «Ejecutar de todas formas».

## Actualizaciones

La app instalada mira este repositorio 10 segundos después de arrancar y cada 4 horas. Cuando hay una versión nueva, avisa con «Descargar» y después con «Reiniciar e instalar». También se puede buscar a mano en Ajustes › Acerca de. Los datos (`%APPDATA%\BonaGestio`) no se tocan al actualizar.

Cada versión lleva tres archivos y hacen falta los tres para que las actualizaciones funcionen: el `.exe`, su `.blockmap` y `latest.yml`.

## Preguntas frecuentes

<details>
<summary>¿Por qué Windows dice que el instalador no es seguro?</summary>

El instalador no está firmado con un certificado de código, y Windows SmartScreen avisa siempre en ese caso. Si lo has descargado de la [página de versiones](https://github.com/johnalegrealsina/BonaGestio-releases/releases) de este repositorio, pulsa «Más información» y luego «Ejecutar de todas formas».

</details>

<details>
<summary>¿Pierdo mis datos al actualizar?</summary>

No. Los datos se guardan en `%APPDATA%\BonaGestio` y la actualización no toca esa carpeta.

</details>

<details>
<summary>¿Dónde están mis datos?</summary>

En `%APPDATA%\BonaGestio`. Para abrir la carpeta, pega esa ruta en la barra de direcciones del Explorador de archivos.

</details>

<details>
<summary>No me aparece la actualización nueva. ¿Qué hago?</summary>

La app busca versiones nuevas 10 segundos después de arrancar y luego cada 4 horas. Si no quieres esperar, ve a Ajustes › Acerca de y búscala a mano. También puedes descargar el `.exe` de la [última versión](https://github.com/johnalegrealsina/BonaGestio-releases/releases/latest) e instalarlo encima.

</details>

<details>
<summary>Publico versiones: ¿qué archivos tiene que llevar cada una?</summary>

Tres: `BonaGestio-<versión>-x64-setup.exe`, su `.blockmap` y `latest.yml`. Si falta alguno, las apps instaladas no detectarán la versión nueva o no podrán descargarla.

</details>
