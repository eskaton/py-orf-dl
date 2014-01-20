ORF Downloader
======

Synopsis
----------

orf-dl.py is a script to download videos from tvthek.orf.at.
It depends on rtmpdump and Python 2.7.

Usage
-----

```
Usage: orf-dl.py -u <url> [-o <output-file>]
```

There is no error handling. If the script fails either the ORF site is down
or they changed the layout of their site.
