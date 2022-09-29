# RestDayAPI
  This is a repository of rest day application software. The software uses lua scripting language to automate your computer's mouse and keyboard and detect images on the screen. You can download the bot at: https://elitegamingbot.com/rest-day/

lua API for rest day scripting application

## Creating a bot
```
bot=Bot() --creates a bot object to be use for clicking,typing and detecting images on the screen
bot:click(Location(x,y)) -- click screen at coordinates x,y
bot:type(letters) --letters is a string e.g. "abcde"
```


## Detecting images
```
bot:imageExists(imageName,currentFunction,isTextLogs)
  
  Parameters:
  
  imageName(type:string) - name of the image e.g. example.png
  currentFunction(type:string) - any string you like as a title of the currently executing bot e.g. "[Photoshop Bot]"
  isTextLogs(type:boolean) - if true,display bot logs at the logs section of the software
  
  Returns:
  true or false
  
```
Sample Usage:
```
  if bot:imageExists("image.png","[Calculator Bot]",true) do
     bot:clickLastMatch()
  end
```
  
For more info on the API's classes and functions visit the [Wiki](https://github.com/elitegamingbot/RestDayAPI/wiki)
