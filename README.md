# magicbiff
Multi-color Ascii GraphICs from Binary Image File Formats

I linked my image-to-text web application (which I have now dubbed [MAGICBIFF](https://www.killsignal.net/img2txt/ascii-art.html), with explanation of why I made yet another such app along with examples of what it does at the preceding link) in a comment on a [HN thread about another ascii art tool](https://news.ycombinator.com/item?id=38329736) and had a couple of folks reply and ask if the source was available.

Since it runs entirely in the browser, the source (HTML/CSS/JS) is of course available as it is sent over https when requested and can be seen as plain text via view-source or the Inspector.   It then occurred to me that even so, perhaps they wanted to be able to be notified of changes, fork, submit PR, etc.. all the stuff that  site like GitHub makes easily available. 

So, as promised, I have cleaned the code up at least to the point where it doesn't embarrass me to deliberately associate it with my name, and here you shall find it. I have a blac&white version and a color version that I'll want to consolidate, and I will probably put the documentation page (linked at the top of this README) and its image assets in this repo as well ut here is a first commit.

# Configuration
Placing the single html file in the location of your choosing (e.g., your local filesystem or on a public webserver) given the filename of your choice and opening it in a modern browser that supports CSS, JS, and the Canvas element should be all that is needed to run the app in its current state exactly as the one on [my site](https://www.killsignal.net/img2txt/cimg.html) works. Let me know if you have any issues.   
