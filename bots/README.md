## Installation on Vps server

###  Requirements to use this bot
 - Vps server with Ubuntu (Use google cloud it's free)
 - install python
 - Install a Google and chromedriver (On your server ofc)

### Installation of the bot to the server
  - Open the console of your server
  - Login as root
  - Type: `crontab -e`
  - Scroll back and add this line: `1 * * * *   python3 /path_of_the_file/file.py`
  - Type `CTRL + X` ==> `Y` ==> and now quit
  NOTE: Don't forget to upload the file on your server
  
  
  ## Installation on Heroku (We're working on it)
