# casual-markdown-cv

[casual-markdown-cv](https://github.com/casualwriter/casual-markdown-cv) is a minimal way to create markdown resume and host on github (or other static web hosting)

It is quite annoying to maintain resume in multiple format, MS Word, PDF, TXT as well as wanna to have an HTML format online. 

found Github markdown editor is very handy to draft a nice resume. Here is a sample template: [resume.md](https://github.com/casualwriter/casual-markdown-cv/blob/main/resume.md), however, it is not good enough to send to recruiter.

so, add a little code, and transform to online resume with nice [layout](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume.html) (self-host at github).

then may print it to PDF format, and share by url. (for github, it can accessed by raw.githack.com natually)

## Themes

The following themes are available now

* [resume.html](resume.html)  // default theme  [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume.html)
* [resume-qrcode.html](resume-qrcode.html) // show QR code of URL [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume-qrcode.html)
* [resume-dark.html](resume-dark.html) // dark theme, font=verdana [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume-dark.html)
* [resume-warm.html](resume-warm.html) // warm theme, font=calibri [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume-warm.html)
* [resume-blue.html](resume-blue.html) // blue theme, font=arial [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume-blue.html)
* [resume-web.html](resume-web.html) // sample for web developer [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume-web.html)

Sorry for my poor UI design, if still not good enough, please fork this repo and make your own.

## Usage

just fork [this repo](https://github.com/casualwriter/casual-markdown-cv), and choose a resume template to revise.
then check html layout by https://raw.githack.com/YOUR-REPO-NAME/casual-markdown-cv/main/resume.html

by the way, this template basically use markdown as web page, which not limit for resume purpose. for example,

* [project-plan.html](project-plan.html) // project plan [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/project-plan.html)
* [document.html](document.html) // documentation [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/document.html)

## How it works

The code is simple, just add below (11 lines) as the header. It will convert the markdown content to HTML web page.

```
<!DOCTYPE html>
<title>Resume</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/casualwriter/casual-markdown/dist/casual-markdown.css">
<script src="https://cdn.jsdelivr.net/gh/casualwriter/casual-markdown/dist/casual-markdown.js"></script>
<style>  
  body { line-height:1.5; margin:auto; padding:3px; max-width:1024px; display:none; FONT-FAMILY:"Segoe UI",ARIAL; }
  h1  { font-size:200%; padding:16px; border:1px solid lightgrey; BACKGROUND:#f0f0f0; }
  h2  { border-bottom:1px solid grey; padding:2px }
</style>
<body onload="document.body.innerHTML=md.html(document.body.innerHTML); document.body.style.display='block';">
<!--======= COPY ABOVE CODE AS HEADER, THEN FOLLOW WITH RESUME CONTENT IN MARKDOWN FORMAT =========-->

<img style="float:right;border-radius:50%;width:70px;padding:6px" src="avatar-man.jpg" />

<span style="float:right;padding:6px"> 
  someone@email.com <br> mobile: +852 xxxxxxxx <br> Nationality: Chinese
</span>

# Casualwriter

```

## Credit

* inspired by https://github.com/youngyangyang04/Markdown-Resume-Template
* thanks and reference to CV samples, https://www.resumewriter.hk/blog/cv-samples/

(Sept 2022)







