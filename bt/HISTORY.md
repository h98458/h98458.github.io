## 08.03.2013

* sphinx searching is stable right now, you can config to use it
* modify giza library, to support get sphinx search stats from response
* add page navigation to http 

## 07.30.2013

* add sphinx (coreseek which based on sphinx) to help searhcing, in expirement stage

## 07.21.2013

* rewrite hash_reader, now it will keep a wait_download cache
* change hash_writer(crawler) to insert unique hash

## 07.19.2013

* add simple json searhch api to http

## 07.15.2013

* crawler now will keep a hash cache, merge same hash in the cache, this makes hash_reader process less hashes

## 07.08.2013

* add torrent importer which can import local torrents into torrents database

## 07.05.2013

* add torrent downloader which will download torrents and store them in database or local file system
* hash_reader now use local torrents first, if not it will download, and depends on the config it may save the file too

