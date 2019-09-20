---
title: "Devlog One: Messing things up" 
summary: A detailed account of how this site almost wasn't
date: "2019-09-12"

reading_time: true  # Show estimated reading time?
share: true  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: ""
---

# A detailed account of how this site almost wasn't


This site, in theory, should have been easy-peasy to put together. It is based off of a template that really only requires you to fill in the blanks. In practice, things didn't go quite so smoothly for me. During the class when we went through the site building process, I latched onto one thing that was mentioned: the "#" makes items invisible. That, however, is only part of what was actually said, and this incident is a prime example of why context matters. 

When I got home after class and sat down to make my site, I went into the index in my repository and went wild throwing #'s infront of any info I didn't want to share on my site, like my social media links, publications, and location information. At the same time, I was also updating my bio and some of the more simple details, like my university affiliation. I saved it my changes, flipped to my netlify deploy log, and watched as the error messages started to roll in. Because of the one piece of info I remembered in class, "# makes items invisible," I approached fixing the problem having already decided the one thing it couldn't be were all the # keys I sprinkled in. So when it directed my to an error on the line of my bio, I somehow thought the program must have disagreed with how I described myself and that was the source of the error. This is something I seriously believed, enough to change my bio and redeploy multiple times. In hindsight, this is a hilarious line of logic. 

Once I realized (about 8 deploys later) that the changes I was making weren't useful, I put into action some of Shawn's suggestions for how to move forward:

1. **Close your machine**. When you get frustrated and can't figure things out, sometimes the best way forward is to walk away and give it some space. 
2. **Read the instructions** that the creator of the template put together exactly for situations like this, and google a heck-ton to fill in the blanks. There is a great guide for [getting started](https://sourcethemes.com/academic/docs/) with the academic template.  
3. Check the **deploy log** and see where the error is. Note: You should refer to the most recent deploy failure rather than than scrolling back to the first one. 
4. **Investigate the code** in github that your deploy log identified as the source of the error. Refer to the history of the file on github to see exactly what was changed and how it differs from the previous iteration (which was an iteration that worked)
5. If you're still confused, **reach out for help**. Email Shawn to take a look. 

Shawn was able to come in, take a look at my repository, and push changes to me that I could then merge/pull into my own erroneous code. 

After this first blunder, I learned to really let go of what I thought I knew to be facts and operate on the basis of not knowing anything and being open to seeing everything as a potential problem or solution. It was my stubborn hang-up on the idea that the #'s were right even if the error code was pointing to their line that caused me to miss the obvious. 

Moving forward, everything has been going a lot more smoothly, and I've employed another strategy for my work, specifically for when I've tried to build something where an existing template in my repository is missing: *copy and paste* it from someone else, like Shawn! If people have their code open and available for sharing, take advantage of it! No need to reinvent the wheel when it's already organized and functioning perfectly fine just a few clicks away. 

All in all, it was a rough start, but things are finally rolling. 

