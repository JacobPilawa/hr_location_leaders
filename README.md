# HR Location Leaders

While watching the [Dodgers smoke the Yankees](https://baseballsavant.mlb.com/gamefeed?gamePk=777698), I came across [a cool tweet](https://x.com/SamEhrlich/status/1928963541962240107) from  Sam Ehrlich (who himself came across [a cool tweet](https://x.com/CrumpledJumper/status/1928928847959044348) from Todd Whitehead) showing the MLB Zone Hit Leaders by batting stance. I was curious about homerun location leaders, so I threw together this quick notebook to satisfy my curiosity (and to try to more actively use Github). 

I query statcast for homeruns from the start of the season to today, divide the outfield into a number of sectors, and find the HR leaders in each of these sectors. Extremely simple (and not guaranteed to be pretty), but sort of interesting to see which hitters are hitting where this season. It sort of makes sense when you see who is at the top of each sector (from the games I've seen this season), but always fun to see it spelled out in data!

Here's a sample output (on 5/31/25), using 5 sectors:

![output](example_ouput/hrs_through_may.png)
