kiwi torrent research  
uncensored bittorrent data set  
[data set sources](https://github.com/Kiwi-Torrent-Research/Kiwi-Torrent-Research/tree/main/sources)

releases:
| date | torrents | files | compressed | extracted | notes |
|------|----------|-------|------------|-----------|-------|
| [30/08/2023](https://github.com/Kiwi-Torrent-Research/Kiwi-Torrent-Research/raw/main/Kiwi_Torrent_Research_sqlite_30_08_2023.torrent) | 107,234,785 | 1,684,742,255 | 59.6 GiB | 169 GiB | 
| [21/07/2023](https://github.com/Kiwi-Torrent-Research/Kiwi-Torrent-Research/raw/main/Kiwi_Torrent_Research_sqlite_21_07_2023.torrent) | 106,776,147 | 1,675,238,283 | 59.3 Gib | 168 GiB |
| [24/05/2023](https://github.com/Kiwi-Torrent-Research/Kiwi-Torrent-Research/raw/main/Kiwi_Torrent_Research_sqlite_24_05_2023.torrent) | 61,807,957 | 718,410,792 | 27.8 GiB | 75.9 GiB |
| [30/04/2023](https://github.com/Kiwi-Torrent-Research/Kiwi-Torrent-Research/raw/main/Kiwi_Torrent_Research_sqlite_30_04_2023.torrent) | 61,536,875 | 710,030,949 | 27.5 GiB | 75.0 Gib | [Academic Torrents](https://academictorrents.com/details/a7b9f1b1ffd2d7bbf6b11960a0c7bbf3a754e8a6) |

sqlite database:
| table | fields | indexed fields |
|-------|--------|----------------|
| torrents | infohash, name, size, uploaded, seeders, leechers, peers, num_files | infohash, size, uploaded |
| files | id, name, size | id |
| search (virtual, fts5) | name, size, uploaded, filename, filesize | * |

torrents inserted in descending order of seeders, leechers, peers, uploaded
