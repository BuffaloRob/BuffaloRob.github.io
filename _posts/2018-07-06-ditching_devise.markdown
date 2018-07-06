---
layout: post
title:      "Ditching Devise"
date:       2018-07-06 14:09:54 +0000
permalink:  ditching_devise
---


This one has taken me way too long to complete, it's been 4 months since the last project I completed. I should've finished this in no more than half that amount of time. The silver lining is that I do feel like I will probably save myself some time in the future after having wasted so much time on this project. I needed to learn when to let go and change what I'm doing, I needed to remember one of my favorite quotes from Einstein, "Insanity is doing the same thing over and over again, but expecting different results." 
I was pretty close to completing this project when I all of a sudden couldn't login to my app anymore using devise the way I had hundreds of times before. I could login using OAuth for Facebook but it just bothered me. I attributed it to me trying to update the rails version I was using on the project, even though I was pretty certain that wasn't it. I also wanted to redo some things on my old app that I was building off of so I took the plunge after weeks of troubleshooting my log in issues and decided to redo the project from the ground up with a more flexible schema (the original was 'forced into a box' because of the constraints on the last project).
Everything was going great with my new project and I finsihed up the Jquery part in no time, the morning after I finished my project I went to login and it gave me the same problem as the old project where the login screen would just hang. I was more resolved than every to fix the problem, and I came pretty close to a real solution when I realized that I could just use something besides devise. After some googling and looking around I found Clearance and decided to roll with it. In a few short hours I had Devise removed and Clearance up and running with no issues. If that was my first instinct then I would have been done weeks/months ago, I'll just have to look at it as a learning experience. Now I'm just cleaning some things up and I should have my code reviewed sometime next week, I'm really looking forward to the last part of my Flatiron journey and more importantly, wrapping this up so I can move on and become a professional. 

