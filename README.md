# Dictado

Dictado por voz y transcripción de reuniones, **todo en tu ordenador**: el audio no sale de él, sin límites ni suscripciones.

## Descargar

Ve a **[Releases](../../releases/latest)** (a la derecha, "Releases") y descarga el archivo de tu sistema:

- **Windows 10 / 11:** `Dictado-Windows.zip`

## Instalar en Windows

1. Descomprime `Dictado-Windows.zip` en una carpeta: clic derecho → **"Extraer todo…"**. No lo abras desde dentro del zip.
2. Abre **`Dictado.exe`**. Si Windows avisa con *"Windows protegió su PC"*, pulsa **"Más información"** y luego **"Ejecutar de todas formas"**. Sale porque la app no está firmada por una empresa.
3. La primera vez descarga los modelos de voz (unos 760 MB, solo una vez) y comprueba si tu tarjeta gráfica sirve para ir más rápido.
4. Aparece un icono de **micrófono junto al reloj**. Si no lo ves, pulsa la flechita **^**. Ahí está el menú.

## Cómo se usa

- **Dictar:** pulsa **Ctrl + Alt + Espacio**, habla y vuelve a pulsar **Ctrl + Alt + Espacio**. El texto se escribe donde tengas el cursor. **Esc** cancela.
- **Reuniones:** menú → **"Transcribir reunión"**. Escucha el sonido del ordenador (también con cascos) y tu micrófono, y lo muestra como un chat: los demás a la izquierda y tú a la derecha. Al pulsar **"Detener"**, el modelo preciso lo repasa todo y deja la **versión final**, con la hora de cada parte y el botón **"Copiar todo"**.
- Todo se guarda en **Documentos\Transcripciones**.
- **Tarjeta gráfica:** si es buena (NVIDIA, AMD o Intel recientes), la app la usa sola y el modelo preciso escribe ya en directo.
- **Nombres que salen mal:** menú → **"Nombres propios para la transcripción…"**.

Funciona con [whisper.cpp](https://github.com/ggml-org/whisper.cpp) y los modelos Whisper de OpenAI, que se ejecutan en tu ordenador.
