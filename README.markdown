# Slide Show (S9) Template Pack - impress.js

The [impress.js](https://github.com/bartaz/impress.js) package by Bartek Szopka (aka bartaz)
bundled up into a Slide Show (S9) template pack.

Note, the package is configured to use the following headers in `slides.html.erb`:

    author: Your Name Here
    title: Your Slide Show Title Here
 
## Try It Yourself - How To Use the Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ slideshow -f impress.js

Or as an alternative clone the template pack using `git`. Issue the commands:

    $ cd ~/.slideshow/templates
    $ git clone git://github.com/geraldb/slideshow-impress.js.git

To check if the new template got installed, use the `-l/--list` switch/command:

    $ slideshow -l

Listing something like:

    Installed templates include:
       impress.js.txt (/home/gerald/.slideshow/templates/impress.js/impress.js.txt)

Now you're ready to use it using the `-t/--template` switch. Example:

    $ slideshow -t impress.js.txt sample

That's it. 

## Samples

See the samples in Markdown in the repo. Example:

    !SLIDE
    
    Slide One
    
    
    !SLIDE y=600
    
    Slide Two
    
    
    !SLIDE x=1200 y=600 rotate=180
    
    Slide Three
    
    
    !SLIDE x=1200 scale=0.5
    
    Slide Four


## Questions? Comments?

Questions? Comments?
Send them along to the [Free Web Slide Show Alternatives (S5, S6, S9, Slidy And Friends) Forum/Mailing List](http://groups.google.com/group/webslideshow).
Thanks!

## What's Slide Show (S9)?

A Ruby gem that lets you create slide shows and author slides in plain text
using a wiki-style markup language that's easy-to-write and easy-to-read.
More [Slide Show (S9) Project Site &raquo;](http://slideshow.rubyforge.org)