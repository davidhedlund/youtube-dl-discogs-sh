Mass download music from your favorite artists found on YouTube. -- gratis, and in free formats.

# Is this legal?
I don't know. However, this program has never been popular and it's full of bugs so it's not a significant threat to the music industry.

# Will this project survive?
YouTube Music rivals with Spotify so it's possible that YouTube will remove gratis music streaming within a few years: https://www.digitalmusicnews.com/2017/08/21/music-industry-free-streaming-spotify/

# What is the primary goal with this project?

The name of this software is youtube-dl-discogs-sh, it ends with "-sh" since its a bash script that runs in GNU/Linux environments only. youtube-dl is written in Python, I hope someone want to rewrite this software in Python as well, then it should be renamed to simply youtube-dl-discogs and be offered as a official plugin for youtube-dl as both youtube-dl and youtube-dl-discogs are cross platformed.

# Why don't you accept donations?

This project have and will never accept donations.

Have a thought for the record labels of the various artists. The music is everything. This can't be emphasized enough. Please buy copies of their music to support their living. Avoid supporting SaaSS ("Service as a Software Substitute") like Spotify (see https://stallman.org/spotify.html).

youtube-dl-discogs-sh is just a simple wrapper that fully depends on [youtube-dl](https://github.com/rg3/youtube-dl) and the [Discogs](https://github.com/discogs) (who also promotes its users to buy music to support their artists). Please donate to them if you want to support the software work behind this project.

I don't want the administrative workload coming with donations. I don't want the project to become in need of funding in any way: no dedicated home page + no forum = no cost = no need for funding. I want to be free to move onto something else if ever I get tired working on these projects (no donations = no expectations).

# Is this really legal?

Yes, both YouTube and Discogs are llegal, therfore its legal to parsing Discogs to download track lists from YouTube.

However, I warn anyone to make huge profits by making derivates of this project. Grooveshark faced copyright issues and, the company could have been liable for up to $736 million in damages, then people died:
* Grooveshark Co-Founder Josh Greenberg Found Dead At 28: http://techcrunch.com/2015/07/20/grooveshark-co-founder-josh-greenberg-found-dead-at-28/
* Grooveshark Director of International Sales Eddy Vasquez was fatally shot and killed: http://www.digitalmusicnews.com/permalink/2013/11/11/groovesharkmurdered

# Meta data added to downloaded files
Both Discogs (artist) and YouTube (statistical) meta data are be added to the audio files.

# Who will use it?

* People who like to listen to music off-line.
* youtube-dl-discogs-sh is a useful source to get lots of audio files that can be used for streaming media servers like Icecast, without getting into legal trouble.

# Which artists will not be offended?
Examples of artists that publish all their music free on YouTube
Gigi D'Agostino
  YouTube channel: https://www.youtube.com/channel/UC7Sqfp5sOFUI4436LBoB_JQ
  Discogs entry: http://www.discogs.com/artist/15228-Gigi-DAgostino

# Inbuilt packages

This software comes with
* bashlib (parseJSON dependency)
* parseJSON
