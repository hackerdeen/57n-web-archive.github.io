# Welcome to the 57North Archive

![57North Logo](https://hackerdeen.github.io/57n-web-archive.github.io/mediawiki/images/thumb/3/3d/57_North_WLL.svg/286px-57_North_WLL.svg.png)

This is a static file set in github, accessed via github pages.  There are a few things here, we may add more over time.  Each archived system lived in a sub-directory of this.

This can be used as a static file store for systems that are achived, or anything reasonably static like that. 
* It can be viewed at [https://hackerdeen.github.io/57n-web-archive.github.io](https://hackerdeen.github.io/57n-web-archive.github.io)
* It can be edited at [https://github.com/hackerdeen/57n-web-archive.github.io](https://github.com/hackerdeen/57n-web-archive.github.io)


## Mailing List Archive [view>](https://hackerdeen.github.io/57n-web-archive.github.io/mailing_list/)

There is a mailing list archive. All mailing lists are archived here, this is not an automated process, but a system for perhaps keeping old mailing list data when migrating to a new server, or that sort of thing.  The archive date is noted on the [index page](https://hackerdeen.github.io/57n-web-archive.github.io/mailing_list/).


## Wiki, pre may 2020 [view>](https://hackerdeen.github.io/57n-web-archive.github.io/mediawiki/index.php/Main_Page.html)

There is a static copy of the Media Wiki based wiki. See [https://hackerdeen.github.io/57n-web-archive.github.io/mediawiki/index.php/Main_Page.html](https://hackerdeen.github.io/57n-web-archive.github.io/mediawiki/index.php/Main_Page.html).  The MediaWiki based Wiki was replaced with DocuWiki in May 2020.

Things that don't work in the static version...
* Login
* Editing
* Search


## Method

* The files are typically archived via [HTTrack](https://www.httrack.com/).  
* The files are added to this GitHub repo.
* It is all automagically published via [Github pages](https://pages.github.com/).
* Sometimes it takes a couple of minutes between when a change goes into git and when it displays or updates in github pages.


## HTTrack Examples

'httrack https://lists.57north.co/listinfo/57north-announce https://lists.57north.co/pipermail/57north-announce/ https://lists.57north.co/listinfo/57north-ctte https://lists.57north.co/pipermail/57north-ctte/ https://lists.57north.co/listinfo/57north-discuss https://lists.57north.co/pipermail/57north-discuss/ https://lists.57north.co/listinfo/57north-music https://lists.57north.co/pipermail/57north-music/ https://lists.57north.co/listinfo  -O "/home/andy/temp/57n/httrack/archive3"  -%v'