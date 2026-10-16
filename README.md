# Para Valentina

Página web minimalista para que Nicole le pida a Valentina que sean novias. Se abre en el celular escaneando un QR.

**Recorrido:** portada → 4 capítulos de la historia (amigas → confianza → el cambio → hoy) →
años y días en números → "lo que sé de ti" → sobre con una carta → **"¿Quieres ser mi novia?"** →
pantalla final. Tiene una melodía suave de piano que ya viene incluida, así que no hay que subir ninguna canción.

Para pasar de pantalla se toca a la derecha (o se desliza el dedo). Para devolverse, se toca a la izquierda.

---

## Guía de GitHub desde cero

Todo se hace desde la página web de GitHub (github.com), sin instalar nada.
Funciona en el computador y también en el navegador del celular (en el computador es más cómodo).

### 1. Abrir el repositorio
Entra a **https://github.com/vvgggggg/Nicole**. Vas a ver una lista de archivos:
`index.html` (la página), la carpeta `fotos`, `qr.png` y este `README.md`.

### 2. Subir las fotos
1. Haz clic en la carpeta **`fotos`**.
2. Arriba a la derecha: botón **Add file → Upload files**.
3. Arrastra las fotos (máximo 4, una por capítulo). Usa fotos **verticales** si puedes.
   - Las fotos del iPhone a veces salen en formato `.HEIC`, y eso no funciona en la web.
     Pásalas a JPG antes de subirlas (por ejemplo, mándatelas por WhatsApp y descárgalas).
   - Ponles nombres sencillos, sin espacios ni tildes: `1.jpg`, `2.jpg`, `3.jpg`, `4.jpg`.
4. Abajo, clic en el botón verde **Commit changes**. (En GitHub, "commit" significa "guardar".)

Si las nombras `1.jpg` a `4.jpg`, no tienes que cambiar nada más: ya quedan conectadas.

### 3. Editar los textos
1. Vuelve al inicio del repositorio y haz clic en **`index.html`**.
2. Clic en el **ícono del lápiz ✏️** (arriba a la derecha del archivo), que sirve para editar.
3. Busca el bloque que dice **`EDITA SOLO ESTE BLOQUE`**. Todo lo que hay que cambiar está ahí:
   - `seConocieron`: la fecha en que se conocieron, en formato `AAAA-MM-DD`, por ejemplo `"2015-09-20"`.
   - `algoNuevo`: la fecha en que empezó lo de ahora.
   - `historia`: el título y el texto de cada capítulo, y el nombre de su foto.
   - `loQueSe`, `carta`, `final`: los textos.
4. Reglas para no dañar nada:
   - Cambia solo lo que está **entre comillas** `"así"`.
   - No borres las comillas, las comas `,` ni las llaves `{ }`.
   - `<i>palabra</i>` pone esa palabra en cursiva y en color terracota. Úsalo para resaltar una palabra.
5. Clic en el botón verde **Commit changes…** y otra vez **Commit changes** en la ventana que aparece.

### 4. Publicar la página (solo se hace una vez)
1. Primero, el repositorio tiene que ser **público**: **Settings** (la pestaña con el ícono de engranaje ⚙️) →
   baja hasta el final, a **Danger Zone** → **Change visibility** → **Make public**.
2. En **Settings**, menú de la izquierda → **Pages**.
3. En **Branch**, elige **`main`**, deja la carpeta **`/ (root)`** y dale **Save**.
4. Espera 1–2 minutos y recarga la página de Settings. Arriba va a aparecer el link:
   **https://vvgggggg.github.io/Nicole/**

Cada vez que guardes un cambio (commit), la página se actualiza sola en 1–2 minutos.
Si no ves el cambio, recarga la página en el celular.

### 5. El QR
El archivo `qr.png` ya apunta a **https://vvgggggg.github.io/Nicole/**. Haz clic en él dentro de GitHub
y luego en **Download** para bajarlo. Imprímelo en una tarjeta.

---

## Antes del momento
- Abre el link en tu celular y recorre la página completa: revisa que se vean las fotos y que no haya errores en los textos.
- **Sonido:** la melodía arranca al tocar "Empezar". En iPhone, si no suena, revisa que el celular no esté en modo silencio (el interruptor del costado).
- Si quieres quitar la música, cambia `musica: true` por `musica: false`.
- Si toca "Necesito pensarlo", sale un mensaje tranquilo y un botón para volver a la pregunta.
