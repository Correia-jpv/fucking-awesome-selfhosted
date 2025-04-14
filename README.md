# Awesome-Selfhosted

[![Awesome](_static/awesome.png)](https://github.com/sindresorhus/awesome) [![](https://github.com/awesome-selfhosted/awesome-selfhosted-data/actions/workflows/check-dead-links.yml/badge.svg)](https://github.com/awesome-selfhosted/awesome-selfhosted-data/issues/1) [![](https://github.com/awesome-selfhosted/awesome-selfhosted-data/actions/workflows/check-unmaintained-projects.yml/badge.svg)](https://github.com/awesome-selfhosted/awesome-selfhosted-data/issues/1) [![](https://img.shields.io/liberapay/goal/awesome-selfhosted?logo=liberapay)](https://liberapay.com/awesome-selfhosted/)

Self-hosting is the practice of hosting and managing applications on your own server(s) instead of consuming from 🌎 [SaaSS](www.gnu.org/philosophy/who-does-that-server-really-serve.html) providers.

This is a list of 🌎 [Free](en.wikipedia.org/wiki/Free_software) Software 🌎 [network services](en.wikipedia.org/wiki/Network_service) and 🌎 [web applications](en.wikipedia.org/wiki/Web_application) which can be hosted on your own server(s). Non-Free software is listed on the [Non-Free](https://github.com/correia-jpv/fucking-awesome-selfhosted/blob/master/non-free.md) page.

* 🌎 [HTML version](awesome-selfhosted.net/) (recommended)**, [Markdown version](https://github.com/correia-jpv/fucking-awesome-selfhosted) (legacy).

See [Contributing](#contributing).

--------------------

## Table of contents

- [Software](#software)
  - [Analytics](#analytics)
  - [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)
  - [Automation](#automation)
  - [Backup](#backup)
  - [Blogging Platforms](#blogging-platforms)
  - [Booking and Scheduling](#booking-and-scheduling)
  - [Bookmarks and Link Sharing](#bookmarks-and-link-sharing)
  - [Calendar & Contacts](#calendar--contacts)
  - [Communication - Custom Communication Systems](#communication---custom-communication-systems)
  - [Communication - Email - Complete Solutions](#communication---email---complete-solutions)
  - [Communication - Email - Mail Delivery Agents](#communication---email---mail-delivery-agents)
  - [Communication - Email - Mail Transfer Agents](#communication---email---mail-transfer-agents)
  - [Communication - Email - Mailing Lists and Newsletters](#communication---email---mailing-lists-and-newsletters)
  - [Communication - Email - Webmail Clients](#communication---email---webmail-clients)
  - [Communication - IRC](#communication---irc)
  - [Communication - SIP](#communication---sip)
  - [Communication - Social Networks and Forums](#communication---social-networks-and-forums)
  - [Communication - Video Conferencing](#communication---video-conferencing)
  - [Communication - XMPP - Servers](#communication---xmpp---servers)
  - [Communication - XMPP - Web Clients](#communication---xmpp---web-clients)
  - [Community-Supported Agriculture (CSA)](#community-supported-agriculture-csa)
  - [Conference Management](#conference-management)
  - [Content Management Systems (CMS)](#content-management-systems-cms)
  - [Customer Relationship Management (CRM)](#customer-relationship-management-crm)
  - [Database Management](#database-management)
  - [DNS](#dns)
  - [Document Management](#document-management)
  - [Document Management - E-books](#document-management---e-books)
  - [Document Management - Institutional Repository and Digital Library Software](#document-management---institutional-repository-and-digital-library-software)
  - [Document Management - Integrated Library Systems (ILS)](#document-management---integrated-library-systems-ils)
  - [E-commerce](#e-commerce)
  - [Federated Identity & Authentication](#federated-identity--authentication)
  - [Feed Readers](#feed-readers)
  - [File Transfer & Synchronization](#file-transfer--synchronization)
  - [File Transfer - Distributed Filesystems](#file-transfer---distributed-filesystems)
  - [File Transfer - Object Storage & File Servers](#file-transfer---object-storage--file-servers)
  - [File Transfer - Peer-to-peer Filesharing](#file-transfer---peer-to-peer-filesharing)
  - [File Transfer - Single-click & Drag-n-drop Upload](#file-transfer---single-click--drag-n-drop-upload)
  - [File Transfer - Web-based File Managers](#file-transfer---web-based-file-managers)
  - [Games](#games)
  - [Games - Administrative Utilities & Control Panels](#games---administrative-utilities--control-panels)
  - [Genealogy](#genealogy)
  - [Groupware](#groupware)
  - [Human Resources Management (HRM)](#human-resources-management-hrm)
  - [Identity Management](#identity-management)
  - [Internet of Things (IoT)](#internet-of-things-iot)
  - [Inventory Management](#inventory-management)
  - [Knowledge Management Tools](#knowledge-management-tools)
  - [Learning and Courses](#learning-and-courses)
  - [Manufacturing](#manufacturing)
  - [Maps and Global Positioning System (GPS)](#maps-and-global-positioning-system-gps)
  - [Media Management](#media-management)
  - [Media Streaming](#media-streaming)
  - [Media Streaming - Audio Streaming](#media-streaming---audio-streaming)
  - [Media Streaming - Multimedia Streaming](#media-streaming---multimedia-streaming)
  - [Media Streaming - Video Streaming](#media-streaming---video-streaming)
  - [Miscellaneous](#miscellaneous)
  - [Money, Budgeting & Management](#money-budgeting--management)
  - [Monitoring](#monitoring)
  - [Note-taking & Editors](#note-taking--editors)
  - [Office Suites](#office-suites)
  - [Password Managers](#password-managers)
  - [Pastebins](#pastebins)
  - [Personal Dashboards](#personal-dashboards)
  - [Photo Galleries](#photo-galleries)
  - [Polls and Events](#polls-and-events)
  - [Proxy](#proxy)
  - [Recipe Management](#recipe-management)
  - [Remote Access](#remote-access)
  - [Resource Planning](#resource-planning)
  - [Search Engines](#search-engines)
  - [Self-hosting Solutions](#self-hosting-solutions)
  - [Software Development](#software-development)
  - [Software Development - API Management](#software-development---api-management)
  - [Software Development - Continuous Integration & Deployment](#software-development---continuous-integration--deployment)
  - [Software Development - FaaS & Serverless](#software-development---faas--serverless)
  - [Software Development - Feature Toggle](#software-development---feature-toggle)
  - [Software Development - IDE & Tools](#software-development---ide--tools)
  - [Software Development - Localization](#software-development---localization)
  - [Software Development - Low Code](#software-development---low-code)
  - [Software Development - Project Management](#software-development---project-management)
  - [Software Development - Testing](#software-development---testing)
  - [Static Site Generators](#static-site-generators)
  - [Status / Uptime pages](#status--uptime-pages)
  - [Task Management & To-do Lists](#task-management--to-do-lists)
  - [Ticketing](#ticketing)
  - [Time Tracking](#time-tracking)
  - [URL Shorteners](#url-shorteners)
  - [Video Surveillance](#video-surveillance)
  - [VPN](#vpn)
  - [Web Servers](#web-servers)
  - [Wikis](#wikis)
- [List of Licenses](#list-of-licenses)
- [Anti-features](#anti-features)
- [External Links](#external-links)
- [Contributing](#contributing)
- [License](#license)

--------------------

## Software

### Analytics

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Analytics](en.wikipedia.org/wiki/Analytics) is the systematic computational analysis of data or statistics. It is used for the discovery, interpretation, and communication of meaningful patterns in data.

_Related: [Database Management](#database-management), [Personal Dashboards](#personal-dashboards)_

- 🌎 [Aptabase](aptabase.com/) - Privacy first and simple analytics for mobile and desktop apps. (<b><code>&nbsp;&nbsp;1294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Source Code](https://github.com/aptabase/aptabase))) `AGPL-3.0` `Docker`
- [AWStats](http://www.awstats.org/) - Generate statistics from web, streaming, ftp or mail server logfiles.  🌎 [Demo](www.awstats.org/#DEMO), <b><code>&nbsp;&nbsp;&nbsp;393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [Source Code](https://github.com/eldy/awstats))) `GPL-3.0` `Perl`
- 🌎 [Countly Community Edition](count.ly) - Real time mobile and web analytics, crash reporting and push notifications platform. ([Source Code](https://github.com/countly)) `AGPL-3.0` `Nodejs/Docker`
- [Druid](http://druid.io/) - Distributed, column-oriented, real-time analytics data store. (<b><code>&nbsp;13671⭐</code></b> <b><code>&nbsp;&nbsp;3731🍴</code></b> [Source Code](https://github.com/apache/druid))) `Apache-2.0` `Java/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [EDA](https://github.com/jortilles/EDA)) - Web application for data analysis and visualization. `AGPL-3.0` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [ghstats](https://github.com/vladkens/ghstats)) `⚠` - Dashboard for tracking GitHub repos traffic history longer than 14 days. `MIT` `Docker`
- [GoAccess](http://goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal. (<b><code>&nbsp;19233⭐</code></b> <b><code>&nbsp;&nbsp;1136🍴</code></b> [Source Code](https://github.com/allinurl/goaccess))) `GPL-2.0` `C`
- 🌎 [GoatCounter](www.goatcounter.com) - Easy web statistics without tracking of personal data. (<b><code>&nbsp;&nbsp;4827⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;210🍴</code></b> [Source Code](https://github.com/arp242/goatcounter))) `EUPL-1.2` `Go`
- 🌎 [Litlyx](litlyx.com) - All-in-one Analytics Solution. Setup in 30 seconds. Display all your data on an AI-powered dashboard. Fully self-hostable and GDPR compliant. (<b><code>&nbsp;&nbsp;1123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Source Code](https://github.com/Litlyx/litlyx))) `Apache-2.0` `Docker`
- 🌎 [Liwan](liwan.dev/) - Easy & privacy-first web analytics.  🌎 [Demo](demo.liwan.dev/p/liwan.dev), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/explodingcamera/liwan))) `AGPL-3.0` `Rust/Docker`
- 🌎 [Matomo](matomo.org/) - Google Analytics alternative that protects your data and your customers' privacy. (<b><code>&nbsp;20403⭐</code></b> <b><code>&nbsp;&nbsp;2703🍴</code></b> [Source Code](https://github.com/matomo-org/matomo))) `GPL-3.0` `PHP`
- 🌎 [Metabase](metabase.com/) - Easy, open-source way for everyone in your company to ask questions and learn from data. (<b><code>&nbsp;41578⭐</code></b> <b><code>&nbsp;&nbsp;5494🍴</code></b> [Source Code](https://github.com/metabase/metabase))) `AGPL-3.0` `Java/Docker`
- 🌎 [Middleware](middlewarehq.com/) - Tool designed to help engineering leaders measure and analyze the effectiveness of their teams using the DORA metrics. (<b><code>&nbsp;&nbsp;1287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [Source Code](https://github.com/middlewarehq/middleware))) `Apache-2.0` `Docker/Python/Nodejs`
- 🌎 [Mixpost](mixpost.app/) - Self-hosted social media management software. Easily create, schedule, publish, and manage social media content in one place (alternative to Hootsuite, Buffer, and other social media tools). (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Source Code](https://github.com/inovector/MixpostApp))) `MIT` `PHP/Docker`
- 🌎 [Netron](netron.app/) - Visualizer for neural network and machine learning models. (<b><code>&nbsp;29908⭐</code></b> <b><code>&nbsp;&nbsp;2879🍴</code></b> [Source Code](https://github.com/lutzroeder/netron))) `MIT` `Python/Nodejs`
- 🌎 [Offen](www.offen.dev/) - Fair, lightweight and open web analytics tool. Gain insights while your users have full access to their data.  🌎 [Demo](www.offen.dev/try-demo/), <b><code>&nbsp;&nbsp;&nbsp;923⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [Source Code](https://github.com/offen/offen))) `Apache-2.0` `Go/Docker`
- 🌎 [Plausible Analytics](plausible.io/) - Simple, open-source, lightweight (< 1 KB) and privacy-friendly web analytics. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/plausible/analytics/))) `AGPL-3.0` `Elixir`
- 🌎 [PostHog](posthog.com) - Product analytics, session recording, feature flagging and a/b testing that you can self-host (alternative to Mixpanel/Amplitude/Heap/HotJar/Optimizely). (<b><code>&nbsp;25778⭐</code></b> <b><code>&nbsp;&nbsp;1598🍴</code></b> [Source Code](https://github.com/posthog/posthog))) `MIT` `Python`
- 🌎 [Postiz](postiz.com) `⚠` - Schedule posts, track the performance of your content, and manage all your social media accounts in one place (Alternative to Buffer, Hootsuite, Sprout Social). (<b><code>&nbsp;19492⭐</code></b> <b><code>&nbsp;&nbsp;3105🍴</code></b> [Source Code](https://github.com/gitroomhq/postiz-app))) `Apache-2.0` `Docker`
- 🌎 [Prisme Analytics](www.prismeanalytics.com) - A privacy-focused and progressive analytics service based on Grafana.  🌎 [Demo](app.prismeanalytics.com/grafana), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/prismelabs/analytics))) `AGPL-3.0/MIT` `Docker`
- [Redash](http://redash.io) - Connect and query your data sources, build dashboards to visualize data and share them with your company. (<b><code>&nbsp;27207⭐</code></b> <b><code>&nbsp;&nbsp;4458🍴</code></b> [Source Code](https://github.com/getredash/redash))) `BSD-2-Clause` `Docker`
- 🌎 [RudderStack](rudderstack.com/) - Collect, unify, transform, and store your customer data, and route it to a wide range of common, popular marketing, sales, and product tools (alternative to Segment). (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/rudderlabs/rudder-server/))) `AGPL-3.0` `Docker/K8S/Go/Nodejs`
- <b><code>&nbsp;&nbsp;3008⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;197🍴</code></b> [Shynet](https://github.com/milesmcc/shynet)) - Modern, privacy-friendly, and detailed web analytics that works without cookies or JS. `Apache-2.0` `Python/Docker`
- <b><code>&nbsp;&nbsp;1259⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;383🍴</code></b> [Socioboard](https://github.com/socioboard/Socioboard-5.0)) `⚠` - Social media management, analytics, and reporting platform supporting nine social media networks out-of-the-box. `GPL-3.0` `Nodejs`
- [Superset](http://superset.apache.org/) - Modern data exploration and visualization platform. (<b><code>&nbsp;65678⭐</code></b> <b><code>&nbsp;14830🍴</code></b> [Source Code](https://github.com/apache/superset))) `Apache-2.0` `Python`
- 🌎 [Swetrix](swetrix.com/) - Ultimate, open-source web analytics to satisfy all your needs.  🌎 [Demo](swetrix.com/projects/STEzHcB1rALV), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Source Code](https://github.com/Swetrix/selfhosting))) `AGPL-3.0` `Docker`
- 🌎 [Umami](umami.is/) - Simple, fast, privacy-focused alternative to Google Analytics.  🌎 [Demo](analytics.umami.is/share/LGazGOecbDtaIwDr/umami.is), <b><code>&nbsp;25898⭐</code></b> <b><code>&nbsp;&nbsp;4763🍴</code></b> [Source Code](https://github.com/umami-software/umami))) `MIT` `Nodejs/Docker`


### Archiving and Digital Preservation (DP)

**[`^        back to top        ^`](#awesome-selfhosted)**

Digital 🌎 [archiving](en.wikipedia.org/wiki/Archival_science) and 🌎 [preservation](en.wikipedia.org/wiki/Digital_preservation) software.

_Related: [Content Management Systems (CMS)](#content-management-systems-cms)_

_See also: <b><code>&nbsp;&nbsp;2213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [awesome-web-archiving](https://github.com/iipc/awesome-web-archiving))_

- 🌎 [ArchiveBox](archivebox.io/) - Create HTML & screenshot archives of sites from your bookmarks, browsing history, RSS feeds, or other sources (alternative to Wayback Machine). (<b><code>&nbsp;23631⭐</code></b> <b><code>&nbsp;&nbsp;1249🍴</code></b> [Source Code](https://github.com/ArchiveBox/ArchiveBox))) `MIT` `Python/Docker`
- 🌎 [ArchivesSpace](archivesspace.org/) - Archives information management application for managing and providing Web access to archives, manuscripts and digital objects.  🌎 [Demo](archivesspace.org/application/sandbox), <b><code>&nbsp;&nbsp;&nbsp;368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;233🍴</code></b> [Source Code](https://github.com/archivesspace/archivesspace))) `ECL-2.0` `Ruby`
- 🌎 [bitmagnet](bitmagnet.io) - BitTorrent indexer, DHT crawler, content classifier and torrent search engine with web UI, GraphQL API and Servarr stack integration. (<b><code>&nbsp;&nbsp;2906⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [Source Code](https://github.com/bitmagnet-io/bitmagnet))) `MIT` `Go/Docker`
- 🌎 [CKAN](ckan.org) - CKAN is a tool for making open data websites. (<b><code>&nbsp;&nbsp;4666⭐</code></b> <b><code>&nbsp;&nbsp;2031🍴</code></b> [Source Code](https://github.com/ckan/ckan))) `AGPL-3.0` `Python`
- 🌎 [Collective Access - Providence](collectiveaccess.org/) - Highly configurable Web-based framework for management, description, and discovery of digital and physical collections supporting a variety of metadata standards, data types, and media formats. (<b><code>&nbsp;&nbsp;&nbsp;316⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [Source Code](https://github.com/collectiveaccess/providence))) `GPL-3.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;677⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Ganymede](https://github.com/Zibbp/ganymede)) `⚠` - Twitch VOD and Live Stream archiving platform. Includes a rendered chat for each archive. `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [LiveStreamDVR](https://github.com/MrBrax/LiveStreamDVR)) `⚠` - An automatic Twitch recorder capable of capturing live streams, chat messages and stream metadata. `MIT` `Python/Nodejs/Docker`
- 🌎 [Omeka S](omeka.org/s/) - Omeka S is a web publication system for universities, galleries, libraries, archives, and museums. It consists of a local network of independently curated exhibits sharing a collaboratively built pool of items, media, and their metadata. (<b><code>&nbsp;&nbsp;&nbsp;430⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;145🍴</code></b> [Source Code](https://github.com/omeka/omeka-s))) `GPL-3.0` `Nodejs`
- 🌎 [Wallabag](www.wallabag.org) - Wallabag, formerly Poche, is a web application allowing you to save articles to read them later with improved readability. (<b><code>&nbsp;11137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;790🍴</code></b> [Source Code](https://github.com/wallabag/wallabag))) `MIT` `PHP`
- <b><code>&nbsp;&nbsp;1934⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Wayback](https://github.com/wabarc/wayback)) - A self-hosted toolkit for archiving webpages to the Internet Archive, archive.today, IPFS, and local file systems. `GPL-3.0` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;132⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Webarchive](https://github.com/derfenix/webarchive)) - Lightweight self-hosted _wayback machine_ that creates HTML and PDF files from your bookmarks. `BSD-3-Clause` `Go`


### Automation

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Automation](en.wikipedia.org/wiki/Automation) software designed to reduce human intervention in processes.

_Related: [Internet of Things (IoT)](#internet-of-things-iot), [Software Development - Continuous Integration & Deployment](#software-development---continuous-integration--deployment), [Media Management](#media-management)_

- 🌎 [Activepieces](www.activepieces.com) - No-code business automation tool like Zapier or Tray. For example, you can send a Slack notification for each new Trello card. (<b><code>&nbsp;13668⭐</code></b> <b><code>&nbsp;&nbsp;1759🍴</code></b> [Source Code](https://github.com/activepieces/activepieces))) `MIT` `Docker`
- 🌎 [Apache Airflow](airflow.apache.org/) - Platform to programmatically author, schedule, and monitor workflows. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/apache/airflow/))) `Apache-2.0` `Python/Docker`
- 🌎 [Automatisch](automatisch.io) - Business automation tool that lets you connect different services like Twitter, Slack, and more to automate your business processes (alternative to Zapier). (<b><code>&nbsp;&nbsp;8653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;640🍴</code></b> [Source Code](https://github.com/automatisch/automatisch))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [BookBounty](https://github.com/TheWicklowWolf/BookBounty)) `⚠` - Retrieve missing Readarr books from Library Genesis. `MPL-2.0` `Docker`
- <b><code>&nbsp;23471⭐</code></b> <b><code>&nbsp;&nbsp;1280🍴</code></b> [changedetection.io](https://github.com/dgtlmoon/changedetection.io)) - Self-hosted tool for staying up-to-date with web-site content changes. `Apache-2.0` `Python/Docker`
- 🌎 [ChiefOnboarding](chiefonboarding.com) - Employee onboarding platform that allows you to provision user accounts and create sequences with todo items, resources, text/email/Slack messages, and more! Available as a web portal and Slack bot. (<b><code>&nbsp;&nbsp;&nbsp;753⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [Source Code](https://github.com/chiefonboarding/ChiefOnboarding))) `AGPL-3.0` `Docker`
- 🌎 [Discount Bandit](discount-bandit.cybrarist.com/) `⚠` - Track pricing, stock status of products across multiple stores such as Amazon, Ebay, Walmart, etc.  🌎 [Demo](discount-bandit.cybrarist.com/screenshots.html), <b><code>&nbsp;&nbsp;&nbsp;416⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Source Code](https://github.com/Cybrarist/Discount-Bandit))) `GPL-3.0` `PHP/Docker`
- 🌎 [Dittofeed](www.dittofeed.com) - Omni-channel customer engagement and messaging automation platform (alternative to Braze, Customer.io, Iterable).  🌎 [Demo](demo.dittofeed.com/dashboard/journeys), <b><code>&nbsp;&nbsp;2253⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;229🍴</code></b> [Source Code](https://github.com/dittofeed/dittofeed))) `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [feedmixer](https://github.com/cristoper/feedmixer)) - FeedMixer is a WSGI (Python3) micro web service which takes a list of feed URLs and returns a new feed consisting of the most recent n entries from each given feed(Returns Atom, RSS, or JSON).  🌎 [Demo](mretc.net/feedmixer/json?f=https://hnrss.org/newest&f=https://americancynic.net/atom.xml&n=1)) `WTFPL` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Github Ntfy](https://github.com/BreizhHardware/ntfy_alerts)) `⚠` - Push notifications to NTFY when a new release is available on Docker Hub or Github. (<b><code>&nbsp;22386⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;887🍴</code></b> [Clients](https://github.com/binwiederhier/ntfy))) `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;395⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [HandBrake Web](https://github.com/TheNickOfTime/handbrake-web)) - Platform to use one or more instances of HandBrake video transcoder on a headless device via a web interface. `AGPL-3.0` `Docker`
- 🌎 [Healthchecks](healthchecks.io/) - Django app which listens for pings and sends alerts when pings are late. (<b><code>&nbsp;&nbsp;8798⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;882🍴</code></b> [Source Code](https://github.com/healthchecks/healthchecks))) `BSD-3-Clause` `Python`
- <b><code>&nbsp;&nbsp;1236⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [HRConvert2](https://github.com/zelon88/HRConvert2)) - Drag-and-drop file conversion server with session based authentication, automatic temporary file maintenance, and logging capability. `GPL-3.0` `PHP`
- <b><code>&nbsp;45846⭐</code></b> <b><code>&nbsp;&nbsp;3945🍴</code></b> [Huginn](https://github.com/huginn/huginn)) - Allows you to build agents that monitor and act on your behalf. `MIT` `Ruby`
- 🌎 [Kestra](kestra.io) - Event-driven, language-agnostic platform to create, schedule, and monitor workflows. In code. Coordinate data pipelines and tasks such as ETL and ELT. (<b><code>&nbsp;16805⭐</code></b> <b><code>&nbsp;&nbsp;1430🍴</code></b> [Source Code](https://github.com/kestra-io/kestra))) `Apache-2.0` `Docker`
- 🌎 [Kibitzr](kibitzr.github.io) - Lightweight personal web assistant with powerful integrations. (<b><code>&nbsp;&nbsp;&nbsp;673⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [Source Code](https://github.com/kibitzr/kibitzr))) `MIT` `Python`
- 🌎 [LazyLibrarian](gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - LazyLibrarian is a program to follow authors and grab metadata for all your digital reading needs. It uses a combination of Goodreads Librarything and optionally GoogleBooks as sources for author info and book info. `GPL-3.0` `Python`
- 🌎 [Leon](getleon.ai) - Open-source personal assistant who can live on your server. (<b><code>&nbsp;16153⭐</code></b> <b><code>&nbsp;&nbsp;1340🍴</code></b> [Source Code](https://github.com/leon-ai/leon))) `MIT` `Nodejs`
- <b><code>&nbsp;&nbsp;2012⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;200🍴</code></b> [Matchering](https://github.com/sergree/matchering)) - A containerized web app for automated music mastering (alternative to LANDR, eMastered, and MajorDecibel). `GPL-3.0` `Docker`
- 🌎 [Mylar3](mylarcomics.com/) - Automated Comic Book (cbr/cbz) downloader program for use with NZB and torrents. (<b><code>&nbsp;&nbsp;1177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [Source Code](https://github.com/mylar3/mylar3))) `GPL-3.0` `Python/Docker`
- <b><code>&nbsp;&nbsp;2884⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [OliveTin](https://github.com/OliveTin/OliveTin)) - OliveTin is a web interface for running Linux shell commands. `AGPL-3.0` `Go`
- 🌎 [pyLoad](pyload.net/) - Lightweight, customizable and remotely manageable downloader for 1-click-hosting sites like rapidshare.com or uploaded.to. (<b><code>&nbsp;&nbsp;3473⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;721🍴</code></b> [Source Code](https://github.com/pyload/pyload))) `GPL-3.0` `Python`
- 🌎 [StackStorm](stackstorm.com) - StackStorm (aka _IFTTT for Ops_) is event-driven automation for auto-remediation, security responses, troubleshooting, deployments, and more. Includes rules engine, workflow, 160 integration packs with 6000+ actions and ChatOps. (<b><code>&nbsp;&nbsp;6219⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;753🍴</code></b> [Source Code](https://github.com/StackStorm/st2))) `Apache-2.0` `Python`
- <b><code>&nbsp;&nbsp;1254⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [µTask](https://github.com/ovh/utask)) - Automation engine that models and executes business processes declared in yaml. `BSD-3-Clause` `Go/Docker`


### Backup

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Backup](en.wikipedia.org/wiki/Backup) software.

**Please visit <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/Backups](https://github.com/awesome-foss/awesome-sysadmin#backups))**



### Blogging Platforms

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [blog](en.wikipedia.org/wiki/Blog) is a discussion or informational website consisting of discrete, diary-style text entries (posts).

_Related: [Static Site Generators](#static-site-generators), [Content Management Systems (CMS)](#content-management-systems-cms)_

_See also: 🌎 [WeblogMatrix](www.weblogmatrix.org/)_

- 🌎 [Antville](antville.org) - Free, open source project aimed at the development of a high performance, feature rich weblog hosting software. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Source Code](https://github.com/antville/antville))) `Apache-2.0` `Javascript`
- 🌎 [Castopod](castopod.org) - A podcast management hosting platform that includes the latest podcast 2.0 standards, an automated Fediverse feed, analytics, an embeddable player, and more.  🌎 [Source Code](code.castopod.org/adaures/castopod)) `AGPL-3.0` `PHP/Docker`
- 🌎 [Chyrp Lite](chyrplite.net) - Extra-awesome, extra-lightweight blog engine. (<b><code>&nbsp;&nbsp;&nbsp;427⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [Source Code](https://github.com/xenocrat/chyrp-lite))) `BSD-3-Clause` `PHP`
- 🌎 [Dotclear](git.dotclear.org/dev/dotclear) - Take control over your blog. `GPL-2.0` `PHP`
- 🌎 [FlatPress](flatpress.org/) - A lightweight, easy-to-set-up flat-file blogging engine. (<b><code>&nbsp;&nbsp;&nbsp;190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Source Code](https://github.com/flatpressblog/flatpress))) `GPL-2.0` `PHP`
- 🌎 [Ghost](ghost.org/) - Just a blogging platform. (<b><code>&nbsp;49000⭐</code></b> <b><code>&nbsp;10699🍴</code></b> [Source Code](https://github.com/TryGhost/Ghost))) `MIT` `Nodejs`
- 🌎 [Haven](havenweb.org/) - Private blogging system with markdown editing and built in RSS reader.  🌎 [Demo](havenweb.org/demo.html), <b><code>&nbsp;&nbsp;&nbsp;690⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Source Code](https://github.com/havenweb/haven))) `MIT` `Ruby`
- 🌎 [HTMLy](www.htmly.com/) - Databaseless PHP blogging platform. A flat-file CMS that allows you to create a fast, secure, and powerful website or blog in seconds. ([Demo](http://demo.htmly.com/), <b><code>&nbsp;&nbsp;1161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;275🍴</code></b> [Source Code](https://github.com/danpros/htmly)), 🌎 [Clients](www.htmly.com/theme/)) `GPL-2.0` `PHP`
- 🌎 [Known](withknown.com/) - A collaborative social publishing platform. (<b><code>&nbsp;&nbsp;1086⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;196🍴</code></b> [Source Code](https://github.com/idno/known))) `Apache-2.0` `PHP`
- 🌎 [Mataroa](mataroa.blog/) - Mataroa is a naked blogging platform for minimalists. (<b><code>&nbsp;&nbsp;&nbsp;282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Source Code](https://github.com/mataroa-blog/mataroa))) `MIT` `Python`
- 🌎 [PluXml](pluxml.org) - XML-based blog/CMS platform. (<b><code>&nbsp;&nbsp;&nbsp;227⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Source Code](https://github.com/pluxml/PluXml))) `GPL-3.0` `PHP`
- 🌎 [Serendipity](docs.s9y.org/) - Serendipity (s9y) is a highly extensible and customizable PHP blog engine using Smarty templating. (<b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/s9y/serendipity))) `BSD-3-Clause` `PHP`
- 🌎 [WriteFreely](writefreely.org) - Writing software for starting a minimalist, federated blog — or an entire community. (<b><code>&nbsp;&nbsp;4712⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;335🍴</code></b> [Source Code](https://github.com/writefreely/writefreely))) `AGPL-3.0` `Go`


### Booking and Scheduling

**[`^        back to top        ^`](#awesome-selfhosted)**

Event scheduling, reservation, and appointment management software.

_Related: [Polls and Events](#polls-and-events)_

- 🌎 [Alf.io](alf.io/) - Ticket reservation system.  🌎 [Demo](demo.alf.io/authentication), <b><code>&nbsp;&nbsp;1478⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;360🍴</code></b> [Source Code](https://github.com/alfio-event/alf.io))) `GPL-3.0` `Java`
- 🌎 [Cal.com](cal.com/) - The open-source online appointment scheduling system.  🌎 [Demo](app.cal.com/bailey), <b><code>&nbsp;35644⭐</code></b> <b><code>&nbsp;&nbsp;9134🍴</code></b> [Source Code](https://github.com/calcom/cal.com))) `AGPL-3.0` `Nodejs`
- 🌎 [Easy!Appointments](easyappointments.org/) - A highly customizable web application that allows your customers to book appointments with you via the web.  🌎 [Demo](demo.easyappointments.org/), <b><code>&nbsp;&nbsp;3581⭐</code></b> <b><code>&nbsp;&nbsp;1340🍴</code></b> [Source Code](https://github.com/alextselegidis/easyappointments))) `GPL-3.0` `PHP`
- 🌎 [Hi.Events](hi.events) - Event management and ticketing platform for conferences, concerts, and more. Offering customizable event pages and embeddable ticket widgets.  🌎 [Demo](demo.hi.events/event/1/dog-conf-2030), <b><code>&nbsp;&nbsp;2761⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;326🍴</code></b> [Source Code](https://github.com/HiEventsDev/hi.events))) `AGPL-3.0` `Docker`
- 🌎 [QloApps](qloapps.com/) - An open-source, customizable and intuitive web-based hotel reservation system and a booking engine.  🌎 [Demo](demo.qloapps.com/), <b><code>&nbsp;&nbsp;4670⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;551🍴</code></b> [Source Code](https://github.com/webkul/hotelcommerce))) `OSL-3.0` `PHP/Nodejs`
- 🌎 [Rallly](rallly.co) - Create polls to vote on dates and times (alternative to Doodle).  🌎 [Demo](app.rallly.co), <b><code>&nbsp;&nbsp;4183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;406🍴</code></b> [Source Code](https://github.com/lukevella/rallly))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Seatsurfing](seatsurfing.app/) - Webbased app to book seats, desks and rooms for offices. (<b><code>&nbsp;&nbsp;&nbsp;189⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Source Code](https://github.com/seatsurfing/backend))) `GPL-3.0` `Docker`


### Bookmarks and Link Sharing

**[`^        back to top        ^`](#awesome-selfhosted)**

Software which allows users to add, annotate, edit, and share [bookmarks](https://en.wikipedia.org/wiki/Bookmark_(digital)) of web documents.

- <b><code>&nbsp;&nbsp;1039⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [Briefkasten](https://github.com/ndom91/briefkasten)) - Modern app for saving and managing your own bookmarks. Includes a browser extension.  🌎 [Demo](briefkastenhq.com/auth/signin)) `MIT` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;6682⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;297🍴</code></b> [Buku](https://github.com/jarun/Buku)) - Powerful bookmark manager and a personal textual mini-web. `GPL-3.0` `Python/deb`
- 🌎 [Digibunch](ladigitale.dev/digibunch/#/) - Create bunches of links to share with your learners or colleagues.  🌎 [Demo](ladigitale.dev/digibunch/#/b/5f67b12092b60), 🌎 [Source Code](codeberg.org/ladigitale/digibunch)) `AGPL-3.0` `Nodejs/PHP`
- <b><code>&nbsp;&nbsp;&nbsp;828⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Espial](https://github.com/jonschoning/espial)) - An open-source, web-based bookmarking server. `AGPL-3.0` `Haskell`
- 🌎 [Firefox Account Server](mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html) - This allows you to host your own Firefox accounts server. (<b><code>&nbsp;&nbsp;&nbsp;628⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;212🍴</code></b> [Source Code](https://github.com/mozilla/fxa))) `MPL-2.0` `Nodejs/Java`
- 🌎 [Grimoire](grimoire.pro) - Bookmark manager with a modern UI, automatic content & metadata extraction, categorization, filtering, and more. It has fully documented REST API, and Docker image for easy deployment. (<b><code>&nbsp;&nbsp;2394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [Source Code](https://github.com/goniszewski/grimoire))) `MIT` `Nodejs/Docker`
- 🌎 [Karakeep](karakeep.app/) - Bookmark-everything app with a touch of AI for the data hoarders out there.  🌎 [Demo](try.karakeep.app/signin), <b><code>&nbsp;15005⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;591🍴</code></b> [Source Code](https://github.com/karakeep-app/karakeep))) `AGPL-3.0` `Docker`
- 🌎 [LinkAce](www.linkace.org/) - A bookmark archive with automatic backups to the Internet Archive, link monitoring, and a full REST API. Installation is done via Docker, or as a simple PHP application.  🌎 [Demo](demo.linkace.org/guest/links), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/Kovah/LinkAce/))) `GPL-3.0` `Docker/PHP`
- <b><code>&nbsp;&nbsp;7991⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;379🍴</code></b> [linkding](https://github.com/sissbruecker/linkding)) - Minimal bookmark management with a fast and clean UI. Simple installation through Docker and can run on your Raspberry Pi. `MIT` `Docker/Python/Nodejs`
- 🌎 [LinkWarden](linkwarden.app/) - A self-hosted bookmark + archive manager to store your useful links. (<b><code>&nbsp;11158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;424🍴</code></b> [Source Code](https://github.com/linkwarden/linkwarden))) `MIT` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [NeonLink](https://github.com/AlexSciFier/neonlink)) - Self-hosted bookmark service with unique design and simple installation with Docker. `MIT` `Docker`
- 🌎 [Readeck](readeck.org/en/) - Readeck is a simple web application that lets you save the precious readable content of web pages you like and want to keep forever. See it as a bookmark manager and a read later tool.  🌎 [Source Code](codeberg.org/readeck/readeck), 🌎 [Clients](codeberg.org/readeck/browser-extension)) `AGPL-3.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Servas](https://github.com/beromir/Servas)) - A self-hosted bookmark management tool. It allows organization with tags, groups, and a list specifically for later access. It supports multiple users with 2FA. Companion browser extensions are available for Firefox and Chrome. (<b><code>&nbsp;&nbsp;&nbsp;653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Clients](https://github.com/beromir/Servas#browser-extensions))) `GPL-3.0` `Docker/Nodejs/PHP`
- <b><code>&nbsp;&nbsp;3609⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;298🍴</code></b> [Shaarli](https://github.com/shaarli/Shaarli)) - Personal, minimalist, super-fast, no-database bookmarking and link sharing platform.  🌎 [Demo](demo.shaarli.org)) `Zlib` `PHP/deb`
- <b><code>&nbsp;10238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;577🍴</code></b> [Shiori](https://github.com/go-shiori/shiori)) - Simple bookmark manager built with Go. `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;2560⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;125🍴</code></b> [Slash](https://github.com/boojack/slash)) - An open source, self-hosted bookmarks and link sharing platform. `GPL-3.0` `Docker`
- 🌎 [SyncMarks](codeberg.org/Offerel/SyncMarks-Webapp) - Sync and manage your browser bookmarks from Edge, Firefox and Chromium.  🌎 [Clients](codeberg.org/Offerel/SyncMarks-Extension)) `AGPL-3.0` `PHP`


### Calendar & Contacts

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [CalDAV](en.wikipedia.org/wiki/CalDAV) and 🌎 [CardDAV](en.wikipedia.org/wiki/CardDAV) protocol servers and web clients/interfaces for 🌎 [Electronic calendar](en.wikipedia.org/wiki/Calendaring_software), 🌎 [address book](en.wikipedia.org/wiki/Address_book) and 🌎 [contact management](en.wikipedia.org/wiki/Contact_manager).

_Related: [Groupware](#groupware)_

_See also: 🌎 [Comparison of CalDAV and CardDAV implementations - Wikipedia](en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations)_

- 🌎 [Baïkal](sabre.io/baikal/) - Lightweight CalDAV and CardDAV server based on sabre/dav. (<b><code>&nbsp;&nbsp;2677⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;294🍴</code></b> [Source Code](https://github.com/sabre-io/Baikal))) `GPL-3.0` `PHP`
- 🌎 [DAViCal](www.davical.org/) - Server for calendar sharing (CalDAV) that uses a PostgreSQL database as a data store.  🌎 [Source Code](gitlab.com/davical-project/davical)) `GPL-2.0` `PHP/deb`
- <b><code>&nbsp;&nbsp;&nbsp;457⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Davis](https://github.com/tchapi/davis)) - A simple, dockerizable and fully translatable admin interface for sabre/dav based on Symfony 5 and Bootstrap 4, largely inspired by Baïkal. `MIT` `PHP`
- 🌎 [Etebase (EteSync)](www.etebase.com/) - End-to-end encrypted and journaled personal information server supporting calendar and contact data, offering its own clients. (<b><code>&nbsp;&nbsp;1634⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Source Code](https://github.com/etesync/server))) `AGPL-3.0` `Python/Django`
- <b><code>&nbsp;&nbsp;&nbsp;246⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Manage My Damn Life](https://github.com/intri-in/manage-my-damn-life-nextjs)) - Manage my Damn Life (MMDL) is a self-hosted front end for managing your CalDAV tasks and calendars. `GPL-3.0` `Nodejs/Docker`
- 🌎 [Radicale](radicale.org/) - Simple calendar and contact server with extremely low administrative overhead. (<b><code>&nbsp;&nbsp;3648⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;456🍴</code></b> [Source Code](https://github.com/Kozea/Radicale))) `GPL-3.0` `Python/deb`
- 🌎 [SabreDAV](sabre.io/) - Open source CardDAV, CalDAV, and WebDAV framework and server. (<b><code>&nbsp;&nbsp;1604⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;351🍴</code></b> [Source Code](https://github.com/sabre-io/dav))) `MIT` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;469⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Xandikos](https://github.com/jelmer/xandikos)) - Open source CardDAV and CalDAV server with minimal administrative overhead, backed by a Git repository. `GPL-3.0` `Python/deb`


### Communication - Custom Communication Systems

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Communication software](en.wikipedia.org/wiki/Communication_software) used to provide remote access to systems and exchange files and messages in text, audio and/or video formats between different computers or users, using their own custom protocols.

- 🌎 [AnyCable](anycable.io/) - Realtime server for reliable two-way communication over WebSockets, Server-sent events, etc.  🌎 [Demo](demo.anycable.io), <b><code>&nbsp;&nbsp;2033⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [Source Code](https://github.com/anycable/anycable))) `MIT` `Go/Docker`
- <b><code>&nbsp;13113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;449🍴</code></b> [Apprise](https://github.com/caronc/apprise)) - Apprise allows you to send a notification to almost all of the most popular notification services available to us today such as: Telegram, Discord, Slack, Amazon SNS, Gotify, etc. `MIT` `Python/Docker/deb`
- 🌎 [Centrifugo](centrifugal.dev/) - Language-agnostic real-time messaging (Websocket or SockJS) server. (<b><code>&nbsp;&nbsp;8891⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;619🍴</code></b> [Demo](https://github.com/centrifugal/centrifugo#demo)), <b><code>&nbsp;&nbsp;8891⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;619🍴</code></b> [Source Code](https://github.com/centrifugal/centrifugo))) `MIT` `Go/Docker/K8S`
- 🌎 [Chatwoot](www.chatwoot.com) - Self-hosted customer communication platform (alternative to Intercom & Zendesk). (<b><code>&nbsp;23185⭐</code></b> <b><code>&nbsp;&nbsp;4175🍴</code></b> [Source Code](https://github.com/chatwoot/chatwoot))) `MIT` `Ruby/Docker/K8S`
- 🌎 [Chitchatter](chitchatter.im/) - A peer-to-peer chat app that is serverless, decentralized, and ephemeral. (<b><code>&nbsp;&nbsp;1794⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;251🍴</code></b> [Source Code](https://github.com/jeremyckahn/chitchatter))) `GPL-2.0` `Nodejs`
- 🌎 [Conduit](conduit.rs/) - A simple, fast, and reliable chat server powered by Matrix.  🌎 [Source Code](gitlab.com/famedly/conduit)) `Apache-2.0` `Rust`
- <b><code>&nbsp;&nbsp;1006⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Databag](https://github.com/balzack/databag)) - Federated, end-to-end encrypted messaging service for the web, iOS, and Android, supporting text, photos, video, and WebRTC video and audio calls.  🌎 [Demo](databag.coredb.org/#/create)) `Apache-2.0` `Docker`
- 🌎 [Element](element.io) - Fully-featured Matrix client for Web, iOS & Android. (<b><code>&nbsp;11654⭐</code></b> <b><code>&nbsp;&nbsp;2156🍴</code></b> [Source Code](https://github.com/vector-im/element-web))) `Apache-2.0` `Nodejs`
- 🌎 [GlobaLeaks](www.globaleaks.org/) - Whistleblowing software enabling anyone to easily set up and maintain a secure reporting platform.  🌎 [Demo](demo.globaleaks.org), <b><code>&nbsp;&nbsp;1317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;289🍴</code></b> [Source Code](https://github.com/globaleaks/whistleblowing-software))) `AGPL-3.0` `Python/deb/Docker`
- 🌎 [GNUnet](gnunet.org/) - Free software framework for decentralized, peer-to-peer networking.  🌎 [Source Code](gnunet.org/git/)) `GPL-3.0` `C`
- 🌎 [Gotify](gotify.net/) - Self-hosted notification server with Android and CLI clients, similar to PushBullet. (<b><code>&nbsp;12335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;666🍴</code></b> [Source Code](https://github.com/gotify/server)), <b><code>&nbsp;&nbsp;1074⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [Clients](https://github.com/gotify/android))) `MIT` `Go/Docker`
- 🌎 [Hyphanet](hyphanet.org/) - Anonymously share files, browse and publish _freesites_ (web sites accessible only through Hyphanet) and chat on forums. (<b><code>&nbsp;&nbsp;1061⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [Source Code](https://github.com/hyphanet/fred))) `GPL-2.0` `Java`
- 🌎 [Jami](jami.net/) - Free and universal communication platform which preserves the user's privacy and freedoms (formerly GNU Ring).  🌎 [Source Code](git.jami.net/savoirfairelinux?sort=latest_activity_desc&filter=jami)) `GPL-3.0` `C++`
- 🌎 [Live Helper Chat](livehelperchat.com/) - Live Support chat for your website. (<b><code>&nbsp;&nbsp;2050⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;705🍴</code></b> [Source Code](https://github.com/LiveHelperChat/livehelperchat))) `Apache-2.0` `PHP`
- 🌎 [Mattermost](mattermost.com/) - Platform for secure collaboration across the entire software development lifecycle, can be integrated with Gitlab (alternative to Slack). (<b><code>&nbsp;32293⭐</code></b> <b><code>&nbsp;&nbsp;7699🍴</code></b> [Source Code](https://github.com/mattermost/mattermost))) `AGPL-3.0/Apache-2.0` `Go/Docker/K8S`
- 🌎 [MiAOU](miaou.dystroy.org/login) - Multi-room persistent chat server. (<b><code>&nbsp;&nbsp;&nbsp;545⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [Source Code](https://github.com/Canop/miaou))) `MIT` `Nodejs`
- 🌎 [Mumble](wiki.mumble.info/wiki/Main_Page) - Low-latency, high quality voice/text chat software. (<b><code>&nbsp;&nbsp;6785⭐</code></b> <b><code>&nbsp;&nbsp;1163🍴</code></b> [Source Code](https://github.com/mumble-voip/mumble)), 🌎 [Clients](wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++/deb`
- <b><code>&nbsp;&nbsp;&nbsp;801⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [Notifo](https://github.com/notifo-io/notifo)) - Multichannel notification server with support for Email, Mobile Push, Web Push, SMS, messaging and a javascript plugin. `MIT` `C#`
- 🌎 [Novu](novu.co/) - Self-hosted / cloud notification infrastructure for developers. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/novuhq/novu/))) `MIT` `Docker/Nodejs`
- 🌎 [ntfy](ntfy.sh/) - Push notifications to phone or desktop using HTTP PUT/POST, with Android app, CLI and web app, similar to Pushover and Gotify.  🌎 [Demo](ntfy.sh/app), <b><code>&nbsp;22386⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;887🍴</code></b> [Source Code](https://github.com/binwiederhier/ntfy)), <b><code>&nbsp;&nbsp;&nbsp;628⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [Clients](https://github.com/binwiederhier/ntfy-android))) `Apache-2.0/GPL-2.0` `Go/Docker/K8S`
- 🌎 [OTS](ots.fyi/) - One-Time-Secret sharing platform with a symmetric 256bit AES encryption in the browser. (<b><code>&nbsp;&nbsp;&nbsp;533⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Source Code](https://github.com/Luzifer/ots))) `Apache-2.0` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;336⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [PushBits](https://github.com/pushbits/server)) - Self-hosted notification server for relaying push notifications via Matrix, similar to PushBullet and Gotify. `ISC` `Go`
- 🌎 [RetroShare](retroshare.cc) - Secured and decentralized communication system. Offers decentralized chat, forums, messaging, file transfer. (<b><code>&nbsp;&nbsp;1802⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;285🍴</code></b> [Source Code](https://github.com/RetroShare/RetroShare))) `GPL-2.0` `C++`
- 🌎 [Revolt](revolt.chat/) - Revolt is a user-first chat platform built with modern web technologies. (<b><code>&nbsp;&nbsp;1266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [Source Code](https://github.com/revoltchat/self-hosted))) `AGPL-3.0` `Rust`
- 🌎 [Rocket.Chat](rocket.chat/) - Teamchat solution similar to Gitter.im or Slack. (<b><code>&nbsp;42457⭐</code></b> <b><code>&nbsp;11635🍴</code></b> [Source Code](https://github.com/RocketChat/Rocket.Chat))) `MIT` `Nodejs/Docker/K8S`
- 🌎 [SAMA](samacloud.io) - Next-Gen self-hosted chat server and clients.  🌎 [Demo](app.samacloud.io/demo), <b><code>&nbsp;&nbsp;&nbsp;118⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Source Code](https://github.com/SAMA-Communications/sama-server)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Clients](https://github.com/SAMA-Communications/sama-client))) `GPL-3.0` `Nodejs/Docker`
- 🌎 [Screego](screego.net) - Screego is a simple tool to quickly share your screen to one or multiple people via web browser.  🌎 [Demo](app.screego.net/), <b><code>&nbsp;&nbsp;8472⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;611🍴</code></b> [Source Code](https://github.com/screego/server))) `GPL-3.0` `Docker/Go`
- <b><code>&nbsp;&nbsp;&nbsp;398⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Shhh](https://github.com/smallwat3r/shhh)) - Keep secrets out of emails or chat logs, share them using secure links with passphrase and expiration dates. `MIT` `Python`
- <b><code>&nbsp;&nbsp;8304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;403🍴</code></b> [SimpleX Chat](https://github.com/simplex-chat/simplex-chat)) - The most private and secure chat and applications platform - now with double ratchet E2E encryption. `AGPL-3.0` `Haskell`
- 🌎 [Spectrum 2](spectrum.im/) - Spectrum 2 is an open source instant messaging transport.  It allows users to chat together even when they are using different IM networks. (<b><code>&nbsp;&nbsp;&nbsp;411⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [Source Code](https://github.com/SpectrumIM/spectrum2))) `GPL-3.0` `C++`
- 🌎 [Synapse](element-hq.github.io/synapse/latest/index.html) - Server for 🌎 [Matrix](matrix.org/), an open standard for decentralized persistent communication. (<b><code>&nbsp;&nbsp;2257⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;287🍴</code></b> [Source Code](https://github.com/element-hq/synapse))) `Apache-2.0` `Python/deb`
- 🌎 [Syndie](syndie.de) - Syndie is a libre system for operating distributed forums. `CC0-1.0` `Java`
- 🌎 [Tailchat](tailchat.msgbyte.com/) - Next generation noIM application in your own workspace, not only another Slack/Discord/rocket.chat.  🌎 [Demo](nightly.paw.msgbyte.com/), <b><code>&nbsp;&nbsp;3197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;343🍴</code></b> [Source Code](https://github.com/msgbyte/tailchat))) `Apache-2.0` `Docker/K8S/Nodejs`
- 🌎 [Tiledesk](tiledesk.com) - All-in-one customer engagement platform from lead-gen to post-sales, from WhatsApp to your website. With omni-channel live agents and AI-powered chatbots (alternative to Intercom, Zendesk, Tawk.to and Tidio). (<b><code>&nbsp;&nbsp;&nbsp;209⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [Source Code](https://github.com/Tiledesk/tiledesk))) `MIT` `Docker/K8S`
- [Tinode](https://github.com/tinode) - Instant messaging platform. Backend in Go. Clients: Swift iOS, Java Android, JS webapp, scriptable command line; chatbots.  🌎 [Demo](sandbox.tinode.co/), <b><code>&nbsp;12397⭐</code></b> <b><code>&nbsp;&nbsp;1934🍴</code></b> [Source Code](https://github.com/tinode/chat)), <b><code>&nbsp;&nbsp;&nbsp;336⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;202🍴</code></b> [Clients](https://github.com/tinode/webapp))) `GPL-3.0` `Go`
- 🌎 [Tox](tox.chat/) - Distributed, secure messenger with audio and video chat capabilities. (<b><code>&nbsp;&nbsp;2382⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;293🍴</code></b> [Source Code](https://github.com/TokTok/c-toxcore))) `GPL-3.0` `C`
- 🌎 [Typebot](typebot.io) - Conversational app builder (alternative to Typeform or Landbot). (<b><code>&nbsp;&nbsp;8460⭐</code></b> <b><code>&nbsp;&nbsp;2440🍴</code></b> [Source Code](https://github.com/baptisteArno/typebot.io))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;2322⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;446🍴</code></b> [WBO](https://github.com/lovasoa/whitebophir)) - Web Whiteboard to collaborate in real-time on schemas, drawings, and notes.  🌎 [Demo](wbo.ophir.dev/)) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Zulip](zulip.org) - Zulip is a powerful, open source group chat application. (<b><code>&nbsp;22631⭐</code></b> <b><code>&nbsp;&nbsp;8451🍴</code></b> [Source Code](https://github.com/zulip/zulip))) `Apache-2.0` `Python`


### Communication - Email - Complete Solutions

**[`^        back to top        ^`](#awesome-selfhosted)**

Simple deployment of 🌎 [E-mail](en.wikipedia.org/wiki/Email) servers, e.g. for inexperienced or impatient admins.

- 🌎 [AnonAddy](anonaddy.com) - Email forwarding service for creating aliases. (<b><code>&nbsp;&nbsp;3728⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;195🍴</code></b> [Source Code](https://github.com/anonaddy/anonaddy))) `MIT` `PHP/Docker`
- 🌎 [DebOps](docs.debops.org/) - Your Debian-based data center in a box. A set of general-purpose Ansible roles that can be used to manage Debian or Ubuntu hosts. (<b><code>&nbsp;&nbsp;1299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;356🍴</code></b> [Source Code](https://github.com/debops/debops))) `GPL-3.0` `Ansible/Python`
- 🌎 [docker-mailserver](docker-mailserver.github.io/docker-mailserver/edge/) - Production-ready fullstack but simple mail server (SMTP, IMAP, LDAP, Antispam, Antivirus, etc.) running inside a container. Only configuration files, no SQL database. (<b><code>&nbsp;15750⭐</code></b> <b><code>&nbsp;&nbsp;1903🍴</code></b> [Source Code](https://github.com/docker-mailserver/docker-mailserver))) `MIT` `Docker`
- 🌎 [Dovel](dovel.email) - SMTP server that sends and receives emails according to a simple configuration file, with an optional web interface that you can use to browse your emails.  🌎 [Source Code](dovel.email/server/tree.html)) `LGPL-3.0` `Go`
- <b><code>&nbsp;&nbsp;1919⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;321🍴</code></b> [emailwiz](https://github.com/LukeSmithxyz/emailwiz)) - Luke Smith's bash script to completely automate the setup of a Postfix/Dovecot/SpamAssassin/OpenDKIM server on debian. `GPL-3.0` `Shell`
- <b><code>&nbsp;&nbsp;&nbsp;485⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [homebox](https://github.com/progmaticltd/homebox)) - Suite of Ansible scripts to deploy a fully functional mail server on Debian. Unobtrusive and automatic as much as possible, focusing on stability and security. `GPL-3.0` `Shell`
- 🌎 [Inboxen](inboxen.org) - Inboxen is a service that provides you with an infinite number of unique inboxes.  🌎 [Source Code](codeberg.org/Inboxen/Inboxen)) `GPL-3.0` `Python`
- 🌎 [iRedMail](www.iredmail.org/) - Full-featured mail server solution based on Postfix and Dovecot. (<b><code>&nbsp;&nbsp;1587⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;223🍴</code></b> [Source Code](https://github.com/iredmail/iRedMail))) `GPL-3.0` `Shell`
- <b><code>&nbsp;&nbsp;5476⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;277🍴</code></b> [Maddy Mail Server](https://github.com/foxcpp/maddy)) - All-in-one mail server that implements SMTP (both MTA and MX) and IMAP. Replaces Postfix, Dovecot, OpenDKIM, OpenSPF, OpenDMARC with single daemon. `GPL-3.0` `Go`
- 🌎 [Mail-in-a-Box](mailinabox.email/) - Turns any Ubuntu server into a fully functional mail server with one command. (<b><code>&nbsp;14401⭐</code></b> <b><code>&nbsp;&nbsp;1474🍴</code></b> [Source Code](https://github.com/mail-in-a-box/mailinabox))) `CC0-1.0` `Shell`
- 🌎 [Mailcow](mailcow.email/) - Mail server suite based on Dovecot, Postfix and other open source software, that provides a modern Web UI for administration. (<b><code>&nbsp;10059⭐</code></b> <b><code>&nbsp;&nbsp;1296🍴</code></b> [Source Code](https://github.com/mailcow/mailcow-dockerized))) `GPL-2.0` `Docker/PHP`
- 🌎 [Mailu](mailu.io/) - Mailu is a simple yet full-featured mail server as a set of Docker images. (<b><code>&nbsp;&nbsp;6371⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;882🍴</code></b> [Source Code](https://github.com/Mailu/Mailu))) `MIT` `Docker/Python`
- 🌎 [Modoboa](modoboa.org/en/) - Modoboa is a mail hosting and management platform including a modern and simplified Web User Interface. (<b><code>&nbsp;&nbsp;3211⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;422🍴</code></b> [Source Code](https://github.com/modoboa/modoboa))) `ISC` `Python`
- 🌎 [Mox](www.xmox.nl/) - Complete e-mail solution with IMAP4, SMTP, SPF, DKIM, DMARC, MTA-STS, DANE and DNSSEC, reputation-based and content-based junk filtering, Internationalization (IDNA), automatic TLS with ACME and Let's Encrypt, account autoconfiguration, and webmail. (<b><code>&nbsp;&nbsp;4792⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;145🍴</code></b> [Source Code](https://github.com/mjl-/mox))) `MIT` `Go`
- 🌎 [Postal](docs.postalserver.io/) - A complete and fully featured mail server for use by websites & web servers. (<b><code>&nbsp;15406⭐</code></b> <b><code>&nbsp;&nbsp;1107🍴</code></b> [Source Code](https://github.com/postalserver/postal))) `MIT` `Docker/Ruby`
- 🌎 [Simple NixOS Mailserver](gitlab.com/simple-nixos-mailserver/nixos-mailserver) - Complete mailserver solution leveraging the Nix Ecosystem. `GPL-3.0` `Nix`
- 🌎 [SimpleLogin](simplelogin.io) - Open source email alias solution to protect your email address. Comes with browser extensions and mobile apps. (<b><code>&nbsp;&nbsp;5615⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;473🍴</code></b> [Source Code](https://github.com/simple-login/app))) `MIT` `Docker/Python`
- 🌎 [Stalwart Mail Server](stalw.art) - All-in-one mail server with JMAP, IMAP4, and SMTP support and a wide range of modern features. (<b><code>&nbsp;&nbsp;7286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;342🍴</code></b> [Source Code](https://github.com/stalwartlabs/mail-server))) `AGPL-3.0` `Rust/Docker`
- 🌎 [wildduck](wildduck.email/) - Scalable no-SPOF IMAP/POP3 mail server. (<b><code>&nbsp;&nbsp;1977⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;272🍴</code></b> [Source Code](https://github.com/nodemailer/wildduck))) `EUPL-1.2` `Nodejs/Docker`


### Communication - Email - Mail Delivery Agents

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Mail Delivery Agents](en.wikipedia.org/wiki/Message_delivery_agent) (MDAs) - 🌎 [IMAP](en.wikipedia.org/wiki/Internet_Message_Access_Protocol) 🌎 [POP3](en.wikipedia.org/wiki/Post_Office_Protocol) server software.

- 🌎 [Cyrus IMAP](www.cyrusimap.org/) - Email (IMAP/POP3), contacts and calendar server. (<b><code>&nbsp;&nbsp;&nbsp;575⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [Source Code](https://github.com/cyrusimap/cyrus-imapd))) `BSD-3-Clause-Attribution` `C`
- 🌎 [DavMail](davmail.sourceforge.net/) `⚠` - POP/IMAP/SMTP/Caldav/Carddav/LDAP exchange gateway allowing users to use any mail/calendar client with an Exchange server, even from the internet or behind a firewall through Outlook Web Access. (<b><code>&nbsp;&nbsp;&nbsp;620⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Source Code](https://github.com/mguessan/davmail))) `GPL-2.0` `Java`
- 🌎 [Dovecot](www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind. (<b><code>&nbsp;&nbsp;1049⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;299🍴</code></b> [Source Code](https://github.com/dovecot/core))) `MIT/LGPL-2.1` `C/deb`
- 🌎 [Piler](www.mailpiler.org/) - Feature-rich email archiving solution. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/jsuto/piler/))) `GPL-3.0` `C`


### Communication - Email - Mail Transfer Agents

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Mail Transfer Agents](en.wikipedia.org/wiki/Message_transfer_agent) (MTAs) - 🌎 [SMTP](en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol) servers.

- 🌎 [chasquid](blitiri.com.ar/p/chasquid/) - SMTP (email) server with a focus on simplicity, security, and ease of operation.  🌎 [Source Code](blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- 🌎 [Courier MTA](www.courier-mta.org/) - Fast, scalable, enterprise mail/groupware server providing ESMTP, IMAP, POP3, webmail, mailing list, basic web-based calendaring and scheduling services.  🌎 [Source Code](www.courier-mta.org/repo.html)) `GPL-3.0` `C/deb`
- <b><code>&nbsp;&nbsp;&nbsp;240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [DragonFly](https://github.com/corecode/dma)) - A small MTA for home and office use. Works on Linux and FreeBSD. `BSD-3-Clause` `C`
- 🌎 [EmailRelay](emailrelay.sourceforge.net/) - A small and easy to configure SMTP and POP3 server for Windows and Linux.  🌎 [Source Code](sourceforge.net/p/emailrelay/code/HEAD/tree/)) `GPL-3.0` `C++`
- 🌎 [Exim](www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge.  🌎 [Source Code](git.exim.org/exim.git)) `GPL-3.0` `C/deb`
- 🌎 [Haraka](haraka.github.io/) - High-performance, pluginable SMTP server written in Javascript. (<b><code>&nbsp;&nbsp;5233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;663🍴</code></b> [Source Code](https://github.com/haraka/Haraka))) `MIT` `Nodejs`
- 🌎 [MailCatcher](mailcatcher.me/) - Ruby gem that deploys a simply SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. (<b><code>&nbsp;&nbsp;6595⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;588🍴</code></b> [Source Code](https://github.com/sj26/mailcatcher))) `MIT` `Ruby`
- 🌎 [OpenSMTPD](opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project.  🌎 [Source Code](cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C/deb`
- <b><code>&nbsp;&nbsp;&nbsp;686⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [OpenTrashmail](https://github.com/HaschekSolutions/opentrashmail)) - Complete trashmail solution that exposes an SMTP server and has a web interface to manage received emails. Works with multiple and wildcard domains and is fully file based (no database needed). Includes RSS feeds and JSON API. `Apache-2.0` `Python/PHP/Docker`
- [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement. `IPL-1.0` `C/deb`
- 🌎 [Sendmail](www.proofpoint.com/us/products/email-protection/open-source-email-solution) - Message transfer agent (MTA). `Sendmail` `C/deb`
- 🌎 [Slimta](slimta.github.io/) - Mail Transfer Library built on Python. (<b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Source Code](https://github.com/slimta/python-slimta))) `MIT` `Python`


### Communication - Email - Mailing Lists and Newsletters

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Mailing list](en.wikipedia.org/wiki/Mailing_list) servers and mass mailing software - one message to many recipients.

- 🌎 [HyperKitty](wiki.list.org/HyperKitty) - Open source Django application to provide a web interface to access GNU Mailman v3 archives.  🌎 [Demo](lists.mailman3.org/), 🌎 [Source Code](gitlab.com/mailman/hyperkitty)) `GPL-3.0` `Python`
- 🌎 [Keila](www.keila.io) - Self-hosted reliable and easy-to-use newsletter tool (alternative to Mailchimp or Sendinblue).  🌎 [Demo](app.keila.io), <b><code>&nbsp;&nbsp;1650⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [Source Code](https://github.com/pentacent/keila))) `AGPL-3.0` `Docker`
- 🌎 [Listmonk](listmonk.app/) - High performance, self-hosted newsletter and mailing list manager with a modern dashboard. (<b><code>&nbsp;16452⭐</code></b> <b><code>&nbsp;&nbsp;1539🍴</code></b> [Source Code](https://github.com/knadh/listmonk))) `AGPL-3.0` `Go/Docker`
- 🌎 [Mailman](www.gnu.org/software/mailman/) - The Gnu mailing list server. `GPL-3.0` `Python`
- 🌎 [Mautic](www.mautic.org/) - Mautic is marketing automation software (email, social and more). (<b><code>&nbsp;&nbsp;7947⭐</code></b> <b><code>&nbsp;&nbsp;2804🍴</code></b> [Source Code](https://github.com/mautic/mautic))) `GPL-3.0` `PHP`
- 🌎 [phpList](www.phplist.org) - Newsletter and email marketing with advanced management of subscribers, bounces, and plugins. (<b><code>&nbsp;&nbsp;&nbsp;784⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;274🍴</code></b> [Source Code](https://github.com/phpList/phplist3))) `AGPL-3.0` `PHP`
- 🌎 [Postorius](docs.mailman3.org/projects/postorius/en/latest/) - Web user interface to access GNU Mailman.  🌎 [Source Code](gitlab.com/mailman/postorius/)) `GPL-3.0` `Python`
- 🌎 [Schleuder](schleuder.nadir.org/) - GPG-enabled mailing list manager with resending-capabilities.  🌎 [Source Code](0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- 🌎 [Sympa](www.sympa.community/) - Mailing list manager. (<b><code>&nbsp;&nbsp;&nbsp;261⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [Source Code](https://github.com/sympa-community/sympa))) `GPL-2.0` `Perl`


### Communication - Email - Webmail Clients

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Webmail](en.wikipedia.org/wiki/Webmail) clients.

- 🌎 [Cypht](cypht.org) - Feed reader for your email accounts. (<b><code>&nbsp;&nbsp;1076⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [Source Code](https://github.com/cypht-org/cypht))) `LGPL-2.1` `PHP`
- 🌎 [Roundcube](roundcube.net) - Browser-based IMAP client with an application-like user interface. (<b><code>&nbsp;&nbsp;6192⭐</code></b> <b><code>&nbsp;&nbsp;1667🍴</code></b> [Source Code](https://github.com/roundcube/roundcubemail))) `GPL-3.0` `PHP/deb`
- 🌎 [SnappyMail](snappymail.eu/) - Simple, modern, lightweight & fast web-based email client (fork of RainLoop).  🌎 [Demo](snappymail.eu/demo/), <b><code>&nbsp;&nbsp;1210⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [Source Code](https://github.com/the-djmaze/snappymail))) `AGPL-3.0` `PHP`
- 🌎 [SquirrelMail](squirrelmail.org) - Another browser-based IMAP client.  🌎 [Source Code](sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`


### Communication - IRC

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [IRC](en.wikipedia.org/wiki/Internet_Relay_Chat) communication software.

- 🌎 [Convos](convos.chat/) - Always online web IRC client.  🌎 [Demo](convos.chat/#instant-demo), <b><code>&nbsp;&nbsp;1078⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [Source Code](https://github.com/convos-chat/convos))) `Artistic-2.0` `Perl/Docker`
- 🌎 [Ergo](ergo.chat/) - Modern IRCv3 server written in Go, combining the features of an ircd, a services framework, and a bouncer. (<b><code>&nbsp;&nbsp;2796⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;200🍴</code></b> [Source Code](https://github.com/ergochat/ergo))) `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;954⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;181🍴</code></b> [Glowing Bear](https://github.com/glowing-bear/glowing-bear)) - A web frontend for WeeChat.  🌎 [Demo](www.glowing-bear.org)) `GPL-3.0` `Nodejs`
- 🌎 [InspIRCd](www.inspircd.org/) - Modular IRC server written in C++ for Linux, BSD, Windows, and macOS. (<b><code>&nbsp;&nbsp;1220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;269🍴</code></b> [Source Code](https://github.com/inspircd/inspircd))) `GPL-2.0` `C++/Docker`
- 🌎 [Kiwi IRC](kiwiirc.com/) - Responsive web IRC client with theming support.  🌎 [Demo](kiwiirc.com/nextclient/), <b><code>&nbsp;&nbsp;&nbsp;898⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [Source Code](https://github.com/kiwiirc/kiwiirc))) `Apache-2.0` `Nodejs`
- 🌎 [ngircd](ngircd.barton.de/) - Free, portable and lightweight Internet Relay Chat server for small or private networks. (<b><code>&nbsp;&nbsp;&nbsp;468⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [Source Code](https://github.com/ngircd/ngircd))) `GPL-2.0` `C/deb`
- 🌎 [Quassel IRC](quassel-irc.org/) - Distributed IRC client, meaning that one (or multiple) client(s) can attach to and detach from a central core. (<b><code>&nbsp;&nbsp;&nbsp;736⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [Source Code](https://github.com/quassel/quassel))) `GPL-2.0` `C++`
- 🌎 [Robust IRC](robustirc.net/) - RobustIRC is IRC without netsplits. Distributed IRC server, based on RobustSession protocol. (<b><code>&nbsp;&nbsp;&nbsp;181⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Source Code](https://github.com/robustirc/robustirc))) `BSD-3-Clause` `Go`
- 🌎 [The Lounge](thelounge.chat/) - Self-hosted web IRC client.  🌎 [Demo](demo.thelounge.chat/), <b><code>&nbsp;&nbsp;5842⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;703🍴</code></b> [Source Code](https://github.com/thelounge/thelounge))) `MIT` `Nodejs/Docker`
- 🌎 [UnrealIRCd](www.unrealircd.org/) - Modular, advanced and highly configurable IRC server written in C for Linux, BSD, Windows, and macOS. (<b><code>&nbsp;&nbsp;&nbsp;448⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [Source Code](https://github.com/unrealircd/unrealircd))) `GPL-2.0` `C`
- 🌎 [Weechat](weechat.org/) - Fast, light and extensible chat client. (<b><code>&nbsp;&nbsp;3070⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;335🍴</code></b> [Source Code](https://github.com/weechat/weechat))) `GPL-3.0` `C/Docker/deb`
- 🌎 [ZNC](wiki.znc.in/ZNC) - Advanced IRC bouncer. (<b><code>&nbsp;&nbsp;2043⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;381🍴</code></b> [Source Code](https://github.com/znc/znc))) `Apache-2.0` `C++/deb`


### Communication - SIP

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [SIP](en.wikipedia.org/wiki/Session_Initiation_Protocol) 🌎 [IPBX](en.wikipedia.org/wiki/IP_PBX) telephony software.

- 🌎 [Asterisk](www.asterisk.org/) - Easy to use but advanced IP PBX system, VoIP gateway and conference server. (<b><code>&nbsp;&nbsp;2491⭐</code></b> <b><code>&nbsp;&nbsp;1036🍴</code></b> [Source Code](https://github.com/asterisk/asterisk))) `GPL-2.0` `C/deb`
- 🌎 [Eqivo](eqivo.org/) - Eqivo implements an API layer on top of FreeSWITCH facilitating integration between web applications and voice/video-enabled endpoints such as traditional phone lines (PSTN), VoIP phones, webRTC clients etc. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;84⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Source Code](https://github.com/rtckit/eqivo))) `MIT` `Docker/PHP`
- 🌎 [Flexisip](www.linphone.org/en/flexisip-sip-server/) - A complete, modular and scalable SIP server, includes a push gateway, to deliver SIP incoming calls or text messages on mobile device platforms where push notifications are required to receive information when the app is not active in the foreground. (<b><code>&nbsp;&nbsp;&nbsp;161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [Source Code](https://github.com/BelledonneCommunications/flexisip))) `AGPL-3.0` `C/Docker`
- 🌎 [Freepbx](www.freepbx.org) - Web-based open source GUI that controls and manages Asterisk.  🌎 [Source Code](git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- 🌎 [FreeSWITCH](freeswitch.org/) - Scalable open source cross-platform telephony platform. (<b><code>&nbsp;&nbsp;3968⭐</code></b> <b><code>&nbsp;&nbsp;1512🍴</code></b> [Source Code](https://github.com/signalwire/freeswitch))) `MPL-2.0` `C`
- 🌎 [FusionPBX](www.fusionpbx.com/) - Open source project that provides a customizable and flexible web interface to the very powerful and highly scalable multi-platform voice switch called FreeSWITCH. (<b><code>&nbsp;&nbsp;&nbsp;843⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;683🍴</code></b> [Source Code](https://github.com/fusionpbx/fusionpbx))) `MPL-1.1` `PHP`
- 🌎 [Kamailio](www.kamailio.org/w/) - Modular SIP server (registrar/proxy/router/etc). (<b><code>&nbsp;&nbsp;2424⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;988🍴</code></b> [Source Code](https://github.com/kamailio/kamailio))) `GPL-2.0` `C/deb`
- 🌎 [openSIPS](opensips.org/) - OpenSIPS is an Open Source SIP proxy/server for voice, video, IM, presence and any other SIP extensions. (<b><code>&nbsp;&nbsp;1339⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;597🍴</code></b> [Source Code](https://github.com/OpenSIPS/opensips))) `GPL-2.0` `C`
- 🌎 [Routr](routr.io) - A lightweight sip proxy, location server, and registrar for a reliable and scalable SIP infrastructure. (<b><code>&nbsp;&nbsp;1504⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [Source Code](https://github.com/fonoster/routr))) `MIT` `Docker/K8S`
- 🌎 [SIP3](sip3.io/) - VoIP troubleshooting and monitoring platform.  🌎 [Demo](demo.sip3.io), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/sip3io/))) `Apache-2.0` `Java`
- 🌎 [SIPCAPTURE Homer](www.sipcapture.org/) - Troubleshooting and monitoring VoIP calls. (<b><code>&nbsp;&nbsp;1747⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;251🍴</code></b> [Source Code](https://github.com/sipcapture/homer))) `AGPL-3.0` `Nodejs/Go/Docker`
- 🌎 [Wazo](wazo-platform.org/) - Full-featured IPBX solution built atop Asterisk with integrated Web administration interface and REST-ful API. ([Source Code](https://github.com/wazo-platform)) `GPL-3.0` `Python`
- 🌎 [Yeti-Switch](yeti-switch.org/) - Transit class4 softswitch(SBC) with integrated billing and routing engine and REST API.  🌎 [Demo](yeti-switch.org/demo.html), [Source Code](https://github.com/yeti-switch)) `GPL-2.0` `C++/Ruby`


### Communication - Social Networks and Forums

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Social Networking](en.wikipedia.org/wiki/Social_networking_service) and 🌎 [Forum](en.wikipedia.org/wiki/Internet_forum) software.

- 🌎 [Akkoma](akkoma.social/) - Federated microblogging server with Mastodon, GNU social, and ActivityPub compatibility.  🌎 [Source Code](akkoma.dev/AkkomaGang/akkoma)) `AGPL-3.0` `Elixir/Docker`
- 🌎 [Answer](answer.dev/) - Knowledge-based community software. You can use it to quickly build your Q&A community for product technical support, customer support, user communication, and more. (<b><code>&nbsp;14243⭐</code></b> <b><code>&nbsp;&nbsp;1136🍴</code></b> [Source Code](https://github.com/answerdev/answer))) `Apache-2.0` `Docker/Go`
- 🌎 [Artalk](artalk.js.org/) - Comment system built in Golang, providing a lightweight and highly customizable solution for adding comments to your website. (<b><code>&nbsp;&nbsp;1865⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [Source Code](https://github.com/ArtalkJS/Artalk))) `MIT` `Go/Docker`
- 🌎 [AsmBB](board.asm32.info) - Fast, SQLite-powered forum engine written in ASM.  🌎 [Source Code](asm32.info/fossil/asmbb/index)) `EUPL-1.2` `Assembly`
- 🌎 [BuddyPress](buddypress.org/about/) - Powerful plugin that takes your WordPress.org powered site beyond the blog with social-network features like user profiles, activity streams, user groups, and more. (<b><code>&nbsp;&nbsp;&nbsp;232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [Source Code](https://github.com/buddypress/BuddyPress))) `GPL-2.0` `PHP`
- 🌎 [Chirpy](chirpy.dev) - Chirpy is an open-source, privacy-friendly and customizable Disqus (comment system) alternate.  🌎 [Demo](chirpy.dev/play), <b><code>&nbsp;&nbsp;&nbsp;577⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Source Code](https://github.com/devrsi0n/chirpy))) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Coral](coralproject.net/) - A better commenting experience from Vox Media. (<b><code>&nbsp;&nbsp;1934⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;361🍴</code></b> [Source Code](https://github.com/coralproject/talk))) `Apache-2.0` `Docker/Nodejs`
- 🌎 [diaspora*](diasporafoundation.org/) - Distributed social networking server. (<b><code>&nbsp;13466⭐</code></b> <b><code>&nbsp;&nbsp;2918🍴</code></b> [Source Code](https://github.com/diaspora/diaspora))) `AGPL-3.0` `Ruby`
- 🌎 [Discourse](www.discourse.org/) - Advanced forum / community solution based on Ruby and JS.  🌎 [Demo](try.discourse.org/), <b><code>&nbsp;43720⭐</code></b> <b><code>&nbsp;&nbsp;8501🍴</code></b> [Source Code](https://github.com/discourse/discourse))) `GPL-2.0` `Docker`
- 🌎 [Elgg](elgg.org/) - Powerful open source social networking engine. (<b><code>&nbsp;&nbsp;1652⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;662🍴</code></b> [Source Code](https://github.com/Elgg/Elgg))) `GPL-2.0` `PHP`
- 🌎 [Enigma 1/2 BBS](nuskooler.github.io/enigma-bbs/) - Enigma 1/2 is a modern, multi-platform BBS engine with unlimited "callers" and legacy DOS door game support. (<b><code>&nbsp;&nbsp;&nbsp;574⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Source Code](https://github.com/NuSkooler/enigma-bbs))) `BSD-2-Clause` `Shell/Docker/Nodejs`
- 🌎 [Flarum](flarum.org) - Delightfully simple forums. Flarum is the next-generation forum software that makes online discussion fun again. (<b><code>&nbsp;15689⭐</code></b> <b><code>&nbsp;&nbsp;1620🍴</code></b> [Source Code](https://github.com/flarum/flarum))) `MIT` `PHP`
- 🌎 [Friendica](friendi.ca/) - Social Communication Server. (<b><code>&nbsp;&nbsp;1544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;355🍴</code></b> [Source Code](https://github.com/friendica/friendica))) `AGPL-3.0` `PHP`
- <b><code>&nbsp;&nbsp;4112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;373🍴</code></b> [GoToSocial](https://github.com/superseriousbusiness/gotosocial)) - ActivityPub federated social network server implementing the Mastodon client API. `AGPL-3.0` `Docker/Go`
- 🌎 [Hatsu](hatsu.cli.rs/) - Bridge that interacts with Fediverse on behalf of your static site. (<b><code>&nbsp;&nbsp;&nbsp;188⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Source Code](https://github.com/importantimport/hatsu))) `AGPL-3.0` `Docker/Rust`
- 🌎 [Hubzilla](hubzilla.org) - Decentralized identity, privacy, publishing, sharing, cloud storage, and communications/social platform.  🌎 [Source Code](framagit.org/hubzilla/core)) `MIT` `PHP`
- 🌎 [HumHub](www.humhub.org/) - Flexible kit for private social networks. (<b><code>&nbsp;&nbsp;6420⭐</code></b> <b><code>&nbsp;&nbsp;1672🍴</code></b> [Source Code](https://github.com/humhub/humhub))) `AGPL-3.0` `PHP`
- 🌎 [Isso](isso-comments.de/) - Lightweight commenting server written in Python and Javascript. It aims to be a drop-in replacement for Disqus. (<b><code>&nbsp;&nbsp;5131⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;440🍴</code></b> [Source Code](https://github.com/posativ/isso))) `MIT` `Python/Docker`
- 🌎 [Lemmy](join-lemmy.org/) - A link aggregator / reddit clone for the fediverse (alternative to Reddit). (<b><code>&nbsp;13692⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;918🍴</code></b> [Source Code](https://github.com/LemmyNet/lemmy))) `AGPL-3.0` `Docker/Rust`
- <b><code>&nbsp;&nbsp;5098⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [Libreddit](https://github.com/libreddit/libreddit)) `⚠` - Private front-end for Reddit written in Rust. `AGPL-3.0` `Rust`
- 🌎 [Loomio](www.loomio.org/) - Loomio is a collaborative decision-making tool that makes it easy for anyone to participate in decisions which affect them. (<b><code>&nbsp;&nbsp;2428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;693🍴</code></b> [Source Code](https://github.com/loomio/loomio))) `AGPL-3.0` `Docker`
- 🌎 [Mastodon](joinmastodon.org/) - Federated microblogging server. (<b><code>&nbsp;48103⭐</code></b> <b><code>&nbsp;&nbsp;7155🍴</code></b> [Source Code](https://github.com/mastodon/mastodon)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Clients](https://github.com/hyperupcall/awesome-mastodon))) `AGPL-3.0` `Ruby`
- 🌎 [Misago](misago-project.org/) - Misago is fully featured modern forum application that is fast, scalable and responsive. (<b><code>&nbsp;&nbsp;2609⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;532🍴</code></b> [Source Code](https://github.com/rafalp/Misago))) `GPL-2.0` `Docker`
- 🌎 [Misskey](misskey.io/) - Decentralized app-like microblogging server/SNS for the Fediverse, using the ActivityPub protocol like GNU social and Mastodon. (<b><code>&nbsp;10485⭐</code></b> <b><code>&nbsp;&nbsp;1447🍴</code></b> [Source Code](https://github.com/misskey-dev/misskey))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Movim](movim.eu/) - Modern, federated social network based on XMPP, with a fully featured group-chat, subscriptions and microblogging. (<b><code>&nbsp;&nbsp;1782⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [Source Code](https://github.com/movim/movim))) `AGPL-3.0` `PHP/Docker`
- 🌎 [MyBB](mybb.com/) - Free, extensible forum software package. (<b><code>&nbsp;&nbsp;1137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;416🍴</code></b> [Source Code](https://github.com/mybb/mybb))) `LGPL-3.0` `PHP`
- 🌎 [NodeBB](nodebb.org/) - Forum software built for the modern web. (<b><code>&nbsp;14520⭐</code></b> <b><code>&nbsp;&nbsp;2837🍴</code></b> [Source Code](https://github.com/NodeBB/NodeBB))) `GPL-3.0` `Nodejs`
- 🌎 [OSSN](www.opensource-socialnetwork.org/) - Open Source Social Network (OSSN) is a social networking software written in PHP. It allows you to make a social networking website and helps your members build social relationships, with people who share similar professional or personal interests. (<b><code>&nbsp;&nbsp;1113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;526🍴</code></b> [Source Code](https://github.com/opensource-socialnetwork/opensource-socialnetwork))) `GPL-2.0` `PHP`
- 🌎 [phpBB](www.phpbb.com/) - Flat-forum bulletin board software solution that can be used to stay in touch with a group of people or can power your entire website. (<b><code>&nbsp;&nbsp;1909⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;968🍴</code></b> [Source Code](https://github.com/phpbb/phpbb))) `GPL-2.0` `PHP`
- 🌎 [PixelFed](pixelfed.social) - Pixelfed is an open-source, federated platform alternate to Instagram. (<b><code>&nbsp;&nbsp;6538⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;761🍴</code></b> [Source Code](https://github.com/pixelfed/pixelfed))) `AGPL-3.0` `PHP`
- 🌎 [Pleroma](pleroma.social) - Federated microblogging server, Mastodon, GNU social, & ActivityPub compatible.  🌎 [Source Code](git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- 🌎 [qpixel](codidact.com/) - Q&A-based community knowledge-sharing software. (<b><code>&nbsp;&nbsp;&nbsp;405⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Source Code](https://github.com/codidact/qpixel))) `AGPL-3.0` `Ruby`
- <b><code>&nbsp;&nbsp;1896⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;134🍴</code></b> [Redlib](https://github.com/redlib-org/redlib)) `⚠` - An alternative private front-end to Reddit, with its origins in Libreddit. `AGPL-3.0` `Rust`
- 🌎 [remark42](remark42.com/) - A lightweight and simple comment engine, which doesn't spy on users. It can be embedded into blogs, articles or any other place where readers add comments.  🌎 [Demo](remark42.com/demo/), <b><code>&nbsp;&nbsp;5109⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;395🍴</code></b> [Source Code](https://github.com/umputun/remark42))) `MIT` `Docker/Go`
- <b><code>&nbsp;&nbsp;&nbsp;281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Retrospring](https://github.com/retrospring/retrospring)) - A free, open-source social network following the Q/A (question and answer) principle of sites like Formspring, ask.fm or CuriousCat.  🌎 [Demo](retrospring.net)) `AGPL-3.0` `Ruby/Nodejs`
- 🌎 [Scoold](scoold.com) - Stack Overflow in a JAR. An enterprise-ready Q&A platform with full-text search, SAML, LDAP integration and social login support.  🌎 [Demo](live.scoold.com), <b><code>&nbsp;&nbsp;&nbsp;877⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;238🍴</code></b> [Source Code](https://github.com/Erudika/scoold))) `Apache-2.0` `Java/Docker/K8S`
- 🌎 [Simple Machines Forum](www.simplemachines.org/) - Free, professional grade software package that allows you to set up your own online community within minutes. (<b><code>&nbsp;&nbsp;&nbsp;640⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;258🍴</code></b> [Source Code](https://github.com/SimpleMachines/SMF))) `BSD-3-Clause` `PHP`
- 🌎 [Socialhome](socialhome.network) - Federated and decentralized profile builder and social network engine.  🌎 [Demo](socialhome.network/), <b><code>&nbsp;&nbsp;&nbsp;366⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [Source Code](https://github.com/jaywink/socialhome))) `AGPL-3.0` `Docker/Python`
- 🌎 [Takahē](jointakahe.org/) - Federated microblogging server. Mastodon, & ActivityPub compatible. (<b><code>&nbsp;&nbsp;1155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [Source Code](https://github.com/jointakahe/takahe))) `BSD-3-Clause` `Docker`
- 🌎 [Talkyard](www.talkyard.io/) - Create a community, where your users can suggest ideas and get questions answered. And have friendly open-ended discussions and chat (Slack/StackOverflow/Discourse/Reddit/Disqus hybrid).  🌎 [Demo](www.talkyard.io/forum/latest), <b><code>&nbsp;&nbsp;1746⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [Source Code](https://github.com/debiki/talkyard))) `AGPL-3.0` `Docker/Scala`
- 🌎 [yarn.social](yarn.social) - Self-Hosted, Twitter™-like Decentralised micro-logging platform. No ads, no tracking, your content, your data.  🌎 [Source Code](git.mills.io/yarnsocial/yarn)) `MIT` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Zusam](https://github.com/zusam/zusam)) - Free and open-source way to self-host private forums for groups of friends or family.  🌎 [Demo](demo.zusam.org)) `AGPL-3.0` `PHP`


### Communication - Video Conferencing

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Video/Web Conferencing](en.wikipedia.org/wiki/Web_conferencing) tools and software.

_Related: [Conference Management](#conference-management)_

- 🌎 [BigBlueButton](bigbluebutton.org/) - Supports real-time sharing of audio, video, slides (with whiteboard controls), chat, and the screen. Instructors can engage remote students with polling, emojis, and breakout rooms. (<b><code>&nbsp;&nbsp;8759⭐</code></b> <b><code>&nbsp;&nbsp;5971🍴</code></b> [Source Code](https://github.com/bigbluebutton/bigbluebutton))) `LGPL-3.0` `Java`
- 🌎 [Galene](galene.org/) - Galène (or Galene) is a videoconference server (an “SFU”) that is easy to deploy and that requires moderate server resources. (<b><code>&nbsp;&nbsp;1043⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [Source Code](https://github.com/jech/galene))) `MIT` `Go`
- 🌎 [Janus](janus.conf.meetecho.com/) - General-purpose, lightweight, minimalist WebRTC Server.  🌎 [Demo](janus.conf.meetecho.com/demos/), <b><code>&nbsp;&nbsp;8557⭐</code></b> <b><code>&nbsp;&nbsp;2526🍴</code></b> [Source Code](https://github.com/meetecho/janus-gateway))) `GPL-3.0` `C`
- 🌎 [Jitsi Meet](jitsi.org/Projects/JitsiMeet) - Jitsi Meet is an OpenSource (MIT) WebRTC Javascript application that uses Jitsi Videobridge to provide high quality, scalable video conferences.  🌎 [Demo](meet.jit.si), <b><code>&nbsp;25214⭐</code></b> <b><code>&nbsp;&nbsp;7128🍴</code></b> [Source Code](https://github.com/jitsi/jitsi-meet))) `Apache-2.0` `Nodejs/Docker/deb`
- 🌎 [Jitsi Video Bridge](jitsi.org/Projects/JitsiVideobridge) - WebRTC compatible Selective Forwarding Unit (SFU) that allows for multiuser video communication. (<b><code>&nbsp;&nbsp;2962⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;999🍴</code></b> [Source Code](https://github.com/jitsi/jitsi-videobridge))) `Apache-2.0` `Java/deb`
- 🌎 [MiroTalk C2C](c2c.mirotalk.com) - Real-time cam-2-cam video calls & screen sharing, end-to-end encrypted, to embed in any website with a simple iframe. (<b><code>&nbsp;&nbsp;&nbsp;267⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [Source Code](https://github.com/miroslavpejic85/mirotalkc2c))) `MIT` `Nodejs/Docker`
- 🌎 [MiroTalk P2P](p2p.mirotalk.com) - Simple, secure, fast real-time video conferences up to 4k and 60fps, compatible with all browsers and platforms.  🌎 [Demo](p2p.mirotalk.com/newcall), <b><code>&nbsp;&nbsp;3438⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;617🍴</code></b> [Source Code](https://github.com/miroslavpejic85/mirotalk))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [MiroTalk SFU](sfu.mirotalk.com) - Simple, secure, scalable real-time video conferences up to 4k, compatible with all browsers and platforms.  🌎 [Demo](sfu.mirotalk.com/newroom), <b><code>&nbsp;&nbsp;2318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;373🍴</code></b> [Source Code](https://github.com/miroslavpejic85/mirotalksfu))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [plugNmeet](www.plugnmeet.org/) - Scalable, High Performance, Open source web conferencing system.  🌎 [Demo](demo.plugnmeet.com/login.html), <b><code>&nbsp;&nbsp;&nbsp;349⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [Source Code](https://github.com/mynaparrot/plugNmeet-server))) `MIT` `Docker/Go`


### Communication - XMPP - Servers

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Extensible Messaging and Presence Protocol](en.wikipedia.org/wiki/XMPP) servers.

- 🌎 [ejabberd](www.ejabberd.im/) - XMPP instant messaging server. (<b><code>&nbsp;&nbsp;6247⭐</code></b> <b><code>&nbsp;&nbsp;1525🍴</code></b> [Source Code](https://github.com/processone/ejabberd))) `GPL-2.0` `Erlang/Docker`
- 🌎 [MongooseIM](www.erlang-solutions.com/products/mongooseim.html) - Mobile messaging platform with a focus on performance and scalability. (<b><code>&nbsp;&nbsp;1684⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;429🍴</code></b> [Source Code](https://github.com/esl/MongooseIM))) `GPL-2.0` `Erlang/Docker/K8S`
- 🌎 [Openfire](www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server. (<b><code>&nbsp;&nbsp;2924⭐</code></b> <b><code>&nbsp;&nbsp;1375🍴</code></b> [Source Code](https://github.com/igniterealtime/Openfire))) `Apache-2.0` `Java`
- 🌎 [Prosody IM](prosody.im/) - Feature-rich and easy to configure XMPP server.  🌎 [Source Code](hg.prosody.im/)) `MIT` `Lua`
- 🌎 [Snikket](snikket.org/) - All-in-one Dockerized easy XMPP solution, including web admin and clients. (<b><code>&nbsp;&nbsp;&nbsp;295⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Source Code](https://github.com/snikket-im/snikket-server)), 🌎 [Clients](snikket.org/app/)) `Apache-2.0` `Docker`
- 🌎 [Tigase](tigase.net/xmpp-server) - XMPP server implementation in Java. (<b><code>&nbsp;&nbsp;&nbsp;331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [Source Code](https://github.com/tigase/tigase-server))) `GPL-3.0` `Java`


### Communication - XMPP - Web Clients

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Extensible Messaging and Presence Protocol](en.wikipedia.org/wiki/XMPP) Web clients/interfaces.

- 🌎 [Converse.js](conversejs.org/) - Free and open-source XMPP chat client in your browser. (<b><code>&nbsp;&nbsp;3123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;784🍴</code></b> [Source Code](https://github.com/conversejs/converse.js))) `MPL-2.0` `Javascript`
- 🌎 [JSXC](jsxc.org) - Real-time XMPP web chat application with video calls, file transfer and encrypted communication. There are also versions for Nextcloud/Owncloud and SOGo. (<b><code>&nbsp;&nbsp;&nbsp;730⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;240🍴</code></b> [Source Code](https://github.com/jsxc/jsxc))) `MIT` `Javascript`
- 🌎 [Libervia](repos.goffi.org/libervia-web) - Web frontend from Salut à Toi. `AGPL-3.0` `Python`
- 🌎 [Salut à Toi](www.salut-a-toi.org/) - Multipurpose, multi frontend, libre and decentralized communication tool.  🌎 [Source Code](repos.goffi.org/libervia-backend)) `AGPL-3.0` `Python`


### Community-Supported Agriculture (CSA)

**[`^        back to top        ^`](#awesome-selfhosted)**

Management and administration tools for community supported agriculture and food cooperatives.

_Related: [E-commerce](#e-commerce)_

- 🌎 [ACP Admin](acp-admin.ch/) - CSA administration. Manage members, subscriptions, deliveries, drop-off locations, member participation, invoices and emails (documentation in French). (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/acp-admin/acp-admin/))) `MIT` `Ruby`
- 🌎 [E-Label](filipecarneiro.github.io/ELabel/) - Solution for electronic labels, with QR Codes, on wine bottles sold within the European Union. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Source Code](https://github.com/filipecarneiro/ELabel))) `MIT` `Docker`
- 🌎 [FoodCoopShop](www.foodcoopshop.com/) - User-friendly open source software for food-coops. (<b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Source Code](https://github.com/foodcoopshop/foodcoopshop))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Foodsoft](foodcoops.net/) - Web-based software to manage a non-profit food coop (product catalog, ordering, accounting, job scheduling). (<b><code>&nbsp;&nbsp;&nbsp;333⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;147🍴</code></b> [Source Code](https://github.com/foodcoops/foodsoft))) `AGPL-3.0` `Docker/Ruby`
- 🌎 [juntagrico](juntagrico.org/) - Management platform for community gardens and vegetable cooperatives. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Source Code](https://github.com/juntagrico/juntagrico))) `LGPL-3.0` `Python`
- 🌎 [Open Food Network](www.openfoodnetwork.org/) - Online marketplace for local food. It enables a network of independent online food stores that connect farmers and food hubs with individuals and local businesses. (<b><code>&nbsp;&nbsp;1163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;730🍴</code></b> [Source Code](https://github.com/openfoodfoundation/openfoodnetwork))) `AGPL-3.0` `Ruby`
- 🌎 [OpenOlitor](openolitor.org/) - Administration platform for Community Supported Agriculture groups. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/OpenOlitor/openolitor-server))) `AGPL-3.0` `Scala`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [teikei](https://github.com/teikei/teikei)) - A web application that maps out community-supported agriculture based on crowdsourced data.  🌎 [Demo](ernte-teilen.org/karte/#/)) `AGPL-3.0` `Nodejs`


### Conference Management

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for submission of 🌎 [abstracts](en.wikipedia.org/wiki/Abstract_management) and preparation/management of academic conferences.

- 🌎 [indico](getindico.io/) - A feature-rich event management system, made @ CERN, the place where the Web was born.  🌎 [Demo](sandbox.getindico.io/), <b><code>&nbsp;&nbsp;1861⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;457🍴</code></b> [Source Code](https://github.com/indico/indico))) `MIT` `Python`
- 🌎 [motion.tools (Antragsgrün)](motion.tools/) - A web tool for managing motions and amendments for (political) conventions.  🌎 [Demo](sandbox.motion.tools/createsite), <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Source Code](https://github.com/CatoTH/antragsgruen))) `AGPL-3.0` `PHP/Docker`
- 🌎 [OpenSlides](openslides.com/) - A web based presentation and assembly system for managing and projecting agenda, motions and elections of an assembly.  🌎 [Demo](demo.os4.openslides.com/login), <b><code>&nbsp;&nbsp;&nbsp;530⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [Source Code](https://github.com/OpenSlides/OpenSlides))) `MIT` `Docker`
- 🌎 [osem](osem.io/) - Event management tailored to free Software conferences. (<b><code>&nbsp;&nbsp;&nbsp;887⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;495🍴</code></b> [Source Code](https://github.com/openSUSE/osem))) `MIT` `Ruby/Docker`
- 🌎 [pretalx](pretalx.org) - Web-based event management, including running a Call for Papers, reviewing submissions, and scheduling talks. Exports and imports for various related tools. (<b><code>&nbsp;&nbsp;&nbsp;784⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;218🍴</code></b> [Source Code](https://github.com/pretalx/pretalx))) `Apache-2.0` `Python`


### Content Management Systems (CMS)

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Content Management Systems](en.wikipedia.org/wiki/Content_management_system) offer a practical way to setup a website with many features, using third party plugins, themes and functionality that are easy to add and customize.

_Related: [Blogging Platforms](#blogging-platforms), [Static Site Generators](#static-site-generators), [Photo Galleries](#photo-galleries)_

- 🌎 [Alfresco Community Edition](www.alfresco.com/products/community/download) - The open source Enterprise Content Management software that handles any type of content, allowing users to easily share and collaborate on content. (<b><code>&nbsp;&nbsp;&nbsp;161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/Alfresco/alfresco-community-repo))) `LGPL-3.0` `Java`
- 🌎 [Apostrophe](apostrophecms.com/) - CMS with a focus on extensible in-context editing tools.  🌎 [Demo](apostrophecms.com/demo), <b><code>&nbsp;&nbsp;4421⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;600🍴</code></b> [Source Code](https://github.com/apostrophecms/apostrophe))) `MIT` `Nodejs`
- 🌎 [Backdrop CMS](backdropcms.org/) - Comprehensive CMS for small to medium sized businesses and non-profits. (<b><code>&nbsp;&nbsp;1004⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;386🍴</code></b> [Source Code](https://github.com/backdrop/backdrop))) `GPL-2.0` `PHP`
- 🌎 [BigTree CMS](www.bigtreecms.org/) - Straightforward, well documented, and capable CMS. (<b><code>&nbsp;&nbsp;&nbsp;218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Source Code](https://github.com/bigtreecms/BigTree-CMS))) `LGPL-2.1` `PHP`
- 🌎 [Bludit](www.bludit.com/) `⚠` - Build a site or blog in seconds. Bludit uses flat-files (text files in JSON format) to store posts and pages. (<b><code>&nbsp;&nbsp;1317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;294🍴</code></b> [Source Code](https://github.com/bludit/bludit))) `MIT` `PHP`
- 🌎 [CMS Made Simple](www.cmsmadesimple.org/) - Open source content management system, faster and easier management of website contents, scalable for small businesses to large corporations. ([Source Code](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-2.0` `PHP`
- 🌎 [Cockpit](getcockpit.com) - Simple Content Platform to manage any structured content. (<b><code>&nbsp;&nbsp;&nbsp;436⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Source Code](https://github.com/Cockpit-HQ/Cockpit))) `MIT` `PHP`
- 🌎 [Concrete 5 CMS](www.concretecms.com) - Open source content management system. (<b><code>&nbsp;&nbsp;&nbsp;791⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;462🍴</code></b> [Source Code](https://github.com/concretecms/concretecms))) `MIT` `PHP`
- 🌎 [Contao](contao.org/) - Contao is a powerful open source CMS that allows you to create professional websites and scalable web applications. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/contao/contao/))) `LGPL-3.0` `PHP`
- 🌎 [CouchCMS](www.couchcms.com/) - Simple Open-Source CMS for designers. (<b><code>&nbsp;&nbsp;&nbsp;355⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [Source Code](https://github.com/CouchCMS/CouchCMS))) `CPAL-1.0` `PHP`
- 🌎 [Drupal](www.drupal.org/) - Advanced open source content management platform.  🌎 [Source Code](git.drupalcode.org/project/drupal)) `GPL-2.0` `PHP`
- 🌎 [eLabFTW](www.elabftw.net) - Online lab notebook for research labs. Store experiments, use a database to find reagents or protocols, use trusted timestamping to legally timestamp an experiment, export as pdf or zip archive, share with collaborators….  🌎 [Demo](demo.elabftw.net), <b><code>&nbsp;&nbsp;1090⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;231🍴</code></b> [Source Code](https://github.com/elabftw/elabftw))) `AGPL-3.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;440⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Expressa](https://github.com/thomas4019/expressa)) - Content Management System for powering database driven websites using JSON schemas. Provides permission management and automatic REST APIs. `MIT` `Nodejs`
- 🌎 [Joomla!](www.joomla.org/) - Advanced Content Management System (CMS). (<b><code>&nbsp;&nbsp;4880⭐</code></b> <b><code>&nbsp;&nbsp;3711🍴</code></b> [Source Code](https://github.com/joomla/joomla-cms))) `GPL-2.0` `PHP`
- 🌎 [KeystoneJS](keystonejs.com/) - CMS and Web Application Platform. (<b><code>&nbsp;&nbsp;9498⭐</code></b> <b><code>&nbsp;&nbsp;1188🍴</code></b> [Source Code](https://github.com/keystonejs/keystone))) `MIT` `Nodejs`
- 🌎 [Localess](localess.org/home) `⚠` - Powerful translation management and content management system. Manage and translate your website or app content into multiple languages, using AI to translate faster. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Source Code](https://github.com/Lessify/localess))) `MIT` `Docker`
- 🌎 [MODX](modx.com/) - MODX is an advanced content management and publishing platform. The current version is called 'Revolution'. (<b><code>&nbsp;&nbsp;1376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;529🍴</code></b> [Source Code](https://github.com/modxcms/revolution))) `GPL-2.0` `PHP`
- 🌎 [Neos](www.neos.io) - Neos or TYPO3 Neos (for version 1) is a modern, open source CMS. ([Source Code](https://github.com/neos)) `GPL-3.0` `PHP`
- 🌎 [Noosfero](gitlab.com/noosfero/noosfero) - Noosfero is a web platform for social and solidarity economy networks with blog, e-Portfolios, CMS, RSS, thematic discussion, events agenda and collective intelligence for solidarity economy in the same system. `AGPL-3.0` `Ruby`
- 🌎 [Omeka](omeka.org) - Create complex narratives and share rich collections, adhering to Dublin Core standards with Omeka on your server, designed for scholars, museums, libraries, archives, and enthusiasts.  🌎 [Demo](omeka.org/classic/showcase/), <b><code>&nbsp;&nbsp;&nbsp;502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;199🍴</code></b> [Source Code](https://github.com/omeka/Omeka))) `GPL-3.0` `PHP`
- 🌎 [Payload CMS](payloadcms.com/) - Developer-first headless CMS and application framework. (<b><code>&nbsp;33909⭐</code></b> <b><code>&nbsp;&nbsp;2301🍴</code></b> [Source Code](https://github.com/payloadcms/payload))) `MIT` `Nodejs`
- [Pimcore](http://www.pimcore.com/) - Multi-Channel Experience and Engagement Management Platform. (<b><code>&nbsp;&nbsp;3543⭐</code></b> <b><code>&nbsp;&nbsp;1468🍴</code></b> [Source Code](https://github.com/pimcore/pimcore))) `GPL-3.0` `PHP/Docker`
- 🌎 [Plone](plone.org/) - Powerful open-source CMS system. ([Source Code](https://github.com/plone)) `ZPL-2.0` `Python/Docker`
- 🌎 [Publify](publify.github.io/) - Simple but full featured web publishing software. (<b><code>&nbsp;&nbsp;1838⭐</code></b> <b><code>&nbsp;&nbsp;3675🍴</code></b> [Source Code](https://github.com/publify/publify))) `MIT` `Ruby`
- 🌎 [REDAXO](www.redaxo.org) - Simple, flexible and useful content management system (documentation only available in German). (<b><code>&nbsp;&nbsp;&nbsp;336⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [Source Code](https://github.com/redaxo/redaxo))) `MIT` `PHP/Docker`
- 🌎 [Roadiz](www.roadiz.io/) - Modern CMS based on a node system which can handle many types of services. (<b><code>&nbsp;&nbsp;&nbsp;373⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Source Code](https://github.com/roadiz/roadiz))) `MIT` `PHP`
- 🌎 [SilverStripe](www.silverstripe.org) - Easy to use CMS with powerful MVC framework underlying.  🌎 [Demo](demo.silverstripe.org/), [Source Code](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- 🌎 [SPIP](www.spip.net/fr) - Publication system for the Internet aimed at collaborative work, multilingual environments, and simplicity of use for web authors.  🌎 [Source Code](git.spip.net/)) `GPL-3.0` `PHP`
- 🌎 [Squidex](squidex.io) - Headless CMS, based on MongoDB, CQRS and Event Sourcing.  🌎 [Demo](cloud.squidex.io), <b><code>&nbsp;&nbsp;2373⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;473🍴</code></b> [Source Code](https://github.com/Squidex/squidex))) `MIT` `.NET`
- 🌎 [Strapi](strapi.io/) - The most advanced open-source Content Management Framework (headless-CMS) to build powerful API with no effort. (<b><code>&nbsp;66098⭐</code></b> <b><code>&nbsp;&nbsp;8473🍴</code></b> [Source Code](https://github.com/strapi/strapi))) `MIT` `Nodejs`
- 🌎 [Textpattern](textpattern.com/) - Flexible, elegant and easy-to-use CMS.  🌎 [Demo](textpattern.co/demo), <b><code>&nbsp;&nbsp;&nbsp;819⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [Source Code](https://github.com/textpattern/textpattern))) `GPL-2.0` `PHP`
- 🌎 [Typemill](typemill.net/) - Author-friendly flat-file-cms with a visual markdown editor based on vue.js. (<b><code>&nbsp;&nbsp;&nbsp;494⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Source Code](https://github.com/typemill/typemill))) `MIT` `PHP`
- 🌎 [TYPO3](typo3.org/) - Powerful and advanced CMS with a large community. (<b><code>&nbsp;&nbsp;1099⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;678🍴</code></b> [Source Code](https://github.com/TYPO3/typo3))) `GPL-2.0` `PHP`
- 🌎 [Umbraco](umbraco.com/) - The friendly CMS. Free and open source with an amazing community. (<b><code>&nbsp;&nbsp;4814⭐</code></b> <b><code>&nbsp;&nbsp;2767🍴</code></b> [Source Code](https://github.com/umbraco/Umbraco-CMS))) `MIT` `.NET`
- 🌎 [Vvveb CMS](www.vvveb.com) - Powerful and easy to use CMS to build websites, blogs or e-commerce stores.  🌎 [Demo](demo.vvveb.com), <b><code>&nbsp;&nbsp;&nbsp;557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [Source Code](https://github.com/givanz/Vvveb))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Wagtail](wagtail.io/) - Django content management system focused on flexibility and user experience. (<b><code>&nbsp;19064⭐</code></b> <b><code>&nbsp;&nbsp;4058🍴</code></b> [Source Code](https://github.com/wagtail/wagtail))) `BSD-3-Clause` `Python`
- 🌎 [WinterCMS](wintercms.com/) - Speedy and secure content management system built on the Laravel PHP framework. (<b><code>&nbsp;&nbsp;1412⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;206🍴</code></b> [Source Code](https://github.com/wintercms/winter))) `MIT` `PHP`
- 🌎 [WonderCMS](www.wondercms.com) - WonderCMS is the smallest flat file CMS since 2008.  🌎 [Demo](www.wondercms.com/demo), <b><code>&nbsp;&nbsp;&nbsp;681⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;164🍴</code></b> [Source Code](https://github.com/WonderCMS/wondercms))) `MIT` `PHP`
- 🌎 [WordPress](wordpress.org/) - World's most-used blogging and CMS engine. (<b><code>&nbsp;20047⭐</code></b> <b><code>&nbsp;12771🍴</code></b> [Source Code](https://github.com/WordPress/WordPress))) `GPL-2.0` `PHP`


### Customer Relationship Management (CRM)

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Customer relationship management (CRM)](en.wikipedia.org/wiki/Customer_relationship_management) is a strategic process that organizations use to manage, analyze, and improve their interactions with customers.

_Related: [Communication - Email - Mailing Lists and Newsletters](#communication---email---mailing-lists-and-newsletters), [Analytics](#analytics), [Calendar & Contacts](#calendar--contacts)_

- 🌎 [Corteza](cortezaproject.org) - CRM including a unified workspace, enterprise messaging and a low code environment for rapidly and securely delivering records-based management solutions.  🌎 [Demo](latest.cortezaproject.org), <b><code>&nbsp;&nbsp;1765⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;426🍴</code></b> [Source Code](https://github.com/cortezaproject/corteza))) `Apache-2.0` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [Django-CRM](https://github.com/DjangoCRM/django-crm)) - Analytical CRM with tasks management, email marketing and many more. Django CRM is built for individual use, businesses of any size or freelancers and is designed to provide easy customization and quick development. `AGPL-3.0` `Python`
- 🌎 [EspoCRM](www.espocrm.com/) - CRM with a frontend designed as a single page application, and a REST API.  🌎 [Demo](demo.espocrm.com/), <b><code>&nbsp;&nbsp;2124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;621🍴</code></b> [Source Code](https://github.com/espocrm/espocrm))) `AGPL-3.0` `PHP`
- 🌎 [Krayin](krayincrm.com/) - CRM solution for SMEs and Enterprises for complete customer lifecycle management.  🌎 [Demo](demo.krayincrm.com/), <b><code>&nbsp;13989⭐</code></b> <b><code>&nbsp;&nbsp;1004🍴</code></b> [Source Code](https://github.com/krayin/laravel-crm))) `MIT` `PHP`
- 🌎 [Monica](monicahq.com/) - Personal relationship manager, and a new kind of CRM to organize interactions with your friends and family. (<b><code>&nbsp;22610⭐</code></b> <b><code>&nbsp;&nbsp;2263🍴</code></b> [Source Code](https://github.com/monicahq/monica))) `AGPL-3.0` `PHP/Docker`
- 🌎 [SuiteCRM](suitecrm.com) - The award-winning, enterprise-class open source CRM. (<b><code>&nbsp;&nbsp;4799⭐</code></b> <b><code>&nbsp;&nbsp;2147🍴</code></b> [Source Code](https://github.com/salesagility/SuiteCRM))) `AGPL-3.0` `PHP`
- 🌎 [Twenty](twenty.com) - A modern CRM offering the flexibility of open source, advanced features, and a sleek design. (<b><code>&nbsp;27534⭐</code></b> <b><code>&nbsp;&nbsp;3041🍴</code></b> [Source Code](https://github.com/twentyhq/twenty))) `AGPL-3.0` `Docker`


### Database Management

**[`^        back to top        ^`](#awesome-selfhosted)**

Web interfaces for 🌎 [database](en.wikipedia.org/wiki/Database) management. Includes tools for database analytics and visualization.

_Related: [Analytics](#analytics), [Automation](#automation)_

_See also: 🌎 [dbdb.io - Database of Databases](dbdb.io/)_

- 🌎 [Adminer](www.adminer.org/) - Database management in a single PHP file. Available for MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch, MongoDB and others. (<b><code>&nbsp;&nbsp;6636⭐</code></b> <b><code>&nbsp;&nbsp;1101🍴</code></b> [Source Code](https://github.com/vrana/adminer))) `Apache-2.0/GPL-2.0` `PHP`
- 🌎 [Azimutt](azimutt.app) - Visual database exploration made for real world databases (big and messy). Explore your database schema as well as data, document them, extend them and even get analysis and guidelines.  🌎 [Demo](azimutt.app/gallery/gospeak), <b><code>&nbsp;&nbsp;1847⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [Source Code](https://github.com/azimuttapp/azimutt))) `MIT` `Elixir/Nodejs/Docker`
- 🌎 [Baserow](baserow.io/) - Create your own database without technical experience (alternative to Airtable).  🌎 [Source Code](gitlab.com/bramw/baserow)) `MIT` `Docker`
- 🌎 [Bytebase](www.bytebase.com/) - Safe database schema change and version control for DevOps teams, supports MySQL, PostgreSQL, TiDB, ClickHouse, and Snowflake.  🌎 [Demo](demo.bytebase.com), <b><code>&nbsp;12251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;793🍴</code></b> [Source Code](https://github.com/bytebase/bytebase))) `MIT` `Docker/K8S/Go`
- 🌎 [Chartbrew](chartbrew.com) - Web application that can connect directly to databases and APIs and use the data to create beautiful charts.  🌎 [Demo](app.chartbrew.com/live-demo), <b><code>&nbsp;&nbsp;2820⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;338🍴</code></b> [Source Code](https://github.com/chartbrew/chartbrew))) `MIT` `Nodejs/Docker`
- 🌎 [CloudBeaver](dbeaver.com/) - Self-hosted management of databases, supports PostgreSQL, MySQL, SQLite and more. A web/hosted version of DBeaver. (<b><code>&nbsp;&nbsp;3829⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;425🍴</code></b> [Source Code](https://github.com/dbeaver/cloudbeaver))) `Apache-2.0` `Docker`
- 🌎 [Databunker](databunker.org/) - Network-based, self-hosted, GDPR compliant, secure database for personal data or PII. (<b><code>&nbsp;&nbsp;1292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Source Code](https://github.com/securitybunker/databunker))) `MIT` `Docker`
- 🌎 [Datasette](datasette.io/) - An open source multi-tool for exploring and publishing data, easy import and export and database management.  🌎 [Demo](global-power-plants.datasettes.com/global-power-plants/global-power-plants), <b><code>&nbsp;&nbsp;9944⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;725🍴</code></b> [Source Code](https://github.com/simonw/datasette))) `Apache-2.0` `Python/Docker`
- 🌎 [Directus](directus.io/) - An Instant App & API for your SQL Database. Directus wraps your new or existing SQL database with a realtime GraphQL+REST API for developers, and an intuitive admin app for non-technical users. (<b><code>&nbsp;29913⭐</code></b> <b><code>&nbsp;&nbsp;4149🍴</code></b> [Source Code](https://github.com/directus/directus))) `GPL-3.0` `Nodejs/Docker`
- 🌎 [Evidence](evidence.dev) - Evidence is a code-based BI tool. Write reports using SQL and markdown and they render as a website. (<b><code>&nbsp;&nbsp;5109⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;250🍴</code></b> [Source Code](https://github.com/evidence-dev/evidence))) `MIT` `Nodejs`
- 🌎 [Limbas](www.limbas.com/en/) - Limbas is a database framework for creating database-driven business applications. As a graphical database frontend, it enables the efficient processing of data stocks and the flexible development of comfortable database applications. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Source Code](https://github.com/limbas/limbas))) `GPL-2.0` `PHP`
- 🌎 [Mathesar](mathesar.org/) - An intuitive UI for managing data collaboratively, for users of all technical skill levels. Built on Postgres – connect an existing DB or set up a new one. (<b><code>&nbsp;&nbsp;4068⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;377🍴</code></b> [Source Code](https://github.com/centerofci/mathesar))) `GPL-3.0` `Docker/Python`
- 🌎 [MindsDB](mindsdb.com/) - MindsDB is an open source self hosted AI layer for existing databases that allows you to effortlessly develop, train and deploy state-of-the-art machine learning models using standard queries. (<b><code>&nbsp;27705⭐</code></b> <b><code>&nbsp;&nbsp;4957🍴</code></b> [Source Code](https://github.com/mindsdb/mindsdb))) `GPL-3.0` `Docker/Python`
- 🌎 [NocoDB](www.nocodb.com/) - No-code platform that turns any database into a smart spreadsheet (alternative to Airtable or Smartsheet). (<b><code>&nbsp;53722⭐</code></b> <b><code>&nbsp;&nbsp;3762🍴</code></b> [Source Code](https://github.com/nocodb/nocodb))) `GPL-3.0` `Nodejs/Docker`
- 🌎 [WebDB](webdb.app) - Efficient database IDE.  🌎 [Demo](demo.webdb.app/), 🌎 [Source Code](gitlab.com/web-db/app)) `AGPL-3.0` `Docker`


### DNS

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [DNS](en.wikipedia.org/wiki/Domain_Name_System) servers and management tools with advertisement blocking functionality, primarily aimed at home or small networks.

_See also: <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/DNS - Servers](https://github.com/awesome-foss/awesome-sysadmin#dns---servers)), <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/DNS - Control Panels & Domain Management](https://github.com/awesome-foss/awesome-sysadmin#dns---control-panels--domain-management))_

- 🌎 [AdGuard Home](adguard.com/en/adguard-home/overview.html) - User-friendly ads & trackers blocking DNS server. (<b><code>&nbsp;27905⭐</code></b> <b><code>&nbsp;&nbsp;1975🍴</code></b> [Source Code](https://github.com/AdguardTeam/AdGuardHome))) `GPL-3.0` `Docker`
- 🌎 [blocky](0xerr0r.github.io/blocky/latest/) - Fast and lightweight DNS proxy as ad-blocker for local network with many features (alternative to Pi-hole). (<b><code>&nbsp;&nbsp;5244⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;234🍴</code></b> [Source Code](https://github.com/0xERR0R/blocky))) `Apache-2.0` `Go/Docker`
- 🌎 [Maza ad blocking](maza-ad-blocking.andros.dev/) - Local ad blocker. Like Pi-hole but local and using your operating system. (<b><code>&nbsp;&nbsp;1823⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [Source Code](https://github.com/tanrax/maza-ad-blocking))) `Apache-2.0` `Shell`
- 🌎 [Pi-hole](pi-hole.net/) - A blackhole for Internet advertisements with a GUI for management and monitoring. (<b><code>&nbsp;51469⭐</code></b> <b><code>&nbsp;&nbsp;2801🍴</code></b> [Source Code](https://github.com/pi-hole/pi-hole))) `EUPL-1.2` `Shell/PHP/Docker`
- 🌎 [Technitium DNS Server](technitium.com/dns/) - Authoritative/recursive DNS server with ad blocking functionality. (<b><code>&nbsp;&nbsp;5242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;478🍴</code></b> [Source Code](https://github.com/TechnitiumSoftware/DnsServer))) `GPL-3.0` `Docker/C#`


### Document Management

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [document management system](en.wikipedia.org/wiki/Document_management_system) (DMS) is a system used to receive, track, manage and store documents and reduce paper.

- 🌎 [DocKing](docking.shipsaas.tech) - Document management service/microservice that handles templates and renders them in PDF format, all in one place.  🌎 [Demo](docking-demo.shipsaas.tech/console), <b><code>&nbsp;&nbsp;&nbsp;255⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Source Code](https://github.com/shipsaas/docking))) `MIT` `PHP/Nodejs/Docker`
- 🌎 [Docspell](docspell.org) - Auto-tagging document organizer and archive. (<b><code>&nbsp;&nbsp;1782⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;139🍴</code></b> [Source Code](https://github.com/eikek/docspell))) `GPL-3.0` `Scala/Java/Docker`
- 🌎 [Documenso](documenso.com) - Digital document signing platform (alternative to DocuSign). (<b><code>&nbsp;10743⭐</code></b> <b><code>&nbsp;&nbsp;1610🍴</code></b> [Source Code](https://github.com/documenso/documenso))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Docuseal](www.docuseal.co) - Create, fill, and sign digital documents (alternative to DocuSign).  🌎 [Demo](demo.docuseal.tech/), <b><code>&nbsp;&nbsp;8987⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;635🍴</code></b> [Source Code](https://github.com/docusealco/docuseal))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [EveryDocs](https://github.com/jonashellmann/everydocs-core)) - A simple Document Management System for private use with basic functionality to organize your documents digitally. `GPL-3.0` `Docker/Ruby`
- 🌎 [Gotenberg](gotenberg.dev) - Developer-friendly API to interact with powerful tools like Chromium and LibreOffice for converting numerous document formats (HTML, Markdown, Word, Excel, etc.) into PDF files, and more. (<b><code>&nbsp;&nbsp;8984⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;608🍴</code></b> [Source Code](https://github.com/gotenberg/gotenberg)), <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Clients](https://github.com/gotenberg/awesome-gotenberg))) `MIT` `Docker`
- 🌎 [I, Librarian](i-librarian.net) - I, Librarian can organize PDF papers and office documents. It provides a lot of extra features for students and research groups both in industry and academia.  🌎 [Demo](i-librarian.net/demo/), <b><code>&nbsp;&nbsp;&nbsp;292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Source Code](https://github.com/mkucej/i-librarian-free))) `GPL-3.0` `PHP`
- 🌎 [Mayan EDMS](www.mayan-edms.com) - Free Open Source Electronic Document Management System. An electronic vault for your documents with preview generation, OCR, and automatic categorization among other features.  🌎 [Source Code](gitlab.com/mayan-edms/mayan-edms)) `Apache-2.0` `Python`
- 🌎 [OpenSign](www.opensignlabs.com) `⚠` - Free, open source & self-hosted document signing software (alternative to DocuSign). (<b><code>&nbsp;&nbsp;4507⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;410🍴</code></b> [Source Code](https://github.com/opensignlabs/opensign))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Paperless-ngx](docs.paperless-ngx.com/) - Scan, index, and archive all of your paper documents with an improved interface (fork of Paperless).  🌎 [Demo](demo.paperless-ngx.com/), <b><code>&nbsp;26327⭐</code></b> <b><code>&nbsp;&nbsp;1533🍴</code></b> [Source Code](https://github.com/paperless-ngx/paperless-ngx))) `GPL-3.0` `Python/Docker`
- 🌎 [Papermerge](papermerge.com) - Document management system focused on scanned documents (electronic archives). Features file browsing in similar way to dropbox/google drive. OCR, full text search, text overlay/selection. (<b><code>&nbsp;&nbsp;&nbsp;345⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [Source Code](https://github.com/papermerge/papermerge-core))) `Apache-2.0` `Docker/K8S`
- <b><code>&nbsp;&nbsp;&nbsp;921⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [PdfDing](https://github.com/mrmn2/PdfDing)) - PDF manager, viewer and editor offering a seamless user experience on multiple devices. It's designed to be minimal, fast, and easy to set up using Docker.  🌎 [Demo](demo.pdfding.com)) `GPL-3.0` `Docker`
- 🌎 [SeedDMS](www.seeddms.org) - Document Management System with workflows, access rights, fulltext search, and more.  🌎 [Demo](www.seeddms.org/about/), 🌎 [Source Code](sourceforge.net/p/seeddms/code/ci/master/tree/)) `GPL-2.0` `PHP`
- <b><code>&nbsp;55860⭐</code></b> <b><code>&nbsp;&nbsp;4643🍴</code></b> [Stirling-PDF](https://github.com/Frooodle/Stirling-PDF)) - Local hosted web application that allows you to perform various operations on PDF files, such as merging, splitting, file conversions and OCR. `Apache-2.0` `Docker/Java`
- 🌎 [Teedy](teedy.io/) - Lightweight document management system packed with all the features you can expect from big expensive solutions (Ex SismicsDocs).  🌎 [Demo](demo.teedy.io/), <b><code>&nbsp;&nbsp;2120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;521🍴</code></b> [Source Code](https://github.com/sismics/docs))) `GPL-2.0` `Docker/Java`


### Document Management - E-books

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Ebook](en.wikipedia.org/wiki/Ebook) library management software.

- 🌎 [Atsumeru](atsumeru.xyz) - Manga/comic/light novel media server with clients for Windows, Linux, macOS and Android. (<b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Source Code](https://github.com/AtsumeruDev/Atsumeru)), 🌎 [Clients](atsumeru.xyz/guides/#how-does-it-work)) `MIT` `Java/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;296⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [BookLogr](https://github.com/Mozzo1000/booklogr)) - Manage your personal book library with ease.  🌎 [Demo](demo.booklogr.app/)) `Apache-2.0` `Docker`
- <b><code>&nbsp;14361⭐</code></b> <b><code>&nbsp;&nbsp;1517🍴</code></b> [Calibre Web](https://github.com/janeczku/calibre-web)) - Web app providing a clean interface for browsing, reading and downloading eBooks using an existing Calibre database. `GPL-3.0` `Python`
- 🌎 [Calibre](calibre-ebook.com/) - E-book library manager that can view, convert, and catalog e-books in most of the major e-book formats and provides a built-in Web server for remote clients.  🌎 [Demo](calibre-ebook.com/demo), <b><code>&nbsp;21148⭐</code></b> <b><code>&nbsp;&nbsp;2337🍴</code></b> [Source Code](https://github.com/kovidgoyal/calibre))) `GPL-3.0` `Python/deb`
- 🌎 [Kavita](www.kavitareader.com/) - Cross-platform e-book/manga/comic/pdf server and web reader with user management, ratings and reviews, and metadata support.  🌎 [Demo](www.kavitareader.com/#demo), <b><code>&nbsp;&nbsp;7470⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;392🍴</code></b> [Source Code](https://github.com/Kareadita/Kavita))) `GPL-3.0` `.NET/Docker`
- 🌎 [Komga](komga.org) - Media server for comics/mangas/BDs with API and OPDS support, a modern web interface for exploring your libraries, as well as a web reader. (<b><code>&nbsp;&nbsp;4711⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;283🍴</code></b> [Source Code](https://github.com/gotson/komga))) `MIT` `Java/Docker`
- 🌎 [Librum](librumreader.com) - A modern e-book reader and library manager that supports most major book formats, runs on all devices and offers great tools to boost productivity. (<b><code>&nbsp;&nbsp;4444⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [Source Code](https://github.com/Librum-Reader/Librum))) `GPL-3.0` `C++`
- 🌎 [Stump](www.stumpapp.dev) - A fast, free and open source comics, manga and digital book server with OPDS support. (<b><code>&nbsp;&nbsp;1291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [Source Code](https://github.com/stumpapp/stump))) `MIT` `Rust`
- 🌎 [The Epube](gitlab.tt-rss.org/main/the-epube/-/wikis/home) - Self-hosted web EPUB reader using EPUB.js, Bootstrap, and Calibre.  🌎 [Source Code](gitlab.tt-rss.org/main/the-epube)) `GPL-3.0` `PHP`


### Document Management - Institutional Repository and Digital Library Software

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Institutional repository](en.wikipedia.org/wiki/Institutional_repository) and 🌎 [digital library](en.wikipedia.org/wiki/Digital_library) management software.

- [DSpace](http://www.dspace.org/) - Turnkey repository application providing durable access to digital resources. (<b><code>&nbsp;&nbsp;&nbsp;952⭐</code></b> <b><code>&nbsp;&nbsp;1334🍴</code></b> [Source Code](https://github.com/DSpace/DSpace))) `BSD-3-Clause` `Java`
- 🌎 [EPrints](www.eprints.org/) - Digital document management system with a flexible metadata and workflow model primarily aimed at academic institutions. ([Demo](http://tryme.demo.eprints-hosting.org/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Source Code](https://github.com/eprints/eprints3.4))) `GPL-3.0` `Perl`
- 🌎 [Fedora Commons Repository](wiki.lyrasis.org/display/FF/Fedora+Repository+Home) - Robust and modular repository system for the management and dissemination of digital content especially suited for digital libraries and archives, both for access and preservation. (<b><code>&nbsp;&nbsp;&nbsp;219⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [Source Code](https://github.com/fcrepo/fcrepo))) `Apache-2.0` `Java`
- 🌎 [InvenioRDM](inveniordm.docs.cern.ch/) - Highly scalable turn-key research data management platform with a beautiful user experience.  🌎 [Demo](inveniordm.web.cern.ch/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/inveniosoftware/)), 🌎 [Clients](inveniosoftware.org/products/rdm/)) `MIT` `Python`
- 🌎 [Islandora](www.islandora.ca/) - Drupal module for browsing and managing Fedora-based digital repositories.  🌎 [Demo](sandbox.islandora.ca/), <b><code>&nbsp;&nbsp;&nbsp;153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [Source Code](https://github.com/Islandora/islandora))) `GPL-3.0` `PHP`
- 🌎 [Samvera Hyrax](samvera.org/) - Front-end for the Samvera framework, which itself is a Ruby on Rails application for browsing and managing Fedora-based digital repositories. (<b><code>&nbsp;&nbsp;&nbsp;187⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [Source Code](https://github.com/samvera/hyrax))) `Apache-2.0` `Ruby`


### Document Management - Integrated Library Systems (ILS)

**[`^        back to top        ^`](#awesome-selfhosted)**

An 🌎 [integrated library system](en.wikipedia.org/wiki/Integrated_library_system) is an enterprise resource planning system for a library, used to track items owned, orders made, bills paid, and patrons who have borrowed.

_Related: [Content Management Systems (CMS)](#content-management-systems-cms), [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)_

- 🌎 [Evergreen](evergreen-ils.org) - Highly-scalable software for libraries that helps library patrons find library materials, and helps libraries manage, catalog, and circulate those materials. (<b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [Source Code](https://github.com/evergreen-library-system/Evergreen))) `GPL-2.0` `PLpgSQL`
- 🌎 [Koha](koha-community.org/) - Enterprise-class ILS with modules for acquisitions, circulation, cataloging, label printing, offline circulation for when Internet access is not available, and much more.  🌎 [Demo](koha-community.org/demo/), <b><code>&nbsp;&nbsp;&nbsp;508⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;264🍴</code></b> [Source Code](https://github.com/Koha-Community/Koha))) `GPL-3.0` `Perl`
- 🌎 [RERO ILS](rero21.ch/) - Large-scale ILS that can be run as a service with consortial features, intended primarily for library networks. Includes most standard modules (circulation, acquisitions, cataloging,...) and a web-based public and professional interface.  🌎 [Demo](ils.test.rero.ch/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Source Code](https://github.com/rero/rero-ils))) `AGPL-3.0` `Python/Docker`


### E-commerce

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [E-commerce](en.wikipedia.org/wiki/E-commerce) software.

_Related: [Community-Supported Agriculture (CSA)](#community-supported-agriculture-csa)_

- 🌎 [Aimeos](aimeos.org/) - E-commerce framework for building custom online shops, market places and complex B2B applications scaling to billions of items with Laravel.  🌎 [Demo](demo.aimeos.org/), <b><code>&nbsp;&nbsp;4492⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;282🍴</code></b> [Source Code](https://github.com/aimeos/aimeos))) `LGPL-3.0/MIT` `PHP`
- 🌎 [Bagisto](bagisto.com/en/) - Leading Laravel open source e-commerce framework with multi-inventory sources, taxation, localization, dropshipping and more exciting features.  🌎 [Demo](demo.bagisto.com/), <b><code>&nbsp;17912⭐</code></b> <b><code>&nbsp;&nbsp;2416🍴</code></b> [Source Code](https://github.com/bagisto/bagisto))) `MIT` `PHP`
- 🌎 [CoreShop](www.coreshop.org) - CoreShop is an e-commerce plugin for Pimcore. (<b><code>&nbsp;&nbsp;&nbsp;286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [Source Code](https://github.com/coreshop/CoreShop))) `GPL-3.0` `PHP`
- 🌎 [Drupal Commerce](drupalcommerce.org) - Drupal Commerce is a popular e-commerce module for Drupal CMS, with support for dozens of payment, shipping, and shopping related modules.  🌎 [Source Code](git.drupalcode.org/project/commerce)) `GPL-2.0` `PHP`
- 🌎 [EverShop](evershop.io/) `⚠` - E-commerce platform with essential commerce features. Modular architecture and fully customizable.  🌎 [Demo](demo.evershop.io/), <b><code>&nbsp;&nbsp;4960⭐</code></b> <b><code>&nbsp;&nbsp;1386🍴</code></b> [Source Code](https://github.com/evershopcommerce/evershop))) `GPL-3.0` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Litecart](https://github.com/shurco/litecart)) `⚠` - Shopping cart in 1 file (with support for payment by card or cryptocurrency). `MIT` `Go/Docker`
- <b><code>&nbsp;11764⭐</code></b> <b><code>&nbsp;&nbsp;9363🍴</code></b> [Magento Open Source](https://github.com/magento/magento2)) - Leading provider of open omnichannel innovation. `OSL-3.0` `PHP`
- 🌎 [MedusaJs](medusajs.com/) - Medusa is an open-source headless commerce engine that enables developers to create amazing digital commerce experiences.  🌎 [Demo](next.medusajs.com/), <b><code>&nbsp;28545⭐</code></b> <b><code>&nbsp;&nbsp;3167🍴</code></b> [Source Code](https://github.com/medusajs/medusa))) `MIT` `Nodejs`
- 🌎 [Microweber](microweber.com/) - Drag and Drop CMS and online shop. (<b><code>&nbsp;&nbsp;3243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;899🍴</code></b> [Source Code](https://github.com/microweber/microweber))) `Apache-2.0` `PHP`
- <b><code>&nbsp;&nbsp;3639⭐</code></b> <b><code>&nbsp;&nbsp;2256🍴</code></b> [Open Source POS](https://github.com/opensourcepos/opensourcepos)) - Open Source Point of Sale is a web based point of sale system. `MIT` `PHP`
- 🌎 [OpenCart](www.opencart.com) - Free open source shopping cart solution. (<b><code>&nbsp;&nbsp;7740⭐</code></b> <b><code>&nbsp;&nbsp;4918🍴</code></b> [Source Code](https://github.com/opencart/opencart))) `GPL-3.0` `PHP`
- 🌎 [PrestaShop](www.prestashop.com/) - PrestaShop offers a free, open-source and fully scalable e-commerce solution.  🌎 [Demo](demo.prestashop.com/), <b><code>&nbsp;&nbsp;8502⭐</code></b> <b><code>&nbsp;&nbsp;4882🍴</code></b> [Source Code](https://github.com/PrestaShop/PrestaShop))) `OSL-3.0` `PHP`
- 🌎 [Pretix](pretix.eu/) - Django based ticket sales platform for events. (<b><code>&nbsp;&nbsp;2034⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;503🍴</code></b> [Source Code](https://github.com/pretix/pretix))) `Apache-2.0` `Python/Docker`
- 🌎 [s-cart](s-cart.org/) - S-Cart is a free e-commerce website project for individuals and businesses, built on top of Laravel Framework.  🌎 [Demo](demo.s-cart.org/), <b><code>&nbsp;&nbsp;&nbsp;700⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;348🍴</code></b> [Source Code](https://github.com/s-cart/s-cart))) `MIT` `PHP`
- 🌎 [Saleor](saleor.io) - Django based open-sourced e-commerce storefront.  🌎 [Demo](demo.saleor.io/), <b><code>&nbsp;21394⭐</code></b> <b><code>&nbsp;&nbsp;5647🍴</code></b> [Source Code](https://github.com/saleor/saleor))) `BSD-3-Clause` `Docker/Python`
- 🌎 [Shopware Community Edition](www.shopware.com/en/community/community-edition/) - PHP based open source e-commerce software made in Germany.  🌎 [Demo](www.shopware.com/en/test-demo/), <b><code>&nbsp;&nbsp;3011⭐</code></b> <b><code>&nbsp;&nbsp;1070🍴</code></b> [Source Code](https://github.com/shopware/platform))) `MIT` `PHP`
- 🌎 [Solidus](solidus.io/) - A free, open-source ecommerce platform that gives you complete control over your store. (<b><code>&nbsp;&nbsp;5135⭐</code></b> <b><code>&nbsp;&nbsp;1323🍴</code></b> [Source Code](https://github.com/solidusio/solidus))) `BSD-3-Clause` `Ruby/Docker`
- 🌎 [Spree Commerce](spreecommerce.org) - Spree is a complete, modular & API-driven open source e-commerce solution for Ruby on Rails.  🌎 [Demo](demo.spreecommerce.org/), <b><code>&nbsp;14554⭐</code></b> <b><code>&nbsp;&nbsp;5070🍴</code></b> [Source Code](https://github.com/spree/spree))) `BSD-3-Clause` `Ruby`
- 🌎 [Sylius](sylius.com) - Symfony2 powered open source full-stack platform for eCommerce.  🌎 [Demo](sylius.com/try/), <b><code>&nbsp;&nbsp;8180⭐</code></b> <b><code>&nbsp;&nbsp;2116🍴</code></b> [Source Code](https://github.com/Sylius/Sylius))) `MIT` `PHP`
- 🌎 [Thelia](thelia.net/) - Thelia is an open source and flexible e-commerce solution.  🌎 [Demo](demo.thelia.net/), <b><code>&nbsp;&nbsp;&nbsp;861⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;310🍴</code></b> [Source Code](https://github.com/thelia/thelia))) `LGPL-3.0` `PHP`
- 🌎 [Vendure](www.vendure.io) - A headless commerce framework.  🌎 [Demo](demo.vendure.io), <b><code>&nbsp;&nbsp;6148⭐</code></b> <b><code>&nbsp;&nbsp;1100🍴</code></b> [Source Code](https://github.com/vendure-ecommerce/vendure))) `MIT` `Nodejs`
- 🌎 [WooCommerce](woocommerce.com/) - WordPress based e-commerce solution. (<b><code>&nbsp;&nbsp;9692⭐</code></b> <b><code>&nbsp;10771🍴</code></b> [Source Code](https://github.com/woocommerce/woocommerce))) `GPL-3.0` `PHP`


### Federated Identity & Authentication

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Federated identity](en.wikipedia.org/wiki/Federated_identity) and 🌎 [authentication](en.wikipedia.org/wiki/Electronic_authentication) software.

**Please visit <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/Identity Management](https://github.com/awesome-foss/awesome-sysadmin#identity-management))**



### Feed Readers

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [news aggregator](en.wikipedia.org/wiki/News_aggregator), also termed a feed aggregator, feed reader, news reader, 🌎 [RSS](en.wikipedia.org/wiki/RSS) reader, is an application that aggregates web content such as newspapers/blogs/vlogs/podcasts in one location for easy viewing.

- <b><code>&nbsp;&nbsp;&nbsp;203⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Bubo Reader](https://github.com/georgemandis/bubo-rss)) - Irrationally minimal RSS feed reader.  🌎 [Demo](bubo-rss-demo.netlify.app/)) `MIT` `Nodejs`
- 🌎 [CommaFeed](www.commafeed.com/) - Google Reader inspired self-hosted RSS reader.  🌎 [Demo](www.commafeed.com/#/app/category/all), <b><code>&nbsp;&nbsp;3019⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;385🍴</code></b> [Source Code](https://github.com/Athou/commafeed))) `Apache-2.0` `Java/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [FeedCord](https://github.com/Qolors/FeedCord)) `⚠` - A simple, lightweight & customizable RSS News Feed for your Discord Server. `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;362⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Feedpushr](https://github.com/ncarlier/feedpushr)) - Powerful RSS aggregator, able to transform and send articles to many outputs. Single binary, extensible with plugins. `GPL-3.0` `Go/Docker`
- 🌎 [Feeds Fun](feeds.fun/) - News reader with tags, scoring, and AI. (<b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/Tiendil/feeds.fun))) `BSD-3-Clause` `Python`
- 🌎 [FreshRSS](freshrss.org/) - Self-hostable RSS feed aggregator.  🌎 [Demo](demo.freshrss.org/i/), <b><code>&nbsp;11276⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;925🍴</code></b> [Source Code](https://github.com/FreshRSS/FreshRSS)), <b><code>&nbsp;&nbsp;&nbsp;124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Clients](https://github.com/Alkarex/EasyRSS))) `AGPL-3.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;1509⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Fusion](https://github.com/0x2E/fusion)) - A lightweight RSS aggregator and reader. `MIT` `Go/Docker`
- 🌎 [JARR](1pxsolidblack.pl/jarr-en.html) - JARR (Just Another RSS Reader) is a web-based news aggregator and reader (fork of Newspipe).  🌎 [Demo](www.jarr.info/), <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Source Code](https://github.com/jaesivsm/JARR))) `AGPL-3.0` `Docker/Python`
- <b><code>&nbsp;&nbsp;&nbsp;283⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Kriss Feed](https://github.com/tontof/kriss_feed)) - Simple and smart (or stupid) feed reader. `CC0-1.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Leed](https://github.com/LeedRSS/Leed)) - Leed (for Light Feed) is a Free and minimalist RSS aggregator. `AGPL-3.0` `PHP`
- 🌎 [Miniflux](miniflux.app/) - Miniflux is a minimalist and open source news reader, written in Go and PostgreSQL. (<b><code>&nbsp;&nbsp;7472⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;765🍴</code></b> [Source Code](https://github.com/miniflux/v2))) `Apache-2.0` `Go/deb/Docker`
- 🌎 [NewsBlur](www.newsblur.com/) - NewsBlur is a personal news reader that brings people together to talk about the world. A new sound of an old instrument. (<b><code>&nbsp;&nbsp;7043⭐</code></b> <b><code>&nbsp;&nbsp;1010🍴</code></b> [Source Code](https://github.com/samuelclay/NewsBlur))) `MIT` `Python`
- 🌎 [Newspipe](git.sr.ht/~cedric/newspipe) - Newspipe is a web news reader.  🌎 [Demo](www.newspipe.org/signup)) `AGPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Precis](https://github.com/leozqin/precis)) - Extensibility-oriented RSS reader that can use LLMs (including local LLMs) to summarize RSS entries with built-in notification support. `MIT` `Python/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;483⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [reader](https://github.com/lemon24/reader)) - A Python feed reader web app and library (so you can use it to build your own), with only standard library and pure-Python dependencies. `BSD-3-Clause` `Python`
- 🌎 [Readflow](readflow.app) - Lightweight news reader with modern interface and features: full-text search, automatic categorization, archiving, offline support, notifications... (<b><code>&nbsp;&nbsp;&nbsp;433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Source Code](https://github.com/ncarlier/readflow))) `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;7869⭐</code></b> <b><code>&nbsp;&nbsp;1079🍴</code></b> [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge)) - Generate RSS/ATOM feeds for websites which don't have one. `Unlicense` `PHP/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;450⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [RSS Monster](https://github.com/pietheinstrengholt/rssmonster)) - An easy to use web-based RSS aggregator and reader compatible with the Fever API (alternative to Google Reader). `MIT` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;401⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [RSS2EMail](https://github.com/rss2email/rss2email)) - Fetches RSS/Atom-feeds and pushes new Content to any email-receiver, supports OPML. `GPL-2.0` `Python/deb`
- 🌎 [RSSHub](docs.rsshub.app) - An easy to use, and extensible RSS feed aggregator, it's capable of generating RSS feeds from pretty much everything ranging from social media to university departments.  🌎 [Demo](rsshub.app), <b><code>&nbsp;36164⭐</code></b> <b><code>&nbsp;&nbsp;7953🍴</code></b> [Source Code](https://github.com/DIYgod/RSSHub))) `MIT` `Nodejs/Docker`
- 🌎 [Selfoss](selfoss.aditu.de/) - New multipurpose rss reader, live stream, mashup, aggregation web application. (<b><code>&nbsp;&nbsp;2402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;343🍴</code></b> [Source Code](https://github.com/fossar/selfoss))) `GPL-3.0` `PHP`
- <b><code>&nbsp;&nbsp;4006⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;399🍴</code></b> [Stringer](https://github.com/stringer-rss/stringer)) - Work-in-progress self-hosted, anti-social RSS reader. `MIT` `Ruby`
- 🌎 [Tiny Tiny RSS](tt-rss.org) - Open source web-based news feed (RSS/Atom) reader and aggregator.  🌎 [Demo](srv.tt-rss.org/tt-rss/), 🌎 [Source Code](git.tt-rss.org/fox/tt-rss)) `GPL-3.0` `Docker/PHP`
- <b><code>&nbsp;&nbsp;3187⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;233🍴</code></b> [Yarr](https://github.com/nkanaev/yarr)) - Yarr (yet another rss reader) is a web-based feed aggregator which can be used both as a desktop application and a personal self-hosted server. `MIT` `Go`


### File Transfer & Synchronization

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [File transfer](en.wikipedia.org/wiki/File_transfer), 🌎 [sharing](en.wikipedia.org/wiki/File_sharing) and 🌎 [synchronization software](en.wikipedia.org/wiki/File_synchronization) software.

_Related: [Groupware](#groupware)_

- 🌎 [bewCloud](bewcloud.com) - File sharing + sync, notes, and photos (alternative to Nextcloud and ownCloud's RSS reader). (<b><code>&nbsp;&nbsp;&nbsp;541⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Source Code](https://github.com/bewcloud/bewcloud)), [Clients](https://github.com/bewcloud)) `AGPL-3.0` `Docker`
- 🌎 [Git Annex](git-annex.branchable.com/) - File synchronization between computers, servers, external drives.  🌎 [Source Code](git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- 🌎 [Kinto](kinto.readthedocs.org) - Kinto is a minimalist JSON storage service with synchronisation and sharing abilities. ([Source Code](https://github.com/Kinto)) `Apache-2.0` `Python`
- 🌎 [Nextcloud](nextcloud.com/) - Access and share your files, calendars, contacts, mail and 🌎 [more](apps.nextcloud.com/) from any device, on your terms.  🌎 [Demo](try.nextcloud.com/), <b><code>&nbsp;29225⭐</code></b> <b><code>&nbsp;&nbsp;4244🍴</code></b> [Source Code](https://github.com/nextcloud/server))) `AGPL-3.0` `PHP/deb`
- 🌎 [OpenSSH SFTP server](www.openssh.com/) - Secure File Transfer Program.  🌎 [Source Code](cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh/)) `BSD-2-Clause` `C/deb`
- 🌎 [ownCloud](owncloud.org/) - All-in-one solution for saving, synchronizing, viewing, editing and sharing files, calendars, address books and more. (<b><code>&nbsp;&nbsp;8499⭐</code></b> <b><code>&nbsp;&nbsp;2057🍴</code></b> [Source Code](https://github.com/owncloud/core)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Clients](https://github.com/owncloud/core/wiki/Apps))) `AGPL-3.0` `PHP/Docker/deb`
- 🌎 [Peergos](peergos.org) - Secure and private space online where you can store, share and view your photos, videos, music and documents. Also includes a calendar, news feed, task lists, chat and email client. ([Source Code](https://github.com/Peergos)) `AGPL-3.0` `Java`
- 🌎 [Puter](puter.com/) - Web-based operating system designed to be feature-rich, exceptionally fast, and highly extensible.  🌎 [Demo](puter.com/), <b><code>&nbsp;30156⭐</code></b> <b><code>&nbsp;&nbsp;2232🍴</code></b> [Source Code](https://github.com/heyputer/puter))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Pydio](pydio.com/) - Turn any web server into a powerful file management system and an alternative to mainstream cloud storage providers.  🌎 [Demo](pydio.com/en/demo), <b><code>&nbsp;&nbsp;1939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [Source Code](https://github.com/pydio/cells))) `AGPL-3.0` `Go`
- 🌎 [Samba](www.samba.org/) - Samba is the standard Windows interoperability suite of programs for Linux and Unix. It provides secure, stable and fast file and print services for all clients using the SMB/CIFS protocol.  🌎 [Source Code](git.samba.org/samba.git/)) `GPL-3.0` `C`
- 🌎 [Seafile](www.seafile.com/en/home/) - File hosting and sharing solution primary for teams and organizations. (<b><code>&nbsp;12970⭐</code></b> <b><code>&nbsp;&nbsp;1571🍴</code></b> [Source Code](https://github.com/haiwen/seafile))) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- 🌎 [Syncthing](syncthing.net/) - Syncthing is an open source peer-to-peer file synchronisation tool. (<b><code>&nbsp;69390⭐</code></b> <b><code>&nbsp;&nbsp;4474🍴</code></b> [Source Code](https://github.com/syncthing/syncthing))) `MPL-2.0` `Go/Docker/deb`
- 🌎 [Unison](www.cis.upenn.edu/~bcpierce/unison/) - Unison is a file-synchronization tool for OSX, Unix, and Windows. (<b><code>&nbsp;&nbsp;4496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [Source Code](https://github.com/bcpierce00/unison))) `GPL-3.0` `deb/OCaml`


### File Transfer - Distributed Filesystems

**[`^        back to top        ^`](#awesome-selfhosted)**

Network distributed filesystems.

**Please visit <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/Distributed Filesystems](https://github.com/awesome-foss/awesome-sysadmin#distributed-filesystems))**



### File Transfer - Object Storage & File Servers

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Object storage](en.wikipedia.org/wiki/Object_storage) is a computer data storage that manages data as objects, as opposed to other storage architectures like file systems which manages data as a file hierarchy, and block storage which manages data as blocks within sectors and tracks.

- 🌎 [GarageHQ](garagehq.deuxfleurs.fr/) - An open-source geo-distributed storage service you can self-host to fulfill many needs - S3 compatible.  🌎 [Source Code](git.deuxfleurs.fr/Deuxfleurs/garage)) `AGPL-3.0` `Docker/Rust`
- 🌎 [Minio](min.io/) - Minio is an open source object storage server compatible with Amazon S3 APIs. (<b><code>&nbsp;51722⭐</code></b> <b><code>&nbsp;&nbsp;5768🍴</code></b> [Source Code](https://github.com/minio/minio))) `AGPL-3.0` `Go/Docker/K8S`
- <b><code>&nbsp;24121⭐</code></b> <b><code>&nbsp;&nbsp;2377🍴</code></b> [SeaweedFS](https://github.com/seaweedfs/seaweedfs)) - SeaweedFS is an open source distributed file system supporting WebDAV, S3 API, FUSE mount, HDFS, etc, optimized for lots of small files, and easy to add capacity. `Apache-2.0` `Go`
- <b><code>&nbsp;10238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;801🍴</code></b> [SFTPGo](https://github.com/drakkan/sftpgo)) - Flexible, fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. `AGPL-3.0` `Go/deb/Docker`
- 🌎 [Zenko CloudServer](www.zenko.io/cloudserver) - Zenko CloudServer, an open-source implementation of a server handling the Amazon S3 protocol. (<b><code>&nbsp;&nbsp;1771⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [Source Code](https://github.com/scality/cloudserver))) `Apache-2.0` `Docker/Nodejs`
- 🌎 [ZOT OCI Registry](zotregistry.dev) - A production-ready vendor-neutral OCI-native container image registry.  🌎 [Demo](zothub.io), <b><code>&nbsp;&nbsp;1200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [Source Code](https://github.com/project-zot/zot))) `Apache-2.0` `Go/Docker`


### File Transfer - Peer-to-peer Filesharing

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Peer-to-peer file sharing](en.wikipedia.org/wiki/Peer-to-peer_file_sharing) is the distribution and 🌎 [sharing](en.wikipedia.org/wiki/File_sharing) of digital media using 🌎 [peer-to-peer](en.wikipedia.org/wiki/Peer-to-peer) (P2P) networking technology.

- 🌎 [bittorrent-tracker](webtorrent.io/) - Simple, robust, BitTorrent tracker (client and server) implementation. (<b><code>&nbsp;&nbsp;1822⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;322🍴</code></b> [Source Code](https://github.com/webtorrent/bittorrent-tracker))) `MIT` `Nodejs`
- 🌎 [Dat Project](dat-ecosystem.org/) - Powerful decentralized file sharing applications built from a large ecosystem of modules. ([Source Code](https://github.com/datproject)) `MIT` `Nodejs`
- 🌎 [Deluge](deluge-torrent.org/) - Lightweight, cross-platform BitTorrent client.  🌎 [Source Code](git.deluge-torrent.org/deluge/tree/?h=develop)) `GPL-3.0` `Python/deb`
- 🌎 [qBittorrent](www.qbittorrent.org/) - Free cross-platform bittorrent client with a feature rich Web UI for remote access. (<b><code>&nbsp;30694⭐</code></b> <b><code>&nbsp;&nbsp;4164🍴</code></b> [Source Code](https://github.com/qbittorrent/qBittorrent))) `GPL-2.0` `C++`
- <b><code>&nbsp;&nbsp;5139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;295🍴</code></b> [Send](https://github.com/timvisee/send)) - Simple, private, end to end encrypted temporary file sharing, originally built by Mozilla. (<b><code>&nbsp;&nbsp;5139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;295🍴</code></b> [Clients](https://github.com/timvisee/send#clients))) `MPL-2.0` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;1530⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [slskd](https://github.com/slskd/slskd)) `⚠` - A modern client-server application for the Soulseek file sharing network. `AGPL-3.0` `Docker/C#`
- 🌎 [Transmission](transmissionbt.com/) - Fast, easy, free Bittorrent client. (<b><code>&nbsp;12935⭐</code></b> <b><code>&nbsp;&nbsp;1252🍴</code></b> [Source Code](https://github.com/transmission/transmission))) `GPL-3.0` `C++/deb`


### File Transfer - Single-click & Drag-n-drop Upload

**[`^        back to top        ^`](#awesome-selfhosted)**

Simplified file servers for sharing of one-time/short-lived/temporary files, providing single-click or 🌎 [drag-and-drop](en.wikipedia.org/wiki/Drag_and_drop) upload functionality.

- 🌎 [Chibisafe](chibisafe.moe) - File uploader service that aims to to be easy to use and set up. It accepts files, photos, documents, anything you imagine and gives you back a shareable link for you to send to others. (<b><code>&nbsp;&nbsp;2115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;278🍴</code></b> [Source Code](https://github.com/chibisafe/chibisafe))) `MIT` `Docker/Nodejs`
- 🌎 [Digirecord](ladigitale.dev/digirecord/) - Record and share audio files (documentation in French).  🌎 [Source Code](codeberg.org/ladigitale/digirecord)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [elixire](gitlab.com/elixire/elixire) - Simple yet advanced screenshot uploading and link shortening service.  🌎 [Clients](gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
- 🌎 [Enclosed](enclosed.cc/) - A minimalistic web application designed for sending private and secure notes.  🌎 [Demo](enclosed.cc/), <b><code>&nbsp;&nbsp;1317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Source Code](https://github.com/CorentinTh/enclosed))) `Apache-2.0` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;239⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Files Sharing](https://github.com/axeloz/filesharing)) - Open Source and self-hosted files sharing application based on unique and temporary links. `GPL-3.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;1850⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [Gokapi](https://github.com/Forceu/gokapi)) - Lightweight server to share files, which expire after a set amount of downloads or days. Similar to the discontinued Firefox Send, with the difference that only the admin is allowed to upload files. `GPL-3.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;290⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [goploader](https://github.com/Depado/goploader)) - Easy file sharing with server-side encryption, curl/httpie/wget compliant. `MIT` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [GoSƐ](https://github.com/stv0g/gose)) - GoSƐ is a modern file-uploader focusing on scalability and simplicity. It only depends on a S3 storage backend and hence scales horizontally without the need for additional databases or caches. `Apache-2.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;6492⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;667🍴</code></b> [OnionShare](https://github.com/onionshare/onionshare)) - Securely and anonymously share a file of any size. `GPL-2.0` `Python/deb`
- <b><code>&nbsp;&nbsp;6425⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;365🍴</code></b> [Pairdrop](https://github.com/schlagmichdoch/pairdrop)) - Local file sharing in your browser, inspired by Apple's AirDrop (fork of Snapdrop). `GPL-3.0` `Docker`
- 🌎 [PicoShare](pico.rocks) - A minimalist, easy-to-host service for sharing images and other files.  🌎 [Demo](demo.pico.rocks), <b><code>&nbsp;&nbsp;2491⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [Source Code](https://github.com/mtlynch/picoshare))) `AGPL-3.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;996⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Picsur](https://github.com/CaramelFur/Picsur)) - A simple imaging hosting platform that allows you to easily host, edit, and share images. `GPL-3.0` `Docker`
- 🌎 [PictShare](www.pictshare.net/) - PictShare is a multi lingual, open source image hosting service with a simple resizing and upload API. (<b><code>&nbsp;&nbsp;&nbsp;860⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [Source Code](https://github.com/HaschekSolutions/pictshare))) `Apache-2.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;4075⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;285🍴</code></b> [Pingvin Share](https://github.com/stonith404/pingvin-share)) - A self-hosted file sharing platform that combines lightness and beauty, perfect for seamless and efficient file sharing.  🌎 [Demo](pingvin-share.dev.eliasschneider.com)) `BSD-2-Clause` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;1541⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [Plik](https://github.com/root-gg/plik)) - Plik is a scalable and friendly temporary file upload system.  🌎 [Demo](plik.root.gg/)) `MIT` `Go/Docker`
- 🌎 [ProjectSend](www.projectsend.org/) - Upload files and assign them to specific clients you create. Give access to those files to your clients. (<b><code>&nbsp;&nbsp;1543⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;322🍴</code></b> [Source Code](https://github.com/projectsend/projectsend))) `GPL-2.0` `PHP`
- <b><code>&nbsp;&nbsp;1652⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;222🍴</code></b> [PsiTransfer](https://github.com/psi-4ward/psitransfer)) - Simple open source self-hosted file sharing solution with robust up-/download-resume and password protection. `BSD-2-Clause` `Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [QuickShare](https://github.com/ihexxa/quickshare)) - Quick and simple file sharing between different devices. `LGPL-3.0` `Docker/Go`
- <b><code>&nbsp;&nbsp;1004⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Sharry](https://github.com/eikek/sharry)) - Share files easily over the internet between authenticated and anonymous users (both ways) with resumable up- and downloads. `GPL-3.0` `Scala/Java/deb/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Shifter](https://github.com/TobySuch/Shifter)) - A simple, self-hosted file-sharing web app, powered by Django. `MIT` `Docker`
- <b><code>&nbsp;15474⭐</code></b> <b><code>&nbsp;&nbsp;1553🍴</code></b> [transfer.sh](https://github.com/dutchcoders/transfer.sh)) - Easy file sharing from the command line. `MIT` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;932⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [Uguu](https://github.com/nokonoko/uguu)) - Stores files and deletes after X amount of time. `MIT` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Uploady](https://github.com/farisc0de/Uploady)) - Uploady is a simple file uploader script with multi file upload support. `MIT` `PHP`
- 🌎 [XBackBone](xbackbone.app/) - A simple, fast and lightweight file manager with instant sharing tools integration, like ShareX (a free and open-source screenshot utility for Windows). (<b><code>&nbsp;&nbsp;1056⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [Source Code](https://github.com/SergiX44/XBackBone))) `AGPL-3.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;2044⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;163🍴</code></b> [Zipline](https://github.com/diced/zipline)) - A lightweight, fast and reliable file sharing server that is commonly used with ShareX, offering a react-based Web UI and fast API. `MIT` `Docker/Nodejs`


### File Transfer - Web-based File Managers

**[`^        back to top        ^`](#awesome-selfhosted)**

Web-based 🌎 [file managers](en.wikipedia.org/wiki/File_manager).

_Related: [Groupware](#groupware)_

- 🌎 [Apaxy](oupala.github.io/apaxy/) - Theme built to enhance the experience of browsing web directories, using the mod_autoindex Apache module and some CSS to override the default style of a directory listing. (<b><code>&nbsp;&nbsp;1891⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;258🍴</code></b> [Source Code](https://github.com/oupala/apaxy))) `GPL-3.0` `Javascript`
- <b><code>&nbsp;&nbsp;1155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [copyparty](https://github.com/9001/copyparty)) - Portable file server with accelerated resumable uploads, deduplication, WebDAV, FTP, zeroconf, media indexer, video thumbnails, audio transcoding, and write-only folders, in a single file with no mandatory dependencies.  🌎 [Demo](a.ocv.me/pub/demo/)) `MIT` `Python`
- 🌎 [DirectoryLister](www.directorylister.com/) - Simple PHP based directory lister that lists a directory and all its sub-directories and allows you to navigate there within. (<b><code>&nbsp;&nbsp;2329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;515🍴</code></b> [Source Code](https://github.com/DirectoryLister/DirectoryLister))) `MIT` `PHP`
- 🌎 [filebrowser](filebrowser.org/) - Web File Browser with a Material Design web interface. (<b><code>&nbsp;28591⭐</code></b> <b><code>&nbsp;&nbsp;3221🍴</code></b> [Source Code](https://github.com/filebrowser/filebrowser))) `Apache-2.0` `Go`
- 🌎 [FileGator](filegator.io/) - FileGator is a powerful multi-user file manager with a single page front-end.  🌎 [Demo](demo.filegator.io), <b><code>&nbsp;&nbsp;2368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;397🍴</code></b> [Source Code](https://github.com/filegator/filegator))) `MIT` `PHP/Docker`
- 🌎 [Filestash](www.filestash.app/) - A web file manager that lets you manage your data anywhere it is located: FTP, SFTP, WebDAV, Git, S3, Minio, Dropbox, or Google Drive.  🌎 [Demo](demo.filestash.app/), <b><code>&nbsp;11193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;827🍴</code></b> [Source Code](https://github.com/mickael-kerjean/filestash))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;963⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [Gossa](https://github.com/pldubouilh/gossa)) - Gossa is a light and simple webserver for your files. `MIT` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [IFM](https://github.com/misterunknown/ifm)) - Single script file manager. `MIT` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;302⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [mikochi](https://github.com/zer0tonin/Mikochi)) - Browse remote folders, upload files, delete, rename, download and stream files to VLC/mpv. `MIT` `Go/Docker/K8S`
- <b><code>&nbsp;&nbsp;6536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;315🍴</code></b> [miniserve](https://github.com/svenstaro/miniserve)) - CLI tool to serve files and dirs over HTTP. `MIT` `Rust`
- 🌎 [ResourceSpace](www.resourcespace.com) - ResourceSpace open source digital asset management software is the simple, fast, and free way to organise your digital assets.  🌎 [Demo](www.resourcespace.com/trial), 🌎 [Source Code](www.resourcespace.com/svn)) `BSD-4-Clause` `PHP`
- 🌎 [Surfer](git.cloudron.io/cloudron/surfer) - Simple static file server with webui to manage files. `MIT` `Nodejs`
- 🌎 [TagSpaces](www.tagspaces.org/) - TagSpaces is an offline, cross-platform file manager and organiser that also can function as a note taking app. The WebDAV version of the application can be installed on top of a WebDAV servers such as Nextcloud or ownCloud.  🌎 [Demo](demo.tagspaces.com), <b><code>&nbsp;&nbsp;4139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;427🍴</code></b> [Source Code](https://github.com/tagspaces/tagspaces))) `AGPL-3.0` `Nodejs`
- 🌎 [Tiny File Manager](tinyfilemanager.github.io) - Web based File Manager in PHP, simple, fast and small file manager with a single file.  🌎 [Demo](tinyfilemanager.github.io/demo/), <b><code>&nbsp;&nbsp;5262⭐</code></b> <b><code>&nbsp;&nbsp;1722🍴</code></b> [Source Code](https://github.com/prasathmani/tinyfilemanager))) `GPL-3.0` `PHP`


### Games

**[`^        back to top        ^`](#awesome-selfhosted)**

Multiplayer game servers and 🌎 [browser games](en.wikipedia.org/wiki/Browser_game).

_Related: [Games - Administrative Utilities & Control Panels](#games---administrative-utilities--control-panels)_

- 🌎 [0 A.D.](play0ad.com/) - Cross-platform real-time strategy game of ancient warfare.  🌎 [Source Code](gitea.wildfiregames.com/0ad/0ad)) `MIT/GPL-2.0/Zlib` `C++/C/deb`
- <b><code>&nbsp;&nbsp;7524⭐</code></b> <b><code>&nbsp;&nbsp;1646🍴</code></b> [A Dark Room](https://github.com/doublespeakgames/adarkroom)) - Minimalist text adventure game for your browser.  🌎 [Demo](adarkroom.doublespeakgames.com/)) `MPL-2.0` `Javascript`
- 🌎 [Digibuzzer](digibuzzer.app/) - Create a virtual game room around a connected buzzer (documentation in French).  🌎 [Demo](digibuzzer.app/), 🌎 [Source Code](codeberg.org/ladigitale/digibuzzer)) `AGPL-3.0` `Nodejs`
- 🌎 [Lila](lichess.org/) - The forever free, adless and open source chess server powering lichess.org, with official iOS and Android client apps. (<b><code>&nbsp;16477⭐</code></b> <b><code>&nbsp;&nbsp;2372🍴</code></b> [Source Code](https://github.com/lichess-org/lila))) `AGPL-3.0` `Scala`
- 🌎 [Luanti](www.luanti.org/) - An open source voxel game engine (formerly Minetest). Play one of our many games, mod a game to your liking, make your own game, or play on a multiplayer server. (<b><code>&nbsp;11323⭐</code></b> <b><code>&nbsp;&nbsp;2092🍴</code></b> [Source Code](https://github.com/minetest/minetest))) `LGPL-2.1/MIT/Zlib` `C++/Lua/deb`
- 🌎 [Mindustry](mindustrygame.github.io/) - Factorio-like tower defense game. Build production chains to gather more resources, and build complex facilities. (<b><code>&nbsp;23604⭐</code></b> <b><code>&nbsp;&nbsp;3068🍴</code></b> [Source Code](https://github.com/Anuken/Mindustry))) `GPL-3.0` `Java`
- 🌎 [MTA:SA](multitheftauto.com/) `⚠` - Multi Theft Auto (MTA) is a software project that adds network play functionality to Rockstar North's Grand Theft Auto game series, in which this functionality is not originally found. (<b><code>&nbsp;&nbsp;1487⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;451🍴</code></b> [Source Code](https://github.com/multitheftauto/mtasa-blue))) `GPL-3.0` `C++`
- 🌎 [OpenTTD](www.openttd.org/) - Open source transport tycoon simulation game. (<b><code>&nbsp;&nbsp;6829⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;971🍴</code></b> [Source Code](https://github.com/OpenTTD/OpenTTD)), 🌎 [Clients](bananas.openttd.org/)) `GPL-2.0` `C++/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [piqueserver](https://github.com/piqueserver/piqueserver)) - Server for openspades, the first-person shooter in a destructible voxel world. (<b><code>&nbsp;&nbsp;1159⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [Clients](https://github.com/yvt/openspades))) `GPL-3.0` `Python/C++`
- <b><code>&nbsp;&nbsp;&nbsp;631⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [Posio](https://github.com/abrenaut/posio)) - Geography multiplayer game. `MIT` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;259⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Quizmaster](https://github.com/nymanjens/quizmaster)) - A web-app for conducting a quiz, including a page for players to enter their answers. `Apache-2.0` `Scala`
- 🌎 [Red Eclipse 2](redeclipse.net) - A FOSS Arena First-Person Shooter Similar to Unreal Tournament. (<b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Source Code](https://github.com/redeclipse/base))) `Zlib/MIT/CC-BY-SA-4.0` `C/C++/deb`
- <b><code>&nbsp;&nbsp;&nbsp;517⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;191🍴</code></b> [Scribble.rs](https://github.com/scribble-rs/scribble.rs)) - A web-based pictionary game.  🌎 [Demo](scribblers.fly.dev)) `BSD-3-Clause` `Go/Docker`
- 🌎 [Suroi](suroi.io/) - An open-source 2D battle royale game inspired by surviv.io.  🌎 [Demo](suroi.io/), <b><code>&nbsp;&nbsp;&nbsp;348⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;189🍴</code></b> [Source Code](https://github.com/HasangerGames/suroi))) `GPL-3.0` `Nodejs`
- <b><code>&nbsp;&nbsp;5879⭐</code></b> <b><code>&nbsp;&nbsp;1070🍴</code></b> [The Battle for Wesnoth](https://github.com/wesnoth/wesnoth)) - The Battle for Wesnoth is an Open Source, turn-based tactical strategy game with a high fantasy theme, featuring both singleplayer and online/hotseat multiplayer combat. `GPL-2.0` `C++/deb`
- 🌎 [Veloren](veloren.net/) - Multiplayer RPG. Open-source game inspired by Cube World, Legend of Zelda, Dwarf Fortress and Minecraft.  🌎 [Source Code](gitlab.com/veloren/veloren)) `GPL-3.0` `Rust`
- <b><code>&nbsp;&nbsp;&nbsp;192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [Word Mastermind](https://github.com/clupasq/word-mastermind)) - Wordle clone. A Mastermind-like game, but instead of colors you need to guess words.  🌎 [Demo](word-mastermind.glitch.me/)) `MIT` `Nodejs`
- 🌎 [Zero-K](zero-k.info/) - Open Source on Springrts engine. Zero-K is a traditional real time strategy game with a focus on player creativity through terrain manipulation, physics, and a large roster of unique units - all while being balanced to support competitive play. (<b><code>&nbsp;&nbsp;&nbsp;714⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;218🍴</code></b> [Source Code](https://github.com/ZeroK-RTS/Zero-K))) `GPL-2.0` `Lua`


### Games - Administrative Utilities & Control Panels

**[`^        back to top        ^`](#awesome-selfhosted)**

Utilities for managing game servers.

_Related: [Games](#games)_

- 🌎 [auto-mcs](www.auto-mcs.com) - Cross-platform Minecraft server manager. (<b><code>&nbsp;&nbsp;&nbsp;240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/macarooni-man/auto-mcs))) `AGPL-3.0` `Python`
- 🌎 [Crafty Controller](craftycontrol.com/) - Crafty Controller is a free and open-source Minecraft launcher and manager that allows users to start and administer Minecraft servers from a user-friendly interface.  🌎 [Source Code](gitlab.com/crafty-controller/crafty-4)) `GPL-3.0` `Docker/Python`
- 🌎 [EasyWI](easy-wi.com) - Easy-Wi is a Web-interface that allows you to manage server daemons like gameservers. In addition it provides you with a CMS which includes a fully automated game- and voiceserver lending service. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/easy-wi/developer/))) `GPL-3.0` `PHP/Shell`
- <b><code>&nbsp;&nbsp;&nbsp;526⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Gaseous Server](https://github.com/gaseous-project/gaseous-server)) `⚠` - A game ROM manager, with a built in web based emulator using multiple sources to identify and provide metadata. `AGPL-3.0` `Docker/.NET`
- 🌎 [Kubek](kubek.seeeroy.ru) - Web management panel for Minecraft servers. (<b><code>&nbsp;&nbsp;&nbsp;108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Source Code](https://github.com/seeroy/kubek-minecraft-dashboard))) `GPL-3.0` `Nodejs`
- 🌎 [Lancache](lancache.net) `⚠` - LAN Party game caching made easy. (<b><code>&nbsp;&nbsp;&nbsp;789⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Source Code](https://github.com/lancachenet/monolithic))) `MIT` `Docker/Shell`
- 🌎 [LinuxGSM](linuxgsm.com/) - CLI tool for deployment and management of dedicated game servers on Linux: more than 120 games are supported. (<b><code>&nbsp;&nbsp;4494⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;842🍴</code></b> [Source Code](https://github.com/GameServerManagers/LinuxGSM))) `MIT` `Shell`
- <b><code>&nbsp;&nbsp;&nbsp;927⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Lodestone](https://github.com/Lodestone-Team/lodestone)) - A free, open source server hosting tool for Minecraft and other multiplayers. `AGPL-3.0` `Docker/Rust`
- 🌎 [Minus Games](accessory.github.io/minus_games_user_guide) - Sync games and save files across multiple devices. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/Accessory/minus_games))) `MIT` `Rust`
- 🌎 [Pelican Panel](pelican.dev/) - Web application for easy management of game servers, offering a user-friendly interface for deploying, configuring, and managing servers, server monitoring tools, and extensive customization options (fork of Pterodactyl). (<b><code>&nbsp;&nbsp;1233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [Source Code](https://github.com/pelican-dev/panel))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Pterodactyl](pterodactyl.io/) - Management panel for game servers, with an intuitive UI for end users. (<b><code>&nbsp;&nbsp;7424⭐</code></b> <b><code>&nbsp;&nbsp;1975🍴</code></b> [Source Code](https://github.com/pterodactyl/panel))) `MIT` `PHP`
- 🌎 [PufferPanel](www.pufferpanel.com/) - PufferPanel is an open source game server management panel, designed for both small networks and game server providers. (<b><code>&nbsp;&nbsp;1480⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;237🍴</code></b> [Source Code](https://github.com/pufferpanel/pufferpanel))) `Apache-2.0` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;540⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [RconCli](https://github.com/gorcon/rcon-cli)) - CLI for executing queries on a remote Valve Source dedicated server using the RCON Protocol. `MIT` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;996⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Retrom](https://github.com/JMBeresford/retrom)) - Private cloud game library distribution server + frontend/launcher. `GPL-3.0` `Docker/Rust`
- 🌎 [RomM](romm.app/) `⚠` - ROM manager for organizing, enriching, and playing retro games, with support for 400+ platforms.  🌎 [Demo](demo.romm.app/), <b><code>&nbsp;&nbsp;3535⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;154🍴</code></b> [Source Code](https://github.com/rommapp/romm))) `AGPL-3.0` `Docker`
- 🌎 [SourceBans++](sbpp.github.io/) - Admin, ban, and communication management system for games running on the Source engine. (<b><code>&nbsp;&nbsp;&nbsp;342⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [Source Code](https://github.com/sbpp/sourcebans-pp))) `CC-BY-SA-4.0` `PHP`
- 🌎 [Sunshine](app.lizardbyte.dev/Sunshine/) - Remote game stream host for Moonlight with support up to 120 frames per second and 4K resolution. (<b><code>&nbsp;24353⭐</code></b> <b><code>&nbsp;&nbsp;1162🍴</code></b> [Source Code](https://github.com/LizardByte/Sunshine))) `GPL-3.0` `C++/deb/Docker`


### Genealogy

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Genealogy software](en.wikipedia.org/wiki/Genealogy_software) used to record, organize, and publish genealogical data.

- 🌎 [Genea.app](www.genea.app/) - Genea is a privacy by design and open source tool anyone can use to author or edit their family tree. Data is stored in the GEDCOM format and all processing is done in the browser. (<b><code>&nbsp;&nbsp;&nbsp;225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Source Code](https://github.com/genea-app/genea-app))) `MIT` `Javascript`
- 🌎 [GeneWeb](geneweb.tuxfamily.org/wiki/GeneWeb) - Genealogy software. It comes with a Web interface and can be used off-line or as a Web service.  🌎 [Demo](demo.geneweb.tuxfamily.org/gw7/), <b><code>&nbsp;&nbsp;&nbsp;338⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [Source Code](https://github.com/geneweb/geneweb))) `GPL-2.0` `OCaml`
- 🌎 [Gramps Web](www.grampsweb.org/) - Web app for collaborative genealogy, based on and interoperable with Gramps, the open source genealogy desktop application.  🌎 [Demo](gramps-project.github.io/gramps-web-api/), <b><code>&nbsp;&nbsp;&nbsp;103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Source Code](https://github.com/gramps-project/gramps-web-api))) `AGPL-3.0` `Docker`
- 🌎 [webtrees](www.webtrees.net) - Webtrees is the web's leading online collaborative genealogy application.  🌎 [Demo](dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), <b><code>&nbsp;&nbsp;&nbsp;588⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;310🍴</code></b> [Source Code](https://github.com/fisharebest/webtrees))) `GPL-3.0` `PHP`


### Groupware

**[`^        back to top        ^`](#awesome-selfhosted)**

Collaborative software or 🌎 [groupware](en.wikipedia.org/wiki/Collaborative_software) is designed to help people working on a common task to attain their goals. Groupware often regroups multiple services such as file sharing, calendar/events management, address books... in a single, integrated application.

- 🌎 [Citadel](www.citadel.org/) - Groupware including email, calendar/scheduling, address books, forums, mailing lists, IM, wiki and blog engines, RSS aggregation and more.  🌎 [Source Code](www.citadel.org/source.html)) `GPL-3.0` `C/Docker/Shell`
- 🌎 [Cozy Cloud](cozy.io/) - Personal cloud where you can manage and sync your contact, files and calendars, and manage your budget with an app store full of community contributions. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/cozy/))) `GPL-3.0` `Nodejs`
- 🌎 [Digipad](digipad.app/) - An online self-hosted application for creating collaborative digital notepads (Documentation in french).  🌎 [Source Code](codeberg.org/ladigitale/digipad)) `AGPL-3.0` `Nodejs`
- 🌎 [Digistorm](digistorm.app/) - Create collaborative surveys, quizzes, brainstorms, and word clouds (documentation in French).  🌎 [Demo](digistorm.app/), 🌎 [Source Code](codeberg.org/ladigitale/digistorm)) `AGPL-3.0` `Nodejs`
- 🌎 [Digiwall](digiwall.app/) - Create multimedia collaborative walls for in-person or remote work (documentation in French).  🌎 [Source Code](codeberg.org/ladigitale/digiwall)) `AGPL-3.0` `Nodejs`
- 🌎 [egroupware](www.egroupware.org/) - Software suite including calendars, address books, notepad, project management tools, client relationship management tools (CRM), knowledge management tools, a wiki and a CMS. (<b><code>&nbsp;&nbsp;&nbsp;265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [Source Code](https://github.com/EGroupware/egroupware))) `GPL-2.0` `PHP`
- 🌎 [Group Office](www.group-office.com) - Group-Office is an enterprise CRM and groupware tool. Share projects, calendars, files and e-mail online with co-workers and clients. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/Intermesh/groupoffice/))) `AGPL-3.0` `PHP`
- 🌎 [Openmeetings](openmeetings.apache.org/index.html) - Openmeetings provides video conferencing, instant messaging, white board, collaborative document editing and other groupware tools using API functions of the Red5 Streaming Server for Remoting and Streaming.  🌎 [Source Code](openmeetings.apache.org/scm.html)) `Apache-2.0` `Java`
- 🌎 [SOGo](www.sogo.nu/) - SOGo offers multiple ways to access the calendaring and messaging data. CalDAV, CardDAV, GroupDAV, as well as ActiveSync, including native Outlook compatibility and Web interface.  🌎 [Demo](demo.sogo.nu/SOGo/), <b><code>&nbsp;&nbsp;1900⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;284🍴</code></b> [Source Code](https://github.com/Alinto/sogo))) `LGPL-2.1` `Objective-C`
- 🌎 [Tine](www.tine-groupware.de/) - Software for digital collaboration in companies and organizations. From powerful groupware functionalities to clever add-ons, tine combines everything to make daily team collaboration easier. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/tine-groupware/tine))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;227⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Tracim](https://github.com/tracim/tracim)) - Collaborative Platform for team collaboration: file,threads,notes,agenda,etc. `AGPL-3.0/LGPL-3.0/MIT` `Python`
- 🌎 [Zimbra Collaboration](www.zimbra.com/) - Email, calendar, collaboration server with Web interface and lots of integrations. ([Source Code](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`


### Human Resources Management (HRM)

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [human resources management system](en.wikipedia.org/wiki/Human_resource_management_system) combines a number of systems and processes to ensure the easy management of 🌎 [human resources](en.wikipedia.org/wiki/Human_resources), business processes and data.

- 🌎 [admidio](www.admidio.org/) - User management system for websites of organizations and groups. The system has a flexible role model so that it’s possible to reflect the structure and permissions of your organization.  🌎 [Demo](www.admidio.org/demo/), <b><code>&nbsp;&nbsp;&nbsp;369⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [Source Code](https://github.com/Admidio/admidio))) `GPL-2.0` `PHP/Docker`
- 🌎 [Frappe HR](frappe.io/hr) - Complete HRMS solution with over 13 different modules right from employee management, onboarding, leaves, to payroll, taxation, and more. (<b><code>&nbsp;&nbsp;1996⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;990🍴</code></b> [Source Code](https://github.com/frappe/hrms))) `GPL-3.0` `Docker/Python/Nodejs`
- 🌎 [MintHCM](minthcm.org/) - Tool for Human Capital Management based on two popular, well-known business applications SugarCRM Community Edition and SuiteCRM. (<b><code>&nbsp;&nbsp;&nbsp;171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Source Code](https://github.com/minthcm/minthcm))) `AGPL-3.0` `PHP`
- 🌎 [OrangeHRM](www.orangehrm.com/) - OrangeHRM is a comprehensive HRM system that captures all the essential functionalities required for any enterprise.  🌎 [Demo](opensource-demo.orangehrmlive.com/), <b><code>&nbsp;&nbsp;&nbsp;899⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;600🍴</code></b> [Source Code](https://github.com/orangehrm/orangehrm))) `GPL-2.0` `PHP`


### Identity Management

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Identity management](en.wikipedia.org/wiki/Identity_management) (IdM), also known as identity and access management (IAM or IdAM), is a framework of policies and technologies to ensure that the right users have the appropriate access to technology resources.

**Please visit <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/Identity Management](https://github.com/awesome-foss/awesome-sysadmin#identity-management))**



### Internet of Things (IoT)

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Internet of Things](en.wikipedia.org/wiki/Internet_of_things) describes physical objects with sensors, processing ability, software, and other technologies that connect and exchange data with other devices over the Internet.

- 🌎 [Domoticz](www.domoticz.com/) - Home Automation System that lets you monitor and configure various devices like: Lights, Switches, various sensors/meters like Temperature, Rain, Wind, UV, Electra, Gas, Water and much more. (<b><code>&nbsp;&nbsp;3580⭐</code></b> <b><code>&nbsp;&nbsp;1134🍴</code></b> [Source Code](https://github.com/domoticz/domoticz)), <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [Clients](https://github.com/domoticz/domoticz-android))) `GPL-3.0` `C/C++/Docker/Shell`
- 🌎 [EMQX](www.emqx.io/) - An ultra-scalable open-source MQTT broker. Connect 100M+ IoT devices in one single cluster, move and process real-time IoT data with 1M msg/s throughput at 1ms latency.  🌎 [Demo](www.emqx.com/en/mqtt/public-mqtt5-broker), <b><code>&nbsp;14666⭐</code></b> <b><code>&nbsp;&nbsp;2292🍴</code></b> [Source Code](https://github.com/emqx/emqx))) `Apache-2.0` `Docker/Erlang`
- 🌎 [FHEM](fhem.de/fhem.html) - FHEM is used to automate common tasks in the household like switching lamps and heating. It can also be used to log events like temperature or power consumption. You can control it via web or smartphone frontends, telnet or TCP/IP directly.  🌎 [Source Code](svn.fhem.de/trac)) `GPL-3.0` `Perl`
- 🌎 [FlowForge](flowforge.com/) - FlowForge allows companies to deploy Node-RED applications in a reliable, scalable and secure manner. The FlowForge platform provides DevOps capabilities for Node-RED development teams. (<b><code>&nbsp;&nbsp;&nbsp;316⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Source Code](https://github.com/flowforge/flowforge))) `Apache-2.0` `Nodejs/Docker/K8S`
- 🌎 [Gladys](gladysassistant.com/) - Gladys is a privacy-first, open-source home assistant. (<b><code>&nbsp;&nbsp;2792⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;291🍴</code></b> [Source Code](https://github.com/GladysAssistant/Gladys))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [Home Assistant](home-assistant.io/) - Open-source home automation platform.  🌎 [Demo](home-assistant.io/demo/), <b><code>&nbsp;78062⭐</code></b> <b><code>&nbsp;33256🍴</code></b> [Source Code](https://github.com/home-assistant/core))) `Apache-2.0` `Python/Docker`
- 🌎 [ioBroker](www.iobroker.net/) - Integration platform for the Internet of Things, focused on building automation, smart metering, ambient assisted living, process automation, visualization and data logging. (<b><code>&nbsp;&nbsp;1315⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;154🍴</code></b> [Source Code](https://github.com/ioBroker/ioBroker))) `MIT` `Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [LHA](https://github.com/javalikescript/lha)) - Light Home Automation application. LHA is fully extensible using Blockly, HTML or Lua. It includes extensions such as ConBee, Philips Hue or Z-Wave JS. `MIT` `Lua`
- 🌎 [Node RED](nodered.org/) - Browser-based flow editor that helps you wiring hardware devices, APIs and online services to create IoT solutions. (<b><code>&nbsp;20844⭐</code></b> <b><code>&nbsp;&nbsp;3530🍴</code></b> [Source Code](https://github.com/node-red/node-red))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [openHAB](www.openhab.org) - Vendor and technology agnostic open source software for home automation. (<b><code>&nbsp;&nbsp;&nbsp;995⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;436🍴</code></b> [Source Code](https://github.com/openhab/openhab-core))) `EPL-2.0` `Java`
- 🌎 [OpenRemote](openremote.io) - Open-Source IoT Platform - IoT Asset management, Flow Rules and WHEN-THEN rules, Data visualization, Edge Gateway.  🌎 [Demo](demo.openremote.io/), <b><code>&nbsp;&nbsp;1380⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;329🍴</code></b> [Source Code](https://github.com/openremote/openremote))) `AGPL-3.0` `Java`
- 🌎 [SIP Irrigation Control](dan-in-ca.github.io/SIP/) - Open source software for sprinkler/irrigation control. (<b><code>&nbsp;&nbsp;&nbsp;374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [Source Code](https://github.com/Dan-in-CA/SIP))) `GPL-3.0` `Python`
- 🌎 [Tasmota](tasmota.com) - Open source firmware for ESP devices. Total local control with quick setup and updates. Control using MQTT, Web UI, HTTP or serial. Automate using timers, rules or scripts. Integration with home automation solutions. (<b><code>&nbsp;23051⭐</code></b> <b><code>&nbsp;&nbsp;4888🍴</code></b> [Source Code](https://github.com/arendst/Tasmota))) `GPL-3.0` `C/C++`
- 🌎 [Thingsboard](thingsboard.io/) - Open-source IoT Platform - Device management, data collection, processing and visualization.  🌎 [Demo](demo.thingsboard.io/signup), <b><code>&nbsp;18617⭐</code></b> <b><code>&nbsp;&nbsp;5490🍴</code></b> [Source Code](https://github.com/thingsboard/thingsboard))) `Apache-2.0` `Java/Docker/K8S`
- 🌎 [WebThings Gateway](webthings.io/gateway/) - WebThings is an open source implementation of the Web of Things, including the WebThings Gateway and the WebThings Framework. (<b><code>&nbsp;&nbsp;2620⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;334🍴</code></b> [Source Code](https://github.com/WebThingsIO/gateway))) `MPL-2.0` `Nodejs`


### Inventory Management

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Inventory management software](en.wikipedia.org/wiki/Inventory_management_software).

_Related: [Money, Budgeting & Management](#money-budgeting--management), [Resource Planning](#resource-planning)_

_See also: <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/IT Asset Management](https://github.com/awesome-foss/awesome-sysadmin#it-asset-management))_

- 🌎 [Cannery](cannery.app) - Firearm and ammunition tracker app.  🌎 [Source Code](gitea.bubbletea.dev/shibao/cannery)) `AGPL-3.0` `Docker`
- 🌎 [HomeBox (SysAdminsMedia)](homebox.software/) - Inventory and organization system built for the Home User.  🌎 [Demo](demo.homebox.software/), <b><code>&nbsp;&nbsp;2403⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [Source Code](https://github.com/sysadminsmedia/homebox))) `AGPL-3.0` `Docker/Go`
- 🌎 [Inventaire](inventaire.io/welcome) - Collaborative resources mapper project, while yet only focused on exploring books mapping with wikidata and ISBNs. (<b><code>&nbsp;&nbsp;&nbsp;456⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Source Code](https://github.com/inventaire/inventaire))) `AGPL-3.0` `Nodejs`
- 🌎 [Inventree](inventree.readthedocs.io/en/latest/) - InvenTree is an open-source inventory management system which provides intuitive parts management and stock control.  🌎 [Demo](inventree.org/demo), <b><code>&nbsp;&nbsp;4885⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;905🍴</code></b> [Source Code](https://github.com/inventree/InvenTree))) `MIT` `Python`
- 🌎 [Open QuarterMaster](openquartermaster.com/) - Powerful inventory management system, designed to be flexible and scalable. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Source Code](https://github.com/Epic-Breakfast-Productions/OpenQuarterMaster))) `GPL-3.0` `deb/Docker`
- 🌎 [Part-DB](docs.part-db.de/) - An inventory management system for your electronic components.  🌎 [Demo](demo.part-db.de/en/), <b><code>&nbsp;&nbsp;1155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;131🍴</code></b> [Source Code](https://github.com/Part-DB/Part-DB-server))) `AGPL-3.0` `Docker/PHP/Nodejs`
- 🌎 [Shelf](www.shelf.nu) - Asset and equipment tracking software used by teams who value clarity. Shelf is an asset database and QR asset label generator that lets you create, manage and overview your assets across locations. Unlimited assets, free forever. (<b><code>&nbsp;&nbsp;2060⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;200🍴</code></b> [Source Code](https://github.com/Shelf-nu/shelf.nu))) `AGPL-3.0` `Nodejs`


### Knowledge Management Tools

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Knowledge management](en.wikipedia.org/wiki/Knowledge_management) is the collection of methods relating to creating, sharing, using and managing the knowledge and information.

_Related: [Note-taking & Editors](#note-taking--editors), [Wikis](#wikis), [Database Management](#database-management)_

- <b><code>&nbsp;&nbsp;1231⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Atomic Server](https://github.com/atomicdata-dev/atomic-server)) - Knowledge graph database with documents (similar to Notion), tables, search, and a powerful linked data API. Lightweight, very fast and no runtime dependencies.  🌎 [Demo](atomicdata.dev/)) `MIT` `Docker/Rust`
- 🌎 [Digimindmap](ladigitale.dev/digimindmap/#/) - Create simple mindmaps (documentation in French).  🌎 [Demo](ladigitale.dev/digimindmap/#/), 🌎 [Source Code](codeberg.org/ladigitale/digimindmap)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [LibreKB](librekb.com/) - A web-based knowledge base solution. A simple web app, it runs on pretty much any web server or hosting provider with PHP and MySQL. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/michaelstaake/LibreKB/))) `GPL-3.0` `PHP`
- 🌎 [memEx](gitea.bubbletea.dev/shibao/memEx) - A structured personal knowledge base, inspired by zettlekasten and org-mode. `AGPL-3.0` `Docker`
- 🌎 [SiYuan](b3log.org/siyuan/) - A privacy-first personal knowledge management software, written in typescript and golang. (<b><code>&nbsp;33860⭐</code></b> <b><code>&nbsp;&nbsp;2070🍴</code></b> [Source Code](https://github.com/siyuan-note/siyuan))) `AGPL-3.0` `Docker/Go`
- <b><code>&nbsp;&nbsp;&nbsp;319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [TeamMapper](https://github.com/b310-digital/teammapper)) - Host and create your own mindmaps. Share your mindmap sessions with your team and collaborate live on mindmaps.  🌎 [Demo](map.kits.blog)) `MIT` `Docker/Nodejs`


### Learning and Courses

**[`^        back to top        ^`](#awesome-selfhosted)**

Tools and software to help with education and learning.

- 🌎 [Canvas LMS](www.instructure.com/canvas/) - Canvas is the trusted, open-source learning management system (LMS) that is revolutionizing the way we educate.  🌎 [Demo](canvas.instructure.com/register), <b><code>&nbsp;&nbsp;5946⭐</code></b> <b><code>&nbsp;&nbsp;2639🍴</code></b> [Source Code](https://github.com/instructure/canvas-lms))) `AGPL-3.0` `Ruby`
- 🌎 [Chamilo LMS](chamilo.org/) - Chamilo LMS allows you to create a virtual campus for the provision of online or semi-online training. (<b><code>&nbsp;&nbsp;&nbsp;848⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;494🍴</code></b> [Source Code](https://github.com/chamilo/chamilo-lms))) `GPL-3.0` `PHP`
- 🌎 [Digiscreen](ladigitale.dev/digiscreen/) - Interactive whiteboard/wallpaper for the classroom, in person or remotely (documentation in French).  🌎 [Demo](ladigitale.dev/digiscreen/), 🌎 [Source Code](codeberg.org/ladigitale/digiscreen)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [Digitools](ladigitale.dev/digitools) - A set of simple tools to accompany the animation of courses in person or remotely. (documentation in French).  🌎 [Demo](ladigitale.dev/digitools/), 🌎 [Source Code](codeberg.org/ladigitale/digitools)) `AGPL-3.0` `PHP`
- 🌎 [edX](www.edx.org/) - The Open edX platform is open-source code that powers edX.org. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/edx/))) `AGPL-3.0` `Python`
- 🌎 [Gibbon](gibbonedu.org/) - The flexible, open source school management platform designed to make life better for teachers, students, parents and leaders. (<b><code>&nbsp;&nbsp;&nbsp;518⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;321🍴</code></b> [Source Code](https://github.com/GibbonEdu/core))) `GPL-3.0` `PHP`
- 🌎 [ILIAS](www.ilias.de) - ILIAS is the Learning Management System that can cope with anything you throw at it.  🌎 [Demo](demo.ilias.de), <b><code>&nbsp;&nbsp;&nbsp;423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;361🍴</code></b> [Source Code](https://github.com/ILIAS-eLearning/ILIAS))) `GPL-3.0` `PHP`
- 🌎 [INGInious](inginious.org/?lang=en) - Intelligent grader that allows secured and automated testing of code made by students. (<b><code>&nbsp;&nbsp;&nbsp;219⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;140🍴</code></b> [Source Code](https://github.com/UCL-INGI/INGInious)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Clients](https://github.com/UCL-INGI/INGInious-plugins))) `AGPL-3.0` `Python/Docker`
- 🌎 [Moodle](moodle.org/) - Moodle is a learning and courses platform with one of the largest open source communities worldwide.  🌎 [Demo](moodle.org/demo/), 🌎 [Source Code](git.moodle.org/gw)) `GPL-3.0` `PHP`
- 🌎 [Open eClass](www.openeclass.org/) - Open eClass is an advanced e-learning solution that can enhance the teaching and learning process.  🌎 [Demo](demo.openeclass.org/), <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Source Code](https://github.com/gunet/openeclass))) `GPL-2.0` `PHP`
- 🌎 [OpenOLAT](www.openolat.com/?lang=en) - OpenOLAT is a web-based learning management system for teaching, education, assessment and communication.  🌎 [Demo](learn.olat.com), <b><code>&nbsp;&nbsp;&nbsp;351⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [Source Code](https://github.com/OpenOLAT/OpenOLAT))) `Apache-2.0` `Java`
- 🌎 [QST](qstonline.org) - Online assessment software. From a quick quiz on your phone to large scale, high stakes, proctored desktop testing, easy, secure and economical.  🌎 [Demo](qstonline.org/free_account.htm), 🌎 [Source Code](sourceforge.net/projects/qstonline/)) `GPL-2.0` `Perl`
- 🌎 [RELATE](documen.tician.de/relate/) - RELATE is a web-based courseware package, includes features such as: flexible rules, statistics, multi-course support, class calendar. (<b><code>&nbsp;&nbsp;&nbsp;403⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [Source Code](https://github.com/inducer/relate))) `MIT` `Python`
- 🌎 [RosarioSIS](www.rosariosis.org/) - RosarioSIS, free Student Information System for school management.  🌎 [Demo](www.rosariosis.org/demo/), 🌎 [Source Code](gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Schoco](https://github.com/PhiTux/schoco)) - Online IDE for learning Java programming at school, including automatic JUnit tests. Designed to give coding homework/assignments. `MIT` `Docker`
- 🌎 [scholarsome](www.scholarsome.com/) - Web-based and open source interactive flashcard learning software studying for the masses.  🌎 [Demo](scholarsome.com/), <b><code>&nbsp;&nbsp;&nbsp;596⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Source Code](https://github.com/hwgilbert16/scholarsome))) `GPL-3.0` `Docker`


### Manufacturing

**[`^        back to top        ^`](#awesome-selfhosted)**

Software to manage 🌎 [3D printers](en.wikipedia.org/wiki/3D_printing), 🌎 [CNC machines](en.wikipedia.org/wiki/Numerical_control) and other physical manufacturing tools.

- 🌎 [CNCjs](cnc.js.org/) - A web-based interface for CNC milling controller running Grbl, Smoothieware, or TinyG. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/cncjs/cncjs/))) `MIT` `Nodejs`
- 🌎 [Fluidd](docs.fluidd.xyz/) - Lightweight & responsive user interface for Klipper, the 3D printer firmware. (<b><code>&nbsp;&nbsp;1516⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;472🍴</code></b> [Source Code](https://github.com/fluidd-core/fluidd))) `GPL-3.0` `Docker/Nodejs`
- 🌎 [Mainsail](docs.mainsail.xyz/) - A modern and responsive user interface for the Klipper 3D printer firmware. Control and monitor your printer from everywhere, from any device. (<b><code>&nbsp;&nbsp;1855⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;415🍴</code></b> [Source Code](https://github.com/mainsail-crew/mainsail))) `GPL-3.0` `Docker/Python`
- 🌎 [Manyfold](manyfold.app) - Digital asset manager for 3d print files; STL, OBJ, 3MF and more. (<b><code>&nbsp;&nbsp;1130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Source Code](https://github.com/manyfold3d/manyfold))) `MIT` `Docker`
- 🌎 [Octoprint](octoprint.org/) - A snappy web interface for controlling consumer 3D printers. (<b><code>&nbsp;&nbsp;8519⭐</code></b> <b><code>&nbsp;&nbsp;1685🍴</code></b> [Source Code](https://github.com/OctoPrint/OctoPrint))) `AGPL-3.0` `Docker/Python`


### Maps and Global Positioning System (GPS)

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Maps](en.wikipedia.org/wiki/Map), 🌎 [cartography](en.wikipedia.org/wiki/Cartography), 🌎 [GIS](en.wikipedia.org/wiki/Geographic_information_system) and 🌎 [GPS](en.wikipedia.org/wiki/Global_Positioning_System) software.

_See also: <b><code>&nbsp;&nbsp;&nbsp;743⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [awesome-openstreetmap](https://github.com/osmlab/awesome-openstreetmap)), <b><code>&nbsp;&nbsp;4745⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;755🍴</code></b> [awesome-gis](https://github.com/sshuair/awesome-gis))_

- 🌎 [AdventureLog](adventurelog.app) - Travel tracker and trip planner.  🌎 [Demo](adventurelog.app), <b><code>&nbsp;&nbsp;1085⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Source Code](https://github.com/seanmorley15/AdventureLog))) `GPL-3.0` `Docker`
- 🌎 [AirTrail](airtrail.johan.ohly.dk) - Personal flight tracking system. (<b><code>&nbsp;&nbsp;&nbsp;484⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Source Code](https://github.com/johanohly/AirTrail))) `GPL-3.0` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Bicimon](https://github.com/knrdl/bicimon)) - Bike Speedometer as Progressive Web App.  🌎 [Demo](knrdl.github.io/bicimon/)) `MIT` `Javascript`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Geo2tz](https://github.com/noandrea/geo2tz)) - Get the timezone from geo coordinates (lat, lon). `MIT` `Go/Docker`
- 🌎 [GraphHopper](graphhopper.com/) - Fast routing library and server using OpenStreetMap. (<b><code>&nbsp;&nbsp;5713⭐</code></b> <b><code>&nbsp;&nbsp;1690🍴</code></b> [Source Code](https://github.com/graphhopper/graphhopper))) `Apache-2.0` `Java`
- 🌎 [Nominatim](nominatim.org/) - Server application for geocoding (address -> coordinates) and reverse geocoding (coordinates -> address) on OpenStreetMap data. (<b><code>&nbsp;&nbsp;3467⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;747🍴</code></b> [Source Code](https://github.com/osm-search/Nominatim))) `GPL-2.0` `C`
- [Open Source Routing Machine (OSRM)](http://project-osrm.org/) - High performance routing engine designed to run on OpenStreetMap data and offering an HTTP API, C++ library interface, and Nodejs wrapper.  🌎 [Demo](map.project-osrm.org/), <b><code>&nbsp;&nbsp;6737⭐</code></b> <b><code>&nbsp;&nbsp;3530🍴</code></b> [Source Code](https://github.com/Project-OSRM/osrm-backend))) `BSD-2-Clause` `C++`
- 🌎 [OpenRouteService](openrouteservice.org/) - Selfhosted route service with directions, isochrones, time-distance matrix, route optimization, etc.  🌎 [Demo](openrouteservice.org/dev/#/api-docs/introduction), <b><code>&nbsp;&nbsp;1575⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;431🍴</code></b> [Source Code](https://github.com/GIScience/openrouteservice))) `GPL-3.0` `Docker/Java`
- 🌎 [OpenStreetMap](www.openstreetmap.org/) - Collaborative project to create a free editable map of the world. (<b><code>&nbsp;&nbsp;2341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;958🍴</code></b> [Source Code](https://github.com/openstreetmap/openstreetmap-website)), 🌎 [Clients](wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- 🌎 [OpenTripPlanner](www.opentripplanner.org/) - Multimodal trip planning software based on OpenStreetMap data and consuming published GTFS-formatted data to suggest routes using local public transit systems. (<b><code>&nbsp;&nbsp;2318⭐</code></b> <b><code>&nbsp;&nbsp;1056🍴</code></b> [Source Code](https://github.com/opentripplanner/OpenTripPlanner))) `LGPL-3.0` `Java/Javascript`
- <b><code>&nbsp;&nbsp;&nbsp;960⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [OwnTracks Recorder](https://github.com/owntracks/recorder)) `⚠` - Store and access data published by 🌎 [OwnTracks](owntracks.org/) location tracking apps. `GPL-2.0` `C/Lua/deb/Docker`
- 🌎 [TileServer GL](tileserver.readthedocs.io/) - Vector and raster maps with GL styles. Server side rendering by Mapbox GL Native. Map tile server for Mapbox GL JS, Android, iOS, Leaflet, OpenLayers, GIS via WMTS, etc. (<b><code>&nbsp;&nbsp;2384⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;655🍴</code></b> [Source Code](https://github.com/maptiler/tileserver-gl))) `BSD-2-Clause` `Nodejs/Docker`
- 🌎 [Traccar](www.traccar.org/) - Java application to track GPS positions. Supports loads of tracking devices and protocols, has an Android and iOS App. Has a web interface to view your trips.  🌎 [Demo](demo.traccar.org/), [Source Code](https://github.com/traccar)) `Apache-2.0` `Java`
- <b><code>&nbsp;&nbsp;1900⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [wanderer](https://github.com/Flomp/wanderer)) - Trail database where you can upload your recorded tracks or create new ones and add various metadata to build an easily searchable catalogue.  🌎 [Demo](demo.wanderer.to)) `AGPL-3.0` `Docker/Go/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;573⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [μlogger](https://github.com/bfabiszewski/ulogger-server)) - Collect geolocation from users in real-time and display their GPS tracks on a website. ([Demo](http://ulogger.fabiszewski.net/)) `GPL-3.0` `PHP`


### Media Management

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Digital media](en.wikipedia.org/wiki/Digital_media) management tools and software.

_Related: [Automation](#automation), [Media Streaming](#media-streaming), [Media Streaming - Audio Streaming](#media-streaming---audio-streaming), [Media Streaming - Multimedia Streaming](#media-streaming---multimedia-streaming), [Media Streaming - Video Streaming](#media-streaming---video-streaming)_

- <b><code>&nbsp;&nbsp;&nbsp;196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [ChannelTube](https://github.com/TheWicklowWolf/ChannelTube)) `⚠` - Download video or audio from YouTube channels on a schedule via yt-dlp. `AGPL-3.0` `Docker`
- 🌎 [Dagu](dagu.readthedocs.io/) - Powerful Cron alternative with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. (<b><code>&nbsp;&nbsp;1953⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;167🍴</code></b> [Source Code](https://github.com/dagu-dev/dagu))) `GPL-3.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;3466⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;597🍴</code></b> [Headphones](https://github.com/rembo10/headphones)) - Automated music downloader for NZB and Torrent, written in Python. It supports SABnzbd, NZBget, Transmission, µTorrent, Deluge and Blackhole. `GPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;5044⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;353🍴</code></b> [Jellyseerr](https://github.com/Fallenbagel/jellyseerr)) - Manage requests for your media library, supports Plex, Jellyfin and Emby media servers (fork of Overseerr). `MIT` `Docker/Nodejs`
- 🌎 [Lidarr](lidarr.audio/) - Lidarr is a music collection manager for Usenet and BitTorrent users. (<b><code>&nbsp;&nbsp;4016⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [Source Code](https://github.com/Lidarr/Lidarr))) `GPL-3.0` `C#/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [LidaTube](https://github.com/TheWicklowWolf/LidaTube)) `⚠` - Finding and fetch missing Lidarr albums via yt-dlp. `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Lidify](https://github.com/TheWicklowWolf/Lidify)) `⚠` - Music discovery tool that provides recommendations based on selected Lidarr artists, using Spotify or LastFM. `MIT` `Docker`
- <b><code>&nbsp;&nbsp;1862⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;278🍴</code></b> [Medusa](https://github.com/pymedusa/Medusa)) - Automatic Video library manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic. (<b><code>&nbsp;&nbsp;2122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;653🍴</code></b> [Clients](https://github.com/medusajs/nextjs-starter-medusa))) `GPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;351⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [MetaTube](https://github.com/JVT038/MetaTube)) `⚠` - Automatically download music from YouTube add metadata from Spotify, Deezer or Musicbrainz. `GPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;8519⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;567🍴</code></b> [MeTube](https://github.com/alexta69/metube)) - Web GUI for youtube-dl, with playlist support. Allows downloading videos from dozens of websites. `AGPL-3.0` `Python/Nodejs/Docker`
- <b><code>&nbsp;&nbsp;1119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [nefarious](https://github.com/lardbit/nefarious)) - Automate downloading Movies and TV Shows. `GPL-3.0` `Python`
- 🌎 [Ombi](ombi.io/) - A content request system for Plex/Emby, connects to SickRage, CouchPotato, Sonarr, with a growing feature set.  🌎 [Demo](app.ombi.io/), <b><code>&nbsp;&nbsp;3860⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;407🍴</code></b> [Source Code](https://github.com/Ombi-app/Ombi))) `GPL-2.0` `C#/deb`
- 🌎 [Overseerr](overseerr.dev/) `⚠` - Overseerr is a free and open source software application for managing requests for your media library. It integrates with your existing services, such as Sonarr, Radarr, and Plex!. (<b><code>&nbsp;&nbsp;4388⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;494🍴</code></b> [Source Code](https://github.com/sct/overseerr))) `MIT` `Docker`
- <b><code>&nbsp;&nbsp;2928⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Pinchflat](https://github.com/kieraneglin/pinchflat)) `⚠` - Download YouTube content built using yt-dlp. `AGPL-3.0` `Docker`
- 🌎 [PlexRipper](www.plexripper.rocks/) `⚠` - Cross-platform Plex media downloader that seamlessly adds media from other Plex servers to your own. (<b><code>&nbsp;&nbsp;&nbsp;397⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Source Code](https://github.com/PlexRipper/PlexRipper))) `GPL-3.0` `Docker`
- 🌎 [PodFetch](samtv12345.github.io/PodFetch) - Sleek and efficient podcast downloader. (<b><code>&nbsp;&nbsp;&nbsp;404⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Source Code](https://github.com/SamTV12345/PodFetch))) `Apache-2.0` `Docker/Rust`
- 🌎 [Radarr](radarr.video/) - Radarr is an independent fork of Sonarr reworked for automatically downloading movies via Usenet and BitTorrent, à la Couchpotato. (<b><code>&nbsp;11324⭐</code></b> <b><code>&nbsp;&nbsp;1040🍴</code></b> [Source Code](https://github.com/Radarr/Radarr))) `GPL-3.0` `C#/Docker`
- <b><code>&nbsp;&nbsp;1639⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [Reiverr](https://github.com/aleksilassila/reiverr)) `⚠` - Clean combined interface for Jellyfin, TMDB, Radarr and Sonarr, as well as a replacement to Overseerr. `AGPL-3.0` `Docker`
- 🌎 [SickChill](sickchill.github.io/) - Automatic video library manager for TV shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic. (<b><code>&nbsp;&nbsp;2422⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;593🍴</code></b> [Source Code](https://github.com/SickChill/SickChill))) `GPL-3.0` `Python/Docker`
- 🌎 [Sonarr](sonarr.tv/) - Automatic TV Shows downloader and manager for Usenet and BitTorrent. It can grab, sort and rename new episodes and automatically upgrade the quality of files already downloaded when a better quality format becomes available. (<b><code>&nbsp;11633⭐</code></b> <b><code>&nbsp;&nbsp;1536🍴</code></b> [Source Code](https://github.com/Sonarr/Sonarr))) `GPL-3.0` `C#/Docker`
- <b><code>&nbsp;&nbsp;2223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;134🍴</code></b> [tubesync](https://github.com/meeb/tubesync)) `⚠` - Syncs YouTube channels and playlists to a locally hosted media server. `AGPL-3.0` `Docker/Python`
- <b><code>&nbsp;&nbsp;&nbsp;727⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Watcharr](https://github.com/sbondCo/Watcharr)) - Add and track all the shows and movies you are watching. Comes with user authentication, modern and clean UI and a very simple setup.  🌎 [Demo](beta.watcharr.app/)) `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [ydl_api_ng](https://github.com/Totonyus/ydl_api_ng)) - Simple youtube-dl REST API to launch downloads on a distant server. `GPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [YoutubeDL-Server](https://github.com/nbr23/youtube-dl-server)) - Web and REST interface to Youtube-DL for downloading videos onto a server. `MIT` `Python/Docker`
- <b><code>&nbsp;&nbsp;1432⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [yt-dlp Web UI](https://github.com/marcopeocchi/yt-dlp-web-ui)) - Web GUI for yt-dlp. `MPL-2.0` `Docker/Go/Nodejs`


### Media Streaming

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Streaming media](en.wikipedia.org/wiki/Streaming_media) is multimedia that is delivered and consumed in a continuous manner from a source, with little or no intermediate storage in network elements.

**Please visit [Media streaming - Audio Streaming](#media-streaming---audio-streaming), [Media streaming - Multimedia Streaming](#media-streaming---multimedia-streaming), [Media streaming - Video Streaming](#media-streaming---video-streaming), [Media Management](#media-management)**

_See also: 🌎 [List of streaming media systems - Wikipedia](en.wikipedia.org/wiki/List_of_streaming_media_systems), 🌎 [Comparison of streaming media systems - Wikipedia](en.wikipedia.org/wiki/Comparison_of_streaming_media_systems)_



### Media Streaming - Audio Streaming

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Audio](en.wikipedia.org/wiki/Audio) streaming tools and software.

_Related: [Media Management](#media-management)_

- 🌎 [Ampache](ampache.org/) - Web based audio/video streaming application.  🌎 [Demo](play.dogmazic.net/), <b><code>&nbsp;&nbsp;3635⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;593🍴</code></b> [Source Code](https://github.com/ampache/ampache))) `AGPL-3.0` `PHP`
- 🌎 [Audiobookshelf](www.audiobookshelf.org/) - Audiobook and podcast server. It streams all audio formats, keeps and syncs progress across devices. Comes with open-source apps for Android and iOS. (<b><code>&nbsp;&nbsp;8332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;561🍴</code></b> [Source Code](https://github.com/advplyr/audiobookshelf)), <b><code>&nbsp;&nbsp;1634⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;213🍴</code></b> [Clients](https://github.com/advplyr/audiobookshelf-app))) `GPL-3.0` `Docker/deb/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;761⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Audioserve](https://github.com/izderadicka/audioserve)) - Simple personal server to serve audio files from directories (audiobooks, music, podcasts...). Focused on simplicity and supports sync of play position between clients. `MIT` `Rust`
- 🌎 [AzuraCast](www.azuracast.com/) - Modern and accessible web radio management suite. (<b><code>&nbsp;&nbsp;3345⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;599🍴</code></b> [Source Code](https://github.com/AzuraCast/AzuraCast))) `Apache-2.0` `Docker`
- 🌎 [Beets](beets.io/) - Music library manager and MusicBrainz tagger (command-line and Web interface). (<b><code>&nbsp;13395⭐</code></b> <b><code>&nbsp;&nbsp;1865🍴</code></b> [Source Code](https://github.com/beetbox/beets))) `MIT` `Python/deb`
- <b><code>&nbsp;&nbsp;3513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [Black Candy](https://github.com/blackcandy-org/black_candy)) - Music streaming server. `MIT` `Docker/Ruby`
- 🌎 [Funkwhale](dev.funkwhale.audio/funkwhale) - Modern, web-based, convivial, multi-user and free music server. `BSD-3-Clause` `Python/Django`
- <b><code>&nbsp;&nbsp;1849⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [gonic](https://github.com/sentriz/gonic)) - Lightweight music streaming server. Subsonic compatible. `GPL-3.0` `Go/Docker`
- 🌎 [HoloPlay](app.holoplay.io) `⚠` - Web app using Invidious API for listening to Youtube audio sources. (<b><code>&nbsp;&nbsp;&nbsp;109⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Source Code](https://github.com/stephane-r/holoplay-pwa))) `MIT` `Nodejs/Docker`
- 🌎 [koel](koel.dev/) - Personal music streaming server that works.  🌎 [Demo](demo.koel.dev/), <b><code>&nbsp;16348⭐</code></b> <b><code>&nbsp;&nbsp;2010🍴</code></b> [Source Code](https://github.com/koel/koel))) `MIT` `PHP`
- 🌎 [LibreTime](libretime.org) - Simple, open source platform that lets you broadcast streaming radio on the web (fork of <b><code>&nbsp;&nbsp;&nbsp;620⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;267🍴</code></b> [Airtime](https://github.com/sourcefabric/Airtime))). (<b><code>&nbsp;&nbsp;&nbsp;851⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;232🍴</code></b> [Source Code](https://github.com/LibreTime/libretime))) `AGPL-3.0` `Docker/PHP`
- <b><code>&nbsp;&nbsp;1285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [LMS](https://github.com/epoupon/lms)) - Access your self-hosted music using a web interface. `GPL-3.0` `Docker/deb/C++`
- <b><code>&nbsp;&nbsp;1306⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Maloja](https://github.com/krateng/maloja)) - Self-hosted music scrobble database (alternative to Last.fm).  🌎 [Demo](maloja.krateng.ch/)) `GPL-3.0` `Python/Docker`
- 🌎 [moOde Audio](moodeaudio.org/) - Audiophile-quality music playback for the wonderful Raspberry Pi family of single board computers. (<b><code>&nbsp;&nbsp;1091⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [Source Code](https://github.com/moode-player/moode))) `GPL-3.0` `PHP`
- 🌎 [Mopidy](docs.mopidy.com/) `⚠` - Extensible music server. Offers a superset of the mpd API, as well as integration with 3rd party services like Spotify, SoundCloud etc. (<b><code>&nbsp;&nbsp;8243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;696🍴</code></b> [Source Code](https://github.com/mopidy/mopidy))) `Apache-2.0` `Python/deb`
- 🌎 [mpd](www.musicpd.org/) - Daemon to remotely play music, stream music, handle and organize playlists. Many clients available. (<b><code>&nbsp;&nbsp;2319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;372🍴</code></b> [Source Code](https://github.com/MusicPlayerDaemon/MPD)), 🌎 [Clients](www.musicpd.org/clients/)) `GPL-2.0` `C++`
- 🌎 [mStream](mstream.io/) - Music streaming server with GUI management tools. Runs on Mac, Windows, and Linux. (<b><code>&nbsp;&nbsp;2256⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;191🍴</code></b> [Source Code](https://github.com/IrosTheBeggar/mStream))) `GPL-2.0` `Nodejs`
- 🌎 [multi-scrobbler](foxxmd.github.io/multi-scrobbler) - Scrobble plays from multiple sources to multiple scrobbling services. (<b><code>&nbsp;&nbsp;&nbsp;541⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Source Code](https://github.com/FoxxMD/multi-scrobbler))) `MIT` `Nodejs/Docker`
- 🌎 [musikcube](musikcube.com/) - Streaming audio server with Linux/macOS/Windows/Android clients. (<b><code>&nbsp;&nbsp;4391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;300🍴</code></b> [Source Code](https://github.com/clangen/musikcube))) `BSD-3-Clause` `C++/deb`
- 🌎 [Navidrome Music Server](www.navidrome.org) - Modern Music Server and Streamer, compatible with Subsonic/Airsonic.  🌎 [Demo](www.navidrome.org/demo), <b><code>&nbsp;13975⭐</code></b> <b><code>&nbsp;&nbsp;1023🍴</code></b> [Source Code](https://github.com/navidrome/navidrome)), 🌎 [Clients](www.navidrome.org/docs/overview/#apps)) `GPL-3.0` `Docker/Go`
- 🌎 [Pinepods](www.pinepods.online/) - A rust based podcast management system with multi-user support. Pinepods utilizes a central database so aspects like listen time and themes follow from device to device.  🌎 [Demo](try.pinepods.online), <b><code>&nbsp;&nbsp;&nbsp;382⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Source Code](https://github.com/madeofpendletonwool/PinePods))) `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;2190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [Polaris](https://github.com/agersant/polaris)) - Music browsing and streaming application optimized for large music collections, ease of use and high performance. `MIT` `Rust/Docker`
- <b><code>&nbsp;&nbsp;6561⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;468🍴</code></b> [Snapcast](https://github.com/badaix/snapcast)) - Synchronous multiroom audio server. `GPL-3.0` `C++/deb`
- <b><code>&nbsp;&nbsp;&nbsp;622⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [Stretto](https://github.com/benkaiser/stretto)) `⚠` - Music player with Youtube/Soundcloud import and iTunes/Spotify discovery.  🌎 [Demo](next.kaiserapps.com), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Clients](https://github.com/benkaiser/stretto-mobile-next))) `MIT` `Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;274⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [Supysonic](https://github.com/spl0k/supysonic)) - Python implementation of the Subsonic server API. `AGPL-3.0` `Python/deb`
- 🌎 [SwingMusic](swingmusic.vercel.app/) - Swing Music is a beautiful, self-hosted music player and streaming server for your local audio files. Like a cooler Spotify ... but bring your own music. (<b><code>&nbsp;&nbsp;&nbsp;994⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Source Code](https://github.com/swing-opensource/swingmusic))) `MIT` `Python/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [vod2pod-rss](https://github.com/madiele/vod2pod-rss)) `⚠` - Convert YouTube and Twitch channels to podcasts, no storage required. Transcodes VoDs to MP3 192k on the fly, generates an RSS feed to use in podcast clients. `MIT` `Docker`


### Media Streaming - Multimedia Streaming

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Multimedia](en.wikipedia.org/wiki/Multimedia) streaming tools and software.

_Related: [Media Streaming - Video Streaming](#media-streaming---video-streaming), [Media Streaming - Audio Streaming](#media-streaming---audio-streaming), [Media Management](#media-management)_

- 🌎 [ClipBucket](clipbucket.fr/) - Start your own video sharing website (YouTube/Netflix Clone) in a matter of minutes.  🌎 [Demo](demo.clipbucket.oxygenz.fr/), <b><code>&nbsp;&nbsp;&nbsp;112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [Source Code](https://github.com/MacWarrior/clipbucket-v5))) `AAL` `Docker/PHP`
- 🌎 [Gerbera](gerbera.io/) - Gerbera is an UPnP Media Server. It allows you to stream your digital media throughout your home network and listen to/watch it on a variety of UPnP compatible devices. (<b><code>&nbsp;&nbsp;1245⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;216🍴</code></b> [Source Code](https://github.com/gerbera/gerbera))) `GPL-2.0` `Docker/deb/C++`
- 🌎 [Icecast 2](icecast.org) - Streaming audio/video server which can be used to create an Internet radio station or a privately running jukebox and many things in between.  🌎 [Source Code](gitlab.xiph.org/xiph/icecast-server), 🌎 [Clients](icecast.org/apps/)) `GPL-2.0` `C`
- 🌎 [Jellyfin](jellyfin.org) - Media server for audio, video, books, comics, and photos with a sleek interface and robust transcoding capabilities. Almost all modern platforms have clients, including Roku, Android TV, iOS, and Kodi.  🌎 [Demo](demo.jellyfin.org/stable), <b><code>&nbsp;38723⭐</code></b> <b><code>&nbsp;&nbsp;3445🍴</code></b> [Source Code](https://github.com/jellyfin/jellyfin)), <b><code>&nbsp;&nbsp;3037⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [Clients](https://github.com/awesome-jellyfin/awesome-jellyfin))) `GPL-2.0` `C#/deb/Docker`
- 🌎 [Karaoke Eternal](www.karaoke-eternal.com) - Host awesome karaoke parties where everyone can easily find and queue songs from their phone's browser. The player is also fully browser-based with support for MP3+G, MP4 and WebGL visualizations.  🌎 [Source Code](www.karaoke-eternal.com/repo)) `ISC` `Docker/Nodejs`
- 🌎 [Kodi](kodi.tv/) - Multimedia/Entertainment center, formerly known as XBMC. Runs on Android, BSD, Linux, macOS, iOS and Windows. (<b><code>&nbsp;19181⭐</code></b> <b><code>&nbsp;&nbsp;6362🍴</code></b> [Source Code](https://github.com/xbmc/xbmc))) `GPL-2.0` `C++/deb`
- <b><code>&nbsp;&nbsp;2021⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Kyoo](https://github.com/zoriya/kyoo)) - Innovative media browser designed for seamless streaming of anime, series and movies, offering advanced features like dynamic transcoding, auto watch history and intelligent metadata retrieval.  🌎 [Demo](kyoo.zoriya.dev)) `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;706⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Meelo](https://github.com/Arthi-chaud/Meelo)) - Personal Music Server, designed for collectors and music maniacs. `GPL-3.0` `Docker`
- 🌎 [MistServer](mistserver.org/) - Public domain streaming media server that works with any device and any format. (<b><code>&nbsp;&nbsp;&nbsp;414⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [Source Code](https://github.com/DDVTECH/mistserver))) `Unlicense` `C++`
- [NymphCast](http://nyanko.ws/nymphcast.php) - Turn your choice of Linux-capable hardware into an audio and video source for a television or powered speakers (alternative to Chromecast). (<b><code>&nbsp;&nbsp;2470⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [Source Code](https://github.com/MayaPosch/NymphCast))) `BSD-3-Clause` `C++`
- 🌎 [ReadyMedia](sourceforge.net/projects/minidlna/) - Simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients. Formerly known as MiniDLNA.  🌎 [Source Code](sourceforge.net/p/minidlna/git/ci/master/tree/)) `GPL-2.0` `C`
- 🌎 [Rygel](gnome.pages.gitlab.gnome.org/rygel/) - Rygel is a UPnP AV MediaServer that allows you to easily share audio, video, and pictures. Media player software may use Rygel to become a MediaRenderer that may be controlled remotely by a UPnP or DLNA Controller.  🌎 [Source Code](gitlab.gnome.org/GNOME/rygel/)) `GPL-3.0` `C`
- 🌎 [Stash](stashapp.cc) - A web-based library organizer and player for your adult media stash, with auto-tagging and metadata scraping support. (<b><code>&nbsp;10225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;852🍴</code></b> [Source Code](https://github.com/stashapp/stash))) `AGPL-3.0` `Docker/Go`
- <b><code>&nbsp;&nbsp;1814⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;253🍴</code></b> [µStreamer](https://github.com/pikvm/ustreamer)) - Lightweight and very quick server to stream MJPEG video from any V4L2 device to the net. `GPL-3.0` `C/deb`
- 🌎 [üWave](u-wave.net/) `⚠` - Self-hosted collaborative listening platform. Users take turns playing media—songs, talks, gameplay videos, or anything else—from a variety of media sources like YouTube and SoundCloud.  🌎 [Demo](wlk.yt/), [Source Code](https://github.com/u-wave)) `MIT` `Nodejs`


### Media Streaming - Video Streaming

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Video](en.wikipedia.org/wiki/Video) streaming tools and software.

_Related: [Video Surveillance](#video-surveillance), [Media Streaming - Multimedia Streaming](#media-streaming---multimedia-streaming), [Photo Galleries](#photo-galleries), [Media Management](#media-management)_

- <b><code>&nbsp;&nbsp;1513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;235🍴</code></b> [CyTube](https://github.com/calzoneman/sync)) - CyTube is a web application providing media synchronization, chat, and more for an arbitrary number of channels.  🌎 [Demo](cytu.be)) `MIT` `Nodejs`
- <b><code>&nbsp;17107⭐</code></b> <b><code>&nbsp;&nbsp;1930🍴</code></b> [Invidious](https://github.com/iv-org/invidious)) `⚠` - Alternative YouTube front-end.  🌎 [Demo](docs.invidious.io/instances/)) `AGPL-3.0` `Docker/Crystal`
- 🌎 [MediaCMS](mediacms.io) - MediaCMS is a modern, fully featured open source video and media CMS, written in Python/Django/React, featuring a REST API. (<b><code>&nbsp;&nbsp;3318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;606🍴</code></b> [Source Code](https://github.com/mediacms-io/mediacms))) `AGPL-3.0` `Python/Docker`
- <b><code>&nbsp;&nbsp;2720⭐</code></b> <b><code>&nbsp;&nbsp;1070🍴</code></b> [OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)) - OvenMediaEngine is a selfhostable Open-Source Streaming Server with Sub-Second Latency.  🌎 [Demo](demo.ovenplayer.com)) `GPL-3.0` `C++/Docker`
- 🌎 [Owncast](owncast.online/) - Decentralized single-user live video streaming and chat server for running your own live streams similar in style to the large mainstream options. (<b><code>&nbsp;10029⭐</code></b> <b><code>&nbsp;&nbsp;1007🍴</code></b> [Source Code](https://github.com/owncast/owncast))) `MIT` `Go`
- 🌎 [PeerTube](joinpeertube.org/en/) - Decentralized video streaming platform using P2P (BitTorrent) directly in the web browser. (<b><code>&nbsp;13625⭐</code></b> <b><code>&nbsp;&nbsp;1573🍴</code></b> [Source Code](https://github.com/Chocobozzz/PeerTube))) `AGPL-3.0` `Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Rapidbay](https://github.com/hauxir/rapidbay/)) - Self-hosted torrent videostreaming service/torrent client that allows searching and playing videos from torrents in the browser or from a Chromecast/AppleTV/Smart TV. `MIT` `Python/Docker`
- 🌎 [Restreamer](datarhei.github.io/restreamer/) - Restreamer allows you to do h.264 real-time video streaming on your website without a streaming provider. (<b><code>&nbsp;&nbsp;4334⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;465🍴</code></b> [Source Code](https://github.com/datarhei/restreamer))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [SRS](ossrs.io/) - A simple, high efficiency and real-time video server, supports RTMP, WebRTC, HLS, HTTP-FLV and SRT. (<b><code>&nbsp;26753⭐</code></b> <b><code>&nbsp;&nbsp;5478🍴</code></b> [Source Code](https://github.com/ossrs/srs))) `MIT` `Docker/C++`
- <b><code>&nbsp;&nbsp;&nbsp;298⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [SyncTube](https://github.com/RblSb/SyncTube)) - Lightweight and very simple to setup CyTube alternative to watch videos with friends and chat. `MIT` `Nodejs/Haxe`
- 🌎 [Tube Archivist](tubearchivist.com/) `⚠` - Organize, search, and enjoy your YouTube collection. Subscribe, download, and track viewed content with metadata indexing and a user-friendly interface. (<b><code>&nbsp;&nbsp;5912⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [Source Code](https://github.com/tubearchivist/tubearchivist)), 🌎 [Clients](docs.tubearchivist.com/faq/#how-do-i-import-my-videos-to-emby-plex-jellyfin-kodi)) `GPL-3.0` `Docker`
- 🌎 [Tube](git.mills.io/prologic/tube) - Youtube-like (_without censorship and features you don't need!_) video sharing app written in Go which also supports automatic transcoding to MP4 H.265 AAC, multiple collections and RSS feed.  🌎 [Demo](tube.mills.io)) `MIT` `Go`
- 🌎 [VideoLAN Client (VLC)](www.videolan.org/) - Cross-platform multimedia player client and server supporting most multimedia files as well as DVDs, Audio CDs, VCDs, and various streaming protocols.  🌎 [Source Code](code.videolan.org/videolan/vlc)) `GPL-2.0` `C/deb`


### Miscellaneous

**[`^        back to top        ^`](#awesome-selfhosted)**

Software that does not fit in another section.

- <b><code>&nbsp;&nbsp;2682⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [2FAuth](https://github.com/Bubka/2FAuth)) - Manage your Two-Factor Authentication (2FA) accounts and generate their security codes.  🌎 [Demo](demo.2fauth.app/)) `AGPL-3.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [AlertHub](https://github.com/Ardakilic/alerthub)) `⚠` - Get alerts from GitHub releases. `MIT` `Nodejs/Docker`
- 🌎 [Anchr](anchr.io) - Toolbox for tiny tasks on the internet, including bookmark collections, URL shortening and (encrypted) image uploads. (<b><code>&nbsp;&nbsp;&nbsp;300⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Source Code](https://github.com/muety/anchr))) `GPL-3.0` `Nodejs`
- 🌎 [asciinema](asciinema.org/) - Web app for hosting asciicasts.  🌎 [Demo](asciinema.org/explore), <b><code>&nbsp;&nbsp;2359⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;269🍴</code></b> [Source Code](https://github.com/asciinema/asciinema-server))) `Apache-2.0` `Elixir/Docker`
- <b><code>&nbsp;&nbsp;2310⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [Baby Buddy](https://github.com/babybuddy/babybuddy)) - Helps caregivers track baby sleep, feedings, diaper changes, and tummy time. (<b><code>&nbsp;&nbsp;2310⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [Demo](https://github.com/babybuddy/babybuddy#-demo))) `BSD-2-Clause` `Python`
- 🌎 [beelzebub](beelzebub-honeypot.com/) `⚠` - Honeypot framework designed to provide a highly secure environment for detecting and analyzing cyber attacks. (<b><code>&nbsp;&nbsp;1009⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Source Code](https://github.com/mariocandela/beelzebub))) `MIT` `Docker/K8S/Go`
- <b><code>&nbsp;&nbsp;&nbsp;787⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [ClipCascade](https://github.com/Sathvik-Rao/ClipCascade)) - Syncs your clipboard across multiple devices instantly, without any button press. Available on Windows, macOS, Linux, and Android, it provides seamless and secure clipboard sharing with end-to-end data encryption. `GPL-3.0` `Java/Docker`
- 🌎 [Cloudlog](magicbug.co.uk/cloudlog/) - Cloudlog is a self-hosted PHP application that allows you to log your amateur radio contacts anywhere. (<b><code>&nbsp;&nbsp;&nbsp;493⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [Source Code](https://github.com/magicbug/cloudlog))) `MIT` `PHP/Docker`
- <b><code>&nbsp;&nbsp;1353⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [ConvertX](https://github.com/C4illin/ConvertX)) - Online file converter which supports over a thousand different formats. `AGPL-3.0` `Docker`
- 🌎 [CUPS](www.cups.org/) - The Common Unix Print System uses Internet Printing Protocol (IPP) to support printing to local and network printers. (<b><code>&nbsp;&nbsp;1234⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;236🍴</code></b> [Source Code](https://github.com/OpenPrinting/cups))) `GPL-2.0` `C`
- <b><code>&nbsp;30898⭐</code></b> <b><code>&nbsp;&nbsp;3455🍴</code></b> [CyberChef](https://github.com/gchq/CyberChef)) - Perform all manner of operations within a web browser such as AES, DES and Blowfish encryption and decryption, creating hexdumps, calculating hashes, and much more.  🌎 [Demo](gchq.github.io/CyberChef)) `Apache-2.0` `Javascript`
- 🌎 [Digiboard](digiboard.app/) - Create collaborative whiteboards (documentation in French).  🌎 [Source Code](codeberg.org/ladigitale/digiboard)) `AGPL-3.0` `Nodejs`
- 🌎 [Digicard](codeberg.org/ladigitale/digicard) - Create simple graphic compositions (documentation in French).  🌎 [Demo](ladigitale.dev/digicard/)) `AGPL-3.0` `Nodejs`
- 🌎 [Digicut](ladigitale.dev/digicut/) - Cut audio and video files using FFMPEG.wasm (documentation in French).  🌎 [Source Code](codeberg.org/ladigitale/digicut)) `AGPL-3.0` `Nodejs`
- 🌎 [Digiface](ladigitale.dev/digiface/) - Create avatars using the Avataaars library (documentation in French).  🌎 [Demo](ladigitale.dev/digiface/), 🌎 [Source Code](codeberg.org/ladigitale/digiface)) `AGPL-3.0` `Nodejs`
- 🌎 [Digiflashcards](ladigitale.dev/digiflashcards/) - An online application to create flashcards (documentation in French).  🌎 [Source Code](codeberg.org/ladigitale/digiflashcards)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [Digimerge](ladigitale.dev/digimerge/) - Assemble audio and video files directly in your browser (documentation in French).  🌎 [Demo](ladigitale.dev/digimerge/), 🌎 [Source Code](codeberg.org/ladigitale/Digimerge)) `AGPL-3.0` `Nodejs`
- 🌎 [Digiquiz](ladigitale.dev/digiquiz/) - An online application to publish content created with H5P (documentation in French).  🌎 [Source Code](codeberg.org/ladigitale/digiquiz)) `AGPL-3.0` `Nodejs`
- 🌎 [Digiread](ladigitale.dev/digiread/) `⚠` - Clean up online pages and articles using Mozilla's Readability (documentation in French).  🌎 [Source Code](codeberg.org/ladigitale/digiread)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [Digisteps](ladigitale.dev/digisteps/) - A simple application for creating online educational paths (documentation in French).  🌎 [Source Code](codeberg.org/ladigitale/digisteps)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [Digitranscode](ladigitale.dev/digitranscode) - Convert audio files and videos directly in the browser (documentation in French).  🌎 [Demo](ladigitale.dev/digitranscode), 🌎 [Source Code](codeberg.org/ladigitale/digitranscode)) `AGPL-3.0` `Nodejs`
- 🌎 [Digiview](ladigitale.dev/digiview/) `⚠` - View YouTube videos in a distraction-free interface (documentation in French).  🌎 [Demo](ladigitale.dev/digiview/), 🌎 [Source Code](codeberg.org/ladigitale/digiview)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [Digiwords](ladigitale.dev/digiwords/) - A simple online application for creating word clouds (documentation in French).  🌎 [Source Code](codeberg.org/ladigitale/digiwords)) `AGPL-3.0` `Nodejs/PHP`
- <b><code>&nbsp;&nbsp;&nbsp;840⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [DOCAT](https://github.com/docat-org/docat)) - Host your docs. Simple. Versioned. Fancy. `MIT` `Python/Docker`
- 🌎 [DOMJudge](www.domjudge.org/) - A system for running a programming contest, like the ICPC regional and world championship programming contests.  🌎 [Demo](www.domjudge.org/demo), <b><code>&nbsp;&nbsp;&nbsp;786⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [Source Code](https://github.com/DOMjudge/domjudge))) `GPL-2.0/BSD-3-Clause/MIT` `PHP`
- 🌎 [Endurain](docs.endurain.com/) - Fitness tracking service designed to give users full control over their data and hosting environment. (<b><code>&nbsp;&nbsp;&nbsp;884⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Source Code](https://github.com/joaovitoriasilva/endurain))) `AGPL-3.0` `Docker`
- 🌎 [ESMira](esmira.kl.ac.at) - Run longitudinal studies (ESM, AA, EMA) with data collection and communication with participants being completely anonymous.  🌎 [Demo](demo-esmira.kl.ac.at/#admin,username:demo,password:demodemodemo), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/KL-Psychological-Methodology/ESMira))) `AGPL-3.0` `PHP`
- 🌎 [F-Droid](f-droid.org) - Server tools for maintaining an F-Droid repository system.  🌎 [Source Code](gitlab.com/fdroid/fdroidserver)) `AGPL-3.0` `Python/Docker/deb`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Fasten Health](https://github.com/fastenhealth/fasten-onprem/)) `⚠` - Fasten is an open-source, self-hosted, personal/family electronic medical record aggregator, designed to integrate with 100,000's of insurances/hospitals/clinics in the United States. `GPL-3.0` `Go/Docker`
- 🌎 [Flyimg](flyimg.io) - Resize and crop images on the fly. Get optimised images with MozJPEG, WebP or PNG using ImageMagick, with an efficient caching system.  🌎 [Demo](demo.flyimg.io), <b><code>&nbsp;&nbsp;1105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [Source Code](https://github.com/flyimg/flyimg))) `MIT` `Docker`
- 🌎 [Geeftlist](codeberg.org/nanawel/geeftlist) - Collaborative platform for managing, sharing and reserving gifts between friends and family. `GPL-3.0` `Docker`
- <b><code>&nbsp;12409⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;437🍴</code></b> [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper)) `⚠` - Hassle-Free Way to Self-Host Google Fonts. Get eot, ttf, svg, woff and woff2 files + CSS snippets.  🌎 [Demo](gwfh.mranftl.com/fonts)) `MIT` `Nodejs`
- 🌎 [Gophish](getgophish.com/) - Gophish is a powerful, open-source phishing framework that makes it easy to test your organization's exposure to phishing. (<b><code>&nbsp;12456⭐</code></b> <b><code>&nbsp;&nbsp;2522🍴</code></b> [Source Code](https://github.com/gophish/gophish))) `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [graph-vl](https://github.com/verifid/graph-vl)) - Identity document verification using Machine Learning and GraphQL. `MIT` `Python/Docker/K8S`
- 🌎 [Habitica](habitica.com/) - Habit tracker app which treats your goals like a Role Playing Game. Previously called HabitRPG. (<b><code>&nbsp;12736⭐</code></b> <b><code>&nbsp;&nbsp;4202🍴</code></b> [Source Code](https://github.com/HabitRPG/habitica))) `GPL-3.0/CC-BY-SA-3.0` `Nodejs/Docker`
- 🌎 [HortusFox](hortusfox.github.io) - A collaborative plant management system. (<b><code>&nbsp;&nbsp;&nbsp;862⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Source Code](https://github.com/danielbrendel/hortusfox-web))) `MIT` `PHP/Docker`
- <b><code>&nbsp;&nbsp;2853⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [iSponsorBlockTV](https://github.com/dmunozv04/iSponsorBlockTV)) `⚠` - SponsorBlock for YouTube TV, allows skipping sponsors, muting and skipping ads. `GPL-3.0` `Docker/Python`
- 🌎 [Jelu](bayang.github.io/jelu-web) - Self hosted read and to-read list book tracker. (<b><code>&nbsp;&nbsp;&nbsp;457⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Source Code](https://github.com/bayang/jelu))) `MIT` `Java/Docker`
- 🌎 [Kasm Workspaces](kasmweb.com/) - Streaming containerized apps and desktops to end-users. Examples include Ubuntu in your browser, or simply single apps such as Chrome, OpenOffice, Gimp, Filezilla etc.  🌎 [Demo](www.kasmweb.com/#demo), [Source Code](https://github.com/kasmtech)) `GPL-3.0` `Docker`
- 🌎 [Koillection](koillection.github.io/) - Koillection is a service allowing users to manage any kind of collections. (<b><code>&nbsp;&nbsp;&nbsp;813⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Source Code](https://github.com/benjaminjonard/koillection))) `MIT` `Docker/PHP`
- <b><code>&nbsp;20919⭐</code></b> <b><code>&nbsp;&nbsp;2131🍴</code></b> [Lama-Cleaner](https://github.com/Sanster/lama-cleaner)) `⚠` - A free and open-source inpainting tool powered by SOTA AI model. `Apache-2.0` `Python/Docker`
- 🌎 [LanguageTool](languagetool.org/) - Proofread more than 20 languages. It finds many errors that a simple spell checker cannot detect. (<b><code>&nbsp;12985⭐</code></b> <b><code>&nbsp;&nbsp;1428🍴</code></b> [Source Code](https://github.com/languagetool-org/languagetool)), 🌎 [Clients](languagetool.org/insights/post/product-windows-app/)) `LGPL-2.1` `Java/Docker`
- 🌎 [Libre Translate](libretranslate.com/) - Free and Open Source Machine Translation API, entirely self-hosted. (<b><code>&nbsp;11143⭐</code></b> <b><code>&nbsp;&nbsp;1062🍴</code></b> [Source Code](https://github.com/LibreTranslate/LibreTranslate))) `AGPL-3.0` `Docker/Python`
- 🌎 [LubeLogger](lubelogger.com) - A web-based vehicle maintenance and fuel mileage tracker. (<b><code>&nbsp;&nbsp;1517⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [Demo](https://github.com/hargata/lubelog?tab=readme-ov-file#demo)), <b><code>&nbsp;&nbsp;1517⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [Source Code](https://github.com/hargata/lubelog))) `MIT` `Docker/K8S/C#`
- 🌎 [Mere Medical](meremedical.co/) `⚠` - With Mere Medical, you can finally manage all of your medical records from Epic MyChart, Cerner, and OnPatient patient portals in one place. Privacy-focused, self-hosted, and offline-first.  🌎 [Demo](demo.meremedical.co), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/cfu288/mere-medical))) `GPL-3.0` `Docker/Nodejs`
- 🌎 [mosparo](mosparo.io/) - The modern spam protection tool. It replaces other captcha methods with a simple and easy to use spam protection solution. (<b><code>&nbsp;&nbsp;&nbsp;215⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Source Code](https://github.com/mosparo/mosparo))) `MIT` `PHP`
- 🌎 [MyIP](ipcheck.ing) `⚠` - All in one IP Toolbox. Easy to check what's your IPs, IP geolocation, check for DNS leaks, examine WebRTC connections, speed test, ping test, MTR test, check website availability and more.  🌎 [Demo](ipcheck.ing), <b><code>&nbsp;&nbsp;8090⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;899🍴</code></b> [Source Code](https://github.com/jason5ng32/MyIP))) `MIT` `Nodejs/Docker`
- 🌎 [Neko](neko.m1k1o.net) - A self hosted virtual browser (rabb.it clone) that runs in Docker. (<b><code>&nbsp;10030⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;692🍴</code></b> [Source Code](https://github.com/m1k1o/neko))) `Apache-2.0` `Docker/Go`
- 🌎 [Open-Meteo](open-meteo.com/) - Open-source weather API with open-data forecasts, historical and climate data from all major national weather services.  🌎 [Demo](open-meteo.com/en/docs), <b><code>&nbsp;&nbsp;3081⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [Source Code](https://github.com/open-meteo/open-meteo))) `AGPL-3.0` `Docker`
- 🌎 [OpenZiti](openziti.github.io/) - Fully-featured, self-hostable, zero trust, full mesh overlay network. Includes a 2FA support out of the box, clients for all major desktop/mobile OS'es. (<b><code>&nbsp;&nbsp;3233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;181🍴</code></b> [Source Code](https://github.com/openziti/ziti))) `Apache-2.0` `Go`
- 🌎 [penpot](penpot.app/) - A web based design and prototyping platform meant for cross-domain teams. (<b><code>&nbsp;37409⭐</code></b> <b><code>&nbsp;&nbsp;1926🍴</code></b> [Source Code](https://github.com/penpot/penpot))) `MPL-2.0` `Docker`
- 🌎 [POMjs](password.oppetmoln.se/) - Random Password Generator. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Source Code](https://github.com/joho1968/POMjs))) `GPL-2.0` `Javascript`
- 🌎 [Reactive Resume](rxresu.me/) - A one-of-a-kind resume builder that keeps your privacy in mind. Completely secure, customizable, portable, open-source and free forever.  🌎 [Demo](rxresu.me/app/dashboard/), <b><code>&nbsp;30411⭐</code></b> <b><code>&nbsp;&nbsp;3131🍴</code></b> [Source Code](https://github.com/AmruthPillai/Reactive-Resume))) `MIT` `Docker/Nodejs`
- 🌎 [ReleaseBell](releasebell.com/) - Send release notifications for starred Github repos.  🌎 [Source Code](git.cloudron.io/cloudron/releasebell)) `MIT` `Nodejs`
- 🌎 [revealjs](revealjs.com) - Framework for easily creating beautiful presentations using HTML.  🌎 [Demo](revealjs.com/), <b><code>&nbsp;68691⭐</code></b> <b><code>&nbsp;16702🍴</code></b> [Source Code](https://github.com/hakimel/reveal.js))) `MIT` `Javascript`
- 🌎 [Revive Adserver](www.revive-adserver.com/) - World's most popular free, open source ad serving system. Formerly known as OpenX Adserver and phpAdsNew. (<b><code>&nbsp;&nbsp;1313⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;567🍴</code></b> [Source Code](https://github.com/revive-adserver/revive-adserver))) `GPL-2.0` `PHP`
- [SANE Network Scanning](http://sane-project.org/) - Allow remote clients to access image acquisition devices (scanners) available on the local host. ([Source Code](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- 🌎 [Speed Test by OpenSpeedTest™](openspeedtest.com/) - Free & Open-Source HTML5 Network Performance Estimation Tool. (<b><code>&nbsp;&nbsp;2640⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;252🍴</code></b> [Source Code](https://github.com/openspeedtest/Speed-Test))) `MIT` `Docker`
- 🌎 [Speedtest Tracker](docs.speedtest-tracker.dev/) - Monitor the performance and uptime of your internet connection. (<b><code>&nbsp;&nbsp;3516⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [Source Code](https://github.com/alexjustesen/speedtest-tracker))) `MIT` `Docker/K8S`
- 🌎 [string.is](string.is/) - An open-source, privacy-friendly online string toolkit for developers. (<b><code>&nbsp;&nbsp;&nbsp;268⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Source Code](https://github.com/recurser/string-is))) `AGPL-3.0` `Nodejs`
- 🌎 [Teleport](goteleport.com/) - Certificate authority and access plane for SSH, Kubernetes, web applications, and databases. (<b><code>&nbsp;18292⭐</code></b> <b><code>&nbsp;&nbsp;1818🍴</code></b> [Source Code](https://github.com/gravitational/teleport))) `Apache-2.0` `Go/Docker/K8S`
- <b><code>&nbsp;&nbsp;6578⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;790🍴</code></b> [TeslaMate](https://github.com/adriankumpf/teslamate)) - A powerful data logger for Tesla vehicles. `MIT` `Elixir/Docker`
- <b><code>&nbsp;&nbsp;3112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Upsnap](https://github.com/seriousm4x/UpSnap)) - A simple Wake on LAN (WOL) dashboard app. Wake up devices on your network and see current status. `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [URL-to-PNG](https://github.com/jasonraimondi/url-to-png)) - URL to PNG utility featuring parallel rendering using Playwright for screenshots and with storage caching via Local, S3, or CouchDB. `MIT` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Wakupator](https://github.com/Gibus21250/Wakupator)) - Wake On LAN Machine Manager based on network traffic. `MIT` `C`
- 🌎 [Wavelog](www.wavelog.org) - Webbased Logging Software for Radio Amateurs. Enhanced QSO logging, statistics and maps for your browser.  🌎 [Demo](demo.wavelog.org), <b><code>&nbsp;&nbsp;&nbsp;242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Source Code](https://github.com/wavelog/wavelog))) `MIT` `PHP/Docker`
- 🌎 [WeeWX](weewx.com/) - Open source software for your weather station.  🌎 [Demo](weewx.com/showcase.html), <b><code>&nbsp;&nbsp;1055⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;308🍴</code></b> [Source Code](https://github.com/weewx/weewx))) `GPL-3.0` `Python/deb`
- 🌎 [WeTTY](butlerx.github.io/wetty/#/) - Terminal in browser over http/https. (<b><code>&nbsp;&nbsp;4529⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;692🍴</code></b> [Source Code](https://github.com/butlerx/wetty))) `MIT` `Docker/Nodejs`
- 🌎 [wger](wger.de/) - Web-based personal workout, fitness and weight logger/tracker. It can also be used as a simple gym management utility and offers a full REST API as well.  🌎 [Demo](wger.de/en/dashboard), <b><code>&nbsp;&nbsp;4533⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;673🍴</code></b> [Source Code](https://github.com/wger-project/wger))) `AGPL-3.0` `Python/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Yamtrack](https://github.com/FuzzyGrim/Yamtrack)) `⚠` - Media tracker for movies, tv shows, anime, manga, video games and books. (<b><code>&nbsp;&nbsp;&nbsp;332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Demo](https://github.com/FuzzyGrim/Yamtrack?tab=readme-ov-file#demo))) `AGPL-3.0` `Docker/Python`


### Money, Budgeting & Management

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Money management](en.wikipedia.org/wiki/Money_management) and budgeting software.

_Related: [Inventory Management](#inventory-management), [Resource Planning](#resource-planning)_

- 🌎 [Actual](actualbudget.github.io/docs/) - Local-first personal finance tool based on zero-sum budgeting, supporting synchronization across devices, custom rules, manual transaction importing (from QIF, OFX, and QFX files), and optional automatic synchronization with many banks. (<b><code>&nbsp;18338⭐</code></b> <b><code>&nbsp;&nbsp;1438🍴</code></b> [Source Code](https://github.com/actualbudget/actual))) `MIT` `Nodejs/Docker`
- 🌎 [Bigcapital](bigcapital.app/) - Financial accounting and inventory management software for small to medium businesses. (<b><code>&nbsp;&nbsp;2787⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;274🍴</code></b> [Source Code](https://github.com/bigcapitalhq/bigcapital))) `AGPL-3.0` `Docker`
- 🌎 [Bitcart](bitcart.ai) - Cryptocurrencies payment processor and development platform.  🌎 [Demo](admin.bitcart.ai), <b><code>&nbsp;&nbsp;&nbsp;634⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [Source Code](https://github.com/bitcart/bitcart))) `MIT` `Docker/Python/Nodejs`
- 🌎 [BTCPay Server](btcpayserver.org/) - Bitcoin and other cryptocurrencies payment processor.  🌎 [Demo](mainnet.demo.btcpayserver.org/), <b><code>&nbsp;&nbsp;6699⭐</code></b> <b><code>&nbsp;&nbsp;1732🍴</code></b> [Source Code](https://github.com/btcpayserver/btcpayserver))) `MIT` `C#`
- 🌎 [DePay](depay.com) - Accept Web3 Payments directly into your wallet. Peer-to-peer, free, self-hosted & open-source.  🌎 [Demo](depay.com/products/payments), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Source Code](https://github.com/depayfi/widgets))) `MIT` `Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;824⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [ExpenseOwl](https://github.com/tanq16/expenseowl)) - Extremely simple expense tracker with a beautiful UI. `MIT` `Go/Docker/K8S`
- 🌎 [ezbookkeeping](ezbookkeeping.mayswind.net/) - A lightweight personal bookkeeping app hosted by yourself.  🌎 [Demo](ezbookkeeping-demo.mayswind.net/), <b><code>&nbsp;&nbsp;&nbsp;644⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Source Code](https://github.com/mayswind/ezbookkeeping))) `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;255⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Family Accounting Tool](https://github.com/nymanjens/facto)) - Web-based finance management tool for partners with partially shared expenses. `Apache-2.0` `Scala`
- 🌎 [Fava](beancount.github.io/fava/) - Fava is the web frontend of Beancount, a text based double-entry accounting system.  🌎 [Demo](fava.pythonanywhere.com/example-with-budgets/income_statement/), <b><code>&nbsp;&nbsp;2113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;305🍴</code></b> [Source Code](https://github.com/beancount/fava))) `MIT` `Python`
- 🌎 [Firefly III](firefly-iii.org/) - Firefly III is a modern financial manager. It helps you to keep track of your money and make budget forecasts. It supports credit cards, has an advanced rule engine and can import data from many banks.  🌎 [Demo](demo.firefly-iii.org/), <b><code>&nbsp;18698⭐</code></b> <b><code>&nbsp;&nbsp;1656🍴</code></b> [Source Code](https://github.com/firefly-iii/firefly-iii))) `AGPL-3.0` `PHP/Docker`
- 🌎 [FOSSBilling](fossbilling.org/) - Free and open source hosting and billing automation. Integrates with WHM, CWP, cPanel and HestiaCP. Full API and easily extensible.  🌎 [Demo](fossbilling.org/demo), <b><code>&nbsp;&nbsp;&nbsp;995⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [Source Code](https://github.com/FOSSBilling/FOSSBilling))) `Apache-2.0` `PHP/Docker`
- 🌎 [Galette](galette.eu/) - Galette is a membership management web application towards non profit organizations.  🌎 [Source Code](git.tuxfamily.org/galette/galette.git/)) `GPL-3.0` `PHP`
- 🌎 [Ghostfolio](ghostfol.io/) - Wealth management software to keep track of stocks, ETFs and cryptocurrencies. (<b><code>&nbsp;&nbsp;5610⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;572🍴</code></b> [Source Code](https://github.com/ghostfolio/ghostfolio))) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [GRR](grr.devome.com/?lang=en) - Assets management and booking for small/medium companies. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Source Code](https://github.com/JeromeDevome/GRR))) `GPL-2.0` `PHP`
- 🌎 [HyperSwitch](hyperswitch.io/) `⚠` - HyperSwitch is an Open Source Financial Switch to make payments Fast, Reliable and Affordable. It lets you connect with multiple payment processors and route traffic effortlessly, all with a single API integration. (<b><code>&nbsp;15676⭐</code></b> <b><code>&nbsp;&nbsp;1580🍴</code></b> [Source Code](https://github.com/juspay/hyperswitch))) `Apache-2.0` `Docker/Rust`
- 🌎 [IHateMoney](ihatemoney.org/) - Manage your shared expenses, easily.  🌎 [Demo](ihatemoney.org/demo/), <b><code>&nbsp;&nbsp;1249⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [Source Code](https://github.com/spiral-project/ihatemoney))) `BSD-3-Clause` `Docker/Python`
- 🌎 [Invoice Ninja](www.invoiceninja.org/) - Powerful tool to invoice clients online.  🌎 [Demo](app.invoiceninja.com/invoices/create), <b><code>&nbsp;&nbsp;8740⭐</code></b> <b><code>&nbsp;&nbsp;2361🍴</code></b> [Source Code](https://github.com/invoiceninja/invoiceninja))) `AAL` `PHP/Docker/K8S`
- <b><code>&nbsp;&nbsp;2683⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;822🍴</code></b> [InvoicePlane](https://github.com/InvoicePlane/InvoicePlane)) - Manage quotes, invoices, payments and customers for your small business. `MIT` `PHP`
- 🌎 [InvoiceShelf](invoiceshelf.com/) - A software that helps you track expenses, payments & create professional invoices & estimates (fork of Crater). (<b><code>&nbsp;&nbsp;1035⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;188🍴</code></b> [Source Code](https://github.com/InvoiceShelf/InvoiceShelf))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Kill Bill](killbill.io/) - Open-Source Subscription Billing & Payments Platform. Have access to real-time analytics and financial reports. (<b><code>&nbsp;&nbsp;4828⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;812🍴</code></b> [Source Code](https://github.com/killbill/killbill))) `Apache-2.0` `Java/Docker`
- 🌎 [Kresus](kresus.org/) - Open source personal finance manager.  🌎 [Demo](kresus.org/en/demo.html), <b><code>&nbsp;&nbsp;&nbsp;312⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Source Code](https://github.com/kresusapp/kresus))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Lago](www.getlago.com/) - Open-source metering and usage-based billing. (<b><code>&nbsp;&nbsp;7542⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;369🍴</code></b> [Source Code](https://github.com/getlago/lago))) `AGPL-3.0` `Docker`
- 🌎 [Maybe](maybe.co/) - An OS for your personal finances built by a small team alongside an incredible community. (<b><code>&nbsp;42891⭐</code></b> <b><code>&nbsp;&nbsp;3093🍴</code></b> [Source Code](https://github.com/maybe-finance/maybe))) `AGPL-3.0` `Docker`
- 🌎 [Mybucks.online](mybucks.online) - A secure, browser-based, password-only self-custodial cryptocurrency wallet.  🌎 [Demo](app.mybucks.online), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Source Code](https://github.com/mybucks-online/app))) `MIT` `Nodejs`
- 🌎 [MyFin Budget](myfinbudget.com) - Personal finances platform (web + REST API + Android) that'll help you budget, keep track of your income/spending and forecast your financial future. (<b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Demo](https://github.com/afaneca/myfin?tab=readme-ov-file#demo-account---try-it-for-yourself)), <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Source Code](https://github.com/afaneca/myfin)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Clients](https://github.com/afaneca/myfin-api))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [OctoBot](www.octobot.cloud/) - Open-source cryptocurrency trading bot. (<b><code>&nbsp;&nbsp;3947⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;864🍴</code></b> [Source Code](https://github.com/Drakkar-Software/OctoBot))) `GPL-3.0` `Python/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;198⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Ocular](https://github.com/simonwep/ocular)) - Simplistic and straightforward budgeting app to track your budget across months and years.  🌎 [Demo](ocular.reinisch.io/#demo)) `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;848⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [OpenBudgeteer](https://github.com/TheAxelander/OpenBudgeteer)) - A budgeting app based on the Bucket Budgeting Principle. `MIT` `Docker/C#`
- 🌎 [Receipt Wrangler](receiptwrangler.io) `⚠` - Easy-to-use receipt manager, powered by AI. Allows users to create receipts effortlessly and quickly, categorize and more.  🌎 [Demo](demo.receiptwrangler.io), <b><code>&nbsp;&nbsp;&nbsp;124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/Receipt-Wrangler/receipt-wrangler-api))) `AGPL-3.0` `Docker`
- 🌎 [REI3](rei3.de/home_en/) - Open source, expandable Business Management Software. Manage tasks, time, assets and much more.  🌎 [Demo](rei3.de/demo_en/), <b><code>&nbsp;&nbsp;&nbsp;423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Source Code](https://github.com/r3-team/r3))) `MIT` `Go`
- 🌎 [SHKeeper](shkeeper.io/) - Cryptocurrency payment processor with the unique combination of gateway and merchant allowing you to accept payments in multiple cryptocurrencies without fees and intermediaries. (<b><code>&nbsp;&nbsp;&nbsp;341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Demo](https://github.com/vsys-host/shkeeper.io?tab=readme-ov-file#11-demo)), <b><code>&nbsp;&nbsp;&nbsp;341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Source Code](https://github.com/vsys-host/shkeeper.io))) `GPL-3.0` `Python`
- 🌎 [SolidInvoice](solidinvoice.co) - Open source invoicing and quote application. (<b><code>&nbsp;&nbsp;&nbsp;653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [Source Code](https://github.com/SolidInvoice/SolidInvoice))) `MIT` `PHP`
- 🌎 [Wallos](wallosapp.com) - Lightweight personal subscription tracker with statistics and optional notifications. (<b><code>&nbsp;&nbsp;4302⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;183🍴</code></b> [Demo](https://github.com/ellite/wallos?tab=readme-ov-file#demo)), <b><code>&nbsp;&nbsp;4302⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;183🍴</code></b> [Source Code](https://github.com/ellite/wallos))) `GPL-3.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;410⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [WYGIWYH](https://github.com/eitchtee/WYGIWYH)) - Simple and powerful finance tracker.  🌎 [Demo](wygiwyh-demo.herculino.com/)) `AGPL-3.0` `Docker/Django`
- 🌎 [YAFFA](www.yaffa.cc) - Personal finance web application, that can be used to keep track of your money, expenses, budgets, and investments. It also helps with long-term financial planning.  🌎 [Demo](sandbox.yaffa.cc), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Source Code](https://github.com/kantorge/yaffa))) `MIT` `PHP`


### Monitoring

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for 🌎 [monitoring](en.wikipedia.org/wiki/Monitoring#Computing) systems, networks, applications and websites. 

**Please visit <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/Monitoring](https://github.com/awesome-foss/awesome-sysadmin#monitoring)), <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/Metrics and Metric Collection](https://github.com/awesome-foss/awesome-sysadmin#metrics--metric-collection))**



### Note-taking & Editors

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Note taking](en.wikipedia.org/wiki/Note-taking) editors.

_Related: [Wikis](#wikis)_

- 🌎 [Blinko](blinko.space/) - A personal note tool with AI features. (<b><code>&nbsp;&nbsp;3232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [Source Code](https://github.com/blinko-space/blinko))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;267⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [DailyTxT](https://github.com/PhiTux/DailyTxT)) - Encrypted diary Web application to save your personal memories of each day. Includes a search function and encrypted file upload. `MIT` `Docker`
- 🌎 [Dnote](www.getdnote.com) - A simple command line notebook with multi-device sync and web interface. (<b><code>&nbsp;&nbsp;2859⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [Source Code](https://github.com/dnote/dnote))) `AGPL-3.0` `Go`
- 🌎 [Docs](docs.numerique.gouv.fr/) - Collaborative note taking, wiki and documentation platform that scales. (<b><code>&nbsp;11379⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;269🍴</code></b> [Source Code](https://github.com/suitenumerique/docs))) `MIT` `K8S`
- 🌎 [draw.io](draw.io) - Diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams. (<b><code>&nbsp;&nbsp;1171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;207🍴</code></b> [Source Code](https://github.com/jgraph/drawio))) `Apache-2.0` `Javascript/Docker`
- <b><code>&nbsp;&nbsp;2031⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [flatnotes](https://github.com/dullage/flatnotes)) - A self-hosted, database-less note-taking web app that utilises a flat folder of markdown files for storage.  🌎 [Demo](demo.flatnotes.io)) `MIT` `Docker`
- 🌎 [HedgeDoc](hedgedoc.org/) - Realtime collaborative markdown notes on all platforms, formerly known as CodiMD and HackMD CE.  🌎 [Demo](demo.hedgedoc.org/), <b><code>&nbsp;&nbsp;5858⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;429🍴</code></b> [Source Code](https://github.com/hedgedoc/hedgedoc))) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Joplin](joplinapp.org/) - Joplin is a note taking application with Markdown editor and encryption support for mobile and desktop platforms. Runs client-side and syncs through self hosted Nextcloud or similar (alternative to Evernote). (<b><code>&nbsp;48718⭐</code></b> <b><code>&nbsp;&nbsp;5281🍴</code></b> [Source Code](https://github.com/laurent22/joplin))) `MIT` `Nodejs`
- 🌎 [kiwix-serve](www.kiwix.org/en/downloads/kiwix-serve/) - HTTP daemon for serving wikis from ZIM files. (<b><code>&nbsp;&nbsp;&nbsp;552⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [Source Code](https://github.com/kiwix/kiwix-tools))) `GPL-3.0` `C++`
- 🌎 [Livebook](livebook.dev) - Realtime collaborative notebook app based on Markdown that supports running Elixir code snippets, TeX and Mermaid Diagrams. Easily deployed using Docker or Elixir. (<b><code>&nbsp;&nbsp;5264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;456🍴</code></b> [Source Code](https://github.com/livebook-dev/livebook))) `Apache-2.0` `Elixir/Docker`
- 🌎 [Memos](usememos.com/) - An open source, self-hosted knowledge base that works with a SQLite db file. (<b><code>&nbsp;38870⭐</code></b> <b><code>&nbsp;&nbsp;2778🍴</code></b> [Source Code](https://github.com/usememos/memos))) `MIT` `Docker/Go`
- <b><code>&nbsp;&nbsp;1254⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;296🍴</code></b> [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad)) - Minimalist notepad.cc clone.  🌎 [Demo](notes.orga.cat/)) `Apache-2.0` `PHP`
- 🌎 [Note Mark](notemark.docs.enchantedcode.co.uk/) - A minimal web-based Markdown notes app. (<b><code>&nbsp;&nbsp;&nbsp;464⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Source Code](https://github.com/enchant97/note-mark))) `AGPL-3.0` `Docker`
- 🌎 [Oddmuse](oddmuse.org/) - A simple wiki engine written in Perl. No database required. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Source Code](https://github.com/kensanata/oddmuse))) `GPL-3.0` `Perl`
- 🌎 [Overleaf](www.overleaf.com/) - Web-based collaborative LaTeX editor. (<b><code>&nbsp;15124⭐</code></b> <b><code>&nbsp;&nbsp;1557🍴</code></b> [Source Code](https://github.com/overleaf/overleaf))) `AGPL-3.0` `Ruby`
- 🌎 [Plainpad](alextselegidis.com/get/plainpad/) - A modern note taking application for the cloud, utilizing the best features of progressive web apps technology.  🌎 [Demo](alextselegidis.com/try/plainpad/), <b><code>&nbsp;&nbsp;&nbsp;329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Source Code](https://github.com/alextselegidis/plainpad))) `GPL-3.0` `PHP`
- 🌎 [SilverBullet](silverbullet.md/) - Note-taking application optimized for people with a hacker mindset.  🌎 [Demo](play.silverbullet.md/), <b><code>&nbsp;&nbsp;3220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;237🍴</code></b> [Source Code](https://github.com/silverbulletmd/silverbullet)), 🌎 [Clients](silverbullet.md/Libraries)) `MIT` `Docker/Deno`
- 🌎 [Standard Notes](docs.standardnotes.com/self-hosting/getting-started) - Simple and private notes app. Protect your privacy while getting more done. That's Standard Notes.  🌎 [Demo](app.standardnotes.com/), <b><code>&nbsp;&nbsp;5672⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;455🍴</code></b> [Source Code](https://github.com/standardnotes/app))) `GPL-3.0` `Ruby`
- <b><code>&nbsp;28454⭐</code></b> <b><code>&nbsp;&nbsp;1928🍴</code></b> [Trilium Notes](https://github.com/zadam/trilium)) - Trilium Notes is a hierarchical note taking application with focus on building large personal knowledge bases. `AGPL-3.0` `Nodejs/Docker/K8S`
- 🌎 [turndown](mixmark-io.github.io/turndown/) - HTML to Markdown converter written in Javascript. (<b><code>&nbsp;&nbsp;9541⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;907🍴</code></b> [Source Code](https://github.com/mixmark-io/turndown))) `MIT` `Javascript`
- 🌎 [Turtl](turtl.it/) - Totally private personal database and note taking app. ([Source Code](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- 🌎 [Writing](josephernest.github.io/writing/) - Lightweight distraction-free text editor, in the browser (Markdown and LaTeX supported). No lag when writing. (<b><code>&nbsp;&nbsp;1053⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [Source Code](https://github.com/josephernest/writing))) `MIT` `Javascript`


### Office Suites

**[`^        back to top        ^`](#awesome-selfhosted)**

An 🌎 [office suite](en.wikipedia.org/wiki/List_of_office_suites) is a collection of productivity software usually containing at least a word processor, spreadsheet and a presentation program.

- 🌎 [Collabora Online Development Edition](www.collaboraoffice.com/code) - Collabora Online Development Edition (CODE) is a powerful LibreOffice-based online office that supports all major document, spreadsheet and presentation file formats, which you can integrate in your own infrastructure.  🌎 [Source Code](cgit.freedesktop.org/libreoffice/online/)) `MPL-2.0` `C++`
- 🌎 [CryptPad](cryptpad.org) - CryptPad is a collaboration suite that is end-to-end-encrypted and open-source. It is built to enable collaboration, synchronizing changes to documents in real time. (<b><code>&nbsp;&nbsp;6192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;697🍴</code></b> [Source Code](https://github.com/cryptpad/cryptpad))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Digislides](ladigitale.dev/digislides/) - Create multimedia presentations in a quick and easy way. (documentation in French).  🌎 [Demo](ladigitale.dev/digislides/), 🌎 [Source Code](codeberg.org/ladigitale/Digislides)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [Etherpad](etherpad.org/) - Etherpad is a highly customizable Open Source online editor providing collaborative editing in really real-time.  🌎 [Demo](demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), <b><code>&nbsp;17327⭐</code></b> <b><code>&nbsp;&nbsp;2911🍴</code></b> [Source Code](https://github.com/ether/etherpad-lite))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [Grist](getgrist.com/) - Grist is a next-generation spreadsheet with relational structure, formula-based access control, and a portable, self-contained format (alternative to Airtable).  🌎 [Demo](docs.getgrist.com), <b><code>&nbsp;&nbsp;8264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;398🍴</code></b> [Source Code](https://github.com/gristlabs/grist-core))) `Apache-2.0` `Nodejs/Python/Docker`
- 🌎 [ONLYOFFICE](helpcenter.onlyoffice.com/faq/server-opensource.aspx) - Office suite that enables you to manage documents, projects, team and customer relations in one place. (<b><code>&nbsp;&nbsp;5336⭐</code></b> <b><code>&nbsp;&nbsp;1125🍴</code></b> [Source Code](https://github.com/ONLYOFFICE/DocumentServer))) `AGPL-3.0` `Nodejs/Docker`
- [PHPOffice](https://github.com/PHPOffice) - PHPOffice contains libraries which permits to write and read files from most office suites. `LGPL-3.0` `PHP`


### Password Managers

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [password manager](en.wikipedia.org/wiki/Password_manager) allows users to store, generate, and manage their passwords for local applications and online services.

- 🌎 [AliasVault](www.aliasvault.net) - End-to-end encrypted password manager with a built-in email alias generator and server. (<b><code>&nbsp;&nbsp;&nbsp;606⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Source Code](https://github.com/lanedirt/AliasVault))) `MIT` `Docker`
- 🌎 [Bitwarden](bitwarden.com/) `⚠` - Password manager with a webapp, browser extension, and mobile app. (<b><code>&nbsp;16386⭐</code></b> <b><code>&nbsp;&nbsp;1380🍴</code></b> [Source Code](https://github.com/bitwarden/server))) `AGPL-3.0` `Docker/C#`
- 🌎 [Passbolt](www.passbolt.com/) - Password manager dedicated for managing passwords in a collaborative way on any Web server, using a MySQL database backend. (<b><code>&nbsp;&nbsp;4951⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;334🍴</code></b> [Source Code](https://github.com/passbolt/passbolt_api))) `AGPL-3.0` `PHP/deb/K8S/Docker`
- 🌎 [PassIt](passit.io/) - Simple password manage with sharing features by group and user, but no administration interface.  🌎 [Demo](app.passit.io/), 🌎 [Source Code](gitlab.com/passit)) `AGPL-3.0` `Docker/Django`
- 🌎 [Passky](passky.org) - Simple, modern and open source password manager with website, browser extension, android and desktop application.  🌎 [Demo](vault.passky.org), <b><code>&nbsp;&nbsp;&nbsp;211⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Source Code](https://github.com/Rabbit-Company/Passky-Server))) `GPL-3.0` `PHP`
- 🌎 [Psono](psono.com/) - A promising password managers fully featured for teams.  🌎 [Demo](www.psono.pw), 🌎 [Source Code](gitlab.com/psono)) `Apache-2.0` `Python`
- 🌎 [Teampass](teampass.net/) - Password manager dedicated for managing passwords in a collaborative way. One symmetric key is used to encrypt all shared/team passwords and stored server side in a file and the database. works on any server Apache, MySQL and PHP. (<b><code>&nbsp;&nbsp;1716⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;558🍴</code></b> [Source Code](https://github.com/nilsteampassnet/TeamPass))) `GPL-3.0` `PHP`
- <b><code>&nbsp;43479⭐</code></b> <b><code>&nbsp;&nbsp;2056🍴</code></b> [Vaultwarden](https://github.com/dani-garcia/vaultwarden)) - Lightweight Bitwarden server API implementation written in Rust. `GPL-3.0` `Rust/Docker`


### Pastebins

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [pastebin](en.wikipedia.org/wiki/Pastebin) is a type of online content-hosting service used for sharing and storing code and text.

- <b><code>&nbsp;&nbsp;&nbsp;510⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [bin](https://github.com/w4/bin)) - A paste bin that's actually minimalist. `WTFPL/0BSD` `Rust`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [BinPastes](https://github.com/querwurzel/BinPastes)) - Minimal pastebin supporting client-side encryption, fulltext search, one-time messages. Intended for one to few users looking for a simple pastebin deployment.  🌎 [Demo](paste.wylke.it)) `Apache-2.0` `Java`
- 🌎 [dpaste](dpaste.org/) - Simple pastebin with multiple text and code option, with short url result easy to remember. (<b><code>&nbsp;&nbsp;&nbsp;571⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [Source Code](https://github.com/DarrenOfficial/dpaste))) `MIT` `Docker/Django`
- <b><code>&nbsp;&nbsp;&nbsp;439⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [FlashPaper](https://github.com/AndrewPaglusch/FlashPaper)) - A one-time encrypted zero-knowledge password/secret sharing application focused on simplicity and security. No database or complicated set-up required.  🌎 [Demo](flashpaper.io)) `MIT` `Docker/PHP`
- 🌎 [Hemmelig](hemmelig.app) - Share encrypted secrets cross organizations, or as private persons. (<b><code>&nbsp;&nbsp;&nbsp;862⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Source Code](https://github.com/HemmeligOrg/Hemmelig.app))) `MIT` `Docker/Nodejs`
- 🌎 [lesma](lesma.eu) - Simple paste app friendly with browser and command line.  🌎 [Demo](lesma.eu), 🌎 [Source Code](gitlab.com/ogarcia/lesma)) `GPL-3.0` `Rust/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Local Content Share](https://github.com/Tanq16/local-content-share)) - Store and share text snippets and files within your local network. `MIT` `Docker/Go`
- 🌎 [not-th.re](not-th.re) - Simple paste sharing platform, with client side encryption, featuring the monaco browser-based code editor.  🌎 [Demo](not-th.re), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/not-three/main))) `AGPL-3.0` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;2224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [Opengist](https://github.com/thomiceli/opengist)) - Self-hosted pastebin powered by Git.  🌎 [Demo](demo.opengist.io)) `AGPL-3.0` `Docker/Go/Nodejs`
- 🌎 [paaster](paaster.io) - Paaster is a secure by default end-to-end encrypted pastebin built with the objective of simplicity. (<b><code>&nbsp;&nbsp;&nbsp;471⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Source Code](https://github.com/WardPearce/paaster))) `GPL-3.0` `Docker`
- 🌎 [pacebin](git.swurl.xyz/swirl/pacebin.git/about/) - A super-minimal pastebin and file upload service written in pure C, focusing on small executable size, portability, and ease of configuration.  🌎 [Demo](paste.swurl.xyz), 🌎 [Source Code](git.swurl.xyz/swirl/pacebin.git)) `AGPL-3.0` `C`
- 🌎 [Password Pusher](pwpush.com) - A dead-simple application to securely communicate passwords (or text) over the web. Passwords automatically expire after a certain number of views and/or time has passed. (<b><code>&nbsp;&nbsp;2349⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;385🍴</code></b> [Source Code](https://github.com/pglombardo/PasswordPusher))) `GPL-3.0` `Docker/K8S/Ruby`
- 🌎 [Pastefy](pastefy.app/) - Beautiful, simple and easy to deploy Pastebin with optional Client-Encryption, Multitab-Pastes, an API, a highlighted Editor and more. (<b><code>&nbsp;&nbsp;&nbsp;285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Source Code](https://github.com/interaapps/pastefy)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Clients](https://github.com/topics/pastefy-addon))) `MIT` `Docker/K8S/Java`
- 🌎 [PrivateBin](privatebin.info/) - PrivateBin is a minimalist, open source online pastebin/discussion board where the server has zero knowledge of hosted data.  🌎 [Demo](privatebin.net/), <b><code>&nbsp;&nbsp;7072⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;856🍴</code></b> [Source Code](https://github.com/PrivateBin/PrivateBin))) `Zlib` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;895⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [rustypaste](https://github.com/orhun/rustypaste)) - A minimal file upload/pastebin service. `MIT` `Rust`
- 🌎 [SnyPy](snypy.com) - Open source on-prem code snippet manager.  🌎 [Demo](app.snypy.com), [Source Code](https://github.com/snypy)) `MIT` `Docker`
- 🌎 [Spacebin](spaceb.in) - Modern Pastebin server written in Go with a JS-free web UI and tons of features.  🌎 [Demo](spaceb.in), <b><code>&nbsp;&nbsp;&nbsp;109⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Source Code](https://github.com/lukewhrit/spacebin))) `Apache-2.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;532⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age)) - Very simple (to deploy and to use) secret message service using Hashicorp Vault as a secrets storage. `MIT` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;453⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Wastebin](https://github.com/matze/wastebin)) - Lightweight, minimal and fast pastebin with an SQLite backend.  🌎 [Demo](bin.bloerg.net)) `MIT` `Rust/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [YABin](https://github.com/Yureien/YABin)) - A pastebin that contains plentiful features while remaining simple. Supports optional E2E encryption, a client-side CLI app, syntax highlighting, minimalistic UI, APIs, keyboard shortcuts, and more. It can even be run in serverless environments.  🌎 [Demo](bin.sohamsen.me/)) `MIT` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [ybFeed](https://github.com/ybizeul/ybFeed)) - Personal micro feed where you can post snippets of text or images. `MIT` `Go/Nodejs/Docker`
- <b><code>&nbsp;&nbsp;2046⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;310🍴</code></b> [Yopass](https://github.com/jhaals/yopass)) - Secure sharing of secrets, passwords and files.  🌎 [Demo](yopass.se/)) `Apache-2.0` `Go/Docker`


### Personal Dashboards

**[`^        back to top        ^`](#awesome-selfhosted)**

Dashboards for accessing information and applications.

_Related: [Monitoring](#monitoring), [Bookmarks and Link Sharing](#bookmarks-and-link-sharing)_

- 🌎 [Dashy](dashy.to/) - Feature-rich homepage for your homelab, with easy YAML configuration.  🌎 [Demo](demo.dashy.to/), <b><code>&nbsp;20372⭐</code></b> <b><code>&nbsp;&nbsp;1508🍴</code></b> [Source Code](https://github.com/lissy93/dashy))) `MIT` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;642⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Fenrus](https://github.com/revenz/fenrus)) - A self hosted personal home page that allows for multiple users, guest access and multiple dashboards for each user. It also has "Smart Apps" which display live data for those apps. `GPL-3.0` `.NET/Docker`
- <b><code>&nbsp;22425⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;833🍴</code></b> [Glance](https://github.com/glanceapp/glance)) - A highly customizable dashboard that puts all your feeds in one place. `AGPL-3.0` `Docker/Go`
- 🌎 [Heimdall](heimdall.site/) - Heimdall is an elegant solution to organise all your web applications. (<b><code>&nbsp;&nbsp;8305⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;574🍴</code></b> [Source Code](https://github.com/linuxserver/Heimdall))) `MIT` `PHP`
- 🌎 [Hiccup](designedbyashw.in/test/hiccup/) - A beautiful static homepage to get to your links and services quickly. It has built-in search, editing, PWA support and localstorage caching to easily organize your start page. (<b><code>&nbsp;&nbsp;&nbsp;164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Source Code](https://github.com/ashwin-pc/hiccup))) `MIT` `Javascript/Docker`
- 🌎 [Homarr](homarr.dev) - Sleek, modern dashboard with many integrations and web-based config.  🌎 [Demo](demo.homarr.dev), <b><code>&nbsp;&nbsp;&nbsp;577⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Source Code](https://github.com/homarr-labs/homarr))) `MIT` `Docker/Nodejs`
- <b><code>&nbsp;22880⭐</code></b> <b><code>&nbsp;&nbsp;1395🍴</code></b> [Homepage by gethomepage](https://github.com/gethomepage/homepage)) - A highly customizable homepage (or startpage / application dashboard) with Docker and service API integrations. `GPL-3.0` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Homepage by tomershvueli](https://github.com/tomershvueli/homepage)) - Simple, standalone, self-hosted PHP page that is your window to your server and the web. `MIT` `PHP`
- <b><code>&nbsp;10009⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;835🍴</code></b> [Homer](https://github.com/bastienwirtz/homer)) - A dead simple static homepage to expose your server services, with an easy yaml configuration and connectivity check. `Apache-2.0` `Docker/K8S/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Hubleys](https://github.com/knrdl/hubleys-dashboard)) - Self-hosted personal dashboards to organize links for multiple users via a central yaml config. `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;575⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Jump](https://github.com/daledavies/jump)) - Yet another self-hosted startpage for your server designed to be simple, stylish, fast and secure. `MIT` `Docker/PHP`
- 🌎 [LinkStack](linkstack.org/) - Link all your social media platforms easily accessible on one page, customizable through an intuitive, easy to use user/admin interface (alternative to Linktree and Manylink).  🌎 [Demo](linksta.cc/), <b><code>&nbsp;&nbsp;2771⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;281🍴</code></b> [Source Code](https://github.com/LinkStackOrg/LinkStack))) `AGPL-3.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [LittleLink](https://github.com/sethcottle/littlelink/)) - A simplistic approach for links in bio with 100+ branded buttons (alternative to Linktree).  🌎 [Demo](littlelink.io/), <b><code>&nbsp;&nbsp;2133⭐</code></b> <b><code>&nbsp;&nbsp;1118🍴</code></b> [Source Code](https://github.com/sethcottle/littlelink))) `MIT` `Javascript`
- 🌎 [Mafl](mafl.hywax.space/) - Minimalistic flexible homepage. (<b><code>&nbsp;&nbsp;&nbsp;483⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Source Code](https://github.com/hywax/mafl))) `MIT` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;5395⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;298🍴</code></b> [Organizr](https://github.com/causefx/Organizr)) - Organizr aims to be your one stop shop for your Servers Frontend. `GPL-3.0` `PHP/Docker`
- 🌎 [portkey](portkey.page) - A simple web portal that can act as startup page and shows a collection of links/urls. Also supports adding custom pages. Everything with one config file.  🌎 [Demo](demo.portkey.page), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/kodehat/portkey))) `AGPL-3.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;2368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [ryot](https://github.com/ignisda/ryot)) - Platform for tracking various facets of your life - media, fitness, etc. (<b><code>&nbsp;&nbsp;2368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Demo](https://github.com/IgnisDa/ryot?tab=readme-ov-file#-demo))) `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;380⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Starbase 80](https://github.com/notclickable-jordan/starbase-80)) - A simple homepage with an iPad-style application grid, for mobile and desktop. One JSON configuration file. `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Web-Portal](https://github.com/enchant97/web-portal)) - A python web app designed to allow a easy way to manage the links to all of your web services. `AGPL-3.0` `Docker/Python`
- <b><code>&nbsp;&nbsp;3512⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Your Spotify](https://github.com/Yooooomi/your_spotify)) `⚠` - Allows you to record your Spotify listening activity and have statistics about them served through a Web application. `MIT` `Nodejs/Docker`


### Photo Galleries

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [gallery](en.wikipedia.org/wiki/Gallery_Software) is software that helps the user publish or share photos, pictures, videos or other digital media.

_Related: [Static Site Generators](#static-site-generators), [Media Streaming - Video Streaming](#media-streaming---video-streaming), [Content Management Systems (CMS)](#content-management-systems-cms)_

- 🌎 [Chevereto](chevereto.com/) - Ultimate image sharing software. Create your very own personal image hosting website in just minutes. (<b><code>&nbsp;&nbsp;&nbsp;628⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Source Code](https://github.com/chevereto/chevereto))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Coppermine](coppermine-gallery.com/) - Multilingual photo gallery that integrates with various bulletin boards. Includes upload approval and password protected albums.  🌎 [Demo](coppermine-gallery.com/demo/cpg15x/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Source Code](https://github.com/coppermine-gallery/cpg1.6.x))) `GPL-3.0` `PHP`
- 🌎 [Damselfly](damselfly.info) - Fast server-based photo management system for large collections of images. Includes face detection, face & object recognition, powerful search, and EXIF Keyword tagging. Runs on Linux, MacOS and Windows. (<b><code>&nbsp;&nbsp;1615⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [Source Code](https://github.com/webreaper/damselfly))) `GPL-3.0` `Docker/C#/.NET`
- 🌎 [Ente](ente.io/) - An end-to-end encrypted photo-sharing platform (alternative to Google Photos, Apple Photos). (<b><code>&nbsp;18792⭐</code></b> <b><code>&nbsp;&nbsp;1047🍴</code></b> [Source Code](https://github.com/ente-io/ente))) `AGPL-3.0` `Docker/Nodejs/Go`
- 🌎 [HomeGallery](home-gallery.org) - Web gallery to browse personal photos and videos featuring tagging, mobile-friendly, and AI powered image discovery.  🌎 [Demo](demo.home-gallery.org), <b><code>&nbsp;&nbsp;&nbsp;922⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [Source Code](https://github.com/xemle/home-gallery))) `MIT` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;788⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Immich Kiosk](https://github.com/damongolding/immich-kiosk)) - A lightweight slideshow for running on kiosk devices and browsers that uses Immich as a data source. `GPL-3.0` `Docker/Go`
- 🌎 [Immich](immich.app/) - Self-hosted photo and video backup solution directly from your mobile phone. (<b><code>&nbsp;63528⭐</code></b> <b><code>&nbsp;&nbsp;3329🍴</code></b> [Source Code](https://github.com/immich-app/immich))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;7252⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;326🍴</code></b> [LibrePhotos](https://github.com/LibrePhotos/librephotos)) - Self hosted wannabe Google Photos clone, with a slight focus on cool graphs.  🌎 [Clients](docs.librephotos.com/docs/user-guide/mobile/)) `MIT` `Python/Docker`
- 🌎 [Lychee](lycheeorg.github.io/) - Open source grid and album based photo-management-system. (<b><code>&nbsp;&nbsp;3629⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;333🍴</code></b> [Source Code](https://github.com/LycheeOrg/Lychee))) `MIT` `PHP/Docker`
- 🌎 [Mediagoblin](mediagoblin.org) - Free software media publishing platform that anyone can run (alternative to Flickr, YouTube, SoundCloud, etc).  🌎 [Source Code](git.savannah.gnu.org/cgit/mediagoblin.git/tree/)) `AGPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Mejiro](https://github.com/dmpop/mejiro)) - An easy-to-use PHP web application for instant photo publishing. `GPL-3.0` `PHP`
- 🌎 [Nextcloud Memories](memories.gallery/) - Fast, modern and advanced photo management suite. Runs as a Nextcloud app.  🌎 [Demo](demo.memories.gallery/apps/memories/), <b><code>&nbsp;&nbsp;3452⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [Source Code](https://github.com/pulsejet/memories))) `AGPL-3.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;480⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Photofield](https://github.com/SmilyOrg/photofield)) - Experimental fast photo viewer. `MIT` `Docker/Go`
- 🌎 [PhotoPrism](photoprism.org) - Personal photo management powered by Go and Google TensorFlow.  Browse, organize, and share your personal photo collection, using the latest technologies to automatically tag and find pictures.  🌎 [Demo](demo.photoprism.app/library/browse), <b><code>&nbsp;36970⭐</code></b> <b><code>&nbsp;&nbsp;2044🍴</code></b> [Source Code](https://github.com/photoprism/photoprism))) `AGPL-3.0` `Go/Docker`
- 🌎 [Photoview](photoview.github.io/) - A simple and user-friendly Photo Gallery for personal servers. It is made for photographers and aims to provide an easy and fast way to navigate directories, with thousands of high resolution photos. (<b><code>&nbsp;&nbsp;5832⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;423🍴</code></b> [Source Code](https://github.com/photoview/photoview))) `GPL-3.0` `Go/Docker`
- 🌎 [PiGallery 2](bpatrik.github.io/pigallery2/) - A directory-first photo gallery website, with a rich UI, optimised for running on low resource servers. (<b><code>&nbsp;&nbsp;1890⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [Source Code](https://github.com/bpatrik/pigallery2))) `MIT` `Docker/Nodejs`
- 🌎 [Piwigo](piwigo.org/) - Photo gallery software for the web, built by an active community of users and developers. (<b><code>&nbsp;&nbsp;3425⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;453🍴</code></b> [Source Code](https://github.com/Piwigo/Piwigo))) `GPL-2.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;900⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [sigal](https://github.com/saimn/sigal)) - Yet another simple static gallery generator. `MIT` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [SPIS](https://github.com/gbbirkisson/spis)) - A simple, lightweight and fast media server with decent mobile support. `GPL-3.0` `Docker/Rust`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [This week in past](https://github.com/RouHim/this-week-in-past)) - Aggregates images taken this week, from previous years and presents them on a web page with a simple slideshow. `MIT` `Docker/Rust`
- [Thumbor](http://thumbor.org/) - A smart imaging service and enables on-demand cropping, resizing, applying filters and optimizing images. (<b><code>&nbsp;10231⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;838🍴</code></b> [Source Code](https://github.com/thumbor/thumbor))) `MIT` `Python/Docker`
- 🌎 [Zenphoto](www.zenphoto.org/) - Open-source gallery and CMS project. (<b><code>&nbsp;&nbsp;&nbsp;305⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [Source Code](https://github.com/zenphoto/zenphoto))) `GPL-2.0` `PHP`


### Polls and Events

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for organising 🌎 [polls](en.wikipedia.org/wiki/Opinion_poll) and 🌎 [events](en.wikipedia.org/wiki/Event).

_Related: [Booking and Scheduling](#booking-and-scheduling)_

- <b><code>&nbsp;&nbsp;&nbsp;265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Bitpoll](https://github.com/fsinfuhh/Bitpoll)) - Conduct polls about dates, times or general questions.  🌎 [Demo](bitpoll.de/)) `GPL-3.0` `Docker/Python`
- 🌎 [Bracket](docs.bracketapp.nl/) - Flexible tournament system to build a tournament setup, add teams, schedule matches, keep track of scores and present ranking live to the public.  🌎 [Demo](www.bracketapp.nl/demo), <b><code>&nbsp;&nbsp;&nbsp;311⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [Source Code](https://github.com/evroon/bracket))) `AGPL-3.0` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;343⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Christmas Community](https://github.com/Wingysam/Christmas-Community)) - Create a simple place for your entire family to use to find gifts that people want, and to avoid double-gifting. `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Claper](claper.co/) - The ultimate tool to interact with your audience (alternative to Slido, AhaSlides and Mentimeter). (<b><code>&nbsp;&nbsp;&nbsp;544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [Source Code](https://github.com/ClaperCo/Claper))) `GPL-3.0` `Elixir/Docker`
- 🌎 [ClearFlask](clearflask.com) - Community-feedback tool for managing incoming feedback and prioritizing a public roadmap (alternative to Canny, UserVoice, Upvoty).  🌎 [Demo](product.clearflask.com), <b><code>&nbsp;&nbsp;&nbsp;347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Source Code](https://github.com/clearflask/clearflask))) `AGPL-3.0` `Docker`
- 🌎 [docassemble](docassemble.org/) - A free, open-source expert system for guided interviews and document assembly, based on Python, YAML, and Markdown.  🌎 [Demo](demo.docassemble.org/run/legal), <b><code>&nbsp;&nbsp;&nbsp;830⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [Source Code](https://github.com/jhpyle/docassemble))) `MIT` `Docker/Python`
- 🌎 [Fider](fider.io) - Open platform to collect and prioritize feedback (alternative to UserVoice).  🌎 [Demo](demo.fider.io), <b><code>&nbsp;&nbsp;3395⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;675🍴</code></b> [Source Code](https://github.com/getfider/fider))) `MIT` `Docker`
- 🌎 [Formbricks](formbricks.com) - Experience Management Suite built on the largest open source survey stack worldwide. Gracefully gather feedback at every step of the customer journey to know what your customers need.  🌎 [Demo](app.formbricks.com), <b><code>&nbsp;10445⭐</code></b> <b><code>&nbsp;&nbsp;1826🍴</code></b> [Source Code](https://github.com/formbricks/formbricks))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Framadate](framadate.org/abc/) - Online service for planning an appointment or make a decision quickly and easily: Make a poll, Define dates or subjects to choose, Send the poll link to your friends or colleagues, Discuss and make a decision.  🌎 [Demo](framadate.org/aqg259dth55iuhwm), 🌎 [Source Code](framagit.org/framasoft/framadate?)) `CECILL-B` `PHP`
- 🌎 [Gancio](gancio.org/) - A shared agenda for local communities.  🌎 [Source Code](framagit.org/les/gancio)) `AGPL-3.0` `Nodejs`
- 🌎 [gathio](gath.io/) - Self-destructing, shareable, no-registration event pages.  🌎 [Demo](gath.io/), <b><code>&nbsp;&nbsp;&nbsp;351⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Source Code](https://github.com/lowercasename/gathio))) `GPL-3.0` `Nodejs/Docker`
- 🌎 [HeyForm](heyform.net) - Form builder that allows anyone to create engaging conversational forms for surveys, questionnaires, quizzes, and polls. (<b><code>&nbsp;&nbsp;8009⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;574🍴</code></b> [Source Code](https://github.com/heyform/heyform))) `AGPL-3.0` `Docker`
- 🌎 [hitobito](hitobito.com) - A web application to manage complex group hierarchies with members, events and a lot more.  🌎 [Demo](demo.hitobito.com/en/users/sign_in), <b><code>&nbsp;&nbsp;&nbsp;406⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [Source Code](https://github.com/hitobito/hitobito))) `AGPL-3.0` `Ruby`
- 🌎 [Input](getinput.co) - A privacy-focused, no-code, open-source form builder designed for simplicity and brand consistency. (<b><code>&nbsp;&nbsp;&nbsp;218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Source Code](https://github.com/deck9/input))) `AGPL-3.0` `PHP/Nodejs/Docker`
- 🌎 [LimeSurvey](www.limesurvey.org) - Feature-rich Open Source web based polling software. Supports extensive survey logic.  🌎 [Demo](demo.limesurvey.org), <b><code>&nbsp;&nbsp;3064⭐</code></b> <b><code>&nbsp;&nbsp;1030🍴</code></b> [Source Code](https://github.com/LimeSurvey/LimeSurvey))) `GPL-2.0` `PHP`
- 🌎 [Meetable](events.indieweb.org) - A minimal events aggregator. (<b><code>&nbsp;&nbsp;&nbsp;137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/aaronpk/Meetable))) `MIT` `PHP`
- 🌎 [Mobilizon](mobilizon.org) - A federated tool that helps you find, create and organise events and groups.  🌎 [Source Code](framagit.org/framasoft/mobilizon/)) `GPL-3.0` `Elixir/Docker`
- 🌎 [OpnForm](opnform.com) - Beautiful open-source form builder.  🌎 [Demo](opnform.com/forms/create/guest), <b><code>&nbsp;&nbsp;2537⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;357🍴</code></b> [Source Code](https://github.com/JhumanJ/opnform))) `AGPL-3.0` `PHP/Nodejs/Docker`


### Proxy

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [proxy](en.wikipedia.org/wiki/Proxy_server) is a server application that acts as an intermediary between a client requesting a resource and the server providing that resource. This section about forward (i.e. outgoing) proxies. For reverse proxies, see the Web Server section.

_Related: [Web Servers](#web-servers)_

- 🌎 [imgproxy](imgproxy.net/) - Fast and secure standalone server for resizing and converting remote images. It works great when you need to resize multiple images on the fly without preparing a ton of cached resized images or re-doing it every time the design changes. (<b><code>&nbsp;&nbsp;9464⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;664🍴</code></b> [Source Code](https://github.com/imgproxy/imgproxy))) `MIT` `Go/Docker/K8S`
- 🌎 [iodine](code.kryo.se/iodine/) - IPv4 over DNS tunnel solution, enabling you to start up a socks5 proxy listener. (<b><code>&nbsp;&nbsp;6401⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;522🍴</code></b> [Source Code](https://github.com/yarrick/iodine))) `ISC` `C/deb`
- <b><code>&nbsp;&nbsp;&nbsp;124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Koblas](https://github.com/ynuwenhof/koblas)) - Lightweight SOCKS5 proxy server. `MIT` `Rust/Docker`
- 🌎 [Outline Server](getoutline.org/) - A proxy server that runs a Shadowsocks instance for each access key and a REST API to manage the access keys. (<b><code>&nbsp;&nbsp;5936⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;800🍴</code></b> [Source Code](https://github.com/Jigsaw-Code/outline-server))) `Apache-2.0` `Docker/Nodejs`
- 🌎 [Privoxy](www.privoxy.org) - Non-caching web proxy with advanced filtering capabilities for enhancing privacy, modifying web page data and HTTP headers, controlling access, and removing ads and other obnoxious Internet junk. `GPL-2.0` `C/deb`
- <b><code>&nbsp;&nbsp;4196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;324🍴</code></b> [sish](https://github.com/antoniomika/sish)) - HTTP(S)/WS(S)/TCP tunnels to localhost using only SSH (serveo/ngrok alternative). `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server)) - SOCKS5 proxy server with built-in authentication and Telegram-bot for user management and user statistics on data spent (handy when you pay per GB of data). It is dockerised and simple to install. `Apache-2.0` `Docker`
- [Squid](http://www.squid-cache.org/) - Caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages.  🌎 [Source Code](code.launchpad.net/squid)) `GPL-2.0` `C/deb`
- 🌎 [Tinyproxy](tinyproxy.github.io/) - Light-weight HTTP/HTTPS proxy daemon. (<b><code>&nbsp;&nbsp;5147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;695🍴</code></b> [Source Code](https://github.com/tinyproxy/tinyproxy))) `GPL-2.0` `C/deb`
- 🌎 [txtdot](tempoworks.github.io/documentation) - A HTTP proxy that parses only text, links and pictures from pages reducing internet bandwidth usage, removing ads and heavy scripts.  🌎 [Demo](txt.dc09.ru), <b><code>&nbsp;&nbsp;&nbsp;178⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Source Code](https://github.com/TxtDot/txtdot))) `MIT` `Nodejs/Docker`


### Recipe Management

**[`^        back to top        ^`](#awesome-selfhosted)**

Software and tools for managing 🌎 [recipes](en.wikipedia.org/wiki/Recipe).

- 🌎 [Bar Assistant](barassistant.app/) - Manage your home bar while adding your ingredients, searching for cocktails and creating custom cocktail recipes.  🌎 [Demo](demo.barassistant.app/), <b><code>&nbsp;&nbsp;&nbsp;776⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Source Code](https://github.com/karlomikus/bar-assistant))) `MIT` `PHP/Docker`
- 🌎 [Fork Recipes](mikebgrep.github.io/forkapi/clients/) - Manage your food recipes with simplicity. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/mikebgrep/fork.recipes))) `BSD-3-Clause` `Docker`
- 🌎 [KitchenOwl](tombursch.github.io/kitchenowl/) - A cross-platform shopping list, recipe storage, expense tracker, and meal planner following the material design language. (<b><code>&nbsp;&nbsp;1611⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [Source Code](https://github.com/TomBursch/kitchenowl))) `AGPL-3.0` `Docker/deb`
- 🌎 [ManageMeals](managemeals.com/) - Manage recipes, import recipes by URL and organize them without any ads or unnecessary text.  🌎 [Demo](demo.managemeals.com/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/managemeals/manage-meals-web))) `GPL-3.0` `Docker`
- 🌎 [Mealie](nightly.mealie.io/) - Material design inspired recipe manager with category and tag management, shopping-lists, meal-planner, and site customizations. Mealie is focused on simple user interactions to keep the whole family using the app. (<b><code>&nbsp;&nbsp;8863⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;863🍴</code></b> [Source Code](https://github.com/mealie-recipes/mealie))) `MIT` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;707⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [RecipeSage](https://github.com/julianpoy/recipesage)) - A recipe keeper, meal plan organizer, and shopping list manager that can import recipes directly from any URL.  🌎 [Demo](recipesage.com)) `AGPL-3.0` `Nodejs`
- 🌎 [Recipya](recipes.musicavis.ca) - A clean, simple and powerful recipe manager your whole family will enjoy.  🌎 [Demo](recipes.musicavis.ca/guide/login), <b><code>&nbsp;&nbsp;&nbsp;320⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Source Code](https://github.com/reaper47/recipya))) `GPL-3.0` `Docker/Go`
- 🌎 [Specifically Clementines](davideshay.github.io/groceries/) - Grocery shopping app (previously Groceries), providing reliable sync with multiple users/devices (web/Android/iOS), recipes and integration with Tandoor. (<b><code>&nbsp;&nbsp;&nbsp;240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Source Code](https://github.com/davideshay/groceries))) `MIT` `Docker`
- 🌎 [Tamari](tamariapp.com) - Recipe manager web app with a built-in collection of recipes. Organize by favorites and categories, create shopping lists, and plan meals.  🌎 [Demo](app.tamariapp.com), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Source Code](https://github.com/alexbates/Tamari))) `GPL-3.0` `Docker/Python`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [What To Cook?](https://github.com/kassner/whattocook)) - Get a recipe to cook today, based on the ingredients you have at home. `AGPL-3.0` `Docker`


### Remote Access

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Remote desktop](en.wikipedia.org/wiki/Remote_desktop_software) and 🌎 [SSH](en.wikipedia.org/wiki/Secure_Shell) servers and web interfaces for remote management of computer systems.

- 🌎 [Engity's Bifröst](bifroest.engity.org/) - Highly customizable SSH server with several ways to authorize a user and options where and how to execute a user's session. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Source Code](https://github.com/engity-com/bifroest))) `Apache-2.0` `Go/Docker`
- 🌎 [Firezone](www.firezone.dev/) - Self-hosted secure remote access gateway that supports the WireGuard protocol. It offers a Web GUI, 1-line install script, multi-factor auth (MFA), and SSO. (<b><code>&nbsp;&nbsp;7150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;305🍴</code></b> [Source Code](https://github.com/firezone/firezone))) `Apache-2.0` `Elixir/Docker`
- 🌎 [Guacamole](guacamole.apache.org) - Guacamole is a clientless remote desktop gateway. It supports standard protocols like VNC and RDP. (<b><code>&nbsp;&nbsp;3303⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;675🍴</code></b> [Source Code](https://github.com/apache/guacamole-server))) `Apache-2.0` `Java/C`
- 🌎 [MeshCentral](meshcentral.com/) - A full computer management website. With MeshCentral, you can run your own web server to remotely manage and control computers on a local network or anywhere on the internet. (<b><code>&nbsp;&nbsp;4838⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;637🍴</code></b> [Source Code](https://github.com/Ylianst/MeshCentral))) `Apache-2.0` `Nodejs`
- <b><code>&nbsp;&nbsp;4757⭐</code></b> <b><code>&nbsp;&nbsp;1625🍴</code></b> [Remotely](https://github.com/immense/Remotely)) - A remote desktop control and remote scripting solution, enterprise level remote support solution with admin web interface and remote control via browser. `GPL-3.0` `C#/Docker`
- 🌎 [RustDesk](rustdesk.com/) - Remote Desktop Access software that works out-of-the-box (alternative to TeamViewer). (<b><code>&nbsp;&nbsp;7603⭐</code></b> <b><code>&nbsp;&nbsp;1696🍴</code></b> [Source Code](https://github.com/rustdesk/rustdesk-server))) `AGPL-3.0` `Rust/Docker/deb`
- 🌎 [ShellHub](www.shellhub.io) - ShellHub is a modern SSH server for remotely accessing linux devices via command line (using any SSH client) or web-based user interface, designed as an alternative to sshd. (<b><code>&nbsp;&nbsp;1534⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Source Code](https://github.com/shellhub-io/shellhub))) `Apache-2.0` `Docker`
- <b><code>&nbsp;&nbsp;2647⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;376🍴</code></b> [Sshwifty](https://github.com/nirui/sshwifty)) - Sshwifty is a SSH and Telnet connector made for the Web.  🌎 [Demo](sshwifty-demo.nirui.org)) `AGPL-3.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;4466⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;139🍴</code></b> [Warpgate](https://github.com/warp-tech/warpgate)) - Smart SSH and HTTPS bastion that works with any SSH client. `Apache-2.0` `Rust/Docker`


### Resource Planning

**[`^        back to top        ^`](#awesome-selfhosted)**

Software and tools to help with 🌎 [resource and supply planning](en.wikipedia.org/wiki/Resource_planning), including 🌎 [enterprise resource and supply planning (ERP)](en.wikipedia.org/wiki/Enterprise_resource_planning).

_Related: [Money, Budgeting & Management](#money-budgeting--management), [Inventory Management](#inventory-management)_

- 🌎 [Dolibarr](www.dolibarr.org/) - Modern CRM software package to manage your company or foundation activity (contacts, suppliers, invoices, orders, stocks, agenda, accounting, ...).  🌎 [Demo](www.dolibarr.org/onlinedemo.php), <b><code>&nbsp;&nbsp;5900⭐</code></b> <b><code>&nbsp;&nbsp;2917🍴</code></b> [Source Code](https://github.com/Dolibarr/dolibarr))) `GPL-3.0` `PHP/deb`
- 🌎 [ERPNext](erpnext.com) - Free open source ERP system. (<b><code>&nbsp;24507⭐</code></b> <b><code>&nbsp;&nbsp;8117🍴</code></b> [Source Code](https://github.com/frappe/erpnext))) `GPL-3.0` `Python/Docker`
- 🌎 [farmOS](farmos.org/) - Web-based farm record keeping application.  🌎 [Demo](farmos-demo.rootedsolutions.io/), <b><code>&nbsp;&nbsp;1059⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;299🍴</code></b> [Source Code](https://github.com/farmOS/farmOS))) `GPL-2.0` `PHP/Docker`
- 🌎 [grocy](grocy.info/) - ERP beyond your fridge - grocy is a web-based self-hosted groceries & household management solution for your home.  🌎 [Demo](en.demo.grocy.info/), <b><code>&nbsp;&nbsp;7392⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;606🍴</code></b> [Source Code](https://github.com/grocy/grocy))) `MIT` `PHP/Docker`
- 🌎 [LedgerSMB](ledgersmb.org/) - Integrated accounting and ERP system for small and midsize businesses, with double entry accounting, budgeting, invoicing, quotations, projects, orders and inventory management, shipping and more.  🌎 [Demo](demo.cloud.efficito.com/erp/1.5/login.pl), <b><code>&nbsp;&nbsp;&nbsp;463⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [Source Code](https://github.com/ledgersmb/LedgerSMB))) `GPL-2.0` `Docker/Perl`
- 🌎 [Odoo](www.odoo.com) - Free open source ERP system.  🌎 [Demo](demo.odoo.com/), <b><code>&nbsp;42247⭐</code></b> <b><code>&nbsp;27293🍴</code></b> [Source Code](https://github.com/odoo/odoo))) `LGPL-3.0` `Python/deb/Docker`
- 🌎 [OFBiz](ofbiz.apache.org/) - Enterprise Resource Planning system with a suite of business applications flexible enough to be used across any industry. (<b><code>&nbsp;&nbsp;&nbsp;873⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;566🍴</code></b> [Source Code](https://github.com/apache/ofbiz-framework))) `Apache-2.0` `Java`
- 🌎 [Tryton](www.tryton.org/) - Free open source business solution.  🌎 [Demo](www.tryton.org/demo), 🌎 [Source Code](foss.heptapod.net/tryton/tryton)) `GPL-3.0` `Python`


### Search Engines

**[`^        back to top        ^`](#awesome-selfhosted)**

A [search engine](https://en.wikipedia.org/wiki/Search_engine_(computing)) is an 🌎 [information retrieval system](en.wikipedia.org/wiki/Information_retrieval) designed to help find information stored on a computer system. This includes 🌎 [Web search engines](en.wikipedia.org/wiki/Web_search_engine).

- 🌎 [Apache Solr](lucene.apache.org/solr/) - Enterprise search platform featuring full-text search, hit highlighting, faceted search, real-time indexing, dynamic clustering, and rich document (e.g., Word, PDF) handling. (<b><code>&nbsp;&nbsp;1358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;706🍴</code></b> [Source Code](https://github.com/apache/solr))) `Apache-2.0` `Java/Docker/K8S`
- 🌎 [Fess](fess.codelibs.org/) - Fess is a very powerful and easily deployable Enterprise Search Server.  🌎 [Demo](search.n2sm.co.jp/), <b><code>&nbsp;&nbsp;1032⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [Source Code](https://github.com/codelibs/fess))) `Apache-2.0` `Java/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Jina](https://github.com/jina-ai/jina/)) - Cloud-native neural search framework for any kind of data. `Apache-2.0` `Python/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Manticore Search](https://github.com/manticoresoftware/manticoresearch/)) - Full-text search and data analytics, with fast response time for small, medium and big data (alternative to Elasticsearch). `GPL-3.0` `Docker/deb/C++/K8S`
- 🌎 [MeiliSearch](www.meilisearch.com) - Ultra relevant, instant and typo-tolerant full-text search API. (<b><code>&nbsp;50243⭐</code></b> <b><code>&nbsp;&nbsp;1980🍴</code></b> [Source Code](https://github.com/meilisearch/MeiliSearch))) `MIT` `Rust/Docker/deb`
- 🌎 [OpenSearch](opensearch.org) - Open source distributed and RESTful search engine. (<b><code>&nbsp;10500⭐</code></b> <b><code>&nbsp;&nbsp;1988🍴</code></b> [Source Code](https://github.com/opensearch-project/OpenSearch))) `Apache-2.0` `Java/Docker/K8S/deb`
- 🌎 [SearXNG](docs.searxng.org/) `⚠` - Internet metasearch engine which aggregates results from various search services and databases (Fork of Searx). (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/searxng/searxng/))) `AGPL-3.0` `Python/Docker`
- <b><code>&nbsp;&nbsp;1030⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [sist2](https://github.com/simon987/sist2)) - Lightning-fast file system indexer and search tool. `GPL-3.0` `C/Docker`
- 🌎 [Sosse](sosse.readthedocs.io/en/stable/) - Selenium based search engine and crawler with offline archiving.  🌎 [Source Code](gitlab.com/biolds1/sosse)) `AGPL-3.0` `Python/Docker`
- 🌎 [Typesense](typesense.org) - Blazing fast, typo-tolerant open source search engine optimized for developer happiness and ease of use. (<b><code>&nbsp;22769⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;711🍴</code></b> [Source Code](https://github.com/typesense/typesense))) `GPL-3.0` `C++/Docker/K8S/deb`
- <b><code>&nbsp;&nbsp;&nbsp;841⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [Websurfx](https://github.com/neon-mmd/websurfx)) `⚠` - Aggregate results from other search engines (metasearch engine) without ads while keeping privacy and security in mind. It is extremely fast and provides a high level of customization (alternative to SearX). `AGPL-3.0` `Rust/Docker`
- <b><code>&nbsp;10617⭐</code></b> <b><code>&nbsp;&nbsp;1002🍴</code></b> [Whoogle](https://github.com/benbusby/whoogle-search)) `⚠` - A self-hosted, ad-free, privacy-respecting metasearch engine. `MIT` `Python`
- 🌎 [Yacy](yacy.net/en/index.html) - Peer based, decentralized search engine server. (<b><code>&nbsp;&nbsp;3529⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;449🍴</code></b> [Source Code](https://github.com/yacy/yacy_search_server))) `GPL-2.0` `Java/Docker/K8S`
- 🌎 [ZincSearch](zincsearch.com) - Search engine that requires minimal resources (alternative to Elasticsearch). (<b><code>&nbsp;17327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;752🍴</code></b> [Demo](https://github.com/zinclabs/zinc#playground-server)), <b><code>&nbsp;17327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;752🍴</code></b> [Source Code](https://github.com/zincsearch/zincsearch))) `Apache-2.0` `Go/Docker/K8S`


### Self-hosting Solutions

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for easy installation, management and configuration of self-hosted services and applications.

- <b><code>&nbsp;&nbsp;3410⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;505🍴</code></b> [Ansible-NAS](https://github.com/DaveStephens/ansible-nas)) - Build a full-featured home server with this playbook and an Ubuntu box. `MIT` `Ansible/Docker`
- 🌎 [CasaOS](www.casaos.io/) - A simple, easy-to-use, elegant open-source Home Cloud system. (<b><code>&nbsp;29356⭐</code></b> <b><code>&nbsp;&nbsp;1592🍴</code></b> [Source Code](https://github.com/IceWhaleTech/CasaOS))) `Apache-2.0` `Go/Docker`
- 🌎 [DietPi](dietpi.com/) - Minimal Debian OS optimized for single-board computers, which allows you to easily install and manage several services for selfhosting at home. (<b><code>&nbsp;&nbsp;5171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;510🍴</code></b> [Source Code](https://github.com/MichaIng/DietPi))) `GPL-2.0` `Shell`
- 🌎 [DockSTARTer](dockstarter.com/) - DockSTARTer helps you get started with home server apps running in Docker. (<b><code>&nbsp;&nbsp;2407⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;270🍴</code></b> [Source Code](https://github.com/GhostWriters/DockSTARTer))) `MIT` `Shell`
- 🌎 [Dropserver](dropserver.org) - An application platform for your personal web services. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/teleclimber/Dropserver/))) `Apache-2.0` `Go/Deno`
- 🌎 [FreedomBox](freedombox.org/) - Community project to develop, design and promote personal servers running free software for private, personal, communications.  🌎 [Source Code](salsa.debian.org/freedombox-team/freedombox)) `AGPL-3.0` `Python/deb`
- 🌎 [HomelabOS](homelabos.com) - Your very own offline-first privacy-centric open-source data-center. Deploy over 100 services with a few commands.  🌎 [Source Code](gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- 🌎 [HomeServerHQ](www.homeserverhq.com/) - An all-in-one home server infrastructure and installer. Have a fully configured email server, VPN, and public website(s) set up in less than an hour, even behind CGNAT. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Source Code](https://github.com/homeserverhq/hshq))) `GPL-3.0` `Shell`
- 🌎 [LibreServer](libreserver.org/) - Home server configuration based on Debian. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/bashrc2/libreserver))) `AGPL-3.0` `Shell`
- <b><code>&nbsp;&nbsp;&nbsp;110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Mars Server](https://github.com/borjapazr/mars-server)) - Managed home server with Docker, Docker Compose, Make and Bash. `MIT` `Docker`
- 🌎 [Mistborn](gitlab.com/cyber5k/mistborn) - Mistborn is your own virtual private cloud platform and WebUI that manages self hosted services. `MIT` `Shell/Docker`
- <b><code>&nbsp;&nbsp;2681⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;311🍴</code></b> [NextCloudPi](https://github.com/nextcloud/nextcloudpi)) - Nextcloud preinstalled and preconfigured, with a text and web management interface and all the tools needed to self host private data. With installation images for Raspberry Pi, Odroid, Rock64, Docker, and a curl installer for Armbian/Debian. `GPL-2.0` `Shell/PHP`
- 🌎 [OpenMediaVault](www.openmediavault.org/) - OpenMediaVault is the next generation network attached storage (NAS) solution based on Debian Linux. It contains services like SSH, (S)FTP, SMB/CIFS, DAAP media server, RSync, BitTorrent client and many more. (<b><code>&nbsp;&nbsp;5604⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;506🍴</code></b> [Source Code](https://github.com/openmediavault/openmediavault))) `GPL-3.0` `PHP`
- 🌎 [Sandstorm](sandstorm.io/) - Personal server for running self-hosted apps easily and securely.  🌎 [Demo](demo.sandstorm.io/), <b><code>&nbsp;&nbsp;6835⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;709🍴</code></b> [Source Code](https://github.com/sandstorm-io/sandstorm))) `Apache-2.0` `C++/Shell`
- <b><code>&nbsp;&nbsp;&nbsp;265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Self Host Blocks](https://github.com/ibizaman/selfhostblocks)) `⚠` - Modular server management based on NixOS modules and focused on best practices. `AGPL-3.0` `Nix`
- 🌎 [StartOS](start9.com) - Browser-based, graphical Operating System (OS) that makes running a personal server as easy as running a personal computer. (<b><code>&nbsp;&nbsp;1153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [Source Code](https://github.com/Start9Labs/start-os))) `MIT` `Rust`
- 🌎 [Syncloud](syncloud.org/) - Your own online file storage, social network or email server. (<b><code>&nbsp;&nbsp;&nbsp;411⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Source Code](https://github.com/syncloud/platform))) `GPL-3.0` `Go/Shell`
- 🌎 [Tipi](runtipi.io/) - Homeserver manager. One command setup, one click installs for your favorites self-hosted apps. (<b><code>&nbsp;&nbsp;8379⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;304🍴</code></b> [Source Code](https://github.com/meienberger/runtipi))) `GPL-3.0` `Shell`
- 🌎 [UBOS](ubos.net/) - Linux distro that runs on indie boxes (personal servers and IoT devices). Single-command installation and management of apps - Jenkins, Mediawiki, Owncloud, WordPress, etc., and other features. `GPL-3.0` `Perl`
- 🌎 [Websoft9](www.websoft9.com) `⚠` - GitOps-driven, multi-application hosting for cloud servers and home servers, one-click deployment of 200+ open source apps.  🌎 [Demo](www.websoft9.com/demo), <b><code>&nbsp;&nbsp;1655⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;246🍴</code></b> [Source Code](https://github.com/websoft9/websoft9)), 🌎 [Clients](www.websoft9.com/apps)) `LGPL-3.0` `Shell/Python`
- 🌎 [WikiSuite](wikisuite.org) - The most comprehensive and integrated Free / Libre / Open Source enterprise software suite.  🌎 [Source Code](wikisuite.org/Source-Code)) `GPL-3.0/LGPL-2.1/Apache-2.0/MPL-2.0/MPL-1.1/MIT/AGPL-3.0` `Shell/Perl/deb`
- 🌎 [xsrv](xsrv.readthedocs.io/) - Install and manage self-hosted services/applications, on your own server(s). (<b><code>&nbsp;&nbsp;&nbsp;353⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Source Code](https://github.com/nodiscc/xsrv))) `GPL-3.0` `Ansible/Shell`
- 🌎 [YunoHost](yunohost.org/) - Server operating system aiming to make self-hosting accessible to everyone.  🌎 [Demo](yunohost.org/#/try), [Source Code](https://github.com/YunoHost)) `AGPL-3.0` `Python/Shell`


### Software Development

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Software development](en.wikipedia.org/wiki/Software_development) is the process of conceiving, specifying, designing, programming, documenting, testing, and bug fixing involved in creating and maintaining applications, frameworks, or other software components.

**Please visit [Software Development - API Management](#software-development---api-management), [Software Development - Continuous Integration & Deployment](#software-development---continuous-integration--deployment), [Software Development - FaaS & Serverless](#software-development---faas--serverless), [Software Development - IDE & Tools](#software-development---ide--tools), [Software Development - Localization](#software-development---localization), [Software Development - Low Code](#software-development---low-code), [Software Development - Project Management](#software-development---project-management), [Software Development - Testing](#software-development---testing), [Software Development - Feature Toggle](#software-development---feature-toggle)**



### Software Development - API Management

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [API management](en.wikipedia.org/wiki/API_management) is the process of creating and publishing 🌎 [application programming interfaces (APIs)](en.wikipedia.org/wiki/API), enforcing their usage policies, controlling access, nurturing the subscriber community, collecting and analyzing usage statistics, and reporting on performance. 

- 🌎 [DreamFactory](www.dreamfactory.com/) - Turns any SQL/NoSQL/Structured data into Restful API. (<b><code>&nbsp;&nbsp;1597⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;321🍴</code></b> [Source Code](https://github.com/dreamfactorysoftware/dreamfactory))) `Apache-2.0` `PHP/Docker/K8S`
- 🌎 [form.io](form.io) - A REST API building platform that utilizes a drag & drop form builder, and is application framework agnostic. Contains open source and enterprise version.  🌎 [Demo](portal.form.io), [Source Code](https://github.com/formio)) `MIT` `Nodejs/Docker`
- 🌎 [Fusio](www.fusio-project.org/) - Open-source API management platform which helps to build and manage REST APIs.  🌎 [Demo](fusio-project.org/demo), <b><code>&nbsp;&nbsp;1958⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;232🍴</code></b> [Source Code](https://github.com/apioo/fusio))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Graphweaver](graphweaver.com/) - Turn multiple data sources into a single GraphQL API. (<b><code>&nbsp;&nbsp;&nbsp;513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Source Code](https://github.com/exogee-technology/graphweaver))) `MIT` `Nodejs`
- 🌎 [Hasura](hasura.io) - Fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also trigger webhooks on database events. (<b><code>&nbsp;31466⭐</code></b> <b><code>&nbsp;&nbsp;2797🍴</code></b> [Source Code](https://github.com/hasura/graphql-engine))) `Apache-2.0` `Haskell/Docker/K8S`
- 🌎 [Hoppscotch Community Edition](hoppscotch.io) - A free, fast and beautiful API request builder. (<b><code>&nbsp;71119⭐</code></b> <b><code>&nbsp;&nbsp;4868🍴</code></b> [Source Code](https://github.com/hoppscotch/hoppscotch))) `MIT` `Nodejs/Docker`
- 🌎 [Kong](konghq.com/kong/) - The World's Most Popular Open Source Microservice API Gateway and Platform. (<b><code>&nbsp;40576⭐</code></b> <b><code>&nbsp;&nbsp;4904🍴</code></b> [Source Code](https://github.com/Kong/kong))) `Apache-2.0` `Lua/Docker/K8S/deb`
- 🌎 [Lura](luraproject.org/) - Open source High-Performance API Gateway. (<b><code>&nbsp;&nbsp;6514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;565🍴</code></b> [Source Code](https://github.com/luraproject/lura))) `Apache-2.0` `Go`
- 🌎 [Opik](www.comet.com/site/products/opik/) `⚠` - Evaluate, test, and ship LLM applications with a suite of observability tools to calibrate language model outputs across your dev and production lifecycle. (<b><code>&nbsp;&nbsp;6420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;455🍴</code></b> [Source Code](https://github.com/comet-ml/opik))) `Apache-2.0` `Docker/Python`
- 🌎 [Panora](panora.dev) `⚠` - An API to add an integration catalog to your SaaS product in minutes (alternative to Merge.dev). (<b><code>&nbsp;&nbsp;&nbsp;989⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;199🍴</code></b> [Source Code](https://github.com/panoratech/Panora))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Para](paraio.org) - Flexible and modular backend framework/server for object persistence, API development and authentication. (<b><code>&nbsp;&nbsp;&nbsp;537⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [Source Code](https://github.com/erudika/para))) `Apache-2.0` `Java/Docker`
- 🌎 [Svix](svix.com) - Open-source webhooks as a service that makes it super easy for API providers to send webhooks. (<b><code>&nbsp;&nbsp;2637⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [Source Code](https://github.com/svix/svix-webhooks))) `MIT` `Docker/Rust`
- 🌎 [Tyk](tyk.io) - Fast and scalable open source API Gateway. Out of the box, Tyk offers an API Management Platform with an API Gateway, API Analytics, Developer Portal and API Management Dashboard. (<b><code>&nbsp;10034⭐</code></b> <b><code>&nbsp;&nbsp;1111🍴</code></b> [Source Code](https://github.com/TykTechnologies/tyk))) `MPL-2.0` `Go/Docker/K8S`
- 🌎 [Yaade](docs.yaade.io/) - Yaade is an open-source, self-hosted, collaborative API development environment. (<b><code>&nbsp;&nbsp;1700⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [Source Code](https://github.com/EsperoTech/yaade))) `MIT` `Docker`


### Software Development - Continuous Integration & Deployment

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Continuous integration](en.wikipedia.org/wiki/Continuous_integration) and 🌎 [Continuous deployment](en.wikipedia.org/wiki/Continuous_deployment) software and tools.

**Please visit <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/Continuous Integration & Continuous Deployment](https://github.com/awesome-foss/awesome-sysadmin#continuous-integration--continuous-deployment))**

_Related: [Automation](#automation)_



### Software Development - FaaS & Serverless

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Serverless computing](en.wikipedia.org/wiki/Serverless_computing), 🌎 [Function as a Service (FaaS)](en.wikipedia.org/wiki/Function_as_a_service) and 🌎 [Platform as a Service (Paas)](en.wikipedia.org/wiki/Platform_as_a_service) management software.

**Please visit <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/PaaS](https://github.com/awesome-foss/awesome-sysadmin#paas))**



### Software Development - Feature Toggle

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [feature toggle](en.wikipedia.org/wiki/Feature_toggle) in software development provides an alternative to maintaining multiple feature branches in source code.

_Related: [Software Development - IDE & Tools](#software-development---ide--tools)_

- 🌎 [Featbit](www.featbit.co/) - Enterprise-grade feature flag platform that you can self-host. (<b><code>&nbsp;&nbsp;1509⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Source Code](https://github.com/featbit/featbit))) `MIT` `Docker/K8S`
- 🌎 [Flagsmith](flagsmith.com) - Dashboard, API and SDKs for adding Feature Flags to your applications (alternative to LaunchDarkly). (<b><code>&nbsp;&nbsp;5578⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;433🍴</code></b> [Source Code](https://github.com/flagsmith/flagsmith))) `BSD-3-Clause` `Docker/K8S`
- 🌎 [Flipt](flipt.io) - Feature flag solution with support for multiple data backends (alternative to LaunchDarkly).  🌎 [Demo](try.flipt.io), <b><code>&nbsp;&nbsp;4277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;233🍴</code></b> [Source Code](https://github.com/flipt-io/flipt))) `GPL-3.0` `Docker/K8S/Go`
- 🌎 [GO Feature Flag](gofeatureflag.org) - Simple, complete, and lightweight feature flag solution (alternative to LaunchDarkly). (<b><code>&nbsp;&nbsp;1616⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [Source Code](https://github.com/thomaspoignant/go-feature-flag))) `MIT` `Go`


### Software Development - IDE & Tools

**[`^        back to top        ^`](#awesome-selfhosted)**

An 🌎 [integrated development environment (IDE)](en.wikipedia.org/wiki/Integrated_development_environment) is a software application that provides comprehensive facilities to computer programmers for software development.

_Related: [Software Development - Low Code](#software-development---low-code)_

- 🌎 [Atheos](www.atheos.io) - Web-based IDE framework with a small footprint and minimal requirements, continued from Codiad. (<b><code>&nbsp;&nbsp;&nbsp;529⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Source Code](https://github.com/Atheos/Atheos))) `MIT` `PHP/Docker`
- <b><code>&nbsp;70920⭐</code></b> <b><code>&nbsp;&nbsp;5863🍴</code></b> [code-server](https://github.com/coder/code-server)) - VS Code in the browser, hosted on a remote server. `MIT` `Nodejs/Docker`
- 🌎 [Coder](coder.com/) - Remote development machines on your own infrastructure. (<b><code>&nbsp;&nbsp;9460⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;846🍴</code></b> [Source Code](https://github.com/coder/coder))) `AGPL-3.0` `Go/Docker/K8S/deb`
- 🌎 [Eclipse Che](www.eclipse.org/che/) - Open source workspace server and cloud IDE. (<b><code>&nbsp;&nbsp;7029⭐</code></b> <b><code>&nbsp;&nbsp;1185🍴</code></b> [Source Code](https://github.com/eclipse/che))) `EPL-1.0` `Docker/Java`
- <b><code>&nbsp;&nbsp;&nbsp;121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [HttPlaceholder](https://github.com/dukeofharen/httplaceholder)) - Quickly mock away any webservice using HttPlaceholder. HttPlaceholder lets you specify what the request should look like and what response needs to be returned. `MIT` `C#`
- 🌎 [Judge0 CE](judge0.com) - Open source API to compile and run source code. (<b><code>&nbsp;&nbsp;3109⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;548🍴</code></b> [Source Code](https://github.com/judge0/judge0))) `GPL-3.0` `Docker`
- 🌎 [JupyterLab](jupyterlab.readthedocs.io/en/stable/) - Web-based environment for interactive and reproducible computing.  🌎 [Demo](mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/jupyterlab/jupyterlab/))) `BSD-3-Clause` `Python/Docker`
- 🌎 [Langfuse](langfuse.com) - LLM engineering platform for model tracing, prompt management, and application evaluation. Langfuse helps teams collaboratively debug, analyze, and iterate on their LLM applications such as chatbots or AI agents.  🌎 [Demo](langfuse.com/docs/demo), <b><code>&nbsp;10332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;946🍴</code></b> [Source Code](https://github.com/langfuse/langfuse)), 🌎 [Clients](langfuse.com/docs/integrations/overview)) `MIT` `Docker`
- 🌎 [LiveCodes](livecodes.io/docs/features/self-hosting) `⚠` - A feature-rich client-side code playground for React, Vue, Svelte, Solid, Typescript, Python, Go, Ruby, PHP and 90+ other languages.  🌎 [Demo](livecodes.io), <b><code>&nbsp;&nbsp;&nbsp;945⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [Source Code](https://github.com/live-codes/livecodes))) `MIT` `Nodejs`
- 🌎 [Lowdefy](www.lowdefy.com/) - Build internal tools, BI dashboards, admin panels, CRUD apps and workflows in minutes using YAML / JSON on an self-hosted, open-source platform. Connect to your data sources, host via Serverless, Netlify or Docker. (<b><code>&nbsp;&nbsp;2779⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [Source Code](https://github.com/lowdefy/lowdefy))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [RStudio Server](www.rstudio.com/products/rstudio/#Server) - Web browser based IDE for R. (<b><code>&nbsp;&nbsp;4769⭐</code></b> <b><code>&nbsp;&nbsp;1114🍴</code></b> [Source Code](https://github.com/rstudio/rstudio))) `AGPL-3.0` `Java/C++`
- 🌎 [Wakapi](wakapi.dev/) - Tracking tool for coding statistics, compatible with WakaTime. (<b><code>&nbsp;&nbsp;3233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [Source Code](https://github.com/muety/wakapi))) `GPL-3.0` `Go/Docker`


### Software Development - Localization

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Localization](en.wikipedia.org/wiki/Internationalization_and_localization) is the process of adapting code and software to other languages.

- 🌎 [Accent](www.accent.reviews/) - Developer-oriented translation tool. (<b><code>&nbsp;&nbsp;1386⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [Source Code](https://github.com/mirego/accent))) `BSD-3-Clause` `Elixir/Docker`
- 🌎 [Tolgee](tolgee.io) - Developer & translator friendly web-based localization platform enabling users to translate directly in the app they develop. (<b><code>&nbsp;&nbsp;2725⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;245🍴</code></b> [Source Code](https://github.com/tolgee/tolgee-platform))) `Apache-2.0` `Docker/Java`
- 🌎 [Traduora](traduora.co) - Translation management platform for teams. (<b><code>&nbsp;&nbsp;2041⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;210🍴</code></b> [Source Code](https://github.com/ever-co/ever-traduora))) `AGPL-3.0` `Docker/K8S/Nodejs`
- 🌎 [Weblate](weblate.org) - Web-based translation tool with tight version control integration.  🌎 [Demo](demo.weblate.org), <b><code>&nbsp;&nbsp;5012⭐</code></b> <b><code>&nbsp;&nbsp;1095🍴</code></b> [Source Code](https://github.com/WeblateOrg/weblate))) `GPL-3.0` `Python/Docker/K8S`


### Software Development - Low Code

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [low-code](en.wikipedia.org/wiki/Low-code_development_platform) development platform (LCDP) provides a development environment used to create application software through a graphical user interface.

_Related: [Software Development - IDE & Tools](#software-development---ide--tools)_

- 🌎 [Appsmith](www.appsmith.com/) - Build admin panels, CRUD apps and workflows. Build everything you need, 10x faster. (<b><code>&nbsp;36632⭐</code></b> <b><code>&nbsp;&nbsp;3984🍴</code></b> [Source Code](https://github.com/appsmithorg/appsmith))) `Apache-2.0` `Java/Docker/K8S`
- 🌎 [Appwrite](appwrite.io) - End to end backend server for web, native, and mobile developers 🚀. (<b><code>&nbsp;48126⭐</code></b> <b><code>&nbsp;&nbsp;4262🍴</code></b> [Source Code](https://github.com/appwrite/appwrite))) `BSD-3-Clause` `Docker`
- <b><code>&nbsp;&nbsp;1860⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [Dashpress](https://github.com/dashpresshq/dashpress)) - Generate fully functional admin apps in seconds from your database information, with a single command. `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Manifest](manifest.build) - A complete backend that fits into 1 YAML file.  🌎 [Demo](manifest.new), <b><code>&nbsp;&nbsp;2441⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [Source Code](https://github.com/mnfst/manifest))) `MIT` `Nodejs`
- 🌎 [Motor Admin](www.getmotoradmin.com/) - No-code admin panel and business intelligence software - search, create, update, and delete data entries, create custom actions, and build reports. (<b><code>&nbsp;&nbsp;2106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [Source Code](https://github.com/motor-admin/motor-admin))) `AGPL-3.0` `Ruby/Docker`
- 🌎 [PocketBase](pocketbase.io/) - Open Source backend for your next SaaS and Mobile app in 1 file. (<b><code>&nbsp;45331⭐</code></b> <b><code>&nbsp;&nbsp;2217🍴</code></b> [Source Code](https://github.com/pocketbase/pocketbase))) `MIT` `Go/Docker`
- 🌎 [SQLPage](sql-page.com) - SQL-only dynamic website builder. (<b><code>&nbsp;&nbsp;2039⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;126🍴</code></b> [Source Code](https://github.com/sqlpage/SQLPage))) `MIT` `Rust/Docker`
- 🌎 [ToolJet](tooljet.io/) - Low-code framework to build & deploy internal tools with minimal engineering effort (alternative to Retool & Mendix). (<b><code>&nbsp;35352⭐</code></b> <b><code>&nbsp;&nbsp;4546🍴</code></b> [Source Code](https://github.com/ToolJet/ToolJet))) `GPL-3.0` `Nodejs/Docker/K8S`
- 🌎 [TrailBase](trailbase.io/) - Open, sub-millisecond, single-executable FireBase alternative with type-safe REST & realtime APIs, built-in JS/TS runtime, auth & admin UI.  🌎 [Demo](demo.trailbase.io), <b><code>&nbsp;&nbsp;1890⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Source Code](https://github.com/trailbaseio/trailbase))) `OSL-3.0` `Rust/Docker`


### Software Development - Project Management

**[`^        back to top        ^`](#awesome-selfhosted)**

Tools and software for 🌎 [software project management](en.wikipedia.org/wiki/Software_project_management).

_Related: [Ticketing](#ticketing), [Task Management & To-do Lists](#task-management--to-do-lists)_

- 🌎 [Cgit](git.zx2c4.com/cgit/about/) - A fast lightweight web interface for git repositories.  🌎 [Source Code](git.zx2c4.com/cgit/tree/)) `GPL-2.0` `C`
- 🌎 [Forgejo](forgejo.org) - A lightweight software forge focused on scaling, federation, and privacy (fork of Gitea).  🌎 [Demo](next.forgejo.org), 🌎 [Source Code](codeberg.org/forgejo/forgejo/), 🌎 [Clients](codeberg.org/forgejo-contrib/delightful-forgejo)) `MIT` `Docker/Go`
- 🌎 [Fossil](www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - Distributed version control system featuring wiki and bug tracker. `BSD-2-Clause-FreeBSD` `C`
- 🌎 [Gerrit](www.gerritcodereview.com/) - A code review and project management tool for Git based projects. (<b><code>&nbsp;&nbsp;1039⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [Source Code](https://github.com/GerritCodeReview/gerrit))) `Apache-2.0` `Java/Docker`
- 🌎 [Gitblit](www.gitblit.com/) - Pure Java stack for managing, viewing, and serving Git repositories. (<b><code>&nbsp;&nbsp;2307⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;672🍴</code></b> [Source Code](https://github.com/gitblit-org/gitblit))) `Apache-2.0` `Java`
- 🌎 [gitbucket](gitbucket.github.io/gitbucket-news/) - Easily installable GitHub clone powered by Scala. (<b><code>&nbsp;&nbsp;9233⭐</code></b> <b><code>&nbsp;&nbsp;1255🍴</code></b> [Source Code](https://github.com/gitbucket/gitbucket))) `Apache-2.0` `Scala/Java`
- 🌎 [Gitea](gitea.com) - Git with a cup of tea! Painless self-hosted all-in-one software development service, including Git hosting, code review, team collaboration, package registry and CI/CD.  🌎 [Demo](demo.gitea.com), <b><code>&nbsp;48079⭐</code></b> <b><code>&nbsp;&nbsp;5738🍴</code></b> [Source Code](https://github.com/go-gitea/gitea))) `MIT` `Go/Docker/K8S`
- 🌎 [GitLab](about.gitlab.com) - Self Hosted Git repository management, code reviews, issue tracking, activity feeds and wikis.  🌎 [Demo](gitlab.com/), 🌎 [Source Code](gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby/deb/Docker/K8S`
- 🌎 [Gitolite](gitolite.com/gitolite/index.html) - Gitolite allows you to setup git hosting on a central server, with fine-grained access control and many more powerful features. (<b><code>&nbsp;&nbsp;8459⭐</code></b> <b><code>&nbsp;&nbsp;1005🍴</code></b> [Source Code](https://github.com/sitaramc/gitolite))) `GPL-2.0` `Perl`
- 🌎 [Gogs](gogs.io/) - Painless self-hosted Git Service written in Go. (<b><code>&nbsp;46196⭐</code></b> <b><code>&nbsp;&nbsp;5021🍴</code></b> [Source Code](https://github.com/gogs/gogs))) `MIT` `Go`
- 🌎 [Huly](huly.io) - All-in-One Project Management Platform (alternative to Linear, Jira, Slack, Notion, Motion).  🌎 [Demo](app.huly.io), <b><code>&nbsp;20175⭐</code></b> <b><code>&nbsp;&nbsp;1307🍴</code></b> [Source Code](https://github.com/hcengineering/platform))) `EPL-2.0` `Docker/K8S/Nodejs`
- 🌎 [Kallithea](kallithea-scm.org/) - Source code management system that supports two leading version control systems, Mercurial and Git, with a web interface.  🌎 [Source Code](kallithea-scm.org/repos/kallithea)) `GPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;688⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [Klaus](https://github.com/jonashaag/klaus)) - Simple, easy-to-set-up Git web viewer that Just Works. `ISC` `Python/Docker`
- 🌎 [Leantime](leantime.io) - Leantime is a lean project management system for small teams and startups helping to manage projects from ideation through delivery. (<b><code>&nbsp;&nbsp;5241⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;628🍴</code></b> [Source Code](https://github.com/leantime/leantime))) `GPL-2.0` `PHP/Docker`
- 🌎 [Mindwendel](www.mindwendel.com/) - Brainstorm and upvote ideas and thoughts within your team.  🌎 [Demo](www.mindwendel.com), <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Source Code](https://github.com/b310-digital/mindwendel))) `AGPL-3.0` `Docker/Elixir`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [minimal-git-server](https://github.com/mcarbonne/minimal-git-server)) - A lightweight and minimal self-hosted git server with a basic CLI to manage repositories, supporting multiple accounts and running in a container. `MIT` `Docker`
- 🌎 [Octobox](octobox.io/) `⚠` - Take back control of your GitHub Notifications. (<b><code>&nbsp;&nbsp;4394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;347🍴</code></b> [Source Code](https://github.com/octobox/octobox))) `AGPL-3.0` `Ruby/Docker`
- 🌎 [OneDev](onedev.io/) - All-In-One DevOps Platform. With Git Management, Issue Tracking, and CI/CD. Simple yet Powerful.  🌎 [Source Code](code.onedev.io/projects/160)) `MIT` `Java/Docker/K8S`
- 🌎 [OpenProject](www.openproject.org) - OpenProject is a web-based project management system. (<b><code>&nbsp;10372⭐</code></b> <b><code>&nbsp;&nbsp;2536🍴</code></b> [Source Code](https://github.com/opf/openproject))) `GPL-3.0` `Ruby/deb/Docker`
- 🌎 [Pagure](pagure.io/pagure) - A lightweight, powerful, and flexible git-centric forge with features laying the foundation for federated and decentralized development.  🌎 [Demo](pagure.io/)) `GPL-2.0` `Docker/Python/deb`
- 🌎 [Phorge](we.phorge.it/) - Phorge is an open source, community driven platform for collaborating, managing, organizing and reviewing software development projects.  🌎 [Source Code](we.phorge.it/source/phorge/)) `Apache-2.0` `PHP`
- 🌎 [Plane](plane.so) - Helps you track your issues, epics, and product roadmaps in the simplest way possible (alternative to JIRA, Linear and Height).  🌎 [Demo](app.plane.so), <b><code>&nbsp;35278⭐</code></b> <b><code>&nbsp;&nbsp;2174🍴</code></b> [Source Code](https://github.com/makeplane/plane))) `Apache-2.0` `Docker`
- 🌎 [ProjeQtOr](www.projeqtor.org/) - A complete, mature, multi-user project management system with extensive functionality for all phases of a project.  🌎 [Demo](demo.projeqtor.org/), 🌎 [Source Code](sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
- 🌎 [Redmine](www.redmine.org/) - Redmine is a flexible project management web application.  🌎 [Source Code](svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- 🌎 [Review Board](www.reviewboard.org/) - Extensible and friendly code review tool for projects and companies of all sizes.  🌎 [Demo](demo.reviewboard.org/), <b><code>&nbsp;&nbsp;1606⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;431🍴</code></b> [Source Code](https://github.com/reviewboard/reviewboard))) `MIT` `Python/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [rgit](https://github.com/w4/rgit)) - An ultra-fast & lightweight cgit clone. `WTFPL` `Rust/Docker`
- 🌎 [RhodeCode](rhodecode.com/) - RhodeCode is an open source platform for software development teams. It unifies and simplifies repository management for Git, Subversion, and Mercurial.  🌎 [Source Code](code.rhodecode.com/)) `AGPL-3.0` `Python`
- 🌎 [Rukovoditel](www.rukovoditel.net/) - Configurable open source project management, web-based application.  🌎 [Source Code](www.rukovoditel.net/download.php)) `GPL-2.0` `PHP`
- 🌎 [SCM Manager](www.scm-manager.org/) - The easiest way to share and manage your Git, Mercurial and Subversion repositories over http. (<b><code>&nbsp;&nbsp;&nbsp;141⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Source Code](https://github.com/scm-manager/scm-manager))) `BSD-3-Clause` `Java/deb/Docker/K8S`
- 🌎 [Smederee](smeder.ee) - A frugal platform which is dedicated to help people build great software together leveraging the power of the Darcs version control system.  🌎 [Source Code](smeder.ee/~jan0sch/smederee)) `AGPL-3.0` `Scala`
- 🌎 [Sourcehut](sourcehut.org/) - A full web git interface with no javascript.  🌎 [Demo](sr.ht/), 🌎 [Source Code](git.sr.ht/~sircmpwn/git.sr.ht/tree)) `GPL-2.0` `Go`
- 🌎 [Taiga](www.taiga.io/) - Agile Project Management Tool based on the Kanban and Scrum methods. ([Source Code](https://github.com/kaleidos-ventures)) `MPL-2.0` `Docker/Python/Nodejs`
- 🌎 [Titra](titra.io/) - Time-tracking solution for freelancers and small teams. (<b><code>&nbsp;&nbsp;&nbsp;423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Source Code](https://github.com/kromitgmbh/titra))) `GPL-3.0` `Javascript/Docker`
- 🌎 [Trac](trac.edgewall.org/) - Trac is an enhanced wiki and issue tracking system for software development projects. `BSD-3-Clause` `Python/deb`
- 🌎 [Traq](traq.io/) - Project management and issue tracking system written in PHP. (<b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Source Code](https://github.com/nirix/traq))) `GPL-3.0` `PHP/Nodejs`
- 🌎 [Tuleap](www.tuleap.org/) - Tuleap is a libre suite to plan, track, code and collaborate on software projects.  🌎 [Source Code](tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- 🌎 [UVDesk](www.uvdesk.com/) - UVDesk community is a service oriented, event driven extensible opensource helpdesk system that can be used by your organization to provide efficient support to your clients effortlessly whichever way you imagine.  🌎 [Demo](demo.uvdesk.com/), <b><code>&nbsp;11091⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;498🍴</code></b> [Source Code](https://github.com/uvdesk/community-skeleton))) `MIT` `PHP`
- 🌎 [ZenTao](www.zentao.pm/) - An agile(scrum) project management system/tool. (<b><code>&nbsp;&nbsp;1395⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;344🍴</code></b> [Source Code](https://github.com/easysoft/zentaopms))) `AGPL-3.0` `PHP`


### Software Development - Testing

**[`^        back to top        ^`](#awesome-selfhosted)**

Tools and software for 🌎 [software testing](en.wikipedia.org/wiki/Software_testing).

- 🌎 [Bencher](bencher.dev/) - Suite of continuous benchmarking tools designed to catch performance regressions in CI. (<b><code>&nbsp;&nbsp;&nbsp;662⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Source Code](https://github.com/bencherdev/bencher))) `MIT/Apache-2.0` `Rust`
- 🌎 [Sorry Cypress](sorry-cypress.dev) - Alternative open-source dashboard for the Cypress browser automation framework, featuring unlimited parallelization, recording and debugging of tests. (<b><code>&nbsp;&nbsp;2747⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;295🍴</code></b> [Source Code](https://github.com/sorry-cypress/sorry-cypress))) `MIT` `Docker/K8S`
- <b><code>&nbsp;&nbsp;&nbsp;243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [WebHook Tester](https://github.com/tarampampam/webhook-tester)) - Powerful tool for testing WebHooks and more. `MIT` `Docker/Go/deb/K8S`


### Static Site Generators

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Static site generators](en.wikipedia.org/wiki/Web_template_system#Static_site_generators) generate full static HTML websites based on raw data, plain text files and a set of templates. 

**Please visit 🌎 [staticsitegenerators.net](staticsitegenerators.net), 🌎 [staticgen.com](www.staticgen.com)**

_Related: [Blogging Platforms](#blogging-platforms), [Photo Galleries](#photo-galleries), [Content Management Systems (CMS)](#content-management-systems-cms)_



### Status / Uptime pages

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Uptime](en.wikipedia.org/wiki/Uptime) is a measure of system reliability, expressed as the percentage of time a machine, typically a computer, has been working and available. 

_Related: [Monitoring](#monitoring)_

- 🌎 [cState](cstate.netlify.app/) - Static status page for hyperfast Hugo. Clean design, minimal JS, super light HTML/CSS, high customization, optional admin panel, read-only API, IE8+. Best used with Netlify, Docker.  🌎 [Demo](cstate.mnts.lt/), <b><code>&nbsp;&nbsp;2668⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;239🍴</code></b> [Source Code](https://github.com/cstate/cstate))) `MIT` `Go`
- <b><code>&nbsp;&nbsp;7322⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;487🍴</code></b> [Gatus](https://github.com/TwiN/gatus)) - Automated service health dashboard.  🌎 [Demo](status.twin.sh)) `Apache-2.0` `Docker/K8S`
- 🌎 [kener](kener.ing/) - Status page with incident management, easy to use and customize.  🌎 [Demo](kener.ing/), <b><code>&nbsp;&nbsp;3672⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;167🍴</code></b> [Source Code](https://github.com/rajnandan1/kener))) `MIT` `Nodejs/Docker`
- 🌎 [StatPing.ng](statping-ng.github.io/) - An easy to use Status Page for your websites and applications. Statping will automatically fetch the application and render a beautiful status page with tons of features for you to build an even better status page. (<b><code>&nbsp;&nbsp;1672⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;163🍴</code></b> [Source Code](https://github.com/statping-ng/statping-ng))) `GPL-3.0` `Docker/Go`
- 🌎 [Uptime Kuma](uptime.kuma.pet/) - Self-hosted website monitoring tool like "Uptime Robot".  🌎 [Demo](demo.kuma.pet), <b><code>&nbsp;67115⭐</code></b> <b><code>&nbsp;&nbsp;5905🍴</code></b> [Source Code](https://github.com/louislam/uptime-kuma))) `MIT` `Docker/Nodejs`


### Task Management & To-do Lists

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Task management](en.wikipedia.org/wiki/Task_management#Task_management_software) software.

_Related: [Software Development - Project Management](#software-development---project-management), [Ticketing](#ticketing)_

- 🌎 [4ga Boards](4gaboards.com) - Straightforward realtime kanban boards management for intuitive task tracking. Featuring an elegant dark mode, collapsible todo lists, and multitasking tools to supercharge your team's productivity.  🌎 [Demo](demo.4gaboards.com), <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Source Code](https://github.com/RARgames/4gaBoards))) `MIT` `Nodejs/Docker/K8S`
- 🌎 [AppFlowy](appflowy.io/) - Build detailed lists of to-do’s for different projects while tracking the status of each one. Open Source Notion Alternative. (<b><code>&nbsp;62080⭐</code></b> <b><code>&nbsp;&nbsp;4172🍴</code></b> [Source Code](https://github.com/AppFlowy-IO/appflowy))) `AGPL-3.0` `Rust/Dart/Docker`
- 🌎 [Donetick](donetick.com) - Task and chore management tool for personal and family use, with advanced scheduling, flexible assignment, and group sharing capabilities, detailed history, automation via API, simple and modern design.  🌎 [Demo](app.donetick.com/), <b><code>&nbsp;&nbsp;&nbsp;618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Source Code](https://github.com/donetick/donetick))) `AGPL-3.0` `Go/Docker`
- 🌎 [Focalboard](www.focalboard.com/) - Define, organize, track and manage work across individuals and teams (alternative to Trello, Notion, and Asana). (<b><code>&nbsp;23178⭐</code></b> <b><code>&nbsp;&nbsp;2123🍴</code></b> [Source Code](https://github.com/mattermost/focalboard)), 🌎 [Clients](www.focalboard.com/download/personal-edition/desktop/)) `MIT/AGPL-3.0/Apache-2.0` `Nodejs/Go/Docker`
- 🌎 [Kanboard](kanboard.org/) - Simple and open source visual task board. (<b><code>&nbsp;&nbsp;8775⭐</code></b> <b><code>&nbsp;&nbsp;1852🍴</code></b> [Source Code](https://github.com/kanboard/kanboard))) `MIT` `PHP`
- 🌎 [myTinyTodo](www.mytinytodo.net/) - Simple way to manage your todo list in AJAX style. Uses PHP, jQuery, SQLite/MySQL. GTD compliant.  🌎 [Demo](www.mytinytodo.net/demo/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/maxpozdeev/mytinytodo/))) `GPL-2.0` `PHP`
- <b><code>&nbsp;&nbsp;4000⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;259🍴</code></b> [Nullboard](https://github.com/apankrat/nullboard)) - Single-page minimalist kanban board; compact, highly readable and quick to use. `BSD-2-Clause` `Javascript`
- <b><code>&nbsp;&nbsp;&nbsp;117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Our Shopping List](https://github.com/nanawel/our-shopping-list)) - Simple shared list application. Typical uses include shopping lists of course, and any other small todo-list that needs to be used collaboratively.  🌎 [Demo](osl.lanterne-rouge.info/)) `AGPL-3.0` `Docker`
- 🌎 [Planka](planka.app/) - Realtime kanban board for workgroups (alternative to Trello).  🌎 [Demo](plankanban.github.io/planka/#/), <b><code>&nbsp;&nbsp;8977⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;886🍴</code></b> [Source Code](https://github.com/plankanban/planka))) `AGPL-3.0` `Nodejs/Docker/K8S`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Task Keeper](https://github.com/nymanjens/piga)) - List editor for power users, backed by a self-hosted server. `Apache-2.0` `Scala`
- <b><code>&nbsp;&nbsp;1026⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Tasks.md](https://github.com/BaldissaraMatheus/Tasks.md)) - A self-hosted, file based task management board that supports Markdown syntax. `MIT` `Docker`
- 🌎 [Taskwarrior](taskwarrior.org/) - Taskwarrior is Free and Open Source Software that manages your TODO list from your command line. It is flexible, fast, efficient, and unobtrusive. It does its job then gets out of your way.  🌎 [Source Code](taskwarrior.org/download/#git)) `MIT` `C++`
- 🌎 [Tegon](tegon.ai) `⚠` - Dev-first issue tracking tool (alternative to Jira, Linear). (<b><code>&nbsp;&nbsp;1793⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [Source Code](https://github.com/tegonhq/tegon))) `AGPL-3.0` `Docker`
- 🌎 [Tracks](www.getontracks.org/) - Web-based application to help you implement David Allen’s 🌎 [Getting Things Done™](en.wikipedia.org/wiki/Getting_Things_Done) methodology. (<b><code>&nbsp;&nbsp;1201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;538🍴</code></b> [Source Code](https://github.com/TracksApp/tracks))) `GPL-2.0` `Ruby`
- 🌎 [Vikunja](vikunja.io/) - The to-do app to organize your life.  🌎 [Demo](try.vikunja.io/login), 🌎 [Source Code](kolaente.dev/vikunja/)) `GPL-3.0` `Go`
- 🌎 [Wekan](wekan.github.io/) - Open-source Trello-like kanban. (<b><code>&nbsp;20017⭐</code></b> <b><code>&nbsp;&nbsp;2887🍴</code></b> [Source Code](https://github.com/wekan/wekan))) `MIT` `Nodejs`


### Ticketing

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Helpdesk](en.wikipedia.org/wiki/Help_desk_software), 🌎 [bug](en.wikipedia.org/wiki/Bug_tracking_system) and 🌎 [issue](en.wikipedia.org/wiki/Issue_tracking_system) tracking software to help the tracking of user requests, bugs and missing features.

_Related: [Task Management & To-do Lists](#task-management--to-do-lists), [Software Development - Project Management](#software-development---project-management)_

- 🌎 [Bugzilla](www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project. (<b><code>&nbsp;&nbsp;&nbsp;725⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [Source Code](https://github.com/bugzilla/bugzilla))) `MPL-2.0` `Perl`
- <b><code>&nbsp;&nbsp;3401⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;529🍴</code></b> [FreeScout](https://github.com/freescout-helpdesk/freescout)) - Open source clone of Help Scout: email-based customer support application, help desk and shared mailbox. `AGPL-3.0` `PHP/Docker`
- 🌎 [GlitchTip](glitchtip.com) - Open source error-tracking app. GlitchTip collects errors reported by your app.  🌎 [Source Code](gitlab.com/glitchtip/glitchtip)) `MIT` `Python/Docker/K8S`
- 🌎 [ITFlow](itflow.org) - Client IT Documentation, Ticketing, Invoicing and Accounting Web Application for MSPs (Managed Service Providers).  🌎 [Demo](demo.itflow.org), <b><code>&nbsp;&nbsp;&nbsp;677⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;177🍴</code></b> [Source Code](https://github.com/itflow-org/itflow))) `GPL-3.0` `PHP`
- 🌎 [MantisBT](www.mantisbt.org/) - Self hosted bug tracker, fits best for software development.  🌎 [Demo](www.mantisbt.org/bugs/my_view_page.php), <b><code>&nbsp;&nbsp;1690⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;728🍴</code></b> [Source Code](https://github.com/mantisbt/mantisbt))) `GPL-2.0` `PHP`
- 🌎 [OTOBO](otobo.io/en/) - Flexible web-based ticketing system used for Customer Service, Help Desk, IT Service Management.  🌎 [Demo](otobo.io/en/service-management-plattform/otobo-demo/), <b><code>&nbsp;&nbsp;&nbsp;285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Source Code](https://github.com/RotherOSS/otobo))) `GPL-3.0` `Perl/Docker`
- 🌎 [Request Tracker](www.bestpractical.com/rt/) - An enterprise-grade issue tracking system. (<b><code>&nbsp;&nbsp;1011⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;265🍴</code></b> [Source Code](https://github.com/bestpractical/rt))) `GPL-2.0` `Perl`
- 🌎 [Roundup Issue Tracker](www.roundup-tracker.org/) - A simple-to-use and -install issue-tracking system with command-line, web, REST, XML-RPC, and e-mail interfaces. Designed with flexibility in mind - not just another bug tracker.  🌎 [Source Code](www.roundup-tracker.org/code.html)) `MIT/ZPL-2.0` `Python/Docker`
- 🌎 [Trudesk](trudesk.io/) - Trudesk is an open-source help desk/ticketing solution. (<b><code>&nbsp;&nbsp;1399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;464🍴</code></b> [Source Code](https://github.com/polonel/trudesk))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [Zammad](zammad.org/) - Easy to use but powerful open-source support and ticketing system. (<b><code>&nbsp;&nbsp;4749⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;798🍴</code></b> [Source Code](https://github.com/zammad/zammad))) `AGPL-3.0` `Ruby/deb`


### Time Tracking

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Time-tracking software](en.wikipedia.org/wiki/Time-tracking_software) is a category of computer software that allows its users to record time spent on tasks or projects.

- 🌎 [ActivityWatch](activitywatch.net) - Automatically track how you spend time on your devices. (<b><code>&nbsp;13944⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;626🍴</code></b> [Source Code](https://github.com/ActivityWatch/activitywatch))) `MPL-2.0` `Python`
- <b><code>&nbsp;&nbsp;1050⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Beaver Habit Tracker](https://github.com/daya0576/beaverhabits)) - Habit tracking app to save your precious moments in your fleeting life.  🌎 [Demo](beaverhabits.com/demo)) `BSD-3-Clause` `Docker`
- 🌎 [Ever Gauzy](gauzy.co) - Open business management platform for collaborative, on-demand and sharing economies (ERP/CRM/HRM/ATS/PM).  🌎 [Demo](demo.gauzy.co), <b><code>&nbsp;&nbsp;2564⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;589🍴</code></b> [Source Code](https://github.com/ever-co/ever-gauzy))) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Kimai](www.kimai.org/) - Kimai is a free & open source timetracker. It tracks work time and prints out a summary of your activities on demand.  🌎 [Demo](www.kimai.org/demo/), <b><code>&nbsp;&nbsp;3712⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;627🍴</code></b> [Source Code](https://github.com/kimai/kimai))) `AGPL-3.0` `PHP`
- 🌎 [solidtime](www.solidtime.io) - Modern time tracking application for freelancers and agencies. (<b><code>&nbsp;&nbsp;5385⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;284🍴</code></b> [Source Code](https://github.com/solidtime-io/solidtime))) `AGPL-3.0` `Docker`
- 🌎 [TimeTagger](timetagger.app) - An open source time-tracker based on an interactive timeline and powerful reporting.  🌎 [Demo](timetagger.app/app/demo), <b><code>&nbsp;&nbsp;1344⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [Source Code](https://github.com/almarklein/timetagger))) `GPL-3.0` `Python`
- 🌎 [Traggo](traggo.net/) - Traggo is a tag-based time tracking tool. In Traggo there are no tasks, only tagged time spans. (<b><code>&nbsp;&nbsp;1347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Source Code](https://github.com/traggo/server))) `GPL-3.0` `Docker/Go`


### URL Shorteners

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [URL shortening](en.wikipedia.org/wiki/URL_shortening) is the action of shortening a 🌎 [URL](en.wikipedia.org/wiki/Uniform_Resource_Locator) to make it substantially shorter and still direct to the required page. Before hosting one, please see 🌎 [disadvantages](en.wikipedia.org/wiki/URL_shortening#Disadvantages) of URL shorteners.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [bit](https://github.com/sjdonado/bit)) - Fast, lightweight, resource-efficient, compiled URL shortener. `MIT` `Docker/Crystal`
- <b><code>&nbsp;&nbsp;&nbsp;248⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Chhoto URL](https://github.com/SinTan1729/chhoto-url)) - Simple, lightning-fast URL shortener with no bloat (fork of simply-shorten). `MIT` `Rust/Docker`
- 🌎 [clink](git.swurl.xyz/swirl/clink.git/about/) - A super-minimal link shortening service written in pure C, focusing on small executable size, portability, and ease of configuration.  🌎 [Demo](short.swurl.xyz), 🌎 [Source Code](git.swurl.xyz/swirl/clink.git)) `AGPL-3.0` `C`
- 🌎 [Flink](gitlab.com/rtraceio/web/flink) - Create QR Codes, embeddable link previews for your website and crawls/scrapes metadata.  🌎 [Demo](flink.is)) `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Just Short It!](https://github.com/miawinter98/just-short-it)) - A KISS, single-user URL shortener that runs in just one container. `MIT` `Docker`
- 🌎 [Kutt](kutt.it) - A modern URL shortener with support for custom domains and custom URLs.  🌎 [Demo](kutt.it), <b><code>&nbsp;&nbsp;9606⭐</code></b> <b><code>&nbsp;&nbsp;1218🍴</code></b> [Source Code](https://github.com/thedevs-network/kutt))) `MIT` `Nodejs/Docker`
- 🌎 [liteshort](git.ikl.sh/132ikl/liteshort) - User-friendly, actually lightweight, and configurable URL shortener. `MIT` `Python/deb`
- <b><code>&nbsp;&nbsp;&nbsp;212⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Lstu](https://github.com/ldidry/lstu)) - Lightweight URL shortener. `WTFPL` `Perl/Docker`
- 🌎 [rs-short](git.42l.fr/42l/rs-short) - A lightweight link shortener written in Rust, with features such as caching, spambot protection and phishing detection.  🌎 [Demo](s.42l.fr/)) `MPL-2.0` `Rust`
- 🌎 [Shlink](shlink.io) - URL shortener with REST API and command line interface. Includes official progressive web application and docker images. (<b><code>&nbsp;&nbsp;3783⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;300🍴</code></b> [Source Code](https://github.com/shlinkio/shlink)), 🌎 [Clients](shlink.io/apps)) `MIT` `PHP/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener)) - KISS URL shortener, public or private (with account). Minimalist and lightweight. No dependencies.  🌎 [Demo](u.azlux.fr)) `MIT` `PHP`
- 🌎 [YOURLS](yourls.org/) - YOURLS is a set of PHP scripts that will allow you to run Your Own URL Shortener. Features include password protection, URL customization, bookmarklets, statistics, API, plugins, jsonp. (<b><code>&nbsp;11134⭐</code></b> <b><code>&nbsp;&nbsp;1996🍴</code></b> [Source Code](https://github.com/YOURLS/YOURLS))) `MIT` `PHP`


### Video Surveillance

**[`^        back to top        ^`](#awesome-selfhosted)**

Video surveillance, also known as 🌎 [Closed-circuit television (CCTV)](en.wikipedia.org/wiki/Closed-circuit_television), is the use of video cameras for surveillance in areas that require additional security or ongoing monitoring.

_Related: [Media Streaming - Video Streaming](#media-streaming---video-streaming)_

- 🌎 [Bluecherry](www.bluecherrydvr.com/) - Closed-circuit television (CCTV) software application which supports IP and Analog cameras. (<b><code>&nbsp;&nbsp;&nbsp;232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [Source Code](https://github.com/bluecherrydvr/bluecherry-apps))) `GPL-2.0` `PHP`
- 🌎 [Frigate](frigate.video/) - Monitor your security cameras with locally processed AI. (<b><code>&nbsp;21982⭐</code></b> <b><code>&nbsp;&nbsp;2041🍴</code></b> [Source Code](https://github.com/blakeblackshear/frigate))) `MIT` `Docker/Python/Nodejs`
- 🌎 [SentryShot](codeberg.org/SentryShot/sentryshot) - Video surveillance management system. `GPL-2.0` `Docker/Rust`
- 🌎 [Viseron](viseron.netlify.app/) - Self-hosted, local-only NVR and AI Computer Vision software. With features such as object detection, motion detection, face recognition and more, it gives you the power to keep an eye on your home, office or any other place you want to monitor. (<b><code>&nbsp;&nbsp;1954⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [Source Code](https://github.com/roflcoopter/viseron))) `MIT` `Docker`
- 🌎 [Zoneminder](www.zoneminder.com/) - Closed-circuit television (CCTV) software application which supports IP, USB and Analog cameras. (<b><code>&nbsp;&nbsp;5417⭐</code></b> <b><code>&nbsp;&nbsp;1243🍴</code></b> [Source Code](https://github.com/ZoneMinder/ZoneMinder))) `GPL-2.0` `PHP/deb`


### VPN

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [virtual private network (VPN)](en.wikipedia.org/wiki/Virtual_private_network) extends a private network across a public network and enables users to send and receive data across shared or public networks as if their computing devices were directly connected to the private network.

**Please visit <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [awesome-sysadmin/VPN](https://github.com/awesome-foss/awesome-sysadmin#vpn))**



### Web Servers

**[`^        back to top        ^`](#awesome-selfhosted)**

Web Servers and Reverse Proxies. A 🌎 [web server](en.wikipedia.org/wiki/Web_server) is a piece of software and underlying hardware that accepts requests via 🌎 [HTTP](en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) (the network protocol created to distribute web content) or its secure variant 🌎 [HTTPS](en.wikipedia.org/wiki/HTTPS). A 🌎 [Reverse Proxy](en.wikipedia.org/wiki/Reverse_proxy) is a proxy server that appears to any client to be an ordinary web server, but in reality merely acts as an intermediary that forwards requests to one or more ordinary web servers.

_Related: [Proxy](#proxy)_

- 🌎 [Algernon](algernon.roboticoverlords.org/) - Small self-contained pure-Go web server with Lua, Markdown, HTTP/2, QUIC, Redis and PostgreSQL support. (<b><code>&nbsp;&nbsp;2894⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [Source Code](https://github.com/xyproto/algernon))) `BSD-3-Clause` `Go/Docker`
- 🌎 [Apache HTTP Server](httpd.apache.org/) - Secure, efficient and extensible server that provides HTTP services in sync with the current HTTP standards.  🌎 [Source Code](svn.apache.org/repos/asf/httpd/httpd/trunk/)) `Apache-2.0` `C/deb/Docker`
- 🌎 [BunkerWeb](www.bunkerweb.io) - Next-gen Web Application Firewall (WAF) that will protect your web services.  🌎 [Demo](demo.bunkerweb.io), <b><code>&nbsp;&nbsp;7815⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;444🍴</code></b> [Source Code](https://github.com/bunkerity/bunkerweb)), 🌎 [Clients](docs.bunkerweb.io/latest/plugins/)) `AGPL-3.0` `deb/Docker/K8S/Python`
- 🌎 [Caddy](caddyserver.com/) - Powerful, enterprise-ready, open source web server with automatic HTTPS. (<b><code>&nbsp;63402⭐</code></b> <b><code>&nbsp;&nbsp;4254🍴</code></b> [Source Code](https://github.com/caddyserver/caddy))) `Apache-2.0` `Go/deb/Docker`
- <b><code>&nbsp;&nbsp;1662⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [go-doxy](https://github.com/yusing/godoxy)) - A lightweight, simple, and  performant reverse proxy with WebUI, Docker integration, automatic shutdown/startup for container based on traffic. `MIT` `Docker/Go`
- 🌎 [HAProxy](www.haproxy.org/) - Very fast and reliable reverse-proxy offering high availability, load balancing, and proxying for TCP and HTTP-based applications.  🌎 [Source Code](git.haproxy.org/?p=haproxy.git;a=tree)) `GPL-2.0` `C/deb/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Jauth](https://github.com/Jipok/Jauth)) `⚠` - Lightweight SSL/TLS reverse proxy with authorization (via Telegram and SSH) for self-hosted apps. `GPL-3.0` `Go`
- 🌎 [Lighttpd](www.lighttpd.net/) - Secure, fast, compliant, and very flexible web server that has been optimized for high-performance environments.  🌎 [Source Code](git.lighttpd.net/lighttpd/lighttpd1.4)) `BSD-3-Clause` `C/deb/Docker`
- 🌎 [Nginx Proxy Manager](nginxproxymanager.com/) - Nginx Proxy Manager is an easy way to accomplish reverse proxying hosts with SSL termination. (<b><code>&nbsp;25598⭐</code></b> <b><code>&nbsp;&nbsp;2959🍴</code></b> [Source Code](https://github.com/NginxProxyManager/nginx-proxy-manager))) `MIT` `Nodejs/Docker`
- 🌎 [NGINX](nginx.org/en/) - HTTP and reverse proxy server, mail proxy server, and generic TCP/UDP proxy server. (<b><code>&nbsp;26573⭐</code></b> <b><code>&nbsp;&nbsp;7233🍴</code></b> [Source Code](https://github.com/nginx/nginx))) `BSD-2-Clause` `C/deb/Docker`
- 🌎 [Pomerium](www.pomerium.io) - An identity-aware reverse proxy, successor to now obsolete oauth_proxy. It inserts an OAuth step before proxying your request to the backend, so that you can safely expose your self-hosted websites to public Internet. (<b><code>&nbsp;&nbsp;4207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;293🍴</code></b> [Source Code](https://github.com/pomerium/pomerium))) `Apache-2.0` `Go`
- 🌎 [Static Web Server](static-web-server.net/) - Cross-platform, high-performance, and asynchronous web server for static file serving. (<b><code>&nbsp;&nbsp;1753⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Source Code](https://github.com/static-web-server/static-web-server))) `Apache-2.0/MIT` `Rust/Docker`
- <b><code>&nbsp;&nbsp;3199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;263🍴</code></b> [SWAG (Secure Web Application Gateway)](https://github.com/linuxserver/docker-swag)) - Nginx webserver and reverse proxy with PHP support, built-in Certbot (Let's Encrypt) client and fail2ban integration. `GPL-3.0` `Docker`
- 🌎 [Traefik](traefik.io/) - HTTP reverse proxy and load balancer that makes deploying microservices easy. (<b><code>&nbsp;54134⭐</code></b> <b><code>&nbsp;&nbsp;5292🍴</code></b> [Source Code](https://github.com/traefik/traefik))) `MIT` `Go/Docker`
- 🌎 [Varnish](varnish-cache.org/) - Web application accelerator/caching HTTP reverse proxy. (<b><code>&nbsp;&nbsp;3823⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;387🍴</code></b> [Source Code](https://github.com/varnishcache/varnish-cache))) `BSD-3-Clause` `Go/deb/Docker`


### Wikis

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [wiki](en.wikipedia.org/wiki/Wiki) is a publication collaboratively edited and managed by its own audience directly using a web browser.

_Related: [Note-taking & Editors](#note-taking--editors), [Static Site Generators](#static-site-generators), [Knowledge Management Tools](#knowledge-management-tools)_

_See also: 🌎 [Wikimatrix](www.wikimatrix.org/), 🌎 [List of wiki software - Wikipedia](en.wikipedia.org/wiki/List_of_wiki_software), 🌎 [Comparison of wiki software - Wikipedia](en.wikipedia.org/wiki/Comparison_of_wiki_software)_

- 🌎 [AmuseWiki](amusewiki.org/) - Amusewiki is based on the Emacs Muse markup, remaining mostly compatible with the original implementation. It can work as a read-only site, as a moderated wiki, or as a fully open wiki or even as a private site.  🌎 [Demo](sandbox.amusewiki.org), <b><code>&nbsp;&nbsp;&nbsp;193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Source Code](https://github.com/melmothx/amusewiki))) `GPL-1.0` `Perl/Docker`
- 🌎 [BookStack](www.bookstackapp.com/) - Organize and store information. Stores documentation in a book like fashion.  🌎 [Demo](www.bookstackapp.com/#demo), <b><code>&nbsp;16423⭐</code></b> <b><code>&nbsp;&nbsp;2045🍴</code></b> [Source Code](https://github.com/BookStackApp/BookStack))) `MIT` `PHP/Docker`
- <b><code>&nbsp;&nbsp;1858⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;572🍴</code></b> [django-wiki](https://github.com/django-wiki/django-wiki)) - Wiki system with complex functionality for simple integration and a superb interface. Store your knowledge with style: Use django models.  🌎 [Demo](demo.django-wiki.org/)) `GPL-3.0` `Python`
- 🌎 [docmost](docmost.com/) - Collaborative wiki and documentation software (alternative to Confluence, Notion). (<b><code>&nbsp;13302⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;644🍴</code></b> [Source Code](https://github.com/docmost/docmost))) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Documize](documize.com) - Modern Docs + Wiki software with built-in workflow, single binary executable, just bring MySQL/Percona. (<b><code>&nbsp;&nbsp;2212⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [Source Code](https://github.com/documize/community))) `AGPL-3.0` `Go`
- 🌎 [Dokuwiki](www.dokuwiki.org/DokuWiki) - Easy to use, lightweight, standards-compliant wiki engine with a simple syntax allowing reading the data outside the wiki. All data is stored in plain text files, therefore no database is required. (<b><code>&nbsp;&nbsp;4286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;869🍴</code></b> [Source Code](https://github.com/dokuwiki/dokuwiki))) `GPL-2.0` `PHP`
- 🌎 [Feather Wiki](feather.wiki) - A lightning fast and infinitely extensible tool for creating personal non-linear notebooks, databases, and wikis that is entirely self-contained, runs in your browser, and is only 58 kilobytes in size.  🌎 [Demo](feather.wiki/?page=gallery#wikis), 🌎 [Source Code](codeberg.org/Alamantus/FeatherWiki), 🌎 [Clients](feather.wiki/?page=gallery#extensions)) `AGPL-3.0` `Javascript`
- <b><code>&nbsp;&nbsp;2194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [Gitit](https://github.com/jgm/gitit)) - Wiki program that stores pages and uploaded files in a git repository, which can then be modified using the VCS command line tools or the wiki's web interface. `GPL-2.0` `Haskell`
- <b><code>&nbsp;13981⭐</code></b> <b><code>&nbsp;&nbsp;1564🍴</code></b> [Gollum](https://github.com/gollum/gollum)) - Simple, Git-powered wiki with a sweet API and local frontend. `MIT` `Ruby`
- 🌎 [Mediawiki](www.mediawiki.org/wiki/MediaWiki) - MediaWiki is a free and open-source wiki software package written in PHP. It serves as the platform for Wikipedia and the other Wikimedia projects, used by hundreds of millions of people each month.  🌎 [Demo](en.wikipedia.org/wiki/Main_Page), 🌎 [Source Code](phabricator.wikimedia.org/source/mediawiki/)) `GPL-2.0` `PHP`
- 🌎 [Mycorrhiza Wiki](mycorrhiza.wiki/) - Filesystem and git-based wiki engine written in Go using Mycomarkup as its primary markup language. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/bouncepaw/mycorrhiza/))) `AGPL-3.0` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;833⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [Otter Wiki](https://github.com/redimp/otterwiki)) - Simple, easy to use wiki software using markdown. `MIT` `Docker`
- 🌎 [Outline](www.getoutline.com/) `⚠` - An open, extensible, wiki for your team. (<b><code>&nbsp;31585⭐</code></b> <b><code>&nbsp;&nbsp;2521🍴</code></b> [Source Code](https://github.com/outline/outline))) `BSD-3-Clause` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Pepperminty Wiki](https://github.com/sbrl/Pepperminty-Wiki)) - Complete markdown-powered wiki contained in a single PHP file.  🌎 [Demo](starbeamrainbowlabs.com/labs/peppermint/build/)) `MPL-2.0` `PHP`
- 🌎 [PmWiki](www.pmwiki.org) - Wiki-based system for collaborative creation and maintenance of websites. `GPL-3.0` `PHP`
- 🌎 [Raneto](raneto.com/) - Raneto is an open source Knowledgebase platform that uses static Markdown files to power your Knowledgebase. (<b><code>&nbsp;&nbsp;2818⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;445🍴</code></b> [Source Code](https://github.com/ryanlelek/Raneto))) `MIT` `Nodejs`
- 🌎 [TiddlyWiki](tiddlywiki.com/) - Reusable non-linear personal web notebook. (<b><code>&nbsp;&nbsp;8256⭐</code></b> <b><code>&nbsp;&nbsp;1204🍴</code></b> [Source Code](https://github.com/Jermolene/TiddlyWiki5))) `BSD-3-Clause` `Nodejs`
- 🌎 [Tiki](tiki.org/HomePage) - Wiki CMS Groupware with the most built-in features.  🌎 [Demo](tiki.org/Try-Tiki), 🌎 [Source Code](gitlab.com/tikiwiki/tiki)) `LGPL-2.1` `PHP`
- 🌎 [W](w.club1.fr) - Lightweight, mutli-user, flat-file-database Wiki engine. Create pages quickly and edit them in your Web browser using Mardown/HTML/CSS/JS. The main difference with other wiki is that you are encouraged to customize each page style individually. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Source Code](https://github.com/vincent-peugnet/wcms))) `AGPL-3.0` `PHP`
- 🌎 [WackoWiki](wackowiki.org/) - WackoWiki is a light and easy to install multilingual Wiki-engine. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/WackoWiki/wackowiki))) `BSD-3-Clause` `PHP`
- 🌎 [Wiki.js](js.wiki/) - Modern, lightweight and powerful wiki app using Git and Markdown.  🌎 [Demo](docs.requarks.io), <b><code>&nbsp;26056⭐</code></b> <b><code>&nbsp;&nbsp;2886🍴</code></b> [Source Code](https://github.com/Requarks/wiki))) `AGPL-3.0` `Nodejs/Docker/K8S`
- [WikiDocs](http://wikidocs.it) - A databaseless markdown flat-file wiki engine. (<b><code>&nbsp;&nbsp;&nbsp;407⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [Source Code](https://github.com/Zavy86/WikiDocs))) `MIT` `PHP/Docker`
- 🌎 [WiKiss](wikiss.tuxfamily.org/) - Wiki, simple to use and install.  🌎 [Source Code](svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Wikmd](https://github.com/Linbreux/wikmd)) - Modern and simple file based wiki that uses Markdown and Git. `MIT` `Python/Docker`
- 🌎 [XWiki](www.xwiki.org) - Second generation wiki that allows the user to extend its functionalities with a powerful extension-based architecture.  🌎 [Demo](www.xwikiplayground.org/xwiki/bin/view/Main/), <b><code>&nbsp;&nbsp;1060⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;560🍴</code></b> [Source Code](https://github.com/xwiki/xwiki-platform))) `LGPL-2.1` `Java/Docker/deb`
- 🌎 [Zim](zim-wiki.org/) - Graphical text editor used to maintain a collection of wiki pages. Each page can contain links to other pages, simple formatting and images. (<b><code>&nbsp;&nbsp;2016⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;377🍴</code></b> [Source Code](https://github.com/zim-desktop-wiki/zim-desktop-wiki))) `GPL-2.0` `Python/deb`


--------------------

## List of Licenses

**[`^        back to top        ^`](#awesome-selfhosted)**

- `0BSD` - 🌎 [BSD Zero-Clause Licence](spdx.org/licenses/0BSD.html)
- `AAL` - 🌎 [Attribution Assurance License](spdx.org/licenses/AAL.html)
- `AGPL-3.0` - 🌎 [GNU Affero General Public License 3.0](spdx.org/licenses/AGPL-3.0.html)
- `Apache-2.0` - 🌎 [Apache, Version 2.0](spdx.org/licenses/Apache-2.0.html)
- `APSL-2.0` - 🌎 [Apple Public Source License, Version 2.0](spdx.org/licenses/APSL-2.0.html)
- `Artistic-2.0` - 🌎 [Artistic License Version 2.0](spdx.org/licenses/Artistic-2.0.html)
- `Beerware` - 🌎 [Beerware License](spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - 🌎 [BSD 2-clause "Simplified"](spdx.org/licenses/BSD-2-Clause.html)
- `BSD-2-Clause-FreeBSD` - 🌎 [BSD 2-Clause FreeBSD License](spdx.org/licenses/BSD-2-Clause-FreeBSD.html)
- `BSD-3-Clause` - 🌎 [BSD 3-Clause "New" or "Revised"](spdx.org/licenses/BSD-3-Clause.html)
- `BSD-3-Clause-Attribution` - 🌎 [BSD with attribution](spdx.org/licenses/BSD-3-Clause-Attribution.html)
- `BSD-4-Clause` - 🌎 [BSD 4-clause "Original"](spdx.org/licenses/BSD-4-Clause.html)
- `CC-BY-SA-3.0` - 🌎 [Creative Commons Attribution-ShareAlike 3.0 License](spdx.org/licenses/CC-BY-SA-3.0.html)
- `CC-BY-SA-4.0` - 🌎 [Creative Commons Attribution-ShareAlike 4.0 License](spdx.org/licenses/CC-BY-SA-4.0.html)
- `CC0-1.0` - 🌎 [Public Domain/Creative Common Zero 1.0](spdx.org/licenses/CC0-1.0.html)
- `CDDL-1.0` - 🌎 [Common Development and Distribution License](spdx.org/licenses/CDDL-1.0.html)
- `CECILL-B` - 🌎 [CEA CNRS INRIA Logiciel Libre](spdx.org/licenses/CECILL-B.html)
- `CPAL-1.0` - 🌎 [Common Public Attribution License Version 1.0](spdx.org/licenses/CPAL-1.0.html)
- `ECL-2.0` - 🌎 [Educational Community License, Version 2.0](spdx.org/licenses/ECL-2.0.html)
- `EPL-1.0` - 🌎 [Eclipse Public License, Version 1.0](spdx.org/licenses/EPL-1.0.html)
- `EPL-2.0` - 🌎 [Eclipse Public License, Version 2.0](spdx.org/licenses/EPL-2.0.html)
- `EUPL-1.2` - 🌎 [European Union Public License 1.2](spdx.org/licenses/EUPL-1.2.html)
- `GPL-1.0` - 🌎 [GNU General Public License 1.0](spdx.org/licenses/GPL-1.0.html)
- `GPL-2.0` - 🌎 [GNU General Public License 2.0](spdx.org/licenses/GPL-2.0.html)
- `GPL-3.0` - 🌎 [GNU General Public License 3.0](spdx.org/licenses/GPL-3.0.html)
- `IPL-1.0` - 🌎 [IBM Public License](spdx.org/licenses/IPL-1.0.html)
- `ISC` - 🌎 [Internet Systems Consortium License](spdx.org/licenses/ISC.html)
- `LGPL-2.1` - 🌎 [Lesser General Public License 2.1](spdx.org/licenses/LGPL-2.1.html)
- `LGPL-3.0` - 🌎 [Lesser General Public License 3.0](spdx.org/licenses/LGPL-3.0.html)
- `MIT` - 🌎 [MIT License](spdx.org/licenses/MIT.html)
- `MPL-1.1` - 🌎 [Mozilla Public License Version 1.1](spdx.org/licenses/MPL-1.1.html)
- `MPL-2.0` - 🌎 [Mozilla Public License](spdx.org/licenses/MPL-2.0.html)
- `OSL-3.0` - 🌎 [Open Software License 3.0](spdx.org/licenses/OSL-3.0.html)
- `Sendmail` - 🌎 [Sendmail License](spdx.org/licenses/Sendmail.html)
- `Ruby` - 🌎 [Ruby License](spdx.org/licenses/Ruby.html)
- `Unlicense` - 🌎 [The Unlicense](spdx.org/licenses/Unlicense.html)
- `WTFPL` - 🌎 [Do What the Fuck You Want to Public License](spdx.org/licenses/WTFPL.html)
- `Zlib` - 🌎 [Zlib/libpng License](spdx.org/licenses/Zlib.html)
- `ZPL-2.0` - 🌎 [Zope Public License 2.0](spdx.org/licenses/ZPL-2.0.html)


--------------------

## Anti-features

- `⚠ ` - Depends on a proprietary service outside the user's control

--------------------

## External Links

**[`^        back to top        ^`](#awesome-selfhosted)**

- <b><code>&nbsp;28524⭐</code></b> <b><code>&nbsp;&nbsp;1661🍴</code></b> [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin)) - Curated list of amazingly awesome open source sysadmin resources.
- Lists of software aimed at privacy and decentralization in some form: 🌎 [PRISM Break](prism-break.org/en/), 🌎 [privacytools.io](www.privacytools.io/), 🌎 [Alternative Internet](redecentralize.github.io/alternative-internet/), 🌎 [Libre Projects](libreprojects.net/), 🌎 [Easy Indie App](easyindie.app)
- Other Awesome lists: <b><code>&nbsp;13555⭐</code></b> <b><code>&nbsp;&nbsp;2568🍴</code></b> [Awesome Big Data](https://github.com/0xnr/awesome-bigdata)), <b><code>&nbsp;62810⭐</code></b> <b><code>&nbsp;10098🍴</code></b> [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets))
- Dynamic Domain Name services: 🌎 [Afraid.org](freedns.afraid.org/domain/registry/), 🌎 [Pagekite](pagekite.net/)
- Communities/forums: 🌎 [/c/selfhosted on lemmy.world](lemmy.world/c/selfhosted), 🌎 [/c/selfhost on lemmy.ml](lemmy.ml/c/selfhost), 🌎 [/r/selfhosted on reddit](old.reddit.com/r/selfhosted/), 🌎 [r-selfhosted forum](forum.r-selfhosted.com/), 🌎 [/r/selfhosted Matrix Channel](matrix.to/#/#selfhosted:selfhosted.chat), 🌎 [Homelab forum](homelabforum.com/), 🌎 [/r/homelab on reddit](old.reddit.com/r/homelab/), 🌎 [IndieWeb](indieweb.org/)
- 🌎 [theme.park](theme-park.dev/) - A collection of themes/skins for 50 selfhosted apps! (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/GilbN/theme.park/))) `MIT` `CSS`
- 🌎 [Track Awesome Selfhosted](www.trackawesomelist.com/awesome-selfhosted/awesome-selfhosted/) - Get the latest updates of awesome-selfhosted.

--------------------

## Contributing

Contributing guidelines can be found <b><code>&nbsp;&nbsp;&nbsp;623⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;451🍴</code></b> [here](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/CONTRIBUTING.md)).

## License

This list is under the [Creative Commons Attribution-ShareAlike 3.0 Unported](https://github.com/correia-jpv/fucking-awesome-selfhosted/blob/master/LICENSE) License.
Terms of the license are summarized 🌎 [here](creativecommons.org/licenses/by-sa/3.0/).  
The list of authors can be found in the <b><code>&nbsp;&nbsp;&nbsp;623⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;451🍴</code></b> [AUTHORS](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/AUTHORS)) file.

## Source
<b><code>224515⭐</code></b> <b><code>&nbsp;10504🍴</code></b> [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted))