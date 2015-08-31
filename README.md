rssdrop
========

[rssdrop](http://search.cpan.org/~acg/rssdrop-0.2/rssdrop) - deliver rss feeds to Maildirs.

__Please reply to [this issue](https://github.com/petronny/rssdrop/issues/1) to report the feeds that making bugs.__

## Bugs fixed & Enhancements

* Fixed initialization bugs
* HTTPS support
* Locale independence
* Fits more feeds
* Avoid being forbidden by browser signature

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

## Dependencies

### Archlinux

* `perl-xml-simple`
* `perl-date-manip`
* `perl-lwp-protocol-https`: For HTTPS support.

## Now works fine with

* [https://www.archlinux.org/feeds/news/](https://www.archlinux.org/feeds/news/)
* [https://www.archlinuxcn.org/feed/](https://www.archlinuxcn.org/feed/)
* [http://en.cataclysmdda.com/feed](http://en.cataclysmdda.com/feed)
* [http://jingbei.li/atom.xml](http://jingbei.li/atom.xml)

