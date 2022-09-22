# casual-markdown-cv

First, I prefer use **RAW github markdown** as resume. Here is a template: [resume.md](resume.md)

If want a little better, try to add a little code, and transform to [resume.html](resume.html) 

```
<!DOCTYPE html>
<title>Resume</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/casualwriter/casual-markdown/dist/casual-markdown.css">
<script src="https://cdn.jsdelivr.net/gh/casualwriter/casual-markdown/dist/casual-markdown.js"></script>
<style>  
  body { font-family:Verdana,sans-serif; line-height:1.5; margin:auto; max-width:1024px; display:none }
  h1  { font-size:200%; background:#f0f0f0; padding:12px }
  h2  { border-bottom:1px solid grey; padding:6px; }
</style>
<body onload="document.body.innerHTML=md.html(document.body.innerHTML); document.body.style.display='block'">

.... resume content in markdown format ....

```
It is a single html file may run from web or local. check its [layout by github-self-host](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume.html)

If still not good enough, try other themes

* [resume-dark.html](resume-dark.html) [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume-dark.html)
* [resume-warm.html](resume-warm.html) [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume-warm.html)
* [resume-blue.html](resume-blue.html) [(preview)](https://raw.githack.com/casualwriter/casual-markdown-cv/main/resume-blue.html)

Sorry for my poor UI design, if still not good enough, folk this repo and make your own.

## Usage

just folk [this repo](https://github.com/casualwriter/casual-markdown-cv), and choose a reusme template to revise.


## Modification History

* 2022/09/22 initial version




