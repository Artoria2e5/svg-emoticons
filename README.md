svg-emoticons
=============

A collection of svg emoticons that can be used in IM chats and so on. 

Many users like me love collecting interesting (or just _moe_) emotocons so they can use
it over chats. However, many of those chats are quite low-quality (as in image quality), 
and doing the fork-and-recompress process can make a huge decrease on the image qualities.

This repository mainly collect vectorized versions of emotocons, redrawn mainly by me.

Why svg?
- SVG is a great open format for vector images.
- SVG consists of XML code, and editing it creates a lot of diff — that is absolutely the
  best way to write huge quanlities of code. (Just Kidding.)

How to use
----------

Sometimes [Releases](https://github.com/Arthur2e5/svg-emotocons/Releases) contain some Bitmaps
or Optimized PNGs. Check them out.

Use [Download Zip](https://github.com/Arthur2e5/svg-emotocons/archive/master.zip)
on the right side of the page to get a HEAD snapshot containing all the SVGs; or you can wander
around the tree and find the one you want to download.

Ordinary users: 
- Download and install Inkscape(https://inkscape.org). If you are using Linux, try to check
  it out in your distribution's software repository. 
- Considering creating a white rectangle as the background before exporting.
- **File -> Export as PNG.** Choose the suitable file size for you.
- If you are not happy with the file size of the 24-bit PNG, read 
  [This thread (Chinese)](https://www.equn.com/forum/forum.php?mod=viewthread&tid=38948) to get
  instructions on optimizing the file size. [RIOT](http://luci.criosweb.ro/riot/) is a nice
  choise if you use Windows. Saving as 16- to 256-color, max-compressed PNG is recommended.

Webmasters:
- If you are not worried about size or compatibility, just use the SVGs.
- If you are facing old browsers, export it to bitmap just like what ordinary users do.
- For better size or compatibility, try **File -> Save As -> Optimized SVG** in Inkscape.
  Choose the options you want to use.

COPYING
-------

See the files' metadata for Copyright information. 

Since those emotocons are mainly used for IM chats, always claiming the author(s) may be impossible.
Here I reduce this limit so it works only on people who fork those SVG images.

CONTRIBUTING
------------

Simply fork & PR. Don't forget to add your copyright info to the Dublin Core metadata.

You may want to optimize the SVGs before making a PR since it can help reduce some unnecessary digits and/or
style attributes.
