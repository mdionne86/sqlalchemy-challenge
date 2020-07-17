# sqlalchemy-challenge
## Climate Analysis
The first portion was relatively straight forward. Using SQLAlchemy automap function really makes importing a db simple. After that, I just needed to create the DF I was going to work with, and then create the plots. I'm really glad the started code included the hint to use stacked=False. I would have never thought to try that, but I really love the result!

## Flask App
This was a bit of a challenge. I went through a few iterations and ended up starting over as I was having issues. Eventually I realized I had overlooked session.close(), and from there things worked much better.
 