---
layout: project
title:  "Lawn Tennis"
date:   2015-04-23 12:00:00
author: Jack Harrison
downloads:
- Windows: https://www.dropbox.com/s/7zqmtu3xu5k9pwk/LawnTennis%20%28Windows%29.zip?dl=0
- Mac: https://www.dropbox.com/s/xzl2eq9x3jn15ah/LawnTennis%20%28Mac%29.zip?dl=0
categories:
- project
img: 01-lawn-tennis.png
carousel:
- 01-lawn-tennis-01.png
- 01-lawn-tennis-02.png
tagged: Game, Clone, Learning
website: https://github.com/jhrrsn/learninggames
---
####LAWN TENNIS
This was the first clone I put together - somewhat fittingly, as Pong is one of the earliest video games. Unity makes things like detecting collisions and applying forces to objects pretty straightforward, but I had to make some physics fudges to ensure that i) the game was fun and ii) the game didn't reach a stalemate.

On the first point, I increased the ball velocity with every hit to increase tension as the rally continued. I also affected the bounce angle depending on where on the paddle the ball was hit, again to make things more frantic over time. On the second point, I had to introduce a number of fallback statements that triggered if, for example, the ball was stuck going back & forth in a straight line at the top or bottom of the screen. All in all though, this was a simple & fun game to make - especially with the classy theming!
