---
layout: post
title:  "Writing a GEM"
date:   2016-06-12 20:57:23 +0000
---

![](https://raw.githubusercontent.com/rnhutsko/rnhutsko.github.io/master/images/ferrari%20laferrari.jpg)

Working through the Learn curriculum for Ruby Object Oriented programing has had moments of intense concentration, occasional triumphs and every now and then total frustration.  The code-alongs and the coding labs were challenging and informative but I never had the feeling of not knowing where to start.  That is until I came to the writing a GEM project.  I had to re-read the project description several times.  I kept thinking "I must be missing something here".  But no I was not.  I just had no clue what to do.

Then I watched the video that Avi Flombaum posted on how to create a gem.  This was inspiring not just because it made it easier to think about what I wanted to do from a "big picture" point of view but also because Avi said something in the video that cannot be over-emphasised.  Avi made a point to always “do what you can do”.   His method of writing out what he wanted the gem to do in a note.me file was a key insight.  Beginning with the end in mind.  This one exercise embodied this philosophy beautifully.  

After watching Avi I sat down used the bundle gem tool.  I had the idea to scrape Cars.com’s website and return the first 50 used cars for sale.  The bundle tool was incredible.  Made the gem structure super easy.  From there writing the notes file allowed me to think in a step by step way on how the output would look.

It was really easy to then create the skeleton of the user interface.  It seemed as though I went from pure panic on how to do this lab to “oh, I got this” in no time.  This was very encouraging and I really needed that encouragement.  The next part of the development was to begin scraping the Cars.com site.  And I ran hard into a brick wall.

That brick wall is called Angular and Java populated websites.  It seems there is a way to do this but as I do not know any Angular and very limited Java this site was a bridge too far.  It would have been easy to despair at this point.  My whole idea was scraping this site.  Instead of despairing the thought came to me “do what you can do”.  I looked around on some local car dealer sites until I found one that had a pretty basic styled site.  I settled on Hall Automotive’s site.  From there I was quickly able to flesh out the logic to scrape their site.  In fact the site’s structure is actually making the next part of this project pretty easy to conceptualize.  

So if you are getting ready to create a gem for this project or start any project, coding or otherwise, begin with the end in mid and do what you can do.  Move forward step by step and eventually you will build something cool..  
