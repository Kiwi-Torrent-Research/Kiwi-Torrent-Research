kiwi torrent research  
uncensored bittorrent data set

21/07/2023  
168 GiB  
106,776,147 torrents  
1,675,238,283 files

[download (torrent, 59.3 GiB)](https://github.com/Kiwi-Torrent-Research/Kiwi-Torrent-Research/raw/main/Kiwi_Torrent_Research_sqlite_21_07_2023.torrent)

sqlite database:
| table | fields | indexed fields |
|-------|--------|----------------|
| torrents | infohash, name, size, uploaded, seeders, leechers, peers, num_files | infohash, size, uploaded |
| files | id, name, size | id |
| search (virtual, fts5) | name, size, uploaded, filename, filesize | * |

torrents inserted in descending order of seeders, leechers, peers, uploaded
