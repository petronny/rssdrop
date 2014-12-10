rssdrop
========

[rssdrop](http://search.cpan.org/~acg/rssdrop-0.2/rssdrop) - deliver rss feeds to Maildirs

This is a fork for bug fixing.

# EXAMPLES

## Initialize rssdrop

	$ rssdrop --mailfolder path/to/mailfolder

## Subscribe to a new feed

	$ rssdrop -a acme-widgets http://acme.com/widgets.rss

## Fetch items in your new feed

	$ rssdrop acme-widgets

## Unsubscribe

	$ rssdrop -d acme-widgets

## Fetch all new items in all feeds

	$ rssdrop

# Depences

## Archlinux

* `perl-xml-simple`
* `perl-date-manip`
* `perl-lwp-protocol-https`:For HTTPS support.

