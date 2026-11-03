# Yugi Port

Motor hecho desde cero para jugar **Yu-Gi-Oh! Power of Chaos** (Yugi the Destiny, con extras de Joey the Passion y Kaiba the Revenge) en teléfonos Android, en horizontal y con controles táctiles.

> 🔒 **Repositorio privado, copia personal.** La app (APK) solo trae el motor. Las cartas, imágenes, música y voces salen de los archivos del juego, que están guardados aparte en el release **«datos»**. No compartas esos archivos.

---

## Instalación paso a paso

### Qué descargar y dónde está

| Paso | Archivo | Dónde encontrarlo | ¿Obligatorio? | Qué es |
|---|---|---|---|---|
| 1 | `yugi-port-v1.10.7.apk` (4 MB) | Release [**v1.10.7**](../../releases/tag/v1.10.7) | **Sí** | La app |
| 2 | `yugi-todo.ypk` (632 MB) | Release [**datos**](../../releases/tag/datos) | **Sí** | Todo el juego: cartas, imágenes, menús, música, efectos, voces de Yugi, fusiones, y los rivales Joey y Kaiba |
| 3 | `joey-voces.ypk` (89 MB) | Release [**datos**](../../releases/tag/datos) | Opcional | Voces y música de Joey |
| 4 | `kaiba-voces.ypk` (115 MB) | Release [**datos**](../../releases/tag/datos) | Opcional | Voces y música de Kaiba |

Los archivos están al final de cada release, en la sección **Assets**. Para ver los releases desde la portada, entra en **Releases** en la columna derecha.

> Como el repositorio es privado, para descargar tienes que **haber iniciado sesión en GitHub**. Puedes descargar en el navegador del teléfono con tu sesión iniciada, o descargar en el PC y pasar los archivos al teléfono por cable USB, por ejemplo a la carpeta `Descargas`.
>
> **No cambies el nombre de los `.ypk`:** la app reconoce las voces de Joey y de Kaiba por la palabra `joey` o `kaiba` en el nombre del archivo.

### Orden de instalación

1. **Descarga** los archivos de la tabla: la APK y, como mínimo, `yugi-todo.ypk`.
2. **Instala la APK.** Si Android avisa de «origen desconocido», permite instalar desde el navegador o el gestor de archivos que estés usando.
3. **Abre «Yugi Port».** La primera vez pide los archivos del juego.
4. **Elige los `.ypk`.** Puedes seleccionar los tres a la vez: mantén pulsado `yugi-todo.ypk` y toca `joey-voces.ypk` y `kaiba-voces.ypk`. Si no ves los `.ypk`, usa el selector **«Archivos»** del sistema en lugar de la galería.
5. **Espera** a que la barra termine de mostrar «guardando… en el dispositivo». Mientras tanto ya puedes jugar. Al terminar, la app no vuelve a pedirlos y **puedes borrar los `.ypk` de `Descargas`**.

**Para añadir después las voces de Joey o Kaiba:** ve a **OPCIONES → AÑADIR ARCHIVOS**, elige `joey-voces.ypk` o `kaiba-voces.ypk` y la app se reinicia con ellas.

### Actualizar a una versión nueva

1. Descarga la APK del release más reciente (marcado como **Latest**).
2. Instálala **encima** de la que tienes, sin desinstalar.

No hace falta volver a elegir los `.ypk`: la app conserva los archivos del juego, tu colección, tus mazos y tus estadísticas.

> Si desinstalas la app se borra todo. Antes usa **OPCIONES → EXPORTAR DATOS** para guardar tu progreso, y después de reinstalar recupéralo con **IMPORTAR DATOS**. Los `.ypk` los tendrás que elegir otra vez.

### Alternativa: archivos sueltos del PC

En lugar de los `.ypk` también se pueden elegir los archivos originales, que están en la carpeta de instalación de cada juego en el PC:

| Archivo | De qué juego | ¿Obligatorio? |
|---|---|---|
| `data.dat` | Yugi the Destiny | **Sí** |
| `Voice.dat` | Yugi the Destiny | Recomendado (sonido) |
| `yugi_pc.exe` | Yugi the Destiny | Recomendado (fusiones y lista de prohibidas) |
| `joey.dat` | Joey the Passion: su `data.dat` **renombrado** | Opcional |
| `kaiba.dat` | Kaiba the Revenge: su `data.dat` **renombrado** | Opcional |
| `Voice.dat` | Joey the Passion o Kaiba the Revenge | Opcional: la app detecta de cuál de los dos juegos es |

---

## Qué incluye

- **Duelos con las reglas del juego original:** más de 500 efectos de cartas, cadenas, fusiones, rituales y la IA original de la CPU.
- **Rivales:** Yugi, Joey y Kaiba, cada uno con su mazo, su IA, sus voces y su música (Joey y Kaiba necesitan sus archivos).
- **Modos:**
  - Duelo individual y Torneo (al mejor de 3, con intercambio de side deck y la opción de cambiar de baraja entre duelos).
  - «Los 3» (Yugi → Joey → Kaiba).
  - 2 jugadores en el mismo móvil.
  - **Duelo en red** entre dos teléfonos en la misma red Wi-Fi.
- **Colección y mazos:**
  - Cartas de premio al ganar.
  - Álbum con el progreso de cada edición.
  - Editor de mazos con 5 barajas guardadas, autocompletar y estado de tus fusiones.
  - Claves de cartas.
- **Repeticiones:** se guardan y se pueden exportar e importar.
- **Adaptado al móvil:** textos de las cartas en español, paneles laterales en pantallas anchas, velocidad del duelo ajustable, vibración, y una opción para escuchar tu propia música mientras juegas.

---

## Problemas frecuentes

- **No me deja elegir los `.ypk` o los `.dat`:** usa el selector **«Archivos»** del sistema en lugar de la galería. Algunos selectores ocultan extensiones que no conocen.
- **«falta data.dat»:** no elegiste `yugi-todo.ypk`, o con archivos sueltos falta el `data.dat` de **Yugi the Destiny**.
- **Joey o Kaiba juegan sin voz:** falta `joey-voces.ypk` o `kaiba-voces.ypk`, o se les cambió el nombre. Añádelos en **OPCIONES → AÑADIR ARCHIVOS**.
- **No puedo descargar los archivos de GitHub:** el repositorio es privado, así que inicia sesión en GitHub en ese navegador.
- **La música corta la de otra app:** en **OPCIONES → MÁS AJUSTES** elige «Música: La mía».

---

## Privacidad

La app funciona **sin internet** y no recoge ningún dato. La red solo se usa en el modo **Duelo en red**, y únicamente dentro de tu Wi-Fi local.

---

## Aviso legal

Proyecto de aficionados, **sin ánimo de lucro**, sin relación con Konami ni con sus licenciatarios y sin su respaldo. *Yu-Gi-Oh!* y *Power of Chaos* son marcas y obras de Konami y de Kazuki Takahashi.

La APK **no contiene** archivos, imágenes, sonidos ni textos del juego. Los `.ypk` del release «datos» son una **copia de seguridad personal** de un juego comprado, guardada en este repositorio privado: **no los compartas** y no hagas público el repositorio mientras exista ese release.
