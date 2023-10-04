# linkedinbot
It is often hectic to make connections on linkedin by continuously pressing the connect button again and again monotonously. Here is a way to automate it.
### Web driverr
Just copy paste this code on your favourite editor, make sure that you name it something as bot.py with the py extension something like that. 
Now in order to make it work you need to have a webdriver. Since I have used the chrome web driver I will tell you about that. By this I mean that the script that we are executing will only execute on google chrome because we are using the chrome webdriver. We can use others as well, but lets save it for later. 
You can download the chrome web driver from [chromeWebdriver](https://chromedriver.chromium.org/downloads).

### Understanding the code
From the code block at the top we basically log into the linkedin account ull need to put in ur mail id and password there.

Go to your linkedin->hit search->click on people->copy the url->
paste the url in "url of the page you want to connect".

Here is the real code now. 
We create a list of elements with the tagname button this is because when we inspect the page linkedin is clever enough to put unique id for each button.

To click on the button we are using js because linkedin has blocked any activity of python bots.

### Run code
Open terminal run the code as 
```python3 name.py```
