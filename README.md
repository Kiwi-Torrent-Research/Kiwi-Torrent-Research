uncensored bittorrent data set

sqlite database
| table | fields |
|-------|--------|
| torrents | infohash, name, size, uploaded, seeders, leechers, peers, num_files |
| files | id, name, size |
| search (virtual fts5) | name, size, uploaded, filename, filesize |

index on torrents fields: size, uploaded  
torrents inserted in descending order of seeders, leechers, peers, uploaded

26/03/2023  
61,147,993 torrents  
697,919,156 files

1. [download (torrent)](https://github.com/Kiwi-Torrent-Research/Kiwi-Torrent-Research/raw/main/Kiwi_Torrent_Research_sqlite_26_03_2023.torrent)
2. extract
3. run example.py
