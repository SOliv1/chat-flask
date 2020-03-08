# Flask Chat project

This is a chat application written in Flask. 
The purpose of this project is to take data from a URL and store the information in a list

## Deploy our flask chat project to Heroku
### Check list

1) Create requirements.txt
2) Create Procfile
3) Create a new Heroku app
4) Create any config variables
5) Push code to Heroku

### Create Procfile command
echo web: python run.py > Procfile
### Create Procfile command
heroku apps:create
### Create Heroku app command
git remote -v
### Create config variables command
-Go to Heroku - Now click on that, go to Settings, and then *Reveal Config Var
-Create secret key.
-Call it SECRET.
-Give that the value of secretproductionkey1234.
-Then that's added.
### push to Heroku command
Go back Gitpod, back to terminal window, and type git push -u heroku master.
-       push the app to Heroku.
-       And this can take time to build.
-i)     it needs to build source and then install everything from our requirements.txt file.
-ii)    using the magic of technology, we've cut down the process a little bit.
-iii)   we can see that it says that it's now deployed.
-iv)    go back to our app in Heroku and click on open app, we can see that it's up and running.
-v)     choose my username, go to chat, and type a message, which should work.
vi)     open up the flask-chatroom-project in another window
vii)    Try testing with a Chrome incognito window to do this.
Viii)   log in as Jane here.
ix)     Then we can see that my chat is there.
x)      Jane will say Hi Sara.
        And when I go back to my own homepage, I can see that the message is there.
        So our project is now deployed and working.
        And maybe as a personal challenge, you might like to have a look at how to add other functionality to this, such as, maybe, adding a clear chat history link and styling it so that it looks nice.
        But for us, this concludes our mini project.

## Conclusion
In this section, I have learnt a lot about Flask and Python.
I have come a long way as a developer.
I have seen how to create a Flask app and how to create basic and advanced routes.
I have seen how to read in data from a JSON file and how to use the Flask templating language to display that nicely.

###The End

Welcome Sara Oliver,

We have preinstalled all of the tools you need to get started.

To run a frontend application in GitPod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: *Expose*,

Another blue button should appear to click: *Open Browser*.

To run a backend python file, type `python3 app.py`, if your python file is named `app.py` of course.

A blue button should appear to click: *Expose*,

Another blue button should appear to click: *Open Browser*.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the backend lessons. 

Happy coding!
