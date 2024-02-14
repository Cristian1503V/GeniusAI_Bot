# Crea tu propio Bot para Discord 🚀
---

### Resumen
Explora el fascinante mundo de la creación de bots para [Discord](https://discord.com/), aprendiendo a desarrollar una aplicación capaz de proporcionar información relevante sobre temas específicos. En este emocionante viaje, utilizarás el lenguaje de programación Python como tu herramienta principal. Además, aprovecharás las potentes capacidades de los Assistants de OpenAI para mejorar la inteligencia y capacidad de respuesta de tu bot. Todo esto se complementará con el servicio para desarrolladores de Discord, permitiéndote integrar tu bot en la plataforma y ofrecer experiencias interactivas a los usuarios.

Este proyecto te sumergirá en el fascinante cruce entre la programación, la inteligencia artificial y las comunidades en línea. ¡Prepárate para crear un bot único que brinde información útil y enriquecedora a los usuarios de Discord, llevando tus habilidades de desarrollo al siguiente nivel!

---

### Paso N1 
- Inicialmente, es imperativo disponer de una cuenta de Microsoft para acceder a la API de OpenAI.
- Accede a [Microsoft.com](https://www.microsoft.com/es-co) y procede a la creación de una cuenta.

> [!TIP]
> No cierres la cuenta hasta concluir los siguientes pasos, ya que se utilizará en etapas posteriores.

---

### Paso N2 

- Realiza un `git clone` del repositorio para obtener los archivos base del desarrollo.

```
git clone https://github.com/Cristian1503V/GeniusAI_Bot.git
``` 

---

### Paso N3

##### 3.1

- Accede a [OpenAI](https://platform.openai.com/docs/overview).
- Es imperativo contar con una cuenta. Regístrate utilizando la cuenta de [Microsoft.com](https://www.microsoft.com/es-co) creada anteriormente.
- Dirígete a la sección [Assistants 🤖](https://platform.openai.com/assistants) y crea un modelo teniendo en cuenta las instrucciones y los datos que se proporcionarán al modelo. 

##### 3.2
- Debes generar una clave de acceso de OpenAI. Posteriormente, crea un bloc de notas y guarda esta `OPENAI_API_KEY`. 
- Además, necesitarás el `ID_FILE` y el `ASSISTANT_ID` generados al crear tu modelo. Copia y pega en el bloc de notas.

---

### Paso N4 

> [!NOTE] 
> Si ya has completado este paso, omítelo.
- Instala Discord en tu PC.
- Crea un nuevo canal en **Discord** con el nombre que desees para tu bot - 🤖 Ejemplo: **GeniusAI**.
- Accede a tus `Configuraciones ⚙️` de **Discord** y busca `Avanzado`. Activa el `Modo desarrollador`. 

--- 

### Paso N5

##### 5.1
- Ingresa a [Discord Developer](https://discord.com/developers/applications) para crear y configurar el bot.
- En la sección de `Applications`, selecciona `New Application`.
- Asigna un nombre a tu Bot 🤖, por ejemplo, **GeniusAI**, y acepta los términos y condiciones de Discord.
- Al crear tu bot, encontrarás una clave🔑 `DISCORD_CLIENT_ID` muy importante. Llamada `APPLICATION ID`. Cópiala en el bloc de notas.

##### 5.2

- Luego, dirígete a la sección de `OAuth2` y en el subítem [`Url_Generator`](https://discord.com/developers/applications/1207367206921306223/oauth2/url-generator), marca la casilla de `bot` en `SCOPES`.
- Se desplegará otro apartado `BOT PERMISSIONS`. Marca las casillas de `Send Messages` y `Manage Messages`.
- En la parte inferior, encontrarás un apartado `GENERATED URL`. Copia la `URL` generada y guárdala en el bloc de notas. 

##### 5.3

- Ahora, accede a la sección [Bot](https://discord.com/developers/applications/1207224688745648128/bot).
- Haz clic en el botón `Reset Token`. Al hacer esto, se te solicitará tu contraseña y, después de validarla, se te proporcionará un `DISCORD_TOKEN`. Cópialo en el bloc de notas.
    
> [!IMPORTANT] 
> Si encuentras dificultades en este paso, puedes consultar la documentación oficial 
> de [Replit.Docs](https://docs.replit.com/tutorials/python/build-basic-discord-bot-python), donde se explica detalladamente este proceso.


---

### Paso N6

- Regístrate en [replit.com](https://replit.com/~).
- Crea un entorno de desarrollo en Python seleccionando la opción correspondiente en la plataforma.

Estos son los pasos esenciales para comenzar a construir tu bot en Replit, un entorno en línea que facilita el desarrollo y la ejecución de proyectos en Python.
