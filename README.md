# Fooocus Discord Bot
Generate AI Art via a Fooocus server hosted anywhere, calling it through your discord bot.

![image](https://raw.githubusercontent.com/InfernoDragon0/Fooocus-Discord/master/output/1692325614242.png)
> Quality: False, Style: 1, Prompt: cat with sunglasses

### Requirements
- Fooocus Server (you can download and self host one via [Fooocus Github](https://github.com/lllyasviel/Fooocus))
- Discord Bot Token, Client ID and/or Server ID

### How to run
- Use the ```.env.example``` file and rename it to ```.env```
- Add your secrets into the ```.env``` file, including the URL to your Fooocus server
- You can deploy commands with ```node deploy```
- Run the bot with ```npm run start```

### Command
- ```/imagine```: write a prompt to generate an image. Optionals are ```style``` from ```1 to 105``` and ```quality```, set ```quality``` to ```true``` for high quality images. Outputs are also stored in the discord bot folder ```output``` as well.