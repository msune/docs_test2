---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Welcome to the pmacct proeject

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Description

pmacct is a small set of multi-purpose passive network monitoring tools. It can account, classify, aggregate, replicate and export forwarding-plane data, ie. IPv4 and IPv6 traffic; collect and correlate control-plane data via BGP and BMP; collect and correlate RPKI data; collect infrastructure data via Streaming Telemetry. Each component works both as a standalone daemon and as a thread of execution for correlation purposes (ie. enrich NetFlow with BGP data). pmacct main features are:

  * Suitable to ISP, IXP, CDN, IP carrier, Cloud, DC and hot-spots enviroments and SDN solutions
  * Runs on Linux, BSDs, Solaris and embedded systems
  * Support for both IPv4 and IPv6
  * Collects data through libpcap, Netlink/NFLOG, NetFlow v1/v5/v7/v8/v9, sFlow v2/v4/v5 and IPFIX
  * Collects Streaming Telemetry data. Read more here.
  * Supports Cisco NEL for CGNAT scenarios and Cisco NSEL
  * Saves data to a number of backends including:
    * Relational databases: MySQL, PostgreSQL and SQLite
    * noSQL databases: MongoDB and BerkeleyDB
    * AMQP message exchanges: RabbitMQ
    * Kafka message brokers
    * memory tables
    * flat files
  * Exports data to remote collectors through IPFIX, NetFlow v5/v9 and sFlow v5
  * Replicates incoming IPFIX, NetFlow and sFlow packets to remote collectors
  * Flexible architecture to tag, filter, redirect, aggregate and split captured data
  * Comes with:
    * a BGP daemon/thread for efficient visibility into the inter-domain routing plane. Read more [here](http://www.pmacct.net/lucente_pmacct_uknof14.pdf).
      * Supports BGP/MPLS VPNs rfc4364, Label Unicast rfc3107
      * Supports BGP ADD-PATHs (draft-ietf-idr-add-paths) for visibility of BGP multi-path routes
      * Can log live BGP messaging and/or dump BGP tables per peer at regular time interval
    * a BMP daemon/thread to gain insight in BGP data, events and statistics
      * Supports draft-ietf-grow-bmp-loc-rib and draft-ietf-grow-bmp-adj-rib-out
    * an IS-IS/IGP thread for visibility of internal routes
    * a RPKI thread to associate Route Origin Validation (ROV) state to BGP data (from 1.7.3)
* Packet classification via nDPI
* Inspection of tunnelled traffic (ie. GTP)
* GeoIP lookups leveraging Maxmind library
* Pluggable architecture for easy integration of new capturing environments and data backends
* Careful SQL support: data pre-processing, triggers, dynamic table naming
* It's free, open-source, developed and supported with passion and open mind for more than 10 years

## Downloads

### v1.7.8

[http://www.pmacct.net/pmacct-1.7.8.tar.gz](http://www.pmacct.net/pmacct-1.7.8.tar.gz)
[ChangeLog](http://www.pmacct.net/ChangeLog-1.7.8) | [FAQS](http://www.pmacct.net/FAQS-1.7.8) | [CONFIG-KEYS](http://www.pmacct.net/CONFIG-KEYS-1.7.8) | **Latest release**
**Size**: 2175335 bytes | **Date**: 31-Dec-2022


### v1.7.7

[http://www.pmacct.net/pmacct-1.7.7.tar.gz](http://www.pmacct.net/pmacct-1.7.7.tar.gz)
[ChangeLog](http://www.pmacct.net/ChangeLog-1.7.7) | [FAQS](http://www.pmacct.net/FAQS-1.7.7) | [CONFIG-KEYS](http://www.pmacct.net/CONFIG-KEYS-1.7.7)
**Size**: 2149629 bytes | **Date**: 07-Oct-2021

### v1.7.6

[http://www.pmacct.net/pmacct-1.7.6.tar.gz](http://www.pmacct.net/pmacct-1.7.6.tar.gz)
[ChangeLog](http://www.pmacct.net/ChangeLog-1.7.6) | [FAQS](http://www.pmacct.net/FAQS-1.7.6) | [CONFIG-KEYS](http://www.pmacct.net/CONFIG-KEYS-1.7.6)
**Size**: 2126837 bytes | **Date**: 07-Feb-2021

### pmacct-contribs

Code is now maintained through [GitHub](https://github.com/paololucente/pmacct-contrib).

## Online documentation

For official and user-contributed documentation, check out our [wiki](https://github.com/pmacct/pmacct/wiki) on GitHub.

## Documents and presentations

See [here](TODO)

## Links

See a curated list [here](TODO)

## Mailing lists

If you are interested in news (new releases and Changelogs, etc.) either about the project itself or related ones, subscribe to the pmacct-news mailing list. The list can be open for posting - on request, see CONTACTS - to developers involved in projects based on pmacct.


### pmacct-news at pmacct (dot) net
News from the project: new releases, general annoucements, what is about to happen, etc.

To subcribe: send a blank email to: `pmacct-news-subscribe`
Traffic volume: very low

### pmacct-news at pmacct (dot) net

Discussion about project development. A place where talk about what the project still misses, new ideas, novel approaches, etc. It's also the place where to get in touch with other pmacct users.

To subcribe: send a blank email to: `pmacct-discussion-subscribe`
Traffic volume: moderate

## LICENSE.
Licensed under The GNU General Public License, Version 2. see COPYING for details.


## CONTACTS
Any comments are warmly welcome. Feel free to contact me for bugs, critics, requests, suggestions or even for a simple feedback with your opinions about the work done at: <add email>.
