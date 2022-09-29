# RestDayAPI
  This is a repository of rest day application software. The software uses lua scripting language to automate your computer's mouse and keyboard and detect images on the screen. You can download the bot at:https://elitegamingbot.com/rest-day/

lua API for rest day scripting application

#Creating a bot
bot=Bot() --creates a bot object to be use for clicking and typing
bot:click(Location(x,y)) -- click screen at coordinates x,y
bot:type(letters) --letters is a string e.g. "abcde"


#Detecting images
bot:imageExists(imageName,currentFunction,isTextLogs) -- str,str,boolean
  -detects the image on the entire screen
  
For more info visit the wiki https://github.com/elitegamingbot/RestDayAPI/wiki
