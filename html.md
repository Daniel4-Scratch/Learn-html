# Intro
Ever wanted to make a website or a webpage, I'm gonna tell you how. And it's completely **free**!

**Firstly** we need to install some software. 

<img align="right" width="100" alt="Atom Logo" src="https://user-images.githubusercontent.com/65277548/125181862-51a39900-e24c-11eb-9822-92173ef9b37c.png">

## Installing Atom

We're going to use Atom. Atom is a free open source text/file editor for macOS, Linux, and Microsoft Windows.

Go to [atom.io](https://atom.io/) and hit the download button or download it from [github releases](https://github.com/atom/atom/releases/tag/v1.57.0).

[![Install Atom](https://img.shields.io/static/v1?label=Atom&message=Install&color=orange&style=for-the-badge&logo=atom)](https://github.com/atom/atom/releases/tag/v1.57.0)

Unzip the file that downloaded and set up atom. Now Launch it

<img align="center" width="400" alt="Unziping atom" src="https://user-images.githubusercontent.com/65277548/125181957-25d4e300-e24d-11eb-95c3-94947a401bf7.png">

#### Lets get to know atom

<img align="center" width="500" alt="Atom start menu" src="https://user-images.githubusercontent.com/65277548/125182038-d80caa80-e24d-11eb-96f1-e559cbb9943e.png">

## Making our Webpage
HTML is the language that all webpages use to display text and images. Anyone can use it to tell things about themselves.

First download my [starter kit](https://github.com/Daniel4-Scratch/Learn-html/releases). Unzip the file. Hop into Atom then click "Open Project" then select the "Starter Kit Folder", now press open.

<img width="470" alt="Atom Open Project" src="https://user-images.githubusercontent.com/65277548/125182917-7cdeb600-e255-11eb-8fbd-6c299ffbfd92.png"><img width="470" alt="File Select Starter Kit" src="https://user-images.githubusercontent.com/65277548/125183056-92081480-e256-11eb-9f17-f32b202934de.png">

Your computer screen should look like this:

<img width="450" alt="Atom Open Project" src="https://user-images.githubusercontent.com/65277548/125183297-ce3c7480-e258-11eb-9368-69e2517e6296.png">

Make sure on the left hand side is a bar and it has your folder for your website. Click on the folder the click on "index.html".

### About the tags
This code is the code for your webpage. There is a `<!DOCTYPE html>` at the top of the text, this tells the computer that this file is a html website. Under the doctype is `<html>` with a bunch of code in it and ends in `</html>`. `<html></html>` is the code for the website and it holds code in-between the tags; `<head></head>` and `<body></body>`. The head tag is a container for metadata, like; The webpage titles, favicons and information to tell search engines what the website is about. The body tag is container for the content to display on the website. Like your text, images and links.

## Previewing your web page
You should be on the file index.html for this. In the bottom left corner is the name of the file that we are currently editing. If you click that file name it should copy the file directory path to your clipboard. You will need to paste this into a web browser.

<img width="400" alt="Atom File Path" src="https://user-images.githubusercontent.com/65277548/125184130-a3551f00-e25e-11eb-9122-4bab0d737a9a.png">.

Open your web browser and paste the link into the url bar. But nothing appears! That's because we haven't written any text. Keep this file directory link for later so you can test your webpage.

## Adding Content
In-between the body tags add `<p> </p>`. P is short paragraph, so your adding a paragraph into your webpage. Type something in-between the p tags. Then hit command ⌘ + S to save the file. The get the file directory path and paste it into your broswer tada!. What it should look like.

<img width="490" alt="Website" src="https://user-images.githubusercontent.com/65277548/125184507-c59c6c00-e261-11eb-9bc9-680e17e1efc4.png">

And your code should look like
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
  </head>
  <body>
    <p>
      Hello this is my webpage
    </p>
  </body>
</html>

```



