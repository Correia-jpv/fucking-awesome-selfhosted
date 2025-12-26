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
  - [Generative Artificial Intelligence (GenAI)](#generative-artificial-intelligence-genai)
  - [Groupware](#groupware)
  - [Health and Fitness](#health-and-fitness)
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

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [ANALOG](https://github.com/orangecoloured/analog)) - A minimal analytics tool. Tracks events in a span of 10-30 days. `MIT` `Nodejs/Docker`
- 🌎 [Aptabase](aptabase.com/) - Privacy first and simple analytics for mobile and desktop apps. (<b><code>&nbsp;&nbsp;1562⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Source Code](https://github.com/aptabase/aptabase))) `AGPL-3.0` `Docker`
- [AWStats](http://www.awstats.org/) - Generate statistics from web, streaming, ftp or mail server logfiles.  🌎 [Demo](www.awstats.org/#DEMO), <b><code>&nbsp;&nbsp;&nbsp;418⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [Source Code](https://github.com/eldy/awstats))) `GPL-3.0` `Perl`
- 🌎 [Countly Community Edition](count.ly) - Real time mobile and web analytics, crash reporting and push notifications platform. (<b><code>&nbsp;&nbsp;5807⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;979🍴</code></b> [Source Code](https://github.com/Countly/countly-server))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Daily Stars Explorer](emanuelef.github.io/daily-stars-explorer) `⚠` - Track GitHub repo trends with daily star insights to see growth and community interest over time.  🌎 [Demo](emanuelef.github.io/daily-stars-explorer), <b><code>&nbsp;&nbsp;&nbsp;300⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Source Code](https://github.com/emanuelef/daily-stars-explorer))) `MIT` `Go/Nodejs/Docker`
- 🌎 [Druid](druid.apache.org) - Distributed, column-oriented, real-time analytics data store. (<b><code>&nbsp;13906⭐</code></b> <b><code>&nbsp;&nbsp;3770🍴</code></b> [Source Code](https://github.com/apache/druid))) `Apache-2.0` `Java/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [EDA](https://github.com/jortilles/EDA)) - Web application for data analysis and visualization. `AGPL-3.0` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;168⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [ghstats](https://github.com/vladkens/ghstats)) `⚠` - Dashboard for tracking GitHub repos traffic history longer than 14 days. `MIT` `Docker`
- [GoAccess](http://goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal. (<b><code>&nbsp;20078⭐</code></b> <b><code>&nbsp;&nbsp;1170🍴</code></b> [Source Code](https://github.com/allinurl/goaccess))) `GPL-2.0` `C`
- 🌎 [GoatCounter](www.goatcounter.com) - Easy web statistics without tracking of personal data. (<b><code>&nbsp;&nbsp;5347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [Source Code](https://github.com/arp242/goatcounter))) `EUPL-1.2` `Go`
- 🌎 [Litlyx](litlyx.com) - All-in-one Analytics Solution. Setup in 30 seconds. Display all your data on an AI-powered dashboard. Fully self-hostable and GDPR compliant. (<b><code>&nbsp;&nbsp;1650⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Source Code](https://github.com/Litlyx/litlyx))) `Apache-2.0` `Docker`
- 🌎 [Liwan](liwan.dev/) - Privacy-first web analytics.  🌎 [Demo](demo.liwan.dev/p/liwan.dev), <b><code>&nbsp;&nbsp;&nbsp;140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Source Code](https://github.com/explodingcamera/liwan))) `Apache-2.0` `Rust/Docker`
- 🌎 [Matomo](matomo.org/) - Web analytics that protects your data and your customers' privacy (alternative to Google Analytics). (<b><code>&nbsp;21127⭐</code></b> <b><code>&nbsp;&nbsp;2792🍴</code></b> [Source Code](https://github.com/matomo-org/matomo))) `GPL-3.0` `PHP`
- 🌎 [Medama Analytics](oss.medama.io) - Privacy-first website analytics. Tiny, simple, and cookie-free.  🌎 [Demo](demo.medama.io), <b><code>&nbsp;&nbsp;&nbsp;578⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/medama-io/medama))) `Apache-2.0/MIT` `Docker/Go`
- 🌎 [Metabase](metabase.com/) - Easy way for everyone in your company to ask questions and learn from data. (<b><code>&nbsp;45306⭐</code></b> <b><code>&nbsp;&nbsp;6125🍴</code></b> [Source Code](https://github.com/metabase/metabase))) `AGPL-3.0` `Java/Docker`
- 🌎 [Middleware](middlewarehq.com/) - Tool designed to help engineering leaders measure and analyze the effectiveness of their teams using the DORA metrics. (<b><code>&nbsp;&nbsp;1511⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [Source Code](https://github.com/middlewarehq/middleware))) `Apache-2.0` `Docker/Python/Nodejs`
- 🌎 [Mixpost](mixpost.app/) - Social media management software to easily create, schedule, publish, and manage social media content in one place (alternative to Hootsuite and Buffer). (<b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Source Code](https://github.com/inovector/MixpostApp))) `MIT` `PHP/Docker`
- 🌎 [Netron](netron.app/) - Visualizer for neural network and machine learning models. (<b><code>&nbsp;32082⭐</code></b> <b><code>&nbsp;&nbsp;3051🍴</code></b> [Source Code](https://github.com/lutzroeder/netron))) `MIT` `Python/Nodejs`
- 🌎 [Offen](www.offen.dev/) - Fair, lightweight and open web analytics tool. Gain insights while your users have full access to their data.  🌎 [Demo](www.offen.dev/try-demo/), <b><code>&nbsp;&nbsp;&nbsp;962⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Source Code](https://github.com/offen/offen))) `Apache-2.0` `Go/Docker`
- 🌎 [Plausible Analytics](plausible.io/) - Simple, lightweight (< 1 KB) and privacy-friendly web analytics. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/plausible/analytics/))) `AGPL-3.0` `Elixir`
- 🌎 [PostHog](posthog.com) - Product analytics, session recording, feature flagging and a/b testing that you can self-host (alternative to Mixpanel, Amplitude, Heap, HotJar, Optimizely). (<b><code>&nbsp;30544⭐</code></b> <b><code>&nbsp;&nbsp;2142🍴</code></b> [Source Code](https://github.com/posthog/posthog))) `MIT` `Python`
- 🌎 [Postiz](postiz.com) `⚠` - Schedule posts, track the performance of your content, and manage all your social media accounts in one place (Alternative to Buffer, Hootsuite, Sprout Social). (<b><code>&nbsp;24968⭐</code></b> <b><code>&nbsp;&nbsp;4230🍴</code></b> [Source Code](https://github.com/gitroomhq/postiz-app))) `AGPL-3.0` `Docker`
- 🌎 [Prisme Analytics](www.prismeanalytics.com) - Privacy-focused and progressive analytics service based on Grafana. (<b><code>&nbsp;&nbsp;&nbsp;117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/prismelabs/analytics))) `AGPL-3.0/MIT` `Docker`
- [Redash](http://redash.io) - Connect and query your data sources, build dashboards to visualize data and share them with your company. (<b><code>&nbsp;28099⭐</code></b> <b><code>&nbsp;&nbsp;4537🍴</code></b> [Source Code](https://github.com/getredash/redash))) `BSD-2-Clause` `Docker`
- 🌎 [Rybbit](rybbit.io) - Web and products analytics that is easy to setup and more intuitive (alternative to Google Analytics).  🌎 [Demo](demo.rybbit.io/21/), <b><code>&nbsp;10550⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;504🍴</code></b> [Source Code](https://github.com/rybbit-io/rybbit))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;3095⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [Shynet](https://github.com/milesmcc/shynet)) - Modern, privacy-friendly, and detailed web analytics that works without cookies or JS. `Apache-2.0` `Python/Docker`
- <b><code>&nbsp;&nbsp;1391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;402🍴</code></b> [Socioboard](https://github.com/socioboard/Socioboard-5.0)) `⚠` - Social media management, analytics, and reporting platform supporting nine social media networks out-of-the-box. `GPL-3.0` `Nodejs`
- <b><code>&nbsp;&nbsp;1411⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [Statistics for Strava](https://github.com/robiningelbrecht/statistics-for-strava)) `⚠` - Statistics dashboard generated from Strava data.  🌎 [Demo](statistics-for-strava.robiningelbrecht.be/)) `AGPL-3.0` `Docker`
- [Superset](http://superset.apache.org/) - Modern data exploration and visualization platform. (<b><code>&nbsp;69545⭐</code></b> <b><code>&nbsp;16378🍴</code></b> [Source Code](https://github.com/apache/superset))) `Apache-2.0` `Python`
- 🌎 [Swetrix](swetrix.com/) - Ultimate, open-source web analytics to satisfy all your needs.  🌎 [Demo](swetrix.com/projects/STEzHcB1rALV), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Source Code](https://github.com/Swetrix/selfhosting))) `AGPL-3.0` `Docker`
- 🌎 [Umami](umami.is/) - Simple, fast, privacy-focused alternative to Google Analytics.  🌎 [Demo](cloud.umami.is/share/LGazGOecbDtaIwDr), <b><code>&nbsp;34355⭐</code></b> <b><code>&nbsp;&nbsp;6129🍴</code></b> [Source Code](https://github.com/umami-software/umami))) `MIT` `Nodejs/Docker`
- 🌎 [Vince](www.vinceanalytics.com/) - Web analytics and dashboard (alternative to Google Analytics).  🌎 [Demo](demo.vinceanalytics.com/v1/share/vinceanalytics.com?auth=Ls9tV4pzqOn7BJ7-&demo=true), <b><code>&nbsp;&nbsp;1986⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [Source Code](https://github.com/vinceanalytics/vince))) `AGPL-3.0` `Go/Docker/K8S/deb`


### Archiving and Digital Preservation (DP)

**[`^        back to top        ^`](#awesome-selfhosted)**

Digital 🌎 [archiving](en.wikipedia.org/wiki/Archival_science) and 🌎 [preservation](en.wikipedia.org/wiki/Digital_preservation) software.

_Related: [Content Management Systems (CMS)](#content-management-systems-cms)_

_See also: <b><code>&nbsp;&nbsp;2426⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [awesome-web-archiving](https://github.com/iipc/awesome-web-archiving))_

- 🌎 [ArchiveBox](archivebox.io/) - Create HTML & screenshot archives of sites from your bookmarks, browsing history, RSS feeds, or other sources (alternative to Wayback Machine).  🌎 [Demo](demo.archivebox.io/), <b><code>&nbsp;26185⭐</code></b> <b><code>&nbsp;&nbsp;1424🍴</code></b> [Source Code](https://github.com/ArchiveBox/ArchiveBox))) `MIT` `Python/Docker`
- 🌎 [ArchivesSpace](archivesspace.org/) - Archives information management application for managing and providing Web access to archives, manuscripts and digital objects.  🌎 [Demo](archivesspace.org/application/sandbox), <b><code>&nbsp;&nbsp;&nbsp;391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;242🍴</code></b> [Source Code](https://github.com/archivesspace/archivesspace))) `ECL-2.0` `Ruby`
- 🌎 [bitmagnet](bitmagnet.io) - BitTorrent indexer, DHT crawler, content classifier and torrent search engine with web UI, GraphQL API and Servarr stack integration. (<b><code>&nbsp;&nbsp;3711⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [Source Code](https://github.com/bitmagnet-io/bitmagnet))) `MIT` `Go/Docker`
- 🌎 [CKAN](ckan.org) - Make open data websites. (<b><code>&nbsp;&nbsp;4912⭐</code></b> <b><code>&nbsp;&nbsp;2073🍴</code></b> [Source Code](https://github.com/ckan/ckan))) `AGPL-3.0` `Python`
- 🌎 [Collective Access - Providence](collectiveaccess.org/) - Highly configurable Web-based framework for management, description, and discovery of digital and physical collections supporting a variety of metadata standards, data types, and media formats. (<b><code>&nbsp;&nbsp;&nbsp;350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;188🍴</code></b> [Source Code](https://github.com/collectiveaccess/providence))) `GPL-3.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;896⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Ganymede](https://github.com/Zibbp/ganymede)) `⚠` - Twitch VOD and live stream archiving platform. Includes a rendered chat for each archive. `GPL-3.0` `Docker`
- 🌎 [Omeka S](omeka.org/s/) - Next-generation web publishing platform for institutions interested in connecting digital cultural heritage collections with other resources online. (<b><code>&nbsp;&nbsp;&nbsp;460⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [Source Code](https://github.com/omeka/omeka-s))) `GPL-3.0` `Nodejs`
- 🌎 [Wallabag](www.wallabag.org) - Wallabag, formerly Poche, is a web application allowing you to save articles to read them later with improved readability. (<b><code>&nbsp;12272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;846🍴</code></b> [Source Code](https://github.com/wallabag/wallabag))) `MIT` `PHP`
- <b><code>&nbsp;&nbsp;2115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Wayback](https://github.com/wabarc/wayback)) - A self-hosted toolkit for archiving webpages to the Internet Archive, archive.today, IPFS, and local file systems. `GPL-3.0` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Webarchive](https://github.com/derfenix/webarchive)) - Lightweight self-hosted _wayback machine_ that creates HTML and PDF files from your bookmarks. `BSD-3-Clause` `Go`


### Automation

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Automation](en.wikipedia.org/wiki/Automation) software designed to reduce human intervention in processes.

_Related: [Internet of Things (IoT)](#internet-of-things-iot), [Software Development - Continuous Integration & Deployment](#software-development---continuous-integration--deployment), [Media Management](#media-management)_

- 🌎 [Activepieces](www.activepieces.com) - No-code business automation tool like Zapier or Tray. For example, you can send a Slack notification for each new Trello card. (<b><code>&nbsp;19979⭐</code></b> <b><code>&nbsp;&nbsp;3085🍴</code></b> [Source Code](https://github.com/activepieces/activepieces))) `MIT` `Docker`
- 🌎 [Apache Airflow](airflow.apache.org/) - Platform to programmatically author, schedule, and monitor workflows. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/apache/airflow/))) `Apache-2.0` `Python/Docker`
- 🌎 [Automatisch](automatisch.io) - Business automation tool that lets you connect different services like Twitter, Slack, and more to automate your business processes (alternative to Zapier). (<b><code>&nbsp;13423⭐</code></b> <b><code>&nbsp;&nbsp;1021🍴</code></b> [Source Code](https://github.com/automatisch/automatisch))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [BookBounty](https://github.com/TheWicklowWolf/BookBounty)) `⚠` - Retrieve missing Readarr books from Library Genesis. `MPL-2.0` `Docker`
- 🌎 [changedetection.io](changedetection.io/) - Stay up-to-date with web-site content changes. (<b><code>&nbsp;29401⭐</code></b> <b><code>&nbsp;&nbsp;1633🍴</code></b> [Source Code](https://github.com/dgtlmoon/changedetection.io))) `Apache-2.0` `Python/Docker`
- 🌎 [ChiefOnboarding](chiefonboarding.com) - Employee onboarding platform that allows you to provision user accounts and create sequences with todo items, resources, text/email/Slack messages, and more! Available as a web portal and Slack bot. (<b><code>&nbsp;&nbsp;&nbsp;844⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;154🍴</code></b> [Source Code](https://github.com/chiefonboarding/ChiefOnboarding))) `AGPL-3.0` `Docker`
- 🌎 [Cronicle](cronicle.net/) - Simple, distributed task scheduler and runner with a web based UI. (<b><code>&nbsp;&nbsp;5292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;462🍴</code></b> [Source Code](https://github.com/jhuckaby/Cronicle))) `MIT` `Nodejs`
- 🌎 [Dagu](docs.dagu.cloud/) - Powerful Cron alternative with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. (<b><code>&nbsp;&nbsp;2944⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;216🍴</code></b> [Source Code](https://github.com/dagu-org/dagu))) `GPL-3.0` `Go/Docker`
- 🌎 [Discount Bandit](discount-bandit.cybrarist.com/) `⚠` - Track pricing, stock status of products across multiple stores such as Amazon, Ebay, Walmart, etc. (<b><code>&nbsp;&nbsp;&nbsp;598⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Source Code](https://github.com/Cybrarist/Discount-Bandit))) `GPL-3.0` `PHP/Docker`
- 🌎 [Dittofeed](www.dittofeed.com) - Omni-channel customer engagement and messaging automation platform (alternative to Braze, Customer.io, Iterable).  🌎 [Demo](demo.dittofeed.com/dashboard/journeys), <b><code>&nbsp;&nbsp;2581⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [Source Code](https://github.com/dittofeed/dittofeed))) `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [feedmixer](https://github.com/cristoper/feedmixer)) - Micro web service which takes a list of feed URLs and returns a new feed consisting of the most recent n entries from each given feed (returns Atom, RSS, or JSON).  🌎 [Demo](mretc.net/feedmixer/json?f=https://hnrss.org/newest&f=https://americancynic.net/atom.xml&n=1)) `WTFPL` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Github Ntfy](https://github.com/BreizhHardware/ntfy_alerts)) `⚠` - Push notifications to NTFY, Gotify, Discord or Slack when a new release is available on Docker Hub or Github. (<b><code>&nbsp;27880⭐</code></b> <b><code>&nbsp;&nbsp;1136🍴</code></b> [Clients](https://github.com/binwiederhier/ntfy))) `GPL-3.0` `Rust/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;477⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [gocron](https://github.com/flohoss/gocron)) - Task scheduler that allows users to specify recurring jobs via a simple YAML configuration file. `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [HandBrake Web](https://github.com/TheNickOfTime/handbrake-web)) - Use one or more instances of HandBrake video transcoder on a headless device via a web interface. `AGPL-3.0` `Docker`
- 🌎 [Healthchecks](healthchecks.io/) - Listen for pings and sends alerts when pings are late. (<b><code>&nbsp;&nbsp;9710⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;938🍴</code></b> [Source Code](https://github.com/healthchecks/healthchecks))) `BSD-3-Clause` `Python/Docker`
- <b><code>&nbsp;48386⭐</code></b> <b><code>&nbsp;&nbsp;4212🍴</code></b> [Huginn](https://github.com/huginn/huginn)) - Build agents that monitor and act on your behalf. `MIT` `Ruby`
- 🌎 [Kestra](kestra.io) - Event-driven, language-agnostic platform to create, schedule, and monitor workflows. In code. Coordinate data pipelines and tasks such as ETL and ELT. (<b><code>&nbsp;26148⭐</code></b> <b><code>&nbsp;&nbsp;2381🍴</code></b> [Source Code](https://github.com/kestra-io/kestra))) `Apache-2.0` `Docker`
- 🌎 [Kibitzr](kibitzr.github.io) - Lightweight personal web assistant with powerful integrations. (<b><code>&nbsp;&nbsp;&nbsp;706⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Source Code](https://github.com/kibitzr/kibitzr))) `MIT` `Python`
- 🌎 [LazyLibrarian](gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - Follow authors and grab metadata for all your digital reading needs. It uses a combination of Goodreads, Librarything and optionally GoogleBooks as sources for author info and book info. `GPL-3.0` `Python`
- 🌎 [Leon](getleon.ai) - Personal assistant who can live on your server. (<b><code>&nbsp;16856⭐</code></b> <b><code>&nbsp;&nbsp;1414🍴</code></b> [Source Code](https://github.com/leon-ai/leon))) `MIT` `Nodejs`
- <b><code>&nbsp;&nbsp;2342⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;246🍴</code></b> [Matchering](https://github.com/sergree/matchering)) - Automated music mastering (alternative to LANDR, eMastered and MajorDecibel). `GPL-3.0` `Docker`
- 🌎 [Mylar3](mylarcomics.com/) - Automated Comic Book (cbr/cbz) downloader program for use with NZB and torrents. (<b><code>&nbsp;&nbsp;1329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [Source Code](https://github.com/mylar3/mylar3))) `GPL-3.0` `Python/Docker`
- 🌎 [OliveTin](www.olivetin.app/) - Web interface for running Linux shell commands. (<b><code>&nbsp;&nbsp;3340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [Source Code](https://github.com/OliveTin/OliveTin))) `AGPL-3.0` `Go`
- 🌎 [pyLoad](pyload.net/) - Lightweight, customizable and remotely manageable downloader for 1-click-hosting sites like rapidshare.com or uploaded.to. (<b><code>&nbsp;&nbsp;3653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;737🍴</code></b> [Source Code](https://github.com/pyload/pyload))) `AGPL-3.0` `Python`
- 🌎 [StackStorm](stackstorm.com) - StackStorm (aka _IFTTT for Ops_) is event-driven automation for auto-remediation, security responses, troubleshooting, deployments, and more. Includes rules engine, workflow, 160 integration packs with 6000+ actions and ChatOps. (<b><code>&nbsp;&nbsp;6391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;779🍴</code></b> [Source Code](https://github.com/StackStorm/st2))) `Apache-2.0` `Python`
- <b><code>&nbsp;&nbsp;1347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [µTask](https://github.com/ovh/utask)) - Automation engine that models and executes business processes declared in yaml. `BSD-3-Clause` `Go/Docker`


### Backup

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Backup](en.wikipedia.org/wiki/Backup) software.

**Please visit <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/Backups](https://github.com/awesome-foss/awesome-sysadmin#backups))**



### Blogging Platforms

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [blog](en.wikipedia.org/wiki/Blog) is a discussion or informational website consisting of discrete, diary-style text entries (posts).

_Related: [Static Site Generators](#static-site-generators), [Content Management Systems (CMS)](#content-management-systems-cms)_

_See also: 🌎 [WeblogMatrix](www.weblogmatrix.org/)_

- 🌎 [Antville](antville.org) - Free, open source project aimed at the development of a high performance, feature rich weblog hosting software. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Source Code](https://github.com/antville/antville))) `Apache-2.0` `Javascript`
- 🌎 [Castopod](castopod.org) - Podcast management hosting platform that includes the latest podcast 2.0 standards, an automated Fediverse feed, analytics, an embeddable player, and more.  🌎 [Source Code](code.castopod.org/adaures/castopod)) `AGPL-3.0` `PHP/Docker`
- 🌎 [Chyrp Lite](chyrplite.net) - Extra-awesome, extra-lightweight blog engine. (<b><code>&nbsp;&nbsp;&nbsp;466⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Source Code](https://github.com/xenocrat/chyrp-lite))) `BSD-3-Clause` `PHP`
- 🌎 [Dotclear](git.dotclear.org/dev/dotclear) - Take control over your blog. `GPL-2.0` `PHP`
- 🌎 [Ech0](echo.soopy.cn/) - Lightweight federated publishing platform focused on personal idea sharing (documentation in Chinese).  🌎 [Demo](memo.vaaat.com/), <b><code>&nbsp;&nbsp;1604⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [Source Code](https://github.com/lin-snow/Ech0))) `AGPL-3.0` `Docker/K8S`
- 🌎 [FlatPress](flatpress.org/) - A lightweight, easy-to-set-up flat-file blogging engine. (<b><code>&nbsp;&nbsp;&nbsp;203⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [Source Code](https://github.com/flatpressblog/flatpress))) `GPL-2.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;260⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [fx](https://github.com/rikhuijzer/fx)) - Micro-blog tool offering built-in syntax highlighting, mobile publishing and more (alternative to Twitter, Bluesky). `MIT` `Docker`
- 🌎 [Ghost](ghost.org/) - Just a blogging platform. (<b><code>&nbsp;51452⭐</code></b> <b><code>&nbsp;11240🍴</code></b> [Source Code](https://github.com/TryGhost/Ghost))) `MIT` `Nodejs`
- 🌎 [Haven](havenweb.org/) - Private blogging system with markdown editing and built in RSS reader.  🌎 [Demo](havenweb.org/demo.html), <b><code>&nbsp;&nbsp;&nbsp;747⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Source Code](https://github.com/havenweb/haven))) `MIT` `Ruby`
- 🌎 [HTMLy](www.htmly.com/) - Databaseless PHP blogging platform. A flat-file CMS that allows you to create a fast, secure, and powerful website or blog in seconds. ([Demo](http://demo.htmly.com/), <b><code>&nbsp;&nbsp;1295⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;297🍴</code></b> [Source Code](https://github.com/danpros/htmly))) `GPL-2.0` `PHP`
- 🌎 [Known](withknown.com/) - Collaborative social publishing platform. (<b><code>&nbsp;&nbsp;1100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [Source Code](https://github.com/idno/known))) `Apache-2.0` `PHP`
- 🌎 [Mataroa](mataroa.blog/) - Naked blogging platform for minimalists. (<b><code>&nbsp;&nbsp;&nbsp;319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Source Code](https://github.com/mataroablog/mataroa))) `MIT` `Python`
- 🌎 [PluXml](pluxml.org) - XML-based blog/CMS platform. (<b><code>&nbsp;&nbsp;&nbsp;230⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [Source Code](https://github.com/pluxml/PluXml))) `GPL-3.0` `PHP`
- 🌎 [Serendipity](docs.s9y.org/) - Serendipity (s9y) is a highly extensible and customizable PHP blog engine using Smarty templating. (<b><code>&nbsp;&nbsp;&nbsp;220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Source Code](https://github.com/s9y/serendipity))) `BSD-3-Clause` `PHP`
- 🌎 [WriteFreely](writefreely.org) - Writing software for starting a minimalist, federated blog — or an entire community. (<b><code>&nbsp;&nbsp;4998⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;367🍴</code></b> [Source Code](https://github.com/writefreely/writefreely))) `AGPL-3.0` `Go`


### Booking and Scheduling

**[`^        back to top        ^`](#awesome-selfhosted)**

Event scheduling, reservation, and appointment management software.

_Related: [Polls and Events](#polls-and-events)_

- 🌎 [Alf.io](alf.io/) - Ticket reservation system.  🌎 [Demo](demo.alf.io/authentication), <b><code>&nbsp;&nbsp;1540⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;377🍴</code></b> [Source Code](https://github.com/alfio-event/alf.io))) `GPL-3.0` `Java`
- 🌎 [Cal.com](cal.com/) - Online appointment scheduling system.  🌎 [Demo](app.cal.com/bailey), <b><code>&nbsp;39427⭐</code></b> <b><code>&nbsp;11383🍴</code></b> [Source Code](https://github.com/calcom/cal.com))) `AGPL-3.0` `Nodejs`
- 🌎 [Easy!Appointments](easyappointments.org/) - Allows your customers to book appointments with you via the web.  🌎 [Demo](demo.easyappointments.org/), <b><code>&nbsp;&nbsp;3995⭐</code></b> <b><code>&nbsp;&nbsp;1474🍴</code></b> [Source Code](https://github.com/alextselegidis/easyappointments))) `GPL-3.0` `PHP`
- 🌎 [Hi.Events](hi.events) - Event management and ticketing platform for conferences, concerts, and more. Offering customizable event pages and embeddable ticket widgets.  🌎 [Demo](demo.hi.events/event/1/dog-conf-2030), <b><code>&nbsp;&nbsp;3412⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;532🍴</code></b> [Source Code](https://github.com/HiEventsDev/hi.events))) `AGPL-3.0` `Docker`
- 🌎 [LibreBooking](librebooking.readthedocs.io/) - Resource scheduling solution offering a flexible, mobile-friendly, and extensible interface for organizations to manage resource reservations.  🌎 [Demo](librebooking-demo.fly.dev/), <b><code>&nbsp;&nbsp;&nbsp;631⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;322🍴</code></b> [Source Code](https://github.com/LibreBooking/app))) `GPL-3.0` `PHP/Docker`
- 🌎 [QloApps](qloapps.com/) - Customizable and intuitive web-based hotel reservation system and a booking engine.  🌎 [Demo](demo.qloapps.com/), <b><code>&nbsp;11428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;691🍴</code></b> [Source Code](https://github.com/Qloapps/QloApps))) `OSL-3.0` `PHP/Nodejs`
- 🌎 [Rallly](rallly.co) - Create polls to vote on dates and times (alternative to Doodle).  🌎 [Demo](app.rallly.co), <b><code>&nbsp;&nbsp;4866⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;486🍴</code></b> [Source Code](https://github.com/lukevella/rallly))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Seatsurfing](seatsurfing.app/) - Webbased app to book seats, desks and rooms for offices. (<b><code>&nbsp;&nbsp;&nbsp;264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Source Code](https://github.com/seatsurfing/seatsurfing))) `GPL-3.0` `Docker`


### Bookmarks and Link Sharing

**[`^        back to top        ^`](#awesome-selfhosted)**

Software which allows users to add, annotate, edit, and share [bookmarks](https://en.wikipedia.org/wiki/Bookmark_(digital)) of web documents.

- <b><code>&nbsp;&nbsp;1136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Briefkasten](https://github.com/ndom91/briefkasten)) - Modern app for saving and managing your own bookmarks. Includes a browser extension.  🌎 [Demo](briefkastenhq.com/auth/signin)) `MIT` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;6942⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;307🍴</code></b> [Buku](https://github.com/jarun/Buku)) - Powerful bookmark manager and a personal textual mini-web. `GPL-3.0` `Python/deb`
- 🌎 [Digibunch](ladigitale.dev/digibunch/#/) - Create bunches of links to share with your learners or colleagues.  🌎 [Demo](ladigitale.dev/digibunch/#/b/5f67b12092b60), 🌎 [Source Code](codeberg.org/ladigitale/digibunch)) `AGPL-3.0` `Nodejs/PHP`
- <b><code>&nbsp;&nbsp;&nbsp;870⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Espial](https://github.com/jonschoning/espial)) - An open-source, web-based bookmarking server. `AGPL-3.0` `Haskell`
- 🌎 [Firefox Account Server](mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html) - Host your own Firefox accounts server. (<b><code>&nbsp;&nbsp;&nbsp;661⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;218🍴</code></b> [Source Code](https://github.com/mozilla/fxa))) `MPL-2.0` `Nodejs/Java`
- 🌎 [Grimoire](grimoire.pro) - Bookmark manager with a modern UI, automatic content & metadata extraction, categorization, filtering, and more. It has fully documented REST API, and Docker image for easy deployment. (<b><code>&nbsp;&nbsp;2684⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Source Code](https://github.com/goniszewski/grimoire))) `MIT` `Nodejs/Docker`
- 🌎 [Karakeep](karakeep.app/) - Bookmark-everything app with a touch of AI for the data hoarders out there.  🌎 [Demo](try.karakeep.app/signin), <b><code>&nbsp;22071⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;972🍴</code></b> [Source Code](https://github.com/karakeep-app/karakeep))) `AGPL-3.0` `Docker`
- 🌎 [LinkAce](www.linkace.org/) - Bookmark archive with automatic backups to the Internet Archive, link monitoring, and a full REST API. Installation is done via Docker, or as a simple PHP application.  🌎 [Demo](demo.linkace.org/guest/links), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/Kovah/LinkAce/))) `GPL-3.0` `Docker/PHP`
- 🌎 [linkding](linkding.link/) - Minimal bookmark management with a fast and clean UI. Simple installation through Docker and can run on your Raspberry Pi.  🌎 [Demo](demo.linkding.link/login/), <b><code>&nbsp;&nbsp;9749⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;501🍴</code></b> [Source Code](https://github.com/sissbruecker/linkding))) `MIT` `Docker`
- 🌎 [LinkWarden](linkwarden.app/) - Bookmark and archive manager to store your useful links. (<b><code>&nbsp;16433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;647🍴</code></b> [Source Code](https://github.com/linkwarden/linkwarden))) `MIT` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;380⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [NeonLink](https://github.com/AlexSciFier/neonlink)) - Bookmark service with unique design and simple installation with Docker. `MIT` `Docker`
- 🌎 [Readeck](readeck.org/en/) - Save the precious readable content of web pages you like and want to keep forever. See it as a bookmark manager and a read later tool.  🌎 [Source Code](codeberg.org/readeck/readeck), 🌎 [Clients](codeberg.org/readeck/browser-extension)) `AGPL-3.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;750⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Servas](https://github.com/beromir/Servas)) - A self-hosted bookmark management tool. It allows organization with tags, groups, and a list specifically for later access. It supports multiple users with 2FA. Companion browser extensions are available for Firefox and Chrome. (<b><code>&nbsp;&nbsp;&nbsp;750⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Clients](https://github.com/beromir/Servas#browser-extensions))) `GPL-3.0` `Docker/Nodejs/PHP`
- <b><code>&nbsp;&nbsp;3762⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;303🍴</code></b> [Shaarli](https://github.com/shaarli/Shaarli)) - Personal, minimalist, super-fast, no-database bookmarking and link sharing platform.  🌎 [Demo](demo.shaarli.org)) `Zlib` `PHP/deb`
- <b><code>&nbsp;11123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;608🍴</code></b> [Shiori](https://github.com/go-shiori/shiori)) - Simple bookmark manager built with Go. `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;3039⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [Slash](https://github.com/yourselfhosted/slash)) - An open source, self-hosted bookmarks and link sharing platform. `GPL-3.0` `Docker`
- 🌎 [SyncMarks](codeberg.org/Offerel/SyncMarks-Webapp) - Sync and manage your browser bookmarks from Edge, Firefox and Chromium.  🌎 [Clients](codeberg.org/Offerel/SyncMarks-Extension)) `AGPL-3.0` `PHP`


### Calendar & Contacts

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [CalDAV](en.wikipedia.org/wiki/CalDAV) and 🌎 [CardDAV](en.wikipedia.org/wiki/CardDAV) protocol servers and web clients/interfaces for 🌎 [Electronic calendar](en.wikipedia.org/wiki/Calendaring_software), 🌎 [address book](en.wikipedia.org/wiki/Address_book) and 🌎 [contact management](en.wikipedia.org/wiki/Contact_manager).

_Related: [Groupware](#groupware)_

_See also: 🌎 [Comparison of CalDAV and CardDAV implementations - Wikipedia](en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations)_

- 🌎 [Baïkal](sabre.io/baikal/) - Lightweight CalDAV and CardDAV server based on sabre/dav. (<b><code>&nbsp;&nbsp;2979⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;305🍴</code></b> [Source Code](https://github.com/sabre-io/Baikal))) `GPL-3.0` `PHP`
- 🌎 [DAViCal](www.davical.org/) - Server for calendar sharing (CalDAV) that uses a PostgreSQL database as a data store.  🌎 [Source Code](gitlab.com/davical-project/davical)) `GPL-2.0` `PHP/deb`
- <b><code>&nbsp;&nbsp;&nbsp;596⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Davis](https://github.com/tchapi/davis)) - A simple, dockerizable and fully translatable admin interface for sabre/dav based on Symfony 5 and Bootstrap 4, largely inspired by Baïkal. `MIT` `PHP`
- 🌎 [Manage My Damn Life](intri.in/manage-my-damn-life/) - Manage my Damn Life (MMDL) is a self-hosted front end for managing your CalDAV tasks and calendars. (<b><code>&nbsp;&nbsp;&nbsp;484⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Source Code](https://github.com/intri-in/manage-my-damn-life-nextjs))) `GPL-3.0` `Nodejs/Docker`
- 🌎 [Radicale](radicale.org/) - Simple calendar and contact server with extremely low administrative overhead. (<b><code>&nbsp;&nbsp;4200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;488🍴</code></b> [Source Code](https://github.com/Kozea/Radicale))) `GPL-3.0` `Python/deb`
- 🌎 [SabreDAV](sabre.io/) - Open source CardDAV, CalDAV, and WebDAV framework and server. (<b><code>&nbsp;&nbsp;1668⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;362🍴</code></b> [Source Code](https://github.com/sabre-io/dav))) `MIT` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Xandikos](https://github.com/jelmer/xandikos)) - Open source CardDAV and CalDAV server with minimal administrative overhead, backed by a Git repository. `GPL-3.0` `Python/deb`


### Communication - Custom Communication Systems

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Communication software](en.wikipedia.org/wiki/Communication_software) used to provide remote access to systems and exchange files and messages in text, audio and/or video formats between different computers or users, using their own custom protocols.

- 🌎 [AnyCable](anycable.io/) - Realtime server for reliable two-way communication over WebSockets, Server-sent events, etc.  🌎 [Demo](demo.anycable.io), <b><code>&nbsp;&nbsp;2212⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [Source Code](https://github.com/anycable/anycable))) `MIT` `Go/Docker`
- <b><code>&nbsp;15270⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;544🍴</code></b> [Apprise](https://github.com/caronc/apprise)) - Apprise allows you to send a notification to almost all of the most popular notification services available to us today such as: Telegram, Discord, Slack, Amazon SNS, Gotify, etc. `MIT` `Python/Docker/deb`
- 🌎 [Centrifugo](centrifugal.dev/) - Language-agnostic real-time messaging (Websocket or SockJS) server. (<b><code>&nbsp;&nbsp;9667⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;673🍴</code></b> [Demo](https://github.com/centrifugal/centrifugo#demo)), <b><code>&nbsp;&nbsp;9667⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;673🍴</code></b> [Source Code](https://github.com/centrifugal/centrifugo))) `MIT` `Go/Docker/K8S`
- 🌎 [Chitchatter](chitchatter.im/) - Peer-to-peer chat app that is serverless, decentralized, and ephemeral. (<b><code>&nbsp;&nbsp;2146⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;344🍴</code></b> [Source Code](https://github.com/jeremyckahn/chitchatter))) `GPL-2.0` `Nodejs`
- 🌎 [Conduit](conduit.rs/) - A simple, fast, and reliable chat server powered by Matrix.  🌎 [Source Code](gitlab.com/famedly/conduit)) `Apache-2.0` `Rust`
- <b><code>&nbsp;&nbsp;1373⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [Databag](https://github.com/balzack/databag)) - Federated, end-to-end encrypted messaging service for the web, iOS, and Android, supporting text, photos, video, and WebRTC video and audio calls.  🌎 [Demo](databag.coredb.org/#/create)) `Apache-2.0` `Docker`
- 🌎 [Element](element.io) - Fully-featured Matrix client for Web, iOS & Android. (<b><code>&nbsp;12391⭐</code></b> <b><code>&nbsp;&nbsp;2378🍴</code></b> [Source Code](https://github.com/element-hq/element-web))) `Apache-2.0` `Nodejs`
- 🌎 [GlobaLeaks](www.globaleaks.org/) - Whistleblowing software enabling anyone to easily set up and maintain a secure reporting platform.  🌎 [Demo](demo.globaleaks.org), <b><code>&nbsp;&nbsp;1421⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;319🍴</code></b> [Source Code](https://github.com/globaleaks/globaleaks-whistleblowing-software))) `AGPL-3.0` `Python/deb/Docker`
- 🌎 [GNUnet](gnunet.org/) - Software framework for decentralized, peer-to-peer networking.  🌎 [Source Code](gnunet.org/git/)) `GPL-3.0` `C`
- 🌎 [Gotify](gotify.net/) - Notification server with Android and CLI clients (alternative to PushBullet). (<b><code>&nbsp;14309⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;797🍴</code></b> [Source Code](https://github.com/gotify/server)), <b><code>&nbsp;&nbsp;1246⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [Clients](https://github.com/gotify/android))) `MIT` `Go/Docker`
- 🌎 [Hyphanet](hyphanet.org/) - Anonymously share files, browse and publish _freesites_ (web sites accessible only through Hyphanet) and chat on forums. (<b><code>&nbsp;&nbsp;1122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;231🍴</code></b> [Source Code](https://github.com/hyphanet/fred))) `GPL-2.0` `Java`
- 🌎 [Jami](jami.net/) - Universal communication platform which preserves the user's privacy and freedoms.  🌎 [Source Code](git.jami.net/savoirfairelinux?sort=latest_activity_desc&filter=jami)) `GPL-3.0` `C++`
- 🌎 [Live Helper Chat](livehelperchat.com/) - Live Support chat for your website. (<b><code>&nbsp;&nbsp;2173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;737🍴</code></b> [Source Code](https://github.com/LiveHelperChat/livehelperchat))) `Apache-2.0` `PHP`
- 🌎 [Mattermost](mattermost.com/) - Platform for secure collaboration across the entire software development lifecycle, can be integrated with Gitlab (alternative to Slack). (<b><code>&nbsp;34726⭐</code></b> <b><code>&nbsp;&nbsp;8230🍴</code></b> [Source Code](https://github.com/mattermost/mattermost))) `AGPL-3.0/Apache-2.0` `Go/Docker/K8S`
- 🌎 [Mumble](wiki.mumble.info/wiki/Main_Page) - Low-latency, high quality voice/text chat software. (<b><code>&nbsp;&nbsp;7488⭐</code></b> <b><code>&nbsp;&nbsp;1261🍴</code></b> [Source Code](https://github.com/mumble-voip/mumble)), 🌎 [Clients](wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++/deb`
- <b><code>&nbsp;&nbsp;&nbsp;845⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Notifo](https://github.com/notifo-io/notifo)) - Multichannel notification server with support for Email, Mobile Push, Web Push, SMS, messaging and a javascript plugin. `MIT` `C#`
- 🌎 [Novu](novu.co/) - Notification infrastructure for developers. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/novuhq/novu/))) `MIT` `Docker/Nodejs`
- 🌎 [ntfy](ntfy.sh/) - Push notifications to phone or desktop using HTTP PUT/POST, with Android app, CLI and web app, similar to Pushover and Gotify.  🌎 [Demo](ntfy.sh/app), <b><code>&nbsp;27880⭐</code></b> <b><code>&nbsp;&nbsp;1136🍴</code></b> [Source Code](https://github.com/binwiederhier/ntfy)), <b><code>&nbsp;&nbsp;&nbsp;855⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;189🍴</code></b> [Clients](https://github.com/binwiederhier/ntfy-android))) `Apache-2.0/GPL-2.0` `Go/Docker/K8S`
- 🌎 [One Time Secret](docs.onetimesecret.com) - Share sensitive information securely with self-destructing links that are only viewable once.  🌎 [Demo](onetimesecret.com), <b><code>&nbsp;&nbsp;2643⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;421🍴</code></b> [Source Code](https://github.com/onetimesecret/onetimesecret))) `MIT` `Docker/Ruby/Nodejs`
- 🌎 [OTS](ots.fyi/) - One-Time-Secret sharing platform with a symmetric 256bit AES encryption in the browser. (<b><code>&nbsp;&nbsp;&nbsp;710⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Source Code](https://github.com/Luzifer/ots))) `Apache-2.0` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [PushBits](https://github.com/pushbits/server)) - Notification server for relaying push notifications via Matrix, similar to PushBullet and Gotify. `ISC` `Go`
- 🌎 [RetroShare](retroshare.cc) - Secured and decentralized communication system. Offers decentralized chat, forums, messaging, file transfer. (<b><code>&nbsp;&nbsp;1899⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;301🍴</code></b> [Source Code](https://github.com/RetroShare/RetroShare))) `GPL-2.0` `C++`
- 🌎 [Revolt](revolt.chat/) - Revolt is a user-first chat platform built with modern web technologies. (<b><code>&nbsp;&nbsp;1579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [Source Code](https://github.com/revoltchat/self-hosted))) `AGPL-3.0` `Rust`
- 🌎 [Rocket.Chat](rocket.chat/) - Communications platform that puts data protection first (alternative to Gitter.im and Slack). (<b><code>&nbsp;44172⭐</code></b> <b><code>&nbsp;12744🍴</code></b> [Source Code](https://github.com/RocketChat/Rocket.Chat))) `MIT` `Nodejs/Docker/K8S`
- 🌎 [SAMA](samacloud.io) - Next-Gen self-hosted chat server and clients.  🌎 [Demo](app.samacloud.io/demo), <b><code>&nbsp;&nbsp;&nbsp;146⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Source Code](https://github.com/SAMA-Communications/sama-server)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Clients](https://github.com/SAMA-Communications/sama-client))) `GPL-3.0` `Nodejs/Docker`
- 🌎 [Screego](screego.net) - Screego is a simple tool to quickly share your screen to one or multiple people via web browser.  🌎 [Demo](app.screego.net/), <b><code>&nbsp;10092⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;699🍴</code></b> [Source Code](https://github.com/screego/server))) `GPL-3.0` `Docker/Go`
- <b><code>&nbsp;&nbsp;&nbsp;413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Shhh](https://github.com/smallwat3r/shhh)) - Keep secrets out of emails or chat logs, share them using secure links with passphrase and expiration dates. `MIT` `Python`
- <b><code>&nbsp;10107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;536🍴</code></b> [SimpleX Chat](https://github.com/simplex-chat/simplex-chat)) - The most private and secure chat and applications platform - now with double ratchet E2E encryption. `AGPL-3.0` `Haskell`
- 🌎 [Spectrum 2](spectrum.im/) - Spectrum 2 is an open source instant messaging transport.  It allows users to chat together even when they are using different IM networks. (<b><code>&nbsp;&nbsp;&nbsp;413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/SpectrumIM/spectrum2))) `GPL-3.0` `C++`
- 🌎 [Synapse](element-hq.github.io/synapse/latest/index.html) - Server for 🌎 [Matrix](matrix.org/), an open standard for decentralized persistent communication. (<b><code>&nbsp;&nbsp;3278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;430🍴</code></b> [Source Code](https://github.com/element-hq/synapse))) `Apache-2.0` `Python/deb`
- 🌎 [Tailchat](tailchat.msgbyte.com/) - Next generation noIM application in your own workspace, not only another Slack/Discord/rocket.chat.  🌎 [Demo](nightly.paw.msgbyte.com/), <b><code>&nbsp;&nbsp;3490⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;381🍴</code></b> [Source Code](https://github.com/msgbyte/tailchat))) `Apache-2.0` `Docker/K8S/Nodejs`
- 🌎 [Tiledesk](tiledesk.com) - All-in-one customer engagement platform from lead-gen to post-sales, from WhatsApp to your website. With omni-channel live agents and AI-powered chatbots (alternative to Intercom, Zendesk, Tawk.to and Tidio). (<b><code>&nbsp;&nbsp;&nbsp;266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Source Code](https://github.com/Tiledesk/tiledesk))) `MIT` `Docker/K8S`
- [Tinode](https://github.com/tinode) - Instant messaging platform. Backend in Go. Clients: Swift iOS, Java Android, JS webapp, scriptable command line; chatbots.  🌎 [Demo](sandbox.tinode.co/), <b><code>&nbsp;12996⭐</code></b> <b><code>&nbsp;&nbsp;2017🍴</code></b> [Source Code](https://github.com/tinode/chat)), <b><code>&nbsp;&nbsp;&nbsp;343⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [Clients](https://github.com/tinode/webapp))) `GPL-3.0` `Go`
- 🌎 [Tox](tox.chat/) - Distributed, secure messenger with audio and video chat capabilities. (<b><code>&nbsp;&nbsp;2536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;304🍴</code></b> [Source Code](https://github.com/TokTok/c-toxcore))) `GPL-3.0` `C`
- 🌎 [Typebot](typebot.io) - Conversational app builder (alternative to Typeform and Landbot). (<b><code>&nbsp;&nbsp;9506⭐</code></b> <b><code>&nbsp;&nbsp;2884🍴</code></b> [Source Code](https://github.com/baptisteArno/typebot.io))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;2534⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;473🍴</code></b> [WBO](https://github.com/lovasoa/whitebophir)) - Web Whiteboard to collaborate in real-time on schemas, drawings, and notes.  🌎 [Demo](wbo.ophir.dev/)) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Zulip](zulip.org) - Zulip is a powerful, open source group chat application. (<b><code>&nbsp;24083⭐</code></b> <b><code>&nbsp;&nbsp;9185🍴</code></b> [Source Code](https://github.com/zulip/zulip))) `Apache-2.0` `Python`


### Communication - Email - Complete Solutions

**[`^        back to top        ^`](#awesome-selfhosted)**

Simple deployment of 🌎 [E-mail](en.wikipedia.org/wiki/Email) servers, e.g. for inexperienced or impatient admins.

- 🌎 [AnonAddy](anonaddy.com) - Email forwarding service for creating aliases. (<b><code>&nbsp;&nbsp;4266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;238🍴</code></b> [Source Code](https://github.com/anonaddy/anonaddy))) `MIT` `PHP/Docker`
- 🌎 [b1gMail](www.b1gmail.eu) - Complete email solution that runs on any webspace with PHP and MariaDB. It supports POP3 catchall mailboxes and can also integrate with Postfix or b1gMailServer if you're running your own server.  🌎 [Source Code](codeberg.org/b1gMail/b1gMail), 🌎 [Clients](www.b1gmail.eu/en/start/addon-b1gmailserver/)) `GPL-2.0` `PHP`
- 🌎 [DebOps](docs.debops.org/) - Your Debian-based data center in a box. A set of general-purpose Ansible roles that can be used to manage Debian or Ubuntu hosts. (<b><code>&nbsp;&nbsp;1358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;369🍴</code></b> [Source Code](https://github.com/debops/debops))) `GPL-3.0` `Ansible/Python`
- 🌎 [docker-mailserver](docker-mailserver.github.io/docker-mailserver/edge/) - Production-ready fullstack but simple mail server (SMTP, IMAP, LDAP, Antispam, Antivirus, etc.) running inside a container. Only configuration files, no SQL database. (<b><code>&nbsp;17631⭐</code></b> <b><code>&nbsp;&nbsp;1993🍴</code></b> [Source Code](https://github.com/docker-mailserver/docker-mailserver))) `MIT` `Docker`
- 🌎 [Dovel](dovel.email) - SMTP server that sends and receives emails according to a simple configuration file, with an optional web interface that you can use to browse your emails.  🌎 [Source Code](dovel.email/server/tree.html)) `LGPL-3.0` `Go`
- <b><code>&nbsp;&nbsp;2100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;332🍴</code></b> [emailwiz](https://github.com/LukeSmithxyz/emailwiz)) - Luke Smith's bash script to completely automate the setup of a Postfix/Dovecot/SpamAssassin/OpenDKIM server on debian. `GPL-3.0` `Shell`
- 🌎 [Inboxen](inboxen.org) - Lets you have an infinite number of unique inboxes.  🌎 [Source Code](codeberg.org/Inboxen/Inboxen)) `GPL-3.0` `Python`
- 🌎 [iRedMail](www.iredmail.org/) - Full-featured mail server solution based on Postfix and Dovecot. (<b><code>&nbsp;&nbsp;1738⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [Source Code](https://github.com/iredmail/iRedMail))) `GPL-3.0` `Shell`
- 🌎 [Maddy Mail Server](maddy.email/) - All-in-one mail server that implements SMTP (both MTA and MX) and IMAP. Replaces Postfix, Dovecot, OpenDKIM, OpenSPF, OpenDMARC with single daemon. (<b><code>&nbsp;&nbsp;5774⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;303🍴</code></b> [Source Code](https://github.com/foxcpp/maddy))) `GPL-3.0` `Go`
- 🌎 [Mail-in-a-Box](mailinabox.email/) - Turns any Ubuntu server into a fully functional mail server with one command. (<b><code>&nbsp;15102⭐</code></b> <b><code>&nbsp;&nbsp;1525🍴</code></b> [Source Code](https://github.com/mail-in-a-box/mailinabox))) `CC0-1.0` `Shell`
- 🌎 [Mailcow](mailcow.email/) - Mail server suite based on Dovecot, Postfix and other open source software, that provides a modern Web UI for administration. (<b><code>&nbsp;11810⭐</code></b> <b><code>&nbsp;&nbsp;1581🍴</code></b> [Source Code](https://github.com/mailcow/mailcow-dockerized))) `GPL-3.0` `Docker/PHP`
- 🌎 [Mailu](mailu.io/) - Simple yet full-featured mail server as a set of Docker images. (<b><code>&nbsp;&nbsp;6980⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;952🍴</code></b> [Source Code](https://github.com/Mailu/Mailu))) `MIT` `Docker/Python`
- 🌎 [Modoboa](modoboa.org/en/) - Mail hosting and management platform including a modern and simplified web user interface. (<b><code>&nbsp;&nbsp;3424⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;453🍴</code></b> [Source Code](https://github.com/modoboa/modoboa))) `ISC` `Python`
- 🌎 [Mox](www.xmox.nl/) - Complete e-mail solution with IMAP4, SMTP, SPF, DKIM, DMARC, MTA-STS, DANE and DNSSEC, reputation-based and content-based junk filtering, Internationalization (IDNA), automatic TLS with ACME and Let's Encrypt, account autoconfiguration, and webmail. (<b><code>&nbsp;&nbsp;5323⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [Source Code](https://github.com/mjl-/mox))) `MIT` `Go`
- 🌎 [Postal](docs.postalserver.io/) - Complete and fully featured mail server for use by websites & web servers. (<b><code>&nbsp;16153⭐</code></b> <b><code>&nbsp;&nbsp;1191🍴</code></b> [Source Code](https://github.com/postalserver/postal))) `MIT` `Docker/Ruby`
- 🌎 [Simple NixOS Mailserver](gitlab.com/simple-nixos-mailserver/nixos-mailserver) - Complete mailserver solution leveraging the Nix Ecosystem. `GPL-3.0` `Nix`
- 🌎 [SimpleLogin](simplelogin.io) - Open source email alias solution to protect your email address. Comes with browser extensions and mobile apps. (<b><code>&nbsp;&nbsp;6291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;553🍴</code></b> [Source Code](https://github.com/simple-login/app))) `MIT` `Docker/Python`
- 🌎 [Stalwart Mail Server](stalw.art) - All-in-one mail server with JMAP, IMAP4, and SMTP support and a wide range of modern features. (<b><code>&nbsp;10777⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;571🍴</code></b> [Source Code](https://github.com/stalwartlabs/stalwart))) `AGPL-3.0` `Rust/Docker`
- 🌎 [wildduck](wildduck.email/) - Scalable no-SPOF IMAP/POP3 mail server. (<b><code>&nbsp;&nbsp;2059⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;275🍴</code></b> [Source Code](https://github.com/zone-eu/wildduck))) `EUPL-1.2` `Nodejs/Docker`


### Communication - Email - Mail Delivery Agents

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Mail Delivery Agents](en.wikipedia.org/wiki/Message_delivery_agent) (MDAs) - 🌎 [IMAP](en.wikipedia.org/wiki/Internet_Message_Access_Protocol) 🌎 [POP3](en.wikipedia.org/wiki/Post_Office_Protocol) server software.

- 🌎 [Cyrus IMAP](www.cyrusimap.org/) - Email (IMAP/POP3), contacts and calendar server. (<b><code>&nbsp;&nbsp;&nbsp;614⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [Source Code](https://github.com/cyrusimap/cyrus-imapd))) `BSD-3-Clause-Attribution` `C`
- 🌎 [DavMail](davmail.sourceforge.net/) `⚠` - POP/IMAP/SMTP/Caldav/Carddav/LDAP exchange gateway allowing users to use any mail/calendar client with an Exchange server, even from the internet or behind a firewall through Outlook Web Access. (<b><code>&nbsp;&nbsp;&nbsp;686⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [Source Code](https://github.com/mguessan/davmail))) `GPL-2.0` `Java`
- 🌎 [Dovecot](www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind. (<b><code>&nbsp;&nbsp;1147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;321🍴</code></b> [Source Code](https://github.com/dovecot/core))) `MIT/LGPL-2.1` `C/deb`
- 🌎 [Piler](www.mailpiler.org/) - Feature-rich email archiving solution. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/jsuto/piler/))) `GPL-3.0` `C`


### Communication - Email - Mail Transfer Agents

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Mail Transfer Agents](en.wikipedia.org/wiki/Message_transfer_agent) (MTAs) - 🌎 [SMTP](en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol) servers.

- 🌎 [chasquid](blitiri.com.ar/p/chasquid/) - SMTP (email) server with a focus on simplicity, security, and ease of operation.  🌎 [Source Code](blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- 🌎 [Courier MTA](www.courier-mta.org/) - Fast, scalable, enterprise mail/groupware server providing ESMTP, IMAP, POP3, webmail, mailing list, basic web-based calendaring and scheduling services.  🌎 [Source Code](www.courier-mta.org/repo.html)) `GPL-3.0` `C/deb`
- <b><code>&nbsp;&nbsp;&nbsp;255⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [DragonFly](https://github.com/corecode/dma)) - A small MTA for home and office use. Works on Linux and FreeBSD. `BSD-3-Clause` `C`
- 🌎 [EmailRelay](emailrelay.sourceforge.net/) - A small and easy to configure SMTP and POP3 server for Windows and Linux.  🌎 [Source Code](sourceforge.net/p/emailrelay/code/HEAD/tree/)) `GPL-3.0` `C++`
- 🌎 [Exim](www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge.  🌎 [Source Code](git.exim.org/exim.git)) `GPL-3.0` `C/deb`
- 🌎 [Haraka](haraka.github.io/) - Fast, highly extensible, and event driven SMTP server. (<b><code>&nbsp;&nbsp;5511⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;690🍴</code></b> [Source Code](https://github.com/haraka/Haraka))) `MIT` `Nodejs`
- 🌎 [OpenSMTPD](opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project.  🌎 [Source Code](cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C/deb`
- <b><code>&nbsp;&nbsp;&nbsp;781⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [OpenTrashmail](https://github.com/HaschekSolutions/opentrashmail)) - Complete trashmail solution that exposes an SMTP server and has a web interface to manage received emails. Works with multiple and wildcard domains and is fully file based (no database needed). Includes RSS feeds and JSON API. `Apache-2.0` `Python/PHP/Docker`
- [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement. `IPL-1.0` `C/deb`
- 🌎 [Sendmail](www.proofpoint.com/us/products/email-protection/open-source-email-solution) - Message transfer agent (MTA). `Sendmail` `C/deb`


### Communication - Email - Mailing Lists and Newsletters

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Mailing list](en.wikipedia.org/wiki/Mailing_list) servers and mass mailing software - one message to many recipients.

- 🌎 [HyperKitty](wiki.list.org/HyperKitty) - Access GNU Mailman v3 archives.  🌎 [Demo](lists.mailman3.org/), 🌎 [Source Code](gitlab.com/mailman/hyperkitty)) `GPL-3.0` `Python`
- 🌎 [Keila](www.keila.io) - Reliable and easy-to-use newsletter tool (alternative to Mailchimp and Sendinblue).  🌎 [Demo](app.keila.io), <b><code>&nbsp;&nbsp;1916⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [Source Code](https://github.com/pentacent/keila))) `AGPL-3.0` `Docker`
- 🌎 [Listmonk](listmonk.app/) - High performance, self-hosted newsletter and mailing list manager with a modern dashboard.  🌎 [Demo](demo.listmonk.app/), <b><code>&nbsp;18497⭐</code></b> <b><code>&nbsp;&nbsp;1858🍴</code></b> [Source Code](https://github.com/knadh/listmonk))) `AGPL-3.0` `Go/Docker`
- 🌎 [Mailman](www.list.org/) - Manage electronic mail discussion and e-newsletter lists.  🌎 [Source Code](gitlab.com/mailman/)) `GPL-3.0` `Python`
- 🌎 [Mautic](www.mautic.org/) - Marketing automation software (email, social and more). (<b><code>&nbsp;&nbsp;9000⭐</code></b> <b><code>&nbsp;&nbsp;3113🍴</code></b> [Source Code](https://github.com/mautic/mautic))) `GPL-3.0` `PHP`
- 🌎 [phpList](www.phplist.org) - Newsletter and email marketing with advanced management of subscribers, bounces, and plugins. (<b><code>&nbsp;&nbsp;&nbsp;826⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;276🍴</code></b> [Source Code](https://github.com/phpList/phplist3))) `AGPL-3.0` `PHP`
- 🌎 [Postorius](docs.mailman3.org/projects/postorius/en/latest/) - Web user interface to access GNU Mailman.  🌎 [Source Code](gitlab.com/mailman/postorius/)) `GPL-3.0` `Python`
- 🌎 [Schleuder](schleuder.nadir.org/) - GPG-enabled mailing list manager with resending-capabilities.  🌎 [Source Code](0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- 🌎 [Sympa](www.sympa.community/) - Mailing list manager. (<b><code>&nbsp;&nbsp;&nbsp;280⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [Source Code](https://github.com/sympa-community/sympa))) `GPL-2.0` `Perl`


### Communication - Email - Webmail Clients

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Webmail](en.wikipedia.org/wiki/Webmail) clients.

- 🌎 [Cypht](cypht.org) - Feed reader for your email accounts. (<b><code>&nbsp;&nbsp;1384⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;199🍴</code></b> [Source Code](https://github.com/cypht-org/cypht))) `LGPL-2.1` `PHP`
- 🌎 [Roundcube](roundcube.net) - Browser-based IMAP client with an application-like user interface. (<b><code>&nbsp;&nbsp;6694⭐</code></b> <b><code>&nbsp;&nbsp;1731🍴</code></b> [Source Code](https://github.com/roundcube/roundcubemail))) `GPL-3.0` `PHP/deb`
- 🌎 [SnappyMail](snappymail.eu/) - Simple, modern, lightweight & fast web-based email client (fork of RainLoop).  🌎 [Demo](snappymail.eu/demo/), <b><code>&nbsp;&nbsp;1468⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [Source Code](https://github.com/the-djmaze/snappymail))) `AGPL-3.0` `PHP`
- 🌎 [SquirrelMail](squirrelmail.org) - Another browser-based IMAP client.  🌎 [Source Code](sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`


### Communication - IRC

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [IRC](en.wikipedia.org/wiki/Internet_Relay_Chat) communication software.

- 🌎 [Convos](convos.chat/) - Always online web IRC client.  🌎 [Demo](convos.chat/#instant-demo), <b><code>&nbsp;&nbsp;1144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Source Code](https://github.com/convos-chat/convos))) `Artistic-2.0` `Perl/Docker`
- 🌎 [Ergo](ergo.chat/) - Modern IRCv3 server written in Go, combining the features of an ircd, a services framework, and a bouncer. (<b><code>&nbsp;&nbsp;2997⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;218🍴</code></b> [Source Code](https://github.com/ergochat/ergo))) `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;969⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;183🍴</code></b> [Glowing Bear](https://github.com/glowing-bear/glowing-bear)) - A web frontend for WeeChat.  🌎 [Demo](www.glowing-bear.org)) `GPL-3.0` `Nodejs`
- 🌎 [InspIRCd](www.inspircd.org/) - Modular IRC server written in C++ for Linux, BSD, Windows, and macOS. (<b><code>&nbsp;&nbsp;1273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;275🍴</code></b> [Source Code](https://github.com/inspircd/inspircd))) `GPL-2.0` `C++/Docker`
- 🌎 [Kiwi IRC](kiwiirc.com/) - Responsive web IRC client with theming support.  🌎 [Demo](kiwiirc.com/nextclient/), <b><code>&nbsp;&nbsp;&nbsp;940⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;227🍴</code></b> [Source Code](https://github.com/kiwiirc/kiwiirc))) `Apache-2.0` `Nodejs`
- 🌎 [ngircd](ngircd.barton.de/) - Portable and lightweight Internet Relay Chat server for small or private networks. (<b><code>&nbsp;&nbsp;&nbsp;522⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Source Code](https://github.com/ngircd/ngircd))) `GPL-2.0` `C/deb`
- 🌎 [Quassel IRC](quassel-irc.org/) - Distributed IRC client, meaning that one (or multiple) client(s) can attach to and detach from a central core. (<b><code>&nbsp;&nbsp;&nbsp;758⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;223🍴</code></b> [Source Code](https://github.com/quassel/quassel))) `GPL-2.0` `C++`
- 🌎 [Robust IRC](robustirc.net/) - IRC without netsplits. Distributed IRC server, based on RobustSession protocol. (<b><code>&nbsp;&nbsp;&nbsp;192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/robustirc/robustirc))) `BSD-3-Clause` `Go`
- 🌎 [The Lounge](thelounge.chat/) - Self-hosted web IRC client.  🌎 [Demo](demo.thelounge.chat/), <b><code>&nbsp;&nbsp;6087⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;730🍴</code></b> [Source Code](https://github.com/thelounge/thelounge))) `MIT` `Nodejs/Docker`
- 🌎 [UnrealIRCd](www.unrealircd.org/) - Modular, advanced and highly configurable IRC server written in C for Linux, BSD, Windows, and macOS. (<b><code>&nbsp;&nbsp;&nbsp;482⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [Source Code](https://github.com/unrealircd/unrealircd))) `GPL-2.0` `C`
- 🌎 [Weechat](weechat.org/) - Fast, light and extensible chat client. (<b><code>&nbsp;&nbsp;3200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;348🍴</code></b> [Source Code](https://github.com/weechat/weechat))) `GPL-3.0` `C/Docker/deb`
- 🌎 [ZNC](wiki.znc.in/ZNC) - Advanced IRC bouncer. (<b><code>&nbsp;&nbsp;2087⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;388🍴</code></b> [Source Code](https://github.com/znc/znc))) `Apache-2.0` `C++/deb`


### Communication - SIP

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [SIP](en.wikipedia.org/wiki/Session_Initiation_Protocol) 🌎 [IPBX](en.wikipedia.org/wiki/IP_PBX) telephony software.

- 🌎 [Asterisk](www.asterisk.org/) - Easy to use but advanced IP PBX system, VoIP gateway and conference server. (<b><code>&nbsp;&nbsp;2970⭐</code></b> <b><code>&nbsp;&nbsp;1163🍴</code></b> [Source Code](https://github.com/asterisk/asterisk))) `GPL-2.0` `C/deb`
- 🌎 [Flexisip](www.linphone.org/en/flexisip-sip-server/) - Complete, modular and scalable SIP server, includes a push gateway, to deliver SIP incoming calls or text messages on mobile device platforms where push notifications are required to receive information when the app is not active in the foreground. (<b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [Source Code](https://github.com/BelledonneCommunications/flexisip))) `AGPL-3.0` `C/Docker`
- 🌎 [Freepbx](www.freepbx.org) - Web-based open source GUI that controls and manages Asterisk.  🌎 [Source Code](git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- 🌎 [FreeSWITCH](freeswitch.org/) - Scalable open source cross-platform telephony platform. (<b><code>&nbsp;&nbsp;4517⭐</code></b> <b><code>&nbsp;&nbsp;1681🍴</code></b> [Source Code](https://github.com/signalwire/freeswitch))) `MPL-2.0` `C`
- 🌎 [FusionPBX](www.fusionpbx.com/) - Web interface for multi-platform voice switch called FreeSWITCH. (<b><code>&nbsp;&nbsp;&nbsp;954⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;726🍴</code></b> [Source Code](https://github.com/fusionpbx/fusionpbx))) `MPL-1.1` `PHP`
- 🌎 [Kamailio](www.kamailio.org/w/) - Modular SIP server (registrar/proxy/router/etc). (<b><code>&nbsp;&nbsp;2669⭐</code></b> <b><code>&nbsp;&nbsp;1056🍴</code></b> [Source Code](https://github.com/kamailio/kamailio))) `GPL-2.0` `C/deb`
- 🌎 [openSIPS](opensips.org/) - SIP proxy/server for voice, video, IM, presence and any other SIP extensions. (<b><code>&nbsp;&nbsp;1424⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;629🍴</code></b> [Source Code](https://github.com/OpenSIPS/opensips))) `GPL-2.0` `C`
- 🌎 [Routr](routr.io) - Lightweight SIP proxy, location server, and registrar for a reliable and scalable SIP infrastructure. (<b><code>&nbsp;&nbsp;1636⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [Source Code](https://github.com/fonoster/routr))) `MIT` `Docker/K8S`
- 🌎 [SIP3](sip3.io/) - VoIP troubleshooting and monitoring platform.  🌎 [Demo](demo.sip3.io), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/sip3io/))) `Apache-2.0` `Java`
- 🌎 [SIPCAPTURE Homer](www.sipcapture.org/) - Troubleshooting and monitoring VoIP calls. (<b><code>&nbsp;&nbsp;1888⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;250🍴</code></b> [Source Code](https://github.com/sipcapture/homer))) `AGPL-3.0` `Nodejs/Go/Docker`
- 🌎 [Wazo](wazo-platform.org/) - Full-featured IPBX solution built atop Asterisk with integrated Web administration interface and REST-ful API. ([Source Code](https://github.com/wazo-platform)) `GPL-3.0` `Python`
- 🌎 [Yeti-Switch](yeti-switch.org/) - Transit class4 softswitch(SBC) with integrated billing and routing engine and REST API.  🌎 [Demo](yeti-switch.org/demo.html), [Source Code](https://github.com/yeti-switch)) `GPL-2.0` `C++/Ruby`


### Communication - Social Networks and Forums

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Social Networking](en.wikipedia.org/wiki/Social_networking_service) and 🌎 [Forum](en.wikipedia.org/wiki/Internet_forum) software.

- 🌎 [Akkoma](akkoma.social/) - Federated microblogging server with Mastodon, GNU social, and ActivityPub compatibility.  🌎 [Source Code](akkoma.dev/AkkomaGang/akkoma)) `AGPL-3.0` `Elixir/Docker`
- 🌎 [Answer](answer.apache.org) - Knowledge-based community software. You can use it to quickly build your Q&A community for product technical support, customer support, user communication, and more. (<b><code>&nbsp;15226⭐</code></b> <b><code>&nbsp;&nbsp;1255🍴</code></b> [Source Code](https://github.com/apache/answer))) `Apache-2.0` `Docker/Go`
- 🌎 [Artalk](artalk.js.org/) - Comment system built in Golang, providing a lightweight and highly customizable solution for adding comments to your website. (<b><code>&nbsp;&nbsp;2160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [Source Code](https://github.com/ArtalkJS/Artalk))) `MIT` `Go/Docker`
- 🌎 [AsmBB](board.asm32.info) - Fast, SQLite-powered forum engine written in ASM.  🌎 [Source Code](asm32.info/fossil/asmbb/index)) `EUPL-1.2` `Assembly`
- 🌎 [BuddyPress](buddypress.org/about/) - Powerful plugin that takes your WordPress.org powered site beyond the blog with social-network features like user profiles, activity streams, user groups, and more. (<b><code>&nbsp;&nbsp;&nbsp;240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [Source Code](https://github.com/buddypress/BuddyPress))) `GPL-2.0` `PHP`
- 🌎 [Chirpy](chirpy.dev) - Privacy-friendly and customizable Disqus (comment system) alternate.  🌎 [Demo](chirpy.dev/play), <b><code>&nbsp;&nbsp;&nbsp;589⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Source Code](https://github.com/devrsi0n/chirpy))) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Coral](coralproject.net/) - A better commenting experience from Vox Media. (<b><code>&nbsp;&nbsp;1966⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;367🍴</code></b> [Source Code](https://github.com/coralproject/talk))) `Apache-2.0` `Docker/Nodejs`
- 🌎 [diaspora*](diasporafoundation.org/) - Distributed social networking server. (<b><code>&nbsp;13843⭐</code></b> <b><code>&nbsp;&nbsp;2906🍴</code></b> [Source Code](https://github.com/diaspora/diaspora))) `AGPL-3.0` `Ruby`
- 🌎 [Discourse](www.discourse.org/) - Advanced forum / community solution based on Ruby and JS.  🌎 [Demo](try.discourse.org/), <b><code>&nbsp;45863⭐</code></b> <b><code>&nbsp;&nbsp;8758🍴</code></b> [Source Code](https://github.com/discourse/discourse))) `GPL-2.0` `Docker`
- 🌎 [Elgg](elgg.org/) - Powerful open source social networking engine. (<b><code>&nbsp;&nbsp;1673⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;664🍴</code></b> [Source Code](https://github.com/Elgg/Elgg))) `GPL-2.0` `PHP`
- 🌎 [Enigma 1/2 BBS](nuskooler.github.io/enigma-bbs/) - Enigma 1/2 is a modern, multi-platform BBS engine with unlimited "callers" and legacy DOS door game support. (<b><code>&nbsp;&nbsp;&nbsp;611⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [Source Code](https://github.com/NuSkooler/enigma-bbs))) `BSD-2-Clause` `Shell/Docker/Nodejs`
- 🌎 [Flarum](flarum.org) - Delightfully simple forums. Flarum is the next-generation forum software that makes online discussion fun again. (<b><code>&nbsp;16130⭐</code></b> <b><code>&nbsp;&nbsp;1673🍴</code></b> [Source Code](https://github.com/flarum/flarum))) `MIT` `PHP`
- 🌎 [Friendica](friendi.ca/) - Social Communication Server. (<b><code>&nbsp;&nbsp;1617⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;365🍴</code></b> [Source Code](https://github.com/friendica/friendica))) `AGPL-3.0` `PHP`
- 🌎 [GoToSocial](docs.gotosocial.org/en/latest/) - ActivityPub federated social network server implementing the Mastodon client API.  🌎 [Source Code](codeberg.org/superseriousbusiness/gotosocial)) `AGPL-3.0` `Docker/Go`
- 🌎 [Hatsu](hatsu.cli.rs/) - Bridge that interacts with Fediverse on behalf of your static site. (<b><code>&nbsp;&nbsp;&nbsp;224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Source Code](https://github.com/importantimport/hatsu))) `AGPL-3.0` `Docker/Rust`
- 🌎 [Hubzilla](hubzilla.org) - Decentralized identity, privacy, publishing, sharing, cloud storage, and communications/social platform.  🌎 [Source Code](framagit.org/hubzilla/core)) `MIT` `PHP`
- 🌎 [HumHub](www.humhub.org/) - Flexible kit for private social networks. (<b><code>&nbsp;&nbsp;6594⭐</code></b> <b><code>&nbsp;&nbsp;1685🍴</code></b> [Source Code](https://github.com/humhub/humhub))) `AGPL-3.0` `PHP`
- 🌎 [Iceshrimp.NET](iceshrimp.net) - Federated microblogging server that communicates over ActivityPub.  🌎 [Source Code](iceshrimp.dev/iceshrimp/iceshrimp.net)) `EUPL-1.2` `.NET/C#/Docker`
- 🌎 [Isso](isso-comments.de/) - Lightweight commenting server written in Python and Javascript. It aims to be a drop-in replacement for Disqus. (<b><code>&nbsp;&nbsp;5211⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;452🍴</code></b> [Source Code](https://github.com/isso-comments/isso))) `MIT` `Python/Docker`
- 🌎 [Lemmy](join-lemmy.org/) - Link aggregator for the fediverse (alternative to Reddit). (<b><code>&nbsp;14170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;937🍴</code></b> [Source Code](https://github.com/LemmyNet/lemmy))) `AGPL-3.0` `Docker/Rust`
- 🌎 [Loomio](www.loomio.org/) - Collaborative decision-making tool that makes it easy for anyone to participate in decisions which affect them. (<b><code>&nbsp;&nbsp;2505⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;696🍴</code></b> [Source Code](https://github.com/loomio/loomio))) `AGPL-3.0` `Docker`
- 🌎 [Mastodon](joinmastodon.org/) - Federated microblogging server. (<b><code>&nbsp;49411⭐</code></b> <b><code>&nbsp;&nbsp;7378🍴</code></b> [Source Code](https://github.com/mastodon/mastodon)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Clients](https://github.com/hyperupcall/awesome-mastodon))) `AGPL-3.0` `Ruby`
- 🌎 [Misago](misago-project.org/) - Fully featured modern forum application that is fast, scalable and responsive. (<b><code>&nbsp;&nbsp;2702⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;549🍴</code></b> [Source Code](https://github.com/rafalp/Misago))) `GPL-2.0` `Docker`
- 🌎 [Misskey](misskey.io/) - Decentralized app-like microblogging server/SNS for the Fediverse, using the ActivityPub protocol like GNU social and Mastodon. (<b><code>&nbsp;10877⭐</code></b> <b><code>&nbsp;&nbsp;1538🍴</code></b> [Source Code](https://github.com/misskey-dev/misskey))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Movim](movim.eu/) - Modern, federated social network based on XMPP, with a fully featured group-chat, subscriptions and microblogging. (<b><code>&nbsp;&nbsp;1860⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;262🍴</code></b> [Source Code](https://github.com/movim/movim))) `AGPL-3.0` `PHP/Docker`
- 🌎 [MyBB](mybb.com/) - Free, extensible forum software package. (<b><code>&nbsp;&nbsp;1184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;430🍴</code></b> [Source Code](https://github.com/mybb/mybb))) `LGPL-3.0` `PHP`
- 🌎 [NodeBB](nodebb.org/) - Forum software built for the modern web.  🌎 [Demo](try.nodebb.org/), <b><code>&nbsp;14875⭐</code></b> <b><code>&nbsp;&nbsp;2931🍴</code></b> [Source Code](https://github.com/NodeBB/NodeBB))) `GPL-3.0` `Nodejs/Docker`
- 🌎 [OSSN](www.opensource-socialnetwork.org/) - Social networking software that allows you to make a social networking website and helps your members build social relationships, with people who share similar professional or personal interests. (<b><code>&nbsp;&nbsp;1177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;547🍴</code></b> [Source Code](https://github.com/opensource-socialnetwork/opensource-socialnetwork))) `CAL-1.0` `PHP`
- 🌎 [phpBB](www.phpbb.com/) - Flat-forum bulletin board software solution that can be used to stay in touch with a group of people or can power your entire website. (<b><code>&nbsp;&nbsp;2007⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;994🍴</code></b> [Source Code](https://github.com/phpbb/phpbb))) `GPL-2.0` `PHP`
- 🌎 [PixelFed](pixelfed.social) - Ethical photo sharing platform, powered by ActivityPub federation (alternative to Instagram). (<b><code>&nbsp;&nbsp;6830⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;812🍴</code></b> [Source Code](https://github.com/pixelfed/pixelfed))) `AGPL-3.0` `PHP`
- 🌎 [Pleroma](pleroma.social) - Federated microblogging server, Mastodon, GNU social, & ActivityPub compatible.  🌎 [Source Code](git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- 🌎 [qpixel](codidact.com/) - Q&A-based community knowledge-sharing software. (<b><code>&nbsp;&nbsp;&nbsp;435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [Source Code](https://github.com/codidact/qpixel))) `AGPL-3.0` `Ruby`
- <b><code>&nbsp;&nbsp;2927⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [Redlib](https://github.com/redlib-org/redlib)) `⚠` - An alternative private front-end to Reddit, with its origins in Libreddit. `AGPL-3.0` `Rust`
- 🌎 [remark42](remark42.com/) - Lightweight and simple comment engine, which doesn't spy on users. It can be embedded into blogs, articles or any other place where readers add comments.  🌎 [Demo](remark42.com/demo/), <b><code>&nbsp;&nbsp;5337⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;422🍴</code></b> [Source Code](https://github.com/umputun/remark42))) `MIT` `Docker/Go`
- 🌎 [Scoold](scoold.com) - Stack Overflow in a JAR. An enterprise-ready Q&A platform with full-text search, SAML, LDAP integration and social login support.  🌎 [Demo](live.scoold.com), <b><code>&nbsp;&nbsp;&nbsp;910⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;234🍴</code></b> [Source Code](https://github.com/Erudika/scoold))) `Apache-2.0` `Java/Docker/K8S`
- 🌎 [Simple Machines Forum](www.simplemachines.org/) - Free, professional grade software package that allows you to set up your own online community within minutes. (<b><code>&nbsp;&nbsp;&nbsp;685⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;264🍴</code></b> [Source Code](https://github.com/SimpleMachines/SMF))) `BSD-3-Clause` `PHP`
- 🌎 [Socialhome](socialhome.network) - Federated and decentralized profile builder and social network engine.  🌎 [Demo](socialhome.network/), <b><code>&nbsp;&nbsp;&nbsp;375⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [Source Code](https://github.com/jaywink/socialhome))) `AGPL-3.0` `Docker/Python`
- 🌎 [Talkyard](www.talkyard.io/) - Create a community, where your users can suggest ideas and get questions answered. And have friendly open-ended discussions and chat (Slack/StackOverflow/Discourse/Reddit/Disqus hybrid).  🌎 [Demo](www.talkyard.io/forum/latest), <b><code>&nbsp;&nbsp;1801⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [Source Code](https://github.com/debiki/talkyard))) `AGPL-3.0` `Docker/Scala`
- 🌎 [yarn.social](yarn.social) - Self-Hosted, Twitter™-like Decentralised micro-logging platform. No ads, no tracking, your content, your data.  🌎 [Source Code](git.mills.io/yarnsocial/yarn)) `MIT` `Go`


### Communication - Video Conferencing

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Video/Web Conferencing](en.wikipedia.org/wiki/Web_conferencing) tools and software.

_Related: [Conference Management](#conference-management)_

- 🌎 [BigBlueButton](bigbluebutton.org/) - Supports real-time sharing of audio, video, slides (with whiteboard controls), chat, and the screen. Instructors can engage remote students with polling, emojis, and breakout rooms. (<b><code>&nbsp;&nbsp;8992⭐</code></b> <b><code>&nbsp;&nbsp;6005🍴</code></b> [Source Code](https://github.com/bigbluebutton/bigbluebutton))) `LGPL-3.0` `Java`
- 🌎 [Galene](galene.org/) - Video conferencing server that is easy to deploy and that requires moderate server resources. (<b><code>&nbsp;&nbsp;1197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [Source Code](https://github.com/jech/galene))) `MIT` `Go`
- 🌎 [Janus](janus.conf.meetecho.com/) - General-purpose, lightweight, minimalist WebRTC Server.  🌎 [Demo](janus.conf.meetecho.com/demos/), <b><code>&nbsp;&nbsp;8973⭐</code></b> <b><code>&nbsp;&nbsp;2606🍴</code></b> [Source Code](https://github.com/meetecho/janus-gateway))) `GPL-3.0` `C`
- 🌎 [Jitsi Meet](jitsi.org/Projects/JitsiMeet) - WebRTC application that uses Jitsi Videobridge to provide high quality, scalable video conferences.  🌎 [Demo](meet.jit.si), <b><code>&nbsp;28142⭐</code></b> <b><code>&nbsp;&nbsp;7671🍴</code></b> [Source Code](https://github.com/jitsi/jitsi-meet))) `Apache-2.0` `Nodejs/Docker/deb`
- 🌎 [Jitsi Video Bridge](jitsi.org/Projects/JitsiVideobridge) - WebRTC compatible Selective Forwarding Unit (SFU) that allows for multiuser video communication. (<b><code>&nbsp;&nbsp;3037⭐</code></b> <b><code>&nbsp;&nbsp;1017🍴</code></b> [Source Code](https://github.com/jitsi/jitsi-videobridge))) `Apache-2.0` `Java/deb`
- 🌎 [MiroTalk C2C](c2c.mirotalk.com) - Real-time cam-2-cam video calls & screen sharing, end-to-end encrypted, to embed in any website with a simple iframe. (<b><code>&nbsp;&nbsp;&nbsp;450⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [Source Code](https://github.com/miroslavpejic85/mirotalkc2c))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [MiroTalk P2P](p2p.mirotalk.com) - Simple, secure, fast real-time video conferences up to 4k and 60fps, compatible with all browsers and platforms.  🌎 [Demo](p2p.mirotalk.com/newcall), <b><code>&nbsp;&nbsp;4160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;694🍴</code></b> [Source Code](https://github.com/miroslavpejic85/mirotalk))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [MiroTalk SFU](sfu.mirotalk.com) - Simple, secure, scalable real-time video conferences up to 4k, compatible with all browsers and platforms.  🌎 [Demo](sfu.mirotalk.com/newroom), <b><code>&nbsp;&nbsp;2830⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;438🍴</code></b> [Source Code](https://github.com/miroslavpejic85/mirotalksfu))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [plugNmeet](www.plugnmeet.org/) - Scalable and high performance web conferencing system.  🌎 [Demo](demo.plugnmeet.com/login.html), <b><code>&nbsp;&nbsp;&nbsp;413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [Source Code](https://github.com/mynaparrot/plugNmeet-server))) `MIT` `Docker/Go`


### Communication - XMPP - Servers

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Extensible Messaging and Presence Protocol](en.wikipedia.org/wiki/XMPP) servers.

- 🌎 [ejabberd](www.ejabberd.im/) - XMPP instant messaging server. (<b><code>&nbsp;&nbsp;6509⭐</code></b> <b><code>&nbsp;&nbsp;1537🍴</code></b> [Source Code](https://github.com/processone/ejabberd))) `GPL-2.0` `Erlang/Docker`
- 🌎 [MongooseIM](www.erlang-solutions.com/products/mongooseim.html) - Mobile messaging platform with a focus on performance and scalability. (<b><code>&nbsp;&nbsp;1717⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;437🍴</code></b> [Source Code](https://github.com/esl/MongooseIM))) `GPL-2.0` `Erlang/Docker/K8S`
- 🌎 [Openfire](www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server. (<b><code>&nbsp;&nbsp;2979⭐</code></b> <b><code>&nbsp;&nbsp;1394🍴</code></b> [Source Code](https://github.com/igniterealtime/Openfire))) `Apache-2.0` `Java`
- 🌎 [Prosody IM](prosody.im/) - Feature-rich and easy to configure XMPP server.  🌎 [Source Code](hg.prosody.im/)) `MIT` `Lua`
- 🌎 [Snikket](snikket.org/) - All-in-one Dockerized easy XMPP solution, including web admin and clients. (<b><code>&nbsp;&nbsp;&nbsp;354⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Source Code](https://github.com/snikket-im/snikket-server)), 🌎 [Clients](snikket.org/app/)) `Apache-2.0` `Docker`
- 🌎 [Tigase](tigase.net/xmpp-server) - XMPP server implementation in Java. (<b><code>&nbsp;&nbsp;&nbsp;349⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [Source Code](https://github.com/tigase/tigase-server))) `GPL-3.0` `Java`


### Communication - XMPP - Web Clients

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Extensible Messaging and Presence Protocol](en.wikipedia.org/wiki/XMPP) Web clients/interfaces.

- 🌎 [Converse.js](conversejs.org/) - XMPP chat client in your browser. (<b><code>&nbsp;&nbsp;3194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;801🍴</code></b> [Source Code](https://github.com/conversejs/converse.js))) `MPL-2.0` `Javascript`
- 🌎 [Libervia](repos.goffi.org/libervia-web) - Web frontend from Salut à Toi. `AGPL-3.0` `Python`
- 🌎 [Salut à Toi](www.salut-a-toi.org/) - Multipurpose, multi frontend, libre and decentralized communication tool.  🌎 [Source Code](repos.goffi.org/libervia-backend)) `AGPL-3.0` `Python`


### Community-Supported Agriculture (CSA)

**[`^        back to top        ^`](#awesome-selfhosted)**

Management and administration tools for community supported agriculture and food cooperatives.

_Related: [E-commerce](#e-commerce)_

- 🌎 [ACP Admin](acp-admin.ch/) - CSA administration. Manage members, subscriptions, deliveries, drop-off locations, member participation, invoices and emails (documentation in French). (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Source Code](https://github.com/csa-admin-org/csa-admin))) `MIT` `Ruby`
- 🌎 [E-Label](filipecarneiro.github.io/ELabel/) - Solution for electronic labels, with QR Codes, on wine bottles sold within the European Union. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Source Code](https://github.com/filipecarneiro/ELabel))) `MIT` `Docker`
- 🌎 [FoodCoopShop](www.foodcoopshop.com/) - User-friendly software for food-coops. (<b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Source Code](https://github.com/foodcoopshop/foodcoopshop))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Foodsoft](foodcoops.net/) - Manage a non-profit food coop (product catalog, ordering, accounting, job scheduling). (<b><code>&nbsp;&nbsp;&nbsp;348⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [Source Code](https://github.com/foodcoops/foodsoft))) `AGPL-3.0` `Docker/Ruby`
- 🌎 [Hive-Pal](hivepal.app) - Mobile-first beekeeping management app for tracking hives, inspections, queen records, and equipment with streamlined data entry optimized for field use.  🌎 [Demo](hivepal.app), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Source Code](https://github.com/martinhrvn/hive-pal))) `MIT` `Nodejs/Docker`
- 🌎 [juntagrico](juntagrico.org/) - Management platform for community gardens and vegetable cooperatives. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Source Code](https://github.com/juntagrico/juntagrico))) `LGPL-3.0` `Python`
- 🌎 [Open Food Network](www.openfoodnetwork.org/) - Online marketplace for local food. It enables a network of independent online food stores that connect farmers and food hubs with individuals and local businesses. (<b><code>&nbsp;&nbsp;1218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;760🍴</code></b> [Source Code](https://github.com/openfoodfoundation/openfoodnetwork))) `AGPL-3.0` `Ruby`
- 🌎 [OpenOlitor](openolitor.org/) - Administration platform for Community Supported Agriculture groups. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/OpenOlitor/openolitor-server))) `AGPL-3.0` `Scala`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [teikei](https://github.com/teikei/teikei)) - A web application that maps out community-supported agriculture based on crowdsourced data.  🌎 [Demo](ernte-teilen.org/karte/#/)) `AGPL-3.0` `Nodejs`


### Conference Management

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for submission of 🌎 [abstracts](en.wikipedia.org/wiki/Abstract_management) and preparation/management of academic conferences.

- 🌎 [indico](getindico.io/) - Feature-rich event management system, made @ CERN, the place where the Web was born.  🌎 [Demo](sandbox.getindico.io/), <b><code>&nbsp;&nbsp;1996⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;509🍴</code></b> [Source Code](https://github.com/indico/indico))) `MIT` `Python`
- 🌎 [motion.tools (Antragsgrün)](motion.tools/) - Manage motions and amendments for (political) conventions.  🌎 [Demo](sandbox.motion.tools/createsite), <b><code>&nbsp;&nbsp;&nbsp;131⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Source Code](https://github.com/CatoTH/antragsgruen))) `AGPL-3.0` `PHP/Docker`
- 🌎 [OpenSlides](openslides.com/) - Presentation and assembly system for managing and projecting agenda, motions and elections of an assembly.  🌎 [Demo](demo.os4.openslides.com/login), <b><code>&nbsp;&nbsp;&nbsp;585⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [Source Code](https://github.com/OpenSlides/OpenSlides))) `MIT` `Docker`
- 🌎 [osem](osem.io/) - Event management tailored to free Software conferences. (<b><code>&nbsp;&nbsp;&nbsp;909⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;498🍴</code></b> [Source Code](https://github.com/openSUSE/osem))) `MIT` `Ruby/Docker`
- 🌎 [pretalx](pretalx.org) - Web-based event management, including running a Call for Papers, reviewing submissions, and scheduling talks. Exports and imports for various related tools. (<b><code>&nbsp;&nbsp;&nbsp;861⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;239🍴</code></b> [Source Code](https://github.com/pretalx/pretalx))) `Apache-2.0` `Python`


### Content Management Systems (CMS)

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Content Management Systems](en.wikipedia.org/wiki/Content_management_system) offer a practical way to setup a website with many features, using third party plugins, themes and functionality that are easy to add and customize.

_Related: [Blogging Platforms](#blogging-platforms), [Static Site Generators](#static-site-generators), [Photo Galleries](#photo-galleries)_

- 🌎 [Alfresco Community Edition](www.alfresco.com/products/community/download) - The open source Enterprise Content Management software that handles any type of content, allowing users to easily share and collaborate on content. (<b><code>&nbsp;&nbsp;&nbsp;193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [Source Code](https://github.com/Alfresco/alfresco-community-repo))) `LGPL-3.0` `Java`
- 🌎 [Apostrophe](apostrophecms.com/) - CMS with a focus on extensible in-context editing tools.  🌎 [Demo](apostrophecms.com/demo), <b><code>&nbsp;&nbsp;4506⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;620🍴</code></b> [Source Code](https://github.com/apostrophecms/apostrophe))) `MIT` `Nodejs`
- 🌎 [Automad](automad.org/) - Flat-file content management system and template engine.  🌎 [Demo](try.automad.org/), <b><code>&nbsp;&nbsp;&nbsp;844⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Source Code](https://github.com/marcantondahmen/automad))) `MIT` `PHP/Docker`
- 🌎 [Backdrop CMS](backdropcms.org/) - Comprehensive CMS for small to medium sized businesses and non-profits. (<b><code>&nbsp;&nbsp;1024⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;397🍴</code></b> [Source Code](https://github.com/backdrop/backdrop))) `GPL-2.0` `PHP`
- 🌎 [BigTree CMS](www.bigtreecms.org/) - Straightforward, well documented, and capable CMS. (<b><code>&nbsp;&nbsp;&nbsp;222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Source Code](https://github.com/bigtreecms/BigTree-CMS))) `LGPL-2.1` `PHP`
- 🌎 [Bludit](www.bludit.com/) `⚠` - Build a site or blog in seconds. Bludit uses flat-files (text files in JSON format) to store posts and pages. (<b><code>&nbsp;&nbsp;1379⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;308🍴</code></b> [Source Code](https://github.com/bludit/bludit))) `MIT` `PHP`
- 🌎 [CMS Made Simple](www.cmsmadesimple.org/) - Faster and easier management of website contents, scalable for small businesses to large corporations. ([Source Code](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-2.0` `PHP`
- 🌎 [Cockpit](getcockpit.com) - Simple content platform to manage any structured content. (<b><code>&nbsp;&nbsp;&nbsp;639⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Source Code](https://github.com/Cockpit-HQ/Cockpit))) `MIT` `PHP`
- 🌎 [Concrete 5 CMS](www.concretecms.com) - Open source content management system. (<b><code>&nbsp;&nbsp;&nbsp;821⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;464🍴</code></b> [Source Code](https://github.com/concretecms/concretecms))) `MIT` `PHP`
- 🌎 [Contao](contao.org/) - Powerful CMS that allows you to create professional websites and scalable web applications.  🌎 [Demo](demo.contao.org/contao), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/contao/contao/))) `LGPL-3.0` `PHP`
- 🌎 [CouchCMS](www.couchcms.com/) - CMS for designers. (<b><code>&nbsp;&nbsp;&nbsp;367⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [Source Code](https://github.com/CouchCMS/CouchCMS))) `CPAL-1.0` `PHP`
- 🌎 [Drupal](www.drupal.org/) - Advanced open source content management platform.  🌎 [Source Code](git.drupalcode.org/project/drupal)) `GPL-2.0` `PHP`
- 🌎 [eLabFTW](www.elabftw.net) - Online lab notebook for research labs. Store experiments, use a database to find reagents or protocols, use trusted timestamping to legally timestamp an experiment, export as pdf or zip archive, share with collaborators….  🌎 [Demo](demo.elabftw.net), <b><code>&nbsp;&nbsp;1226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;270🍴</code></b> [Source Code](https://github.com/elabftw/elabftw))) `AGPL-3.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;449⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Expressa](https://github.com/thomas4019/expressa)) - Content Management System for powering database driven websites using JSON schemas. Provides permission management and automatic REST APIs. `MIT` `Nodejs`
- 🌎 [Joomla!](www.joomla.org/) - Advanced Content Management System (CMS). (<b><code>&nbsp;&nbsp;5015⭐</code></b> <b><code>&nbsp;&nbsp;3753🍴</code></b> [Source Code](https://github.com/joomla/joomla-cms))) `GPL-2.0` `PHP`
- 🌎 [KeystoneJS](keystonejs.com/) - CMS and web application platform. (<b><code>&nbsp;&nbsp;9815⭐</code></b> <b><code>&nbsp;&nbsp;1247🍴</code></b> [Source Code](https://github.com/keystonejs/keystone))) `MIT` `Nodejs`
- 🌎 [Localess](localess.org/home) `⚠` - Powerful translation management and content management system. Manage and translate your website or app content into multiple languages, using AI to translate faster. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Source Code](https://github.com/Lessify/localess))) `MIT` `Docker`
- 🌎 [MODX](modx.com/) - Advanced content management and publishing platform. The current version is called 'Revolution'. (<b><code>&nbsp;&nbsp;1388⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;531🍴</code></b> [Source Code](https://github.com/modxcms/revolution))) `GPL-2.0` `PHP`
- 🌎 [Neos](www.neos.io) - Neos or TYPO3 Neos (for version 1) is a modern, open source CMS. ([Source Code](https://github.com/neos)) `GPL-3.0` `PHP`
- 🌎 [Noosfero](gitlab.com/noosfero/noosfero) - Platform for social and solidarity economy networks with blog, e-Portfolios, CMS, RSS, thematic discussion, events agenda and collective intelligence for solidarity economy in the same system. `AGPL-3.0` `Ruby`
- 🌎 [Omeka](omeka.org) - Create complex narratives and share rich collections, adhering to Dublin Core standards with Omeka on your server, designed for scholars, museums, libraries, archives, and enthusiasts.  🌎 [Demo](omeka.org/classic/showcase/), <b><code>&nbsp;&nbsp;&nbsp;522⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;206🍴</code></b> [Source Code](https://github.com/omeka/Omeka))) `GPL-3.0` `PHP`
- 🌎 [Payload CMS](payloadcms.com/) - Developer-first headless CMS and application framework. (<b><code>&nbsp;39538⭐</code></b> <b><code>&nbsp;&nbsp;3211🍴</code></b> [Source Code](https://github.com/payloadcms/payload))) `MIT` `Nodejs`
- [Pimcore](http://www.pimcore.com/) - Multi-channel experience and engagement management platform. (<b><code>&nbsp;&nbsp;3691⭐</code></b> <b><code>&nbsp;&nbsp;1497🍴</code></b> [Source Code](https://github.com/pimcore/pimcore))) `GPL-3.0` `PHP/Docker`
- 🌎 [Plone](plone.org/) - Powerful open-source CMS system. ([Source Code](https://github.com/plone)) `ZPL-2.0` `Python/Docker`
- 🌎 [Publify](publify.github.io/) - Simple but full featured web publishing software. (<b><code>&nbsp;&nbsp;1855⭐</code></b> <b><code>&nbsp;&nbsp;3657🍴</code></b> [Source Code](https://github.com/publify/publify))) `MIT` `Ruby`
- 🌎 [REDAXO](www.redaxo.org) - Simple, flexible and useful content management system (documentation in German). (<b><code>&nbsp;&nbsp;&nbsp;347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [Source Code](https://github.com/redaxo/redaxo))) `MIT` `PHP/Docker`
- 🌎 [Roadiz](www.roadiz.io/) - Modern CMS based on a node system which can handle many types of services. (<b><code>&nbsp;&nbsp;&nbsp;374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Source Code](https://github.com/roadiz/roadiz))) `MIT` `PHP`
- 🌎 [SilverStripe](www.silverstripe.org) - Easy to use CMS with powerful MVC framework underlying.  🌎 [Demo](demo.silverstripe.org/), [Source Code](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- 🌎 [SPIP](www.spip.net/fr) - Publication system for the Internet aimed at collaborative work, multilingual environments, and simplicity of use for web authors.  🌎 [Source Code](git.spip.net/)) `GPL-3.0` `PHP`
- 🌎 [Squidex](squidex.io) - Headless CMS, based on MongoDB, CQRS and Event Sourcing.  🌎 [Demo](cloud.squidex.io), <b><code>&nbsp;&nbsp;2470⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;511🍴</code></b> [Source Code](https://github.com/Squidex/squidex))) `MIT` `.NET`
- 🌎 [Strapi](strapi.io/) - The most advanced open-source Content Management Framework (headless-CMS) to build powerful API with no effort. (<b><code>&nbsp;70798⭐</code></b> <b><code>&nbsp;&nbsp;9333🍴</code></b> [Source Code](https://github.com/strapi/strapi))) `MIT` `Nodejs`
- 🌎 [Superdesk](superdesk.org/) `⚠` - End-to-end news creation, production, curation, distribution, and publishing platform. (<b><code>&nbsp;&nbsp;&nbsp;720⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;231🍴</code></b> [Source Code](https://github.com/superdesk/superdesk))) `AGPL-3.0` `Docker/Python/PHP`
- 🌎 [Textpattern](textpattern.com/) - Flexible, elegant and easy-to-use CMS.  🌎 [Demo](textpattern.co/demo), <b><code>&nbsp;&nbsp;&nbsp;850⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [Source Code](https://github.com/textpattern/textpattern))) `GPL-2.0` `PHP`
- 🌎 [Typemill](typemill.net/) - Author-friendly flat-file-cms with a visual markdown editor based on vue.js. (<b><code>&nbsp;&nbsp;&nbsp;564⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [Source Code](https://github.com/typemill/typemill))) `MIT` `PHP`
- 🌎 [TYPO3](typo3.org/) - Powerful and advanced CMS with a large community. (<b><code>&nbsp;&nbsp;1154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;697🍴</code></b> [Source Code](https://github.com/TYPO3/typo3))) `GPL-2.0` `PHP`
- 🌎 [Umbraco](umbraco.com/) - The friendly CMS. Free and open source with an amazing community. (<b><code>&nbsp;&nbsp;5066⭐</code></b> <b><code>&nbsp;&nbsp;2836🍴</code></b> [Source Code](https://github.com/umbraco/Umbraco-CMS))) `MIT` `.NET`
- 🌎 [Vvveb CMS](www.vvveb.com) - Powerful and easy to use CMS to build websites, blogs or e-commerce stores.  🌎 [Demo](demo.vvveb.com), <b><code>&nbsp;&nbsp;&nbsp;936⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [Source Code](https://github.com/givanz/Vvveb))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Wagtail](wagtail.io/) - Django content management system focused on flexibility and user experience. (<b><code>&nbsp;19958⭐</code></b> <b><code>&nbsp;&nbsp;4326🍴</code></b> [Source Code](https://github.com/wagtail/wagtail))) `BSD-3-Clause` `Python`
- 🌎 [WinterCMS](wintercms.com/) - Speedy and secure content management system built on the Laravel PHP framework. (<b><code>&nbsp;&nbsp;1475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;226🍴</code></b> [Source Code](https://github.com/wintercms/winter))) `MIT` `PHP`
- 🌎 [WonderCMS](www.wondercms.com) - WonderCMS is the smallest flat file CMS since 2008.  🌎 [Demo](www.wondercms.com/demo), <b><code>&nbsp;&nbsp;&nbsp;711⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;165🍴</code></b> [Source Code](https://github.com/WonderCMS/wondercms))) `MIT` `PHP`
- 🌎 [WordPress](wordpress.org/) - World's most-used blogging and CMS engine. (<b><code>&nbsp;20746⭐</code></b> <b><code>&nbsp;12922🍴</code></b> [Source Code](https://github.com/WordPress/WordPress))) `GPL-2.0` `PHP`


### Customer Relationship Management (CRM)

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Customer relationship management (CRM)](en.wikipedia.org/wiki/Customer_relationship_management) is a strategic process that organizations use to manage, analyze, and improve their interactions with customers.

_Related: [Communication - Email - Mailing Lists and Newsletters](#communication---email---mailing-lists-and-newsletters), [Analytics](#analytics), [Calendar & Contacts](#calendar--contacts)_

- 🌎 [Corteza](docs.cortezaproject.org) - CRM including a unified workspace, enterprise messaging and a low code environment for rapidly and securely delivering records-based management solutions.  🌎 [Demo](latest.cortezaproject.org), <b><code>&nbsp;&nbsp;1980⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;477🍴</code></b> [Source Code](https://github.com/cortezaproject/corteza))) `Apache-2.0` `Go`
- 🌎 [Django-CRM](DjangoCRM.github.io/info/) - Analytical CRM with tasks management, email marketing and many more. Django CRM is built for individual use, businesses of any size or freelancers and is designed to provide easy customization and quick development. (<b><code>&nbsp;&nbsp;&nbsp;465⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;315🍴</code></b> [Source Code](https://github.com/DjangoCRM/django-crm))) `AGPL-3.0` `Python`
- 🌎 [EspoCRM](www.espocrm.com/) - CRM with a frontend designed as a single page application, and a REST API.  🌎 [Demo](demo.espocrm.com/), <b><code>&nbsp;&nbsp;2701⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;781🍴</code></b> [Source Code](https://github.com/espocrm/espocrm))) `AGPL-3.0` `PHP`
- 🌎 [Krayin](krayincrm.com/) - CRM solution for SMEs and Enterprises for complete customer lifecycle management.  🌎 [Demo](demo.krayincrm.com/), <b><code>&nbsp;20590⭐</code></b> <b><code>&nbsp;&nbsp;1326🍴</code></b> [Source Code](https://github.com/krayin/laravel-crm))) `MIT` `PHP`
- 🌎 [Monica](monicahq.com/) - Personal relationship manager, and a new kind of CRM to organize interactions with your friends and family. (<b><code>&nbsp;23852⭐</code></b> <b><code>&nbsp;&nbsp;2400🍴</code></b> [Source Code](https://github.com/monicahq/monica))) `AGPL-3.0` `PHP/Docker`
- 🌎 [SuiteCRM](suitecrm.com) - The award-winning, enterprise-class open source CRM. (<b><code>&nbsp;&nbsp;5202⭐</code></b> <b><code>&nbsp;&nbsp;2288🍴</code></b> [Source Code](https://github.com/SuiteCRM/SuiteCRM))) `AGPL-3.0` `PHP`
- 🌎 [Twenty](twenty.com) - A modern CRM offering the flexibility of open source, advanced features, and a sleek design. (<b><code>&nbsp;37671⭐</code></b> <b><code>&nbsp;&nbsp;4794🍴</code></b> [Source Code](https://github.com/twentyhq/twenty))) `AGPL-3.0` `Docker`


### Database Management

**[`^        back to top        ^`](#awesome-selfhosted)**

Web interfaces for 🌎 [database](en.wikipedia.org/wiki/Database) management. Includes tools for database analytics and visualization.

_Related: [Analytics](#analytics), [Automation](#automation)_

_See also: 🌎 [dbdb.io - Database of Databases](dbdb.io/)_

- 🌎 [Adminer](www.adminer.org/) - Database management in a single PHP file. Available for MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch, MongoDB and others. (<b><code>&nbsp;&nbsp;7199⭐</code></b> <b><code>&nbsp;&nbsp;1156🍴</code></b> [Source Code](https://github.com/vrana/adminer))) `Apache-2.0/GPL-2.0` `PHP`
- 🌎 [Azimutt](azimutt.app) - Visual database exploration made for real world databases (big and messy). Explore your database schema as well as data, document them, extend them and even get analysis and guidelines.  🌎 [Demo](azimutt.app/gallery/gospeak), <b><code>&nbsp;&nbsp;2032⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [Source Code](https://github.com/azimuttapp/azimutt))) `MIT` `Elixir/Nodejs/Docker`
- 🌎 [Baserow](baserow.io/) - Create your own database without technical experience (alternative to Airtable).  🌎 [Source Code](gitlab.com/baserow/baserow)) `MIT` `Docker`
- 🌎 [Bytebase](www.bytebase.com/) - Safe database schema change and version control for DevOps teams, supports MySQL, PostgreSQL, TiDB, ClickHouse, and Snowflake.  🌎 [Demo](demo.bytebase.com), <b><code>&nbsp;13481⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;882🍴</code></b> [Source Code](https://github.com/bytebase/bytebase))) `MIT` `Docker/K8S/Go`
- 🌎 [Chartbrew](chartbrew.com) - Connect directly to databases and APIs and use the data to create beautiful charts.  🌎 [Demo](app.chartbrew.com/live-demo), <b><code>&nbsp;&nbsp;3536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;402🍴</code></b> [Source Code](https://github.com/chartbrew/chartbrew))) `MIT` `Nodejs/Docker`
- 🌎 [ChartDB](chartdb.io/) - Database diagrams editor that allows you to visualize and design your DB with a single query.  🌎 [Demo](app.chartdb.io), <b><code>&nbsp;20650⭐</code></b> <b><code>&nbsp;&nbsp;1207🍴</code></b> [Source Code](https://github.com/chartdb/chartdb))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [CloudBeaver](dbeaver.com/) - Manage databases, supports PostgreSQL, MySQL, SQLite and more. A web/hosted version of DBeaver. (<b><code>&nbsp;&nbsp;4510⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;500🍴</code></b> [Source Code](https://github.com/dbeaver/cloudbeaver))) `Apache-2.0` `Docker`
- 🌎 [Databunker](databunker.org/) - Network-based, self-hosted, GDPR compliant, secure database for personal data or PII. (<b><code>&nbsp;&nbsp;1372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/securitybunker/databunker))) `MIT` `Docker`
- 🌎 [Datasette](datasette.io/) - Explore and publish data with easy import and export and database management. (<b><code>&nbsp;10609⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;799🍴</code></b> [Source Code](https://github.com/simonw/datasette))) `Apache-2.0` `Python/Docker`
- 🌎 [Evidence](evidence.dev) - Code-based BI tool. Write reports using SQL and markdown and they render as a website. (<b><code>&nbsp;&nbsp;5778⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;310🍴</code></b> [Source Code](https://github.com/evidence-dev/evidence))) `MIT` `Nodejs`
- 🌎 [Kottster](kottster.app/) - Low-code admin panel that connects to your database and automatically generates pages to view and manage your data.  🌎 [Demo](demo.kottster.app/), <b><code>&nbsp;&nbsp;1076⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Source Code](https://github.com/kottster/kottster))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [Limbas](www.limbas.com/en/) - Database framework for creating database-driven business applications. As a graphical database frontend, it enables the efficient processing of data stocks and the flexible development of comfortable database applications. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;58⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/limbas/limbas))) `GPL-2.0` `PHP`
- 🌎 [Mathesar](mathesar.org/) - Intuitive UI to manage data collaboratively, for users of all technical skill levels. Built on Postgres – connect an existing DB or set up a new one. (<b><code>&nbsp;&nbsp;4710⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;463🍴</code></b> [Source Code](https://github.com/mathesar-foundation/mathesar))) `GPL-3.0` `Docker/Python`
- 🌎 [NocoDB](www.nocodb.com/) - No-code platform that turns any database into a smart spreadsheet (alternative to Airtable and Smartsheet). (<b><code>&nbsp;59247⭐</code></b> <b><code>&nbsp;&nbsp;4405🍴</code></b> [Source Code](https://github.com/nocodb/nocodb))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [WebDB](webdb.app) - Efficient database IDE.  🌎 [Demo](demo.webdb.app/), 🌎 [Source Code](gitlab.com/web-db/app)) `AGPL-3.0` `Docker`


### DNS

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [DNS](en.wikipedia.org/wiki/Domain_Name_System) servers and management tools with advertisement blocking functionality, primarily aimed at home or small networks.

_See also: <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/DNS - Servers](https://github.com/awesome-foss/awesome-sysadmin#dns---servers)), <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/DNS - Control Panels & Domain Management](https://github.com/awesome-foss/awesome-sysadmin#dns---control-panels--domain-management))_

- 🌎 [AdGuard Home](adguard.com/en/adguard-home/overview.html) - User-friendly ads & trackers blocking DNS server. (<b><code>&nbsp;31651⭐</code></b> <b><code>&nbsp;&nbsp;2200🍴</code></b> [Source Code](https://github.com/AdguardTeam/AdGuardHome))) `GPL-3.0` `Docker`
- 🌎 [blocky](0xerr0r.github.io/blocky/latest/) - Fast and lightweight DNS proxy as ad-blocker for local network with many features (alternative to Pi-hole). (<b><code>&nbsp;&nbsp;5838⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Source Code](https://github.com/0xERR0R/blocky))) `Apache-2.0` `Go/Docker`
- 🌎 [Maza ad blocking](maza-ad-blocking.andros.dev/) - Local ad blocker. Like Pi-hole but local and using your operating system. (<b><code>&nbsp;&nbsp;1858⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [Source Code](https://github.com/tanrax/maza-ad-blocking))) `Apache-2.0` `Shell`
- 🌎 [Pi-hole](pi-hole.net/) - Blackhole for Internet advertisements with a GUI for management and monitoring. (<b><code>&nbsp;54908⭐</code></b> <b><code>&nbsp;&nbsp;2945🍴</code></b> [Source Code](https://github.com/pi-hole/pi-hole))) `EUPL-1.2` `Shell/PHP/Docker`
- 🌎 [Technitium DNS Server](technitium.com/dns/) - Authoritative/recursive DNS server with ad blocking functionality. (<b><code>&nbsp;&nbsp;7140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;599🍴</code></b> [Source Code](https://github.com/TechnitiumSoftware/DnsServer))) `GPL-3.0` `Docker/C#`


### Document Management

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [document management system](en.wikipedia.org/wiki/Document_management_system) (DMS) is a system used to receive, track, manage and store documents and reduce paper.

- 🌎 [Docspell](docspell.org) - Auto-tagging document organizer and archive. (<b><code>&nbsp;&nbsp;1968⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;154🍴</code></b> [Source Code](https://github.com/eikek/docspell))) `GPL-3.0` `Scala/Java/Docker`
- 🌎 [Documenso](documenso.com) - Digital document signing platform (alternative to DocuSign). (<b><code>&nbsp;12095⭐</code></b> <b><code>&nbsp;&nbsp;2207🍴</code></b> [Source Code](https://github.com/documenso/documenso))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Docuseal](www.docuseal.co) - Create, fill, and sign digital documents (alternative to DocuSign).  🌎 [Demo](demo.docuseal.tech/), <b><code>&nbsp;11051⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;900🍴</code></b> [Source Code](https://github.com/docusealco/docuseal))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;310⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [EveryDocs](https://github.com/jonashellmann/everydocs-core)) - Simple Document Management System for private use with basic functionality to organize your documents digitally. `GPL-3.0` `Docker/Ruby`
- 🌎 [Gotenberg](gotenberg.dev) - Developer-friendly API to interact with powerful tools like Chromium and LibreOffice for converting numerous document formats (HTML, Markdown, Word, Excel, etc.) into PDF files, and more. (<b><code>&nbsp;10738⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;712🍴</code></b> [Source Code](https://github.com/gotenberg/gotenberg))) `MIT` `Docker`
- 🌎 [I, Librarian](i-librarian.net) - Organize PDF papers and office documents. It provides a lot of extra features for students and research groups both in industry and academia.  🌎 [Demo](i-librarian.net/demo/), <b><code>&nbsp;&nbsp;&nbsp;317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Source Code](https://github.com/mkucej/i-librarian-free))) `GPL-3.0` `PHP`
- 🌎 [Mayan EDMS](www.mayan-edms.com) - Electronic document management system for your documents with preview generation, OCR, and automatic categorization among other features.  🌎 [Source Code](gitlab.com/mayan-edms/mayan-edms)) `GPL-2.0` `Docker/K8S`
- 🌎 [OpenSign](www.opensignlabs.com) `⚠` - Document signing software (alternative to DocuSign). (<b><code>&nbsp;&nbsp;5544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;578🍴</code></b> [Source Code](https://github.com/opensignlabs/opensign))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Paperless-ngx](docs.paperless-ngx.com/) - Scan, index, and archive all of your paper documents with an improved interface (fork of Paperless).  🌎 [Demo](demo.paperless-ngx.com/), <b><code>&nbsp;35137⭐</code></b> <b><code>&nbsp;&nbsp;2219🍴</code></b> [Source Code](https://github.com/paperless-ngx/paperless-ngx))) `GPL-3.0` `Python/Docker`
- 🌎 [Papermerge](papermerge.com) - Document management system focused on scanned documents (electronic archives). Features file browsing in similar way to dropbox/google drive. OCR, full text search, text overlay/selection. (<b><code>&nbsp;&nbsp;&nbsp;405⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Source Code](https://github.com/papermerge/papermerge-core))) `Apache-2.0` `Docker/K8S`
- 🌎 [Papra](papra.app) - Minimalist document storage, management and archiving platform designed to be simple to use and accessible to everyone.  🌎 [Demo](demo.papra.app/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/papra-hq/papra/))) `AGPL-3.0` `Docker`
- 🌎 [PdfDing](www.pdfding.com) - PDF manager, viewer and editor offering a seamless user experience on multiple devices. It's designed to be minimal, fast, and easy to set up using Docker.  🌎 [Demo](demo.pdfding.com), <b><code>&nbsp;&nbsp;1495⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [Source Code](https://github.com/mrmn2/PdfDing))) `AGPL-3.0` `Docker/K8S`
- 🌎 [SeedDMS](www.seeddms.org) - Document Management System with workflows, access rights, fulltext search, and more.  🌎 [Demo](www.seeddms.org/about/), 🌎 [Source Code](sourceforge.net/p/seeddms/code/ci/master/tree/)) `GPL-2.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;713⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [Signature PDF](https://github.com/24eme/signaturepdf)) - Sign and manipulate PDFs with collaboration, organization, compression and metadata editing.  🌎 [Demo](pdf.24eme.fr/)) `AGPL-3.0` `PHP/deb/Docker`
- <b><code>&nbsp;71608⭐</code></b> <b><code>&nbsp;&nbsp;6086🍴</code></b> [Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)) - Local hosted web application that allows you to perform various operations on PDF files, such as merging, splitting, file conversions and OCR. `Apache-2.0` `Docker/Java`


### Document Management - E-books

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Ebook](en.wikipedia.org/wiki/Ebook) library management software.

- 🌎 [Atsumeru](atsumeru.xyz) - Manga/comic/light novel media server with clients for Windows, Linux, macOS and Android. (<b><code>&nbsp;&nbsp;&nbsp;156⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Source Code](https://github.com/Atsumeru-xyz/Atsumeru)), 🌎 [Clients](atsumeru.xyz/guides/#how-does-it-work)) `MIT` `Java/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;443⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [BookLogr](https://github.com/Mozzo1000/booklogr)) - Manage your personal book library with ease.  🌎 [Demo](demo.booklogr.app/)) `Apache-2.0` `Docker`
- <b><code>&nbsp;&nbsp;7374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;380🍴</code></b> [BookLore](https://github.com/booklore-app/booklore)) - Host and manage books, with support for PDFs, eBooks, reading progress, metadata, and stats. `GPL-3.0` `Docker`
- <b><code>&nbsp;16171⭐</code></b> <b><code>&nbsp;&nbsp;1693🍴</code></b> [Calibre Web](https://github.com/janeczku/calibre-web)) - Browse, read and download eBooks using an existing Calibre database. `GPL-3.0` `Python`
- 🌎 [Calibre](calibre-ebook.com/) - E-book library manager that can view, convert, and catalog e-books in most of the major e-book formats and provides a built-in Web server for remote clients.  🌎 [Demo](calibre-ebook.com/demo), <b><code>&nbsp;23180⭐</code></b> <b><code>&nbsp;&nbsp;2510🍴</code></b> [Source Code](https://github.com/kovidgoyal/calibre))) `GPL-3.0` `Python/deb`
- 🌎 [Kapowarr](casvt.github.io/Kapowarr/) - Build and manage a comic book library. Download, rename, move and convert issues of the volume to your liking. (<b><code>&nbsp;&nbsp;&nbsp;795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Source Code](https://github.com/Casvt/Kapowarr))) `GPL-3.0` `Docker/Python`
- 🌎 [Kavita](www.kavitareader.com/) - Cross-platform e-book/manga/comic/pdf server and web reader with user management, ratings and reviews, and metadata support.  🌎 [Demo](www.kavitareader.com/#demo), <b><code>&nbsp;&nbsp;9466⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;527🍴</code></b> [Source Code](https://github.com/Kareadita/Kavita))) `GPL-3.0` `.NET/Docker`
- 🌎 [kiwix-serve](www.kiwix.org/en/downloads/kiwix-serve/) - HTTP daemon for serving wikis from ZIM files. (<b><code>&nbsp;&nbsp;&nbsp;748⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [Source Code](https://github.com/kiwix/kiwix-tools))) `GPL-3.0` `C++`
- 🌎 [Komga](komga.org) - Media server for comics/mangas/BDs with API and OPDS support, a modern web interface for exploring your libraries, as well as a web reader. (<b><code>&nbsp;&nbsp;5701⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;338🍴</code></b> [Source Code](https://github.com/gotson/komga))) `MIT` `Java/Docker`
- 🌎 [Stump](www.stumpapp.dev) - A fast, free and open source comics, manga and digital book server with OPDS support. (<b><code>&nbsp;&nbsp;1866⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/stumpapp/stump))) `MIT` `Rust`


### Document Management - Institutional Repository and Digital Library Software

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Institutional repository](en.wikipedia.org/wiki/Institutional_repository) and 🌎 [digital library](en.wikipedia.org/wiki/Digital_library) management software.

- [DSpace](http://www.dspace.org/) - Turnkey repository application providing durable access to digital resources. (<b><code>&nbsp;&nbsp;1032⭐</code></b> <b><code>&nbsp;&nbsp;1400🍴</code></b> [Source Code](https://github.com/DSpace/DSpace))) `BSD-3-Clause` `Java`
- 🌎 [EPrints](www.eprints.org/) - Digital document management system with a flexible metadata and workflow model primarily aimed at academic institutions. ([Demo](http://tryme.demo.eprints-hosting.org/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Source Code](https://github.com/eprints/eprints3.4))) `GPL-3.0` `Perl`
- 🌎 [Fedora Commons Repository](wiki.lyrasis.org/display/FF/Fedora+Repository+Home) - Robust and modular repository system for the management and dissemination of digital content especially suited for digital libraries and archives, both for access and preservation. (<b><code>&nbsp;&nbsp;&nbsp;240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [Source Code](https://github.com/fcrepo/fcrepo))) `Apache-2.0` `Java`
- 🌎 [InvenioRDM](inveniordm.docs.cern.ch/) - Highly scalable turn-key research data management platform with a beautiful user experience.  🌎 [Demo](inveniordm.web.cern.ch/), <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [Source Code](https://github.com/inveniosoftware/invenio-app-rdm)), 🌎 [Clients](inveniosoftware.org/products/rdm/)) `MIT` `Python`
- 🌎 [Islandora](www.islandora.ca/) - Drupal module for browsing and managing Fedora-based digital repositories.  🌎 [Demo](sandbox.islandora.ca/), <b><code>&nbsp;&nbsp;&nbsp;156⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [Source Code](https://github.com/Islandora/islandora))) `GPL-3.0` `PHP`
- 🌎 [Samvera Hyrax](samvera.org/) - Front-end for the Samvera framework, which itself is a Ruby on Rails application for browsing and managing Fedora-based digital repositories. (<b><code>&nbsp;&nbsp;&nbsp;193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;131🍴</code></b> [Source Code](https://github.com/samvera/hyrax))) `Apache-2.0` `Ruby`


### Document Management - Integrated Library Systems (ILS)

**[`^        back to top        ^`](#awesome-selfhosted)**

An 🌎 [integrated library system](en.wikipedia.org/wiki/Integrated_library_system) is an enterprise resource planning system for a library, used to track items owned, orders made, bills paid, and patrons who have borrowed.

_Related: [Content Management Systems (CMS)](#content-management-systems-cms), [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)_

- 🌎 [Evergreen](evergreen-ils.org) - Highly-scalable software for libraries that helps library patrons find library materials, and helps libraries manage, catalog, and circulate those materials. (<b><code>&nbsp;&nbsp;&nbsp;146⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [Source Code](https://github.com/evergreen-library-system/Evergreen))) `GPL-2.0` `PLpgSQL`
- 🌎 [Koha](koha-community.org/) - Enterprise-class ILS with modules for acquisitions, circulation, cataloging, label printing, offline circulation for when Internet access is not available, and much more.  🌎 [Demo](koha-community.org/demo/), <b><code>&nbsp;&nbsp;&nbsp;544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [Source Code](https://github.com/Koha-Community/Koha))) `GPL-3.0` `Perl`
- 🌎 [RERO ILS](rero21.ch/) - Large-scale ILS that can be run as a service with consortial features, intended primarily for library networks. Includes most standard modules (circulation, acquisitions, cataloging,...) and a web-based public and professional interface.  🌎 [Demo](ils.test.rero.ch/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Source Code](https://github.com/rero/rero-ils))) `AGPL-3.0` `Python/Docker`


### E-commerce

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [E-commerce](en.wikipedia.org/wiki/E-commerce) software.

_Related: [Community-Supported Agriculture (CSA)](#community-supported-agriculture-csa)_

- 🌎 [Aimeos](aimeos.org/) - E-commerce framework for building custom online shops, market places and complex B2B applications scaling to billions of items with Laravel.  🌎 [Demo](demo.aimeos.org/), <b><code>&nbsp;&nbsp;5200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;308🍴</code></b> [Source Code](https://github.com/aimeos/aimeos))) `LGPL-3.0/MIT` `PHP`
- 🌎 [Bagisto](bagisto.com/en/) - Leading Laravel open source e-commerce framework with multi-inventory sources, taxation, localization, dropshipping and more exciting features.  🌎 [Demo](demo.bagisto.com/), <b><code>&nbsp;24772⭐</code></b> <b><code>&nbsp;&nbsp;2885🍴</code></b> [Source Code](https://github.com/bagisto/bagisto))) `MIT` `PHP`
- 🌎 [CoreShop](www.coreshop.org) - E-commerce plugin for Pimcore. (<b><code>&nbsp;&nbsp;&nbsp;288⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [Source Code](https://github.com/coreshop/CoreShop))) `GPL-3.0` `PHP`
- 🌎 [Drupal Commerce](drupalcommerce.org) - Popular e-commerce module for Drupal CMS, with support for dozens of payment, shipping, and shopping related modules.  🌎 [Source Code](git.drupalcode.org/project/commerce)) `GPL-2.0` `PHP`
- 🌎 [EverShop](evershop.io/) `⚠` - E-commerce platform with essential commerce features. Modular architecture and fully customizable.  🌎 [Demo](demo.evershop.io/), <b><code>&nbsp;&nbsp;8904⭐</code></b> <b><code>&nbsp;&nbsp;2050🍴</code></b> [Source Code](https://github.com/evershopcommerce/evershop))) `GPL-3.0` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Litecart](https://github.com/shurco/litecart)) `⚠` - Shopping cart in 1 file (with support for payment by card or cryptocurrency). `MIT` `Go/Docker`
- 🌎 [Magento Open Source](business.adobe.com/products/magento/magento-commerce.html) - Leading provider of open omnichannel innovation. (<b><code>&nbsp;12013⭐</code></b> <b><code>&nbsp;&nbsp;9409🍴</code></b> [Source Code](https://github.com/magento/magento2))) `OSL-3.0` `PHP`
- 🌎 [MedusaJs](medusajs.com/) - Headless commerce engine that enables developers to create amazing digital commerce experiences.  🌎 [Demo](next.medusajs.com/), <b><code>&nbsp;31504⭐</code></b> <b><code>&nbsp;&nbsp;3913🍴</code></b> [Source Code](https://github.com/medusajs/medusa))) `MIT` `Nodejs`
- 🌎 [Microweber](microweber.com/) - Drag and Drop CMS and online shop. (<b><code>&nbsp;&nbsp;3368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;927🍴</code></b> [Source Code](https://github.com/microweber/microweber))) `MIT` `PHP`
- <b><code>&nbsp;&nbsp;3982⭐</code></b> <b><code>&nbsp;&nbsp;2429🍴</code></b> [Open Source POS](https://github.com/opensourcepos/opensourcepos)) - Open Source Point of Sale is a web based point of sale system. `MIT` `PHP`
- 🌎 [OpenCart](www.opencart.com) - Shopping cart solution. (<b><code>&nbsp;&nbsp;7991⭐</code></b> <b><code>&nbsp;&nbsp;5022🍴</code></b> [Source Code](https://github.com/opencart/opencart))) `GPL-3.0` `PHP`
- 🌎 [PrestaShop](www.prestashop.com/) - Fully scalable e-commerce solution.  🌎 [Demo](demo.prestashop.com/), <b><code>&nbsp;&nbsp;8909⭐</code></b> <b><code>&nbsp;&nbsp;5011🍴</code></b> [Source Code](https://github.com/PrestaShop/PrestaShop))) `OSL-3.0` `PHP`
- 🌎 [Pretix](pretix.eu/) - Ticket sales platform for events. (<b><code>&nbsp;&nbsp;2286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;583🍴</code></b> [Source Code](https://github.com/pretix/pretix))) `AGPL-3.0` `Python/Docker`
- 🌎 [s-cart](s-cart.org/) - E-commerce website for individuals and businesses, built on top of Laravel Framework.  🌎 [Demo](demo.s-cart.org/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Source Code](https://github.com/gp247net/s-cart))) `MIT` `PHP`
- 🌎 [Saleor](saleor.io) - Django based open-sourced e-commerce storefront.  🌎 [Demo](demo.saleor.io/), <b><code>&nbsp;22423⭐</code></b> <b><code>&nbsp;&nbsp;5879🍴</code></b> [Source Code](https://github.com/saleor/saleor))) `BSD-3-Clause` `Docker/Python`
- 🌎 [Shopware Community Edition](www.shopware.com/en/community/community-edition/) - PHP based open source e-commerce software made in Germany.  🌎 [Demo](www.shopware.com/en/test-demo/), <b><code>&nbsp;&nbsp;3251⭐</code></b> <b><code>&nbsp;&nbsp;1148🍴</code></b> [Source Code](https://github.com/shopware/shopware))) `MIT` `PHP`
- 🌎 [Solidus](solidus.io/) - A free, open-source ecommerce platform that gives you complete control over your store. (<b><code>&nbsp;&nbsp;5243⭐</code></b> <b><code>&nbsp;&nbsp;1360🍴</code></b> [Source Code](https://github.com/solidusio/solidus))) `BSD-3-Clause` `Ruby/Docker`
- 🌎 [Spree Commerce](spreecommerce.org) - Spree is a complete, modular & API-driven open source e-commerce solution for Ruby on Rails.  🌎 [Demo](demo.spreecommerce.org/), <b><code>&nbsp;15110⭐</code></b> <b><code>&nbsp;&nbsp;5208🍴</code></b> [Source Code](https://github.com/spree/spree))) `BSD-3-Clause` `Ruby`
- 🌎 [Sylius](sylius.com) - Symfony2 powered open source full-stack platform for eCommerce.  🌎 [Demo](sylius.com/try/), <b><code>&nbsp;&nbsp;8380⭐</code></b> <b><code>&nbsp;&nbsp;2154🍴</code></b> [Source Code](https://github.com/Sylius/Sylius))) `MIT` `PHP`
- 🌎 [Thelia](thelia.net/) - Thelia is an open source and flexible e-commerce solution.  🌎 [Demo](demo.thelia.net/), <b><code>&nbsp;&nbsp;&nbsp;871⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;313🍴</code></b> [Source Code](https://github.com/thelia/thelia))) `LGPL-3.0` `PHP`
- 🌎 [Vendure](www.vendure.io) - A headless commerce framework.  🌎 [Demo](demo.vendure.io), <b><code>&nbsp;&nbsp;7636⭐</code></b> <b><code>&nbsp;&nbsp;1294🍴</code></b> [Source Code](https://github.com/vendure-ecommerce/vendure))) `MIT` `Nodejs`
- 🌎 [WooCommerce](woocommerce.com/) - WordPress based e-commerce solution. (<b><code>&nbsp;10104⭐</code></b> <b><code>&nbsp;10733🍴</code></b> [Source Code](https://github.com/woocommerce/woocommerce))) `GPL-3.0` `PHP`


### Federated Identity & Authentication

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Federated identity](en.wikipedia.org/wiki/Federated_identity) and 🌎 [authentication](en.wikipedia.org/wiki/Electronic_authentication) software.

**Please visit <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/Identity Management](https://github.com/awesome-foss/awesome-sysadmin#identity-management))**



### Feed Readers

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [news aggregator](en.wikipedia.org/wiki/News_aggregator), also termed a feed aggregator, feed reader, news reader, 🌎 [RSS](en.wikipedia.org/wiki/RSS) reader, is an application that aggregates web content such as newspapers/blogs/vlogs/podcasts in one location for easy viewing.

- <b><code>&nbsp;&nbsp;&nbsp;224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Bubo Reader](https://github.com/georgemandis/bubo-rss)) - Irrationally minimal RSS feed reader.  🌎 [Demo](bubo-rss-demo.netlify.app/)) `MIT` `Nodejs`
- 🌎 [CommaFeed](www.commafeed.com/) - Google Reader inspired self-hosted RSS reader.  🌎 [Demo](www.commafeed.com/#/app/category/all), <b><code>&nbsp;&nbsp;3327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;397🍴</code></b> [Source Code](https://github.com/Athou/commafeed))) `Apache-2.0` `Java/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;283⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [FeedCord](https://github.com/Qolors/FeedCord)) `⚠` - Simple, lightweight & customizable RSS News Feed for your Discord Server. `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;384⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Feedpushr](https://github.com/ncarlier/feedpushr)) - Powerful RSS aggregator, able to transform and send articles to many outputs. Single binary, extensible with plugins. `GPL-3.0` `Go/Docker`
- 🌎 [Feeds Fun](feeds.fun/) - News reader with tags, scoring, and AI. (<b><code>&nbsp;&nbsp;&nbsp;317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Source Code](https://github.com/Tiendil/feeds.fun))) `BSD-3-Clause` `Python`
- 🌎 [FreshRSS](freshrss.org/) - Self-hostable RSS feed aggregator.  🌎 [Demo](demo.freshrss.org/i/), <b><code>&nbsp;13436⭐</code></b> <b><code>&nbsp;&nbsp;1074🍴</code></b> [Source Code](https://github.com/FreshRSS/FreshRSS))) `AGPL-3.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;1910⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [Fusion](https://github.com/0x2E/fusion)) - Lightweight RSS aggregator and reader. `MIT` `Go/Docker`
- 🌎 [JARR](1pxsolidblack.pl/jarr-en.html) - JARR (Just Another RSS Reader) is a web-based news aggregator and reader (fork of Newspipe).  🌎 [Demo](www.jarr.info/), <b><code>&nbsp;&nbsp;&nbsp;128⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Source Code](https://github.com/jaesivsm/JARR))) `AGPL-3.0` `Docker/Python`
- <b><code>&nbsp;&nbsp;&nbsp;285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Kriss Feed](https://github.com/tontof/kriss_feed)) - Simple and smart (or stupid) feed reader. `CC0-1.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;228⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Leed](https://github.com/LeedRSS/Leed)) - Leed (for Light Feed) is a Free and minimalist RSS aggregator. `AGPL-3.0` `PHP`
- 🌎 [Miniflux](miniflux.app/) - Minimalist news reader. (<b><code>&nbsp;&nbsp;8537⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;827🍴</code></b> [Source Code](https://github.com/miniflux/v2))) `Apache-2.0` `Go/deb/Docker`
- 🌎 [NewsBlur](www.newsblur.com/) - Personal news reader that brings people together to talk about the world. A new sound of an old instrument. (<b><code>&nbsp;&nbsp;7234⭐</code></b> <b><code>&nbsp;&nbsp;1022🍴</code></b> [Source Code](https://github.com/samuelclay/NewsBlur))) `MIT` `Python`
- 🌎 [Newspipe](git.sr.ht/~cedric/newspipe) - Web news reader.  🌎 [Demo](www.newspipe.org/signup)) `AGPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Precis](https://github.com/leozqin/precis)) - Extensibility-oriented RSS reader that can use LLMs (including local LLMs) to summarize RSS entries with built-in notification support. `MIT` `Python/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;518⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [reader](https://github.com/lemon24/reader)) - Feed reader web app and library (so you can use it to build your own), with only standard library and pure-Python dependencies. `BSD-3-Clause` `Python`
- 🌎 [Readflow](readflow.app) - Lightweight news reader with modern interface and features: full-text search, automatic categorization, archiving, offline support, notifications. (<b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Source Code](https://github.com/ncarlier/readflow))) `AGPL-3.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;8555⭐</code></b> <b><code>&nbsp;&nbsp;1175🍴</code></b> [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge)) - Generate RSS/ATOM feeds for websites which don't have one. `Unlicense` `PHP/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;460⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [RSS Monster](https://github.com/pietheinstrengholt/rssmonster)) - Easy to use web-based RSS aggregator and reader compatible with the Fever API (alternative to Google Reader). `MIT` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [RSS2EMail](https://github.com/rss2email/rss2email)) - Fetches RSS/Atom-feeds and pushes new content to any email-receiver, supports OPML. `GPL-2.0` `Python/deb`
- 🌎 [RSSHub](docs.rsshub.app) - Easy to use, and extensible RSS feed aggregator capable of generating RSS feeds from pretty much everything ranging from social media to university departments.  🌎 [Demo](rsshub.app), <b><code>&nbsp;40700⭐</code></b> <b><code>&nbsp;&nbsp;8910🍴</code></b> [Source Code](https://github.com/DIYgod/RSSHub))) `MIT` `Nodejs/Docker`
- 🌎 [Selfoss](selfoss.aditu.de/) - New multipurpose rss reader, live stream, mashup, aggregation web application. (<b><code>&nbsp;&nbsp;2445⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;345🍴</code></b> [Source Code](https://github.com/fossar/selfoss))) `GPL-3.0` `PHP`
- <b><code>&nbsp;&nbsp;4076⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;398🍴</code></b> [Stringer](https://github.com/stringer-rss/stringer)) - Work-in-progress self-hosted, anti-social RSS reader. `MIT` `Ruby`
- 🌎 [Tiny Tiny RSS](tt-rss.org) - Web-based news feed (RSS/Atom) reader and aggregator. (<b><code>&nbsp;&nbsp;&nbsp;513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Source Code](https://github.com/tt-rss/tt-rss))) `GPL-3.0` `Docker/PHP`
- 🌎 [TinyFeed](feed.lovergne.dev/) - Generate a static HTML page from a collection of feeds wtih a simple CLI.  🌎 [Demo](feed.lovergne.dev/demo), <b><code>&nbsp;&nbsp;&nbsp;298⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Source Code](https://github.com/TheBigRoomXXL/tinyfeed))) `MIT` `Go/Docker`
- 🌎 [Upvote RSS](www.upvote-rss.com/) `⚠` - Generate rich RSS feeds from Reddit, Hacker News, Lemmy, Mbin, and more.  🌎 [Demo](www.upvote-rss.com/), <b><code>&nbsp;&nbsp;&nbsp;417⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/johnwarne/upvote-rss))) `MIT` `Docker/PHP`
- <b><code>&nbsp;&nbsp;3655⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;271🍴</code></b> [Yarr](https://github.com/nkanaev/yarr)) - Yarr (yet another rss reader) is a web-based feed aggregator which can be used both as a desktop application and a personal self-hosted server. `MIT` `Go`


### File Transfer & Synchronization

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [File transfer](en.wikipedia.org/wiki/File_transfer), 🌎 [sharing](en.wikipedia.org/wiki/File_sharing) and 🌎 [synchronization software](en.wikipedia.org/wiki/File_synchronization) software.

_Related: [Groupware](#groupware)_

- 🌎 [bewCloud](bewcloud.com) - File sharing + sync, notes, and photos (alternative to Nextcloud and ownCloud's RSS reader). (<b><code>&nbsp;&nbsp;1056⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [Source Code](https://github.com/bewcloud/bewcloud)), [Clients](https://github.com/bewcloud)) `AGPL-3.0` `Docker`
- 🌎 [Cloudreve](cloudreve.org/) - File management and sharing system, supports multiple storage providers.  🌎 [Demo](demo.cloudreve.org), <b><code>&nbsp;26298⭐</code></b> <b><code>&nbsp;&nbsp;3751🍴</code></b> [Source Code](https://github.com/cloudreve/cloudreve))) `GPL-3.0` `Docker/Go`
- 🌎 [Git Annex](git-annex.branchable.com/) - File synchronization between computers, servers, external drives.  🌎 [Source Code](git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- 🌎 [Kinto](kinto.readthedocs.org) - Minimalist JSON storage service with synchronisation and sharing abilities. (<b><code>&nbsp;&nbsp;4398⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;421🍴</code></b> [Source Code](https://github.com/Kinto/kinto))) `Apache-2.0` `Python`
- 🌎 [Nextcloud](nextcloud.com/) - Access and share your files, calendars, contacts, mail and 🌎 [more](apps.nextcloud.com/) from any device, on your terms.  🌎 [Demo](try.nextcloud.com/), <b><code>&nbsp;33669⭐</code></b> <b><code>&nbsp;&nbsp;4673🍴</code></b> [Source Code](https://github.com/nextcloud/server))) `AGPL-3.0` `PHP/deb`
- 🌎 [OpenCloud](docs.opencloud.eu/) - File Sharing and Collaboration Platform. (<b><code>&nbsp;&nbsp;4463⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [Source Code](https://github.com/opencloud-eu/opencloud))) `Apache-2.0` `Docker/Go/Nodejs`
- 🌎 [OpenSSH SFTP server](www.openssh.com/) - Secure File Transfer Program.  🌎 [Source Code](cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh/)) `BSD-2-Clause` `C/deb`
- 🌎 [ownCloud](owncloud.org/) - All-in-one solution for saving, synchronizing, viewing, editing and sharing files, calendars, address books and more. (<b><code>&nbsp;&nbsp;8702⭐</code></b> <b><code>&nbsp;&nbsp;2060🍴</code></b> [Source Code](https://github.com/owncloud/core)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Clients](https://github.com/owncloud/core/wiki/Apps))) `AGPL-3.0` `PHP/Docker/deb`
- 🌎 [Peergos](peergos.org) - Secure and private space online where you can store, share and view your photos, videos, music and documents. Also includes a calendar, news feed, task lists, chat and email client. (<b><code>&nbsp;&nbsp;2332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;183🍴</code></b> [Source Code](https://github.com/Peergos/Peergos))) `AGPL-3.0` `Java`
- 🌎 [Puter](puter.com/) - Web-based operating system designed to be feature-rich, exceptionally fast, and highly extensible.  🌎 [Demo](puter.com/), <b><code>&nbsp;38169⭐</code></b> <b><code>&nbsp;&nbsp;3324🍴</code></b> [Source Code](https://github.com/heyputer/puter))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Pydio](pydio.com/) - Turn any web server into a powerful file management system and an alternative to mainstream cloud storage providers.  🌎 [Demo](pydio.com/en/demo), <b><code>&nbsp;&nbsp;2103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;210🍴</code></b> [Source Code](https://github.com/pydio/cells))) `AGPL-3.0` `Go`
- 🌎 [Samba](www.samba.org/) - Samba is the standard Windows interoperability suite of programs for Linux and Unix. It provides secure, stable and fast file and print services for all clients using the SMB/CIFS protocol.  🌎 [Source Code](git.samba.org/samba.git/)) `GPL-3.0` `C`
- 🌎 [Seafile](www.seafile.com/en/home/) - File hosting and sharing solution primary for teams and organizations. (<b><code>&nbsp;14114⭐</code></b> <b><code>&nbsp;&nbsp;1624🍴</code></b> [Source Code](https://github.com/haiwen/seafile))) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- 🌎 [Sync-in](sync-in.com) - File storage, syncing, sharing, and collaboration with real-time editing, permission management, and desktop/CLI clients.  🌎 [Demo](sync-in.com/docs/demo), <b><code>&nbsp;&nbsp;&nbsp;485⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Source Code](https://github.com/Sync-in/server)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Clients](https://github.com/Sync-in/desktop))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Syncthing](syncthing.net/) - Syncthing is an open source peer-to-peer file synchronisation tool. (<b><code>&nbsp;78502⭐</code></b> <b><code>&nbsp;&nbsp;4864🍴</code></b> [Source Code](https://github.com/syncthing/syncthing))) `MPL-2.0` `Go/Docker/deb`
- 🌎 [Unison](www.cis.upenn.edu/~bcpierce/unison/) - Unison is a file-synchronization tool for OSX, Unix, and Windows. (<b><code>&nbsp;&nbsp;5014⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;259🍴</code></b> [Source Code](https://github.com/bcpierce00/unison))) `GPL-3.0` `deb/OCaml`


### File Transfer - Distributed Filesystems

**[`^        back to top        ^`](#awesome-selfhosted)**

Network distributed filesystems.

**Please visit <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/Distributed Filesystems](https://github.com/awesome-foss/awesome-sysadmin#distributed-filesystems))**



### File Transfer - Object Storage & File Servers

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Object storage](en.wikipedia.org/wiki/Object_storage) is a computer data storage that manages data as objects, as opposed to other storage architectures like file systems which manages data as a file hierarchy, and block storage which manages data as blocks within sectors and tracks.

- 🌎 [GarageHQ](garagehq.deuxfleurs.fr/) - Geo-distributed, S3‑compatible storage service that can fulfill many needs.  🌎 [Source Code](git.deuxfleurs.fr/Deuxfleurs/garage)) `AGPL-3.0` `Docker/Rust`
- 🌎 [Harbor](goharbor.io/) - Cloud native image registry that stores, signs, and scans content. (<b><code>&nbsp;27205⭐</code></b> <b><code>&nbsp;&nbsp;5048🍴</code></b> [Source Code](https://github.com/goharbor/harbor))) `Apache-2.0` `Docker/K8S`
- 🌎 [Minio](min.io/) - Object storage server compatible with Amazon S3 APIs. (<b><code>&nbsp;59442⭐</code></b> <b><code>&nbsp;&nbsp;6820🍴</code></b> [Source Code](https://github.com/minio/minio))) `AGPL-3.0` `Go/Docker/K8S`
- <b><code>&nbsp;29116⭐</code></b> <b><code>&nbsp;&nbsp;2637🍴</code></b> [SeaweedFS](https://github.com/seaweedfs/seaweedfs)) - SeaweedFS is an open source distributed file system supporting WebDAV, S3 API, FUSE mount, HDFS, etc, optimized for lots of small files, and easy to add capacity. `Apache-2.0` `Go`
- <b><code>&nbsp;11508⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;887🍴</code></b> [SFTPGo](https://github.com/drakkan/sftpgo)) - Flexible, fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. `AGPL-3.0` `Go/deb/Docker`
- 🌎 [Zenko CloudServer](www.zenko.io/cloudserver) - Zenko CloudServer, an open-source implementation of a server handling the Amazon S3 protocol. (<b><code>&nbsp;&nbsp;1865⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;252🍴</code></b> [Source Code](https://github.com/scality/cloudserver))) `Apache-2.0` `Docker/Nodejs`
- 🌎 [ZOT OCI Registry](zotregistry.dev) - A production-ready vendor-neutral OCI-native container image registry.  🌎 [Demo](zothub.io), <b><code>&nbsp;&nbsp;1632⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;165🍴</code></b> [Source Code](https://github.com/project-zot/zot))) `Apache-2.0` `Go/Docker`


### File Transfer - Peer-to-peer Filesharing

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Peer-to-peer file sharing](en.wikipedia.org/wiki/Peer-to-peer_file_sharing) is the distribution and 🌎 [sharing](en.wikipedia.org/wiki/File_sharing) of digital media using 🌎 [peer-to-peer](en.wikipedia.org/wiki/Peer-to-peer) (P2P) networking technology.

- 🌎 [bittorrent-tracker](webtorrent.io/) - Simple, robust, BitTorrent tracker (client and server) implementation. (<b><code>&nbsp;&nbsp;1903⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;333🍴</code></b> [Source Code](https://github.com/webtorrent/bittorrent-tracker))) `MIT` `Nodejs`
- 🌎 [Deluge](deluge-torrent.org/) - Lightweight, cross-platform BitTorrent client.  🌎 [Source Code](git.deluge-torrent.org/deluge/tree/?h=develop)) `GPL-3.0` `Python/deb`
- 🌎 [qBittorrent](www.qbittorrent.org/) - Free cross-platform bittorrent client with a feature rich Web UI for remote access. (<b><code>&nbsp;34639⭐</code></b> <b><code>&nbsp;&nbsp;4512🍴</code></b> [Source Code](https://github.com/qbittorrent/qBittorrent))) `GPL-2.0` `C++`
- 🌎 [Send](gitlab.com/timvisee/send) - Simple, private, end to end encrypted temporary file sharing, originally built by Mozilla.  🌎 [Demo](send.vis.ee/), 🌎 [Clients](gitlab.com/timvisee/send#clients)) `MPL-2.0` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;2444⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [slskd](https://github.com/slskd/slskd)) `⚠` - A modern client-server application for the Soulseek file sharing network. `AGPL-3.0` `Docker/C#`
- 🌎 [Transmission](transmissionbt.com/) - Fast, easy, free Bittorrent client. (<b><code>&nbsp;13838⭐</code></b> <b><code>&nbsp;&nbsp;1312🍴</code></b> [Source Code](https://github.com/transmission/transmission))) `GPL-3.0` `C++/deb`
- <b><code>&nbsp;&nbsp;&nbsp;510⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [Webtor](https://github.com/webtor-io/self-hosted)) - Web-based torrent client with instant audio/video streaming.  🌎 [Demo](webtor.io)) `MIT` `Docker`


### File Transfer - Single-click & Drag-n-drop Upload

**[`^        back to top        ^`](#awesome-selfhosted)**

Simplified file servers for sharing of one-time/short-lived/temporary files, providing single-click or 🌎 [drag-and-drop](en.wikipedia.org/wiki/Drag_and_drop) upload functionality.

- 🌎 [015](send.fudaoyuan.icu) - A temporary file sharing platform. Focused on providing one-time, temporary file and text upload, processing, and sharing services. (<b><code>&nbsp;&nbsp;&nbsp;279⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Source Code](https://github.com/keven1024/015))) `AGPL-3.0` `Docker`
- 🌎 [Chibisafe](chibisafe.app) - File uploader service that aims to to be easy to use and set up. It accepts files, photos, documents, anything you imagine and gives you back a shareable link for you to send to others. (<b><code>&nbsp;&nbsp;2525⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;298🍴</code></b> [Source Code](https://github.com/chibisafe/chibisafe))) `MIT` `Docker/Nodejs`
- 🌎 [Digirecord](ladigitale.dev/digirecord/) - Record and share audio files (documentation in French).  🌎 [Source Code](codeberg.org/ladigitale/digirecord)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [elixire](gitlab.com/elixire/elixire) - Simple yet advanced screenshot uploading and link shortening service.  🌎 [Clients](gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
- 🌎 [Enclosed](enclosed.cc/) - Minimalistic web application designed for sending private and secure notes.  🌎 [Demo](enclosed.cc/), <b><code>&nbsp;&nbsp;1848⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;154🍴</code></b> [Source Code](https://github.com/CorentinTh/enclosed))) `Apache-2.0` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;269⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Files Sharing](https://github.com/axeloz/filesharing)) - File sharing application based on unique and temporary links. `GPL-3.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Flare](https://github.com/FlintSH/Flare)) - A nonbloated, modern, and highly configurable file/screenshot vault server with support for ShareX, Flameshot, and Spectacle. Offers OCR search and more. `MIT` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;2471⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [Gokapi](https://github.com/Forceu/gokapi)) - Lightweight server to share files, which expire after a set amount of downloads or days. Similar to the discontinued Firefox Send, with the difference that only the admin is allowed to upload files. `GPL-3.0` `Go/Docker`
- 🌎 [goploader](depado.github.io/goploader/) - Easy file sharing with server-side encryption, curl/httpie/wget compliant. (<b><code>&nbsp;&nbsp;&nbsp;298⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Source Code](https://github.com/Depado/goploader))) `MIT` `Go`
- 🌎 [GoSƐ](codeberg.org/stv0g/gose) - Modern file-uploader focusing on scalability and simplicity. It only depends on a S3 storage backend and hence scales horizontally without the need for additional databases or caches. `Apache-2.0` `Go/Docker`
- 🌎 [Jirafeau](gitlab.com/jirafeau/Jirafeau) - One-click-fileshare project. Select your file, upload, and share a link. That's it. `AGPL-3.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;6789⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;688🍴</code></b> [OnionShare](https://github.com/onionshare/onionshare)) - Securely and anonymously share a file of any size. `GPL-3.0` `Python/deb`
- 🌎 [Pairdrop](pairdrop.net/) - Local file sharing in your browser, inspired by Apple's AirDrop (fork of Snapdrop). (<b><code>&nbsp;&nbsp;9479⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;564🍴</code></b> [Source Code](https://github.com/schlagmichdoch/pairdrop))) `GPL-3.0` `Docker`
- 🌎 [PicoShare](pico.rocks) - Minimalist, easy-to-host service for sharing images and other files.  🌎 [Demo](demo.pico.rocks), <b><code>&nbsp;&nbsp;2782⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [Source Code](https://github.com/mtlynch/picoshare))) `AGPL-3.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;1207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Picsur](https://github.com/CaramelFur/Picsur)) - Simple imaging hosting platform that allows you to easily host, edit, and share images.  🌎 [Demo](picsur.org/upload)) `AGPL-3.0` `Docker`
- 🌎 [PictShare](www.pictshare.net/) - Multi lingual image hosting service with a simple resizing and upload API. (<b><code>&nbsp;&nbsp;&nbsp;899⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [Source Code](https://github.com/HaschekSolutions/pictshare))) `Apache-2.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;1679⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [Plik](https://github.com/root-gg/plik)) - Scalable and friendly temporary file upload system.  🌎 [Demo](plik.root.gg/)) `MIT` `Go/Docker`
- 🌎 [ProjectSend](www.projectsend.org/) - Upload files and assign them to specific clients you create. Give access to those files to your clients. (<b><code>&nbsp;&nbsp;1776⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;338🍴</code></b> [Source Code](https://github.com/projectsend/projectsend))) `GPL-2.0` `PHP`
- <b><code>&nbsp;&nbsp;1812⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;240🍴</code></b> [PsiTransfer](https://github.com/psi-4ward/psitransfer)) - Simple file sharing solution with robust up-/download-resume and password protection. `BSD-2-Clause` `Nodejs`
- 🌎 [QuickShare](ihexxa.github.io/quickshare.site/) - Quick and simple file sharing between different devices. (<b><code>&nbsp;&nbsp;&nbsp;599⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Source Code](https://github.com/ihexxa/quickshare))) `LGPL-3.0` `Docker/Go`
- <b><code>&nbsp;&nbsp;1226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Sharry](https://github.com/eikek/sharry)) - Share files easily over the internet between authenticated and anonymous users (both ways) with resumable up- and downloads. `GPL-3.0` `Scala/Java/deb/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Shifter](https://github.com/TobySuch/Shifter)) - A simple, self-hosted file-sharing web app, powered by Django. `MIT` `Docker`
- 🌎 [Slink](docs.slinkapp.io/) - Image sharing platform designed to give users complete control over their media sharing experience. (<b><code>&nbsp;&nbsp;1262⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Source Code](https://github.com/andrii-kryvoviaz/slink))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;15756⭐</code></b> <b><code>&nbsp;&nbsp;1583🍴</code></b> [transfer.sh](https://github.com/dutchcoders/transfer.sh)) - Easy file sharing from the command line. `MIT` `Go`
- <b><code>&nbsp;&nbsp;1082⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [Uguu](https://github.com/nokonoko/uguu)) - Stores files and deletes after X amount of time. `MIT` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Uploady](https://github.com/farisc0de/Uploady)) - Uploady is a simple file uploader script with multi file upload support. `MIT` `PHP`
- 🌎 [XBackBone](xbackbone.app/) - A simple, fast and lightweight file manager with instant sharing tools integration, like ShareX (a free and open-source screenshot utility for Windows). (<b><code>&nbsp;&nbsp;1104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Source Code](https://github.com/SergiX44/XBackBone))) `AGPL-3.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;2723⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;210🍴</code></b> [Zipline](https://github.com/diced/zipline)) - A lightweight, fast and reliable file sharing server that is commonly used with ShareX, offering a react-based Web UI and fast API. `MIT` `Docker/Nodejs`


### File Transfer - Web-based File Managers

**[`^        back to top        ^`](#awesome-selfhosted)**

Web-based 🌎 [file managers](en.wikipedia.org/wiki/File_manager).

_Related: [Groupware](#groupware)_

- 🌎 [Apaxy](oupala.github.io/apaxy/) - Theme built to enhance the experience of browsing web directories, using the mod_autoindex Apache module and some CSS to override the default style of a directory listing. (<b><code>&nbsp;&nbsp;1908⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;262🍴</code></b> [Source Code](https://github.com/oupala/apaxy))) `GPL-3.0` `Javascript`
- <b><code>&nbsp;39647⭐</code></b> <b><code>&nbsp;&nbsp;1631🍴</code></b> [copyparty](https://github.com/9001/copyparty)) - Portable file server with accelerated resumable uploads, deduplication, WebDAV, FTP, zeroconf, media indexer, video thumbnails, audio transcoding, and write-only folders, in a single file with no mandatory dependencies.  🌎 [Demo](a.ocv.me/pub/demo/)) `MIT` `Python`
- 🌎 [Directory Lister](www.directorylister.com/) - Simple PHP based directory lister that lists a directory and all its sub-directories and allows you to navigate there within. (<b><code>&nbsp;&nbsp;2468⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;523🍴</code></b> [Source Code](https://github.com/DirectoryLister/DirectoryLister))) `MIT` `PHP/Docker`
- 🌎 [filebrowser](filebrowser.org/) - Web File Browser with a Material Design web interface. (<b><code>&nbsp;32624⭐</code></b> <b><code>&nbsp;&nbsp;3622🍴</code></b> [Source Code](https://github.com/filebrowser/filebrowser))) `Apache-2.0` `Go`
- 🌎 [FileGator](filegator.io/) - FileGator is a powerful multi-user file manager with a single page front-end.  🌎 [Demo](demo.filegator.io), <b><code>&nbsp;&nbsp;2858⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;434🍴</code></b> [Source Code](https://github.com/filegator/filegator))) `MIT` `PHP/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;708⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [FileRise](https://github.com/error311/FileRise)) - Web file manager with uploads, tagging, share links, gallery/table views, and an in-browser editor. (<b><code>&nbsp;&nbsp;&nbsp;708⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Demo](https://github.com/error311/FileRise?tab=readme-ov-file#live-demo))) `MIT` `Docker/PHP`
- 🌎 [Filestash](www.filestash.app/) - Web file manager that lets you manage your data anywhere it is located: FTP, SFTP, WebDAV, Git, S3, Minio, Dropbox, or Google Drive.  🌎 [Demo](demo.filestash.app/), <b><code>&nbsp;13251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;943🍴</code></b> [Source Code](https://github.com/mickael-kerjean/filestash))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;1057⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [Gossa](https://github.com/pldubouilh/gossa)) - Light and simple webserver for your files. `MIT` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;363⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [IFM](https://github.com/misterunknown/ifm)) - Single script file manager. `MIT` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [mikochi](https://github.com/zer0tonin/Mikochi)) - Browse remote folders, upload files, delete, rename, download and stream files to VLC/mpv. `MIT` `Go/Docker/K8S`
- <b><code>&nbsp;&nbsp;7284⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;355🍴</code></b> [miniserve](https://github.com/svenstaro/miniserve)) - CLI tool to serve files and dirs over HTTP. `MIT` `Rust`
- 🌎 [ResourceSpace](www.resourcespace.com) - Simple, fast, and free way to organise your digital assets.  🌎 [Demo](www.resourcespace.com/trial), 🌎 [Source Code](www.resourcespace.com/svn)) `BSD-4-Clause` `PHP`
- 🌎 [slcl](gitea.privatedns.org/xavi/slcl) - Simple and lightweight web cloud storage.  🌎 [Source Code](codeberg.org/xavidcr/slcl)) `AGPL-3.0` `C`
- 🌎 [Surfer](git.cloudron.io/cloudron/surfer) - Simple static file server with webui to manage files. `MIT` `Nodejs`
- 🌎 [TagSpaces](www.tagspaces.org/) - TagSpaces is an offline, cross-platform file manager and organiser that also can function as a note taking app. The WebDAV version of the application can be installed on top of a WebDAV servers such as Nextcloud or ownCloud.  🌎 [Demo](demo.tagspaces.com), <b><code>&nbsp;&nbsp;4804⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;477🍴</code></b> [Source Code](https://github.com/tagspaces/tagspaces))) `AGPL-3.0` `Nodejs`
- 🌎 [Tiny File Manager](tinyfilemanager.github.io) - Web based File Manager in PHP, simple, fast and small file manager with a single file.  🌎 [Demo](tinyfilemanager.github.io/demo/), <b><code>&nbsp;&nbsp;5708⭐</code></b> <b><code>&nbsp;&nbsp;1804🍴</code></b> [Source Code](https://github.com/prasathmani/tinyfilemanager))) `GPL-3.0` `PHP`


### Games

**[`^        back to top        ^`](#awesome-selfhosted)**

Multiplayer game servers and 🌎 [browser games](en.wikipedia.org/wiki/Browser_game).

_Related: [Games - Administrative Utilities & Control Panels](#games---administrative-utilities--control-panels)_

- 🌎 [0 A.D.](play0ad.com/) - Cross-platform real-time strategy game of ancient warfare.  🌎 [Source Code](gitea.wildfiregames.com/0ad/0ad)) `MIT/GPL-2.0/Zlib` `C++/C/deb`
- <b><code>&nbsp;&nbsp;7906⭐</code></b> <b><code>&nbsp;&nbsp;1717🍴</code></b> [A Dark Room](https://github.com/doublespeakgames/adarkroom)) - Minimalist text adventure game for your browser.  🌎 [Demo](adarkroom.doublespeakgames.com/)) `MPL-2.0` `Javascript`
- 🌎 [Digibuzzer](digibuzzer.app/) - Create a virtual game room around a connected buzzer (documentation in French).  🌎 [Demo](digibuzzer.app/), 🌎 [Source Code](codeberg.org/ladigitale/digibuzzer)) `AGPL-3.0` `Nodejs`
- <b><code>&nbsp;&nbsp;1433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [Hypersomnia](https://github.com/TeamHypersomnia/Hypersomnia)) - Competitive top-down shooter blending Counter-Strike with Hotline Miami. Runs on Linux, Windows, MacOS and the Web.  🌎 [Demo](hypersomnia.io)) `AGPL-3.0` `C++/Docker`
- 🌎 [Lila](lichess.org/) - Ad-less chess server powering lichess.org, with official iOS and Android client apps. (<b><code>&nbsp;17506⭐</code></b> <b><code>&nbsp;&nbsp;2520🍴</code></b> [Source Code](https://github.com/lichess-org/lila))) `AGPL-3.0` `Scala`
- 🌎 [Luanti](www.luanti.org/) - Voxel game engine (formerly Minetest). Play one of our many games, mod a game to your liking, make your own game, or play on a multiplayer server. (<b><code>&nbsp;12165⭐</code></b> <b><code>&nbsp;&nbsp;2221🍴</code></b> [Source Code](https://github.com/luanti-org/luanti))) `LGPL-2.1/MIT/Zlib` `C++/Lua/deb`
- 🌎 [Mindustry](mindustrygame.github.io/) - Factorio-like tower defense game. Build production chains to gather more resources, and build complex facilities. (<b><code>&nbsp;26040⭐</code></b> <b><code>&nbsp;&nbsp;3326🍴</code></b> [Source Code](https://github.com/Anuken/Mindustry))) `GPL-3.0` `Java`
- 🌎 [MTA:SA](multitheftauto.com/) `⚠` - Add network play functionality to Rockstar North's Grand Theft Auto game series, in which this functionality is not originally found. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/multitheftauto/mtasa-blue))) `GPL-3.0` `C++`
- 🌎 [OpenTTD](www.openttd.org/) - Transport tycoon simulation game. (<b><code>&nbsp;&nbsp;7365⭐</code></b> <b><code>&nbsp;&nbsp;1069🍴</code></b> [Source Code](https://github.com/OpenTTD/OpenTTD)), 🌎 [Clients](bananas.openttd.org/)) `GPL-2.0` `C++/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;227⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [piqueserver](https://github.com/piqueserver/piqueserver)) - Server for openspades, the first-person shooter in a destructible voxel world. (<b><code>&nbsp;&nbsp;1198⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;227🍴</code></b> [Clients](https://github.com/yvt/openspades))) `GPL-3.0` `Python/C++`
- <b><code>&nbsp;&nbsp;&nbsp;664⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [Posio](https://github.com/abrenaut/posio)) - Geography multiplayer game. `MIT` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;297⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Quizmaster](https://github.com/nymanjens/quizmaster)) - Web application for conducting a quiz, including a page for players to enter their answers. `Apache-2.0` `Scala`
- 🌎 [Red Eclipse 2](redeclipse.net) - Arena first-person shooter similar to Unreal Tournament. (<b><code>&nbsp;&nbsp;&nbsp;487⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [Source Code](https://github.com/redeclipse/base))) `Zlib/MIT/CC-BY-SA-4.0` `C/C++/deb`
- <b><code>&nbsp;&nbsp;&nbsp;579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [Scribble.rs](https://github.com/scribble-rs/scribble.rs)) - A web-based pictionary game.  🌎 [Demo](scribblers.fly.dev)) `BSD-3-Clause` `Go/Docker`
- 🌎 [Suroi](suroi.io/) - An open-source 2D battle royale game inspired by surviv.io.  🌎 [Demo](suroi.io/), <b><code>&nbsp;&nbsp;&nbsp;422⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;205🍴</code></b> [Source Code](https://github.com/HasangerGames/suroi))) `GPL-3.0` `Nodejs`
- <b><code>&nbsp;&nbsp;6339⭐</code></b> <b><code>&nbsp;&nbsp;1143🍴</code></b> [The Battle for Wesnoth](https://github.com/wesnoth/wesnoth)) - The Battle for Wesnoth is an Open Source, turn-based tactical strategy game with a high fantasy theme, featuring both singleplayer and online/hotseat multiplayer combat. `GPL-2.0` `C++/deb`
- 🌎 [Veloren](veloren.net/) - Multiplayer RPG. Open-source game inspired by Cube World, Legend of Zelda, Dwarf Fortress and Minecraft.  🌎 [Source Code](gitlab.com/veloren/veloren)) `GPL-3.0` `Rust`
- <b><code>&nbsp;&nbsp;&nbsp;246⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [Word Mastermind](https://github.com/clupasq/word-mastermind)) - Wordle clone. A Mastermind-like game, but instead of colors you need to guess words.  🌎 [Demo](word-mastermind.glitch.me/)) `MIT` `Nodejs`
- 🌎 [Zero-K](zero-k.info/) - Open Source on Springrts engine. Zero-K is a traditional real time strategy game with a focus on player creativity through terrain manipulation, physics, and a large roster of unique units - all while being balanced to support competitive play. (<b><code>&nbsp;&nbsp;&nbsp;774⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;232🍴</code></b> [Source Code](https://github.com/ZeroK-RTS/Zero-K))) `GPL-2.0` `Lua`


### Games - Administrative Utilities & Control Panels

**[`^        back to top        ^`](#awesome-selfhosted)**

Utilities for managing game servers.

_Related: [Games](#games)_

- 🌎 [auto-mcs](www.auto-mcs.com) - Cross-platform Minecraft server manager. (<b><code>&nbsp;&nbsp;&nbsp;358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Source Code](https://github.com/macarooni-man/auto-mcs))) `AGPL-3.0` `Python`
- 🌎 [Crafty Controller](craftycontrol.com/) - Minecraft launcher and manager that allows users to start and administer Minecraft servers from a user-friendly interface.  🌎 [Source Code](gitlab.com/crafty-controller/crafty-4)) `GPL-3.0` `Docker/Python`
- 🌎 [Drop](droposs.org) - Game distribution platform, designed for distributing and sharing DRM-free games efficiently (alternative to Steam, GameVault). (<b><code>&nbsp;&nbsp;&nbsp;561⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Source Code](https://github.com/Drop-OSS/drop)), <b><code>&nbsp;&nbsp;&nbsp;147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Clients](https://github.com/Drop-OSS/drop-app))) `AGPL-3.0` `Docker`
- 🌎 [EasyWI](easy-wi.com) - Easy-Wi is a Web-interface that allows you to manage server daemons like gameservers. In addition it provides you with a CMS which includes a fully automated game- and voiceserver lending service. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/easy-wi/developer/))) `GPL-3.0` `PHP/Shell`
- 🌎 [Gameyfin](gameyfin.org) - Video game library manager with automatic scanning, web access, downloads, and plugin support. (<b><code>&nbsp;&nbsp;&nbsp;894⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Source Code](https://github.com/gameyfin/gameyfin))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;781⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Gaseous Server](https://github.com/gaseous-project/gaseous-server)) `⚠` - Game ROM manager with a built-in web-based emulator using multiple sources to identify and provide metadata. `AGPL-3.0` `Docker/.NET`
- 🌎 [Kubek](kubek.seeeroy.ru) - Web management panel for Minecraft servers. (<b><code>&nbsp;&nbsp;&nbsp;125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Source Code](https://github.com/seeroy/kubek-minecraft-dashboard))) `GPL-3.0` `Nodejs`
- 🌎 [Lancache](lancache.net) `⚠` - LAN Party game caching made easy. (<b><code>&nbsp;&nbsp;&nbsp;851⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [Source Code](https://github.com/lancachenet/monolithic))) `MIT` `Docker/Shell`
- 🌎 [LinuxGSM](linuxgsm.com/) - CLI tool for deployment and management of dedicated game servers on Linux: more than 120 games are supported. (<b><code>&nbsp;&nbsp;4707⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;853🍴</code></b> [Source Code](https://github.com/GameServerManagers/LinuxGSM))) `MIT` `Shell`
- 🌎 [Minus Games](accessory.github.io/minus_games_user_guide) - Sync games and save files across multiple devices. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/Accessory/minus_games))) `MIT` `Rust`
- 🌎 [Pelican Panel](pelican.dev/) - Web application for easy management of game servers, offering a user-friendly interface for deploying, configuring, and managing servers, server monitoring tools, and extensive customization options (fork of Pterodactyl). (<b><code>&nbsp;&nbsp;1780⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [Source Code](https://github.com/pelican-dev/panel))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Pterodactyl](pterodactyl.io/) - Management panel for game servers, with an intuitive UI for end users. (<b><code>&nbsp;&nbsp;8424⭐</code></b> <b><code>&nbsp;&nbsp;2401🍴</code></b> [Source Code](https://github.com/pterodactyl/panel))) `MIT` `PHP`
- 🌎 [PufferPanel](www.pufferpanel.com/) - Game server management panel designed for both small networks and game server providers. (<b><code>&nbsp;&nbsp;1622⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;252🍴</code></b> [Source Code](https://github.com/pufferpanel/pufferpanel))) `Apache-2.0` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;612⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [RconCli](https://github.com/gorcon/rcon-cli)) - CLI for executing queries on a remote Valve Source dedicated server using the RCON Protocol. `MIT` `Go`
- <b><code>&nbsp;&nbsp;1614⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Retrom](https://github.com/JMBeresford/retrom)) - Private cloud game library distribution server + frontend/launcher. `GPL-3.0` `Docker/Rust`
- 🌎 [RomM](romm.app/) `⚠` - ROM manager for organizing, enriching, and playing retro games, with support for 400+ platforms.  🌎 [Demo](demo.romm.app/), <b><code>&nbsp;&nbsp;7333⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;315🍴</code></b> [Source Code](https://github.com/rommapp/romm))) `AGPL-3.0` `Docker`
- 🌎 [SourceBans++](sbpp.github.io/) - Admin, ban, and communication management system for games running on the Source engine. (<b><code>&nbsp;&nbsp;&nbsp;348⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;177🍴</code></b> [Source Code](https://github.com/sbpp/sourcebans-pp))) `CC-BY-SA-4.0` `PHP`
- 🌎 [Sunshine](app.lizardbyte.dev/Sunshine/) - Remote game stream host for Moonlight with support up to 120 frames per second and 4K resolution. (<b><code>&nbsp;32690⭐</code></b> <b><code>&nbsp;&nbsp;1586🍴</code></b> [Source Code](https://github.com/LizardByte/Sunshine))) `GPL-3.0` `C++/deb/Docker`


### Genealogy

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Genealogy software](en.wikipedia.org/wiki/Genealogy_software) used to record, organize, and publish genealogical data.

- 🌎 [Genea.app](www.genea.app/) - Genealogy tool designed with privacy in mind that anyone can use to author or edit their family tree. Data is stored in the GEDCOM format and all processing is done in the browser. (<b><code>&nbsp;&nbsp;&nbsp;248⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Source Code](https://github.com/genea-app/genea-app))) `MIT` `Javascript`
- 🌎 [Genealogy](genealogy.kreaweb.be/) - Record family members and their relationships and build a family tree.  🌎 [Demo](genealogy.kreaweb.be/), <b><code>&nbsp;&nbsp;&nbsp;293⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Source Code](https://github.com/MGeurts/genealogy))) `MIT` `PHP`
- 🌎 [GeneWeb](geneweb.tuxfamily.org/wiki/GeneWeb) - Genealogy software that can be used offline or as a Web service. (<b><code>&nbsp;&nbsp;&nbsp;365⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Source Code](https://github.com/geneweb/geneweb))) `GPL-2.0` `OCaml`
- 🌎 [Gramps Web](www.grampsweb.org/) - Web app for collaborative genealogy, based on and interoperable with Gramps, the open source genealogy desktop application.  🌎 [Demo](gramps-project.github.io/gramps-web-api/), <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [Source Code](https://github.com/gramps-project/gramps-web-api))) `AGPL-3.0` `Docker`
- 🌎 [webtrees](www.webtrees.net) - Webtrees is the web's leading online collaborative genealogy application.  🌎 [Demo](dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), <b><code>&nbsp;&nbsp;&nbsp;686⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;335🍴</code></b> [Source Code](https://github.com/fisharebest/webtrees))) `GPL-3.0` `PHP`


### Generative Artificial Intelligence (GenAI)

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Generative Artificial Intelligence (GenAI)](en.wikipedia.org/wiki/Generative_artificial_intelligence) is a subset of 🌎 [artificial intelligence](en.wikipedia.org/wiki/Artificial_intelligence) that uses generative models to produce text, images, videos, or other forms of data.

- 🌎 [Agenta](agenta.ai/) - LLMOps platform for prompt management, LLM evaluation, and observability. Build, evaluate, and monitor production-grade LLM applications with collaborative prompt engineering. (<b><code>&nbsp;&nbsp;3555⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;425🍴</code></b> [Source Code](https://github.com/agenta-ai/agenta))) `MIT` `Docker`
- 🌎 [AnythingLLM](anythingllm.com/) - All-in-one desktop & Docker AI application with built-in RAG, AI agents, No-code agent builder, MCP compatibility, and more. (<b><code>&nbsp;52547⭐</code></b> <b><code>&nbsp;&nbsp;5627🍴</code></b> [Source Code](https://github.com/Mintplex-Labs/anything-llm))) `MIT` `Nodejs/Docker`
- 🌎 [Khoj](khoj.dev/) - Your AI second brain. Get answers from the web or your docs. Build custom agents, schedule automations, do deep research. Turn any online or local LLM into your personal, autonomous AI.  🌎 [Demo](app.khoj.dev/), <b><code>&nbsp;32006⭐</code></b> <b><code>&nbsp;&nbsp;1904🍴</code></b> [Source Code](https://github.com/khoj-ai/khoj))) `AGPL-3.0` `Python/Docker`
- 🌎 [Ollama](ollama.com/) - Get up and running with Llama 3.3, DeepSeek-R1, Phi-4, Gemma 3, and other large language models. (<b><code>158262⭐</code></b> <b><code>&nbsp;14008🍴</code></b> [Source Code](https://github.com/ollama/ollama))) `MIT` `Docker/Python`
- 🌎 [Onyx Community Edition](onyx.app) - Chat UI that works with any LLM. It comes loaded with advanced features like agents, web search, RAG, MCP, deep research, Connectors to 40+ knowledge sources, and more. (<b><code>&nbsp;16911⭐</code></b> <b><code>&nbsp;&nbsp;2259🍴</code></b> [Source Code](https://github.com/onyx-dot-app/onyx))) `MIT` `Docker/K8S`
- 🌎 [Open-WebUI](openwebui.com) - User-friendly AI Interface, supports Ollama, OpenAI API. (<b><code>118974⭐</code></b> <b><code>&nbsp;16752🍴</code></b> [Source Code](https://github.com/open-webui/open-webui))) `BSD-3-Clause` `Docker/Python`
- <b><code>&nbsp;27805⭐</code></b> <b><code>&nbsp;&nbsp;2912🍴</code></b> [Perplexica](https://github.com/ItzCrazyKns/Perplexica)) - AI-powered search engine (alternative to Perplexity AI). `MIT` `Docker`
- 🌎 [TuxSEO](tuxseo.com/) `⚠` - Create automated blog content for your business, using AI. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Source Code](https://github.com/rasulkireev/TuxSEO))) `MIT` `Python/Django/Docker`


### Groupware

**[`^        back to top        ^`](#awesome-selfhosted)**

Collaborative software or 🌎 [groupware](en.wikipedia.org/wiki/Collaborative_software) is designed to help people working on a common task to attain their goals. Groupware often regroups multiple services such as file sharing, calendar/events management, address books... in a single, integrated application.

- 🌎 [Citadel](www.citadel.org/) - Groupware including email, calendar/scheduling, address books, forums, mailing lists, IM, wiki and blog engines, RSS aggregation and more.  🌎 [Source Code](www.citadel.org/source.html)) `GPL-3.0` `C/Docker/Shell`
- 🌎 [Colanode](colanode.com) - Collaboration suite with real-time messaging, rich text pages, file management, and dynamic databases - built for offline work (alternative to Slack, Notion). (<b><code>&nbsp;&nbsp;4196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;222🍴</code></b> [Source Code](https://github.com/colanode/colanode))) `Apache-2.0` `K8S/Docker`
- 🌎 [Cozy Cloud](cozy.io/) - Personal cloud where you can manage and sync your files, notes, contacts, passwords, and documents. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/cozy/)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Clients](https://github.com/cozy/cozy-store))) `GPL-3.0` `Nodejs`
- 🌎 [Digipad](digipad.app/) - An online self-hosted application for creating collaborative digital notepads (Documentation in french).  🌎 [Source Code](codeberg.org/ladigitale/digipad)) `AGPL-3.0` `Nodejs`
- 🌎 [Digistorm](digistorm.app/) - Create collaborative surveys, quizzes, brainstorms, and word clouds (documentation in French).  🌎 [Demo](digistorm.app/), 🌎 [Source Code](codeberg.org/ladigitale/digistorm)) `AGPL-3.0` `Nodejs`
- 🌎 [Digiwall](digiwall.app/) - Create multimedia collaborative walls for in-person or remote work (documentation in French).  🌎 [Source Code](codeberg.org/ladigitale/digiwall)) `AGPL-3.0` `Nodejs`
- 🌎 [egroupware](www.egroupware.org/) - Software suite including calendars, address books, notepad, project management tools, client relationship management tools (CRM), knowledge management tools, a wiki and a CMS. (<b><code>&nbsp;&nbsp;&nbsp;282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [Source Code](https://github.com/EGroupware/egroupware))) `GPL-2.0` `PHP`
- 🌎 [Group Office](www.group-office.com) - Enterprise CRM and groupware tool. Share projects, calendars, files and e-mail online with co-workers and clients. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/Intermesh/groupoffice/))) `AGPL-3.0` `PHP`
- 🌎 [Openmeetings](openmeetings.apache.org/index.html) - Video conferencing, instant messaging, whiteboard, collaborative document editing and other groupware tools using API functions of the Red5 Streaming Server for Remoting and Streaming. (<b><code>&nbsp;&nbsp;&nbsp;669⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;260🍴</code></b> [Source Code](https://github.com/apache/openmeetings))) `Apache-2.0` `Java`
- 🌎 [SOGo](www.sogo.nu/) - SOGo offers multiple ways to access the calendaring and messaging data. CalDAV, CardDAV, GroupDAV, as well as ActiveSync, including native Outlook compatibility and Web interface.  🌎 [Demo](demo.sogo.nu/SOGo/), <b><code>&nbsp;&nbsp;2045⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;300🍴</code></b> [Source Code](https://github.com/Alinto/sogo))) `LGPL-2.1` `Objective-C`
- 🌎 [Tine](www.tine-groupware.de/) - Software for digital collaboration in companies and organizations. From powerful groupware functionalities to clever add-ons, tine combines everything to make daily team collaboration easier. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Source Code](https://github.com/tine-groupware/tine))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Tracim](https://github.com/tracim/tracim)) - Collaborative Platform for team collaboration: file,threads,notes,agenda,etc. `AGPL-3.0/LGPL-3.0/MIT` `Python`
- 🌎 [Zimbra Collaboration](www.zimbra.com/) - Email, calendar, collaboration server with Web interface and lots of integrations. ([Source Code](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`


### Health and Fitness

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Medical](en.wikipedia.org/wiki/Medical_software), 🌎 [Health](en.wikipedia.org/wiki/Health_information_technology) and 🌎 [Fitness](en.wikipedia.org/wiki/Fitness_tracker) software.

- 🌎 [Endurain](docs.endurain.com/) - Fitness tracking service designed to give users full control over their data and hosting environment. (<b><code>&nbsp;&nbsp;1610⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/joaovitoriasilva/endurain))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Fasten Health](https://github.com/fastenhealth/fasten-onprem/)) `⚠` - Personal/family electronic medical record aggregator, designed to integrate with hundreds of thousands of insurances/hospitals/clinics in the United States. `GPL-3.0` `Go/Docker`
- 🌎 [Mere Medical](meremedical.co/) `⚠` - Manage all of your medical records from Epic MyChart, Cerner, and OnPatient patient portals in one place. Privacy-focused, self-hosted, and offline-first.  🌎 [Demo](demo.meremedical.co), <b><code>&nbsp;&nbsp;&nbsp;225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Source Code](https://github.com/cfu288/mere-medical))) `GPL-3.0` `Docker/Nodejs`
- 🌎 [OpenEMR](www.open-emr.org/) - Electronic health records and medical practice management solution.  🌎 [Demo](www.open-emr.org/demo/), <b><code>&nbsp;&nbsp;4603⭐</code></b> <b><code>&nbsp;&nbsp;2670🍴</code></b> [Source Code](https://github.com/openemr/openemr))) `GPL-3.0` `PHP/Docker`
- 🌎 [wger](wger.de/) - Web-based personal workout, fitness and weight logger/tracker. It can also be used as a simple gym management utility and offers a full REST API as well.  🌎 [Demo](wger.de/en/dashboard), <b><code>&nbsp;&nbsp;5436⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;797🍴</code></b> [Source Code](https://github.com/wger-project/wger))) `AGPL-3.0` `Python/Docker`
- 🌎 [Wingfit](wingfit.fr) - Minimalist fitness app to plan your workouts, track your personal records and leverage smartwatch data.  🌎 [Demo](wingfit.fr/home), <b><code>&nbsp;&nbsp;&nbsp;420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Source Code](https://github.com/itskovacs/wingfit))) `CC-BY-SA-4.0` `Python/Docker`


### Human Resources Management (HRM)

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [human resources management system](en.wikipedia.org/wiki/Human_resource_management_system) combines a number of systems and processes to ensure the easy management of 🌎 [human resources](en.wikipedia.org/wiki/Human_resources), business processes and data.

- 🌎 [admidio](www.admidio.org/) - User management system for websites of organizations and groups. The system has a flexible role model so that it’s possible to reflect the structure and permissions of your organization.  🌎 [Demo](www.admidio.org/demo/), <b><code>&nbsp;&nbsp;&nbsp;420⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [Source Code](https://github.com/Admidio/admidio))) `GPL-2.0` `PHP/Docker`
- 🌎 [Frappe HR](frappe.io/hr) - Complete HRMS solution with over 13 different modules right from employee management, onboarding, leaves, to payroll, taxation, and more. (<b><code>&nbsp;&nbsp;7038⭐</code></b> <b><code>&nbsp;&nbsp;1885🍴</code></b> [Source Code](https://github.com/frappe/hrms))) `GPL-3.0` `Docker/Python/Nodejs`
- 🌎 [MintHCM](minthcm.org/) - Tool for Human Capital Management based on two popular, well-known business applications SugarCRM Community Edition and SuiteCRM. (<b><code>&nbsp;&nbsp;&nbsp;275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Source Code](https://github.com/minthcm/minthcm))) `AGPL-3.0` `PHP`


### Identity Management

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Identity management](en.wikipedia.org/wiki/Identity_management) (IdM), also known as identity and access management (IAM or IdAM), is a framework of policies and technologies to ensure that the right users have the appropriate access to technology resources.

**Please visit <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/Identity Management](https://github.com/awesome-foss/awesome-sysadmin#identity-management))**



### Internet of Things (IoT)

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Internet of Things](en.wikipedia.org/wiki/Internet_of_things) describes physical objects with sensors, processing ability, software, and other technologies that connect and exchange data with other devices over the Internet.

- 🌎 [Domoticz](www.domoticz.com/) - Home Automation System that lets you monitor and configure various devices like: Lights, Switches, various sensors/meters like Temperature, Rain, Wind, UV, Electra, Gas, Water and much more. (<b><code>&nbsp;&nbsp;3696⭐</code></b> <b><code>&nbsp;&nbsp;1151🍴</code></b> [Source Code](https://github.com/domoticz/domoticz)), <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [Clients](https://github.com/domoticz/domoticz-android))) `GPL-3.0` `C/C++/Docker/Shell`
- 🌎 [EMQX](www.emqx.io/) - Scalable MQTT broker. Connect 100M+ IoT devices in one single cluster, move and process real-time IoT data with 1M msg/s throughput at 1ms latency.  🌎 [Demo](www.emqx.com/en/mqtt/public-mqtt5-broker), <b><code>&nbsp;15731⭐</code></b> <b><code>&nbsp;&nbsp;2428🍴</code></b> [Source Code](https://github.com/emqx/emqx))) `Apache-2.0` `Docker/Erlang`
- 🌎 [evcc](evcc.io/) - Extensible Electric Vehicle Charge Controller and home energy management system. (<b><code>&nbsp;&nbsp;5902⭐</code></b> <b><code>&nbsp;&nbsp;1148🍴</code></b> [Source Code](https://github.com/evcc-io/evcc))) `MIT` `deb/Docker/Go`
- 🌎 [FHEM](fhem.de/fhem.html) - Automate common tasks in the household like switching lamps and heating. It can also be used to log events like temperature or power consumption. You can control it via web or smartphone frontends, telnet or TCP/IP directly.  🌎 [Source Code](svn.fhem.de/trac)) `GPL-3.0` `Perl`
- 🌎 [FlowForge](flowforge.com/) - Deploy Node-RED applications in a reliable, scalable and secure manner. The FlowForge platform provides DevOps capabilities for Node-RED development teams. (<b><code>&nbsp;&nbsp;&nbsp;366⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [Source Code](https://github.com/FlowFuse/flowfuse))) `Apache-2.0` `Nodejs/Docker/K8S`
- 🌎 [FMD Server](fmd-foss.org) - A server to communicate with the FMD (Find My Device) Android app, to locate and control your devices.  🌎 [Source Code](gitlab.com/fmd-foss/fmd-server), 🌎 [Clients](gitlab.com/fmd-foss/fmd-android)) `GPL-3.0` `Docker/Go`
- 🌎 [Gladys](gladysassistant.com/) - Privacy-first home assistant. (<b><code>&nbsp;&nbsp;2957⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;301🍴</code></b> [Source Code](https://github.com/GladysAssistant/Gladys))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [Home Assistant](home-assistant.io/) - Home automation platform.  🌎 [Demo](home-assistant.io/demo/), <b><code>&nbsp;83691⭐</code></b> <b><code>&nbsp;36292🍴</code></b> [Source Code](https://github.com/home-assistant/core))) `Apache-2.0` `Python/Docker`
- 🌎 [ioBroker](www.iobroker.net/) - Integration platform for the Internet of Things, focused on building automation, smart metering, ambient assisted living, process automation, visualization and data logging. (<b><code>&nbsp;&nbsp;1352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [Source Code](https://github.com/ioBroker/ioBroker))) `MIT` `Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [LHA](https://github.com/javalikescript/lha)) - Light Home Automation application that is fully extensible using Blockly, HTML or Lua. It includes extensions such as ConBee, Philips Hue or Z-Wave JS. `MIT` `Lua`
- 🌎 [Node RED](nodered.org/) - Browser-based flow editor that helps you wiring hardware devices, APIs and online services to create IoT solutions. (<b><code>&nbsp;22517⭐</code></b> <b><code>&nbsp;&nbsp;3763🍴</code></b> [Source Code](https://github.com/node-red/node-red))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [openHAB](www.openhab.org) - Vendor and technology agnostic open source software for home automation. (<b><code>&nbsp;&nbsp;1080⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;459🍴</code></b> [Source Code](https://github.com/openhab/openhab-core))) `EPL-2.0` `Java`
- 🌎 [OpenRemote](openremote.io) - IoT Asset management, Flow Rules and WHEN-THEN rules, Data visualization, Edge Gateway.  🌎 [Demo](demo.openremote.io/), <b><code>&nbsp;&nbsp;1604⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;397🍴</code></b> [Source Code](https://github.com/openremote/openremote))) `AGPL-3.0` `Java`
- 🌎 [SIP Irrigation Control](dan-in-ca.github.io/SIP/) - Open source software for sprinkler/irrigation control. (<b><code>&nbsp;&nbsp;&nbsp;402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;164🍴</code></b> [Source Code](https://github.com/Dan-in-CA/SIP))) `GPL-3.0` `Python`
- 🌎 [Tasmota](tasmota.com) - Open source firmware for ESP devices. Total local control with quick setup and updates. Control using MQTT, Web UI, HTTP or serial. Automate using timers, rules or scripts. Integration with home automation solutions. (<b><code>&nbsp;23978⭐</code></b> <b><code>&nbsp;&nbsp;5040🍴</code></b> [Source Code](https://github.com/arendst/Tasmota))) `GPL-3.0` `C/C++`
- 🌎 [Thingsboard](thingsboard.io/) - Open-source IoT Platform - Device management, data collection, processing and visualization.  🌎 [Demo](demo.thingsboard.io/signup), <b><code>&nbsp;20678⭐</code></b> <b><code>&nbsp;&nbsp;5999🍴</code></b> [Source Code](https://github.com/thingsboard/thingsboard))) `Apache-2.0` `Java/Docker/K8S`
- 🌎 [WebThings Gateway](webthings.io/gateway/) - WebThings is an open source implementation of the Web of Things, including the WebThings Gateway and the WebThings Framework. (<b><code>&nbsp;&nbsp;2630⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;330🍴</code></b> [Source Code](https://github.com/WebThingsIO/gateway))) `MPL-2.0` `Nodejs`


### Inventory Management

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Inventory management software](en.wikipedia.org/wiki/Inventory_management_software).

_Related: [Money, Budgeting & Management](#money-budgeting--management), [Resource Planning](#resource-planning)_

_See also: <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/IT Asset Management](https://github.com/awesome-foss/awesome-sysadmin#it-asset-management))_

- 🌎 [Cannery](cannery.app) - Firearm and ammunition tracker app.  🌎 [Source Code](gitea.bubbletea.dev/shibao/cannery)) `AGPL-3.0` `Docker`
- 🌎 [HomeBox (SysAdminsMedia)](homebox.software/) - Inventory and organization system built for the home user.  🌎 [Demo](demo.homebox.software/), <b><code>&nbsp;&nbsp;4507⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;284🍴</code></b> [Source Code](https://github.com/sysadminsmedia/homebox))) `AGPL-3.0` `Docker/Go`
- 🌎 [Inventaire](inventaire.io/welcome) - Collaborative resources mapper project, while yet only focused on exploring books mapping with wikidata and ISBNs.  🌎 [Source Code](codeberg.org/inventaire/inventaire)) `AGPL-3.0` `Nodejs`
- 🌎 [Inventree](docs.inventree.org/en/latest/) - Inventory management system which provides intuitive parts management and stock control.  🌎 [Demo](inventree.org/demo), <b><code>&nbsp;&nbsp;6144⭐</code></b> <b><code>&nbsp;&nbsp;1188🍴</code></b> [Source Code](https://github.com/inventree/InvenTree))) `MIT` `Python`
- 🌎 [Open QuarterMaster](openquartermaster.com/) - Powerful inventory management system, designed to be flexible and scalable. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Source Code](https://github.com/Epic-Breakfast-Productions/OpenQuarterMaster))) `GPL-3.0` `deb/Docker`
- 🌎 [Part-DB](docs.part-db.de/) - Inventory management system for your electronic components.  🌎 [Demo](demo.part-db.de/en/), <b><code>&nbsp;&nbsp;1417⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [Source Code](https://github.com/Part-DB/Part-DB-server))) `AGPL-3.0` `Docker/PHP/Nodejs`
- 🌎 [Shelf](www.shelf.nu) - Asset and equipment tracking software used by teams who value clarity. Shelf is an asset database and QR asset label generator that lets you create, manage and overview your assets across locations. Unlimited assets, free forever. (<b><code>&nbsp;&nbsp;2357⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;246🍴</code></b> [Source Code](https://github.com/Shelf-nu/shelf.nu))) `AGPL-3.0` `Nodejs`
- <b><code>&nbsp;&nbsp;1987⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;187🍴</code></b> [Spoolman](https://github.com/Donkie/Spoolman)) - Keep track of your inventory of 3D-printer filament spools. `MIT` `Docker/Python`


### Knowledge Management Tools

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Knowledge management](en.wikipedia.org/wiki/Knowledge_management) is the collection of methods relating to creating, sharing, using and managing the knowledge and information.

_Related: [Note-taking & Editors](#note-taking--editors), [Wikis](#wikis), [Database Management](#database-management)_

- 🌎 [AFFiNE Community Edition](affine.pro/) - Next-gen knowledge base that brings planning, sorting and creating all together. Privacy first, customizable and ready to use (alternative to Notion and Miro).  🌎 [Demo](app.affine.pro/), <b><code>&nbsp;61057⭐</code></b> <b><code>&nbsp;&nbsp;4210🍴</code></b> [Source Code](https://github.com/toeverything/AFFiNE))) `MIT/AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;1455⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [Atomic Server](https://github.com/atomicdata-dev/atomic-server)) - Knowledge graph database with documents (similar to Notion), tables, search, and a powerful linked data API. Lightweight, very fast and no runtime dependencies.  🌎 [Demo](atomicdata.dev/)) `MIT` `Docker/Rust`
- 🌎 [Digimindmap](ladigitale.dev/digimindmap/#/) - Create simple mindmaps (documentation in French).  🌎 [Demo](ladigitale.dev/digimindmap/#/), 🌎 [Source Code](codeberg.org/ladigitale/digimindmap)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [LibreKB](librekb.com/) - Web-based knowledge base solution. A simple web app, it runs on pretty much any web server or hosting provider with PHP and MySQL. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/michaelstaake/LibreKB/))) `GPL-3.0` `PHP`
- 🌎 [memEx](gitea.bubbletea.dev/shibao/memEx) - Structured personal knowledge base, inspired by zettlekasten and org-mode. `AGPL-3.0` `Docker`
- 🌎 [SiYuan](b3log.org/siyuan/) - A privacy-first personal knowledge management software, written in typescript and golang. (<b><code>&nbsp;40079⭐</code></b> <b><code>&nbsp;&nbsp;2485🍴</code></b> [Source Code](https://github.com/siyuan-note/siyuan))) `AGPL-3.0` `Docker/Go`
- <b><code>&nbsp;&nbsp;&nbsp;408⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [TeamMapper](https://github.com/b310-digital/teammapper)) - Host and create your own mindmaps. Share your mindmap sessions with your team and collaborate live on mindmaps.  🌎 [Demo](map.kits.blog)) `MIT` `Docker/Nodejs`


### Learning and Courses

**[`^        back to top        ^`](#awesome-selfhosted)**

Tools and software to help with education and learning.

- 🌎 [Canvas LMS](www.instructure.com/canvas/) - Learning management system (LMS) that is revolutionizing the way we educate.  🌎 [Demo](canvas.instructure.com/register), <b><code>&nbsp;&nbsp;6357⭐</code></b> <b><code>&nbsp;&nbsp;2825🍴</code></b> [Source Code](https://github.com/instructure/canvas-lms))) `AGPL-3.0` `Ruby`
- 🌎 [Chamilo LMS](chamilo.org/) - Create a virtual campus for the provision of online or semi-online training. (<b><code>&nbsp;&nbsp;&nbsp;913⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;531🍴</code></b> [Source Code](https://github.com/chamilo/chamilo-lms))) `GPL-3.0` `PHP`
- 🌎 [Digiscreen](ladigitale.dev/digiscreen/) - Interactive whiteboard/wallpaper for the classroom, in person or remotely (documentation in French).  🌎 [Demo](ladigitale.dev/digiscreen/), 🌎 [Source Code](codeberg.org/ladigitale/digiscreen)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [Digitools](ladigitale.dev/digitools) - A set of simple tools to accompany the animation of courses in person or remotely. (documentation in French).  🌎 [Demo](ladigitale.dev/digitools/), 🌎 [Source Code](codeberg.org/ladigitale/digitools)) `AGPL-3.0` `PHP`
- 🌎 [edX](www.edx.org/) - The Open edX platform is open-source code that powers edX.org. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/edx/))) `AGPL-3.0` `Python`
- 🌎 [Gibbon](gibbonedu.org/) - Flexible school management platform designed to make life better for teachers, students, parents and leaders. (<b><code>&nbsp;&nbsp;&nbsp;571⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;381🍴</code></b> [Source Code](https://github.com/GibbonEdu/core))) `GPL-3.0` `PHP`
- 🌎 [ILIAS](www.ilias.de) - Learning management system that can cope with anything you throw at it.  🌎 [Demo](demo.ilias.de), <b><code>&nbsp;&nbsp;&nbsp;454⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;395🍴</code></b> [Source Code](https://github.com/ILIAS-eLearning/ILIAS))) `GPL-3.0` `PHP`
- 🌎 [INGInious](inginious.org/?lang=en) - Intelligent grader that allows secured and automated testing of code made by students. (<b><code>&nbsp;&nbsp;&nbsp;231⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [Source Code](https://github.com/INGInious/INGInious)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Clients](https://github.com/INGInious/plugins))) `AGPL-3.0` `Python/Docker`
- 🌎 [Moodle](moodle.org/) - Learning and courses platform with one of the largest open source communities worldwide.  🌎 [Demo](moodle.org/demo/), 🌎 [Source Code](git.moodle.org/gw)) `GPL-3.0` `PHP`
- 🌎 [Open eClass](www.openeclass.org/) - Open eClass is an advanced e-learning solution that can enhance the teaching and learning process.  🌎 [Demo](demo.openeclass.org/), <b><code>&nbsp;&nbsp;&nbsp;146⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [Source Code](https://github.com/gunet/openeclass))) `GPL-2.0` `PHP`
- 🌎 [OpenOLAT](www.openolat.com/?lang=en) - Learning management system for teaching, education, assessment and communication.  🌎 [Demo](learn.olat.com), <b><code>&nbsp;&nbsp;&nbsp;405⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;168🍴</code></b> [Source Code](https://github.com/OpenOLAT/OpenOLAT))) `Apache-2.0` `Java`
- 🌎 [QST](qstonline.org) - Online assessment software. From a quick quiz on your phone to large scale, high stakes, proctored desktop testing, easy, secure and economical.  🌎 [Demo](qstonline.org/free_account.htm), 🌎 [Source Code](sourceforge.net/projects/qstonline/)) `GPL-2.0` `Perl`
- 🌎 [RELATE](documen.tician.de/relate/) - Courseware package that includes features such as: flexible rules, statistics, multi-course support, class calendar. (<b><code>&nbsp;&nbsp;&nbsp;421⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [Source Code](https://github.com/inducer/relate))) `MIT` `Python`
- 🌎 [RosarioSIS](www.rosariosis.org/) - Student Information System for school management. Features students demographics, grades, scheduling, attendance, student billing, discipline & food service modules.  🌎 [Demo](www.rosariosis.org/demo/), 🌎 [Source Code](gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Schoco](https://github.com/PhiTux/schoco)) - Online IDE for learning Java programming at school, including automatic JUnit tests. Designed to give coding homework/assignments. `MIT` `Docker`


### Manufacturing

**[`^        back to top        ^`](#awesome-selfhosted)**

Software to manage 🌎 [3D printers](en.wikipedia.org/wiki/3D_printing), 🌎 [CNC machines](en.wikipedia.org/wiki/Numerical_control) and other physical manufacturing tools.

- 🌎 [CNCjs](cnc.js.org/) - Web interface for CNC milling controllers running Grbl, Smoothieware, or TinyG. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/cncjs/cncjs/))) `MIT` `Nodejs`
- 🌎 [Fluidd](docs.fluidd.xyz/) - Lightweight & responsive user interface for Klipper, the 3D printer firmware. (<b><code>&nbsp;&nbsp;1666⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;543🍴</code></b> [Source Code](https://github.com/fluidd-core/fluidd))) `GPL-3.0` `Docker/Nodejs`
- 🌎 [Mainsail](docs.mainsail.xyz/) - Modern and responsive user interface for the Klipper 3D printer firmware. Control and monitor your printer from everywhere, from any device. (<b><code>&nbsp;&nbsp;2038⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;494🍴</code></b> [Source Code](https://github.com/mainsail-crew/mainsail))) `GPL-3.0` `Docker/Python`
- 🌎 [Manyfold](manyfold.app) - Digital asset manager for 3d print files; STL, OBJ, 3MF and more. (<b><code>&nbsp;&nbsp;1618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [Source Code](https://github.com/manyfold3d/manyfold))) `MIT` `Docker`
- 🌎 [Octoprint](octoprint.org/) - Snappy web interface for controlling consumer 3D printers. (<b><code>&nbsp;&nbsp;8815⭐</code></b> <b><code>&nbsp;&nbsp;1682🍴</code></b> [Source Code](https://github.com/OctoPrint/OctoPrint))) `AGPL-3.0` `Docker/Python`


### Maps and Global Positioning System (GPS)

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Maps](en.wikipedia.org/wiki/Map), 🌎 [cartography](en.wikipedia.org/wiki/Cartography), 🌎 [GIS](en.wikipedia.org/wiki/Geographic_information_system) and 🌎 [GPS](en.wikipedia.org/wiki/Global_Positioning_System) software.

_See also: <b><code>&nbsp;&nbsp;&nbsp;848⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [awesome-openstreetmap](https://github.com/osmlab/awesome-openstreetmap)), <b><code>&nbsp;&nbsp;5112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;772🍴</code></b> [awesome-gis](https://github.com/sshuair/awesome-gis))_

- 🌎 [AdventureLog](adventurelog.app) - Travel tracker and trip planner.  🌎 [Demo](demo.adventurelog.app/signup), <b><code>&nbsp;&nbsp;2462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;160🍴</code></b> [Source Code](https://github.com/seanmorley15/AdventureLog))) `GPL-3.0` `Docker`
- 🌎 [AirTrail](airtrail.johan.ohly.dk) - Personal flight tracking system. (<b><code>&nbsp;&nbsp;&nbsp;806⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Source Code](https://github.com/johanohly/AirTrail))) `GPL-3.0` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Bicimon](https://github.com/knrdl/bicimon)) - Bike Speedometer as Progressive Web App.  🌎 [Demo](knrdl.github.io/bicimon/)) `MIT` `Javascript`
- 🌎 [Dawarich](dawarich.app/) - Visualize your location history, track your movements, and analyze your travel patterns with complete privacy and control (alternative to Google Timeline a.k.a. Google Location History). (<b><code>&nbsp;&nbsp;7507⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;236🍴</code></b> [Source Code](https://github.com/Freika/dawarich))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Geo2tz](https://github.com/noandrea/geo2tz)) - Get the timezone from geo coordinates (lat, lon). `MIT` `Go/Docker`
- 🌎 [GraphHopper](graphhopper.com/) - Fast routing library and server using OpenStreetMap. (<b><code>&nbsp;&nbsp;6181⭐</code></b> <b><code>&nbsp;&nbsp;1856🍴</code></b> [Source Code](https://github.com/graphhopper/graphhopper))) `Apache-2.0` `Java`
- 🌎 [Nominatim](nominatim.org/) - Server application for geocoding (address -> coordinates) and reverse geocoding (coordinates -> address) on OpenStreetMap data. (<b><code>&nbsp;&nbsp;3947⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;789🍴</code></b> [Source Code](https://github.com/osm-search/Nominatim))) `GPL-2.0` `C`
- [Open Source Routing Machine (OSRM)](http://project-osrm.org/) - High performance routing engine designed to run on OpenStreetMap data and offering an HTTP API, C++ library interface, and Nodejs wrapper.  🌎 [Demo](map.project-osrm.org/), <b><code>&nbsp;&nbsp;7357⭐</code></b> <b><code>&nbsp;&nbsp;3829🍴</code></b> [Source Code](https://github.com/Project-OSRM/osrm-backend))) `BSD-2-Clause` `C++`
- 🌎 [OpenRouteService](openrouteservice.org/) - Route service with directions, isochrones, time-distance matrix, route optimization, etc.  🌎 [Demo](openrouteservice.org/dev/#/api-docs/introduction), <b><code>&nbsp;&nbsp;1790⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;460🍴</code></b> [Source Code](https://github.com/GIScience/openrouteservice))) `GPL-3.0` `Docker/Java`
- 🌎 [OpenStreetMap](www.openstreetmap.org/) - Collaborative project to create a free editable map of the world. (<b><code>&nbsp;&nbsp;2599⭐</code></b> <b><code>&nbsp;&nbsp;1020🍴</code></b> [Source Code](https://github.com/openstreetmap/openstreetmap-website)), 🌎 [Clients](wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- 🌎 [OpenTripPlanner](www.opentripplanner.org/) - Multimodal trip planning software based on OpenStreetMap data and consuming published GTFS-formatted data to suggest routes using local public transit systems. (<b><code>&nbsp;&nbsp;2496⭐</code></b> <b><code>&nbsp;&nbsp;1090🍴</code></b> [Source Code](https://github.com/opentripplanner/OpenTripPlanner))) `LGPL-3.0` `Java/Javascript`
- <b><code>&nbsp;&nbsp;1100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [OwnTracks Recorder](https://github.com/owntracks/recorder)) `⚠` - Store and access data published by 🌎 [OwnTracks](owntracks.org/) location tracking apps. `GPL-2.0` `C/Lua/deb/Docker`
- 🌎 [TileServer GL](tileserver.readthedocs.io/) - Vector and raster maps with GL styles. Server side rendering by Mapbox GL Native. Map tile server for Mapbox GL JS, Android, iOS, Leaflet, OpenLayers, GIS via WMTS, etc. (<b><code>&nbsp;&nbsp;2675⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;689🍴</code></b> [Source Code](https://github.com/maptiler/tileserver-gl))) `BSD-2-Clause` `Nodejs/Docker`
- 🌎 [Traccar](www.traccar.org/) - Java application to track GPS positions. Supports loads of tracking devices and protocols, has an Android and iOS App. Has a web interface to view your trips.  🌎 [Demo](demo.traccar.org/), [Source Code](https://github.com/traccar)) `Apache-2.0` `Java`
- <b><code>&nbsp;&nbsp;3174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [wanderer](https://github.com/Flomp/wanderer)) - Trail database where you can upload your recorded tracks or create new ones and add various metadata to build an easily searchable catalogue.  🌎 [Demo](demo.wanderer.to)) `AGPL-3.0` `Docker/Go/Nodejs`


### Media Management

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Digital media](en.wikipedia.org/wiki/Digital_media) management tools and software.

_Related: [Automation](#automation), [Media Streaming](#media-streaming), [Media Streaming - Audio Streaming](#media-streaming---audio-streaming), [Media Streaming - Multimedia Streaming](#media-streaming---multimedia-streaming), [Media Streaming - Video Streaming](#media-streaming---video-streaming)_

- <b><code>&nbsp;&nbsp;&nbsp;274⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [ChannelTube](https://github.com/TheWicklowWolf/ChannelTube)) `⚠` - Download video or audio from YouTube channels on a schedule via yt-dlp. `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;3724⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;604🍴</code></b> [Headphones](https://github.com/rembo10/headphones)) - Automated music downloader for NZB and Torrent, written in Python. It supports SABnzbd, NZBget, Transmission, µTorrent, Deluge and Blackhole. `GPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;7778⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;535🍴</code></b> [Jellyseerr](https://github.com/Fallenbagel/jellyseerr)) - Manage requests for your media library, supports Plex, Jellyfin and Emby media servers (fork of Overseerr). `MIT` `Docker/Nodejs`
- 🌎 [Lidarr](lidarr.audio/) - Music collection manager for Usenet and BitTorrent users. (<b><code>&nbsp;&nbsp;4826⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;320🍴</code></b> [Source Code](https://github.com/Lidarr/Lidarr))) `GPL-3.0` `C#/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;312⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [LidaTube](https://github.com/TheWicklowWolf/LidaTube)) `⚠` - Finding and fetch missing Lidarr albums via yt-dlp. `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;452⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Lidify](https://github.com/TheWicklowWolf/Lidify)) `⚠` - Music discovery tool that provides recommendations based on selected Lidarr artists, using Spotify or LastFM. `MIT` `Docker`
- <b><code>&nbsp;&nbsp;1926⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;277🍴</code></b> [Medusa](https://github.com/pymedusa/Medusa)) - Automatic Video library manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic. (<b><code>&nbsp;&nbsp;2563⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;912🍴</code></b> [Clients](https://github.com/medusajs/nextjs-starter-medusa))) `GPL-3.0` `Python`
- <b><code>&nbsp;11238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;757🍴</code></b> [MeTube](https://github.com/alexta69/metube)) - Web GUI for youtube-dl, with playlist support. Allows downloading videos from dozens of websites. `AGPL-3.0` `Python/Nodejs/Docker`
- 🌎 [nefarious](lardbit.github.io/nefarious/) - Automate downloading Movies and TV Shows. (<b><code>&nbsp;&nbsp;1206⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Source Code](https://github.com/lardbit/nefarious))) `GPL-3.0` `Python`
- 🌎 [Ombi](ombi.io/) - Content request system for Plex/Emby, connects to SickRage, CouchPotato, Sonarr, with a growing feature set.  🌎 [Demo](app.ombi.io/), <b><code>&nbsp;&nbsp;4019⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;411🍴</code></b> [Source Code](https://github.com/Ombi-app/Ombi))) `GPL-2.0` `C#/deb`
- 🌎 [Overseerr](overseerr.dev/) `⚠` - Manage requests for your media library. It integrates with your existing services, such as Sonarr, Radarr, and Plex!. (<b><code>&nbsp;&nbsp;4954⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;582🍴</code></b> [Source Code](https://github.com/sct/overseerr))) `MIT` `Docker`
- <b><code>&nbsp;&nbsp;4349⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [Pinchflat](https://github.com/kieraneglin/pinchflat)) `⚠` - Download YouTube content built using yt-dlp. `AGPL-3.0` `Docker`
- 🌎 [PodFetch](samtv12345.github.io/PodFetch) - Sleek and efficient podcast downloader. (<b><code>&nbsp;&nbsp;&nbsp;451⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Source Code](https://github.com/SamTV12345/PodFetch))) `Apache-2.0` `Docker/Rust`
- 🌎 [Radarr](radarr.video/) - Automatically download movies via Usenet and BitTorrent (fork of Sonarr). (<b><code>&nbsp;12709⭐</code></b> <b><code>&nbsp;&nbsp;1108🍴</code></b> [Source Code](https://github.com/Radarr/Radarr))) `GPL-3.0` `C#/Docker`
- 🌎 [Reaparr](www.reaparr.rocks/) `⚠` - Cross-platform Plex media downloader that seamlessly adds media from other Plex servers to your own. (<b><code>&nbsp;&nbsp;&nbsp;583⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Source Code](https://github.com/Reaparr/Reaparr))) `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;2072⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [Reiverr](https://github.com/aleksilassila/reiverr)) `⚠` - Clean combined interface for Jellyfin, TMDB, Radarr and Sonarr, as well as a replacement to Overseerr. `AGPL-3.0` `Docker`
- 🌎 [Sonarr](sonarr.tv/) - Automatic TV Shows downloader and manager for Usenet and BitTorrent. It can grab, sort and rename new episodes and automatically upgrade the quality of files already downloaded when a better quality format becomes available. (<b><code>&nbsp;12909⭐</code></b> <b><code>&nbsp;&nbsp;1717🍴</code></b> [Source Code](https://github.com/Sonarr/Sonarr))) `GPL-3.0` `C#/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;676⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Spooty](https://github.com/Raiper34/spooty)) `⚠` - Download tracks/playlists/albums from Spotify. It can also subscribe to a playlist or author page and download new songs upon release. `MIT` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;2544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;145🍴</code></b> [tubesync](https://github.com/meeb/tubesync)) `⚠` - Syncs YouTube channels and playlists to a locally hosted media server. `AGPL-3.0` `Docker/Python`
- <b><code>&nbsp;&nbsp;1154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Watcharr](https://github.com/sbondCo/Watcharr)) - Add and track all the shows and movies you are watching. Comes with user authentication, modern and clean UI and a very simple setup.  🌎 [Demo](beta.watcharr.app/)) `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [ydl_api_ng](https://github.com/Totonyus/ydl_api_ng)) - Simple youtube-dl REST API to launch downloads on a distant server. `GPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;302⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [YoutubeDL-Server](https://github.com/nbr23/youtube-dl-server)) - Web and REST interface to Youtube-DL for downloading videos onto a server. `MIT` `Python/Docker`
- <b><code>&nbsp;&nbsp;2254⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;212🍴</code></b> [yt-dlp Web UI](https://github.com/marcopiovanello/yt-dlp-web-ui)) - Web GUI for yt-dlp. `MPL-2.0` `Docker/Go/Nodejs`


### Media Streaming

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Streaming media](en.wikipedia.org/wiki/Streaming_media) is multimedia that is delivered and consumed in a continuous manner from a source, with little or no intermediate storage in network elements.

**Please visit [Media streaming - Audio Streaming](#media-streaming---audio-streaming), [Media streaming - Multimedia Streaming](#media-streaming---multimedia-streaming), [Media streaming - Video Streaming](#media-streaming---video-streaming), [Media Management](#media-management)**

_See also: 🌎 [List of streaming media systems - Wikipedia](en.wikipedia.org/wiki/List_of_streaming_media_systems), 🌎 [Comparison of streaming media systems - Wikipedia](en.wikipedia.org/wiki/Comparison_of_streaming_media_systems)_



### Media Streaming - Audio Streaming

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Audio](en.wikipedia.org/wiki/Audio) streaming tools and software.

_Related: [Media Management](#media-management)_

- 🌎 [Ampache](ampache.org/) - Web based audio/video streaming application.  🌎 [Demo](play.dogmazic.net/), <b><code>&nbsp;&nbsp;3743⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;606🍴</code></b> [Source Code](https://github.com/ampache/ampache))) `AGPL-3.0` `PHP`
- 🌎 [Audiobookshelf](www.audiobookshelf.org/) - Audiobook and podcast server. It streams all audio formats, keeps and syncs progress across devices. Comes with open-source apps for Android and iOS. (<b><code>&nbsp;11106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;808🍴</code></b> [Source Code](https://github.com/advplyr/audiobookshelf)), <b><code>&nbsp;&nbsp;2193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;288🍴</code></b> [Clients](https://github.com/advplyr/audiobookshelf-app))) `GPL-3.0` `Docker/deb/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;803⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Audioserve](https://github.com/izderadicka/audioserve)) - Simple personal server to serve audio files from directories (audiobooks, music, podcasts...). Focused on simplicity and supports sync of play position between clients. `MIT` `Rust`
- 🌎 [AzuraCast](www.azuracast.com/) - Modern and accessible web radio management suite. (<b><code>&nbsp;&nbsp;3658⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;689🍴</code></b> [Source Code](https://github.com/AzuraCast/AzuraCast))) `Apache-2.0` `Docker`
- 🌎 [Beets](beets.io/) - Music library manager and MusicBrainz tagger (command-line and Web interface). (<b><code>&nbsp;14462⭐</code></b> <b><code>&nbsp;&nbsp;1960🍴</code></b> [Source Code](https://github.com/beetbox/beets))) `MIT` `Python/deb`
- <b><code>&nbsp;&nbsp;4035⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;207🍴</code></b> [Black Candy](https://github.com/blackcandy-org/blackcandy)) - Music streaming server. `MIT` `Docker/Ruby`
- 🌎 [Funkwhale](dev.funkwhale.audio/funkwhale) - Modern, web-based, convivial, multi-user and free music server. `BSD-3-Clause` `Python/Django`
- <b><code>&nbsp;&nbsp;2159⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [gonic](https://github.com/sentriz/gonic)) - Lightweight music streaming server. Subsonic compatible. `GPL-3.0` `Go/Docker`
- 🌎 [koel](koel.dev/) - Personal music streaming server that works.  🌎 [Demo](demo.koel.dev/), <b><code>&nbsp;16911⭐</code></b> <b><code>&nbsp;&nbsp;2077🍴</code></b> [Source Code](https://github.com/koel/koel))) `MIT` `PHP`
- 🌎 [LibreTime](libretime.org) - Broadcast streaming radio on the web (fork of <b><code>&nbsp;&nbsp;&nbsp;628⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;266🍴</code></b> [Airtime](https://github.com/sourcefabric/Airtime))). (<b><code>&nbsp;&nbsp;&nbsp;900⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;242🍴</code></b> [Source Code](https://github.com/LibreTime/libretime))) `AGPL-3.0` `Docker/PHP`
- <b><code>&nbsp;&nbsp;1513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [LMS](https://github.com/epoupon/lms)) - Access your self-hosted music using a web interface. `GPL-3.0` `Docker/deb/C++`
- 🌎 [Lyrion Music Server](lyrion.org/) - Server software which controls a wide range of Squeezebox/Slim Devices audio players and compatible hardware (formerly Logitech Media Server). (<b><code>&nbsp;&nbsp;1591⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;343🍴</code></b> [Source Code](https://github.com/lms-community/slimserver)), 🌎 [Clients](lyrion.org/extensions/applications/)) `GPL-2.0` `deb/Docker/Perl`
- <b><code>&nbsp;&nbsp;1593⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [Maloja](https://github.com/krateng/maloja)) - Music scrobble database (alternative to Last.fm).  🌎 [Demo](maloja.krateng.ch/)) `GPL-3.0` `Python/Docker`
- 🌎 [moOde Audio](moodeaudio.org/) - Audiophile-quality music playback for the wonderful Raspberry Pi family of single board computers. (<b><code>&nbsp;&nbsp;1233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [Source Code](https://github.com/moode-player/moode))) `GPL-3.0` `PHP`
- 🌎 [Mopidy](docs.mopidy.com/) `⚠` - Extensible music server. Offers a superset of the mpd API, as well as integration with 3rd party services like Spotify, SoundCloud etc. (<b><code>&nbsp;&nbsp;8415⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;700🍴</code></b> [Source Code](https://github.com/mopidy/mopidy))) `Apache-2.0` `Python/deb`
- 🌎 [mpd](www.musicpd.org/) - Daemon to remotely play music, stream music, handle and organize playlists. Many clients available. (<b><code>&nbsp;&nbsp;2557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;385🍴</code></b> [Source Code](https://github.com/MusicPlayerDaemon/MPD)), 🌎 [Clients](www.musicpd.org/clients/)) `GPL-2.0` `C++`
- 🌎 [mStream](mstream.io/) - Music streaming server with GUI management tools. Runs on Mac, Windows, and Linux. (<b><code>&nbsp;&nbsp;2313⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [Source Code](https://github.com/IrosTheBeggar/mStream))) `GPL-3.0` `Nodejs`
- 🌎 [multi-scrobbler](foxxmd.github.io/multi-scrobbler) - Scrobble plays from multiple sources to multiple scrobbling services. (<b><code>&nbsp;&nbsp;&nbsp;834⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Source Code](https://github.com/FoxxMD/multi-scrobbler))) `MIT` `Nodejs/Docker`
- 🌎 [musikcube](musikcube.com/) - Streaming audio server with Linux/macOS/Windows/Android clients. (<b><code>&nbsp;&nbsp;4630⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [Source Code](https://github.com/clangen/musikcube))) `BSD-3-Clause` `C++/deb`
- 🌎 [Navidrome Music Server](www.navidrome.org) - Modern Music Server and Streamer, compatible with Subsonic/Airsonic.  🌎 [Demo](www.navidrome.org/demo), <b><code>&nbsp;18147⭐</code></b> <b><code>&nbsp;&nbsp;1300🍴</code></b> [Source Code](https://github.com/navidrome/navidrome)), 🌎 [Clients](www.navidrome.org/docs/overview/#apps)) `GPL-3.0` `Docker/Go`
- 🌎 [Pinepods](www.pinepods.online/) - Podcast management system with multi-user support. Pinepods utilizes a central database so aspects like listen time and themes follow from device to device.  🌎 [Demo](try.pinepods.online), <b><code>&nbsp;&nbsp;&nbsp;751⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Source Code](https://github.com/madeofpendletonwool/PinePods))) `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;2479⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [Polaris](https://github.com/agersant/polaris)) - Music browsing and streaming application optimized for large music collections, ease of use and high performance. `MIT` `Rust/Docker`
- <b><code>&nbsp;&nbsp;7279⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;515🍴</code></b> [Snapcast](https://github.com/badaix/snapcast)) - Synchronous multiroom audio server. `GPL-3.0` `C++/deb`
- <b><code>&nbsp;&nbsp;&nbsp;631⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [Stretto](https://github.com/benkaiser/stretto)) `⚠` - Music player with Youtube/Soundcloud import and iTunes/Spotify discovery.  🌎 [Demo](next.kaiserapps.com), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Clients](https://github.com/benkaiser/stretto-mobile-next))) `MIT` `Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Supysonic](https://github.com/spl0k/supysonic)) - Python implementation of the Subsonic server API. `AGPL-3.0` `Python/deb`
- 🌎 [SwingMusic](swingmusic.vercel.app/) - Swing Music is a beautiful, self-hosted music player and streaming server for your local audio files. Like a cooler Spotify ... but bring your own music. (<b><code>&nbsp;&nbsp;1613⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Source Code](https://github.com/swingmx/swingmusic))) `MIT` `Python/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;337⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [vod2pod-rss](https://github.com/madiele/vod2pod-rss)) `⚠` - Convert YouTube and Twitch channels to podcasts, no storage required. Transcodes VoDs to MP3 192k on the fly, generates an RSS feed to use in podcast clients. `MIT` `Docker`


### Media Streaming - Multimedia Streaming

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Multimedia](en.wikipedia.org/wiki/Multimedia) streaming tools and software.

_Related: [Media Streaming - Video Streaming](#media-streaming---video-streaming), [Media Streaming - Audio Streaming](#media-streaming---audio-streaming), [Media Management](#media-management)_

- 🌎 [ClipBucket](clipbucket.fr/) - Start your own video sharing website (YouTube/Netflix Clone) in a matter of minutes.  🌎 [Demo](demo.clipbucket.oxygenz.fr/), <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [Source Code](https://github.com/MacWarrior/clipbucket-v5))) `AAL` `Docker/PHP`
- <b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [cmyflix](https://github.com/farfalleflickan/cmyflix)) - Minimalist Plex/Jellyfin alternative to stream video. `AGPL-3.0` `C/deb`
- 🌎 [Gerbera](gerbera.io/) - UPnP Media Server, which allows you to stream your digital media throughout your home network and listen to/watch it on a variety of UPnP compatible devices. (<b><code>&nbsp;&nbsp;1321⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;216🍴</code></b> [Source Code](https://github.com/gerbera/gerbera))) `GPL-2.0` `Docker/deb/C++`
- 🌎 [Icecast 2](icecast.org) - Streaming audio/video server which can be used to create an Internet radio station or a privately running jukebox and many things in between.  🌎 [Source Code](gitlab.xiph.org/xiph/icecast-server), 🌎 [Clients](icecast.org/apps/)) `GPL-2.0` `C`
- 🌎 [Jellyfin](jellyfin.org) - Media server for audio, video, books, comics, and photos with a sleek interface and robust transcoding capabilities. Almost all modern platforms have clients, including Roku, Android TV, iOS, and Kodi.  🌎 [Demo](demo.jellyfin.org/stable), <b><code>&nbsp;46919⭐</code></b> <b><code>&nbsp;&nbsp;4243🍴</code></b> [Source Code](https://github.com/jellyfin/jellyfin)), <b><code>&nbsp;&nbsp;5692⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [Clients](https://github.com/awesome-jellyfin/awesome-jellyfin))) `GPL-2.0` `C#/deb/Docker`
- 🌎 [Karaoke Eternal](www.karaoke-eternal.com) - Host awesome karaoke parties where everyone can easily find and queue songs from their phone's browser. The player is also fully browser-based with support for MP3+G, MP4 and WebGL visualizations.  🌎 [Source Code](www.karaoke-eternal.com/repo)) `ISC` `Docker/Nodejs`
- 🌎 [Kodi](kodi.tv/) - Multimedia/Entertainment center, formerly known as XBMC. Runs on Android, BSD, Linux, macOS, iOS and Windows. (<b><code>&nbsp;20222⭐</code></b> <b><code>&nbsp;&nbsp;6470🍴</code></b> [Source Code](https://github.com/xbmc/xbmc))) `GPL-2.0` `C++/deb`
- <b><code>&nbsp;&nbsp;2262⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [Kyoo](https://github.com/zoriya/kyoo)) - Innovative media browser designed for seamless streaming of anime, series and movies, offering advanced features like dynamic transcoding, auto watch history and intelligent metadata retrieval.  🌎 [Demo](kyoo.zoriya.dev)) `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;1015⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Meelo](https://github.com/Arthi-chaud/Meelo)) - Personal Music Server, designed for collectors and music maniacs. `GPL-3.0` `Docker`
- 🌎 [MistServer](mistserver.org/) - Public domain streaming media server that works with any device and any format. (<b><code>&nbsp;&nbsp;&nbsp;467⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [Source Code](https://github.com/DDVTECH/mistserver))) `Unlicense` `C++`
- [NymphCast](http://nyanko.ws/nymphcast.php) - Turn your choice of Linux-capable hardware into an audio and video source for a television or powered speakers (alternative to Chromecast). (<b><code>&nbsp;&nbsp;2524⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [Source Code](https://github.com/MayaPosch/NymphCast))) `BSD-3-Clause` `C++`
- 🌎 [Rygel](gnome.pages.gitlab.gnome.org/rygel/) - UPnP AV MediaServer that allows you to easily share audio, video, and pictures. Media player software may use Rygel to become a MediaRenderer that may be controlled remotely by a UPnP or DLNA Controller.  🌎 [Source Code](gitlab.gnome.org/GNOME/rygel/)) `LGPL-2.1` `C`
- 🌎 [Stash](stashapp.cc) - A web-based library organizer and player for your adult media stash, with auto-tagging and metadata scraping support. (<b><code>&nbsp;11537⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;952🍴</code></b> [Source Code](https://github.com/stashapp/stash))) `AGPL-3.0` `Docker/Go`
- <b><code>&nbsp;&nbsp;1927⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;268🍴</code></b> [µStreamer](https://github.com/pikvm/ustreamer)) - Lightweight and very quick server to stream MJPEG video from any V4L2 device to the net. `GPL-3.0` `C/deb`
- 🌎 [üWave](u-wave.net/) `⚠` - Self-hosted collaborative listening platform. Users take turns playing media—songs, talks, gameplay videos, or anything else—from a variety of media sources like YouTube and SoundCloud.  🌎 [Demo](wlk.yt/), [Source Code](https://github.com/u-wave)) `MIT` `Nodejs`


### Media Streaming - Video Streaming

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Video](en.wikipedia.org/wiki/Video) streaming tools and software.

_Related: [Video Surveillance](#video-surveillance), [Media Streaming - Multimedia Streaming](#media-streaming---multimedia-streaming), [Photo Galleries](#photo-galleries), [Media Management](#media-management)_

- <b><code>&nbsp;&nbsp;1546⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;236🍴</code></b> [CyTube](https://github.com/calzoneman/sync)) - Synchronize media, chat, and more for an arbitrary number of channels.  🌎 [Demo](cytu.be)) `MIT` `Nodejs`
- <b><code>&nbsp;18312⭐</code></b> <b><code>&nbsp;&nbsp;2062🍴</code></b> [Invidious](https://github.com/iv-org/invidious)) `⚠` - Alternative YouTube front-end.  🌎 [Demo](docs.invidious.io/instances/)) `AGPL-3.0` `Docker/Crystal`
- 🌎 [MediaCMS](mediacms.io) - Modern, fully featured open source video and media CMS, written in Python/Django/React, featuring a REST API. (<b><code>&nbsp;&nbsp;4545⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;849🍴</code></b> [Source Code](https://github.com/mediacms-io/mediacms))) `AGPL-3.0` `Python/Docker`
- <b><code>&nbsp;&nbsp;2999⭐</code></b> <b><code>&nbsp;&nbsp;1101🍴</code></b> [OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)) - Streaming Server with Sub-Second Latency.  🌎 [Demo](demo.ovenplayer.com)) `AGPL-3.0` `C++/Docker`
- 🌎 [Owncast](owncast.online/) - Decentralized single-user live video streaming and chat server for running your own live streams similar in style to the large mainstream options. (<b><code>&nbsp;10760⭐</code></b> <b><code>&nbsp;&nbsp;1161🍴</code></b> [Source Code](https://github.com/owncast/owncast))) `MIT` `Go`
- 🌎 [PeerTube](joinpeertube.org/en/) - Decentralized video streaming platform using P2P (BitTorrent) directly in the web browser. (<b><code>&nbsp;14381⭐</code></b> <b><code>&nbsp;&nbsp;1652🍴</code></b> [Source Code](https://github.com/Chocobozzz/PeerTube))) `AGPL-3.0` `Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Rapidbay](https://github.com/hauxir/rapidbay/)) - Videostreaming service/torrent client that allows searching and playing videos from torrents in the browser or from a Chromecast/AppleTV/Smart TV. `MIT` `Python/Docker`
- 🌎 [Restreamer](datarhei.github.io/restreamer/) - Access H.264 real-time video streaming on your website without a streaming provider. (<b><code>&nbsp;&nbsp;4758⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;514🍴</code></b> [Source Code](https://github.com/datarhei/restreamer))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [SRS](ossrs.io/) - A simple, high efficiency and real-time video server, supports RTMP, WebRTC, HLS, HTTP-FLV and SRT. (<b><code>&nbsp;28252⭐</code></b> <b><code>&nbsp;&nbsp;5631🍴</code></b> [Source Code](https://github.com/ossrs/srs))) `MIT` `Docker/C++`
- <b><code>&nbsp;&nbsp;&nbsp;344⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [SyncTube](https://github.com/RblSb/SyncTube)) - Lightweight and very simple to setup CyTube alternative to watch videos with friends and chat. `MIT` `Nodejs/Haxe`
- 🌎 [Tube Archivist](tubearchivist.com/) `⚠` - Organize, search, and enjoy your YouTube collection. Subscribe, download, and track viewed content with metadata indexing and a user-friendly interface. (<b><code>&nbsp;&nbsp;7339⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;344🍴</code></b> [Source Code](https://github.com/tubearchivist/tubearchivist)), 🌎 [Clients](docs.tubearchivist.com/faq/#how-do-i-import-my-videos-to-emby-plex-jellyfin-kodi)) `GPL-3.0` `Docker`
- 🌎 [Tube](git.mills.io/prologic/tube) - Youtube-like (_without censorship and features you don't need!_) video sharing app written in Go which also supports automatic transcoding to MP4 H.265 AAC, multiple collections and RSS feed.  🌎 [Demo](tube.mills.io)) `MIT` `Go`
- 🌎 [VideoLAN Client (VLC)](www.videolan.org/) - Cross-platform multimedia player client and server supporting most multimedia files as well as DVDs, Audio CDs, VCDs, and various streaming protocols.  🌎 [Source Code](code.videolan.org/videolan/vlc)) `GPL-2.0` `C/deb`


### Miscellaneous

**[`^        back to top        ^`](#awesome-selfhosted)**

Software that does not fit in another section.

- <b><code>&nbsp;&nbsp;3622⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;256🍴</code></b> [2FAuth](https://github.com/Bubka/2FAuth)) - Manage your Two-Factor Authentication (2FA) accounts and generate their security codes.  🌎 [Demo](demo.2fauth.app/)) `AGPL-3.0` `PHP/Docker`
- 🌎 [Anchr](anchr.io) - Toolbox for tiny tasks on the internet, including bookmark collections, URL shortening and (encrypted) image uploads. (<b><code>&nbsp;&nbsp;&nbsp;357⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Source Code](https://github.com/muety/anchr))) `GPL-3.0` `Nodejs`
- 🌎 [Anubis](anubis.techaro.lol/) - Web AI firewall utility which protects upstream resources from scraper bots. (<b><code>&nbsp;15744⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;464🍴</code></b> [Source Code](https://github.com/TecharoHQ/anubis))) `MIT` `Docker/deb/Go`
- 🌎 [asciinema](asciinema.org/) - Web app for hosting asciicasts.  🌎 [Demo](asciinema.org/explore), <b><code>&nbsp;&nbsp;2427⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;281🍴</code></b> [Source Code](https://github.com/asciinema/asciinema-server))) `Apache-2.0` `Elixir/Docker`
- <b><code>&nbsp;&nbsp;2607⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;318🍴</code></b> [Baby Buddy](https://github.com/babybuddy/babybuddy)) - Helps caregivers track baby sleep, feedings, diaper changes, and tummy time. (<b><code>&nbsp;&nbsp;2607⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;318🍴</code></b> [Demo](https://github.com/babybuddy/babybuddy#-demo))) `BSD-2-Clause` `Python`
- 🌎 [beelzebub](beelzebub-honeypot.com/) `⚠` - Honeypot framework designed to provide a highly secure environment for detecting and analyzing cyber attacks. (<b><code>&nbsp;&nbsp;1772⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;164🍴</code></b> [Source Code](https://github.com/mariocandela/beelzebub))) `MIT` `Docker/K8S/Go`
- 🌎 [Canary Tokens](canarytokens.org) - Generates lightweight, embedded honeypot triggers called canary tokens for detecting unauthorized access. (<b><code>&nbsp;&nbsp;2717⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;393🍴</code></b> [Source Code](https://github.com/thinkst/opencanary))) `BSD-3-Clause` `Docker/Python`
- <b><code>&nbsp;&nbsp;1304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [ClipCascade](https://github.com/Sathvik-Rao/ClipCascade)) - Syncs your clipboard across multiple devices instantly, without any button press. Available on Windows, macOS, Linux, and Android, it provides seamless and secure clipboard sharing with end-to-end data encryption. `GPL-3.0` `Java/Docker`
- 🌎 [Cloudlog](magicbug.co.uk/cloudlog/) - Log your amateur radio contacts anywhere. (<b><code>&nbsp;&nbsp;&nbsp;537⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;199🍴</code></b> [Source Code](https://github.com/magicbug/cloudlog))) `MIT` `PHP/Docker`
- <b><code>&nbsp;13054⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;672🍴</code></b> [ConvertX](https://github.com/C4illin/ConvertX)) - Online file converter which supports over a thousand different formats. `AGPL-3.0` `Docker`
- 🌎 [CUPS](www.cups.org/) - The Common Unix Print System uses Internet Printing Protocol (IPP) to support printing to local and network printers. (<b><code>&nbsp;&nbsp;1456⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;262🍴</code></b> [Source Code](https://github.com/OpenPrinting/cups))) `GPL-2.0` `C`
- <b><code>&nbsp;33557⭐</code></b> <b><code>&nbsp;&nbsp;3788🍴</code></b> [CyberChef](https://github.com/gchq/CyberChef)) - Perform all manner of operations within a web browser such as AES, DES and Blowfish encryption and decryption, creating hexdumps, calculating hashes, and much more.  🌎 [Demo](gchq.github.io/CyberChef)) `Apache-2.0` `Javascript`
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
- <b><code>&nbsp;&nbsp;&nbsp;878⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [DOCAT](https://github.com/docat-org/docat)) - Host your docs. Simple. Versioned. Fancy. `MIT` `Python/Docker`
- 🌎 [Domain Locker](domain-locker.com) - Domain name portfolio management and tracker.  🌎 [Demo](demo.domain-locker.com), <b><code>&nbsp;&nbsp;1026⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [Source Code](https://github.com/lissy93/domain-locker))) `MIT` `Deno/Docker`
- 🌎 [DOMJudge](www.domjudge.org/) - System for running a programming contest, like the ICPC regional and world championship programming contests.  🌎 [Demo](www.domjudge.org/demo), <b><code>&nbsp;&nbsp;&nbsp;847⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;279🍴</code></b> [Source Code](https://github.com/DOMjudge/domjudge))) `GPL-2.0/BSD-3-Clause/MIT` `PHP`
- 🌎 [ESMira](esmira.kl.ac.at) - Run longitudinal studies (ESM, AA, EMA) with data collection and communication with participants being completely anonymous.  🌎 [Demo](demo-esmira.kl.ac.at/#admin,username:demo,password:demodemodemo), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/KL-Psychological-Methodology/ESMira))) `AGPL-3.0` `PHP`
- 🌎 [F-Droid](f-droid.org) - Server tools for maintaining an F-Droid repository system.  🌎 [Source Code](gitlab.com/fdroid/fdroidserver)) `AGPL-3.0` `Python/Docker/deb`
- 🌎 [Flyimg](flyimg.io) - Resize and crop images on the fly. Get optimised images with MozJPEG, WebP or PNG using ImageMagick, with an efficient caching system.  🌎 [Demo](demo.flyimg.io), <b><code>&nbsp;&nbsp;1167⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [Source Code](https://github.com/flyimg/flyimg))) `MIT` `Docker`
- 🌎 [Geeftlist](codeberg.org/nanawel/geeftlist) - Collaborative platform for managing, sharing and reserving gifts between friends and family. `GPL-3.0` `Docker`
- <b><code>&nbsp;12768⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;439🍴</code></b> [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper)) `⚠` - Hassle-Free Way to Self-Host Google Fonts. Get eot, ttf, svg, woff and woff2 files + CSS snippets.  🌎 [Demo](gwfh.mranftl.com/fonts)) `MIT` `Nodejs`
- 🌎 [Habitica](habitica.com/) - Habit tracker app which treats your goals like a Role Playing Game. (<b><code>&nbsp;13558⭐</code></b> <b><code>&nbsp;&nbsp;4376🍴</code></b> [Source Code](https://github.com/HabitRPG/habitica))) `GPL-3.0/CC-BY-SA-3.0` `Nodejs/Docker`
- 🌎 [HortusFox](hortusfox.github.io) - Collaborative plant management and tracking system for plant enthusiasts. (<b><code>&nbsp;&nbsp;1277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [Source Code](https://github.com/danielbrendel/hortusfox-web))) `MIT` `PHP/Docker`
- <b><code>&nbsp;&nbsp;4661⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;195🍴</code></b> [iSponsorBlockTV](https://github.com/dmunozv04/iSponsorBlockTV)) `⚠` - Block and skip sponsors, while also muting and skipping ads on YouTube. `GPL-3.0` `Docker/Python`
- <b><code>&nbsp;&nbsp;&nbsp;939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [IT-Tools by sharevb](https://github.com/sharevb/it-tools)) - Collection of handy online tools for developers (fork of <b><code>&nbsp;35812⭐</code></b> <b><code>&nbsp;&nbsp;4442🍴</code></b> [it-tools](https://github.com/CorentinTh/it-tools))).  🌎 [Demo](sharevb-it-tools.vercel.app/)) `GPL-3.0` `Docker`
- 🌎 [Jelu](bayang.github.io/jelu-web) - Read and to-read list book tracker. (<b><code>&nbsp;&nbsp;&nbsp;619⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Source Code](https://github.com/bayang/jelu))) `MIT` `Java/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [jetlog](https://github.com/pbogre/jetlog)) - Personal flight tracker and viewer. `GPL-2.0` `Docker`
- 🌎 [Kasm Workspaces](kasmweb.com/) - Streaming containerized apps and desktops to end-users. Examples include Ubuntu in your browser, or simply single apps such as Chrome, OpenOffice, Gimp, Filezilla etc.  🌎 [Demo](www.kasmweb.com/#demo), [Source Code](https://github.com/kasmtech)) `GPL-3.0` `Docker`
- 🌎 [Koillection](koillection.github.io/) - Koillection is a service allowing users to manage any kind of collections. (<b><code>&nbsp;&nbsp;1044⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Source Code](https://github.com/benjaminjonard/koillection))) `MIT` `Docker/PHP`
- 🌎 [LanguageTool](languagetool.org/) - Proofread more than 20 languages. It finds many errors that a simple spell checker cannot detect. (<b><code>&nbsp;13886⭐</code></b> <b><code>&nbsp;&nbsp;1469🍴</code></b> [Source Code](https://github.com/languagetool-org/languagetool)), 🌎 [Clients](languagetool.org/insights/post/product-windows-app/)) `LGPL-2.1` `Java/Docker`
- 🌎 [Libre Translate](libretranslate.com/) - Machine Translation API. (<b><code>&nbsp;13373⭐</code></b> <b><code>&nbsp;&nbsp;1385🍴</code></b> [Source Code](https://github.com/LibreTranslate/LibreTranslate))) `AGPL-3.0` `Docker/Python`
- 🌎 [LubeLogger](lubelogger.com) - Web-based vehicle maintenance and fuel mileage tracker. (<b><code>&nbsp;&nbsp;2130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [Demo](https://github.com/hargata/lubelog?tab=readme-ov-file#demo)), <b><code>&nbsp;&nbsp;2130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [Source Code](https://github.com/hargata/lubelog))) `MIT` `Docker/K8S/C#`
- 🌎 [mosparo](mosparo.io/) - The modern spam protection tool. It replaces other captcha methods with a simple and easy to use spam protection solution. (<b><code>&nbsp;&nbsp;&nbsp;260⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Source Code](https://github.com/mosparo/mosparo))) `MIT` `PHP`
- 🌎 [MyIP](ipcheck.ing) `⚠` - All in one IP Toolbox. Easy to check what's your IPs, IP geolocation, check for DNS leaks, examine WebRTC connections, speed test, ping test, MTR test, check website availability and more.  🌎 [Demo](ipcheck.ing), <b><code>&nbsp;&nbsp;9543⭐</code></b> <b><code>&nbsp;&nbsp;1045🍴</code></b> [Source Code](https://github.com/jason5ng32/MyIP))) `MIT` `Nodejs/Docker`
- 🌎 [MySpeed](myspeed.dev/) - Speed test analysis software that shows your internet speed for up to 30 days. (<b><code>&nbsp;&nbsp;2286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [Source Code](https://github.com/gnmyt/myspeed))) `MIT` `Docker/Nodejs`
- 🌎 [Neko](neko.m1k1o.net) - Virtual browser that runs in docker and uses WebRTC. (<b><code>&nbsp;16377⭐</code></b> <b><code>&nbsp;&nbsp;1107🍴</code></b> [Source Code](https://github.com/m1k1o/neko))) `Apache-2.0` `Docker/Go`
- 🌎 [OmniTools](omnitools.app/) - Collection of powerful web-based tools for everyday tasks (coding, manipulating images/videos, PDFs or crunching numbers...). (<b><code>&nbsp;&nbsp;7935⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;480🍴</code></b> [Source Code](https://github.com/iib0011/omni-tools))) `MIT` `Docker`
- 🌎 [Open-Meteo](open-meteo.com/) - Weather API with open-data forecasts, historical and climate data from all major national weather services.  🌎 [Demo](open-meteo.com/en/docs), <b><code>&nbsp;&nbsp;3981⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;278🍴</code></b> [Source Code](https://github.com/open-meteo/open-meteo))) `AGPL-3.0` `Docker`
- 🌎 [OpenReader WebUI](openreader.richardr.dev/) - EPUB, PDF, DOCX, MD, and TXT file text to speech document reader. Read documents in realtime with high-quality TTS; or extract audiobooks.  🌎 [Demo](openreader.richardr.dev/), <b><code>&nbsp;&nbsp;&nbsp;250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Source Code](https://github.com/richardr1126/OpenReader-WebUI))) `MIT` `Docker`
- 🌎 [OpenZiti](openziti.io/) - Fully-featured, zero trust, full mesh overlay network. Includes a 2FA support out of the box, clients for all major desktop/mobile OS'es. (<b><code>&nbsp;&nbsp;3774⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;229🍴</code></b> [Source Code](https://github.com/openziti/ziti))) `Apache-2.0` `Go`
- 🌎 [Operational.co](operational.co) - Receive alerts in a live timeline from your product.  🌎 [Demo](app.operational.co/?signinas=kevin), <b><code>&nbsp;&nbsp;&nbsp;418⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Source Code](https://github.com/operational-co/operational.co))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [penpot](penpot.app/) - Web-based design and prototyping platform meant for cross-domain teams. (<b><code>&nbsp;43486⭐</code></b> <b><code>&nbsp;&nbsp;2395🍴</code></b> [Source Code](https://github.com/penpot/penpot))) `MPL-2.0` `Docker`
- 🌎 [POMjs](password.oppetmoln.se/) - Random password generator. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Source Code](https://github.com/joho1968/POMjs))) `GPL-2.0` `Javascript`
- 🌎 [Reactive Resume](rxresu.me/) - One-of-a-kind resume builder that keeps your privacy in mind. Completely secure, customizable, portable, open-source and free forever.  🌎 [Demo](rxresu.me/app/dashboard/), <b><code>&nbsp;34205⭐</code></b> <b><code>&nbsp;&nbsp;3744🍴</code></b> [Source Code](https://github.com/AmruthPillai/Reactive-Resume))) `MIT` `Docker/Nodejs`
- 🌎 [revealjs](revealjs.com) - Framework for easily creating beautiful presentations using HTML.  🌎 [Demo](revealjs.com/), <b><code>&nbsp;70299⭐</code></b> <b><code>&nbsp;16813🍴</code></b> [Source Code](https://github.com/hakimel/reveal.js))) `MIT` `Javascript`
- 🌎 [Revive Adserver](www.revive-adserver.com/) - Ad serving system. Formerly known as OpenX Adserver and phpAdsNew. (<b><code>&nbsp;&nbsp;1408⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;589🍴</code></b> [Source Code](https://github.com/revive-adserver/revive-adserver))) `GPL-2.0` `PHP`
- [SANE Network Scanning](http://sane-project.org/) - Allow remote clients to access image acquisition devices (scanners) available on the local host. ([Source Code](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- 🌎 [Speed Test by OpenSpeedTest™](openspeedtest.com/) - Free & Open-Source HTML5 Network Performance Estimation Tool. (<b><code>&nbsp;&nbsp;3264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [Source Code](https://github.com/openspeedtest/Speed-Test))) `MIT` `Docker`
- 🌎 [Speedtest Tracker](docs.speedtest-tracker.dev/) - Monitor the performance and uptime of your internet connection. (<b><code>&nbsp;&nbsp;4966⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;195🍴</code></b> [Source Code](https://github.com/alexjustesen/speedtest-tracker))) `MIT` `Docker/K8S`
- 🌎 [string.is](string.is/) - An open-source, privacy-friendly online string toolkit for developers. (<b><code>&nbsp;&nbsp;&nbsp;292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Source Code](https://github.com/recurser/string-is))) `AGPL-3.0` `Nodejs`
- 🌎 [Teleport](goteleport.com/) - Certificate authority and access plane for SSH, Kubernetes, web applications, and databases. (<b><code>&nbsp;19565⭐</code></b> <b><code>&nbsp;&nbsp;1966🍴</code></b> [Source Code](https://github.com/gravitational/teleport))) `Apache-2.0` `Go/Docker/K8S`
- <b><code>&nbsp;&nbsp;7442⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;891🍴</code></b> [TeslaMate](https://github.com/teslamate-org/teslamate)) - A powerful data logger for Tesla vehicles. `MIT` `Elixir/Docker`
- <b><code>&nbsp;&nbsp;4356⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [Upsnap](https://github.com/seriousm4x/UpSnap)) - A simple Wake on LAN (WOL) dashboard app. Wake up devices on your network and see current status. `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;234⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [URL-to-PNG](https://github.com/jasonraimondi/url-to-png)) - URL to PNG utility featuring parallel rendering using Playwright for screenshots and with storage caching via Local, S3, or CouchDB. `MIT` `Nodejs/Docker`
- 🌎 [Usertour](www.usertour.io/) - User onboarding platform allowing you to create in-app product tours, checklists, and surveys in minutes effortlessly. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/usertour/usertour/))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Wakupator](https://github.com/Gibus21250/Wakupator)) - Wake On LAN Machine Manager based on network traffic. `MIT` `C`
- 🌎 [Warracker](warracker.com) - Warranty tracker that lets you monitor expiry dates, upload receipts/files, and get alerts before warranties expire. (<b><code>&nbsp;&nbsp;1186⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Source Code](https://github.com/sassanix/Warracker))) `AGPL-3.0` `Docker`
- 🌎 [Wavelog](www.wavelog.org) - Webbased Logging Software for Radio Amateurs. Enhanced QSO logging, statistics and maps for your browser.  🌎 [Demo](demo.wavelog.org), <b><code>&nbsp;&nbsp;&nbsp;366⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [Source Code](https://github.com/wavelog/wavelog))) `MIT` `PHP/Docker`
- 🌎 [WeeWX](weewx.com/) - Open source software for your weather station.  🌎 [Demo](weewx.com/showcase.html), <b><code>&nbsp;&nbsp;1121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [Source Code](https://github.com/weewx/weewx))) `GPL-3.0` `Python/deb`
- 🌎 [WeTTY](butlerx.github.io/wetty/#/) - Terminal in browser over http/https. (<b><code>&nbsp;&nbsp;5058⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;739🍴</code></b> [Source Code](https://github.com/butlerx/wetty))) `MIT` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;1720⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [Yamtrack](https://github.com/FuzzyGrim/Yamtrack)) `⚠` - Media tracker for movies, tv shows, anime, manga, video games and books. (<b><code>&nbsp;&nbsp;1720⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [Demo](https://github.com/FuzzyGrim/Yamtrack?tab=readme-ov-file#demo))) `AGPL-3.0` `Docker/Python`
- 🌎 [Zero-TOTP](zero-totp.com) - Complete, reliable, secure and zero-trust webapp based on zero-knowledge encryption to store your TOTP codes. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Source Code](https://github.com/SeaweedbrainCY/zero-totp))) `GPL-3.0` `Docker`


### Money, Budgeting & Management

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Money management](en.wikipedia.org/wiki/Money_management) and budgeting software.

_Related: [Inventory Management](#inventory-management), [Resource Planning](#resource-planning)_

- 🌎 [Actual](actualbudget.org) - Local-first personal finance tool based on zero-sum budgeting, supporting synchronization across devices, custom rules, manual transaction importing (from QIF, OFX, and QFX files), and optional automatic synchronization with many banks. (<b><code>&nbsp;23819⭐</code></b> <b><code>&nbsp;&nbsp;2013🍴</code></b> [Source Code](https://github.com/actualbudget/actual))) `MIT` `Nodejs/Docker`
- 🌎 [Bigcapital](bigcapital.app/) - Financial accounting and inventory management software for small to medium businesses. (<b><code>&nbsp;&nbsp;3443⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;367🍴</code></b> [Source Code](https://github.com/bigcapitalhq/bigcapital))) `AGPL-3.0` `Docker`
- 🌎 [Bitcart](bitcart.ai) - Cryptocurrencies payment processor and development platform.  🌎 [Demo](admin.bitcart.ai), <b><code>&nbsp;&nbsp;&nbsp;862⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [Source Code](https://github.com/bitcart/bitcart))) `MIT` `Docker/Python/Nodejs`
- 🌎 [BTCPay Server](btcpayserver.org/) - Bitcoin and other cryptocurrencies payment processor.  🌎 [Demo](mainnet.demo.btcpayserver.org/), <b><code>&nbsp;&nbsp;7294⭐</code></b> <b><code>&nbsp;&nbsp;1879🍴</code></b> [Source Code](https://github.com/btcpayserver/btcpayserver))) `MIT` `C#`
- 🌎 [DePay](depay.com) - Accept Web3 Payments directly into your wallet. Peer-to-peer, free, self-hosted & open-source.  🌎 [Demo](depay.com/products/payments), <b><code>&nbsp;&nbsp;&nbsp;121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Source Code](https://github.com/depayfi/widgets))) `MIT` `Nodejs`
- <b><code>&nbsp;&nbsp;1309⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [ExpenseOwl](https://github.com/tanq16/expenseowl)) - Extremely simple expense tracker with a beautiful UI. `MIT` `Go/Docker/K8S`
- 🌎 [ezbookkeeping](ezbookkeeping.mayswind.net/) - A lightweight personal bookkeeping app hosted by yourself.  🌎 [Demo](ezbookkeeping-demo.mayswind.net/), <b><code>&nbsp;&nbsp;3423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;351🍴</code></b> [Source Code](https://github.com/mayswind/ezbookkeeping))) `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Family Accounting Tool](https://github.com/nymanjens/facto)) - Web-based finance management tool for partners with partially shared expenses. `Apache-2.0` `Scala`
- 🌎 [Fava](beancount.github.io/fava/) - Web frontend of Beancount, a text based double-entry accounting system.  🌎 [Demo](fava.pythonanywhere.com/example-with-budgets/income_statement/), <b><code>&nbsp;&nbsp;2291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;330🍴</code></b> [Source Code](https://github.com/beancount/fava))) `MIT` `Python`
- 🌎 [Firefly III](firefly-iii.org/) - Firefly III is a modern financial manager. It helps you to keep track of your money and make budget forecasts. It supports credit cards, has an advanced rule engine and can import data from many banks.  🌎 [Demo](demo.firefly-iii.org/), <b><code>&nbsp;21809⭐</code></b> <b><code>&nbsp;&nbsp;2003🍴</code></b> [Source Code](https://github.com/firefly-iii/firefly-iii))) `AGPL-3.0` `PHP/Docker`
- 🌎 [FOSSBilling](fossbilling.org/) - Hosting and billing automation. Integrates with WHM, CWP, cPanel and HestiaCP. Full API and easily extensible.  🌎 [Demo](fossbilling.org/demo), <b><code>&nbsp;&nbsp;1351⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;286🍴</code></b> [Source Code](https://github.com/FOSSBilling/FOSSBilling))) `Apache-2.0` `PHP/Docker`
- 🌎 [Galette](galette.eu/) - Membership management web application aimed towards non profit organizations. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Source Code](https://github.com/galette/galette))) `GPL-3.0` `PHP`
- 🌎 [Ghostfolio](ghostfol.io/) - Wealth management software to keep track of stocks, ETFs and cryptocurrencies. (<b><code>&nbsp;&nbsp;7103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;860🍴</code></b> [Source Code](https://github.com/ghostfolio/ghostfolio))) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [GRR](grr.devome.com/?lang=en) - Assets management and booking for small/medium companies. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;97⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [Source Code](https://github.com/JeromeDevome/GRR))) `GPL-2.0` `PHP`
- 🌎 [HyperSwitch](hyperswitch.io/) `⚠` - Payment switch to make payments fast, reliable and affordable. Connect with multiple payment processors and route traffic effortlessly, all with a single API integration. (<b><code>&nbsp;39314⭐</code></b> <b><code>&nbsp;&nbsp;4558🍴</code></b> [Source Code](https://github.com/juspay/hyperswitch))) `Apache-2.0` `Docker/Rust`
- 🌎 [IHateMoney](ihatemoney.org/) - Manage your shared expenses, easily.  🌎 [Demo](ihatemoney.org/demo/), <b><code>&nbsp;&nbsp;1334⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;284🍴</code></b> [Source Code](https://github.com/spiral-project/ihatemoney))) `BSD-3-Clause` `Docker/Python`
- 🌎 [InvoicePlane](www.invoiceplane.com/) - Manage quotes, invoices, payments and customers for your small business. (<b><code>&nbsp;&nbsp;2903⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;850🍴</code></b> [Source Code](https://github.com/InvoicePlane/InvoicePlane))) `MIT` `PHP`
- 🌎 [InvoiceShelf](invoiceshelf.com/) - Track expenses, payments & create professional invoices & estimates (fork of Crater). (<b><code>&nbsp;&nbsp;1519⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;315🍴</code></b> [Source Code](https://github.com/InvoiceShelf/InvoiceShelf))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Kill Bill](killbill.io/) - Subscription billing & payments platform. Have access to real-time analytics and financial reports. (<b><code>&nbsp;&nbsp;5264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;882🍴</code></b> [Source Code](https://github.com/killbill/killbill))) `Apache-2.0` `Java/Docker`
- 🌎 [Kresus](kresus.org/) - Personal finance manager.  🌎 [Demo](kresus.org/en/demo.html), <b><code>&nbsp;&nbsp;&nbsp;331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Source Code](https://github.com/kresusapp/kresus))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Lago](www.getlago.com/) - Metering and usage-based billing. (<b><code>&nbsp;&nbsp;8986⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;505🍴</code></b> [Source Code](https://github.com/getlago/lago))) `AGPL-3.0` `Docker`
- 🌎 [Mybucks.online](mybucks.online) - Secure, browser-based, password-only self-custodial cryptocurrency wallet.  🌎 [Demo](app.mybucks.online), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Source Code](https://github.com/mybucks-online/app))) `MIT` `Nodejs`
- 🌎 [MyFin Budget](myfinbudget.com) - Personal finances platform (web + REST API + Android) that'll help you budget, keep track of your income/spending and forecast your financial future. (<b><code>&nbsp;&nbsp;&nbsp;217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Demo](https://github.com/afaneca/myfin?tab=readme-ov-file#demo-account---try-it-for-yourself)), <b><code>&nbsp;&nbsp;&nbsp;217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Source Code](https://github.com/afaneca/myfin)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Clients](https://github.com/afaneca/myfin-api))) `GPL-3.0` `Nodejs/Docker`
- 🌎 [OctoBot](www.octobot.cloud/) - Cryptocurrency trading bot. (<b><code>&nbsp;&nbsp;5045⭐</code></b> <b><code>&nbsp;&nbsp;1026🍴</code></b> [Source Code](https://github.com/Drakkar-Software/OctoBot))) `GPL-3.0` `Python/Docker`
- 🌎 [Ocular](simonwep.github.io/ocular/) - Simplistic and straightforward budgeting app to track your budget across months and years.  🌎 [Demo](ocular.reinisch.io/#demo), <b><code>&nbsp;&nbsp;&nbsp;368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Source Code](https://github.com/simonwep/ocular))) `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;919⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [OpenBudgeteer](https://github.com/TheAxelander/OpenBudgeteer)) - Budgeting app based on the Bucket Budgeting Principle. `AGPL-3.0` `Docker/C#`
- 🌎 [Receipt Wrangler](receiptwrangler.io) `⚠` - Easy-to-use receipt manager, powered by AI. Allows users to create receipts effortlessly and quickly, categorize and more.  🌎 [Demo](demo.receiptwrangler.io), <b><code>&nbsp;&nbsp;&nbsp;179⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Source Code](https://github.com/Receipt-Wrangler/receipt-wrangler-api))) `AGPL-3.0` `Docker`
- 🌎 [REI3](rei3.de/home_en/) - Manage tasks, time, assets and much more within your business.  🌎 [Demo](rei3.de/demo_en/), <b><code>&nbsp;&nbsp;&nbsp;522⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Source Code](https://github.com/r3-team/r3))) `MIT` `Go`
- 🌎 [SHKeeper](shkeeper.io/) - Cryptocurrency payment processor with the unique combination of gateway and merchant allowing you to accept payments in multiple cryptocurrencies without fees and intermediaries. (<b><code>&nbsp;&nbsp;&nbsp;486⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [Demo](https://github.com/vsys-host/shkeeper.io?tab=readme-ov-file#11-demo)), <b><code>&nbsp;&nbsp;&nbsp;486⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [Source Code](https://github.com/vsys-host/shkeeper.io))) `GPL-3.0` `Python`
- 🌎 [SolidInvoice](solidinvoice.co) - Open source invoicing and quote application. (<b><code>&nbsp;&nbsp;&nbsp;836⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [Source Code](https://github.com/SolidInvoice/SolidInvoice))) `MIT` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;409⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [VoucherVault](https://github.com/l4rm4nd/VoucherVault)) - Store and manage vouchers, coupons, loyalty and gift cards digitally. Supports expiry notifications, transaction histories, file uploads and OIDC SSO. `GPL-3.0` `Docker`
- 🌎 [Wallos](wallosapp.com) - Lightweight personal subscription tracker with statistics and optional notifications. (<b><code>&nbsp;&nbsp;6974⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;308🍴</code></b> [Demo](https://github.com/ellite/wallos?tab=readme-ov-file#demo)), <b><code>&nbsp;&nbsp;6974⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;308🍴</code></b> [Source Code](https://github.com/ellite/wallos))) `GPL-3.0` `PHP/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;749⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [WYGIWYH](https://github.com/eitchtee/WYGIWYH)) - Simple and powerful finance tracker.  🌎 [Demo](wygiwyh-demo.herculino.com/)) `AGPL-3.0` `Docker/Django`
- 🌎 [YAFFA](www.yaffa.cc) - Personal finance web application, that can be used to keep track of your money, expenses, budgets, and investments. It also helps with long-term financial planning.  🌎 [Demo](sandbox.yaffa.cc), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Source Code](https://github.com/kantorge/yaffa))) `MIT` `PHP`


### Monitoring

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for 🌎 [monitoring](en.wikipedia.org/wiki/Monitoring#Computing) systems, networks, applications and websites. 

**Please visit <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/Monitoring](https://github.com/awesome-foss/awesome-sysadmin#monitoring)), <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/Metrics and Metric Collection](https://github.com/awesome-foss/awesome-sysadmin#metrics--metric-collection))**



### Note-taking & Editors

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Note taking](en.wikipedia.org/wiki/Note-taking) editors.

_Related: [Wikis](#wikis)_

- 🌎 [Blinko](blinko.space/) - A personal note tool with AI features. (<b><code>&nbsp;&nbsp;7720⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;555🍴</code></b> [Source Code](https://github.com/blinkospace/blinko))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;366⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [DailyTxT](https://github.com/PhiTux/DailyTxT)) - Encrypted diary Web application to save your personal memories of each day. Includes a search function and encrypted file upload. `MIT` `Docker`
- 🌎 [Docs](docs.numerique.gouv.fr/) - Collaborative note taking, wiki and documentation platform that scales. (<b><code>&nbsp;15143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;475🍴</code></b> [Source Code](https://github.com/suitenumerique/docs))) `MIT` `K8S`
- 🌎 [draw.io](draw.io) - Diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams. (<b><code>&nbsp;&nbsp;3181⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;560🍴</code></b> [Source Code](https://github.com/jgraph/drawio))) `Apache-2.0` `Javascript/Docker`
- <b><code>&nbsp;&nbsp;2643⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [flatnotes](https://github.com/dullage/flatnotes)) - Database-less note-taking web app that utilises a flat folder of markdown files for storage.  🌎 [Demo](demo.flatnotes.io)) `MIT` `Docker`
- 🌎 [HedgeDoc](hedgedoc.org/) - Realtime collaborative markdown notes on all platforms, formerly known as CodiMD and HackMD CE.  🌎 [Demo](demo.hedgedoc.org/), <b><code>&nbsp;&nbsp;6796⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;513🍴</code></b> [Source Code](https://github.com/hedgedoc/hedgedoc))) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Joplin](joplinapp.org/) - Note taking application with markdown editor and encryption support for mobile and desktop platforms. Runs client-side and syncs through a self hosted Nextcloud instance or similar (alternative to Evernote). (<b><code>&nbsp;52665⭐</code></b> <b><code>&nbsp;&nbsp;5649🍴</code></b> [Source Code](https://github.com/laurent22/joplin))) `MIT` `Nodejs`
- 🌎 [Livebook](livebook.dev) - Realtime collaborative notebook app based on Markdown that supports running Elixir code snippets, TeX and Mermaid Diagrams. Easily deployed using Docker or Elixir. (<b><code>&nbsp;&nbsp;5644⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;483🍴</code></b> [Source Code](https://github.com/livebook-dev/livebook))) `Apache-2.0` `Elixir/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;880⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Many Notes](https://github.com/brufdev/many-notes)) - Markdown note-taking web application designed for simplicity. `MIT` `Docker`
- 🌎 [Memos](usememos.com/) - Knowledge base that works with a SQLite db file.  🌎 [Demo](demo.usememos.com/explore), <b><code>&nbsp;47486⭐</code></b> <b><code>&nbsp;&nbsp;3428🍴</code></b> [Source Code](https://github.com/usememos/memos))) `MIT` `Docker/Go`
- 🌎 [Note Mark](notemark.docs.enchantedcode.co.uk/) - Minimal web-based Markdown notes app. (<b><code>&nbsp;&nbsp;&nbsp;621⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Source Code](https://github.com/enchant97/note-mark))) `AGPL-3.0` `Docker`
- 🌎 [Overleaf](www.overleaf.com/) - Web-based collaborative LaTeX editor. (<b><code>&nbsp;17051⭐</code></b> <b><code>&nbsp;&nbsp;1827🍴</code></b> [Source Code](https://github.com/overleaf/overleaf))) `AGPL-3.0` `Ruby`
- 🌎 [Plainpad](alextselegidis.com/get/plainpad/) - Modern note taking application for the cloud, utilizing the best features of progressive web apps technology.  🌎 [Demo](alextselegidis.com/try/plainpad/), <b><code>&nbsp;&nbsp;&nbsp;377⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Source Code](https://github.com/alextselegidis/plainpad))) `GPL-3.0` `PHP`
- 🌎 [SilverBullet](silverbullet.md/) - Note-taking application optimized for people with a hacker mindset.  🌎 [Demo](play.silverbullet.md/), <b><code>&nbsp;&nbsp;4363⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;318🍴</code></b> [Source Code](https://github.com/silverbulletmd/silverbullet)), 🌎 [Clients](silverbullet.md/Libraries)) `MIT` `Docker/Deno`
- 🌎 [Standard Notes](docs.standardnotes.com/self-hosting/getting-started) - Simple and private notes app. Protect your privacy while getting more done. That's Standard Notes.  🌎 [Demo](app.standardnotes.com/), <b><code>&nbsp;&nbsp;6194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;509🍴</code></b> [Source Code](https://github.com/standardnotes/app))) `GPL-3.0` `Ruby`
- <b><code>&nbsp;33652⭐</code></b> <b><code>&nbsp;&nbsp;2236🍴</code></b> [TriliumNext Notes](https://github.com/TriliumNext/Trilium)) - Cross-platform hierarchical note taking application with focus on building large personal knowledge bases (fork of Trilium Notes). `AGPL-3.0` `Nodejs/Docker/K8S`
- 🌎 [Turtl](turtl.it/) - Totally private personal database and note taking app. ([Source Code](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- 🌎 [Writing](josephernest.github.io/writing/) - Lightweight distraction-free text editor, in the browser (Markdown and LaTeX supported). No lag when writing. (<b><code>&nbsp;&nbsp;1112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Source Code](https://github.com/josephernest/writing))) `MIT` `Javascript`


### Office Suites

**[`^        back to top        ^`](#awesome-selfhosted)**

An 🌎 [office suite](en.wikipedia.org/wiki/List_of_office_suites) is a collection of productivity software usually containing at least a word processor, spreadsheet and a presentation program.

- 🌎 [Collabora Online Development Edition](www.collaboraoffice.com/code) - Collabora Online Development Edition (CODE) is a powerful LibreOffice-based online office that supports all major document, spreadsheet and presentation file formats, which you can integrate in your own infrastructure.  🌎 [Source Code](cgit.freedesktop.org/libreoffice/online/)) `MPL-2.0` `C++`
- 🌎 [CryptPad](cryptpad.org) - Collaboration suite built to enable collaboration, synchronizing changes to documents in real time. (<b><code>&nbsp;&nbsp;7179⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;790🍴</code></b> [Source Code](https://github.com/cryptpad/cryptpad))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Digislides](ladigitale.dev/digislides/) - Create multimedia presentations in a quick and easy way. (documentation in French).  🌎 [Demo](ladigitale.dev/digislides/), 🌎 [Source Code](codeberg.org/ladigitale/Digislides)) `AGPL-3.0` `Nodejs/PHP`
- 🌎 [Etherpad](etherpad.org/) - Highly customizable online editor providing collaborative editing in real-time.  🌎 [Demo](demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), <b><code>&nbsp;18005⭐</code></b> <b><code>&nbsp;&nbsp;2994🍴</code></b> [Source Code](https://github.com/ether/etherpad-lite))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [Grist](getgrist.com/) - Next-generation spreadsheet with relational structure, formula-based access control, and a portable, self-contained format (alternative to Airtable).  🌎 [Demo](docs.getgrist.com), <b><code>&nbsp;10297⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;518🍴</code></b> [Source Code](https://github.com/gristlabs/grist-core))) `Apache-2.0` `Nodejs/Python/Docker`
- 🌎 [ONLYOFFICE](helpcenter.onlyoffice.com/faq/server-opensource.aspx) - Office suite that enables you to manage documents, projects, team and customer relations in one place. (<b><code>&nbsp;&nbsp;6075⭐</code></b> <b><code>&nbsp;&nbsp;1221🍴</code></b> [Source Code](https://github.com/ONLYOFFICE/DocumentServer))) `AGPL-3.0` `Nodejs/Docker`


### Password Managers

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [password manager](en.wikipedia.org/wiki/Password_manager) allows users to store, generate, and manage their passwords for local applications and online services.

- 🌎 [AliasVault](www.aliasvault.net) - End-to-end encrypted password manager with a built-in email alias generator and server. (<b><code>&nbsp;&nbsp;1788⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [Source Code](https://github.com/lanedirt/AliasVault))) `MIT` `Docker`
- 🌎 [Bitwarden](bitwarden.com/) `⚠` - Password manager with a webapp, browser extension, and mobile app. (<b><code>&nbsp;17714⭐</code></b> <b><code>&nbsp;&nbsp;1494🍴</code></b> [Source Code](https://github.com/bitwarden/server))) `AGPL-3.0` `Docker/C#`
- 🌎 [Passbolt](www.passbolt.com/) - Collaborative password manager. (<b><code>&nbsp;&nbsp;5524⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;363🍴</code></b> [Source Code](https://github.com/passbolt/passbolt_api))) `AGPL-3.0` `PHP/deb/K8S/Docker`
- 🌎 [PassIt](passit.io/) - Simple password manage with sharing features by group and user, but no administration interface.  🌎 [Demo](app.passit.io/), 🌎 [Source Code](gitlab.com/passit)) `AGPL-3.0` `Docker/Django`
- 🌎 [Psono](psono.com/) - Password manager for companies.  🌎 [Demo](www.psono.pw), 🌎 [Source Code](gitlab.com/esaqa/psono/psono-fileserver)) `Apache-2.0` `Python`
- 🌎 [Teampass](teampass.net/) - Password manager dedicated for managing passwords in a collaborative way. One symmetric key is used to encrypt all shared/team passwords and stored server side in a file and the database. works on any server Apache, MySQL and PHP. (<b><code>&nbsp;&nbsp;1766⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;570🍴</code></b> [Source Code](https://github.com/nilsteampassnet/TeamPass))) `GPL-3.0` `PHP`
- <b><code>&nbsp;52386⭐</code></b> <b><code>&nbsp;&nbsp;2435🍴</code></b> [Vaultwarden](https://github.com/dani-garcia/vaultwarden)) - Lightweight Bitwarden server API implementation written in Rust. `GPL-3.0` `Rust/Docker`


### Pastebins

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [pastebin](en.wikipedia.org/wiki/Pastebin) is a type of online content-hosting service used for sharing and storing code and text.

- <b><code>&nbsp;&nbsp;&nbsp;621⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [bin](https://github.com/w4/bin)) - A paste bin that's actually minimalist. `WTFPL/0BSD` `Rust`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [BinPastes](https://github.com/querwurzel/BinPastes)) - Minimal pastebin supporting client-side encryption, fulltext search, one-time messages. Intended for one to few users looking for a simple pastebin deployment.  🌎 [Demo](paste.wylke.it)) `Apache-2.0` `Java`
- <b><code>&nbsp;&nbsp;1939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [ByteStash](https://github.com/jordan-dalby/ByteStash)) - Pastebin and file storage service with a simple web interface. Supports syntax highlighting, optional user authentication and public sharing. (<b><code>&nbsp;&nbsp;1939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Demo](https://github.com/jordan-dalby/ByteStash?tab=readme-ov-file#demo))) `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Chiyogami](https://github.com/rhee876527/chiyogami)) - Pastebin with API, client-side encryption, user accounts, syntax highlighting, markdown rendering, and more.  🌎 [Demo](chiyogami.myaddr.dev/)) `BSD-3-Clause` `Docker`
- 🌎 [dpaste](dpaste.org/) - Simple pastebin with multiple text and code option, with short url result easy to remember. (<b><code>&nbsp;&nbsp;&nbsp;587⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;126🍴</code></b> [Source Code](https://github.com/DarrenOfficial/dpaste))) `MIT` `Docker/Django`
- 🌎 [Hemmelig](hemmelig.app) - Share encrypted secrets cross organizations, or as private persons. (<b><code>&nbsp;&nbsp;1060⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/HemmeligOrg/Hemmelig.app))) `MIT` `Docker/Nodejs`
- 🌎 [lesma](lesma.eu) - Simple paste app friendly with browser and command line.  🌎 [Demo](lesma.eu), 🌎 [Source Code](gitlab.com/ogarcia/lesma)) `GPL-3.0` `Rust/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Local Content Share](https://github.com/Tanq16/local-content-share)) - Store and share text snippets and files within your local network. `MIT` `Docker/Go`
- 🌎 [not-th.re](not-th.re) - Simple paste sharing platform, with client side encryption, featuring the monaco browser-based code editor.  🌎 [Demo](not-th.re), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/not-three/main))) `AGPL-3.0` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;2875⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [Opengist](https://github.com/thomiceli/opengist)) - Pastebin powered by Git.  🌎 [Demo](demo.opengist.io)) `AGPL-3.0` `Docker/Go/Nodejs`
- 🌎 [paaster](paaster.io) - End-to-end encrypted pastebin built with the objective of simplicity. (<b><code>&nbsp;&nbsp;&nbsp;505⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Source Code](https://github.com/WardPearce/paaster))) `AGPL-3.0` `Docker`
- 🌎 [pacebin](git.crueter.xyz/crueter/pacebin) - Super-minimal pastebin and file upload service focusing on small executable size, portability, and ease of configuration.  🌎 [Demo](paste.crueter.xyz)) `AGPL-3.0` `C`
- 🌎 [Password Pusher](pwpush.com) - Dead-simple application to securely communicate passwords (or text) over the web. Passwords automatically expire after a certain number of views and/or time has passed. (<b><code>&nbsp;&nbsp;2801⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;423🍴</code></b> [Source Code](https://github.com/pglombardo/PasswordPusher))) `Apache-2.0` `Docker/K8S/Ruby`
- 🌎 [Pastefy](pastefy.app/) - Beautiful, simple and easy to deploy Pastebin with optional client encryption, multitab pastes, an API, a highlighted editor and more. (<b><code>&nbsp;&nbsp;&nbsp;389⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [Source Code](https://github.com/interaapps/pastefy)), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Clients](https://github.com/topics/pastefy-addon))) `MIT` `Docker/K8S/Java`
- 🌎 [PrivateBin](privatebin.info/) - Minimalist pastebin/discussion board where the server has zero knowledge of hosted data.  🌎 [Demo](privatebin.net/), <b><code>&nbsp;&nbsp;7873⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;945🍴</code></b> [Source Code](https://github.com/PrivateBin/PrivateBin))) `Zlib` `PHP`
- <b><code>&nbsp;&nbsp;1057⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [rustypaste](https://github.com/orhun/rustypaste)) - Minimal file upload/pastebin service. `MIT` `Rust`
- 🌎 [SnyPy](snypy.com) - Open source on-prem code snippet manager.  🌎 [Demo](app.snypy.com), [Source Code](https://github.com/snypy)) `MIT` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;558⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age)) - Very simple (to deploy and to use) secret message service using Hashicorp Vault as a secrets storage. `MIT` `Go`
- <b><code>&nbsp;&nbsp;&nbsp;731⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Wastebin](https://github.com/matze/wastebin)) - Lightweight, minimal and fast pastebin with an SQLite backend.  🌎 [Demo](bin.bloerg.net)) `MIT` `Rust/Docker`
- <b><code>&nbsp;&nbsp;2487⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;367🍴</code></b> [Yopass](https://github.com/jhaals/yopass)) - Secure sharing of secrets, passwords and files.  🌎 [Demo](yopass.se/)) `Apache-2.0` `Go/Docker`


### Personal Dashboards

**[`^        back to top        ^`](#awesome-selfhosted)**

Dashboards for accessing information and applications.

_Related: [Monitoring](#monitoring), [Bookmarks and Link Sharing](#bookmarks-and-link-sharing)_

- 🌎 [Dashy](dashy.to/) - Feature-rich homepage for your homelab, with easy YAML configuration.  🌎 [Demo](demo.dashy.to/), <b><code>&nbsp;23457⭐</code></b> <b><code>&nbsp;&nbsp;1714🍴</code></b> [Source Code](https://github.com/lissy93/dashy))) `MIT` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;740⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Fenrus](https://github.com/revenz/fenrus)) - Personal home page that allows for multiple users, guest access and multiple dashboards for each user. It also has "Smart Apps" which display live data for those apps. `GPL-3.0` `.NET/Docker`
- <b><code>&nbsp;30578⭐</code></b> <b><code>&nbsp;&nbsp;1140🍴</code></b> [Glance](https://github.com/glanceapp/glance)) - Highly customizable dashboard that puts all your feeds in one place. `AGPL-3.0` `Docker/Go`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [gobookmarks](https://github.com/arran4/gobookmarks)) - Landing page to display bookmarks stored in GitHub, GitLab or local Git. `AGPL-3.0` `Go/Docker`
- 🌎 [Heimdall](heimdall.site/) - Elegant solution to organise all your web applications. (<b><code>&nbsp;&nbsp;8879⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;596🍴</code></b> [Source Code](https://github.com/linuxserver/Heimdall))) `MIT` `PHP`
- 🌎 [Hiccup](designedbyashw.in/test/hiccup/) - Beautiful static homepage to get to your links and services quickly. It has built-in search, editing, PWA support and localstorage caching to easily organize your start page. (<b><code>&nbsp;&nbsp;&nbsp;186⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Source Code](https://github.com/ashwin-pc/hiccup))) `MIT` `Javascript/Docker`
- 🌎 [Homarr](homarr.dev) - Sleek, modern dashboard with many integrations and web-based config. (<b><code>&nbsp;&nbsp;2489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [Source Code](https://github.com/homarr-labs/homarr))) `MIT` `Docker/Nodejs`
- <b><code>&nbsp;27426⭐</code></b> <b><code>&nbsp;&nbsp;1730🍴</code></b> [Homepage by gethomepage](https://github.com/gethomepage/homepage)) - Highly customizable homepage (or startpage / application dashboard) with Docker and service API integrations. `GPL-3.0` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;321⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Homepage by tomershvueli](https://github.com/tomershvueli/homepage)) - Simple, standalone, self-hosted PHP page that is your window to your server and the web. `MIT` `PHP`
- <b><code>&nbsp;10948⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;887🍴</code></b> [Homer](https://github.com/bastienwirtz/homer)) - Dead simple static homepage to expose your server services, with an easy yaml configuration and connectivity check.  🌎 [Demo](homer-demo.netlify.app)) `Apache-2.0` `Docker/K8S/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Hubleys](https://github.com/knrdl/hubleys-dashboard)) - Personal dashboards to organize links for multiple users via a central yaml config. `MIT` `Docker`
- 🌎 [LinkStack](linkstack.org/) - Link all your social media platforms easily accessible on one page, customizable through an intuitive, easy to use user/admin interface (alternative to Linktree and Manylink).  🌎 [Demo](linksta.cc/), <b><code>&nbsp;&nbsp;3284⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;364🍴</code></b> [Source Code](https://github.com/LinkStackOrg/LinkStack))) `AGPL-3.0` `PHP/Docker`
- 🌎 [LittleLink](littlelink.io/) - Simplistic approach for links in bio with 100+ branded buttons (alternative to Linktree).  🌎 [Demo](littlelink.io/), <b><code>&nbsp;&nbsp;2750⭐</code></b> <b><code>&nbsp;&nbsp;1379🍴</code></b> [Source Code](https://github.com/sethcottle/littlelink))) `MIT` `Javascript`
- 🌎 [Mafl](mafl.hywax.space/) - Minimalistic flexible homepage. (<b><code>&nbsp;&nbsp;&nbsp;632⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Source Code](https://github.com/hywax/mafl))) `MIT` `Docker/Nodejs`
- 🌎 [Personal Management System](volmarg.github.io/) - Organize the essentials of everyday life, everything from a simple to-do list, and notes up to payments, and schedules. (<b><code>&nbsp;&nbsp;3718⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;297🍴</code></b> [Demo](https://github.com/Volmarg/personal-management-system#documentation--demo)), <b><code>&nbsp;&nbsp;3718⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;297🍴</code></b> [Source Code](https://github.com/Volmarg/personal-management-system))) `MIT` `Docker`
- 🌎 [portkey](portkey.page) - Simple web portal that serves as a startup page, displaying a compilation of links and URLs, while also allowing the addition of custom pages, all managed through a single configuration file.  🌎 [Demo](demo.portkey.page), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Source Code](https://github.com/kodehat/portkey))) `AGPL-3.0` `Go/Docker`
- <b><code>&nbsp;&nbsp;2885⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [ryot](https://github.com/ignisda/ryot)) - Track various facets of your life - media, fitness, etc. (<b><code>&nbsp;&nbsp;2885⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [Demo](https://github.com/IgnisDa/ryot?tab=readme-ov-file#-demo))) `GPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;&nbsp;472⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Starbase 80](https://github.com/notclickable-jordan/starbase-80)) - A simple homepage with an iPad-style application grid, for mobile and desktop. One JSON configuration file. `MIT` `Docker`
- <b><code>&nbsp;&nbsp;4112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [Your Spotify](https://github.com/Yooooomi/your_spotify)) `⚠` - Allows you to record your Spotify listening activity and have statistics about them served through a Web application. `MIT` `Nodejs/Docker`


### Photo Galleries

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [gallery](en.wikipedia.org/wiki/Gallery_Software) is software that helps the user publish or share photos, pictures, videos or other digital media.

_Related: [Static Site Generators](#static-site-generators), [Media Streaming - Video Streaming](#media-streaming---video-streaming), [Content Management Systems (CMS)](#content-management-systems-cms)_

- 🌎 [Chevereto](chevereto.com/) - Ultimate image sharing software. Create your very own personal image hosting website in just minutes. (<b><code>&nbsp;&nbsp;&nbsp;858⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Source Code](https://github.com/chevereto/chevereto))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Damselfly](damselfly.info) - Fast server-based photo management system for large collections of images. Includes face detection, face & object recognition, powerful search, and EXIF Keyword tagging. Runs on Linux, MacOS and Windows. (<b><code>&nbsp;&nbsp;1724⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [Source Code](https://github.com/webreaper/damselfly))) `GPL-3.0` `Docker/C#/.NET`
- 🌎 [Ente](ente.io/) - An end-to-end encrypted photo-sharing platform (alternative to Google Photos, Apple Photos). (<b><code>&nbsp;23453⭐</code></b> <b><code>&nbsp;&nbsp;1381🍴</code></b> [Source Code](https://github.com/ente-io/ente))) `AGPL-3.0` `Docker/Nodejs/Go`
- 🌎 [HomeGallery](home-gallery.org) - Browse personal photos and videos featuring tagging, mobile-friendly, and AI powered image discovery.  🌎 [Demo](demo.home-gallery.org), <b><code>&nbsp;&nbsp;1064⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Source Code](https://github.com/xemle/home-gallery))) `MIT` `Nodejs/Docker`
- <b><code>&nbsp;&nbsp;1220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Immich Kiosk](https://github.com/damongolding/immich-kiosk)) - Lightweight slideshow for running on kiosk devices and browsers that uses Immich as a data source. `GPL-3.0` `Docker/Go`
- 🌎 [Immich](immich.app/) - Photo and video backup solution directly from your mobile phone. (<b><code>&nbsp;87410⭐</code></b> <b><code>&nbsp;&nbsp;4610🍴</code></b> [Demo](https://github.com/immich-app/immich#demo)), <b><code>&nbsp;87410⭐</code></b> <b><code>&nbsp;&nbsp;4610🍴</code></b> [Source Code](https://github.com/immich-app/immich))) `AGPL-3.0` `Docker`
- <b><code>&nbsp;&nbsp;7876⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;367🍴</code></b> [LibrePhotos](https://github.com/LibrePhotos/librephotos)) - Photo management service with a slight focus on cool graphs (alternative to Google Photos).  🌎 [Clients](docs.librephotos.com/docs/user-guide/mobile/)) `MIT` `Python/Docker`
- 🌎 [Lychee](lycheeorg.github.io/) - Grid and album based photo-management-system. (<b><code>&nbsp;&nbsp;4013⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;361🍴</code></b> [Source Code](https://github.com/LycheeOrg/Lychee))) `MIT` `PHP/Docker`
- 🌎 [Mediagoblin](mediagoblin.org) - Media publishing platform that anyone can run (alternative to Flickr, YouTube, SoundCloud).  🌎 [Source Code](git.savannah.gnu.org/cgit/mediagoblin.git/tree/)) `AGPL-3.0` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Mejiro](https://github.com/dmpop/pellicola)) - Easy-to-use instant photo publishing. `GPL-3.0` `PHP`
- 🌎 [Nextcloud Memories](memories.gallery/) - Fast, modern and advanced photo management suite. Runs as a Nextcloud app.  🌎 [Demo](demo.memories.gallery/apps/memories/), <b><code>&nbsp;&nbsp;3662⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [Source Code](https://github.com/pulsejet/memories))) `AGPL-3.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;540⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Photofield](https://github.com/SmilyOrg/photofield)) - Experimental fast photo viewer. `MIT` `Docker/Go`
- 🌎 [PhotoPrism](photoprism.org) - Personal photo management powered by Go and Google TensorFlow.  Browse, organize, and share your personal photo collection, using the latest technologies to automatically tag and find pictures.  🌎 [Demo](demo.photoprism.app/library/browse), <b><code>&nbsp;39002⭐</code></b> <b><code>&nbsp;&nbsp;2186🍴</code></b> [Source Code](https://github.com/photoprism/photoprism))) `AGPL-3.0` `Go/Docker`
- 🌎 [Photoview](photoview.github.io/) - Simple and user-friendly photo gallery for personal servers. It is made for photographers and aims to provide an easy and fast way to navigate directories, with thousands of high resolution photos.  🌎 [Demo](photoview.github.io/), <b><code>&nbsp;&nbsp;6296⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;449🍴</code></b> [Source Code](https://github.com/photoview/photoview))) `GPL-3.0` `Go/Docker`
- 🌎 [PiGallery 2](bpatrik.github.io/pigallery2/) - Directory-first photo gallery website, with a rich UI, optimised for running on low resource servers. (<b><code>&nbsp;&nbsp;2089⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [Source Code](https://github.com/bpatrik/pigallery2))) `MIT` `Docker/Nodejs`
- 🌎 [Piwigo](piwigo.org/) - Photo gallery software for the web, built by an active community of users and developers. (<b><code>&nbsp;&nbsp;3673⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;464🍴</code></b> [Source Code](https://github.com/Piwigo/Piwigo))) `GPL-2.0` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;932⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [sigal](https://github.com/saimn/sigal)) - Yet another simple static gallery generator. `MIT` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [SPIS](https://github.com/gbbirkisson/spis)) - A simple, lightweight and fast media server with decent mobile support. `GPL-3.0` `Docker/Rust`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [This week in past](https://github.com/RouHim/this-week-in-past)) - Aggregates images taken this week, from previous years and presents them on a web page with a simple slideshow. `MIT` `Docker/Rust`
- [Thumbor](http://thumbor.org/) - A smart imaging service and enables on-demand cropping, resizing, applying filters and optimizing images. (<b><code>&nbsp;10427⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;864🍴</code></b> [Source Code](https://github.com/thumbor/thumbor))) `MIT` `Python/Docker`
- 🌎 [WeddingShare](docs.wedding-share.org/) - Event photo sharing platform and gallery with slideshow that allows guests to view and share memories via a QR code.  🌎 [Demo](demo.wedding-share.org/), <b><code>&nbsp;&nbsp;&nbsp;800⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Source Code](https://github.com/Cirx08/WeddingShare))) `GPL-3.0` `C#/Docker`
- 🌎 [Zenphoto](www.zenphoto.org/) - Open-source gallery and CMS project. (<b><code>&nbsp;&nbsp;&nbsp;316⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [Source Code](https://github.com/zenphoto/zenphoto))) `GPL-2.0` `PHP`


### Polls and Events

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for organising 🌎 [polls](en.wikipedia.org/wiki/Opinion_poll) and 🌎 [events](en.wikipedia.org/wiki/Event).

_Related: [Booking and Scheduling](#booking-and-scheduling)_

- <b><code>&nbsp;&nbsp;&nbsp;291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Bitpoll](https://github.com/fsinfuhh/Bitpoll)) - Conduct polls about dates, times or general questions.  🌎 [Demo](bitpoll.de/)) `GPL-3.0` `Docker/Python`
- 🌎 [Bracket](docs.bracketapp.nl/) - Flexible tournament system to build a tournament setup, add teams, schedule matches, keep track of scores and present ranking live to the public.  🌎 [Demo](www.bracketapp.nl/demo), <b><code>&nbsp;&nbsp;1544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [Source Code](https://github.com/evroon/bracket))) `AGPL-3.0` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;396⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Christmas Community](https://github.com/Wingysam/Christmas-Community)) - Create a simple place for your entire family to use to find gifts that people want, and to avoid double-gifting. `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Claper](claper.co/) - The ultimate tool to interact with your audience (alternative to Slido, AhaSlides and Mentimeter). (<b><code>&nbsp;&nbsp;&nbsp;679⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [Source Code](https://github.com/ClaperCo/Claper))) `GPL-3.0` `Elixir/Docker`
- 🌎 [ClearFlask](clearflask.com) - Community-feedback tool for managing incoming feedback and prioritizing a public roadmap (alternative to Canny, UserVoice, Upvoty).  🌎 [Demo](product.clearflask.com), <b><code>&nbsp;&nbsp;&nbsp;402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Source Code](https://github.com/clearflask/clearflask))) `AGPL-3.0` `Docker`
- 🌎 [docassemble](docassemble.org/) - A free, open-source expert system for guided interviews and document assembly, based on Python, YAML, and Markdown.  🌎 [Demo](demo.docassemble.org/run/legal), <b><code>&nbsp;&nbsp;&nbsp;910⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;291🍴</code></b> [Source Code](https://github.com/jhpyle/docassemble))) `MIT` `Docker/Python`
- 🌎 [Fider](fider.io) - Open platform to collect and prioritize feedback (alternative to UserVoice).  🌎 [Demo](demo.fider.io), <b><code>&nbsp;&nbsp;3930⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;748🍴</code></b> [Source Code](https://github.com/getfider/fider))) `MIT` `Docker`
- 🌎 [Formbricks](formbricks.com) - Experience Management Suite built on the largest open source survey stack worldwide. Gracefully gather feedback at every step of the customer journey to know what your customers need.  🌎 [Demo](app.formbricks.com), <b><code>&nbsp;11666⭐</code></b> <b><code>&nbsp;&nbsp;2067🍴</code></b> [Source Code](https://github.com/formbricks/formbricks))) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Framadate](framadate.org/abc/) - Online service for planning an appointment or make a decision quickly and easily: Make a poll, Define dates or subjects to choose, Send the poll link to your friends or colleagues, Discuss and make a decision.  🌎 [Demo](framadate.org/aqg259dth55iuhwm), 🌎 [Source Code](framagit.org/framasoft/framadate?)) `CECILL-B` `PHP`
- 🌎 [Gancio](gancio.org/) - Local community event and agenda sharing.  🌎 [Demo](demo.gancio.org/), 🌎 [Source Code](framagit.org/les/gancio)) `AGPL-3.0` `Nodejs`
- 🌎 [gathio](docs.gath.io/) - Self-destructing, shareable, no-registration event pages.  🌎 [Demo](gath.io/), <b><code>&nbsp;&nbsp;&nbsp;412⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Source Code](https://github.com/lowercasename/gathio))) `GPL-3.0` `Nodejs/Docker`
- 🌎 [HeyForm](heyform.net) - Form builder that allows anyone to create engaging conversational forms for surveys, questionnaires, quizzes, and polls. (<b><code>&nbsp;&nbsp;8522⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;653🍴</code></b> [Source Code](https://github.com/heyform/heyform))) `AGPL-3.0` `Docker`
- 🌎 [hitobito](hitobito.com) - Manage complex group hierarchies with members, events and a lot more.  🌎 [Demo](demo.hitobito.com/en/users/sign_in), <b><code>&nbsp;&nbsp;&nbsp;454⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [Source Code](https://github.com/hitobito/hitobito))) `AGPL-3.0` `Ruby`
- 🌎 [Input](getinput.co) - Privacy-focused, no-code, open-source form builder designed for simplicity and brand consistency. (<b><code>&nbsp;&nbsp;&nbsp;246⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Source Code](https://github.com/deck9/input))) `AGPL-3.0` `PHP/Nodejs/Docker`
- 🌎 [LimeSurvey](www.limesurvey.org) - Feature-rich web-based polling software. Supports extensive survey logic.  🌎 [Demo](demo.limesurvey.org), <b><code>&nbsp;&nbsp;3462⭐</code></b> <b><code>&nbsp;&nbsp;1081🍴</code></b> [Source Code](https://github.com/LimeSurvey/LimeSurvey))) `GPL-2.0` `PHP`
- 🌎 [Meetable](events.indieweb.org) - Minimal events aggregator. (<b><code>&nbsp;&nbsp;&nbsp;157⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Source Code](https://github.com/aaronpk/Meetable))) `MIT` `PHP`
- 🌎 [Mobilizon](mobilizon.org) - Federated tool that helps you find, create and organise events and groups.  🌎 [Source Code](framagit.org/framasoft/mobilizon/)) `AGPL-3.0` `Elixir/Docker`
- 🌎 [OpnForm](opnform.com) - Beautiful open-source form builder.  🌎 [Demo](opnform.com/forms/create/guest), <b><code>&nbsp;&nbsp;3055⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;438🍴</code></b> [Source Code](https://github.com/JhumanJ/opnform))) `AGPL-3.0` `PHP/Nodejs/Docker`


### Proxy

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [proxy](en.wikipedia.org/wiki/Proxy_server) is a server application that acts as an intermediary between a client requesting a resource and the server providing that resource. This section about forward (i.e. outgoing) proxies. For reverse proxies, see the Web Server section.

_Related: [Web Servers](#web-servers)_

- 🌎 [g3proxy](g3-project.readthedocs.io/projects/g3proxy/en/latest/) - Forward proxy server supporting proxy chaining, protocol inspection, MITM Interception, ICAP adaptation and transparent proxy. (<b><code>&nbsp;&nbsp;&nbsp;795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Source Code](https://github.com/bytedance/g3/tree/master/g3proxy))) `Apache-2.0` `Rust/deb`
- 🌎 [imgproxy](imgproxy.net/) - Fast and secure standalone server for resizing and converting remote images. (<b><code>&nbsp;10234⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;708🍴</code></b> [Source Code](https://github.com/imgproxy/imgproxy))) `MIT` `Go/Docker/K8S`
- 🌎 [iodine](code.kryo.se/iodine/) - IPv4 over DNS tunnel solution, enabling you to start up a socks5 proxy listener. (<b><code>&nbsp;&nbsp;7514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;570🍴</code></b> [Source Code](https://github.com/yarrick/iodine))) `ISC` `C/deb`
- 🌎 [Outline Server](getoutline.org/) - A proxy server that runs a Shadowsocks instance for each access key and a REST API to manage the access keys. (<b><code>&nbsp;&nbsp;6127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;871🍴</code></b> [Source Code](https://github.com/Jigsaw-Code/outline-server))) `Apache-2.0` `Docker/Nodejs`
- 🌎 [Privoxy](www.privoxy.org) - Non-caching web proxy with advanced filtering capabilities for enhancing privacy, modifying web page data and HTTP headers, controlling access, and removing ads and other obnoxious Internet junk. `GPL-2.0` `C/deb`
- <b><code>&nbsp;&nbsp;4480⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;328🍴</code></b> [sish](https://github.com/antoniomika/sish)) - HTTP(S)/WS(S)/TCP tunnels to localhost using only SSH (serveo/ngrok alternative). `MIT` `Go/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;133⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server)) - SOCKS5 proxy server with built-in authentication and Telegram-bot for user management and user statistics on data spent (handy when you pay per GB of data). It is dockerised and simple to install. `Apache-2.0` `Docker`
- [Squid](http://www.squid-cache.org/) - Caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages.  🌎 [Source Code](code.launchpad.net/squid)) `GPL-2.0` `C/deb`
- 🌎 [Tinyproxy](tinyproxy.github.io/) - Light-weight HTTP/HTTPS proxy daemon. (<b><code>&nbsp;&nbsp;5582⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;743🍴</code></b> [Source Code](https://github.com/tinyproxy/tinyproxy))) `GPL-2.0` `C/deb`
- 🌎 [txtdot](tempoworks.github.io/documentation) - A HTTP proxy that parses only text, links and pictures from pages reducing internet bandwidth usage, removing ads and heavy scripts.  🌎 [Demo](txt.dc09.ru), <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Source Code](https://github.com/TempoWorks/txtdot))) `MIT` `Nodejs/Docker`


### Recipe Management

**[`^        back to top        ^`](#awesome-selfhosted)**

Software and tools for managing 🌎 [recipes](en.wikipedia.org/wiki/Recipe).

- 🌎 [Bar Assistant](barassistant.app/) - Manage your home bar while adding your ingredients, searching for cocktails and creating custom cocktail recipes.  🌎 [Demo](demo.barassistant.app/), <b><code>&nbsp;&nbsp;&nbsp;940⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Source Code](https://github.com/karlomikus/bar-assistant))) `MIT` `PHP/Docker`
- 🌎 [CookCLI](cooklang.org) - Command-line tool for automating meal planning and shopping with Cooklang recipes, scriptable for UNIX workflows, includes web server. (<b><code>&nbsp;&nbsp;1049⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Source Code](https://github.com/cooklang/CookCLI))) `MIT` `Rust`
- 🌎 [Fork Recipes](mikebgrep.github.io/forkapi/latest/clients/) - Manage your food recipes with simplicity. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Source Code](https://github.com/mikebgrep/fork.recipes))) `BSD-3-Clause` `Docker`
- 🌎 [KitchenOwl](docs.kitchenowl.org/latest/) - Cross-platform shopping list, recipe storage, expense tracker, and meal planner following the material design language. (<b><code>&nbsp;&nbsp;2910⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;165🍴</code></b> [Source Code](https://github.com/TomBursch/kitchenowl))) `AGPL-3.0` `Docker/deb`
- 🌎 [ManageMeals](managemeals.com/) - Manage recipes, import recipes by URL and organize them without any ads or unnecessary text.  🌎 [Demo](demo.managemeals.com/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/managemeals/manage-meals-web))) `GPL-3.0` `Docker`
- 🌎 [Mealie](nightly.mealie.io/) - Material design inspired recipe manager with category and tag management, shopping-lists, meal-planner, and site customizations. Mealie is focused on simple user interactions to keep the whole family using the app.  🌎 [Demo](demo.mealie.io), <b><code>&nbsp;10897⭐</code></b> <b><code>&nbsp;&nbsp;1061🍴</code></b> [Source Code](https://github.com/mealie-recipes/mealie))) `MIT` `Python`
- <b><code>&nbsp;&nbsp;&nbsp;814⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [RecipeSage](https://github.com/julianpoy/recipesage)) - A recipe keeper, meal plan organizer, and shopping list manager that can import recipes directly from any URL.  🌎 [Demo](recipesage.com)) `AGPL-3.0` `Nodejs`
- 🌎 [Recipya](recipes.musicavis.ca) - Clean, simple and powerful recipe manager your whole family will enjoy.  🌎 [Demo](recipes.musicavis.ca/guide/login), <b><code>&nbsp;&nbsp;&nbsp;380⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Source Code](https://github.com/reaper47/recipya))) `GPL-3.0` `Docker/Go`
- 🌎 [Specifically Clementines](davideshay.github.io/groceries/) - Grocery shopping app (previously Groceries), providing reliable sync with multiple users/devices (web/Android/iOS), recipes and integration with Tandoor. (<b><code>&nbsp;&nbsp;&nbsp;275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Source Code](https://github.com/davideshay/groceries))) `MIT` `Docker`
- 🌎 [Tamari](tamariapp.com) - Recipe manager web app with a built-in collection of recipes. Organize by favorites and categories, create shopping lists, and plan meals.  🌎 [Demo](app.tamariapp.com), <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Source Code](https://github.com/alexbates/Tamari))) `GPL-3.0` `Docker/Python`
- 🌎 [Vanilla Cookbook](vanilla-cookbook.readthedocs.io/en/) - Recipe manager designed with complexity under the hood, keeping the user experience as uncluttered, simply vanilla as possible. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;71⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Source Code](https://github.com/jt196/vanilla-cookbook))) `GPL-3.0` `Docker/Nodejs`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [What To Cook?](https://github.com/kassner/whattocook)) - Get a recipe to cook today, based on the ingredients you have at home. `AGPL-3.0` `Docker`


### Remote Access

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Remote desktop](en.wikipedia.org/wiki/Remote_desktop_software) and 🌎 [SSH](en.wikipedia.org/wiki/Secure_Shell) servers and web interfaces for remote management of computer systems.

- 🌎 [Engity's Bifröst](bifroest.engity.org/) - Highly customizable SSH server with several ways to authorize a user and options where and how to execute a user's session. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/engity-com/bifroest))) `Apache-2.0` `Go/Docker`
- 🌎 [Firezone](www.firezone.dev/) - Secure remote access gateway that supports the WireGuard protocol. It offers a Web GUI, 1-line install script, multi-factor auth (MFA), and SSO. (<b><code>&nbsp;&nbsp;8320⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;396🍴</code></b> [Source Code](https://github.com/firezone/firezone))) `Apache-2.0` `Elixir/Docker`
- 🌎 [Guacamole](guacamole.apache.org) - Clientless remote desktop gateway supporting standard protocols like VNC and RDP. (<b><code>&nbsp;&nbsp;3638⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;731🍴</code></b> [Source Code](https://github.com/apache/guacamole-server))) `Apache-2.0` `Java/C`
- 🌎 [MeshCentral](meshcentral.com/) - Run your own web server to remotely manage and control computers on a local network or anywhere on the internet. (<b><code>&nbsp;&nbsp;5829⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;766🍴</code></b> [Source Code](https://github.com/Ylianst/MeshCentral))) `Apache-2.0` `Nodejs`
- <b><code>&nbsp;&nbsp;4992⭐</code></b> <b><code>&nbsp;&nbsp;1634🍴</code></b> [Remotely](https://github.com/immense/Remotely)) - Remote desktop control and remote scripting solution, enterprise level remote support solution with admin web interface and remote control via browser. `GPL-3.0` `C#/Docker`
- 🌎 [ShellHub](www.shellhub.io) - Modern SSH server for remotely accessing linux devices via command line (using any SSH client) or web-based user interface (alternative to sshd). (<b><code>&nbsp;&nbsp;1865⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [Source Code](https://github.com/shellhub-io/shellhub))) `Apache-2.0` `Docker`
- <b><code>&nbsp;&nbsp;2955⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;389🍴</code></b> [Sshwifty](https://github.com/nirui/sshwifty)) - Sshwifty is a SSH and Telnet connector made for the Web.  🌎 [Demo](sshwifty-demo.nirui.org)) `AGPL-3.0` `Go/Docker`
- 🌎 [Termix](docs.termix.site/) - Clientless web-based server management platform with SSH terminal, tunneling, and file editing capabilities. (<b><code>&nbsp;&nbsp;8775⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;357🍴</code></b> [Source Code](https://github.com/LukeGus/Termix))) `Apache-2.0` `Docker`
- <b><code>&nbsp;&nbsp;6258⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;219🍴</code></b> [Warpgate](https://github.com/warp-tech/warpgate)) - Smart SSH and HTTPS bastion that works with any SSH client. `Apache-2.0` `Rust/Docker`


### Resource Planning

**[`^        back to top        ^`](#awesome-selfhosted)**

Software and tools to help with 🌎 [resource and supply planning](en.wikipedia.org/wiki/Resource_planning), including 🌎 [enterprise resource and supply planning (ERP)](en.wikipedia.org/wiki/Enterprise_resource_planning).

_Related: [Money, Budgeting & Management](#money-budgeting--management), [Inventory Management](#inventory-management)_

- 🌎 [Dolibarr](www.dolibarr.org/) - Modern CRM software package to manage your company or foundation activity (contacts, suppliers, invoices, orders, stocks, agenda, accounting, ...).  🌎 [Demo](www.dolibarr.org/onlinedemo.php), <b><code>&nbsp;&nbsp;6772⭐</code></b> <b><code>&nbsp;&nbsp;3221🍴</code></b> [Source Code](https://github.com/Dolibarr/dolibarr))) `GPL-3.0` `PHP/deb`
- 🌎 [ERPNext](frappe.io/erpnext) - ERP system to help you run your business. (<b><code>&nbsp;30721⭐</code></b> <b><code>&nbsp;10046🍴</code></b> [Source Code](https://github.com/frappe/erpnext))) `GPL-3.0` `Python/Docker`
- 🌎 [farmOS](farmos.org/) - Web-based farm record keeping application.  🌎 [Demo](farmos-demo.rootedsolutions.io/), <b><code>&nbsp;&nbsp;1182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;332🍴</code></b> [Source Code](https://github.com/farmOS/farmOS))) `GPL-2.0` `PHP/Docker`
- 🌎 [grocy](grocy.info/) - ERP beyond your fridge. Groceries & household management solution for your home.  🌎 [Demo](en.demo.grocy.info/), <b><code>&nbsp;&nbsp;8544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;702🍴</code></b> [Source Code](https://github.com/grocy/grocy))) `MIT` `PHP/Docker`
- 🌎 [LedgerSMB](ledgersmb.org/) - Integrated accounting and ERP system for small and midsize businesses, with double entry accounting, budgeting, invoicing, quotations, projects, orders and inventory management, shipping and more. (<b><code>&nbsp;&nbsp;&nbsp;513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;163🍴</code></b> [Source Code](https://github.com/ledgersmb/LedgerSMB))) `GPL-2.0` `Docker/Perl`
- 🌎 [Odoo](www.odoo.com) - Free open source ERP system.  🌎 [Demo](demo.odoo.com/), <b><code>&nbsp;48037⭐</code></b> <b><code>&nbsp;30883🍴</code></b> [Source Code](https://github.com/odoo/odoo))) `LGPL-3.0` `Python/deb/Docker`
- 🌎 [OFBiz](ofbiz.apache.org/) - Enterprise Resource Planning system with a suite of business applications flexible enough to be used across any industry. (<b><code>&nbsp;&nbsp;&nbsp;975⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;615🍴</code></b> [Source Code](https://github.com/apache/ofbiz-framework))) `Apache-2.0` `Java`
- 🌎 [Tryton](www.tryton.org/) - Free open source business solution.  🌎 [Demo](www.tryton.org/demo), 🌎 [Source Code](foss.heptapod.net/tryton/tryton)) `GPL-3.0` `Python`


### Search Engines

**[`^        back to top        ^`](#awesome-selfhosted)**

A [search engine](https://en.wikipedia.org/wiki/Search_engine_(computing)) is an 🌎 [information retrieval system](en.wikipedia.org/wiki/Information_retrieval) designed to help find information stored on a computer system. This includes 🌎 [Web search engines](en.wikipedia.org/wiki/Web_search_engine).

- 🌎 [Aleph](aleph.occrp.org/) - Tool for indexing large amounts of both documents (PDF, Word, HTML) and structured (CSV, XLS, SQL) data for easy browsing and search. It is built with investigative reporting as a primary use case.  🌎 [Demo](aleph.occrp.org/), <b><code>&nbsp;&nbsp;2297⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;327🍴</code></b> [Source Code](https://github.com/alephdata/aleph))) `MIT` `Docker/K8S`
- 🌎 [Apache Solr](lucene.apache.org/solr/) - Enterprise search platform featuring full-text search, hit highlighting, faceted search, real-time indexing, dynamic clustering, and rich document (e.g., Word, PDF) handling. (<b><code>&nbsp;&nbsp;1537⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;791🍴</code></b> [Source Code](https://github.com/apache/solr))) `Apache-2.0` `Java/Docker/K8S`
- 🌎 [Fess](fess.codelibs.org/) - Powerful and easily deployable Enterprise Search Server.  🌎 [Demo](search.n2sm.co.jp/), <b><code>&nbsp;&nbsp;1068⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;167🍴</code></b> [Source Code](https://github.com/codelibs/fess))) `Apache-2.0` `Java/Docker`
- <b><code>&nbsp;21812⭐</code></b> <b><code>&nbsp;&nbsp;2239🍴</code></b> [Jina](https://github.com/jina-ai/serve)) - Cloud-native neural search framework for any kind of data. `Apache-2.0` `Python/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Manticore Search](https://github.com/manticoresoftware/manticoresearch/)) - Full-text search and data analytics, with fast response time for small, medium and big data (alternative to Elasticsearch). `GPL-3.0` `Docker/deb/C++/K8S`
- 🌎 [MeiliSearch](www.meilisearch.com) - Ultra relevant, instant and typo-tolerant full-text search API. (<b><code>&nbsp;55105⭐</code></b> <b><code>&nbsp;&nbsp;2314🍴</code></b> [Source Code](https://github.com/meilisearch/MeiliSearch))) `MIT` `Rust/Docker/deb`
- 🌎 [OpenSearch](opensearch.org) - Distributed and RESTful search engine. (<b><code>&nbsp;12112⭐</code></b> <b><code>&nbsp;&nbsp;2359🍴</code></b> [Source Code](https://github.com/opensearch-project/OpenSearch))) `Apache-2.0` `Java/Docker/K8S/deb`
- 🌎 [SearXNG](docs.searxng.org/) `⚠` - Internet metasearch engine which aggregates results from various search services and databases (Fork of Searx). (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/searxng/searxng/))) `AGPL-3.0` `Python/Docker`
- <b><code>&nbsp;&nbsp;1176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [sist2](https://github.com/sist2app/sist2)) - Lightning-fast file system indexer and search tool. `GPL-3.0` `C/Docker`
- 🌎 [Sosse](sosse.readthedocs.io/en/stable/) - Selenium based search engine and crawler with offline archiving.  🌎 [Source Code](gitlab.com/biolds1/sosse)) `AGPL-3.0` `Python/Docker`
- 🌎 [Typesense](typesense.org) - Blazing fast, typo-tolerant open source search engine optimized for developer happiness and ease of use. (<b><code>&nbsp;24859⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;840🍴</code></b> [Source Code](https://github.com/typesense/typesense))) `GPL-3.0` `C++/Docker/K8S/deb`
- <b><code>&nbsp;&nbsp;&nbsp;994⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [Websurfx](https://github.com/neon-mmd/websurfx)) `⚠` - Aggregate results from other search engines (metasearch engine) without ads while keeping privacy and security in mind. It is extremely fast and provides a high level of customization (alternative to SearX). `AGPL-3.0` `Rust/Docker`
- <b><code>&nbsp;11169⭐</code></b> <b><code>&nbsp;&nbsp;1031🍴</code></b> [Whoogle](https://github.com/benbusby/whoogle-search)) `⚠` - A self-hosted, ad-free, privacy-respecting metasearch engine. `MIT` `Python`
- 🌎 [Yacy](yacy.net/en/index.html) - Peer based, decentralized search engine server. (<b><code>&nbsp;&nbsp;3769⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;471🍴</code></b> [Source Code](https://github.com/yacy/yacy_search_server))) `GPL-2.0` `Java/Docker/K8S`
- 🌎 [ZincSearch](zincsearch.com) - Search engine that requires minimal resources (alternative to Elasticsearch). (<b><code>&nbsp;17695⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;765🍴</code></b> [Demo](https://github.com/zinclabs/zinc#playground-server)), <b><code>&nbsp;17695⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;765🍴</code></b> [Source Code](https://github.com/zincsearch/zincsearch))) `Apache-2.0` `Go/Docker/K8S`


### Self-hosting Solutions

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for easy installation, management and configuration of self-hosted services and applications.

- <b><code>&nbsp;&nbsp;3642⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;520🍴</code></b> [Ansible-NAS](https://github.com/DaveStephens/ansible-nas)) - Build a full-featured home server with this playbook and an Ubuntu box. `MIT` `Ansible/Docker`
- 🌎 [CasaOS](casaos.zimaspace.com/) - Simple, easy-to-use, elegant Home Cloud system. (<b><code>&nbsp;32690⭐</code></b> <b><code>&nbsp;&nbsp;1815🍴</code></b> [Source Code](https://github.com/IceWhaleTech/CasaOS))) `Apache-2.0` `Go/Docker`
- 🌎 [DietPi](dietpi.com/) - Minimal Debian OS optimized for single-board computers, which allows you to easily install and manage several services for selfhosting at home. (<b><code>&nbsp;&nbsp;5743⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;538🍴</code></b> [Source Code](https://github.com/MichaIng/DietPi))) `GPL-2.0` `Shell`
- 🌎 [DockSTARTer](dockstarter.com/) - DockSTARTer helps you get started with home server apps running in Docker. (<b><code>&nbsp;&nbsp;2514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;291🍴</code></b> [Source Code](https://github.com/GhostWriters/DockSTARTer))) `MIT` `Shell`
- 🌎 [Dropserver](dropserver.org) - An application platform for your personal web services. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/teleclimber/Dropserver/))) `Apache-2.0` `Go/Deno`
- 🌎 [FreedomBox](freedombox.org/) - Community project to develop, design and promote personal servers running free software for private, personal, communications.  🌎 [Source Code](salsa.debian.org/freedombox-team/freedombox)) `AGPL-3.0` `Python/deb`
- 🌎 [HomelabOS](homelabos.com) - Offline privacy-centric data-center. Deploy over 100 services with a few commands.  🌎 [Source Code](gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- 🌎 [HomeServerHQ](www.homeserverhq.com/) - All-in-one home server infrastructure and installer. Have a fully configured email server, VPN, and public website(s) set up in less than an hour, even behind CGNAT. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Source Code](https://github.com/homeserverhq/hshq))) `GPL-3.0` `Shell`
- 🌎 [LibreServer](libreserver.org/) - Home server configuration based on Debian. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/bashrc2/libreserver))) `AGPL-3.0` `Shell`
- 🌎 [Mistborn](gitlab.com/cyber5k/mistborn) - Virtual private cloud platform and WebUI that manages self hosted services. `MIT` `Shell/Docker`
- <b><code>&nbsp;&nbsp;2845⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;314🍴</code></b> [NextCloudPi](https://github.com/nextcloud/nextcloudpi)) - Nextcloud preinstalled and preconfigured, with a text and web management interface and all the tools needed to self host private data. With installation images for Raspberry Pi, Odroid, Rock64, Docker, and a curl installer for Armbian/Debian. `GPL-2.0` `Shell/PHP`
- 🌎 [Nirvati](nirvati.org) - Easily 1-click spin up popular self-hosted apps from a convenient web interface.  🌎 [Source Code](gitlab.com/nirvati-ug/nirvati)) `AGPL-3.0` `Rust/K8S`
- 🌎 [OpenMediaVault](www.openmediavault.org/) - Network attached storage (NAS) solution based on Debian Linux. It contains services like SSH, (S)FTP, SMB/CIFS, DAAP media server, RSync, BitTorrent client and many more. (<b><code>&nbsp;&nbsp;6286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;552🍴</code></b> [Source Code](https://github.com/openmediavault/openmediavault))) `GPL-3.0` `PHP`
- 🌎 [Sandstorm](sandstorm.io/) - Personal server for running self-hosted apps easily and securely.  🌎 [Demo](demo.sandstorm.io/), <b><code>&nbsp;&nbsp;6976⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;710🍴</code></b> [Source Code](https://github.com/sandstorm-io/sandstorm))) `Apache-2.0` `C++/Shell`
- <b><code>&nbsp;&nbsp;&nbsp;399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Self Host Blocks](https://github.com/ibizaman/selfhostblocks)) `⚠` - Modular server management based on NixOS modules and focused on best practices. `AGPL-3.0` `Nix`
- 🌎 [StartOS](start9.com) - Browser-based, graphical Operating System (OS) that makes running a personal server as easy as running a personal computer. (<b><code>&nbsp;&nbsp;1378⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [Source Code](https://github.com/Start9Labs/start-os))) `MIT` `Rust`
- 🌎 [Syncloud](syncloud.org/) - Your own online file storage, social network or email server. (<b><code>&nbsp;&nbsp;&nbsp;423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Source Code](https://github.com/syncloud/platform))) `GPL-3.0` `Go/Shell`
- 🌎 [Tipi](runtipi.io/) - Homeserver manager. One command setup, one click installs for your favorites self-hosted apps. (<b><code>&nbsp;&nbsp;9110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;336🍴</code></b> [Source Code](https://github.com/runtipi/runtipi))) `GPL-3.0` `Shell`
- 🌎 [UBOS](ubos.net/) - Linux distro that runs on indie boxes (personal servers and IoT devices). Single-command installation and management of apps - Jenkins, Mediawiki, Owncloud, WordPress, etc., and other features. `GPL-3.0` `Perl`
- 🌎 [Websoft9](www.websoft9.com) `⚠` - GitOps-driven, multi-application hosting for cloud servers and home servers, one-click deployment of 200+ open source apps.  🌎 [Demo](www.websoft9.com/demo), <b><code>&nbsp;&nbsp;2076⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;314🍴</code></b> [Source Code](https://github.com/websoft9/websoft9)), 🌎 [Clients](www.websoft9.com/apps)) `LGPL-3.0` `Shell/Python`
- 🌎 [WikiSuite](wikisuite.org) - The most comprehensive and integrated Free / Libre / Open Source enterprise software suite.  🌎 [Source Code](wikisuite.org/Source-Code)) `GPL-3.0/LGPL-2.1/Apache-2.0/MPL-2.0/MPL-1.1/MIT/AGPL-3.0` `Shell/Perl/deb`
- 🌎 [xsrv](xsrv.readthedocs.io/) - Install and manage self-hosted services/applications, on your own server(s). (<b><code>&nbsp;&nbsp;&nbsp;387⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Source Code](https://github.com/nodiscc/xsrv))) `GPL-3.0` `Ansible/Shell`
- 🌎 [YunoHost](yunohost.org/) - Server operating system aiming to make self-hosting accessible to everyone.  🌎 [Demo](yunohost.org/#/try), [Source Code](https://github.com/YunoHost)) `AGPL-3.0` `Python/Shell`


### Software Development

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Software development](en.wikipedia.org/wiki/Software_development) is the process of conceiving, specifying, designing, programming, documenting, testing, and bug fixing involved in creating and maintaining applications, frameworks, or other software components.

**Please visit [Software Development - API Management](#software-development---api-management), [Software Development - Continuous Integration & Deployment](#software-development---continuous-integration--deployment), [Software Development - FaaS & Serverless](#software-development---faas--serverless), [Software Development - IDE & Tools](#software-development---ide--tools), [Software Development - Localization](#software-development---localization), [Software Development - Low Code](#software-development---low-code), [Software Development - Project Management](#software-development---project-management), [Software Development - Testing](#software-development---testing), [Software Development - Feature Toggle](#software-development---feature-toggle)**



### Software Development - API Management

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [API management](en.wikipedia.org/wiki/API_management) is the process of creating and publishing 🌎 [application programming interfaces (APIs)](en.wikipedia.org/wiki/API), enforcing their usage policies, controlling access, nurturing the subscriber community, collecting and analyzing usage statistics, and reporting on performance. 

- 🌎 [DreamFactory](www.dreamfactory.com/) - Turns any SQL/NoSQL/Structured data into Restful API. (<b><code>&nbsp;&nbsp;1726⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;343🍴</code></b> [Source Code](https://github.com/dreamfactorysoftware/dreamfactory))) `Apache-2.0` `PHP/Docker/K8S`
- 🌎 [form.io](form.io) - A REST API building platform that utilizes a drag & drop form builder, and is application framework agnostic. Contains open source and enterprise version.  🌎 [Demo](portal.form.io), [Source Code](https://github.com/formio)) `MIT` `Nodejs/Docker`
- 🌎 [Fusio](www.fusio-project.org/) - Open-source API management platform which helps to build and manage REST APIs.  🌎 [Demo](fusio-project.org/demo), <b><code>&nbsp;&nbsp;2065⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;235🍴</code></b> [Source Code](https://github.com/apioo/fusio))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Graphweaver](graphweaver.com/) - Turn multiple data sources into a single GraphQL API. (<b><code>&nbsp;&nbsp;&nbsp;544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Source Code](https://github.com/exogee-technology/graphweaver))) `MIT` `Nodejs`
- 🌎 [Hasura](hasura.io) - Fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also trigger webhooks on database events. (<b><code>&nbsp;31854⭐</code></b> <b><code>&nbsp;&nbsp;2853🍴</code></b> [Source Code](https://github.com/hasura/graphql-engine))) `Apache-2.0` `Haskell/Docker/K8S`
- 🌎 [Hoppscotch Community Edition](hoppscotch.io) - Fast and beautiful API request builder. (<b><code>&nbsp;77391⭐</code></b> <b><code>&nbsp;&nbsp;5481🍴</code></b> [Source Code](https://github.com/hoppscotch/hoppscotch))) `MIT` `Nodejs/Docker`
- 🌎 [Kong](konghq.com/kong/) - Microservice API Gateway and Platform. (<b><code>&nbsp;42443⭐</code></b> <b><code>&nbsp;&nbsp;5044🍴</code></b> [Source Code](https://github.com/Kong/kong))) `Apache-2.0` `Lua/Docker/K8S/deb`
- 🌎 [Lura](luraproject.org/) - High-performance API Gateway. (<b><code>&nbsp;&nbsp;6707⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;580🍴</code></b> [Source Code](https://github.com/luraproject/lura))) `Apache-2.0` `Go`
- 🌎 [Opik](www.comet.com/site/products/opik/) `⚠` - Evaluate, test, and ship LLM applications with a suite of observability tools to calibrate language model outputs across your dev and production lifecycle. (<b><code>&nbsp;16980⭐</code></b> <b><code>&nbsp;&nbsp;1246🍴</code></b> [Source Code](https://github.com/comet-ml/opik))) `Apache-2.0` `Docker/Python`
- 🌎 [Para](paraio.org) - Flexible and modular backend framework/server for object persistence, API development and authentication. (<b><code>&nbsp;&nbsp;&nbsp;560⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [Source Code](https://github.com/erudika/para))) `Apache-2.0` `Java/Docker`
- 🌎 [Svix](svix.com) - Open-source webhooks as a service that makes it super easy for API providers to send webhooks. (<b><code>&nbsp;&nbsp;3039⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;223🍴</code></b> [Source Code](https://github.com/svix/svix-webhooks))) `MIT` `Docker/Rust`
- 🌎 [Tyk](tyk.io) - Fast and scalable open source API Gateway. Out of the box, Tyk offers an API Management Platform with an API Gateway, API Analytics, Developer Portal and API Management Dashboard. (<b><code>&nbsp;10543⭐</code></b> <b><code>&nbsp;&nbsp;1149🍴</code></b> [Source Code](https://github.com/TykTechnologies/tyk))) `MPL-2.0` `Go/Docker/K8S`
- 🌎 [Yaade](docs.yaade.io/) - Yaade is an open-source, self-hosted, collaborative API development environment. (<b><code>&nbsp;&nbsp;1929⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Source Code](https://github.com/EsperoTech/yaade))) `MIT` `Docker`


### Software Development - Continuous Integration & Deployment

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Continuous integration](en.wikipedia.org/wiki/Continuous_integration) and 🌎 [Continuous deployment](en.wikipedia.org/wiki/Continuous_deployment) software and tools.

**Please visit <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/Continuous Integration & Continuous Deployment](https://github.com/awesome-foss/awesome-sysadmin#continuous-integration--continuous-deployment))**

_Related: [Automation](#automation)_



### Software Development - FaaS & Serverless

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Serverless computing](en.wikipedia.org/wiki/Serverless_computing), 🌎 [Function as a Service (FaaS)](en.wikipedia.org/wiki/Function_as_a_service) and 🌎 [Platform as a Service (Paas)](en.wikipedia.org/wiki/Platform_as_a_service) management software.

**Please visit <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/PaaS](https://github.com/awesome-foss/awesome-sysadmin#paas))**



### Software Development - Feature Toggle

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [feature toggle](en.wikipedia.org/wiki/Feature_toggle) in software development provides an alternative to maintaining multiple feature branches in source code.

_Related: [Software Development - IDE & Tools](#software-development---ide--tools)_

- 🌎 [Featbit](www.featbit.co/) - Enterprise-grade feature flag platform that you can self-host. (<b><code>&nbsp;&nbsp;1715⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [Source Code](https://github.com/featbit/featbit))) `MIT` `Docker/K8S`
- 🌎 [Flagsmith](flagsmith.com) - Dashboard, API and SDKs for adding Feature Flags to your applications (alternative to LaunchDarkly). (<b><code>&nbsp;&nbsp;6141⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;466🍴</code></b> [Source Code](https://github.com/flagsmith/flagsmith))) `BSD-3-Clause` `Docker/K8S`
- 🌎 [Flipt](flipt.io) - Feature flag solution with support for multiple data backends (alternative to LaunchDarkly). (<b><code>&nbsp;&nbsp;4668⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;276🍴</code></b> [Source Code](https://github.com/flipt-io/flipt))) `GPL-3.0` `Docker/K8S/Go`
- 🌎 [GO Feature Flag](gofeatureflag.org) - Simple, complete, and lightweight feature flag solution (alternative to LaunchDarkly). (<b><code>&nbsp;&nbsp;1878⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;188🍴</code></b> [Source Code](https://github.com/thomaspoignant/go-feature-flag))) `MIT` `Go`


### Software Development - IDE & Tools

**[`^        back to top        ^`](#awesome-selfhosted)**

An 🌎 [integrated development environment (IDE)](en.wikipedia.org/wiki/Integrated_development_environment) is a software application that provides comprehensive facilities to computer programmers for software development.

_Related: [Software Development - Low Code](#software-development---low-code)_

- 🌎 [Atheos](www.atheos.io) - Web-based IDE framework with a small footprint and minimal requirements, continued from Codiad. (<b><code>&nbsp;&nbsp;&nbsp;637⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Source Code](https://github.com/Atheos/Atheos))) `MIT` `PHP/Docker`
- <b><code>&nbsp;75535⭐</code></b> <b><code>&nbsp;&nbsp;6426🍴</code></b> [code-server](https://github.com/coder/code-server)) - VS Code in the browser, hosted on a remote server. `MIT` `Nodejs/Docker`
- 🌎 [Coder](coder.com/) - Remote development machines on your own infrastructure. (<b><code>&nbsp;11820⭐</code></b> <b><code>&nbsp;&nbsp;1122🍴</code></b> [Source Code](https://github.com/coder/coder))) `AGPL-3.0` `Go/Docker/K8S/deb`
- 🌎 [Eclipse Che](www.eclipse.org/che/) - Open source workspace server and cloud IDE. (<b><code>&nbsp;&nbsp;7108⭐</code></b> <b><code>&nbsp;&nbsp;1197🍴</code></b> [Source Code](https://github.com/eclipse-che/che))) `EPL-1.0` `Docker/Java`
- 🌎 [Judge0 CE](judge0.com) - API to compile and run source code. (<b><code>&nbsp;&nbsp;3730⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;770🍴</code></b> [Source Code](https://github.com/judge0/judge0))) `GPL-3.0` `Docker`
- 🌎 [JupyterLab](jupyterlab.readthedocs.io/en/stable/) - Web-based environment for interactive and reproducible computing.  🌎 [Demo](mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/jupyterlab/jupyterlab/))) `BSD-3-Clause` `Python/Docker`
- 🌎 [Langfuse](langfuse.com) - LLM engineering platform for model tracing, prompt management, and application evaluation. Langfuse helps teams collaboratively debug, analyze, and iterate on their LLM applications such as chatbots or AI agents.  🌎 [Demo](langfuse.com/docs/demo), <b><code>&nbsp;19740⭐</code></b> <b><code>&nbsp;&nbsp;1934🍴</code></b> [Source Code](https://github.com/langfuse/langfuse)), 🌎 [Clients](langfuse.com/docs/integrations/overview)) `MIT` `Docker`
- 🌎 [LiveCodes](livecodes.io/docs/features/self-hosting) `⚠` - Feature-rich client-side code playground for React, Vue, Svelte, Solid, Typescript, Python, Go, Ruby, PHP and 90+ other languages.  🌎 [Demo](livecodes.io), <b><code>&nbsp;&nbsp;1329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [Source Code](https://github.com/live-codes/livecodes))) `MIT` `Nodejs`
- 🌎 [Lowdefy](www.lowdefy.com/) - Build internal tools, BI dashboards, admin panels, CRUD apps and workflows in minutes using YAML / JSON on an self-hosted, open-source platform. Connect to your data sources, host via Serverless, Netlify or Docker. (<b><code>&nbsp;&nbsp;2921⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [Source Code](https://github.com/lowdefy/lowdefy))) `Apache-2.0` `Nodejs/Docker`
- 🌎 [RStudio Server](www.rstudio.com/products/rstudio/#Server) - Web browser based IDE for R. (<b><code>&nbsp;&nbsp;4924⭐</code></b> <b><code>&nbsp;&nbsp;1151🍴</code></b> [Source Code](https://github.com/rstudio/rstudio))) `AGPL-3.0` `Java/C++`
- 🌎 [Wakapi](wakapi.dev/) - Tracking tool for coding statistics, compatible with WakaTime. (<b><code>&nbsp;&nbsp;4014⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;256🍴</code></b> [Source Code](https://github.com/muety/wakapi))) `GPL-3.0` `Go/Docker`


### Software Development - Localization

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Localization](en.wikipedia.org/wiki/Internationalization_and_localization) is the process of adapting code and software to other languages.

- 🌎 [Accent](www.accent.reviews/) - Developer-oriented translation tool. (<b><code>&nbsp;&nbsp;1459⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [Source Code](https://github.com/mirego/accent))) `BSD-3-Clause` `Elixir/Docker`
- 🌎 [Tolgee](tolgee.io) - Developer & translator friendly web-based localization platform enabling users to translate directly in the app they develop. (<b><code>&nbsp;&nbsp;3701⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;321🍴</code></b> [Source Code](https://github.com/tolgee/tolgee-platform))) `Apache-2.0` `Docker/Java`
- 🌎 [Traduora](traduora.co) - Translation management platform for teams. (<b><code>&nbsp;&nbsp;2099⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;222🍴</code></b> [Source Code](https://github.com/ever-co/ever-traduora))) `AGPL-3.0` `Docker/K8S/Nodejs`
- 🌎 [Weblate](weblate.org) - Web-based translation tool with tight version control integration. (<b><code>&nbsp;&nbsp;5632⭐</code></b> <b><code>&nbsp;&nbsp;1210🍴</code></b> [Source Code](https://github.com/WeblateOrg/weblate))) `GPL-3.0` `Python/Docker/K8S`


### Software Development - Low Code

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [low-code](en.wikipedia.org/wiki/Low-code_development_platform) development platform (LCDP) provides a development environment used to create application software through a graphical user interface.

_Related: [Software Development - IDE & Tools](#software-development---ide--tools)_

- 🌎 [Appsmith](www.appsmith.com/) - Build admin panels, CRUD apps and workflows. Build everything you need, 10x faster. (<b><code>&nbsp;38745⭐</code></b> <b><code>&nbsp;&nbsp;4408🍴</code></b> [Source Code](https://github.com/appsmithorg/appsmith))) `Apache-2.0` `Java/Docker/K8S`
- 🌎 [Appwrite](appwrite.io) - End to end backend server for web, native, and mobile developers 🚀. (<b><code>&nbsp;54074⭐</code></b> <b><code>&nbsp;&nbsp;4898🍴</code></b> [Source Code](https://github.com/appwrite/appwrite))) `BSD-3-Clause` `Docker`
- <b><code>&nbsp;&nbsp;1881⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [Dashpress](https://github.com/dashpresshq/dashpress)) - Generate fully functional admin apps in seconds from your database information, with a single command. `AGPL-3.0` `Nodejs/Docker`
- 🌎 [Halo](www.halo.run) - A powerful and easy-to-use website building tool (documentation in Chinese).  🌎 [Demo](demo.halo.run), <b><code>&nbsp;37558⭐</code></b> <b><code>&nbsp;10165🍴</code></b> [Source Code](https://github.com/halo-dev/halo)), <b><code>&nbsp;&nbsp;&nbsp;599⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [Clients](https://github.com/halo-sigs/awesome-halo))) `GPL-3.0` `Java/Docker`
- 🌎 [Manifest](manifest.build) - Complete backend that fits into 1 YAML file.  🌎 [Demo](manifest.new), <b><code>&nbsp;&nbsp;3243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [Source Code](https://github.com/mnfst/manifest))) `MIT` `Nodejs`
- 🌎 [PocketBase](pocketbase.io/) - Backend for your next SaaS and Mobile app in one file. (<b><code>&nbsp;54628⭐</code></b> <b><code>&nbsp;&nbsp;2975🍴</code></b> [Source Code](https://github.com/pocketbase/pocketbase))) `MIT` `Go/Docker`
- 🌎 [Saltcorn](saltcorn.com/) - No-code database application builder for web and mobile applications. One platform for user interface, data backend, durable workflows, email, PDF generation, and AI applications. (<b><code>&nbsp;&nbsp;1975⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;343🍴</code></b> [Source Code](https://github.com/saltcorn/saltcorn))) `MIT` `Docker/Nodejs`
- 🌎 [SQLPage](sql-page.com) - SQL-only dynamic website builder. (<b><code>&nbsp;&nbsp;2404⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;160🍴</code></b> [Source Code](https://github.com/sqlpage/SQLPage))) `MIT` `Rust/Docker`
- 🌎 [ToolJet](tooljet.io/) - Low-code framework to build & deploy internal tools with minimal engineering effort (alternative to Retool and Mendix). (<b><code>&nbsp;37078⭐</code></b> <b><code>&nbsp;&nbsp;4910🍴</code></b> [Source Code](https://github.com/ToolJet/ToolJet))) `GPL-3.0` `Nodejs/Docker/K8S`
- 🌎 [TrailBase](trailbase.io/) - Open, sub-millisecond, single-executable FireBase alternative with type-safe REST & realtime APIs, built-in JS/TS runtime, auth & admin UI.  🌎 [Demo](demo.trailbase.io), <b><code>&nbsp;&nbsp;4314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [Source Code](https://github.com/trailbaseio/trailbase))) `OSL-3.0` `Rust/Docker`


### Software Development - Project Management

**[`^        back to top        ^`](#awesome-selfhosted)**

Tools and software for 🌎 [software project management](en.wikipedia.org/wiki/Software_project_management).

_Related: [Ticketing](#ticketing), [Task Management & To-do Lists](#task-management--to-do-lists)_

- 🌎 [Cgit](git.zx2c4.com/cgit/about/) - Fast lightweight web interface for git repositories.  🌎 [Source Code](git.zx2c4.com/cgit/tree/)) `GPL-2.0` `C`
- 🌎 [Forgejo](forgejo.org) - A lightweight software forge focused on scaling, federation, and privacy (fork of Gitea).  🌎 [Demo](next.forgejo.org), 🌎 [Source Code](codeberg.org/forgejo/forgejo/), 🌎 [Clients](codeberg.org/forgejo-contrib/delightful-forgejo)) `MIT` `Docker/Go`
- 🌎 [Fossil](www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - Distributed version control system featuring wiki and bug tracker. `BSD-2-Clause-FreeBSD` `C`
- 🌎 [Gerrit](www.gerritcodereview.com/) - Code review and project management tool for Git-based projects. (<b><code>&nbsp;&nbsp;1134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [Source Code](https://github.com/GerritCodeReview/gerrit))) `Apache-2.0` `Java/Docker`
- 🌎 [gitbucket](gitbucket.github.io/) - Git platform powered with easy installation, high extensibility & GitHub API compatibility (alternative to GitHub). (<b><code>&nbsp;&nbsp;9332⭐</code></b> <b><code>&nbsp;&nbsp;1264🍴</code></b> [Source Code](https://github.com/gitbucket/gitbucket))) `Apache-2.0` `Scala/Java`
- 🌎 [Gitea](gitea.com) - Git with a cup of tea! Painless self-hosted all-in-one software development service, including Git hosting, code review, team collaboration, package registry and CI/CD.  🌎 [Demo](demo.gitea.com), <b><code>&nbsp;52730⭐</code></b> <b><code>&nbsp;&nbsp;6279🍴</code></b> [Source Code](https://github.com/go-gitea/gitea))) `MIT` `Go/Docker/K8S`
- 🌎 [GitLab](about.gitlab.com) - Self Hosted Git repository management, code reviews, issue tracking, activity feeds and wikis.  🌎 [Demo](gitlab.com/), 🌎 [Source Code](gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby/deb/Docker/K8S`
- 🌎 [Gogs](gogs.io/) - Painless self-hosted Git Service written in Go. (<b><code>&nbsp;47381⭐</code></b> <b><code>&nbsp;&nbsp;5074🍴</code></b> [Source Code](https://github.com/gogs/gogs))) `MIT` `Go`
- 🌎 [Huly](huly.io) - All-in-one project management platform (alternative to Linear, Jira, Slack, Notion, Motion).  🌎 [Demo](app.huly.io), <b><code>&nbsp;23977⭐</code></b> <b><code>&nbsp;&nbsp;1666🍴</code></b> [Source Code](https://github.com/hcengineering/platform))) `EPL-2.0` `Docker/K8S/Nodejs`
- 🌎 [Kallithea](kallithea-scm.org/) - Source code management system that supports two leading version control systems, Mercurial and Git, with a web interface.  🌎 [Source Code](kallithea-scm.org/repos/kallithea)) `GPL-3.0` `Python`
- 🌎 [Kaneo](kaneo.app/) - Project management platform focused on simplicity and efficiency.  🌎 [Demo](demo.kaneo.app/), <b><code>&nbsp;&nbsp;3010⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;234🍴</code></b> [Source Code](https://github.com/usekaneo/kaneo))) `MIT` `K8S/Docker`
- 🌎 [Leantime](leantime.io) - Lean project management system for small teams and startups helping to manage projects from ideation through delivery. (<b><code>&nbsp;&nbsp;8799⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;861🍴</code></b> [Source Code](https://github.com/leantime/leantime))) `AGPL-3.0` `PHP/Docker`
- 🌎 [Mergeable](www.usemergeable.dev) `⚠` - A better inbox for GitHub pull requests.  🌎 [Demo](app.usemergeable.dev), <b><code>&nbsp;&nbsp;&nbsp;102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/pvcnt/mergeable))) `MIT` `Nodejs/Docker/K8S`
- 🌎 [Mindwendel](www.mindwendel.com/) - Brainstorm and upvote ideas and thoughts within your team.  🌎 [Demo](www.mindwendel.com), <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Source Code](https://github.com/b310-digital/mindwendel))) `AGPL-3.0` `Docker/Elixir`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [minimal-git-server](https://github.com/mcarbonne/minimal-git-server)) - Lightweight git server with a basic CLI to manage repositories, supporting multiple accounts and running in a container. `MIT` `Docker`
- 🌎 [Octobox](octobox.io/) `⚠` - Take back control of your GitHub Notifications. (<b><code>&nbsp;&nbsp;4435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;347🍴</code></b> [Source Code](https://github.com/octobox/octobox))) `AGPL-3.0` `Ruby/Docker`
- 🌎 [OneDev](onedev.io/) - All-In-One DevOps Platform. With Git Management, Issue Tracking, and CI/CD. Simple yet Powerful.  🌎 [Source Code](code.onedev.io/projects/160)) `MIT` `Java/Docker/K8S`
- 🌎 [OpenProject](www.openproject.org) - Manage your projects, tasks and goals. Collaborate via work packages and link them to your pull requests on Github. (<b><code>&nbsp;13441⭐</code></b> <b><code>&nbsp;&nbsp;2969🍴</code></b> [Source Code](https://github.com/opf/openproject))) `GPL-3.0` `Ruby/deb/Docker`
- 🌎 [Pagure](pagure.io/pagure) - Lightweight, powerful, and flexible git-centric forge with features laying the foundation for federated and decentralized development.  🌎 [Demo](pagure.io/)) `GPL-2.0` `Docker/Python/deb`
- 🌎 [Phorge](we.phorge.it/) - Community-driven platform for collaborating, managing, organizing and reviewing software development projects.  🌎 [Source Code](we.phorge.it/source/phorge/)) `Apache-2.0` `PHP`
- 🌎 [Plane](plane.so) - Track issues, epics, and product roadmaps in the simplest way possible (alternative to JIRA, Linear and Height).  🌎 [Demo](app.plane.so), <b><code>&nbsp;41892⭐</code></b> <b><code>&nbsp;&nbsp;3078🍴</code></b> [Source Code](https://github.com/makeplane/plane))) `AGPL-3.0` `Docker`
- 🌎 [ProjeQtOr](www.projeqtor.org/) - Complete, mature, multi-user project management system with extensive functionality for all phases of a project.  🌎 [Demo](demo.projeqtor.org/), 🌎 [Source Code](sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
- 🌎 [Redmine](www.redmine.org/) - Flexible project management web application.  🌎 [Source Code](svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- 🌎 [Review Board](www.reviewboard.org/) - Extensible and friendly code review tool for projects and companies of all sizes.  🌎 [Demo](demo.reviewboard.org/), <b><code>&nbsp;&nbsp;1685⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;436🍴</code></b> [Source Code](https://github.com/reviewboard/reviewboard))) `MIT` `Python/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [rgit](https://github.com/w4/rgit)) - Ultra-fast & lightweight cgit clone. `WTFPL` `Rust/Docker`
- 🌎 [RhodeCode](rhodecode.com/) - Unify and simplify repository management for Git, Subversion, and Mercurial.  🌎 [Source Code](code.rhodecode.com/)) `AGPL-3.0` `Python`
- 🌎 [Rukovoditel](www.rukovoditel.net/) - Configurable open source project management, web-based application.  🌎 [Source Code](www.rukovoditel.net/download.php)) `GPL-2.0` `PHP`
- 🌎 [SCM Manager](www.scm-manager.org/) - The easiest way to share and manage your Git, Mercurial and Subversion repositories over http. (<b><code>&nbsp;&nbsp;&nbsp;163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Source Code](https://github.com/scm-manager/scm-manager))) `BSD-3-Clause` `Java/deb/Docker/K8S`
- 🌎 [Smederee](smeder.ee) - A frugal platform which is dedicated to help people build great software together leveraging the power of the Darcs version control system.  🌎 [Source Code](smeder.ee/~jan0sch/smederee)) `AGPL-3.0` `Scala`
- 🌎 [Sourcehut](sourcehut.org/) - A full web git interface with no javascript.  🌎 [Demo](sr.ht/), 🌎 [Source Code](git.sr.ht/~sircmpwn/git.sr.ht/tree)) `GPL-2.0` `Go`
- 🌎 [Taiga](www.taiga.io/) - Agile Project Management Tool based on the Kanban and Scrum methods. ([Source Code](https://github.com/kaleidos-ventures)) `MPL-2.0` `Docker/Python/Nodejs`
- 🌎 [Titra](titra.io/) - Time-tracking solution for freelancers and small teams. (<b><code>&nbsp;&nbsp;&nbsp;452⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [Source Code](https://github.com/kromitgmbh/titra))) `GPL-3.0` `Javascript/Docker`
- 🌎 [Trac](trac.edgewall.org/) - Trac is an enhanced wiki and issue tracking system for software development projects. `BSD-3-Clause` `Python/deb`
- 🌎 [Traq](traq.io/) - Project management and issue tracking system written in PHP. (<b><code>&nbsp;&nbsp;&nbsp;197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Source Code](https://github.com/nirix/traq))) `GPL-3.0` `PHP/Nodejs`
- 🌎 [Tuleap](www.tuleap.org/) - Tuleap is a libre suite to plan, track, code and collaborate on software projects.  🌎 [Source Code](tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- 🌎 [UVDesk](www.uvdesk.com/) - UVDesk community is a service oriented, event driven extensible opensource helpdesk system that can be used by your organization to provide efficient support to your clients effortlessly whichever way you imagine.  🌎 [Demo](demo.uvdesk.com/), <b><code>&nbsp;17024⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;551🍴</code></b> [Source Code](https://github.com/uvdesk/community-skeleton))) `MIT` `PHP`
- 🌎 [ZenTao](www.zentao.pm/) - An agile(scrum) project management system/tool. (<b><code>&nbsp;&nbsp;1527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;362🍴</code></b> [Source Code](https://github.com/easysoft/zentaopms))) `AGPL-3.0` `PHP`


### Software Development - Testing

**[`^        back to top        ^`](#awesome-selfhosted)**

Tools and software for 🌎 [software testing](en.wikipedia.org/wiki/Software_testing).

- 🌎 [Bencher](bencher.dev/) - Suite of continuous benchmarking tools designed to catch performance regressions in CI. (<b><code>&nbsp;&nbsp;&nbsp;782⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Source Code](https://github.com/bencherdev/bencher))) `MIT/Apache-2.0` `Rust`
- <b><code>&nbsp;&nbsp;&nbsp;358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [WebHook Tester](https://github.com/tarampampam/webhook-tester)) - Powerful tool for testing WebHooks and more. `MIT` `Docker/Go/deb/K8S`


### Static Site Generators

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Static site generators](en.wikipedia.org/wiki/Web_template_system#Static_site_generators) generate full static HTML websites based on raw data, plain text files and a set of templates. 

**Please visit 🌎 [staticsitegenerators.bevry.me](staticsitegenerators.bevry.me), 🌎 [staticgen.com](www.staticgen.com)**

_Related: [Blogging Platforms](#blogging-platforms), [Photo Galleries](#photo-galleries), [Content Management Systems (CMS)](#content-management-systems-cms)_



### Status / Uptime pages

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Uptime](en.wikipedia.org/wiki/Uptime) is a measure of system reliability, expressed as the percentage of time a machine, typically a computer, has been working and available. 

_Related: [Monitoring](#monitoring)_

- 🌎 [cState](cstate.netlify.app/) - Static status page for hyperfast Hugo. Clean design, minimal JS, super light HTML/CSS, high customization, optional admin panel, read-only API, IE8+. Best used with Netlify, Docker.  🌎 [Demo](cstate.mnts.lt/), <b><code>&nbsp;&nbsp;2811⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;246🍴</code></b> [Source Code](https://github.com/cstate/cstate))) `MIT` `Go`
- 🌎 [Gatus](gatus.io/) - Automated service health dashboard.  🌎 [Demo](status.twin.sh), <b><code>&nbsp;&nbsp;9380⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;628🍴</code></b> [Source Code](https://github.com/TwiN/gatus))) `Apache-2.0` `Docker/K8S`
- 🌎 [kener](kener.ing/) - Status page with incident management, easy to use and customize.  🌎 [Demo](kener.ing/), <b><code>&nbsp;&nbsp;4606⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [Source Code](https://github.com/rajnandan1/kener))) `MIT` `Nodejs/Docker`
- 🌎 [Kuvasz Uptime](kuvasz-uptime.dev) - Performant, stable uptime & SSL monitoring service with brandable status pages, IAC support, Prometheus integration and a complete REST API.  🌎 [Demo](kuvasz-uptime.dev/demo/), <b><code>&nbsp;&nbsp;&nbsp;475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Source Code](https://github.com/kuvasz-uptime/kuvasz))) `Apache-2.0` `Docker`
- 🌎 [StatPing.ng](statping-ng.github.io/) - An easy to use Status Page for your websites and applications. Statping will automatically fetch the application and render a beautiful status page with tons of features for you to build an even better status page. (<b><code>&nbsp;&nbsp;1894⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;181🍴</code></b> [Source Code](https://github.com/statping-ng/statping-ng))) `GPL-3.0` `Docker/Go`
- 🌎 [Uptime Kuma](uptime.kuma.pet/) - Self-hosted website monitoring tool like "Uptime Robot".  🌎 [Demo](demo.kuma.pet), <b><code>&nbsp;80189⭐</code></b> <b><code>&nbsp;&nbsp;7149🍴</code></b> [Source Code](https://github.com/louislam/uptime-kuma))) `MIT` `Docker/Nodejs`


### Task Management & To-do Lists

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Task management](en.wikipedia.org/wiki/Task_management#Task_management_software) software.

_Related: [Software Development - Project Management](#software-development---project-management), [Ticketing](#ticketing)_

- 🌎 [4ga Boards](4gaboards.com) - Straightforward realtime kanban boards management for intuitive task tracking. Featuring an elegant dark mode, collapsible todo lists, and multitasking tools to supercharge your team's productivity.  🌎 [Demo](demo.4gaboards.com), <b><code>&nbsp;&nbsp;&nbsp;425⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Source Code](https://github.com/RARgames/4gaBoards))) `MIT` `Nodejs/Docker/K8S`
- 🌎 [AppFlowy](appflowy.io/) - Build detailed lists of to-do’s for different projects while tracking the status of each one. Open Source Notion Alternative. (<b><code>&nbsp;67143⭐</code></b> <b><code>&nbsp;&nbsp;4802🍴</code></b> [Source Code](https://github.com/AppFlowy-IO/appflowy))) `AGPL-3.0` `Rust/Dart/Docker`
- 🌎 [Donetick](donetick.com) - Task and chore management tool for personal and family use, with advanced scheduling, flexible assignment, and group sharing capabilities, detailed history, automation via API, simple and modern design.  🌎 [Demo](app.donetick.com/), <b><code>&nbsp;&nbsp;1605⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/donetick/donetick))) `AGPL-3.0` `Go/Docker`
- 🌎 [Focalboard](www.focalboard.com/) - Define, organize, track and manage work across individuals and teams (alternative to Trello, Notion and Asana). (<b><code>&nbsp;25629⭐</code></b> <b><code>&nbsp;&nbsp;2438🍴</code></b> [Source Code](https://github.com/mattermost-community/focalboard)), 🌎 [Clients](www.focalboard.com/download/personal-edition/desktop/)) `MIT/AGPL-3.0/Apache-2.0` `Nodejs/Go/Docker`
- 🌎 [Kanboard](kanboard.org/) - Simple visual task board. (<b><code>&nbsp;&nbsp;9357⭐</code></b> <b><code>&nbsp;&nbsp;1932🍴</code></b> [Source Code](https://github.com/kanboard/kanboard))) `MIT` `PHP`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Listaway](https://github.com/jeffrpowell/listaway/)) - List management app for creating and publicly sharing lists of items. Supports auth, admin tools, item notes and priorities, and opt-in public read-only links with randomized URLs (alternative to Amazon Lists). (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Source Code](https://github.com/jeffrpowell/listaway))) `MIT` `Docker`
- 🌎 [myTinyTodo](www.mytinytodo.net/) - Simple way to manage your todo list in AJAX style. Uses PHP, jQuery, SQLite/MySQL. GTD compliant.  🌎 [Demo](www.mytinytodo.net/demo/), <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/maxpozdeev/mytinytodo/))) `GPL-2.0` `PHP`
- <b><code>&nbsp;&nbsp;4102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;270🍴</code></b> [Nullboard](https://github.com/apankrat/nullboard)) - Single-page minimalist kanban board; compact, highly readable and quick to use.  🌎 [Demo](nullboard.io/preview)) `BSD-2-Clause` `Javascript`
- <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Our Shopping List](https://github.com/nanawel/our-shopping-list)) - Simple shared list application including shopping lists and any other small todo-list that needs to be used collaboratively.  🌎 [Demo](osl.lanterne-rouge.info/)) `AGPL-3.0` `Docker`
- 🌎 [Planka](planka.app/) - Realtime kanban board for workgroups (alternative to Trello).  🌎 [Demo](plankanban.github.io/planka/#/), <b><code>&nbsp;11244⭐</code></b> <b><code>&nbsp;&nbsp;1145🍴</code></b> [Source Code](https://github.com/plankanban/planka))) `AGPL-3.0` `Nodejs/Docker/K8S`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Task Keeper](https://github.com/nymanjens/piga)) - List editor for power users, backed by a self-hosted server. `Apache-2.0` `Scala`
- <b><code>&nbsp;&nbsp;1949⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Tasks.md](https://github.com/BaldissaraMatheus/Tasks.md)) - A self-hosted, file based task management board that supports Markdown syntax. `MIT` `Docker`
- 🌎 [Taskwarrior](taskwarrior.org/) - Taskwarrior is Free and Open Source Software that manages your TODO list from your command line. It is flexible, fast, efficient, and unobtrusive. It does its job then gets out of your way.  🌎 [Source Code](taskwarrior.org/download/#git)) `MIT` `C++`
- 🌎 [Tracks](www.getontracks.org/) - Web-based application to help you implement David Allen’s 🌎 [Getting Things Done™](en.wikipedia.org/wiki/Getting_Things_Done) methodology. (<b><code>&nbsp;&nbsp;1217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;536🍴</code></b> [Source Code](https://github.com/TracksApp/tracks))) `GPL-2.0` `Ruby`
- 🌎 [Vikunja](vikunja.io/) - The to-do app to organize your life.  🌎 [Demo](try.vikunja.io/login), 🌎 [Source Code](kolaente.dev/vikunja/)) `GPL-3.0` `Go`
- 🌎 [Wekan](wekan.github.io/) - Open-source Trello-like kanban. (<b><code>&nbsp;20768⭐</code></b> <b><code>&nbsp;&nbsp;2956🍴</code></b> [Source Code](https://github.com/wekan/wekan))) `MIT` `Nodejs`


### Ticketing

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Helpdesk](en.wikipedia.org/wiki/Help_desk_software), 🌎 [bug](en.wikipedia.org/wiki/Bug_tracking_system) and 🌎 [issue](en.wikipedia.org/wiki/Issue_tracking_system) tracking software to help the tracking of user requests, bugs and missing features.

_Related: [Task Management & To-do Lists](#task-management--to-do-lists), [Software Development - Project Management](#software-development---project-management)_

- 🌎 [Bugzilla](www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project. (<b><code>&nbsp;&nbsp;&nbsp;800⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;310🍴</code></b> [Source Code](https://github.com/bugzilla/bugzilla))) `MPL-2.0` `Perl`
- 🌎 [Frappe Helpdesk](frappe.io/helpdesk) - Helpdesk software which helps you streamline your company's support, offers an easy setup, clean user interface, and automation tools to resolve customer queries efficiently. (<b><code>&nbsp;&nbsp;2834⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;635🍴</code></b> [Source Code](https://github.com/frappe/helpdesk))) `AGPL-3.0` `Docker`
- 🌎 [FreeScout](freescout.net/) - Email-based customer support application, help desk and shared mailbox (alternative to Zendesk and Help Scout).  🌎 [Demo](demo.freescout.net/login), <b><code>&nbsp;&nbsp;3971⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;612🍴</code></b> [Source Code](https://github.com/freescout-help-desk/freescout))) `AGPL-3.0` `PHP/Docker`
- 🌎 [GlitchTip](glitchtip.com) - Error tracking app to collect errors reported by your app.  🌎 [Source Code](gitlab.com/glitchtip/glitchtip)) `MIT` `Python/Docker/K8S`
- 🌎 [ITFlow](itflow.org) - Client IT documentation, ticketing, invoicing and accounting for MSPs (Managed Service Providers).  🌎 [Demo](demo.itflow.org), <b><code>&nbsp;&nbsp;&nbsp;853⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [Source Code](https://github.com/itflow-org/itflow))) `GPL-3.0` `PHP`
- 🌎 [Libredesk](libredesk.io/) - Modern customer support desk. Single binary app. (<b><code>&nbsp;&nbsp;1858⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [Source Code](https://github.com/abhinavxd/libredesk))) `AGPL-3.0` `Docker/Go/Nodejs`
- 🌎 [MantisBT](www.mantisbt.org/) - Bug tracker, fits best for software development.  🌎 [Demo](www.mantisbt.org/bugs/my_view_page.php), <b><code>&nbsp;&nbsp;1739⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;747🍴</code></b> [Source Code](https://github.com/mantisbt/mantisbt))) `GPL-2.0` `PHP`
- 🌎 [OTOBO](otobo.io/en/) - Flexible web-based ticketing system used for customer service, help desk, IT service management.  🌎 [Demo](otobo.io/en/service-management-plattform/otobo-demo/), <b><code>&nbsp;&nbsp;&nbsp;312⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Source Code](https://github.com/RotherOSS/otobo))) `GPL-3.0` `Perl/Docker`
- 🌎 [Request Tracker](www.bestpractical.com/rt/) - Enterprise-grade issue tracking system. (<b><code>&nbsp;&nbsp;1084⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;276🍴</code></b> [Source Code](https://github.com/bestpractical/rt))) `GPL-2.0` `Perl`
- 🌎 [Roundup Issue Tracker](www.roundup-tracker.org/) - Simple-to-use and -install issue tracking system with command-line, web, REST, XML-RPC, and e-mail interfaces. Designed with flexibility in mind - not just another bug tracker.  🌎 [Source Code](www.roundup-tracker.org/code.html)) `MIT/ZPL-2.0` `Python/Docker`
- 🌎 [Zammad](zammad.org/) - Easy to use but powerful open-source support and ticketing system. (<b><code>&nbsp;&nbsp;5290⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;914🍴</code></b> [Source Code](https://github.com/zammad/zammad))) `AGPL-3.0` `Ruby/deb`


### Time Tracking

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [Time-tracking software](en.wikipedia.org/wiki/Time-tracking_software) is a category of computer software that allows its users to record time spent on tasks or projects.

- 🌎 [ActivityWatch](activitywatch.net) - Automatically track how you spend time on your devices. (<b><code>&nbsp;16221⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;789🍴</code></b> [Source Code](https://github.com/ActivityWatch/activitywatch))) `MPL-2.0` `Python`
- <b><code>&nbsp;&nbsp;1600⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [Beaver Habit Tracker](https://github.com/daya0576/beaverhabits)) - Habit tracking app to save your precious moments in your fleeting life.  🌎 [Demo](beaverhabits.com/demo)) `BSD-3-Clause` `Docker`
- 🌎 [Ever Gauzy](gauzy.co) - Open business management platform for collaborative, on-demand and sharing economies (ERP/CRM/HRM/ATS/PM).  🌎 [Demo](demo.gauzy.co), <b><code>&nbsp;&nbsp;3353⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;706🍴</code></b> [Source Code](https://github.com/ever-co/ever-gauzy))) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Kimai](www.kimai.org/) - Track work time and print out a summary of your activities on demand.  🌎 [Demo](www.kimai.org/demo/), <b><code>&nbsp;&nbsp;4333⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;711🍴</code></b> [Source Code](https://github.com/kimai/kimai))) `AGPL-3.0` `PHP`
- 🌎 [solidtime](www.solidtime.io) - Modern time tracking application for freelancers and agencies. (<b><code>&nbsp;&nbsp;7757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;399🍴</code></b> [Source Code](https://github.com/solidtime-io/solidtime))) `AGPL-3.0` `Docker`
- 🌎 [TimeTagger](timetagger.app) - An open source time-tracker based on an interactive timeline and powerful reporting.  🌎 [Demo](timetagger.app/app/demo), <b><code>&nbsp;&nbsp;1593⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [Source Code](https://github.com/almarklein/timetagger))) `GPL-3.0` `Python`
- 🌎 [Traggo](traggo.net/) - Traggo is a tag-based time tracking tool. In Traggo there are no tasks, only tagged time spans. (<b><code>&nbsp;&nbsp;1495⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Source Code](https://github.com/traggo/server))) `GPL-3.0` `Docker/Go`
- 🌎 [Ziit](ziit.app) - The Swiss army knife of code time tracking (alternative to WakaTime). (<b><code>&nbsp;&nbsp;&nbsp;178⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Source Code](https://github.com/0pandadev/ziit))) `AGPL-3.0` `Docker`


### URL Shorteners

**[`^        back to top        ^`](#awesome-selfhosted)**
 🌎 [URL shortening](en.wikipedia.org/wiki/URL_shortening) is the action of shortening a 🌎 [URL](en.wikipedia.org/wiki/Uniform_Resource_Locator) to make it substantially shorter and still direct to the required page. Before hosting one, please see 🌎 [disadvantages](en.wikipedia.org/wiki/URL_shortening#Disadvantages) of URL shorteners.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [bit](https://github.com/sjdonado/bit)) - Fast, lightweight, resource-efficient, compiled URL shortener. `MIT` `Docker/Crystal`
- <b><code>&nbsp;&nbsp;&nbsp;668⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Chhoto URL](https://github.com/SinTan1729/chhoto-url)) - Simple, lightning-fast URL shortener with no bloat (fork of simply-shorten). (<b><code>&nbsp;&nbsp;&nbsp;668⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Demo](https://github.com/SinTan1729/chhoto-url?tab=readme-ov-file#demo)), <b><code>&nbsp;&nbsp;&nbsp;668⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Clients](https://github.com/SinTan1729/chhoto-url/blob/main/TOOLS.md))) `MIT` `Rust/Docker`
- 🌎 [clink](git.crueter.xyz/crueter/clink) - A super-minimal link shortening service written in pure C, focusing on small executable size, portability, and ease of configuration.  🌎 [Demo](short.crueter.xyz)) `AGPL-3.0` `C`
- 🌎 [Flink](gitlab.com/rtraceio/web/flink) - Create QR Codes, embeddable link previews for your website and crawls/scrapes metadata.  🌎 [Demo](flink.is)) `MIT` `Docker`
- 🌎 [Kutt](kutt.it) - Modern URL shortener with support for custom domains and custom URLs.  🌎 [Demo](kutt.it), <b><code>&nbsp;10408⭐</code></b> <b><code>&nbsp;&nbsp;1396🍴</code></b> [Source Code](https://github.com/thedevs-network/kutt))) `MIT` `Nodejs/Docker`
- 🌎 [rs-short](git.42l.fr/42l/rs-short) - Lightweight link shortener written in Rust, with features such as caching, spambot protection and phishing detection.  🌎 [Demo](s.42l.fr/)) `MPL-2.0` `Rust`
- 🌎 [Shlink](shlink.io) - URL shortener with REST API and command line interface. Includes official progressive web application and docker images. (<b><code>&nbsp;&nbsp;4543⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;367🍴</code></b> [Source Code](https://github.com/shlinkio/shlink)), 🌎 [Clients](shlink.io/apps)) `MIT` `PHP/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener)) - KISS URL shortener, public or private (with account). Minimalist and lightweight. No dependencies.  🌎 [Demo](u.azlux.fr)) `MIT` `PHP`
- 🌎 [YOURLS](yourls.org/) - YOURLS is a set of PHP scripts that will allow you to run Your Own URL Shortener. Features include password protection, URL customization, bookmarklets, statistics, API, plugins, jsonp. (<b><code>&nbsp;11756⭐</code></b> <b><code>&nbsp;&nbsp;2073🍴</code></b> [Source Code](https://github.com/YOURLS/YOURLS))) `MIT` `PHP`


### Video Surveillance

**[`^        back to top        ^`](#awesome-selfhosted)**

Video surveillance, also known as 🌎 [Closed-circuit television (CCTV)](en.wikipedia.org/wiki/Closed-circuit_television), is the use of video cameras for surveillance in areas that require additional security or ongoing monitoring.

_Related: [Media Streaming - Video Streaming](#media-streaming---video-streaming)_

- 🌎 [Bluecherry](www.bluecherrydvr.com/) - Closed-circuit television (CCTV) software application which supports IP and Analog cameras. (<b><code>&nbsp;&nbsp;&nbsp;254⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Source Code](https://github.com/bluecherrydvr/bluecherry-apps))) `GPL-2.0` `PHP`
- 🌎 [Frigate](frigate.video/) - Monitor your security cameras with locally processed AI. (<b><code>&nbsp;28364⭐</code></b> <b><code>&nbsp;&nbsp;2647🍴</code></b> [Source Code](https://github.com/blakeblackshear/frigate))) `MIT` `Docker/Python/Nodejs`
- 🌎 [SentryShot](codeberg.org/SentryShot/sentryshot) - Video surveillance management system. `GPL-2.0` `Docker/Rust`
- 🌎 [Viseron](viseron.netlify.app/) - Self-hosted, local-only NVR and AI Computer Vision software. With features such as object detection, motion detection, face recognition and more, it gives you the power to keep an eye on your home, office or any other place you want to monitor. (<b><code>&nbsp;&nbsp;2454⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [Source Code](https://github.com/roflcoopter/viseron))) `MIT` `Docker`
- 🌎 [Zoneminder](www.zoneminder.com/) - Closed-circuit television (CCTV) software application which supports IP, USB and Analog cameras. (<b><code>&nbsp;&nbsp;5706⭐</code></b> <b><code>&nbsp;&nbsp;1269🍴</code></b> [Source Code](https://github.com/ZoneMinder/ZoneMinder))) `GPL-2.0` `PHP/deb`


### VPN

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [virtual private network (VPN)](en.wikipedia.org/wiki/Virtual_private_network) extends a private network across a public network and enables users to send and receive data across shared or public networks as if their computing devices were directly connected to the private network.

**Please visit <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [awesome-sysadmin/VPN](https://github.com/awesome-foss/awesome-sysadmin#vpn))**



### Web Servers

**[`^        back to top        ^`](#awesome-selfhosted)**

Web Servers and Reverse Proxies. A 🌎 [web server](en.wikipedia.org/wiki/Web_server) is a piece of software and underlying hardware that accepts requests via 🌎 [HTTP](en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) (the network protocol created to distribute web content) or its secure variant 🌎 [HTTPS](en.wikipedia.org/wiki/HTTPS). A 🌎 [Reverse Proxy](en.wikipedia.org/wiki/Reverse_proxy) is a proxy server that appears to any client to be an ordinary web server, but in reality merely acts as an intermediary that forwards requests to one or more ordinary web servers.

_Related: [Proxy](#proxy)_

- 🌎 [Algernon](algernon.roboticoverlords.org/) - Small self-contained pure-Go web server with Lua, Markdown, HTTP/2, QUIC, Redis and PostgreSQL support. (<b><code>&nbsp;&nbsp;2972⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Source Code](https://github.com/xyproto/algernon))) `BSD-3-Clause` `Go/Docker`
- 🌎 [Apache HTTP Server](httpd.apache.org/) - Secure, efficient and extensible server that provides HTTP services in sync with the current HTTP standards.  🌎 [Source Code](svn.apache.org/repos/asf/httpd/httpd/trunk/)) `Apache-2.0` `C/deb/Docker`
- 🌎 [BunkerWeb](www.bunkerweb.io) - Next-gen Web Application Firewall (WAF) that will protect your web services.  🌎 [Demo](demo.bunkerweb.io), <b><code>&nbsp;&nbsp;9641⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;547🍴</code></b> [Source Code](https://github.com/bunkerity/bunkerweb)), 🌎 [Clients](docs.bunkerweb.io/latest/plugins/)) `AGPL-3.0` `deb/Docker/K8S/Python`
- 🌎 [Caddy](caddyserver.com/) - Powerful, enterprise-ready, open source web server with automatic HTTPS. (<b><code>&nbsp;68772⭐</code></b> <b><code>&nbsp;&nbsp;4572🍴</code></b> [Source Code](https://github.com/caddyserver/caddy))) `Apache-2.0` `Go/deb/Docker`
- <b><code>&nbsp;&nbsp;2673⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [go-doxy](https://github.com/yusing/godoxy)) - Lightweight, simple, and  performant reverse proxy with WebUI, Docker integration, automatic shutdown/startup for container based on traffic. `MIT` `Docker/Go`
- 🌎 [godoxy](docs.godoxy.dev/) - High-performance reverse proxy and container orchestrator for self-hosters.  🌎 [Demo](demo.godoxy.dev/), <b><code>&nbsp;&nbsp;2673⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [Source Code](https://github.com/yusing/godoxy))) `MIT` `Docker/Go`
- 🌎 [HAProxy](www.haproxy.org/) - Very fast and reliable reverse-proxy offering high availability, load balancing, and proxying for TCP and HTTP-based applications.  🌎 [Source Code](git.haproxy.org/?p=haproxy.git;a=tree)) `GPL-2.0` `C/deb/Docker`
- <b><code>&nbsp;&nbsp;&nbsp;149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Jauth](https://github.com/Jipok/Jauth)) `⚠` - Lightweight SSL/TLS reverse proxy with authorization (via Telegram and SSH) for self-hosted apps. `GPL-3.0` `Go`
- 🌎 [Lighttpd](www.lighttpd.net/) - Secure, fast, compliant, and very flexible web server that has been optimized for high-performance environments.  🌎 [Source Code](git.lighttpd.net/lighttpd/lighttpd1.4)) `BSD-3-Clause` `C/deb/Docker`
- 🌎 [Nginx Proxy Manager](nginxproxymanager.com/) - Docker container for managing Nginx proxy hosts with a simple, powerful interface. (<b><code>&nbsp;30660⭐</code></b> <b><code>&nbsp;&nbsp;3480🍴</code></b> [Source Code](https://github.com/NginxProxyManager/nginx-proxy-manager))) `MIT` `Docker`
- 🌎 [NGINX](nginx.org/en/) - HTTP and reverse proxy server, mail proxy server, and generic TCP/UDP proxy server. (<b><code>&nbsp;28925⭐</code></b> <b><code>&nbsp;&nbsp;7697🍴</code></b> [Source Code](https://github.com/nginx/nginx))) `BSD-2-Clause` `C/deb/Docker`
- 🌎 [Pangolin](digpangolin.com/) - Identity-aware tunneled reverse proxy with dashboard UI, access control, and WireGuard-based tunnels (alternative to Cloudflare Tunnel, Tailscale). (<b><code>&nbsp;17479⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;511🍴</code></b> [Source Code](https://github.com/fosrl/pangolin))) `AGPL-3.0` `Docker`
- 🌎 [Pomerium](www.pomerium.io) - Identity-aware reverse proxy, successor to now obsolete oauth_proxy. It inserts an OAuth step before proxying your request to the backend, so that you can safely expose your self-hosted websites to public Internet. (<b><code>&nbsp;&nbsp;4555⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;317🍴</code></b> [Source Code](https://github.com/pomerium/pomerium))) `Apache-2.0` `Go/Docker`
- 🌎 [SafeLine](waf.chaitin.com/) - Web application firewall / reverse proxy to protect your web apps from attacks and exploits.  🌎 [Demo](demo.waf.chaitin.com/), <b><code>&nbsp;19723⭐</code></b> <b><code>&nbsp;&nbsp;1237🍴</code></b> [Source Code](https://github.com/chaitin/SafeLine))) `GPL-3.0` `Docker`
- 🌎 [Static Web Server](static-web-server.net/) - Cross-platform, high-performance, and asynchronous web server for static file serving. (<b><code>&nbsp;&nbsp;2046⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [Source Code](https://github.com/static-web-server/static-web-server))) `Apache-2.0/MIT` `Rust/Docker`
- <b><code>&nbsp;&nbsp;3535⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;280🍴</code></b> [SWAG (Secure Web Application Gateway)](https://github.com/linuxserver/docker-swag)) - Nginx webserver and reverse proxy with PHP support, built-in Certbot (Let's Encrypt) client and fail2ban integration. `GPL-3.0` `Docker`
- 🌎 [Traefik](traefik.io/) - HTTP reverse proxy and load balancer that makes deploying microservices easy. (<b><code>&nbsp;60737⭐</code></b> <b><code>&nbsp;&nbsp;5741🍴</code></b> [Source Code](https://github.com/traefik/traefik))) `MIT` `Go/Docker`
- 🌎 [UUSEC WAF](uuwaf.uusec.com) - Industry-leading high-performance, AI and semantic technology web application firewall and API security gateway (fork of nginx). (<b><code>&nbsp;&nbsp;1539⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [Source Code](https://github.com/Safe3/uusec-waf))) `GPL-3.0` `C/Lua/Docker`
- 🌎 [Varnish](varnish-cache.org/) - Web application accelerator/caching HTTP reverse proxy. (<b><code>&nbsp;&nbsp;4024⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;400🍴</code></b> [Source Code](https://github.com/varnishcache/varnish-cache))) `BSD-3-Clause` `Go/deb/Docker`
- 🌎 [Zoraxy](zoraxy.aroz.org/) - General purpose HTTP reverse proxy and forwarding tool. (<b><code>&nbsp;&nbsp;4685⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;265🍴</code></b> [Source Code](https://github.com/tobychui/zoraxy))) `AGPL-3.0` `Go/Docker`


### Wikis

**[`^        back to top        ^`](#awesome-selfhosted)**

A 🌎 [wiki](en.wikipedia.org/wiki/Wiki) is a publication collaboratively edited and managed by its own audience directly using a web browser.

_Related: [Note-taking & Editors](#note-taking--editors), [Static Site Generators](#static-site-generators), [Knowledge Management Tools](#knowledge-management-tools)_

_See also: 🌎 [Wikimatrix](www.wikimatrix.org/), 🌎 [List of wiki software - Wikipedia](en.wikipedia.org/wiki/List_of_wiki_software), 🌎 [Comparison of wiki software - Wikipedia](en.wikipedia.org/wiki/Comparison_of_wiki_software)_

- 🌎 [AmuseWiki](amusewiki.org/) - Amusewiki is based on the Emacs Muse markup, remaining mostly compatible with the original implementation. It can work as a read-only site, as a moderated wiki, or as a fully open wiki or even as a private site.  🌎 [Demo](sandbox.amusewiki.org), <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Source Code](https://github.com/melmothx/amusewiki))) `GPL-1.0` `Perl/Docker`
- 🌎 [BookStack](www.bookstackapp.com/) - Organize and store information. Stores documentation in a book like fashion.  🌎 [Demo](www.bookstackapp.com/#demo), <b><code>&nbsp;17933⭐</code></b> <b><code>&nbsp;&nbsp;2291🍴</code></b> [Source Code](https://github.com/BookStackApp/BookStack))) `MIT` `PHP/Docker`
- <b><code>&nbsp;&nbsp;1897⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;585🍴</code></b> [django-wiki](https://github.com/django-wiki/django-wiki)) - Wiki system with complex functionality for simple integration and a superb interface. Store your knowledge with style: Use django models.  🌎 [Demo](demo.django-wiki.org/)) `GPL-3.0` `Python`
- 🌎 [docmost](docmost.com/) - Collaborative wiki and documentation software (alternative to Confluence, Notion). (<b><code>&nbsp;18335⭐</code></b> <b><code>&nbsp;&nbsp;1040🍴</code></b> [Source Code](https://github.com/docmost/docmost))) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Documize](documize.com) - Modern Docs + Wiki software with built-in workflow, single binary executable, just bring MySQL/Percona. (<b><code>&nbsp;&nbsp;2347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;237🍴</code></b> [Source Code](https://github.com/documize/community))) `AGPL-3.0` `Go`
- 🌎 [Dokuwiki](www.dokuwiki.org/DokuWiki) - Easy to use, lightweight, standards-compliant wiki engine with a simple syntax allowing reading the data outside the wiki. All data is stored in plain text files, therefore no database is required. (<b><code>&nbsp;&nbsp;4496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;908🍴</code></b> [Source Code](https://github.com/dokuwiki/dokuwiki))) `GPL-2.0` `PHP`
- 🌎 [Feather Wiki](feather.wiki) - A lightning fast and infinitely extensible tool for creating personal non-linear notebooks, databases, and wikis that is entirely self-contained, runs in your browser, and is only 58 kilobytes in size.  🌎 [Demo](feather.wiki/?page=gallery#wikis), 🌎 [Source Code](codeberg.org/Alamantus/FeatherWiki), 🌎 [Clients](feather.wiki/?page=gallery#extensions)) `AGPL-3.0` `Javascript`
- <b><code>&nbsp;&nbsp;2250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;231🍴</code></b> [Gitit](https://github.com/jgm/gitit)) - Wiki program that stores pages and uploaded files in a git repository, which can then be modified using the VCS command line tools or the wiki's web interface. `GPL-2.0` `Haskell`
- <b><code>&nbsp;14205⭐</code></b> <b><code>&nbsp;&nbsp;1562🍴</code></b> [Gollum](https://github.com/gollum/gollum)) - Simple, Git-powered wiki with a sweet API and local frontend. `MIT` `Ruby`
- 🌎 [Mediawiki](www.mediawiki.org/wiki/MediaWiki) - Wiki software package that powers Wikipedia and all other Wikimedia projects, serving hundreds of millions of users each month.  🌎 [Demo](en.wikipedia.org/wiki/Main_Page), 🌎 [Source Code](phabricator.wikimedia.org/source/mediawiki/)) `GPL-2.0` `PHP`
- 🌎 [Mycorrhiza Wiki](mycorrhiza.wiki/) - Filesystem and git-based wiki engine written in Go using Mycomarkup as its primary markup language. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/bouncepaw/mycorrhiza/))) `AGPL-3.0` `Go`
- 🌎 [Oddmuse](oddmuse.org/) - Simple wiki engine written in Perl. No database required. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Source Code](https://github.com/kensanata/oddmuse))) `GPL-3.0` `Perl`
- 🌎 [Otter Wiki](otterwiki.com/) - Simple, easy to use wiki software using markdown. (<b><code>&nbsp;&nbsp;1186⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Source Code](https://github.com/redimp/otterwiki))) `MIT` `Docker`
- 🌎 [PmWiki](www.pmwiki.org) - Wiki-based system for collaborative creation and maintenance of websites. `GPL-3.0` `PHP`
- 🌎 [Raneto](raneto.com/) - Knowledgebase platform that uses static Markdown files. (<b><code>&nbsp;&nbsp;2863⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;441🍴</code></b> [Source Code](https://github.com/ryanlelek/Raneto))) `MIT` `Nodejs`
- 🌎 [TiddlyWiki](tiddlywiki.com/) - Reusable non-linear personal web notebook. (<b><code>&nbsp;&nbsp;8494⭐</code></b> <b><code>&nbsp;&nbsp;1242🍴</code></b> [Source Code](https://github.com/TiddlyWiki/TiddlyWiki5))) `BSD-3-Clause` `Nodejs`
- 🌎 [Tiki](tiki.org/HomePage) - Wiki CMS Groupware with the most built-in features.  🌎 [Demo](tiki.org/Try-Tiki), 🌎 [Source Code](gitlab.com/tikiwiki/tiki)) `LGPL-2.1` `PHP`
- 🌎 [W](w.club1.fr) - Lightweight, mutli-user, flat-file-database Wiki engine. Create pages quickly and edit them in your Web browser using Mardown/HTML/CSS/JS. The main difference with other wiki is that you are encouraged to customize each page style individually. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Source Code](https://github.com/vincent-peugnet/wcms))) `AGPL-3.0` `PHP`
- 🌎 [WackoWiki](wackowiki.org/) - WackoWiki is a light and easy to install multilingual Wiki-engine. (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Source Code](https://github.com/WackoWiki/wackowiki))) `BSD-3-Clause` `PHP`
- 🌎 [Wiki-Go](leomoon.com/downloads/web-apps/wiki-go/) - A modern, feature-rich, databaseless flat-file wiki platform.  🌎 [Demo](wikigo.leomoon.com), <b><code>&nbsp;&nbsp;&nbsp;466⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Source Code](https://github.com/leomoon-studios/wiki-go))) `GPL-3.0` `Go/Docker`
- 🌎 [Wiki.js](js.wiki/) - Modern, lightweight and powerful wiki app using Git and Markdown.  🌎 [Demo](docs.requarks.io), <b><code>&nbsp;27528⭐</code></b> <b><code>&nbsp;&nbsp;3118🍴</code></b> [Source Code](https://github.com/Requarks/wiki))) `AGPL-3.0` `Nodejs/Docker/K8S`
- [WikiDocs](http://wikidocs.it) - A databaseless markdown flat-file wiki engine. (<b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Source Code](https://github.com/Zavy86/WikiDocs))) `MIT` `PHP/Docker`
- 🌎 [WiKiss](wikiss.tuxfamily.org/) - Wiki, simple to use and install.  🌎 [Source Code](svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
- 🌎 [XWiki](www.xwiki.org) - Second generation wiki that allows the user to extend its functionalities with a powerful extension-based architecture.  🌎 [Demo](www.xwikiplayground.org/xwiki/bin/view/Main/), <b><code>&nbsp;&nbsp;1176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;610🍴</code></b> [Source Code](https://github.com/xwiki/xwiki-platform))) `LGPL-2.1` `Java/Docker/deb`
- 🌎 [Zim](zim-wiki.org/) - Graphical text editor used to maintain a collection of wiki pages. Each page can contain links to other pages, simple formatting and images. (<b><code>&nbsp;&nbsp;2109⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;392🍴</code></b> [Source Code](https://github.com/zim-desktop-wiki/zim-desktop-wiki))) `GPL-2.0` `Python/deb`


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
- `CAL-1.0` - 🌎 [Cryptographic Autonomy License 1.0](spdx.org/licenses/CAL-1.0.html)
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

- Alternative frontends/portals to discover/filter awesome-selfhosted apps: 🌎 [awweso.me](awweso.me/), 🌎 [awesome-web.theravenhub](awesome-web.theravenhub.com/browse.html), 🌎 [awesomehub.web.app](awesomehub.js.org/list/selfhosted)
- <b><code>&nbsp;32180⭐</code></b> <b><code>&nbsp;&nbsp;1871🍴</code></b> [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin)) - Curated list of amazingly awesome open source sysadmin resources.
- Lists of software aimed at privacy and decentralization in some form: 🌎 [PRISM Break](prism-break.org/en/), 🌎 [privacytools.io](www.privacytools.io/), 🌎 [Alternative Internet](redecentralize.github.io/alternative-internet/), 🌎 [Libre Projects](libreprojects.net/), 🌎 [Easy Indie App](easyindie.app)
- Other Awesome lists: <b><code>&nbsp;14117⭐</code></b> <b><code>&nbsp;&nbsp;2592🍴</code></b> [Awesome Big Data](https://github.com/0xnr/awesome-bigdata)), <b><code>&nbsp;71684⭐</code></b> <b><code>&nbsp;11048🍴</code></b> [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets))
- Dynamic Domain Name services: 🌎 [Afraid.org](freedns.afraid.org/domain/registry/), 🌎 [Pagekite](pagekite.net/)
- Communities/forums: 🌎 [/c/selfhosted on lemmy.world](lemmy.world/c/selfhosted), 🌎 [/c/selfhost on lemmy.ml](lemmy.ml/c/selfhost), 🌎 [/r/selfhosted on reddit](old.reddit.com/r/selfhosted/), 🌎 [/r/selfhosted Matrix Channel](matrix.to/#/#selfhosted:selfhosted.chat), 🌎 [/r/homelab on reddit](old.reddit.com/r/homelab/), 🌎 [IndieWeb](indieweb.org/)
- 🌎 [theme.park](theme-park.dev/) - A collection of themes/skins for 50 selfhosted apps! (<b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/GilbN/theme.park/))) `MIT` `CSS`

--------------------

## Contributing

Contributing guidelines can be found <b><code>&nbsp;&nbsp;&nbsp;819⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;670🍴</code></b> [here](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/CONTRIBUTING.md)).

## License

This list is under the [Creative Commons Attribution-ShareAlike 3.0 Unported](https://github.com/correia-jpv/fucking-awesome-selfhosted/blob/master/LICENSE) License.
Terms of the license are summarized 🌎 [here](creativecommons.org/licenses/by-sa/3.0/).  
The list of authors can be found in the <b><code>&nbsp;&nbsp;&nbsp;819⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;670🍴</code></b> [AUTHORS](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/AUTHORS)) file.

## Source
<b><code>264870⭐</code></b> <b><code>&nbsp;12173🍴</code></b> [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted))