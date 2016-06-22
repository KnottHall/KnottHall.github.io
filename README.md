# JustinGarrard.github.io
My repo for the Knott Hall Website

If you are going to add a new field to the dropdown bar, don't forget to add it across all the pages!
  Also, don't use construction.html as a "placeholder" or alter it in anyway.  If you create a page without finished content, better of copying construction.html code to your page so that you don't have to go back and change links from construction.html to the new page once it's finished. I recognize this makes development weird once the site is live, but that's a bridge we'll cross when we need to (I'm thinking version control through Git).
  construction.html contains all the original unaltered code that will make the persistent banners and footers work, need basically all the code there except for the "Whoops, Webmaster at work...." stuff.
  
I don't know how to web develop.
  I did it though and here's how I "managed" it. First, I found some html and css templates online from ZURB's Foundation website (Bless them!). I did some native development first to get a feel for messing around with html and css.  Then I worked on building a homepage and a unique template for the rest of my website's pages.  Benefits of doing all this locally: it was quick so the development moved along quickly.  Consequences of doing all this locally: all my 'href's had to be re-done once I launched the pages I had built to an internet host.  Every link to a page you create has to be re-written once you launch to the internet.  I created too many pages.  Instead would recommend the one homepage and strictly one template (maybe an "under construction" warning) for all the other pages you will want online.  Then deploy, and change a couple links, then build out the rest; rather than stepping through 12 html files and changing the same links in all of them.
  
Ideally, I can use <!--#include virtual="file.html"--> to eliminate having header and footer code in every file, but I think I'm referencing the files wrong in index.html
