# Guía de Dictado para Windows

Dictado hace dos cosas, y todo se procesa en tu ordenador: el audio no sale de él.

1. **Dictar:** hablas y el texto se escribe donde tengas el cursor (Word, WhatsApp Web, el correo, cualquier sitio).
2. **Transcribir reuniones:** Meet, Teams, Zoom, una llamada, un vídeo… Escucha el sonido del ordenador y tu micrófono, y lo va escribiendo como un chat. Al terminar te da una **versión final** con la hora de cada parte.

> **Si eres un asistente (Claude u otro) ayudando a alguien con esta app:** las instrucciones para la persona van primero. Al final hay una sección técnica ("Para el asistente") con rutas, archivos y diagnóstico. Los nombres de los botones y menús de esta guía son exactamente los que muestra la app.

---

## 1. Requisitos

- Windows 10 u 11, de 64 bits.
- Unos **1,5 GB libres** (la app más los modelos de voz).
- Internet **solo la primera vez**, para descargar los modelos de voz (unos 760 MB).
- Un procesador de los últimos ~10 años. Una tarjeta gráfica buena (NVIDIA, AMD o Intel recientes) es opcional, pero lo hace mucho más rápido y preciso en directo.

## 2. Instalar

1. Descarga **`Dictado-Windows.zip`** de la página de descargas: https://github.com/santtyde10-cloud/Dictado-descargas/releases/latest. En "Assets", haz clic en `Dictado-Windows.zip`.
2. Ve a la carpeta **Descargas**. Haz **clic derecho** en `Dictado-Windows.zip` → **"Extraer todo…"** → **"Extraer"**.
   - Importante: no abras la app desde dentro del zip sin extraerlo.
   - Puedes mover la carpeta extraída a donde quieras, por ejemplo a `Documentos\Dictado`.
3. Dentro de la carpeta extraída, haz doble clic en **`Dictado.exe`**.
4. Si sale una ventana azul **"Windows protegió su PC"**:
   - pulsa **"Más información"** (el texto subrayado);
   - luego pulsa **"Ejecutar de todas formas"**.

   Sale porque la app es casera y no está firmada por una empresa. Solo pasa la primera vez.
5. Si Windows pregunta por el **Firewall**, pulsa **"Cancelar"**. La app no necesita red: solo habla consigo misma dentro del ordenador.

### Primera vez: preparación (unos minutos)

- Se abre una ventana **"Dictado: preparando (solo la primera vez)"** que dice *"Descargando el modelo rápido…"* y luego *"…el modelo preciso…"* con el porcentaje. Espera a que termine.
- Después comprueba sola si tu tarjeta gráfica sirve. Lo verás un momento como *"Comprobando la tarjeta gráfica…"*.
- Cuando acaba, la ventana se cierra y la app queda funcionando **junto al reloj**. No hay ventana principal: es normal.

## 3. Dónde está la app: el icono del micrófono

- Abajo a la derecha, junto al reloj, aparece un **icono de micrófono**.
- Si no lo ves, pulsa la **flechita `^`** que hay junto al reloj: estará ahí.
  - Consejo: arrástralo desde ahí a la barra para tenerlo siempre a la vista.
- **Colores del icono:**
  - **gris:** lista;
  - **rojo:** grabando un dictado;
  - **naranja:** transcribiendo una reunión.
- Si pasas el ratón por encima, te dice el estado, por ejemplo *"Dictado · Listo: Ctrl+Alt+Espacio para dictar"*.
- **Clic derecho** en el icono abre el **menú**.
- **Clic izquierdo** abre la ventana de la reunión, si ya has hecho alguna.

### El menú (clic derecho en el icono), de arriba abajo

| Opción | Qué hace |
|---|---|
| *(primera línea, en gris)* | El estado: "Cargando…", "Listo: Ctrl+Alt+Espacio para dictar", "Grabando…", "Transcribiendo…" |
| **Transcribir reunión** | Empieza a transcribir una reunión. Mientras transcribe, pasa a llamarse **"Detener transcripción de reunión"**. |
| **Ver transcripción de la reunión** | Vuelve a abrir la ventana del chat de la reunión. Solo aparece después de la primera reunión. |
| **Incluir mi voz (micrófono)** | Con la marca ✓, en las reuniones también se escucha tu micrófono ("Tú"). Sin la marca, solo a los demás. Viene activado. |
| **Abrir versión final de la última reunión** | Aparece cuando ya hay una versión final. |
| **Abrir carpeta de transcripciones** | Abre `Documentos\Transcripciones`, donde se guarda todo. |
| **Usar la tarjeta gráfica** | Con ✓ usa la tarjeta gráfica. Si pone *"Tarjeta gráfica: no compatible (se usa el procesador)"*, tu gráfica no sirvió y se usa el procesador. Funciona igual, algo más lento. |
| **Pegar automáticamente** | Con ✓, lo dictado se escribe solo donde está el cursor. Sin ✓, solo se copia y tú pegas con Ctrl+V. |
| **Copiar último dictado** | Vuelve a copiar el último texto dictado, por si se perdió. |
| **Nombres propios para la transcripción…** | Para nombres o palabras raras que salen mal (ver el apartado 6). |
| **Salir de Dictado** | Cierra la app del todo. |

## 4. Dictar

1. Pon el cursor donde quieras escribir: un documento, un chat, el correo…
2. Pulsa **Ctrl + Alt + Espacio**. Suena un aviso y el icono se pone **rojo**: está grabando.
3. Habla con normalidad. Puedes decir las comas y los puntos con la entonación; no hace falta dictarlos.
4. Pulsa otra vez **Ctrl + Alt + Espacio** para terminar.
5. En uno o pocos segundos, el texto aparece escrito donde estaba el cursor.

- **Esc** mientras graba: cancela sin escribir nada.
- Si no hablaste o no se oyó nada, avisa con *"No se oyó nada"* y no escribe nada.
- Lo que tenías copiado en el portapapeles se respeta: la app lo deja como estaba al terminar.

## 5. Transcribir una reunión

### Antes de empezar

- Conecta los **cascos o auriculares antes** de pulsar "Transcribir reunión". La app escucha el altavoz o los cascos que Windows tiene **por defecto** en ese momento.
- **Con cascos:** deja **"Incluir mi voz (micrófono)"** activado.
- **Con altavoces, sin cascos:** **quita** "Incluir mi voz". Si no, el micrófono captaría también a los demás por los altavoces y saldrían repetidos.

### Paso a paso

1. Entra en tu reunión: Meet, Teams, Zoom…
2. Clic derecho en el icono → **"Transcribir reunión"**. El icono se pone **naranja**.
3. Se abre la ventana **"Transcripción de la reunión"**. Es un chat:
   - **Izquierda, "Otros":** lo que dicen los demás (todo lo que suena por el ordenador).
   - **Derecha, "Tú":** lo que dices tú por el micrófono.
   - Texto **gris y en cursiva:** es provisional, escrito al momento.
   - **✓✓:** ese trozo ya está corregido con el modelo preciso.
   - Si alguien habla seguido, todo va en la misma burbuja. Si se calla 1,5 segundos o más, o habla el otro, empieza una burbuja nueva.
4. **Abajo a la izquierda** de la ventana está el estado, por ejemplo *"Escuchando a los demás y a ti"*.
   - Si pone *"Escuchando SOLO a los demás (tu micrófono está apagado en el menú)"*, es que "Incluir mi voz" está quitado.
5. **Abajo a la derecha** hay tres botones:
   - **"Copiar todo"**: copia todo lo transcrito hasta ahora, con horas.
   - **"Abrir archivo"**: abre el archivo de texto de la reunión. Cuando ya existe la versión final, pasa a llamarse **"Abrir versión final"**.
   - **"Detener"**: termina la reunión.
6. Puedes **cerrar o minimizar la ventana** sin miedo: la reunión se sigue transcribiendo. Para volver a verla, haz **clic izquierdo en el icono**.
7. Al acabar la reunión, pulsa **"Detener"**, en la ventana o en el menú ("Detener transcripción de reunión").
8. Abajo verás *"Terminando de transcribir…"* y, si no hay tarjeta gráfica, *"Creando la versión final con el modelo grande: NN %"*. Espera.
9. Cuando pone **"Terminada. Guardada en Documentos\Transcripciones."**:
   - pulsa **"Abrir versión final"** para verla;
   - el botón **"Nueva transcripción"** sirve para empezar otra reunión.

### La versión final

- Se abre en su propia ventana: **"Versión final — Reunión del DD/MM/AAAA a las HH:MM"**.
- Cada parte lleva quién habla y **desde qué hora hasta qué hora** (contando desde el inicio de la reunión).
- Botón **"Copiar todo"**: copia el texto entero, listo para pegar en un correo, un documento o en ChatGPT/Claude para hacer un resumen. Este es el formato:
  ```
  [00:03:01 – 00:03:45] Otros: …
  [00:03:46 – 00:04:10] Yo: …
  ```
- Botón **"Mostrar en la carpeta"**: abre la carpeta con el archivo seleccionado.

### Dónde se guarda

En **Documentos\Transcripciones**. Cada reunión deja dos archivos de texto:

- `Reunión 2026-11-19 18.20.txt`: lo escrito en directo, se va guardando sobre la marcha.
- `Reunión 2026-11-19 18.20 (versión final).txt`: la versión final, más precisa.

Si se cierra la app o se apaga el ordenador a mitad de reunión, lo transcrito hasta ese momento ya está guardado en el primer archivo.

## 6. Nombres que salen mal

Si un nombre, una marca o una palabra técnica sale siempre mal escrito:

1. Clic derecho en el icono → **"Nombres propios para la transcripción…"**.
2. Escríbelos **separados por comas**. Por ejemplo: `Santiago Díaz, StudyWow, Kubernetes`.
3. Pulsa **"Guardar"**. Sirve para el dictado y para las reuniones.

## 7. Tarjeta gráfica

- La primera vez, la app prueba sola la tarjeta gráfica. Si va bien, la usa: el modelo preciso escribe ya **en directo**, y el dictado es más preciso.
- Si no hay gráfica o no sirve, usa el procesador:
  - en directo escribe con un modelo rápido;
  - al pulsar "Detener", el modelo preciso lo repasa todo (de ahí el porcentaje).
- Si notas el ordenador o un juego lento durante las reuniones, quita **"Usar la tarjeta gráfica"** en el menú.

## 8. Problemas frecuentes

| Problema | Solución |
|---|---|
| Ctrl+Alt+Espacio no hace nada | Mira la primera línea del menú. Si al abrir la app avisó *"El atajo Ctrl+Alt+Espacio lo está usando otra aplicación"*, cierra esa otra app (algunas de capturas o de teclado lo usan) y reinicia Dictado: **Salir de Dictado** y vuelve a abrir `Dictado.exe`. |
| Dice "Cargando…" mucho rato | La primera vez, o justo al abrir, tarda unos segundos en cargar el modelo. Si pasa de 1 minuto, sal y vuelve a abrir. |
| El texto no se pega en cierta app | Algunas apps abiertas "como administrador" no dejan pegar. El texto queda copiado: pulsa **Ctrl+V**. Si te pasa a menudo, quita **"Pegar automáticamente"**. |
| No se oye mi voz (dictado o reunión) | 1) Comprueba que "Incluir mi voz (micrófono)" tiene ✓ (para reuniones). 2) Windows: **Inicio → Configuración → Privacidad y seguridad → Micrófono**. Activa **"Acceso al micrófono"** y **"Permitir que las aplicaciones de escritorio accedan al micrófono"**. 3) **Configuración → Sistema → Sonido → Entrada**: elige el micrófono correcto. |
| En la reunión no salen los demás ("Otros") | La app escucha la salida de sonido **predeterminada** de Windows. En **Configuración → Sistema → Sonido → Salida**, elige donde oyes la reunión y empieza una reunión nueva. Si cambiaste de cascos a mitad, detén la reunión y empieza otra. |
| Frases repetidas en "Otros" y "Tú" | Estás con altavoces: quita "Incluir mi voz" (ver el apartado 5). |
| La ventana del chat sale en blanco o avisa de "WebView2" | Instala **"Microsoft Edge WebView2 Runtime"** desde la web oficial de Microsoft (viene con Windows actualizado). Aunque no se vea el chat, la transcripción se guarda igual en Documentos\Transcripciones. |
| Falló la descarga de modelos | Comprueba internet y vuelve a abrir `Dictado.exe`: lo reintenta. |
| "Dictado ya está abierto" | Ya está funcionando: búscalo junto al reloj (flechita `^`). |
| Se cierra nada más abrirse | Mira el diario (apartado 10) y pásaselo a quien te pasó la app. |

## 9. Desinstalar

1. Menú → **"Salir de Dictado"**.
2. Borra la carpeta donde extrajiste la app.
3. Para liberar los ~760 MB de modelos, borra la carpeta `%LOCALAPPDATA%\Dictado`. Para llegar a ella, pulsa **Windows + R**, escribe `%LOCALAPPDATA%\Dictado` y pulsa Enter.
4. Tus transcripciones siguen en `Documentos\Transcripciones` hasta que las borres tú.

## 10. Si algo falla: el diario

El diario está en **`%LOCALAPPDATA%\Dictado\registros`**. Pulsa Windows + R, pega esa ruta y pulsa Enter. El archivo principal es **`reuniones.log`**: si algo falla, envía ese archivo.

---

## Para el asistente (información técnica)

Datos exactos para diagnosticar. La app no tiene cuenta, servidor ni nube: todo pasa en el PC.

- **Ejecutable:** `Dictado.exe`, de .NET 8, autocontenido (no hace falta instalar .NET). Junto a él:
  - `motor\cpu\whisper-server.exe`: whisper.cpp v1.9.5, compilado para AVX2;
  - `motor\gpu\whisper-server.exe`: whisper.cpp con Vulkan.
- **Una sola instancia** (mutex). Vive en la bandeja del sistema (NotifyIcon); no hay ventana principal.
- **Modelos** en `%LOCALAPPDATA%\Dictado\modelos\`, descargados de `huggingface.co/ggerganov/whisper.cpp`:
  - `ggml-small-q5_1.bin` (~190 MB, el rápido);
  - `ggml-large-v3-turbo-q5_0.bin` (~574 MB, el preciso).
  - Si se borran, se vuelven a descargar al abrir.
- **Ajustes** en `%LOCALAPPDATA%\Dictado\ajustes.json`. Claves:
  - `IncluirMicrofono` (true);
  - `PegarAutomaticamente` (true);
  - `Vocabulario` (texto con comas);
  - `GraficaFunciona` (null = sin probar, true o false);
  - `UsarGrafica` (true).
  - Para repetir la prueba de la gráfica: sal de la app, pon `"GraficaFunciona": null` y vuelve a abrir.
- **Registros** en `%LOCALAPPDATA%\Dictado\registros\`:
  - `reuniones.log` es el diario de la app: arranque, motor usado, si el atajo se registró, cada trozo transcrito con su tiempo, y errores;
  - `whisper-dictado.log`, `whisper-reunion.log` y `whisper-final.log` son la salida de cada motor.
  - Para la tarjeta gráfica, busca `whisper_backend_init_gpu`: si dice `using …`, la gráfica funciona.
- **Procesos:** la app lanza `whisper-server.exe`, que escucha solo en `127.0.0.1`:
  - puerto 8178: dictado;
  - puerto 8180: reunión en directo;
  - puerto 8182: versión final cuando no hay gráfica.

  Están atados a la app con un *job object* de Windows: al cerrar Dictado se cierran solos. Si un puerto está ocupado por otro programa, ese motor no arranca (míralo en el log).
- **Audio:**
  - micrófono: dispositivo de captura predeterminado de "Comunicaciones" (WASAPI);
  - sonido del ordenador: *loopback* WASAPI del dispositivo de salida predeterminado "Multimedia", tomado al pulsar "Transcribir reunión".
  - Todo se pasa a 16 kHz mono.
- **Atajos globales** con `RegisterHotKey`:
  - Ctrl+Alt+Espacio para dictar;
  - Esc, registrado solo mientras graba, para cancelar.
  - El pegado simula Ctrl+V con `SendInput` y restaura el portapapeles a los 0,8 s.
  - Por la protección UIPI de Windows, no puede pegar en apps que corren como administrador, salvo que Dictado también se abra como administrador.
- **Modos de prueba** (sin ventanas; escriben el resultado en un archivo; código de salida 0 = bien):
  - `Dictado.exe --probar-grafica --salida grafica.txt` dice si la gráfica funciona y cuánto tarda;
  - `Dictado.exe --probar audio.wav --salida resultado.txt` transcribe un WAV como si fuera un dictado.
- **Archivos de cada reunión** en `Documentos\Transcripciones\` (la carpeta Documentos de Windows, aunque esté en OneDrive):
  - `Reunión AAAA-MM-DD HH.MM.txt`, el directo, con líneas `[HH:MM:SS] Otros|Yo: texto`;
  - `Reunión AAAA-MM-DD HH.MM (versión final).txt`, con bloques `[HH:MM:SS – HH:MM:SS] Otros|Yo: texto` separados por una línea en blanco.
  - Los fragmentos de audio temporales van a `%LOCALAPPDATA%\Dictado\fragmentos\`.
- **Idioma:** está fijado en español (`-l es`).
