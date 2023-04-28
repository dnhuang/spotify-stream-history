# spotify-stream-history

Project I started on 4/27/2023.

Discovered from [this article](https://towardsdatascience.com/get-your-spotify-streaming-history-with-python-d5a208bbcbd3#:~:text=Getting%20the%20data,option%20to%20request%20your%20data.) that I could actually *request* my Spotify Data. I was curious and wanted to see how my taste in music had changed the past year, so that's where the motivation for this short project came from.

Of the various `.json` files provided by Spotify, really only the `StreamingHistory#.json` files were useful, all the other ones were either logistical information or sensitive, private information (address, payment info, etc.), so I left those out (and there's not much to analyze either).

The data I was given ranged from $4/21/2022$ to $4/20/2023$. I believe the data were within this timeframe because they were dependent on the day I requested the data; I asked for the data in on $4/18/2023$ and Spotify finished compiling it on $4/22/2023$. Yes, it took me another $5$ days to finally to get around to look at it.

I had some issues embedding the a video of one of my functions running in the `analysis.ipynb`, so I ended up settling with a `.gif` and embedding the video below in this `README.md`.

https://user-images.githubusercontent.com/40350729/235043526-b3f69c94-0f13-4691-8472-f6c339732553.mov

Overall, I thought my listening behavior was quite interesting, transitioning from a k-r&b fan, to a full blow post-malone fanatic, and slowly transitioning back to Kpop with a sprinkle of some Jpop. I believe a lot of these transitions can be explained by the media I was consuming at the time (Jdrama/Kdrama/anime), and I may consider sharing that in `analysis.ipynb` one day, but for now, just code and some of comments on what I see.
