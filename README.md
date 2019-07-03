# DiscordBotGUIDE

### Hola y bienvenido a la guia para crear tu propio bot

#### EMPECEMOS:


## El codigo inicial es:

<code const Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
  console.log(`Logged in as ${client.user.tag}!`);
});

client.on('message', msg => {
  if (msg.content === 'ping') {
    msg.reply('Pong!');
  }
});

client.login('token')>



#### Pero antes en la consola del proyecto habra que instalar cosas asi que:

<code npm install discord.js>

#### Y si quieres puedes instalar nodemon poniendo:

<code npm install nodemon -D >

#### Para mas pasar a la siguiente pagina.