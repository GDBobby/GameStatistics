# Game Map Statistics
 
The plan is to get a systematic approach to map design. 


Currently, all I have is a function that checks amount of hits to defeat a monster given a damage range, and a wrapper function that converts that into perfect experience per minute.
Given the perfect experience per minute given a monster, and a map that only has that one monster, I can collect real world data for actual efficiency, then use the ratio between perfect monster exp and real mosnter efficiency on a given map to calculate map efficiency.

There's a few things that complicate this, 
1. The more takes it takes to defeat a monster, the less walking a player does, thus, the map design matters less.
 For example, say a map has 5 monsters 2 seconds apart, and they take 100 hits to defeat and I attack once per second. I will spend 105 seconds per monster, at around 95% efficiency.
 On the contrary, say I have monster that takes 3 hits to defeat, and they're, on average, one second apart. Now I spend 4 seconds per monster, at 75% efficiency.

2. Class balancing changes map sizes. A character with a teleport/super jump is playing a smaller map than one that isn't.
   This usually isn't something that's addressed. I've only seen it addressed in Starcraft pro maps.
   Old just gave mages the ultimate ability that effectively makes the map tiny, and gave them laughable boss damage in return.
   Modern maplestory gives everyone a super jump.

3. 3D maps are going to be much more complex, particularly with terrain that affects player movement, like swimming. Ladders in 2d maps will also make this a little more complex, and give the player a little more opportunity to express some skill in the most mundane ways.

Why would this even matter?
Well, your average MMO gamer is always looking for the best spot to grind at. If spot A is 1% better than spot B, 90% of your player base will spend their time at spot B.
However, if half your character classes are better at spot B, and the other half are better at spot A, you now have a 50/50 split.

Isn't it a little tedious to grind out this information?
Sure. I would personally make a headless client and let some bots run at it for a few hours. But, I'm personally against the MMO genre as it stands, and I think the age of bots replacing humans in MMOs is nigh.
With that aside, I think a developer would spend five minute per map collecting average data, more time to be more accurate of course. Then they have real data they can act on, rather than waiting weeks or months to see heatmaps that merely portray player preferences. Combining this data with a heatmap may provide more valuable insight, i.e. why would players prefer a map that is not the most optimal.

I collected all data on old school maplestory. All formulas are from there, and any rounding errors in those formulas are intentional to accurately reflect old school maplestory.
I won't plug the server, many of these old school maplestorys are of questionable legality and POTENTIALLLY contain security risk.
