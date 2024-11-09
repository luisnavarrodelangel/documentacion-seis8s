# Documentación de Seis8s
##(Taller de Transferencias Aurales 2024)

## Diapositivas

<div style='position: relative; padding-bottom: 56.25%; padding-top: 35px; height: 0; overflow: hidden;'><iframe sandbox='allow-scripts allow-same-origin allow-presentation' allowfullscreen='true' allowtransparency='true' frameborder='0' height='315' src='https://www.mentimeter.com/app/presentation/n/bl3sqjhxztxw5vahh471djmgkj5xr19r/embed' style='position: absolute; top: 0; left: 0; width: 100%; height: 100%;' width='420'></iframe></div>

## Lecturas recomendadas

- La cumbia como matriz sonora de Latinoamérica: los colombias de Monterrey-México, 1960-2008, interculturalidad, identidad, espacio y cuerpo: [https://repositorio.colmex.mx/concern/theses/kk91fk66p?locale=es](https://repositorio.colmex.mx/concern/theses/kk91fk66p?locale=es)
- La invención de la música latinoamericana: [https://fce.com.ar/tienda/arte/la-invencion-de-la-musica-latinoamericana/?srsltid=AfmBOoogMJTlc1FkT7jpPyDxYVKEtzCkHF3iiVnZ8fg-h8qlvYKIyVrI](https://fce.com.ar/tienda/arte/la-invencion-de-la-musica-latinoamericana/?srsltid=AfmBOoogMJTlc1FkT7jpPyDxYVKEtzCkHF3iiVnZ8fg-h8qlvYKIyVrI)

## Atajos con el teclado (shortcuts)

| Descripción | Atajo Windows       | Atajo Mac       | Imagen                         |
|----------------|----------------|----------------|-------------------------------|
| Ejecutar/enviar saludos | Shift + Enter | Shift + Enter | ![Alt text](images/saludos.png)   |
| Ejecutar el código | Shift + Enter| Shift + Enter | ![Alt text](images/play.png)   |
| Detener el código | Ctrl + '.' | Ctrl + '.' | ![Alt text](images/stop.png)   |
| Agrandar texto | Ctrl + '+' | Command + '+' | ![Alt text](images/zoomin.png)   |
| Achicar texto |Ctrl + '-' | Command + '-' | ![Alt text](images/zoomout.png)   |
| Descargar documento  |Ctrl + s | Command + s | ![Alt text](images/save.png)   |
| Abrir documento |Ctrl + o | Command + o | ![Alt text](images/open.png)   |


## Codigos de ejemplo

Consulta códigos de ejemplo en el siguiente link: [https://luisnavarrodelangel.github.io/ejemplos-seis8s/ejemplos](https://luisnavarrodelangel.github.io/ejemplos-seis8s/ejemplos)

## Comandos globales

- Los siguientes comandos controlan los instrumentos y la composición globalmente:

| Comando |Descripción| Ejemplo
|----------------|----------------|----------------|
| `tempo` | Establece la velocidad de la música |`tempo 80;`|
| `paneo` | Mueve el sonido a la izquierda, derecha o en medio |`paneo 0;`|
| `volumen` | Establece el volumen maestro/general de la música |`volumen 0.85;`|
| `armonia` | Establece los acordes de los instrumentos |`armonia |C||Dm|;`|
| `acordes` | Es un comando sinónimo del comando armonia|`acordes |C||Dm|;`|

## Comandos de los instrumentos

- Los siguientes comandos controlan los instrumentos individualmente:

### Comandos de notación musical

- La siguiente tabla muestra las figuras rítmicas de los instrumentos en Seis8s:

![Alt text](images/figuras_ritmicas.jpeg)

- Abajo se muestran los mandos para generar las figuras rítmicas de la tabla anterior:

| Comando | Figura rítmica | Valor
|----------------|----------------|----------------|
| `1n` | 𝅝 | 4 tiempos|
| `1s` | 𝄻 | 4 tiempos|
| `2n` |𝅗𝅥  | 2 tiempos|
| `2s` |𝄼  |2 tiempos|
| `4n` | 𝅘𝅥 |1 tiempo|
| `4s` | 𝄽 |1 tiempo|
| `8n` | 𝅘𝅥𝅮  | 1/2 tiempo|
| `8n` | 𝄾  |1/2 tiempo|
| `16n` | 𝅘𝅥𝅯 | 1/4 tiempo|
| `16s` | 𝄿  | 1/4 tiempo|

### Comandos del bajo

| Comando |Descripción| Ejemplo
|----------------|----------------|----------------|
| `bajo` | Toca un bajo default |`bajo;`|
| `sonido` | Cambia el sample o muestra  |`bajo (sonido 6);`|
| `volumen` | Cambia el volumen  |`bajo (volumen 0.85);`|
| `paneo` | Mueve el instrumento a la izquierda, derecha o centro  |`bajo (paneo 0.5);`|
| `octava` | Hace el instrumento más grave o agudo  |`bajo (octava 6);`|
| `tumbao` | Estable la línea melódica  | `bajo (tumbao | 𝅘𝅥  𝄽  𝅘𝅥 /3 𝅘𝅥 /5 || 𝅘𝅥  𝄽  𝅘𝅥 /3 𝅘𝅥 /5 |);`|


### Comandos del teclado
### Comandos de las congas
### Comandos de bombo
### Comandos del contratiempo
