# Groundfish Catch Monitor, Phase 1, Step 2: Data Collection
By the time I started working on this capstone project, the "N+1 fish, N+2 fish" competition had ended and the training data that DrivenData had provided was no longer available. So I emailed an inquiry to info@drivendata.org, and they sent me a link to a version of the data on Academic Torrents:

>[N+1 fish, N+2 fish dataset (train_videos)](http://academictorrents.com/details/d232b4221119f034e5fdce2d1e5c16c142c2180d)
>http://academictorrents.com/details/d232b4221119f034e5fdce2d1e5c16c142c2180d

I installed the latest version of Transmission (a BitTorrent client) on my Mac and used it to download the entire data set -- 1,333 MP4 videos, averaging around 4 minutes each, along with matching label data in separate JSON files, for a total size of about 70 GB. I've uploaded a sample pair of files -- one MP4 file, plus its corresponding JSON file -- to a subdirectory in this repository called [training data sample](/training%20data%20sample/).

DrivenData subsequently added an ["Open data" tab](https://www.drivendata.org/competitions/48/identify-fish-challenge/page/168/) to the competition's website, including a link to the Academic Torrents repository, and explained that they're making the data available "for ongoing use, practice, and learning."
