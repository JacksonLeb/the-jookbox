# The Jookbox: Jukebox meets Youtube Music Streaming

## The Idea
So I am sure many of you are familiar with youtube music streaming accounts such as "Lo-Fi Beats to Work and Study To" and "Coding Music Livestream". These are a fun way to listen, work and study with tons of people around the world at the same time. This also is a way to listen to a curated playlist, so you don't have to focus on which song to listen to next. However, what if you want to have a say in what is being played next? Is it really a cohesive community of music listeners if the listeners can't even decide on what they are listening to? What if you could utliize the concept of a jukebox, a central music device that plays songs decided by a paying listener, to other youtube music livestreams

## Implementation
So first I need to find a music streaming service for the livestream. Spotify requires a premium membership to avoid ads, and as a broke college student, this wouldnt work too well. Spotify is free and easily accessible, however, the soundcloud is *very* lenient when it comes to uploads. If only there was a music streaming service hosted by YouTube... Oh wait! There is! Youtube Music is Google's competition to the music streaming giants, and its **Free**. They don't have an official api, but luckily [sigma67](https://github.com/sigma67/ytmusicapi) has done the exceptional honor of creating a very well documented alternative. So, by using [sigma67's](https://github.com/sigma67/ytmusicapi) api, and hosting the livestream on YouTube itself, I think we can make this idea a reality. 

## Logistics
Here is what I have in mind of how this idea is going to come into fruition. The livestream will start with a blank playlist. Then if a listener will want to queue a song, they will donate $1 to the stream (Donation amount subject to change). If the queue is already pretty full, we can give updates on when the listner's song is going to be played using the livestream's chat. If the queue is fairly empty, we can randomly select songs or even use previously queued songs. If this idea really takes off, maybe ill implement a feature to have a listener's song be put at the front of the queue. I am writing this documentation before I have actually started coding this project, so I expect many things will change. However, if you are following along on this journey, welcome. Let's see where this takes us. 

