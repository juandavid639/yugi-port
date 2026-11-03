# Yugi Port

Motor hecho desde cero para jugar **Yu-Gi-Oh! Power of Chaos** (Yugi the Destiny, con extras de Joey the Passion y Kaiba the Revenge) en teléfonos Android, en horizontal y con controles táctiles.

> ⚠️ **Este proyecto NO incluye el juego.** La app no trae cartas, imágenes, música, voces ni textos de Konami: los lee en tu teléfono desde **tu propia copia** de los juegos de PC. Sin esos archivos la app no funciona.

---

## Qué necesitas

- Un teléfono **Android 7.0 o superior** (recomendado: 4 GB de RAM o más).
- Tu copia de **Yu-Gi-Oh! Power of Chaos: Yugi the Destiny** para PC.
- Unos **700 MB libres** en el teléfono para los archivos del juego.

### Archivos del juego

Están en la carpeta donde instalaste el juego en tu PC.

| Archivo | De qué juego | ¿Obligatorio? | Para qué sirve |
|---|---|---|---|
| `data.dat` | Yugi the Destiny | **Sí** | Cartas, imágenes, menús y textos |
| `Voice.dat` | Yugi the Destiny | Recomendado | Música, efectos de sonido y voces |
| `yugi_pc.exe` | Yugi the Destiny | Recomendado | Fusiones y lista de cartas prohibidas y limitadas |
| `joey.dat` | Joey the Passion | Opcional | Es su `data.dat` **renombrado**: rival Joey, sus cartas y las imágenes de cartas que falten |
| `kaiba.dat` | Kaiba the Revenge | Opcional | Es su `data.dat` **renombrado**: rival Kaiba y sus cartas |
| `Voice.dat` | Joey the Passion o Kaiba the Revenge | Opcional | Voces y música de Joey o Kaiba. Se pueden dejar con el nombre `Voice.dat`: la app detecta de qué juego es cada uno |

> Los `data.dat` de Joey y Kaiba **deben renombrarse** a `joey.dat` y `kaiba.dat`, porque los tres juegos usan el mismo nombre.

---

## Instalación

1. **Descarga la APK** desde la sección [Releases](../../releases) de este repositorio (`yugi-port-vX.Y.Z.apk`, unos 4 MB).
2. **Copia los archivos del juego** de la tabla anterior al teléfono por cable USB, por ejemplo a la carpeta `Descargas`.
3. **Instala la APK.** Si Android avisa de «origen desconocido», permite la instalación desde tu navegador o tu gestor de archivos.
4. **Abre «Yugi Port»** y, cuando te lo pida, **selecciona todos los archivos a la vez**: mantén pulsado el primero y toca los demás.
5. **Espera.** La primera vez la app copia los archivos a su memoria interna y aparece una barra de progreso. Al terminar ya no vuelve a pedirlos, y **puedes borrar las copias de `Descargas`**.

¿Tienes Joey o Kaiba y no los añadiste al principio? Ve a **OPCIONES → AÑADIR ARCHIVOS**, elígelos y la app se reinicia con ellos.

### Actualizar

Instala la APK nueva **encima** de la que tienes, sin desinstalar. Conservas tu colección, tus mazos, tus estadísticas y los archivos del juego.

> Si desinstalas la app se borra todo. Antes usa **OPCIONES → EXPORTAR DATOS** para guardar una copia de tu progreso y luego recupérala con **IMPORTAR DATOS**.

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

- **No me deja elegir los archivos `.dat`:** usa el selector de archivos del sistema («Archivos») en lugar de la galería. Algunos selectores ocultan extensiones que no conocen.
- **«falta data.dat»:** el único obligatorio es el `data.dat` de **Yugi the Destiny**. Comprueba que no lo renombraste.
- **No salen Joey o Kaiba como rivales:** faltan `joey.dat` o `kaiba.dat`, o no se renombraron.
- **La música corta la de otra app:** en **OPCIONES → MÁS AJUSTES** elige «Música: La mía».

---

## Privacidad

La app funciona **sin internet** y no recoge ningún dato. La red solo se usa en el modo **Duelo en red**, y únicamente dentro de tu Wi-Fi local.

---

## Aviso legal

Proyecto de aficionados, **sin ánimo de lucro**, sin relación con Konami ni con sus licenciatarios y sin su respaldo. *Yu-Gi-Oh!* y *Power of Chaos* son marcas y obras de Konami y de Kazuki Takahashi.

Este repositorio y la APK **no contienen** archivos, imágenes, sonidos ni textos del juego. Para usarla necesitas tu propia copia legítima. **No publiques ni pidas** los archivos del juego (`.dat`, `.exe` ni paquetes que los contengan) en este repositorio.
