---
title: "Devlog Three: A Second Pair of Eyes"  
summary: tldr; never underestimate the value of "a second pair of eyes" 
date: "2019-10-09"

reading_time: true  # Show estimated reading time?
share: true  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: "DevlogThreeBanner.png"

---
*I began writing this devlog over a week ago, but (as is always the case mid-semester) I began losing track of things and it fell to the wayside. With this in mind, I am going to keep things short and bitter, building on what I started to write oh so many days ago:*

Two days ago, while I was creating my [Guerrilla DH Project: The First Class Check-In](https://marissafoley.netlify.com/post/10-07-2019-presentationdevlog/) post about a dh visual art project, I got tangled in what felt like another *unsolvable* problem. As a visual art project, including images in the post was essential, but I could not for the life of me figure out how to do so! 

I tried several different pieces of code to try that I found through a simple google search. Googling is always my step one. This search led my to a github forum that suggested: 
A. `[my_image](files/my_image.png)`
B. `<img src="myimage.png">`

So, I popped those in as-is and merely changed the "my image" name to whatever each of my images were called... Error. But not the kind of error where netlify flashes the big red **failure** button for you (thank goodness - I always take a real ego hit when that happens). Instead, my images were merely just appearing as little thumbnail stand-ins with the alternative text listed in their place. 

My next step is to try adding the full file path in, rather than just listing it as "files." This makes a ton of sense to me because my images aren't even kept in a folder titled "files." I adjust these with the full file path, and smugly flip to my site to see the images finally appear. Error, again. 

My third step in this process: close my computer. This can be solved another day, in a less frustrated state. 

*I should note here that I was attempting to throw this post with images together late at night (when all my most pressing work is done) after spending several hours working on another large project. There is something to be said for timing and awareness in all of this. 

Step four brings us into the classroom the next morning. Here, I ask my professor for help. After some more experimenting with different file names and moving stuff around, we realize it isn't the whole file path or no file path that is needed - instead, the *thing* just needs to know the folder the image is in, but no path further back beyond that needs to be included. I make my adjustments and BAM, two out of three images are up and running. 

This seems like a big win, but... TWO OUT OF THREE? C'MON! Are you kidding me? After all that? I copy and paste from the working lines - trying, retrying, reretrying, again and again. 10 minutes of me tinkering with this issue pass. Nothing.

At this point our time in the classroom is up. People are filing out, and my confusion and frustration begings multiplying all over again. Then Shawn walks over to my machine, takes a 2 second look, and sees I sloppily saved my file name with a   `-` instead of an `_` as I had done with all the others. One simple character was the issue. I made the quick fix and voila, there was my post, images and all, and all the images. 

So, moral of the story: the value of a second pair of eyes should never be underestimated as the simplest mistakes are often the hardest to spot. 

Other moral: Working after midnight often results in simple, sloppy mistakes. 
