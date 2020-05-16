# UQ-LaTeX
A repository for anything LaTeX related (except assessment) to a course at The University of Queensland. Disclaimer that a lot of the current notes at the time of writing is unfinished because... I have no excuse.

## Motivation
<img src = "https://upload.wikimedia.org/wikipedia/commons/9/92/LaTeX_logo.svg" width="60" height="25" /> is cool. I began tinkering with it in my senior years of High School. There is still a lot for me to learn and poke at but nonetheless I basically do everything in some form of LaTeX. I know that many other students share the same feelings for this typesetting language and so I decided to make my own collective repository. 

## How to do *stuff*
Well it depends. If you want to just look at the `.pdf` files, almost *all* modern computers will be able to handle that. But if you really need a pdf viewer, [Adobe Acrobat Reader](https://get.adobe.com/uk/reader/otherversions/ ) is a goto for Windows. (If you are using Linux then you should know how to get a pdf viewer...)

*However*, if you want to *edit* the files, things get fun.


Lets start with your operating system, if you don't care about running it on your OS, [Overleaf](https://overleaf.com) is a web-based LaTeX document editor and is pretty fantasitc.

### Windows
If you are running Windows, I reccomend downloading [MikTeX](https://miktex.org/download). This is just because it has quite a nice friendly looking interface for packages etc. [MiKTeX](https://miktex.org/download) simply compiles what you have written. So you need something to *write it in*. I reccomend [TeXWorks](http://www.tug.org/texworks/) or [TeXStudio](https://www.texstudio.org/) for writing. They have the ability to build and compile with the click of a button and that is incredibly handy when starting out.

### MacOS
Honestly I am not too familiar with MacOS but I know that you can get an almost identical setup to Windows with [MiKTeX](https://miktex.org/download) and [TeXStudio](https://www.texstudio.org/).

### Linux
The fun part.
<img src="https://i.kym-cdn.com/entries/icons/original/000/030/904/Screenshot_10.jpg" />


There are a multitude of ways to do things with LaTeX on Linux. But for now I will just begin with the most simple configuration... I personally quite like TeXLive, its simple and it has everything you need. For writing, you can really just use any text editor you like and compile within the terminal. 

*If you want* you can use [TeXWorks](http://www.tug.org/texworks/) or [TeXStudio](https://www.texstudio.org/), particularly the latter. They have ports for almost all mainstream Linux distros. (*pssttt...* you can even use [MiKTeX](https://miktex.org/download) on Linux too... if you really want to...).

...

Ok now that they are gone we can get into the nitty gritty. [TeXLive](https://www.tug.org/texlive/) is available on most Linux distros.

On Ubuntu we can install it with the command:
``` sh
sudo apt install texlive-full
```
Now for writing; like I said before, it really doesn't matter where you write it in because in the end its just *text*. So lets play around with configurations that I know atleast.

#### Vim
[Vim](https://vim.org) is a console based text-editor built off of the old-school [Vi](https://en.wikipedia.org/wiki/Vi). **Disclaimer:** if you don't already use Vim, the learning curve is slightly high but the payoff is fun. 

Utilizing Vim's plugin system, there are many handy tools for writing TeX. First and foremost is [VimTex](https://github.com/lervag/vimtex). A pretty neat tool that can allow you to compile your document within Vim and have it updated in real time. 

You can basically do all you need to do with that, but if you want to play around with **snippets** then I reccomend the plugin [UltiSnips](https://github.com/SirVer/ultisnips). 

I may put this in a different place because there is a lot more left to do and say but this file is getting slightly long.
