# ScratchOS 1.Reddit Apps
Developer made apps for ScratchOS 1.Reddit will be hosted here.
## How can I upload my own app?
Simply fork this repository and merge it back with your app.
## How can I make an app?
All applications must be a standalone ```.html``` file. You need to keep your application in a folder with **the same name as the .html file you put in the folder**.

You also need an application icon in any 1:1 ratio in any of the following filetypes:

```.svg```
```.png```
```.jpg```

You also need a ```.json``` index in the following format:
```json
{
  "title":"your title",
  "favicon":"your icon",
  "file":"the name of your .html file",
  "screensize":{"x":"your default x size","y":"your default y size"},
  "fullscreen-supported":"'yes' or 'no'",
  "version":"your app's version",
  "required":"leave this as 'no'" 
}

```
Apps must be suitable for all ages with no 18+ content of any kind. If something isn't age-appropriate, don't submit it. If you're unsure, submit a PR and we will comment why we can't allow your application.
