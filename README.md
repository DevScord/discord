const Discord = require('discord.js')
const bot = new Discord.Client()

bot.on('ready', function () {
    console.log("Je suis connecté !")
    })
    
    bot.on('message', message => {
        if (message.content === 'ping') {
          message.reply('pong !')
        }
      })

    bot.login('NjI1MzQ4MDIwMTE1OTk2NzAy.XYePqg.VEFsC0DAzQRNJQOma1hj2QdOF3o')
