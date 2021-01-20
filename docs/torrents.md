# Library Genesis Charitable Seeding Project

In November 2019 reddit user shrine asked the communities /r/seedboxes and /r/DataHoarder to consider supporting two of the most important library collections in history - not with money, but with their bandwidth. By December thousands of seeders were active on torrents for more than 2.4 million books, and by January the Sci-Hub collection was complete. You can learn more about this work in [TorrentFreak](https://torrentfreak.com/meet-the-guy-behind-the-libgen-torrent-seeding-movement-191205/) and [Vice](https://www.vice.com/en_us/article/pa7jxb/archivists-are-trying-to-make-sure-a-pirate-bay-of-science-never-goes-down).

Once Sci-Hub was seeded, we put the archive to work to create an experimental, curated Coronavirus research capsule spanning decades, perhaps the first of its kind (covered in [Vice](https://www.vice.com/en_us/article/z3b3v5/archivists-are-bypassing-paywalls-to-share-studies-about-coronaviruses)).

##  How can I help seed the torrents?
You can join the [Library Genesis Seeding Project](https://www.reddit.com/r/DataHoarder/comments/ed9byj/library_genesis_project_update_25_million_books/) to help seed the torrents that serve to preserve and archive the 2.5-million books in the library collection. [PhillM's LibGen torrent index](https://phillm.net/libgen-seeds-needed.php) tracks which torrents need seeders, start there.

## How do the torrents work?
The torrents are divided into three collections: scitech, fiction, and scimag. The book files and SQL databases together make up the library, so distributing these torrents means anyone in the world can create a mirror of Library Genesis. The SQL database files contain the file extension, book names, authors, and all other meta information.

* `scitech` spans 2.4 million books packaged into 2,400+ torrents, with each torrent containing 1,000 books. Each scitech book file is named for its MD5 hash string.
* `fiction` spans 2.4 million books packaged into 1,000 torrents, with each torrent containing 1,000 books. Each fiction book file is named for its MD5 hash string. Fiction SQL databases are divided into Russian and Foreign language (i.e. all languages other than Russian).
* `scimag` spans 80 million scientific articles packaged into 800+ torrents, with each torrent containing 100 zip files. Each scientific article is named for its DOI.

## How do the SQL databases work?

You can download the SQL databases from [https://lgdumps.xyz/dumps/](https://lgdumps.xyz/dumps/). Open them using MySQL or other equivalent software.