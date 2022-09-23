# casual-markdown-cv

First of all, I prefer use **RAW github markdown** as resume. Here is a sample template: [resume.md](resume.md)

If wanna a little better, may add a little code, and transform to [resume.html](resume.html).  
here is the [layout](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume.html) (self-host at github).

```
<!DOCTYPE html>
<title>Resume</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/casualwriter/casual-markdown/dist/casual-markdown.css">
<script src="https://cdn.jsdelivr.net/gh/casualwriter/casual-markdown/dist/casual-markdown.js"></script>
<style>  
  body { font-family:verdana,arial; line-height:1.5; margin:auto; padding:3px; max-width:1024px; display:none}
  h1  { font-size:200%; padding:12px; border:1px solid lightgrey; background:#f0f0f0;  }
  h2  { border-bottom:1px solid grey; padding:6px; }
</style>
<body onload="document.body.innerHTML=md.html(document.body.innerHTML); document.body.style.display='block'">

... resume content in markdown format ...

```

It is a single html file may run from WEB or LOCAL, quite handy to share by url or print to PDF.

If still not good enough, may try other themes

* [resume-dark.html](resume-dark.html) // dark theme, font=verdana [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume-dark.html)
* [resume-warm.html](resume-warm.html) // warm theme, font=calibri [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume-warm.html)
* [resume-blue.html](resume-blue.html) // blue theme, font=arial [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume-blue.html)

Sorry for my poor UI design, if still not good enough, please fork this repo and make your own.

## Usage

just fork [this repo](https://github.com/casualwriter/casual-markdown-cv), and choose a reusme template to revise.

by the way, this template basically use markdown as web page, which not limit for resume purpose. for example,

* [project-plan.html](project-plan.html) // project plan [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/project-plan.html)
* [document.html](document.html) // documentation [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/document.html)


## Credit

the template is inspired by https://github.com/youngyangyang04/Markdown-Resume-Template

(2022/09/23, initial verison)







