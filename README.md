##Titulo
Noticiero climatico

##Descripción
El tema trata sobre el cambio climático, algo que nos afecta en varios aspectos hoy en día, aunque claro...como diría Paulo Coelho, Los problemas nunca se acaban. Pero las soluciones tampoco!. En este proyecto, tenemos a nuestro noticiero climático, alias NoCli, quien por medio de la plataforma de discord, diariamente presentara al usuario noticias sobre el cambio climático, y a la vez soluciones. También cuenta con sintetizador de voz, modo que promedio del phyton no solo buscará informar al usuario en discord sino también a los programadores. En este, se estará utilizando por la comodidad la versión 3.9 del intérprete de phyton. "Si estás lo suficientemente preocupado por un resultado, posiblemente harás algo para solucionarlo." - William James

## Caracteristicas 
Proporciona datos del cambio clímatico
Brinda imagenes
Brinda soluciones reales para mitigar el daño ambiental
Tiene sintetizador de voz
Da estadisticas de contaminación contra diferentes países 

## Requisitos
Version Python 3.9 o superior
Cuenta y servidor de discord
El token del bot
Librería discord

##Ejecución
#Inicia el bot
intents = discord.Intents.default()
intents.message_content = True
bot = commands.Bot(command_prefix ="!", intents=intents)

#Comandos
!menu
!noticia
!dato
!extra

##Configuración del bot

1. Ve a [Discord Developer Portal](https://discord.com/developers/applications)
2. Crea una nueva aplicación y un bot.
3. Copia el **token** y pégalo en tu `.env` o `config.py`
4. Genera un enlace de invitación con los permisos que necesites:

##Autor
Desarrollado por **Lian** y **Aleja** 
📧 Contactos: lian.segura@filipenses.com  y aleja.cocorico@winbina.com
🌐 [GitHub](https://github.com/LianSegura/Readme.md/edit/main/README.md)

##Instalaciones
pip install discord
pip install -r requirements.txt
Clona repositorio
   ```bash
    git clone https://github.com/LianSegura/Readme.md/edit/main/README.md
    cd DiscordBotXYZ

