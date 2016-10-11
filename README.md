# NFL Analysis

Machine learning has had many impacts across multiple fields and industries in at least the past 10 years. In sports, statistics began playing a large role in team design and recruitment, especially after the success of the Oakland A's in the early 2000's using the methods outlined in the book and movie *Money Ball*. To read more about the use of statistics in Baseball, see [Sabremetrics in wikipedia](https://en.wikipedia.org/wiki/Sabermetrics).

I happen to live under a rock, so I hadn't actually seen *Money Ball* until very recently on a flight-- and, wow, what an awesome movie! I was quite inspired after watching it and thought by this time probably all kinds of stats are being used to guide business and sports decisions in all major sports. I'm a huge AI and machine learning (intelligence) aficionado, and I've been a lifelong sufferer as a Miami Dolphins fan, so I decided why not check out some NFL datasets and see if one can make predictions on the success rate of certain players? Maybe the poor Dolphins could be better advised on who to draft.

## But how does one exactly define success at the NFL level?

I'm not sure. But one metric which is difficult to argue against is whether or not someone's made it to the Probowl. It may not be perfect, and it may not work at all, but let's give it a shot and see where it takes us.

To get started, first thing we need is data. After looking around the web a bit, I found that http://www.pro-football-reference.com/ has some pretty easily accessible (and machine readable) table data available on the Combine results and also historic probowl data.

So the question is pretty clear, could we predict, based on Combine metrics alone, which player, by position will most likely become a probowler? Let's find out..
