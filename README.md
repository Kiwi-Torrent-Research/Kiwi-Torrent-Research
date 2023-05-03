kiwi torrent research  
uncensored bittorrent data set

30/04/2023  
75.1 GiB  
61,536,875 torrents  
710,030,949 files

1. [download (torrent)](https://github.com/Kiwi-Torrent-Research/Kiwi-Torrent-Research/raw/main/Kiwi_Torrent_Research_sqlite_30_04_2023.torrent)
2. extract
3. run example.py


sqlite database:
| table | fields | indexed fields |
|-------|--------|----------------|
| torrents | infohash, name, size, uploaded, seeders, leechers, peers, num_files | infohash, size, uploaded |
| files | id, name, size | id |
| search (virtual, fts5) | name, size, uploaded, filename, filesize | * |

torrents inserted in descending order of seeders, leechers, peers, uploaded
