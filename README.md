# Newsletter-Signup

first you have to download all the file and folder from the github

Then put the downloaded file in new folder

second you have to install latest node.js and git

After install the node.js in the terminal  or Command Promt see that
By typing node --version if you get the version which you install then you have sucessfully install the node.js

NOw going into the New Folder in which you put the downloaded file by using command promt 

cd (change directory command)

cd path of the new Folder 

You have to make your know JSON File so delete the existing json file

So type command 

npm init 

for making JSON FILE

Then,

Now in the command prompt install express, request, body-parser, nodemon

By Typing

npm install express

npm install request

npm install body-parser

npm install nodemon

Now , 

Now you the to make the account on mailchimp

https://login.mailchimp.com/?referrer=%2Flists%2Fmembers%3Fid%3D251746#p:1-s:25-sa:last_update_time-so:false

Now go into the account section and find the api key section in it 

So in tyhe api key section you can generate your know api key

which you had to put in the

app.js on the Line 44

username of your mail chimp : api key which we get

Now go into the audience section in mail chimp then go to the manage audience dropdown section select settings
you get your list id put your list id on the app.js file

on the line 40 

insted of list id you put your know list id wich you get by goning into the settings of the manage audience at the last

SO when you get the api key 

At the last of key -usX

Here X means any random number you get so put this X value in the 

app.js file on the line 40

insited of X put the random value you get

Now make the account in heroku app

https://www.heroku.com/

heroku is your online server

now go to the command prompt and type

heroku login

then, type

git add .

then, type

git commit -m"Change in file"

then, type

heroku create

you get the link server of your website

then, type

git push heroku master

then wait 5 to 10 min

and then open the server link site

And Your Successfully if you follow all the steps
