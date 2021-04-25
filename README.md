I am not necessarily sure whatt I am trying to accomplish with this project.
My primary goal, I believe, is to somehow download and listen to youtube videos and extract the audio and then perform sentiment analysis on said extracted audio.
I know of sites like merv.tech which allow us to comb through reddit/twitter/telegram etc to look at a prevelance of search terms but I've yet to see something like this developed for youtube or any of the youtube-clones.

Flow of information:
Youtube account/Bot Account subscribed to certain Crypto-youtubers
downloads the video, when correctly downloaded it will add the name to a textfile which needs to be constantly read, 
    if a video name is not on the textfile than it needs to be downloaded and watched -- to prevent duplicates. and information needs to be timestamped as well.
Once a video is ready to be listened to we then feed it into the machin learning software for it to output a transcript
Once a transcript is produced we feed it into the second model to perform a sentiment analysis 
Sentiment analysis performed and we then output the file into an excel spreadsheet for all content produced by that youtuber to catalogue their current thoughts on whatever project is being discussed,