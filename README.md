# magicbiff
Multi-color Ascii GraphICs from Binary Image File Formats

I linked my image-to-text web application (which I have now dubbed [MAGICBIFF](https://www.killsignal.net/img2txt/ascii-art.html)), with explanation of why I made yet another such app along with examples of what it does at the preceding link) in a comment on a [HN thread about another ascii art tool](https://news.ycombinator.com/item?id=38329736) and had a couple of folks reply and ask if the source was available.

Since it runs entirely in the browser, the source (HTML/CSS/JS) is of course available as it is sent over https when requested and can be seen as plain text via view-source or the Inspector.   It then occurred to me that even so, perhaps they wanted to be able to be notified of changes, fork, submit PR, etc.. all the stuff that  site like GitHub makes easily available. 

So, as promised, I have cleaned the code up at least to the point where it doesn't embarrass me to associate it with my name, and here you shall find it. I have a black&white version and a color version (this is the color version at the moment) that I'll want to consolidate, because there are some tradeoffs between "resolution" and colorization that some may find interesting. 

# Example live web deployment link 
[magicbiff](https://www.killsignal.net/magicbiff)

# Installation/Configuration
Short version: clone this repo. Wherever you place the directory, just access the index.html file with a web browser. (The directory URI is probably enough, without the "index.html" filename if being served via a webserver.)

Overly-verbose version: Placing the index.html file in the location of your choosing (e.g., your local filesystem or on a public webserver) given the filename of your choice and opening it in a modern browser that supports CSS, JS, and the Canvas element should be all that is needed to run the app in its current state exactly as the one on [my site](https://www.killsignal.net/magicbiff) works. Of course you are free to rename any of the files and use as-is, or as example (or not-at-all) the [comparisons_and_examples](https://www.killsignal.net/magicbiff/comparisons_and_examples.html) page and images.    

# Additional info
I have recently uploaded the original b&w version of the tool since I think the vertical line spacing trick has its own value, complementing the current color version. While it is not possible to use both the drop shadow bgcolor trick and the vertical space squishing trick together, a version that uses colored characters and the vertical spacing effect together should be pretty easy. Until then, it is usable on its own.  
