# /r/scihub FAQ - Frequently Asked Questions

## Is Sci-Hub down? Why can't I access Sci-Hub?

No, Sci-Hub is up and working. **But your government may have banned access to Sci-Hub.** How can you fight against your government's censorship over the internet? We have some answers.

### Solution 1
>[Enable DNS over HTTPS](https://developers.cloudflare.com/1.1.1.1/dns-over-https/web-browser) to override your country's censorship over the internet.

### Solution 2
>Install a [free VPN](https://protonvpn.com/) or download [the Tor Browser](https://www.torproject.org/download/) to access websites your government has banned.

### Solution 3
>Request articles using the [Official Telegram Sci-Hub Bot](https://t.me/scihubot) or [Nexus Search Telegram bot](https://t.me/libgen_scihub_bot). [libgen.rs/scimag](http://libgen.rs/scimag) also provides a historical archive.

## Why is Sci-Hub showing me a blank page or error? The article won't show up.

1. If the article is from 2021 or late 2020 then Sci-Hub will not download it for you. Sci-Hub froze new downloads globally during the court trial in India, which means no new papers. You can still access the papers Sci-Hub has already saved.
1. If Sci-Hub is delivering a white page or a Russian error message then that journal may be inaccessible for other technical reasons.

## How else can I download articles for free?
1. [ResearchGate](https://www.researchgate.net/) or [Academia.edu](https://www.academia.edu/) have many papers that have been uploaded by authors.
1. Try the [OpenAccess Button](https://openaccessbutton.org/) or [Unpaywall](https://unpaywall.org/)
1. Try e-mailing the authors
1. Request the article via [reddit.com/r/Scholar](https://reddit.com/r/Scholar) or [other social media groups](https://www.facebook.com/groups/546916758676870).

## Official Sci-Hub Mirrors
These official links are the ones listed on the official VK or the former Twitter.

* [**sci-hub.do**](https://sci-hub.do/)
* [**sci-hub.st**](https://sci-hub.st/)
* [**sci-hub.se**](https://sci-hub.se)
* [**telegram.me/scihubot**](https://telegram.me/scihubot) (Sci-Hub Telegram Bot)

## Official Sci-Hub Social

* [**facebook.com/sci.hub.org**](https://www.facebook.com/sci.hub.org) (Facebook)
* [**vk.com/sci\_hub**](https://vk.com/sci_hub) (VKontakte)
* [**engineuring.wordpress.com**](https://engineuring.wordpress.com/) (Alexandra Elbakyan's personal blog)

## Trusted Third-Party Scimag Archives

*scimag* is an archive of more than 80 million Sci-Hub-indexed articles provided by the Library Genesis project mirrors. Enter a DOI to search the archive. Note that this archive is only a snapshot of articles previously requested by Sci-Hub users in the past and cannot proxy you to fresh articles.

* [**libgen.rs/scimag**](http://libgen.rs/scimag)
* [**libgen.fun/scimag**](https://libgen.fun/scimag)

## Trusted Third-Party Extensions and Software

* [**Sci-Hub X Now!**](https://chrome.google.com/webstore/detail/sci-hub-x-now/gmmnidkpkgiohfdoenhpghbilmeeagjj), an open source Chrome extension from [Gerry Chen](https://github.com/gchenfc/sci-hub-now).
* [**github.com/ethanwillis/zotero-scihub**](https://github.com/ethanwillis/zotero-scihub) (coded by developer [Ethan Willis](https://stackoverflow.com/cv/ethanwillis) and recommended by the late [Jon Tennant](https://twitter.com/Protohedgehog/status/1030248351470563328))
* This list will grow as more extensions are vetted by the community.

## Sci-Hub for Developers

* [Visit the awesome-libgen collection on GitHub](https://github.com/freereadorg/awesome-libgen)
* **Big Picture:** Sci-Hub's article repo and database is DUMB SIMPLE, but their magical proxy isn't.
* **Legal Notice:** USDOJ and Elsevier really don't like their proxy, for good reason, so I recommend against working on anything like that, but instead play with the open (and legal) database of DOIs. A database of metadata is legal and not in clear violation of IP law (*IANAL*).
* **Sci-Hub** **Torrents:** The [Rescue Mission scimag-archive torrents](https://www.reddit.com/r/DataHoarder/comments/nc27fv/rescue_mission_for_scihub_and_open_science_we_are/) work like this: ./DOI, that's it.
* **Sci-Hub** **API:** A live API implementation of Sci-Hub can be seen in the Zotero plugin, see [ethanwillis/zotero-scihub](https://github.com/ethanwillis/zotero-scihub), it's just a URL + DOI + optional captcha. That's the whole damn API.
* **Sci-Hub** **Database:** Sci-Hub's database is available here: [libgen.rs/dbdump](http://libgen.rs/dbdumps/) and database documentation is available here: [lucidhack/knowl](https://gitlab.com/lucidhack/knowl/-/wikis/References/Libgen-Science-Tables)
* **Some examples of big brain problems to solve:**

>How to legally ingest new papers from authors and load them onto the existing SQL database?

>How to make use of de-centralized solutions like WebTorrent and IPFS to deliver papers?

>How to extract good metadata from scientific PDFs?

>How to use [existing DOI databases](https://www.crossref.org/education/retrieve-metadata/) to improve Sci-Hub's database?

>How to make it easier for libraries and universities in the developing world to access papers?