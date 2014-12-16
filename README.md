rssdrop
========

[rssdrop](http://search.cpan.org/~acg/rssdrop-0.2/rssdrop) - deliver rss feeds to Maildirs.

Please reply to [this issue](https://github.com/petronny/rssdrop/issues/1) to report the feeds that making bugs.

## Bugs fixed & Enhancements

* Initialization bugs
* HTTPS support
* Locale independence
* More feeds fitting

## EXAMPLES

### Initialize rssdrop

	$ rssdrop --mailfolder path/to/mailfolder

### Subscribe to a new feed

	$ rssdrop -a acme-widgets http://acme.com/widgets.rss

### Fetch items in your new feed

	$ rssdrop acme-widgets

### Unsubscribe

	$ rssdrop -d acme-widgets

### Fetch all new items in all feeds

	$ rssdrop

## Depences

### Archlinux

* `perl-xml-simple`
* `perl-date-manip`
* `perl-lwp-protocol-https`: For HTTPS support.

## Now works fine with

* [https://www.archlinux.org/feeds/news/](https://www.archlinux.org/feeds/news/)
* [https://www.archlinuxcn.org/feed/](https://www.archlinuxcn.org/feed/)
* [http://en.cataclysmdda.com/feed](http://en.cataclysmdda.com/feed)
* [http://jingbei.tk/atom.xml](http://jingbei.tk/atom.xml)

