kiwi torrent research  
uncensored bittorrent data set

24/05/2023  
75.9 GiB  
61,807,957 torrents  
718,410,792 files

[download (torrent, 27.8 GiB)](https://github.com/Kiwi-Torrent-Research/Kiwi-Torrent-Research/raw/main/Kiwi_Torrent_Research_sqlite_24_05_2023.torrent)

sqlite database:
| table | fields | indexed fields |
|-------|--------|----------------|
| torrents | infohash, name, size, uploaded, seeders, leechers, peers, num_files | infohash, size, uploaded |
| files | id, name, size | id |
| search (virtual, fts5) | name, size, uploaded, filename, filesize | * |

torrents inserted in descending order of seeders, leechers, peers, uploaded
