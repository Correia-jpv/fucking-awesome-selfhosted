# Awesome-Selfhosted

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![](https://img.shields.io/travis/awesome-selfhosted/awesome-selfhosted/master?label=link%20checks)](https://github.com/correia-jpv/fucking-awesome-selfhosted/issues/2266)

Self-hosting is the practice of hosting and managing applications on your own server(s) instead of consuming from 🌎 [SaaSS](www.gnu.org/philosophy/who-does-that-server-really-serve.html) providers.

This is a list of 🌎 [Free](en.wikipedia.org/wiki/Free_software) Software 🌎 [network services](en.wikipedia.org/wiki/Network_service) and 🌎 [web applications](en.wikipedia.org/wiki/Web_application) which can be hosted on your own server(s). Non-Free software is listed on the [Non-Free](non-free.md) page.

See [Contributing](.github/CONTRIBUTING.md).

--------------------


## Table of contents

- [Software](#software)
  - [Analytics](#analytics)
  - [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)
  - [Automation](#automation)
  - [Blogging Platforms](#blogging-platforms)
  - [Booking and Scheduling](#booking-and-scheduling)
  - [Bookmarks and Link Sharing](#bookmarks-and-link-sharing)
  - [Calendar & Contacts](#calendar--contacts)
  - [Calendar & Contacts - CalDAV or CardDAV Servers](#calendar--contacts---caldav-or-carddav-servers)
  - [Calendar & Contacts - CalDAV or CardDAV Web-based Clients](#calendar--contacts---caldav-or-carddav-web-based-clients)
  - [Communication](#communication)
  - [Communication - Custom Communication Systems](#communication---custom-communication-systems)
  - [Communication - Email](#communication---email)
  - [Communication - Email - Complete Solutions](#communication---email---complete-solutions)
  - [Communication - Email - Mail Delivery Agents](#communication---email---mail-delivery-agents)
  - [Communication - Email - Mail Transfer Agents](#communication---email---mail-transfer-agents)
  - [Communication - Email - Mailing Lists and Newsletters](#communication---email---mailing-lists-and-newsletters)
  - [Communication - Email - Webmail Clients](#communication---email---webmail-clients)
  - [Communication - IRC](#communication---irc)
  - [Communication - SIP](#communication---sip)
  - [Communication - Social Networks and Forums](#communication---social-networks-and-forums)
  - [Communication - Video Conferencing](#communication---video-conferencing)
  - [Communication - XMPP](#communication---xmpp)
  - [Communication - XMPP - Servers](#communication---xmpp---servers)
  - [Communication - XMPP - Web Clients](#communication---xmpp---web-clients)
  - [Community-Supported Agriculture (CSA)](#community-supported-agriculture-csa)
  - [Conference Management](#conference-management)
  - [Content Management Systems (CMS)](#content-management-systems-cms)
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
  - [Gateways and Terminal Sharing](#gateways-and-terminal-sharing)
  - [Genealogy](#genealogy)
  - [Groupware](#groupware)
  - [Human Resources Management (HRM)](#human-resources-management-hrm)
  - [Internet of Things (IoT)](#internet-of-things-iot)
  - [Knowledge Management Tools](#knowledge-management-tools)
  - [Learning and Courses](#learning-and-courses)
  - [Maps and Global Positioning System (GPS)](#maps-and-global-positioning-system-gps)
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
  - [Photo and Video Galleries](#photo-and-video-galleries)
  - [Polls and Events](#polls-and-events)
  - [Proxy](#proxy)
  - [Read-it-later Lists](#read-it-later-lists)
  - [Recipe Management](#recipe-management)
  - [Resource Planning](#resource-planning)
  - [Resource Planning - Enterprise Resource Planning](#resource-planning---enterprise-resource-planning)
  - [Search Engines](#search-engines)
  - [Self-hosting Solutions](#self-hosting-solutions)
  - [Software Development](#software-development)
  - [Software Development - API Management](#software-development---api-management)
  - [Software Development - Bug Trackers](#software-development---bug-trackers)
  - [Software Development - Continuous Integration & Deployment](#software-development---continuous-integration--deployment)
  - [Software Development - FaaS & Serverless](#software-development---faas--serverless)
  - [Software Development - IDE & Tools](#software-development---ide--tools)
  - [Software Development - Localization](#software-development---localization)
  - [Software Development - Project Management](#software-development---project-management)
  - [Software Development - UX Testing](#software-development---ux-testing)
  - [Static Site Generators](#static-site-generators)
  - [Status / Uptime pages](#status--uptime-pages)
  - [Task Management & To-do Lists](#task-management--to-do-lists)
  - [Ticketing](#ticketing)
  - [Time Trackers](#time-trackers)
  - [URL Shorteners](#url-shorteners)
  - [VPN](#vpn)
  - [Web Servers](#web-servers)
  - [Wikis](#wikis)
- [List of Licenses](#list-of-licenses)
- [Anti-features](#anti-features)
- [External Links](#external-links)
- [Contributing](#contributing)
- [Authors](#authors)
- [License](#license)

--------------------

## Software

### Analytics

**[`^        back to top        ^`](#)**

**Please visit  <b><code>&nbsp;&nbsp;3217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;415🍴</code></b> [Awesome Analytics](https://github.com/0xnr/awesome-analytics)**

_Related: [Personal Dashboards](#personal-dashboards)_


### Archiving and Digital Preservation (DP)

**[`^        back to top        ^`](#)**

_Related: [Content Management Systems (CMS)](#content-management-systems-cms)_

- 🌎 [Access to Memory (AtoM)](www.accesstomemory.org/) - Web-based, open source application for standards-based archival description and access in a multilingual, multi-repository environment.  🌎 [Demo](demo.accesstomemory.org/),  <b><code>&nbsp;&nbsp;&nbsp;180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [Source Code](https://github.com/artefactual/atom)) `AGPL-3.0-only` `PHP`
- 🌎 [ArchiveBox](archivebox.io/) - Self-hosted _wayback machine_ that creates HTML & screenshot archives of sites from your bookmarks, browsing history, RSS feeds, or other sources. ( <b><code>&nbsp;13854⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;800🍴</code></b> [Source Code](https://github.com/ArchiveBox/ArchiveBox)) `MIT` `Python`
- 🌎 [Archivematica](www.archivematica.org/) - Mature digital preservation system designed to maintain standards-based, long-term access to collections of digital objects.  🌎 [Demo](sandbox.archivematica.org/administration/accounts/login/),  <b><code>&nbsp;&nbsp;&nbsp;324⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [Source Code](https://github.com/artefactual/archivematica)) `AGPL-3.0-only` `Python`
- 🌎 [ArchivesSpace](archivesspace.org/) - Archives information management application for managing and providing Web access to archives, manuscripts and digital objects.  🌎 [Demo](archivesspace.org/application/demo/),  <b><code>&nbsp;&nbsp;&nbsp;261⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;207🍴</code></b> [Source Code](https://github.com/archivesspace/archivesspace)) `ECL-2.0` `Ruby`
- 🌎 [CKAN](ckan.org) - CKAN is a tool for making open data websites. ( <b><code>&nbsp;&nbsp;3482⭐</code></b> <b><code>&nbsp;&nbsp;1775🍴</code></b> [Source Code](https://github.com/ckan/ckan)) `AGPL-3.0` `Python`
- 🌎 [Collective Access - Providence](collectiveaccess.org/) - Highly configurable Web-based framework for management, description, and discovery of digital and physical collections supporting a variety of metadata standards, data types, and media formats. ( <b><code>&nbsp;&nbsp;&nbsp;230⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [Source Code](https://github.com/collectiveaccess/providence)) `GPL-3.0-only` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;664⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Horahora](https://github.com/horahoradev/horahora) - Video hosting website and video archival manager for Niconico, Bilibili, and Youtube. `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [LiveStreamDVR](https://github.com/MrBrax/LiveStreamDVR) `⚠` - An automatic Twitch recorder capable of capturing live streams, chat messages and stream metadata. `MIT` `Python/Nodejs`


### Automation

**[`^        back to top        ^`](#)**

_Related: [Internet of Things (IoT)](#internet-of-things-iot)_

- 🌎 [Accelerated Text](www.acceleratedtext.com/) - Automatically generate multiple natural language descriptions of your data varying in wording and structure. ( <b><code>&nbsp;&nbsp;&nbsp;605⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Source Code](https://github.com/tokenmill/accelerated-text)) `Apache-2.0` `Java`
- 🌎 [Actionsflow](actionsflow.github.io/docs/) `⚠` - The free Zapier/IFTTT alternative for developers to automate your workflows based on Github actions. ( <b><code>&nbsp;&nbsp;2527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [Source Code](https://github.com/actionsflow/actionsflow)) `MIT` `Docker/Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;593⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [ActiveWorkflow](https://github.com/automaticmode/active_workflow) - An intelligent process and workflow automation platform based on software agents. `MIT` `Ruby`
- 🌎 [Alltube](www.alltubedownload.net) - Web interface for  <b><code>111799⭐</code></b> <b><code>&nbsp;&nbsp;7978🍴</code></b> [youtube-dl](https://github.com/ytdl-org/youtube-dl), a program to download videos and audio from 🌎 [more than 100 websites](ytdl-org.github.io/youtube-dl/supportedsites.html). ( <b><code>&nbsp;&nbsp;2410⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;529🍴</code></b> [Source Code](https://github.com/Rudloff/alltube)) `GPL-3.0` `PHP`
- 🌎 [AmIUnique](amiunique.org/) - Learn how identifiable you are on the Internet (browser fingerprinting tool). ( <b><code>&nbsp;&nbsp;&nbsp;629⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Source Code](https://github.com/DIVERSIFY-project/amiunique)) `MIT` `Java`
- 🌎 [Baserow](baserow.io/) - Open source online database tool and Airtable alternative. Create your own database without technical experience.  🌎 [Source Code](gitlab.com/bramw/baserow)) `MIT` `Python/Nodejs`
-  <b><code>&nbsp;&nbsp;5674⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;296🍴</code></b> [Beehive](https://github.com/muesli/beehive) - Flexible event and agent system, which allows you to create your own agents that perform automated tasks triggered by events and filters. `AGPL-3.0` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [betanin](https://github.com/sentriz/betanin) - Music organization man-in-the-middle of your torrent client and music player. Based on beets.io, similar to Sonarr and Radarr. `GPL-3.0` `Python`
- 🌎 [ChiefOnboarding](chiefonboarding.com) - Employee onboarding platform that allows you to provision user accounts and create sequences with todo items, resources, text/email/Slack messages, and more! Available as a web portal and Slack bot. ( <b><code>&nbsp;&nbsp;&nbsp;275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Source Code](https://github.com/chiefonboarding/ChiefOnboarding)) `AGPL-3.0` `Python`
- 🌎 [CouchPotato](couchpota.to/) - CouchPotato is an automatic Video Library Manager for Movies. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ( <b><code>&nbsp;&nbsp;3872⭐</code></b> <b><code>&nbsp;&nbsp;1289🍴</code></b> [Source Code](https://github.com/CouchPotato/CouchPotatoServer)) `GPL-3.0` `Python`
- 🌎 [Datasette](datasette.io/) - An open source multi-tool for exploring and publishing data, easy import and export and database management.  🌎 [Demo](global-power-plants.datasettes.com/global-power-plants/global-power-plants),  <b><code>&nbsp;&nbsp;6297⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;433🍴</code></b> [Source Code](https://github.com/simonw/datasette)) `Apache-2.0` `Python`
- 🌎 [Eonza](www.eonza.org) - Eonza is used to create scripts and automate tasks on servers or VPS hosting. Manage your servers from any browser on any device.  🌎 [Demo](playground.eonza.org/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Source Code](https://github.com/gentee/eonza)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Episodes](https://github.com/guptachetan1997/Episodes) `⚠` - Self Hosted TV show Episode tracker and recommender built using django, bootstrap4. `MIT` `Python`
- 🌎 [Exadel CompreFace](exadel.com/solutions/compreface/) - Face recognition system that provides REST API for face recognition, face detection, and other face services, and is easily deployed with docker. There are SDKs for Python and JavaScript languages. Can be used without prior machine learning skills. ( <b><code>&nbsp;&nbsp;2111⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;271🍴</code></b> [Source Code](https://github.com/exadel-inc/CompreFace)) `Apache-2.0` `Docker/Java/Nodejs`
- 🌎 [feed2toot](feed2toot.readthedocs.io/) - Feed2toot parses a RSS feed, extracts the last entries and sends them to Mastodon.  🌎 [Source Code](gitlab.com/chaica/feed2toot)) `GPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [feedmixer](https://github.com/cristoper/feedmixer) - FeedMixer is a WSGI (Python3) micro web service which takes a list of feed URLs and returns a new feed consisting of the most recent n entries from each given feed(Returns Atom, RSS, or JSON).  🌎 [Demo](mretc.net/feedmixer/json?f=https://hnrss.org/newest&f=https://americancynic.net/atom.xml&n=1)) `WTFPL` `Python`
-  <b><code>&nbsp;&nbsp;3120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;617🍴</code></b> [Headphones](https://github.com/rembo10/headphones) - Automated music downloader for NZB and Torrent, written in Python. It supports SABnzbd, NZBget, Transmission, µTorrent, Deluge and Blackhole. `GPL-3.0` `Python`
- 🌎 [Healthchecks](healthchecks.io/) - Django app which listens for pings and sends alerts when pings are late. ( <b><code>&nbsp;&nbsp;5333⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;610🍴</code></b> [Source Code](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [homebank-converter](https://github.com/Binnette/homebank-converter) - Web app to convert an export bank file to compatible Homebank csv.  🌎 [Demo](binnette.github.io/homebank-converter/)) `AGPL-3.0` `HTML5`
-  <b><code>&nbsp;&nbsp;&nbsp;333⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [HRConvert2](https://github.com/zelon88/HRConvert2) - Drag-and-drop file conversion server with session based authentication, automatic temporary file maintenance, and logging capability. `GPL-3.0` `PHP`
-  <b><code>&nbsp;36076⭐</code></b> <b><code>&nbsp;&nbsp;3286🍴</code></b> [Huginn](https://github.com/huginn/huginn) - Allows you to build agents that monitor and act on your behalf. `MIT` `Ruby`
- 🌎 [Kibitzr](kibitzr.github.io) - Lightweight personal web assistant with powerful integrations. ( <b><code>&nbsp;&nbsp;&nbsp;485⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Source Code](https://github.com/kibitzr/kibitzr)) `MIT` `Python`
- 🌎 [Krayin](krayincrm.com/) - Free and Opensource Laravel CRM Application. ( <b><code>&nbsp;&nbsp;&nbsp;939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [Source Code](https://github.com/krayin/laravel-crm)) `MIT` `PHP`
- 🌎 [LazyLibrarian](gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - LazyLibrarian is a program to follow authors and grab metadata for all your digital reading needs. It uses a combination of Goodreads Librarything and optionally GoogleBooks as sources for author info and book info. `GPL-3.0` `Python`
- 🌎 [Leon](getleon.ai) - Open-source personal assistant who can live on your server. ( <b><code>&nbsp;&nbsp;8874⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;792🍴</code></b> [Source Code](https://github.com/leon-ai/leon)) `MIT` `Nodejs`
- 🌎 [Lidarr](lidarr.audio/) - Lidarr is a music collection manager for Usenet and BitTorrent users. ( <b><code>&nbsp;&nbsp;2397⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [Source Code](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#`
- 🌎 [Medusa](pymedusa.com/) - Automatic Video Library Manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic. ( <b><code>&nbsp;&nbsp;1479⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Source Code](https://github.com/pymedusa/Medusa)) `GPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [MetaTube](https://github.com/JVT038/MetaTube) `⚠` - A Web GUI to automatically download music from YouTube add metadata from Spotify, Deezer or Musicbrainz. `GPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;1001⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [MeTube](https://github.com/alexta69/metube) - Web GUI for youtube-dl, with playlist support. Allows downloading videos from dozens of websites. `AGPL-3.0` `Python/Nodejs/Docker`
-  <b><code>&nbsp;&nbsp;&nbsp;622⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [nefarious](https://github.com/lardbit/nefarious) - Web application that automates downloading Movies and TV Shows. `GPL-3.0` `Python`
- 🌎 [NocoDB](www.nocodb.com/) - No-code platform that turns any database into a smart spreadsheet. It can be considered as an Airtable or Smartsheet alternative. ( <b><code>&nbsp;28945⭐</code></b> <b><code>&nbsp;&nbsp;1768🍴</code></b> [Source Code](https://github.com/nocodb/nocodb)) `GPL-3.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;696⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [OliveTin](https://github.com/OliveTin/OliveTin) - OliveTin is a web interface for running Linux shell commands. `AGPL-3.0` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;487⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [Patrowl](https://github.com/Patrowl/PatrowlManager) - Open Source, Smart and Scalable Security Operations Orchestration Platform. `AGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;768⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Podgrab](https://github.com/akhilrex/podgrab) - Lightweight podcast manager and automatic podcast episode downloader. It will monitor podcasts for your and download them automatically whenever a new episode goes live. `GPL-3.0` `Docker/Go`
- 🌎 [pyLoad](pyload.net/) - Lightweight, customizable and remotely manageable downloader for 1-click-hosting sites like rapidshare.com or uploaded.to. ( <b><code>&nbsp;&nbsp;2592⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;651🍴</code></b> [Source Code](https://github.com/pyload/pyload)) `GPL-3.0` `Python`
- 🌎 [Radarr](radarr.video/) - Radarr is an independent fork of Sonarr reworked for automatically downloading movies via Usenet and BitTorrent, à la Couchpotato. ( <b><code>&nbsp;&nbsp;6448⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;773🍴</code></b> [Source Code](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#`
- 🌎 [SickRage](www.sickrage.ca) - SickRage is an automatic Video Library Manager for TV Shows. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ( <b><code>&nbsp;&nbsp;1525⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;701🍴</code></b> [Source Code](https://github.com/SickRage/SickRage)) `GPL-3.0` `Python`
- 🌎 [SiteInspector](www.getsiteinspector.com/) - Web-based tool for catching spelling errors, grammatical errors, broken links, and other errors on websites.  🌎 [Demo](demo.getsiteinspector.com/reports),  <b><code>&nbsp;&nbsp;&nbsp;164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Source Code](https://github.com/siteinspector/siteinspector)) `AGPL-3.0` `Ruby`
- 🌎 [Sonarr](sonarr.tv/) - Automatic TV Shows downloader and manager for Usenet and BitTorrent. It can grab, sort and rename new episodes and automatically upgrade the quality of files already downloaded when a better quality format becomes available. ( <b><code>&nbsp;&nbsp;7519⭐</code></b> <b><code>&nbsp;&nbsp;1051🍴</code></b> [Source Code](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#`
- 🌎 [StackStorm](stackstorm.com) - StackStorm (aka _IFTTT for Ops_) is event-driven automation for auto-remediation, security responses, troubleshooting, deployments, and more. Includes rules engine, workflow, 160 integration packs with 6000+ actions and ChatOps. ( <b><code>&nbsp;&nbsp;4887⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;663🍴</code></b> [Source Code](https://github.com/StackStorm/st2)) `Apache-2.0` `Python`
-  <b><code>&nbsp;&nbsp;8855⭐</code></b> <b><code>&nbsp;&nbsp;1418🍴</code></b> [WebUI-aria2](https://github.com/ziahamza/webui-aria2) - Interface to interact with the aria2 downloader. Very simple to use, just download and open index.html in any web browser.  🌎 [Demo](ziahamza.github.io/webui-aria2/)) `MIT` `HTML5`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [ydl_api_ng](https://github.com/Totonyus/ydl_api_ng) - Simple youtube-dl REST API to launch downloads on a distant server. `GPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;1512⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [YoutubeDL-Material](https://github.com/Tzahi12345/YoutubeDL-Material) - Material Design inspired YouTube downloader, based on youtube-dl. Supports playlists, quality select, search, dark mode and much more, all with a clean and modern design. `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;8188⭐</code></b> <b><code>&nbsp;&nbsp;2100🍴</code></b> [Zenbot](https://github.com/DeviaVir/zenbot) - Zenbot is a lightweight, extendable, artificially intelligent trading bot for Bitcoin, Ether, Litecoin, and more. `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;681⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [µTask](https://github.com/ovh/utask) - Automation engine that models and executes business processes declared in yaml. `BSD-3-Clause` `Go`


### Blogging Platforms

**[`^        back to top        ^`](#)**

_Related: [Static Site Generators](#static-site-generators), [Content Management Systems (CMS)](#content-management-systems-cms)_

_See also: 🌎 [WeblogMatrix](www.weblogmatrix.org/)_

- 🌎 [Antville](antville.org) - Free, open source project aimed at the development of a high performance, feature rich weblog hosting software. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Source Code](https://github.com/antville/antville)) `Apache-2.0` `Javascript`
-  <b><code>&nbsp;&nbsp;&nbsp;217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Blog](https://github.com/m1k1o/blog) - Facebook-styled blog. Free, extremely lightweight, single-user and easy to install. `GPL-3.0` `PHP`
- 🌎 [Canvas](trycanvas.app/) - A Laravel publishing platform. ( <b><code>&nbsp;&nbsp;2988⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;497🍴</code></b> [Source Code](https://github.com/austintoddj/canvas)) `MIT` `PHP`
- 🌎 [Castopod](castopod.org) - A podcast management hosting platform that includes the latest podcast 2.0 standards, an automated Fediverse feed, analytics, an embeddable player, and more.  🌎 [Source Code](code.castopod.org/adaures/castopod)) `AGPL-3.0` `PHP`
- 🌎 [Chyrp Lite](chyrplite.net) - Extra-awesome, extra-lightweight blog engine. ( <b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Source Code](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- 🌎 [Dotclear](dotclear.org/) - Take control over your blog.  🌎 [Source Code](git.dotclear.org/dev/dotclear)) `GPL-2.0` `PHP`
- 🌎 [Ghost](ghost.org/) - Just a blogging platform. ( <b><code>&nbsp;40721⭐</code></b> <b><code>&nbsp;&nbsp;8787🍴</code></b> [Source Code](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
- 🌎 [Haven](havenweb.org/) - Private blogging system with markdown editing and built in RSS reader.  🌎 [Demo](havenweb.org/demo.html),  <b><code>&nbsp;&nbsp;&nbsp;448⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Source Code](https://github.com/havenweb/haven)) `MIT` `Ruby`
- 🌎 [htmly](www.htmly.com/) - Databaseless Blogging Platform (Flat-File Blog).  🌎 [Demo](demo.htmly.com/),  <b><code>&nbsp;&nbsp;&nbsp;811⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;219🍴</code></b> [Source Code](https://github.com/danpros/htmly)) `GPL-2.0` `PHP`
- 🌎 [Known](withknown.com/) - A collaborative social publishing platform. ( <b><code>&nbsp;&nbsp;&nbsp;944⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [Source Code](https://github.com/idno/known)) `Apache-2.0` `PHP`
- 🌎 [Plume](joinplu.me/) - Federated blogging engine, based on ActivityPub. ( <b><code>&nbsp;&nbsp;1736⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [Source Code](https://github.com/Plume-org/Plume)) `AGPL-3.0` `Rust`
- 🌎 [PluXml](pluxml.org) - XML-based blog/CMS platform. ( <b><code>&nbsp;&nbsp;&nbsp;190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Source Code](https://github.com/pluxml/PluXml)) `GPL-1.0` `PHP`
- 🌎 [Serendipity](docs.s9y.org/) - Serendipity (s9y) is a highly extensible and customizable PHP blog engine using Smarty templating. ( <b><code>&nbsp;&nbsp;&nbsp;171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [Source Code](https://github.com/s9y/serendipity)) `BSD-3-Clause` `PHP`


### Booking and Scheduling

**[`^        back to top        ^`](#)**

_Related: [Polls and Events](#polls-and-events)_

- 🌎 [Alf.io](alf.io/) - The open source ticket reservation system.  🌎 [Demo](demo.alf.io/authentication),  <b><code>&nbsp;&nbsp;&nbsp;993⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;277🍴</code></b> [Source Code](https://github.com/alfio-event/alf.io)) `GPL-3.0` `Java`
- 🌎 [Cal.com](cal.com/) - The open-source online appointment scheduling system.  🌎 [Demo](app.cal.com/bailey),  <b><code>&nbsp;12419⭐</code></b> <b><code>&nbsp;&nbsp;1448🍴</code></b> [Source Code](https://github.com/calcom/cal.com)) `MIT` `Nodejs`
- 🌎 [Easy!Appointments](easyappointments.org/) - A highly customizable web application that allows your customers to book appointments with you via the web.  🌎 [Demo](easyappointments.org/demo/),  <b><code>&nbsp;&nbsp;2279⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;984🍴</code></b> [Source Code](https://github.com/alextselegidis/easyappointments)) `GPL-3.0` `PHP`


### Bookmarks and Link Sharing

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Briefkasten](https://github.com/ndom91/briefkasten) - Modern app for saving and managing your own bookmarks. Includes a browser extension.  🌎 [Demo](briefkasten.vercel.app)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;141⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [dyu bookmarks](https://github.com/dyu/bookmarks) - Single-threaded/process bookmark app powered by leveldb and uWebSockets. Supports importing from Delicious and Chrome.  🌎 [Demo](dyuproject.com/bookmarks/)) `Apache-2.0` `Java`
-  <b><code>&nbsp;&nbsp;&nbsp;524⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Espial](https://github.com/jonschoning/espial) - An open-source, web-based bookmarking server. `AGPL-3.0` `Haskell`
- 🌎 [Firefox Account Server](mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html) - This allows you to host your own Firefox accounts server. ( <b><code>&nbsp;&nbsp;&nbsp;427⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;194🍴</code></b> [Source Code](https://github.com/mozilla/fxa)) `MPL-2.0` `Nodejs, Java`
-  <b><code>&nbsp;&nbsp;1645⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [Firefox Sync Server](https://github.com/mozilla-services/syncserver) - Sync Firefox bookmarks, passwords, history, tabs, preferences. `MPL-2.0` `Python`
- 🌎 [Geekmarks](geekmarks.dmitryfrank.com/) - Personal bookmarking service focused on speed and organization using hierarchical tags. ( <b><code>&nbsp;&nbsp;&nbsp;565⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Source Code](https://github.com/dimonomid/geekmarks)) `BSD-2-Clause` `Go`
- 🌎 [golinks](git.mills.io/prologic/golinks) - Web application that allows you to create smart bookmarks, commands and aliases by pointing your web browser's default search engine at a running instance. Similar to bunny1 or yubnub.  🌎 [Demo](search.mills.io)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Hackershare](https://github.com/hackershare/hackershare) - Social bookmarks website for hackers.  🌎 [Demo](hackershare.dev)) `MIT` `Ruby`
- 🌎 [LinkAce](www.linkace.org/) - A bookmark archive with automatic backups to the Internet Archive, link monitoring, and a full REST API. Installation is done via Docker, or as a simple PHP application.  🌎 [Demo](demo.linkace.org/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/Kovah/LinkAce/)) `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;1946⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [linkding](https://github.com/sissbruecker/linkding) - Minimal bookmark management with a fast and clean UI. Simple installation through Docker and can run on your Raspberry Pi.  🌎 [Demo](demo.linkding.link/)) `MIT` `Docker/Python/Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;363⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [LinkWarden](https://github.com/Daniel31x13/link-warden) - A self-hosted bookmark + archive manager to store your useful links.  🌎 [Demo](linkwarden.netlify.app/)) `MIT` `Docker/Nodejs`
- 🌎 [Lobsters](lobste.rs) - Run your own link aggregation site. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/jcs/lobsters)) `BSD-3-Clause` `Ruby`
- 🌎 [No Fuss Bookmarks](nofussbm.herokuapp.com/signup.html) - Very simple software and service to store bookmarks especially designed for hackers (that don't need fancy interfaces, but nice API). ( <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Source Code](https://github.com/mapio/nofussbm)) `GPL-3.0` `Python`
- 🌎 [Pinry](docs.getpinry.com/) - The tiling image board system for people who want to save, tag, and share images, videos, and webpages.  🌎 [Demo](pin.37soloist.com/),  <b><code>&nbsp;&nbsp;2592⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;331🍴</code></b> [Source Code](https://github.com/pinry/pinry)) `BSD-2-Clause` `Python`
-  <b><code>&nbsp;&nbsp;1562⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [Reminiscence](https://github.com/kanishka-linux/reminiscence) - Self-Hosted Bookmark And Archive Manager. `AGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;2702⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;267🍴</code></b> [Shaarli](https://github.com/shaarli/Shaarli) - Personal, minimalist, super-fast, no-database bookmarking and link sharing platform.  🌎 [Demo](demo.shaarli.org)) `Zlib` `PHP`
-  <b><code>&nbsp;&nbsp;6299⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;424🍴</code></b> [Shiori](https://github.com/go-shiori/shiori) - Simple bookmark manager built with Go. `MIT` `Go`
- 🌎 [ubookmark](ungleich.ch/u/projects/ubookmark/) - LDAP enabled bookmarking service.  🌎 [Demo](ipv6.blog), 🌎 [Source Code](code.ungleich.ch/ungleich-public/ubookmark/)) `GPL-2.0` `Python`
- 🌎 [unmark](unmark.it/) - Open source to do app for links. ( <b><code>&nbsp;&nbsp;1544⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;191🍴</code></b> [Source Code](https://github.com/cdevroe/unmark)) `MIT` `PHP`
- 🌎 [xBrowserSync](www.xbrowsersync.org) - Open source tool for syncing browser data between browsers and devices. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/xBrowserSync)) `MIT` `Nodejs`


### Calendar & Contacts

**[`^        back to top        ^`](#)**

_Related: [Groupware](#groupware)_

_See also: 🌎 [Comparison of CalDAV and CardDAV implementations - Wikipedia](en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations)_


### Calendar & Contacts - CalDAV or CardDAV Servers

**[`^        back to top        ^`](#)**

- 🌎 [Baïkal](sabre.io/baikal/) - Lightweight CalDAV and CardDAV server based on sabre/dav. ( <b><code>&nbsp;&nbsp;1955⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;268🍴</code></b> [Source Code](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- 🌎 [calypso](keithp.com/calypso/) - Python-based CalDAV and CardDAV server, forked from Radicale.  🌎 [Source Code](keithp.com/git/calypso.git)) `GPL-3.0` `Python`
- 🌎 [DAViCal](www.davical.org/) - Server for calendar sharing (CalDAV) that uses a PostgreSQL database as a data store.  🌎 [Source Code](gitlab.com/davical-project/davical)) `GPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;126⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Davis](https://github.com/tchapi/davis) - A simple, dockerizable and fully translatable admin interface for sabre/dav based on Symfony 5 and Bootstrap 4, largely inspired by Baïkal. `MIT` `PHP`
- 🌎 [DecSync CC](f-droid.org/packages/org.decsync.cc/) - Serverless contacts, calendar synchronization using your own file syncing method i.e Syncthing, Nextcloud etc. ( <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Source Code](https://github.com/39aldo39/DecSyncCC)) `GPL-3.0` `Kotlin`
- 🌎 [Etebase (EteSync)](www.etebase.com/) - End-to-end encrypted and journaled personal information server supporting calendar and contact data, offering its own clients. ( <b><code>&nbsp;&nbsp;1131⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [Source Code](https://github.com/etesync/server)) `AGPL-3.0` `Python/Django`
- 🌎 [Radicale](radicale.org/) - Simple calendar and contact server with extremely low administrative overhead. ( <b><code>&nbsp;&nbsp;2478⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;374🍴</code></b> [Source Code](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python`
- 🌎 [SabreDAV](sabre.io/) - Open source CardDAV, CalDAV, and WebDAV framework and server. ( <b><code>&nbsp;&nbsp;1242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;324🍴</code></b> [Source Code](https://github.com/sabre-io/dav)) `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;228⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Xandikos](https://github.com/jelmer/xandikos) - Open source CardDAV and CalDAV server with minimal administrative overhead, backed by a Git repository. `GPL-3.0` `Python`


### Calendar & Contacts - CalDAV or CardDAV Web-based Clients

**[`^        back to top        ^`](#)**

- 🌎 [AgenDAV](agendav.github.io/agendav/) - Multilanguage CalDAV web client with a rich AJAX interface and shared calendars support. ( <b><code>&nbsp;&nbsp;&nbsp;492⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [Source Code](https://github.com/agendav/agendav)) `GPL-3.0` `PHP`
- 🌎 [Bloben](bloben.com) - CalDAV web client.  🌎 [Demo](demo.bloben.com/api/v1/users/login-demo?username=demo&password=Bg8v16a4q7gvC&redirect=https://demo.bloben.com/calendar?demo=true),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Source Code](https://github.com/nibdo/bloben-app)) `AGPL-3.0` `Docker`
- 🌎 [EteSync Web](www.etesync.com/faq/#web-client) - EteSync's official Web-based client (i.e., their Web app).  🌎 [Demo](client.etesync.com/),  <b><code>&nbsp;&nbsp;&nbsp;216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Source Code](https://github.com/etesync/etesync-web)) `AGPL-3.0` `Javascript`
- 🌎 [InfCloud](www.inf-it.com/open-source/clients/infcloud/) - Open source CalDAV/CardDAV web client implementation.  🌎 [Demo](www.inf-it.com/infcloud/), 🌎 [Source Code](www.inf-it.com/InfCloud_0.13.1.zip)) `AGPL-3.0` `Javascript`


### Communication

**[`^        back to top        ^`](#)**


### Communication - Custom Communication Systems

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [BluetoothCommunicatorExample](https://github.com/niedev/BluetoothCommunicatorExample) - Bluetooth LE chat app to communicate between android devices with P2P architecture. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Clients](https://github.com/niedev/RTranslator)) `Apache-2.0` `Java`
- 🌎 [Centrifugo](centrifugal.dev/) - Language-agnostic real-time messaging (Websocket or SockJS) server. ( <b><code>&nbsp;&nbsp;6232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;499🍴</code></b> [Demo](https://github.com/centrifugal/centrifugo#demo),  <b><code>&nbsp;&nbsp;6232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;499🍴</code></b> [Source Code](https://github.com/centrifugal/centrifugo)) `MIT` `Go`
- 🌎 [Chaskiq](chaskiq.io) - Full featured livechat, helpcenter and CRM as an alternative to Intercom & Drift, Crisp and others. ( <b><code>&nbsp;&nbsp;2037⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;268🍴</code></b> [Source Code](https://github.com/chaskiq/chaskiq)) `AGPL-3.0` `Ruby`
- 🌎 [Chatwoot](www.chatwoot.com) - Self-hosted customer communication platform, an alternative to Intercom & Zendesk. ( <b><code>&nbsp;13232⭐</code></b> <b><code>&nbsp;&nbsp;1664🍴</code></b> [Source Code](https://github.com/chatwoot/chatwoot)) `MIT` `Ruby`
- 🌎 [Conduit](conduit.rs/) - A simple, fast, and reliable chat server powered by Matrix.  🌎 [Source Code](gitlab.com/famedly/conduit)) `Apache-2.0` `Rust`
-  <b><code>&nbsp;&nbsp;&nbsp;739⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [Darkwire.io](https://github.com/darkwire/darkwire.io) - End-to-end encrypted instant web chat. `MIT` `Nodejs`
- 🌎 [Element](element.io) - Fully-featured Matrix client for Web, iOS & Android. ( <b><code>&nbsp;&nbsp;8573⭐</code></b> <b><code>&nbsp;&nbsp;1475🍴</code></b> [Source Code](https://github.com/vector-im/element-web)) `Apache-2.0` `Javascript`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Enigma Reloaded](https://github.com/enigma-reloaded/enigma-reloaded) - DIY Message and file encryption for any platform. `GPL-3.0` `Javascript`
- 🌎 [Freenet](freenetproject.org/index.html) - Anonymously share files, browse and publish _freesites_ (web sites accessible only through Freenet) and chat on forums. ( <b><code>&nbsp;&nbsp;&nbsp;816⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;190🍴</code></b> [Source Code](https://github.com/freenet/fred)) `GPL-2.0` `Java`
- 🌎 [GNUnet](gnunet.org/) - Free software framework for decentralized, peer-to-peer networking.  🌎 [Source Code](gnunet.org/git/)) `GPL-3.0` `C`
- 🌎 [Gotify](gotify.net/) - Self-hosted notification server with Android and CLI clients, similar to PushBullet. ( <b><code>&nbsp;&nbsp;7543⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;412🍴</code></b> [Source Code](https://github.com/gotify/server),  <b><code>&nbsp;&nbsp;&nbsp;513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [Clients](https://github.com/gotify/android)) `MIT` `Go`
- 🌎 [Hawkpost](hawkpost.co) - HawkPost is a web app that lets you create unique links that you can share with a person that desires to send you important information but doesn't know how to encrypt it. The message is encrypted in their browser and sent to your email address. ( <b><code>&nbsp;&nbsp;&nbsp;886⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [Source Code](https://github.com/whitesmith/hawkpost)) `MIT` `Python`
- 🌎 [Jam](jamshelf.com/) - Jam is an open source alternative to Clubhouse: private audio chat rooms to talk to friends and family.  🌎 [Demo](jam.systems/),  <b><code>&nbsp;&nbsp;1050⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [Source Code](https://github.com/jam-systems/jam)) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Jami](jami.net/) - Free and universal communication platform which preserves the user's privacy and freedoms (formerly GNU Ring).  🌎 [Source Code](git.jami.net/savoirfairelinux/jami-project)) `GPL-3.0` `C++`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [KChat](https://github.com/php-kchat/kchat) - PHP Based Live Chat Application. `Apache-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [LeapChat](https://github.com/cryptag/leapchat) - Ephemeral, encrypted, in-browser chat rooms. `AGPL-3.0` `Javascript`
- 🌎 [LibreNews](librenews.io/) - Decentralized and secure breaking news notification system. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/milesmcc/LibreNews-Server/)) `GPL-3.0` `Python`
- 🌎 [Live Helper Chat](livehelperchat.com/) - Live Support chat for your website. ( <b><code>&nbsp;&nbsp;1655⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;650🍴</code></b> [Source Code](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- 🌎 [Mattermost](mattermost.org/) - Open-source, on-prem Slack-alternative. It can be integrated with Gitlab. ( <b><code>&nbsp;23540⭐</code></b> <b><code>&nbsp;&nbsp;5595🍴</code></b> [Source Code](https://github.com/mattermost/mattermost-server)) `AGPL-3.0/Apache-2.0` `Go`
- 🌎 [MiAOU](miaou.dystroy.org/login) - Multi-room persistent chat server. ( <b><code>&nbsp;&nbsp;&nbsp;513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Source Code](https://github.com/Canop/miaou)) `MIT` `Nodejs`
- 🌎 [Mibew](mibew.org) - Mibew Messenger is an open-source live support application written in PHP and MySQL. It enables one-on-one chat assistance in real-time directly from your website.  🌎 [Demo](mibew.org/demo2),  <b><code>&nbsp;&nbsp;&nbsp;439⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [Source Code](https://github.com/Mibew/mibew)) `Apache-2.0` `PHP`
- 🌎 [Mumble](wiki.mumble.info/wiki/Main_Page) - Low-latency, high quality voice/text chat software. ( <b><code>&nbsp;&nbsp;4888⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;973🍴</code></b> [Source Code](https://github.com/mumble-voip/mumble), 🌎 [Clients](wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++`
-  <b><code>&nbsp;&nbsp;&nbsp;241⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Notifo](https://github.com/notifo-io/notifo) - Multichannel notification server with support for Email, Mobile Push, Web Push, SMS, messaging and a javascript plugin. `MIT` `C#`
- 🌎 [ntfy](ntfy.sh/) - Push notifications to phone or desktop using HTTP PUT/POST, with Android app, CLI and web app, similar to Pushover and Gotify.  🌎 [Demo](ntfy.sh/app),  <b><code>&nbsp;&nbsp;2524⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Source Code](https://github.com/binwiederhier/ntfy),  <b><code>&nbsp;&nbsp;&nbsp;151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Clients](https://github.com/binwiederhier/ntfy-android)) `Apache-2.0/GPL-2.0` `Go`
- 🌎 [OTS](ots.fyi/) - One-Time-Secret sharing platform with a symmetric 256bit AES encryption in the browser. ( <b><code>&nbsp;&nbsp;&nbsp;198⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Source Code](https://github.com/Luzifer/ots)) `Apache-2.0` `Go`
- 🌎 [Papercups](papercups.io/) - An open source live customer chat web app written in Elixir.  🌎 [Demo](app.papercups.io/demo),  <b><code>&nbsp;&nbsp;4904⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;375🍴</code></b> [Source Code](https://github.com/papercups-io/papercups)) `MIT` `Elixir`
-  <b><code>&nbsp;&nbsp;&nbsp;164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [PushBits](https://github.com/pushbits/server) - Self-hosted notification server for relaying push notifications via Matrix, similar to PushBullet and Gotify. `ISC` `Go`
- 🌎 [Rallly](rallly.co) - Rallly is an open-source alternative to Doodle that lets you create polls to vote on dates and times. ( <b><code>&nbsp;&nbsp;&nbsp;942⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [Source Code](https://github.com/lukevella/Rallly)) `AGPL-3.0` `Nodejs`
- 🌎 [RetroShare](retroshare.cc) - Secured and decentralized communication system. Offers decentralized chat, forums, messaging, file transfer. ( <b><code>&nbsp;&nbsp;1475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;253🍴</code></b> [Source Code](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `C++`
- 🌎 [Revolt](revolt.chat/) - Revolt is a user-first chat platform built with modern web technologies. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/revoltchat)) `AGPL-3.0` `Rust`
- 🌎 [Rocket.Chat](rocket.chat/) - Teamchat solution similar to Gitter.im or Slack. ( <b><code>&nbsp;32664⭐</code></b> <b><code>&nbsp;&nbsp;7496🍴</code></b> [Source Code](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Screensy](https://github.com/screensy/screensy) - Simple peer-to-peer screen sharing solution for sharing your screen with WebRTC.  🌎 [Demo](screensy.stef.link)) `GPL-3.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Shhh](https://github.com/smallwat3r/shhh) - Keep secrets out of emails or chat logs, share them using secure links with passphrase and expiration dates. `MIT` `Python`
-  <b><code>&nbsp;&nbsp;1363⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [SimpleX Chat](https://github.com/simplex-chat/simplex-chat) - The most private and secure chat and applications platform - now with double ratchet E2E encryption. `AGPL-3.0` `Haskell`
- 🌎 [Soketi](soketi.app/) - Soketi is a free, open-source Pusher drop-in alternative. ( <b><code>&nbsp;&nbsp;2124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/soketi/soketi)) `MIT` `Nodejs`
- 🌎 [Spectrum 2](spectrum.im/) - Spectrum 2 is an open source instant messaging transport.  It allows users to chat together even when they are using different IM networks. ( <b><code>&nbsp;&nbsp;&nbsp;335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/SpectrumIM/spectrum2)) `GPL-3.0` `C++`
- 🌎 [StoneAge Messenger](cweb.gitlab.io/StoneAge.html) - A self-hosted Android messenger, S3-compatible storage is the only backend needed.  🌎 [Source Code](gitlab.com/cweb-repos/cweb-conversations), 🌎 [Clients](f-droid.org/en/packages/com.cweb.messenger/)) `GPL-3.0` `Java`
- 🌎 [Synapse](matrix.org/docs/projects/server/synapse) - Server for 🌎 [Matrix](matrix.org/), an open standard for decentralized persistent communication. ( <b><code>&nbsp;&nbsp;9702⭐</code></b> <b><code>&nbsp;&nbsp;1808🍴</code></b> [Source Code](https://github.com/matrix-org/synapse)) `Apache-2.0` `Python`
- 🌎 [Syndie](syndie.de) - Syndie is a libre system for operating distributed forums. `CC0-1.0` `Java`
-  <b><code>&nbsp;&nbsp;2433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;427🍴</code></b> [TextBelt](https://github.com/typpo/textbelt) `⚠` - Outgoing SMS API that uses carrier-specific gateways to deliver your text messages for free, and without ads. `MIT` `Javascript`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Tinode](https://github.com/tinode) - Instant messaging platform. Backend in Go. Clients: Swift iOS, Java Android, JS webapp, scriptable command line; chatbots.  🌎 [Demo](sandbox.tinode.co/),  <b><code>&nbsp;&nbsp;9022⭐</code></b> <b><code>&nbsp;&nbsp;1389🍴</code></b> [Source Code](https://github.com/tinode/chat),  <b><code>&nbsp;&nbsp;&nbsp;219⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [Clients](https://github.com/tinode/webapp)) `GPL-3.0` `Go`
- 🌎 [Tox](tox.chat/) - Distributed, secure messenger with audio and video chat capabilities. ( <b><code>&nbsp;&nbsp;1755⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;263🍴</code></b> [Source Code](https://github.com/TokTok/c-toxcore)) `GPL-3.0` `C`
- 🌎 [Tuber](blog.trailofbits.com/2015/12/15/self-hosted-video-chat-with-tuber/) - Peer-to-peer video chat that works. ( <b><code>&nbsp;&nbsp;&nbsp;353⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [Source Code](https://github.com/trailofbits/tubertc)) `MIT` `Javascript`
- 🌎 [Typebot](typebot.io) - Typebot is a conversational app builder as an alternative to Typeform or Landbot. ( <b><code>&nbsp;&nbsp;1271⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [Source Code](https://github.com/baptisteArno/typebot.io)) `AGPL-3.0` `Docker`
-  <b><code>&nbsp;&nbsp;1321⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;305🍴</code></b> [WBO](https://github.com/lovasoa/whitebophir#wbo) -  A web Whiteboard to collaborate in real-time on schemas, drawings, and notes.  🌎 [Demo](wbo.ophir.dev/)) `AGPL-3.0` `Nodejs/Docker`
- 🌎 [ZeroNet](zeronet.io/) `⚠` - Open, free, and uncensorable websites, using Bitcoin cryptography and BitTorrent network. ( <b><code>&nbsp;17556⭐</code></b> <b><code>&nbsp;&nbsp;2254🍴</code></b> [Source Code](https://github.com/HelloZeroNet/ZeroNet)) `GPL-2.0` `Python`
- 🌎 [Zulip](zulip.org) - Zulip is a powerful, open source group chat application. ( <b><code>&nbsp;16111⭐</code></b> <b><code>&nbsp;&nbsp;5428🍴</code></b> [Source Code](https://github.com/zulip/zulip)) `Apache-2.0` `Python`


### Communication - Email

**[`^        back to top        ^`](#)**


### Communication - Email - Complete Solutions

**[`^        back to top        ^`](#)**

Simple deployment of a mail server, e.g. for inexperienced or impatient admins.

- 🌎 [AnonAddy](anonaddy.com) - Open source email forwarding service for creating aliases. ( <b><code>&nbsp;&nbsp;1830⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [Source Code](https://github.com/anonaddy/anonaddy)) `MIT` `PHP`
- 🌎 [DebOps](docs.debops.org/) - Your Debian-based data center in a box. A set of general-purpose Ansible roles that can be used to manage Debian or Ubuntu hosts. ( <b><code>&nbsp;&nbsp;&nbsp;941⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;308🍴</code></b> [Source Code](https://github.com/debops/debops)) `GPL-3.0-only` `YAML/Ansible/Python`
- 🌎 [docker-mailserver](docker-mailserver.github.io/docker-mailserver/edge/) - Production-ready fullstack but simple mail server (SMTP, IMAP, LDAP, Antispam, Antivirus, etc.) running inside a container. Only configuration files, no SQL database. ( <b><code>&nbsp;&nbsp;9306⭐</code></b> <b><code>&nbsp;&nbsp;1379🍴</code></b> [Source Code](https://github.com/docker-mailserver/docker-mailserver)) `MIT` `Docker`
-  <b><code>&nbsp;&nbsp;1003⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;194🍴</code></b> [emailwiz](https://github.com/LukeSmithxyz/emailwiz) - Luke Smith's bash script to completely automate the setup of a Postfix/Dovecot/SpamAssassin/OpenDKIM server on debian. `GPL-3.0` `Bash`
-  <b><code>&nbsp;&nbsp;&nbsp;126⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Excision Mail](https://github.com/Excision-Mail/Excision-Mail) - Fullstack, security focused mailserver based on OpenSMTPD for OpenBSD using ansible. `ISC` `Shell/Ansible`
-  <b><code>&nbsp;&nbsp;&nbsp;322⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [homebox](https://github.com/progmaticltd/homebox) - Suite of Ansible scripts to deploy a fully functional mail server on Debian. Unobtrusive and automatic as much as possible, focusing on stability and security. `GPL-3.0` `Shell`
- 🌎 [Inboxen](inboxen.org) - Inboxen is a service that provides you with an infinite number of unique inboxes. ( <b><code>&nbsp;&nbsp;&nbsp;243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Source Code](https://github.com/Inboxen/Inboxen)) `GPL-3.0` `Python`
- 🌎 [iRedMail](www.iredmail.org/) - Full-featured mail server solution based on Postfix and Dovecot. ( <b><code>&nbsp;&nbsp;&nbsp;818⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;157🍴</code></b> [Source Code](https://github.com/iredmail/iRedMail)) `GPL-3.0` `Shell`
-  <b><code>&nbsp;&nbsp;3186⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [Maddy Mail Server](https://github.com/foxcpp/maddy) - All-in-one mail server that implements SMTP (both MTA and MX) and IMAP. Replaces Postfix, Dovecot, OpenDKIM, OpenSPF, OpenDMARC with single daemon. `GPL-3.0` `Go`
- 🌎 [Mail-in-a-Box](mailinabox.email/) - Turns any Ubuntu server into a fully functional mail server with one command. ( <b><code>&nbsp;11221⭐</code></b> <b><code>&nbsp;&nbsp;1232🍴</code></b> [Source Code](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- 🌎 [Mailcow](mailcow.email/) - Mail server suite based on Dovecot, Postfix and other open source software, that provides a modern Web UI for administration. ( <b><code>&nbsp;&nbsp;5374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;855🍴</code></b> [Source Code](https://github.com/mailcow/mailcow-dockerized)) `GPL-2.0` `Docker/PHP`
- 🌎 [Mailu](mailu.io/) - Mailu is a simple yet full-featured mail server as a set of Docker images. ( <b><code>&nbsp;&nbsp;3813⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;653🍴</code></b> [Source Code](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- 🌎 [Modoboa](modoboa.org/en/) - Modoboa is a mail hosting and management platform including a modern and simplified Web User Interface. ( <b><code>&nbsp;&nbsp;2169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [Source Code](https://github.com/modoboa/modoboa)) `ISC` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Ptorx](https://github.com/xyfir/ptorx) - Email privacy. Anonymously send and receive with alias forwarding. `GPL-3.0` `Nodejs`
- 🌎 [Simple NixOS Mailserver](gitlab.com/simple-nixos-mailserver/nixos-mailserver) - Complete mailserver solution leveraging the Nix Ecosystem. `GPL-3.0` `Nix`
- 🌎 [SimpleLogin](simplelogin.io) - Open source email alias solution to protect your email address. Comes with browser extensions and mobile apps. ( <b><code>&nbsp;&nbsp;2679⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;258🍴</code></b> [Source Code](https://github.com/simple-login/app)) `MIT` `Docker/Python`
- 🌎 [wildduck](wildduck.email/) - Scalable no-SPOF IMAP/POP3 mail server. ( <b><code>&nbsp;&nbsp;1551⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;235🍴</code></b> [Source Code](https://github.com/nodemailer/wildduck)) `EUPL-1.2` `Nodejs`


### Communication - Email - Mail Delivery Agents

**[`^        back to top        ^`](#)**

MDAs - IMAP/POP3 software

- 🌎 [Cyrus IMAP](www.cyrusimap.org/) - Email (IMAP/POP3), contacts and calendar server. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/cyrusimap/cyrus-imapd )) `BSD-3-Clause-Attribution` `C`
- 🌎 [Dovecot](www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind. ( <b><code>&nbsp;&nbsp;&nbsp;689⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;239🍴</code></b> [Source Code](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [MailForm](https://github.com/Feuerhamster/mailform) - Lightweight self-hosted open source alternative to Formspree and SendGrid. `Apache-2.0` `Nodejs`
- 🌎 [Piler](www.mailpiler.org/wiki/start) - Feature-rich open source email archiving solution.  🌎 [Source Code](bitbucket.org/jsuto/piler)) `GPL-3.0` `C`


### Communication - Email - Mail Transfer Agents

**[`^        back to top        ^`](#)**

MTAs / SMTP servers

- 🌎 [chasquid](blitiri.com.ar/p/chasquid/) - SMTP (email) server with a focus on simplicity, security, and ease of operation.  🌎 [Source Code](blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- 🌎 [Courier MTA](www.courier-mta.org/) - Fast, scalable, enterprise mail/groupware server providing ESMTP, IMAP, POP3, webmail, mailing list, basic web-based calendaring and scheduling services.  🌎 [Source Code](www.courier-mta.org/repo.html)) `GPL-3.0` `C`
- 🌎 [Exim](www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge.  🌎 [Source Code](git.exim.org/exim.git)) `GPL-3.0` `C`
- 🌎 [Haraka](haraka.github.io/) - High-performance, pluginable SMTP server written in Javascript. ( <b><code>&nbsp;&nbsp;4200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;622🍴</code></b> [Source Code](https://github.com/haraka/Haraka)) `MIT` `Javascript`
- 🌎 [MailCatcher](mailcatcher.me/) - Ruby gem that deploys a simply SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. ( <b><code>&nbsp;&nbsp;5689⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;534🍴</code></b> [Source Code](https://github.com/sj26/mailcatcher)) `MIT` `Ruby`
- 🌎 [Maildrop](gitlab.com/markbeeson/maildrop) - Disposable email SMTP server, also useful for development. `MIT` `Scala`
-  <b><code>&nbsp;10480⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;837🍴</code></b> [MailHog](https://github.com/mailhog/MailHog) - Small Golang executable which runs an SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. `MIT` `Go`
- 🌎 [OpenSMTPD](opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project.  🌎 [Source Code](cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C`
- [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement. `IPL-1.0` `C`
- 🌎 [Qmail](cr.yp.to/qmail.html) - Secure Sendmail replacement.  🌎 [Source Code](sources.debian.net/src/netqmail/1.06-5/)) `CC0-1.0` `C`
- 🌎 [Sendmail](www.proofpoint.com/us/products/email-protection/open-source-email-solution) - Message transfer agent (MTA). `Sendmail` `C`
- 🌎 [Slimta](www.slimta.org) - Mail Transfer Library built on Python. ( <b><code>&nbsp;&nbsp;&nbsp;158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Source Code](https://github.com/slimta/python-slimta)) `MIT` `Python`


### Communication - Email - Mailing Lists and Newsletters

**[`^        back to top        ^`](#)**

Mailing lists servers and mass mailing software - one message to many recipients.

- 🌎 [Dada Mail](dadamailproject.com/) - Web-based list management system that can be used for announcement lists and/or discussion lists. ( <b><code>&nbsp;&nbsp;&nbsp;140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Source Code](https://github.com/justingit/dada-mail)) `GPL-2.0` `Perl`
- 🌎 [Gray Duck Mail](grayduckmail.com) - Self hosted email discussion list management that uses external email providers. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Source Code](https://github.com/wagesj45/gray-duck-mail)) `GPL-3.0` `Docker`
- 🌎 [HyperKitty](wiki.list.org/HyperKitty) - Open source Django application to provide a web interface to access GNU Mailman v3 archives.  🌎 [Demo](lists.mailman3.org/), 🌎 [Source Code](gitlab.com/mailman/hyperkitty)) `GPL-3.0` `Python`
- 🌎 [Keila](www.keila.io) - Self-hosted reliable and easy-to-use newsletter tool. Alternative to proprietary services like Mailchimp or Sendinblue.  🌎 [Demo](app.keila.io),  <b><code>&nbsp;&nbsp;&nbsp;595⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Source Code](https://github.com/pentacent/keila)) `AGPL-3.0` `Elixir`
- 🌎 [Listmonk](listmonk.app/) - High performance, self-hosted newsletter and mailing list manager with a modern dashboard. ( <b><code>&nbsp;&nbsp;8333⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;634🍴</code></b> [Source Code](https://github.com/knadh/listmonk)) `AGPL-3.0` `Go`
- 🌎 [Mailman](www.gnu.org/software/mailman/) - The Gnu mailing list server. `GPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;5062⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;691🍴</code></b> [Mailtrain](https://github.com/Mailtrain-org/mailtrain) - Self hosted newsletter application. `GPL-3.0` `Nodejs`
- 🌎 [Mautic](www.mautic.org/) - Mautic is marketing automation software (email, social and more). ( <b><code>&nbsp;&nbsp;5234⭐</code></b> <b><code>&nbsp;&nbsp;1960🍴</code></b> [Source Code](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- 🌎 [phpList](phplist.org) - Newsletter and email marketing with advanced management of subscribers, bounces, and plugins. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/phpList/)) `AGPL-3.0` `PHP`
- 🌎 [Postal](postal.atech.media/) - Fully featured open source mail delivery platform for incoming and outgoing e-mail. ( <b><code>&nbsp;11857⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;849🍴</code></b> [Source Code](https://github.com/postalhq/postal)) `MIT` `Ruby`
- 🌎 [Postorius](docs.mailman3.org/projects/postorius/en/latest/) - Web user interface to access GNU Mailman.  🌎 [Source Code](gitlab.com/mailman/postorius/)) `GPL-3.0` `Python`
- 🌎 [Schleuder](schleuder.nadir.org/) - GPG-enabled mailing list manager with resending-capabilities.  🌎 [Source Code](0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- 🌎 [Sympa](www.sympa.org/) - Mailing list manager. `GPL-2.0` `Perl`


### Communication - Email - Webmail Clients

**[`^        back to top        ^`](#)**
 🌎 [Webmail](en.wikipedia.org/wiki/Webmail) clients for email 

- 🌎 [Afterlogic WebMail Lite](afterlogic.org/webmail-lite) - Fast and easy-to-use webmail front-end for your existing IMAP mail server, Plesk or cPanel.  🌎 [Demo](lite.afterlogic.com/),  <b><code>&nbsp;&nbsp;&nbsp;422⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [Source Code](https://github.com/afterlogic/webmail-lite)) `AGPL-3.0` `PHP`
- 🌎 [Cypht](cypht.org) - Feed reader for your email accounts. ( <b><code>&nbsp;&nbsp;&nbsp;732⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [Source Code](https://github.com/jasonmunro/cypht)) `LGPL-2.1` `PHP`
- 🌎 [IMP](www.horde.org/apps/imp/) - HORDE application that provides webmail access to IMAP and POP3 accounts. ([Demo](http://demo.horde.org/), 🌎 [Source Code](www.horde.org/download/imp)) `GPL-2.0` `PHP`
- 🌎 [Isotope Mail](blog.marcnuri.com/isotope-mail-client-introduction/) - Microservice based webmail client built with ReactJS and Spring. ( <b><code>&nbsp;&nbsp;&nbsp;192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Source Code](https://github.com/manusa/isotope-mail)) `Apache-2.0` `Docker/Java`
- 🌎 [MailCare](mailcare.io) - Open source disposable email address service. ( <b><code>&nbsp;&nbsp;&nbsp;216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Source Code](https://github.com/mailcare/mailcare)) `MIT` `PHP`
- 🌎 [Mailpile](www.mailpile.is/) - Webmail client with search, filtering, encryption features and more. ( <b><code>&nbsp;&nbsp;8616⭐</code></b> <b><code>&nbsp;&nbsp;1051🍴</code></b> [Source Code](https://github.com/mailpile/Mailpile)) `AGPL-3.0` `Python`
- 🌎 [Roundcube](roundcube.net) - Browser-based IMAP client with an application-like user interface. ( <b><code>&nbsp;&nbsp;4476⭐</code></b> <b><code>&nbsp;&nbsp;1500🍴</code></b> [Source Code](https://github.com/roundcube/roundcubemail)) `GPL-3.0` `PHP`
- 🌎 [SnappyMail](snappymail.eu/) - Simple, modern, lightweight & fast web-based email client. (It is an actively developed fork of RainLoop).  🌎 [Demo](snappymail.eu/demo/),  <b><code>&nbsp;&nbsp;&nbsp;308⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Source Code](https://github.com/the-djmaze/snappymail)) `AGPL-3.0` `PHP`
- 🌎 [SquirrelMail](squirrelmail.org) - Another browser-based IMAP client.  🌎 [Source Code](sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`


### Communication - IRC

**[`^        back to top        ^`](#)**
 🌎 [IRC](en.wikipedia.org/wiki/Internet_Relay_Chat) communication software

- 🌎 [Convos](convos.chat/) - Always online web IRC client.  🌎 [Demo](convos.chat/#instant-demo),  <b><code>&nbsp;&nbsp;&nbsp;891⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Source Code](https://github.com/nordaaker/convos)) `Artistic-2.0` `Perl`
-  <b><code>&nbsp;&nbsp;&nbsp;633⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Dispatch](https://github.com/khlieng/dispatch) - Self-hosted web IRC client written in Go. `MIT` `Go`
- 🌎 [Ergo](ergo.chat/) - Modern IRCv3 server written in Go, combining the features of an ircd, a services framework, and a bouncer. ( <b><code>&nbsp;&nbsp;1759⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [Source Code](https://github.com/ergochat/ergo)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;887⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [Glowing Bear](https://github.com/glowing-bear/glowing-bear) - A web frontend for WeeChat.  🌎 [Demo](www.glowing-bear.org)) `GPL-3.0` `Javascript`
- 🌎 [InspIRCd](www.inspircd.org/) - Modular IRC server written in C++ for Linux, BSD, Windows, and macOS. ( <b><code>&nbsp;&nbsp;&nbsp;976⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;256🍴</code></b> [Source Code](https://github.com/inspircd/inspircd)) `GPL-2.0` `C++`
- 🌎 [Kiwi IRC](kiwiirc.com/) - Responsive web IRC client with theming support.  🌎 [Demo](kiwiirc.com/nextclient/),  <b><code>&nbsp;&nbsp;&nbsp;665⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;212🍴</code></b> [Source Code](https://github.com/kiwiirc/kiwiirc)) `Apache-2.0` `Nodejs`
- 🌎 [ngircd](ngircd.barton.de/) - Free, portable and lightweight Internet Relay Chat server for small or private networks. ( <b><code>&nbsp;&nbsp;&nbsp;337⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Source Code](https://github.com/ngircd/ngircd)) `GPL-2.0` `C`
- 🌎 [Quassel IRC](quassel-irc.org/) - Distributed IRC client, meaning that one (or multiple) client(s) can attach to and detach from a central core. ( <b><code>&nbsp;&nbsp;&nbsp;652⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [Source Code](https://github.com/quassel/quassel)) `GPL-2.0` `C++`
- 🌎 [Robust IRC](robustirc.net/) - RobustIRC is IRC without netsplits. Distributed IRC server, based on RobustSession protocol. ( <b><code>&nbsp;&nbsp;&nbsp;157⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Source Code](https://github.com/robustirc/robustirc)) `BSD-3-Clause` `Go`
- 🌎 [The Lounge](thelounge.chat/) - Self-hosted web IRC client.  🌎 [Demo](demo.thelounge.chat/),  <b><code>&nbsp;&nbsp;4802⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;615🍴</code></b> [Source Code](https://github.com/thelounge/thelounge)) `MIT` `Nodejs`
- 🌎 [Tiny Tiny IRC](tt-rss.org/tt-irc/) - An open source AJAX-powered chat platform with support for IRC  🌎 [Source Code](git.tt-rss.org/fox/tt-irc)). `GPL-3.0` `PHP/Java`
- 🌎 [UnrealIRCd](www.unrealircd.org/) - Modular, advanced and highly configurable IRC server written in C for Linux, BSD, Windows, and macOS. ( <b><code>&nbsp;&nbsp;&nbsp;335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;125🍴</code></b> [Source Code](https://github.com/unrealircd/unrealircd)) `GPL-2.0` `C`
- 🌎 [Weechat](weechat.org/) - Fast, light and extensible chat client. `GPL-3.0` `C`
- 🌎 [ZNC](wiki.znc.in/ZNC) - Advanced IRC bouncer. ( <b><code>&nbsp;&nbsp;1889⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;385🍴</code></b> [Source Code](https://github.com/znc/znc)) `Apache-2.0` `C++`


### Communication - SIP

**[`^        back to top        ^`](#)**
 🌎 [SIP](en.wikipedia.org/wiki/Session_Initiation_Protocol) 🌎 [IPBX](en.wikipedia.org/wiki/IP_PBX) telephony software

- 🌎 [Asterisk](www.asterisk.org/) - Easy to use but advanced IP PBX system, VoIP gateway and conference server. `GPL-2.0` `C`
- 🌎 [ASTPP](www.astppbilling.org/) - VoIP Billing Solution for Freeswitch. It supports prepaid and postpaid billing with call rating and credit control. It also provides many other features. ( <b><code>&nbsp;&nbsp;&nbsp;130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;153🍴</code></b> [Source Code](https://github.com/iNextrix/ASTPP)) `AGPL-3.0` `PHP`
- 🌎 [Eqivo](eqivo.org/) - Eqivo implements an API layer on top of FreeSWITCH facilitating integration between web applications and voice/video-enabled endpoints such as traditional phone lines (PSTN), VoIP phones, webRTC clients etc. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Source Code](https://github.com/rtckit/eqivo)) `MIT` `PHP`
- 🌎 [Freepbx](www.freepbx.org) - Web-based open source GUI that controls and manages Asterisk.  🌎 [Source Code](git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- 🌎 [FreeSWITCH](freeswitch.org/) - Scalable open source cross-platform telephony platform.  🌎 [Source Code](freeswitch.org/stash/projects/FS/repos/freeswitch/browse)) `MPL-2.0` `C`
- 🌎 [FusionPBX](www.fusionpbx.com/) - Open source project that provides a customizable and flexible web interface to the very powerful and highly scalable multi-platform voice switch called FreeSWITCH. ( <b><code>&nbsp;&nbsp;&nbsp;580⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;580🍴</code></b> [Source Code](https://github.com/fusionpbx/fusionpbx)) `MPL-1.1` `PHP`
- 🌎 [Kamailio](www.kamailio.org/w/) - Modular SIP server (registrar/proxy/router/etc). ( <b><code>&nbsp;&nbsp;1663⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;782🍴</code></b> [Source Code](https://github.com/kamailio/kamailio)) `GPL-2.0` `C`
- 🌎 [Kazoo](2600hz.org/) - KAZOO is an open-source, highly scalable software platform designed to provide carrier-grade VoIP switch functions and features. ( <b><code>&nbsp;&nbsp;&nbsp;881⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;446🍴</code></b> [Source Code](https://github.com/2600hz/KAZOO)) `MPL-1.1` `Erlang`
- 🌎 [Routr](routr.io) - A lightweight sip proxy, location server, and registrar for a reliable and scalable SIP infrastructure. ( <b><code>&nbsp;&nbsp;&nbsp;935⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [Source Code](https://github.com/fonoster/routr)) `MIT` `Javascript`
- 🌎 [SIP3](sip3.io/) - VoIP troubleshooting and monitoring platform.  🌎 [Demo](demo.sip3.io),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/sip3io/)) `Apache-2.0` `Kotlin`
- 🌎 [SIPCAPTURE Homer](www.sipcapture.org/) - Troubleshooting and monitoring VoIP calls. ( <b><code>&nbsp;&nbsp;1174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [Source Code](https://github.com/sipcapture/homer)) `AGPL-3.0` `Angular/C`
- 🌎 [SipXcom](sipxcom.org/) - Open source unified communications system. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Source Code](https://github.com/sipXcom/sipxecs)) `AGPL-3.0` `Java`
- 🌎 [Wazo](wazo-platform.org/) - Full-featured IPBX solution built atop Asterisk with integrated Web administration interface and REST-ful API. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/wazo-platform)) `GPL-3.0` `Python`
- 🌎 [Yeti-Switch](yeti-switch.org/) - Transit class4 softswitch(SBC) with integrated billing and routing engine and REST API.  🌎 [Demo](yeti-switch.org/demo.html),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/yeti-switch)) `GPL-2.0` `C++/Ruby`


### Communication - Social Networks and Forums

**[`^        back to top        ^`](#)**
 🌎 [Social Networking](en.wikipedia.org/wiki/Social_networking_service) and 🌎 [Forum](en.wikipedia.org/wiki/Internet_forum) software

-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Abilian SBE](https://github.com/abilian/abilian-sbe) - Open Source Collaboration and Social Networking framework and platform. `LGPL-2.1` `Python`
- 🌎 [Anahita](www.getanahita.com/) - Open Source Social Networking Framework and Platform. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/anahitasocial)) `GPL-3.0` `PHP`
- 🌎 [AsmBB](board.asm32.info) - A fast, SQLite-powered forum engine written in ASM.  🌎 [Source Code](asm32.info/fossil/asmbb/index)) `EUPL-1.2` `Assembly`
- 🌎 [bbPress](bbpress.org/) - Forum software with a twist from the creators of WordPress. Easily setup discussion forums inside your WordPress.org powered site.  🌎 [Source Code](bbpress.trac.wordpress.org/browser/trunk)) `GPL-2.0` `PHP`
- 🌎 [Bibliogram](bibliogram.art) `⚠` - An alternative front-end for Instagram.  🌎 [Source Code](sr.ht/~cadence/bibliogram/)) `AGPL-3.0` `Nodejs`
- 🌎 [Bootcamp](trybootcamp.vitorfs.com) - Enterprise social network. ( <b><code>&nbsp;&nbsp;2143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;998🍴</code></b> [Source Code](https://github.com/vitorfs/bootcamp)) `MIT` `Python`
- [Buddycloud](http://buddycloud.com/) - Tools, libraries, services and a community to build user-to-user, group and social messaging into your app. Saves time. Scales up. Supports you. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/buddycloud)) `Apache-2.0` `Java`
- 🌎 [BuddyPress](buddypress.org/about/) - Powerful plugin that takes your WordPress.org powered site beyond the blog with social-network features like user profiles, activity streams, user groups, and more. ( <b><code>&nbsp;&nbsp;&nbsp;193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [Source Code](https://github.com/buddypress/BuddyPress)) `GPL-2.0` `PHP`
- 🌎 [Cactus Comments](cactus.chat/) - Cactus Comments is a federated comment system for the open web built on Matrix.  🌎 [Demo](cactus.chat/demo/), 🌎 [Source Code](gitlab.com/cactus-comments/)) `GPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [cartulary](https://github.com/daveajones/cartulary) - RSS reader, readability tool, article archiver, microblogger, social graph manager and reading list manager. `CDDL-1.0` `PHP`
- 🌎 [Commento](gitlab.com/commento/commento) - Commento is a discussion platform that you can embed on your blog, news articles, and any place where you want your readers to add comments. `MIT` `Go`
- 🌎 [Coral](coralproject.net/) - A better commenting experience from Vox Media. ( <b><code>&nbsp;&nbsp;1769⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;335🍴</code></b> [Source Code](https://github.com/coralproject/talk)) `Apache-2.0` `Nodejs`
- 🌎 [diaspora*](diasporafoundation.org/) - Distributed social networking server. ( <b><code>&nbsp;13094⭐</code></b> <b><code>&nbsp;&nbsp;2944🍴</code></b> [Source Code](https://github.com/diaspora/diaspora)) `AGPL-3.0` `Ruby`
- 🌎 [Discourse](www.discourse.org/) - Advanced forum / community solution based on Ruby and JS.  🌎 [Demo](try.discourse.org/),  <b><code>&nbsp;36069⭐</code></b> <b><code>&nbsp;&nbsp;7742🍴</code></b> [Source Code](https://github.com/discourse/discourse)) `GPL-2.0` `Ruby`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [dyu comments](https://github.com/dyu/comments) - Real-time, markdown-enabled comment engine powered by leveldb.  🌎 [Demo](dyu.github.io/comments/real-time/)) `Apache-2.0` `Java`
- 🌎 [Elgg](elgg.org/) - Powerful open source social networking engine. ( <b><code>&nbsp;&nbsp;1534⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;672🍴</code></b> [Source Code](https://github.com/Elgg/Elgg)) `GPL-2.0` `PHP`
- 🌎 [Enigma 1/2 BBS](nuskooler.github.io/enigma-bbs/) - Enigma 1/2 is a modern, multi-platform BBS engine with unlimited "callers" and legacy DOS door game support.  🌎 [Demo](l33t.codes/xibalba-bbs/),  <b><code>&nbsp;&nbsp;&nbsp;375⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Source Code](https://github.com/NuSkooler/enigma-bbs)) `BSD-2-Clause` `Nodejs/Javascript`
-  <b><code>&nbsp;&nbsp;&nbsp;126⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [EpochTalk](https://github.com/epochtalk/epochtalk) - Next Generation Forum Software. `MIT` `Nodejs`
- 🌎 [Flarum](flarum.org) - Delightfully simple forums. Flarum is the next-generation forum software that makes online discussion fun again. ( <b><code>&nbsp;13004⭐</code></b> <b><code>&nbsp;&nbsp;1410🍴</code></b> [Source Code](https://github.com/flarum/flarum)) `MIT` `PHP`
- 🌎 [FlaskBB](flaskbb.org/) - FlaskBB is forum software written in Python using the microframework Flask. You can easily create new topics, posts and send other users private messages. It also includes basic administration and moderation tools. ( <b><code>&nbsp;&nbsp;2219⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;559🍴</code></b> [Source Code](https://github.com/flaskbb/flaskbb)) `BSD-3-Clause` `Python`
- 🌎 [FluxBB](fluxbb.org/) - Fast, light, user-friendly forum software for your website. ( <b><code>&nbsp;&nbsp;&nbsp;471⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [Source Code](https://github.com/fluxbb/fluxbb)) `GPL-2.0` `PHP`
- 🌎 [Friendica](friendi.ca/) - Social Communication Server. ( <b><code>&nbsp;&nbsp;1049⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;281🍴</code></b> [Source Code](https://github.com/friendica/friendica)) `AGPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Glosa](https://github.com/glosa/glosa-server) - Open source commentary system easy to integrate with static pages. You can import from Disqus. `GPL-3.0` `Java`
- 🌎 [GNU social](gnu.io/social/) - Social communication software for both public and private communications.  🌎 [Source Code](notabug.org/diogo/gnu-social)) `AGPL-3.0` `PHP`
- 🌎 [Hubzilla](hubzilla.org) - Decentralized identity, privacy, publishing, sharing, cloud storage, and communications/social platform.  🌎 [Source Code](framagit.org/hubzilla/core)) `MIT` `PHP`
- 🌎 [HumHub](www.humhub.org/) - Flexible kit for private social networks. ( <b><code>&nbsp;&nbsp;5842⭐</code></b> <b><code>&nbsp;&nbsp;1611🍴</code></b> [Source Code](https://github.com/humhub/humhub)) `AGPL-3.0` `PHP`
- 🌎 [Isso](posativ.org/isso/) - Lightweight commenting server written in Python and Javascript. It aims to be a drop-in replacement for Disqus. ( <b><code>&nbsp;&nbsp;4607⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;419🍴</code></b> [Source Code](https://github.com/posativ/isso)) `MIT` `Python`
- 🌎 [Lemmy](join-lemmy.org/) - A link aggregator / reddit clone for the fediverse. Reddit alternative built in Rust. ( <b><code>&nbsp;&nbsp;6541⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;415🍴</code></b> [Source Code](https://github.com/LemmyNet/lemmy)) `AGPL-3.0` `Rust`
- 🌎 [Libreddit](libredd.it/) `⚠` - Private front-end for Reddit written in Rust. ( <b><code>&nbsp;&nbsp;3100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [Source Code](https://github.com/spikecodes/libreddit)) `AGPL-3.0` `Rust`
- 🌎 [Loomio](www.loomio.org/) - Loomio is a collaborative decision-making tool that makes it easy for anyone to participate in decisions which affect them. ( <b><code>&nbsp;&nbsp;2115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;660🍴</code></b> [Source Code](https://github.com/loomio/loomio)) `AGPL-3.0` `Ruby`
- 🌎 [Mastodon](joinmastodon.org/) - Federated microblogging server, an alternative to GNU social. ( <b><code>&nbsp;29636⭐</code></b> <b><code>&nbsp;&nbsp;4627🍴</code></b> [Source Code](https://github.com/tootsuite/mastodon)) `AGPL-3.0` `Ruby`
- 🌎 [Misago](misago-project.org/) - Misago is fully featured modern forum application that is fast, scalable and responsive. ( <b><code>&nbsp;&nbsp;2210⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;473🍴</code></b> [Source Code](https://github.com/rafalp/Misago)) `GPL-2.0` `Python`
- 🌎 [Misskey](misskey.io/) - Decentralized app-like microblogging server/SNS for the Fediverse, using the ActivityPub protocol like GNU social and Mastodon. ( <b><code>&nbsp;&nbsp;2812⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;419🍴</code></b> [Source Code](https://github.com/misskey-dev/misskey)) `AGPL-3.0` `Nodejs`
- 🌎 [Movim](movim.eu/) - Modern, federated social network based on XMPP, with a fully featured group-chat, subscriptions and microblogging. ( <b><code>&nbsp;&nbsp;1390⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [Source Code](https://github.com/movim/movim)) `AGPL-3.0` `PHP`
- 🌎 [MyBB](mybb.com/) - Free, extensible forum software package. ( <b><code>&nbsp;&nbsp;&nbsp;855⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;380🍴</code></b> [Source Code](https://github.com/mybb/mybb)) `LGPL-3.0` `PHP`
- 🌎 [Nitter](nitter.net) `⚠` - A alternative front end to twitter. ( <b><code>&nbsp;&nbsp;5139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;231🍴</code></b> [Source Code](https://github.com/zedeus/nitter)) `AGPL-3.0` `Nimble`
- 🌎 [NodeBB](nodebb.org/) - Forum software built for the modern web. ( <b><code>&nbsp;12757⭐</code></b> <b><code>&nbsp;&nbsp;2565🍴</code></b> [Source Code](https://github.com/NodeBB/NodeBB)) `GPL-3.0` `Nodejs`
- 🌎 [Orange Forum](www.goodoldweb.com/) - Orange Forum is an easy to deploy forum that has minimal dependencies and uses very little javascript. ( <b><code>&nbsp;&nbsp;&nbsp;416⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Source Code](https://github.com/s-gv/orangeforum)) `BSD-3-Clause` `Go`
- 🌎 [OSSN](www.opensource-socialnetwork.org/) - Open Source Social Network (OSSN) is a social networking software written in PHP. It allows you to make a social networking website and helps your members build social relationships, with people who share similar professional or personal interests. ( <b><code>&nbsp;&nbsp;&nbsp;877⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;470🍴</code></b> [Source Code](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `GPL-2.0` `PHP`
- 🌎 [phpBB](www.phpbb.com/) - Flat-forum bulletin board software solution that can be used to stay in touch with a group of people or can power your entire website. ( <b><code>&nbsp;&nbsp;1543⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;891🍴</code></b> [Source Code](https://github.com/phpbb/phpbb)) `GPL-2.0` `PHP`
- 🌎 [PixelFed](pixelfed.social) - Pixelfed is an open-source, federated platform alternate to Instagram. ( <b><code>&nbsp;&nbsp;3705⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;452🍴</code></b> [Source Code](https://github.com/pixelfed/pixelfed)) `AGPL-3.0` `PHP`
- 🌎 [Pleroma](pleroma.social) - Federated microblogging server, Mastodon, GNU social, & ActivityPub compatible.  🌎 [Source Code](git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- [Pump.io](http://pump.io/) - Stream server that does most of what people really want from a social network. ( <b><code>&nbsp;&nbsp;2122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;349🍴</code></b> [Source Code](https://github.com/pump-io/pump.io)) `Apache-2.0` `Nodejs`
- 🌎 [remark42](remark42.com/) - A lightweight and simple comment engine, which doesn't spy on users. It can be embedded into blogs, articles or any other place where readers add comments.  🌎 [Demo](remark42.com/demo/),  <b><code>&nbsp;&nbsp;3855⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;317🍴</code></b> [Source Code](https://github.com/umputun/remark42)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;1766⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [schnack](https://github.com/schn4ck/schnack) - Schnack is simple self-hosted node app for Disqus-like drop-in commenting on static websites. `LIL-1.0` `Nodejs`
- 🌎 [Scoold](scoold.com) - Stack Overflow in a JAR. An enterprise-ready Q&A platform with full-text search, SAML, LDAP integration and social login support.  🌎 [Demo](live.scoold.com),  <b><code>&nbsp;&nbsp;&nbsp;646⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [Source Code](https://github.com/Erudika/scoold)) `Apache-2.0` `Java`
- 🌎 [Simple Machines Forum](www.simplemachines.org/) - Free, professional grade software package that allows you to set up your own online community within minutes. ( <b><code>&nbsp;&nbsp;&nbsp;470⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Source Code](https://github.com/SimpleMachines/SMF2.1)) `BSD-3-Clause` `PHP`
- 🌎 [Socialhome](socialhome.network) - Federated and decentralized profile builder and social network engine.  🌎 [Demo](socialhome.network/),  <b><code>&nbsp;&nbsp;&nbsp;322⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [Source Code](https://github.com/jaywink/socialhome)) `AGPL-3.0` `Python`
- 🌎 [Talkyard](www.talkyard.io/) - Create a community, where your users can suggest ideas and get questions answered. And have friendly open-ended discussions and chat (Slack/StackOverflow/Discourse/Reddit/Disqus hybrid).  🌎 [Demo](www.talkyard.io/forum/latest),  <b><code>&nbsp;&nbsp;1465⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [Source Code](https://github.com/debiki/talkyard)) `AGPL-3.0` `Scala`
- 🌎 [Teddit](teddit.net) `⚠` - Alternative Reddit front-end focused on privacy.  🌎 [Source Code](codeberg.org/teddit/teddit)) `AGPL-3.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;1481⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [Thredded](https://github.com/thredded/thredded) - Forums, feature-rich and simple. `MIT` `Ruby`
- 🌎 [Tokumei](tokumei.co/) - Anonymous microblogging platform.  🌎 [Source Code](gitlab.com/tokumei/tokumei)) `ISC` `rc`
- [twister](http://twister.net.co/) - Fully decentralized P2P microblogging platform leveraging the free software implementations of Bitcoin and BitTorrent protocols. ( <b><code>&nbsp;&nbsp;1403⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Source Code](https://github.com/miguelfreitas/twister-core)) `MIT` `C++`
- 🌎 [Vanilla Forums](vanillaforums.org/) - Simple and flexible forum software. ( <b><code>&nbsp;&nbsp;2545⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;763🍴</code></b> [Source Code](https://github.com/vanilla/vanilla)) `GPL-2.0` `PHP`
- 🌎 [yarn.social](yarn.social) - Self-Hosted, Twitter™-like Decentralised micro-logging platform. No ads, no tracking, your content, your data.  🌎 [Source Code](git.mills.io/yarnsocial/yarn)) `MIT` `Go`
- 🌎 [Zusam](zusam.org) - Free and open-source way to self-host private forums for groups of friends or family.  🌎 [Demo](demo.zusam.org),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Source Code](https://github.com/zusam/zusam)) `AGPL-3.0` `PHP`


### Communication - Video Conferencing

**[`^        back to top        ^`](#)**
 🌎 [Video / Web Conferencing](en.wikipedia.org/wiki/Web_conferencing) tools and software

_Related: [Conference Management](#conference-management)_

- 🌎 [BigBlueButton](bigbluebutton.org/) - Supports real-time sharing of audio, video, slides (with whiteboard controls), chat, and the screen. Instructors can engage remote students with polling, emojis, and breakout rooms.  🌎 [Demo](demo.bigbluebutton.org/gl),  <b><code>&nbsp;&nbsp;7580⭐</code></b> <b><code>&nbsp;&nbsp;5791🍴</code></b> [Source Code](https://github.com/bigbluebutton/bigbluebutton)) `LGPL-3.0` `Java`
- 🌎 [Jitsi Meet](jitsi.org/Projects/JitsiMeet) - Jitsi Meet is an OpenSource (MIT) WebRTC Javascript application that uses Jitsi Videobridge to provide high quality, scalable video conferences. ( <b><code>&nbsp;18360⭐</code></b> <b><code>&nbsp;&nbsp;5850🍴</code></b> [Source Code](https://github.com/jitsi/jitsi-meet)) `MIT` `Javascript`
- 🌎 [Jitsi Video Bridge](jitsi.org/Projects/JitsiVideobridge) - WebRTC compatible Selective Forwarding Unit (SFU) that allows for multiuser video communication. ( <b><code>&nbsp;&nbsp;2618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;940🍴</code></b> [Source Code](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java`
- 🌎 [Galene](galene.org/) - Galène (or Galene) is a videoconference server (an “SFU”) that is easy to deploy and that requires moderate server resources. ( <b><code>&nbsp;&nbsp;&nbsp;650⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [Source Code](https://github.com/jech/galene)) `MIT` `Go`
- 🌎 [LiveKit](livekit.io/) - Modern, scalable WebRTC conferencing platform with client SDKs.  🌎 [Demo](livekit.io/playground),  <b><code>&nbsp;&nbsp;3637⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;247🍴</code></b> [Source Code](https://github.com/livekit/livekit-server)) `Apache-2.0` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Wirow](https://github.com/wirow-io/wirow-server) - A full featured self-hosted video web-conferencing platform. `AGPL-3.0` `C`


### Communication - XMPP

**[`^        back to top        ^`](#)**
 🌎 [Extensible Messaging and Presence Protocol](en.wikipedia.org/wiki/XMPP) software


### Communication - XMPP - Servers

**[`^        back to top        ^`](#)**

- 🌎 [ejabberd](www.ejabberd.im/) - XMPP instant messaging server. ( <b><code>&nbsp;&nbsp;5253⭐</code></b> <b><code>&nbsp;&nbsp;1481🍴</code></b> [Source Code](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang`
-  <b><code>&nbsp;&nbsp;1294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [jackal](https://github.com/ortuman/jackal) - XMPP server with focus on stability, simple configuration and low resource consumption. `Apache-2.0` `Go`
- 🌎 [Kontalk](www.kontalk.org) - Kontalk is an Open Source Messenger, similar to WhatsApp (app for android only currently), including end-to-end encryption, server is based on Tigase XMPP Server. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/kontalk)) `GPL-3.0` `Java`
- 🌎 [Metronome IM](metronome.im/) - Fork of Prosody IM. ( <b><code>&nbsp;&nbsp;&nbsp;152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Source Code](https://github.com/maranda/metronome)) `MIT` `Lua`
- 🌎 [MongooseIM](www.erlang-solutions.com/products/mongooseim.html) - Mobile messaging platform with a focus on performance and scalability. ( <b><code>&nbsp;&nbsp;1498⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;418🍴</code></b> [Source Code](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang`
- 🌎 [Openfire](www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server. ( <b><code>&nbsp;&nbsp;2515⭐</code></b> <b><code>&nbsp;&nbsp;1307🍴</code></b> [Source Code](https://github.com/igniterealtime/Openfire)) `Apache-2.0` `Java`
- 🌎 [Prosody IM](prosody.im/) - Feature-rich and easy to configure XMPP server.  🌎 [Source Code](hg.prosody.im/)) `MIT` `Lua`
- 🌎 [Snikket](snikket.org/) - All-in-one Dockerized easy XMPP solution, including web admin and clients. ( <b><code>&nbsp;&nbsp;&nbsp;152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Source Code](https://github.com/snikket-im/snikket-server), 🌎 [Clients](snikket.org/app/)) `Apache-2.0` `Lua/Python`
- 🌎 [Tigase](tigase.net/xmpp-server) - XMPP server implementation in Java. `GPL-3.0` `Java`


### Communication - XMPP - Web Clients

**[`^        back to top        ^`](#)**

- 🌎 [Candy](candy-chat.github.io/candy/) - Multi user XMPP client written in Javascript. ( <b><code>&nbsp;&nbsp;1326⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;385🍴</code></b> [Source Code](https://github.com/candy-chat/candy)) `MIT` `Javascript`
- 🌎 [Converse.js](conversejs.org/) - Free and open-source XMPP chat client in your browser. ( <b><code>&nbsp;&nbsp;2825⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;744🍴</code></b> [Source Code](https://github.com/conversejs/converse.js)) `MPL-2.0` `Javascript`
- 🌎 [JSXC](jsxc.org) - Real-time XMPP web chat application with video calls, file transfer and encrypted communication. There are also versions for Nextcloud/Owncloud and SOGo. ( <b><code>&nbsp;&nbsp;&nbsp;669⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;250🍴</code></b> [Source Code](https://github.com/jsxc/jsxc)) `MIT` `Javascript`
- 🌎 [Libervia](wiki.goffi.org/wiki/Libervia/en) - Web frontend from Salut à Toi.  🌎 [Source Code](repos.goffi.org/libervia-web)) `AGPL-3.0` `Python`
- 🌎 [Salut à Toi](www.salut-a-toi.org/) - Multipurpose, multi frontend, libre and decentralized communication tool.  🌎 [Source Code](repos.goffi.org/libervia-backend)) `AGPL-3.0` `Python`


### Community-Supported Agriculture (CSA)

**[`^        back to top        ^`](#)**

Management and administration tools for community supported agriculture and food cooperatives

_Related: [E-commerce](#e-commerce)_

- 🌎 [ACP Admin](acp-admin.ch/) - CSA administration. Manage members, subscriptions, deliveries, drop-off locations, member participation, invoices and emails. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/acp-admin/acp-admin/)) `MIT` `Ruby`
- 🌎 [Cagette](cagette.net/) - Open source web app to help people build a better and sustainable food system. Some people call it a 'foodhub' - a mix between a groupware and a marketplace, helping consumers to order food from local farmers and producers. ( <b><code>&nbsp;&nbsp;&nbsp;121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Source Code](https://github.com/CagetteNet/cagette)) `GPL-2.0` `Haxe`
- 🌎 [FoodCoopShop](www.foodcoopshop.com/) - User-friendly open source software for food-coops. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Source Code](https://github.com/foodcoopshop/foodcoopshop)) `MIT` `PHP`
- 🌎 [Foodsoft](foodcoops.net/) - Web-based software to manage a non-profit food coop (product catalog, ordering, accounting, job scheduling). ( <b><code>&nbsp;&nbsp;&nbsp;264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;134🍴</code></b> [Source Code](https://github.com/foodcoops/foodsoft)) `AGPL-3.0` `Ruby`
- 🌎 [juntagrico](juntagrico.org/) - Management platform for community gardens and vegetable cooperatives. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Source Code](https://github.com/juntagrico/juntagrico)) `LGPL-3.0` `Python`
- 🌎 [Local Food Nodes](localfoodnodes.org/) - Your open source platform for peoples driven local food markets and CSA.  🌎 [Source Code](gitlab.com/localfoodnodes/localfoodnodes)) `MIT` `PHP`
- 🌎 [Open Food Network](www.openfoodnetwork.org/) - Online marketplace for local food. It enables a network of independent online food stores that connect farmers and food hubs with individuals and local businesses. ( <b><code>&nbsp;&nbsp;&nbsp;855⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;582🍴</code></b> [Source Code](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPL-3.0` `Ruby`
- 🌎 [OpenOlitor](openolitor.org/) - Administration platform for Community Supported Agriculture groups. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/OpenOlitor)) `AGPL-3.0` `Scala`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [teikei](https://github.com/teikei/teikei) - A web application that maps out community-supported agriculture based on crowdsourced data.  🌎 [Demo](ernte-teilen.org/karte/#/)) `AGPL-3.0` `Nodejs`


### Conference Management

**[`^        back to top        ^`](#)**

- [Conference Organizing Distribution (COD)](http://usecod.com/) - Create conference and event websites built on top of Drupal.  🌎 [Source Code](git.drupalcode.org/project/cod)) `GPL-1.0` `PHP`
- 🌎 [frab](frab.github.io/frab/) - Web-based conference planning and management system. It helps to collect submissions, to manage talks and speakers and to create a schedule. ( <b><code>&nbsp;&nbsp;&nbsp;656⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [Source Code](https://github.com/frab/frab)) `MIT` `Ruby`
- 🌎 [indico](getindico.io/) - A feature-rich event management system, made @ CERN, the place where the Web was born.  🌎 [Demo](sandbox.getindico.io/),  <b><code>&nbsp;&nbsp;1360⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;338🍴</code></b> [Source Code](https://github.com/indico/indico)) `MIT` `Python`
- 🌎 [Open Conference Systems (OCS)](pkp.sfu.ca/ocs/) - Free Web publishing tool that will create a complete Web presence for your scholarly conference. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [Source Code](https://github.com/pkp/ocs)) `GPL-1.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;541⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;190🍴</code></b> [OpenCFP](https://github.com/opencfp/opencfp) - Conference talk submission system. `MIT` `PHP`
- 🌎 [osem](osem.io/) - Event management tailored to free Software conferences.  🌎 [Demo](demo.osem.io/),  <b><code>&nbsp;&nbsp;&nbsp;728⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;480🍴</code></b> [Source Code](https://github.com/openSUSE/osem)) `MIT` `Ruby`
- 🌎 [pretalx](pretalx.org) - Web-based event management, including running a Call for Papers, reviewing submissions, and scheduling talks. Exports and imports for various related tools. ( <b><code>&nbsp;&nbsp;&nbsp;449⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;131🍴</code></b> [Source Code](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`


### Content Management Systems (CMS)

**[`^        back to top        ^`](#)**

CMS are a practical way to setup a website with many features. CMS often come with third party plugins, themes and functionality that is easy to add and customize to your needs.

_Related: [Blogging Platforms](#blogging-platforms), [Static Site Generators](#static-site-generators)_

- 🌎 [Alfresco Community Edition](www.alfresco.com/products/community/download) - The open source Enterprise Content Management software that handles any type of content, allowing users to easily share and collaborate on content.  🌎 [Source Code](hub.alfresco.com/t5/alfresco-content-services-hub/project-overview-repository/ba-p/290502)) `LGPL-3.0` `Java`
- 🌎 [Apostrophe](apostrophecms.com/) - CMS with a focus on extensible in-context editing tools.  🌎 [Demo](apostrophecms.com/demo),  <b><code>&nbsp;&nbsp;3866⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;511🍴</code></b> [Source Code](https://github.com/apostrophecms/apostrophe)) `MIT` `Nodejs`
- 🌎 [b2evolution CMS](b2evolution.net/) - The most integrated CMS ever: b2evolution includes everything you need to build websites for publishing, sharing and interacting with your community. ( <b><code>&nbsp;&nbsp;&nbsp;159⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Source Code](https://github.com/b2evolution/b2evolution)) `GPL-2.0` `PHP`
- 🌎 [Backdrop CMS](backdropcms.org/) - Comprehensive CMS for small to medium sized businesses and non-profits. ( <b><code>&nbsp;&nbsp;&nbsp;857⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;357🍴</code></b> [Source Code](https://github.com/backdrop/backdrop)) `GPL-2.0` `PHP`
- 🌎 [BigTree CMS](www.bigtreecms.org/) - Straightforward, well documented, and capable written with PHP and MySQL. ( <b><code>&nbsp;&nbsp;&nbsp;198⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Source Code](https://github.com/bigtreecms/BigTree-CMS)) `LGPL-2.1` `PHP`
- 🌎 [Bludit](www.bludit.com/) `⚠` - Simple application to build a site or blog in seconds. Bludit uses flat-files (text files in JSON format) to store posts and pages.  🌎 [Demo](demo.bludit.com/),  <b><code>&nbsp;&nbsp;1014⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;256🍴</code></b> [Source Code](https://github.com/bludit/bludit)) `MIT` `PHP`
- 🌎 [Bolt CMS](boltcms.io/) - Open source Content Management Tool, which strives to be as simple and straightforward as possible. ( <b><code>&nbsp;&nbsp;&nbsp;390⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [Source Code](https://github.com/bolt/core)) `MIT` `PHP`
- 🌎 [CMS Made Simple](www.cmsmadesimple.org/) - Open source content management system, faster and easier management of website contents, scalable for small businesses to large corporations. ([Source Code](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-1.0` `PHP`
- 🌎 [Cockpit](getcockpit.com) - Simple Content Platform to manage any structured content. ( <b><code>&nbsp;&nbsp;5343⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;551🍴</code></b> [Source Code](https://github.com/agentejo/cockpit)) `MIT` `PHP`
- 🌎 [Concrete 5 CMS](www.concretecms.com) - Open source content management system. ( <b><code>&nbsp;&nbsp;&nbsp;701⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;420🍴</code></b> [Source Code](https://github.com/concrete5/concrete5)) `MIT` `PHP`
- 🌎 [Contao](contao.org/) - Contao is a powerful open source CMS that allows you to create professional websites and scalable web applications. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/contao/contao/)) `LGPL-3.0` `PHP`
- 🌎 [CouchCMS](www.couchcms.com/) - Simple Open-Source CMS for designers. ( <b><code>&nbsp;&nbsp;&nbsp;308⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [Source Code](https://github.com/CouchCMS/CouchCMS)) `CPAL-1.0` `PHP`
- 🌎 [Directus](directus.io/) - An Instant App & API for your SQL Database. Directus wraps your new or existing SQL database with a realtime GraphQL+REST API for developers, and an intuitive admin app for non-technical users. ( <b><code>&nbsp;16990⭐</code></b> <b><code>&nbsp;&nbsp;1957🍴</code></b> [Source Code](https://github.com/directus/directus)) `GPL-3.0` `Nodejs`
- 🌎 [Drupal](www.drupal.org/) - Advanced open source content management platform.  🌎 [Source Code](git.drupalcode.org/project/drupal)) `GPL-2.0` `PHP`
- 🌎 [eLabFTW](www.elabftw.net) - Online lab notebook for research labs. Store experiments, use a database to find reagents or protocols, use trusted timestamping to legally timestamp an experiment, export as pdf or zip archive, share with collaborators….  🌎 [Demo](demo.elabftw.net),  <b><code>&nbsp;&nbsp;&nbsp;639⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [Source Code](https://github.com/elabftw/elabftw)) `AGPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Expressa](https://github.com/thomas4019/expressa) - Content Management System for powering database driven websites using JSON schemas. Provides permission management and automatic REST APIs. `MIT` `Nodejs`
- 🌎 [Flextype](flextype.org/) - Flextype is an open-source Hybrid Content Management System with the freedom of a headless CMS and with the full functionality of a traditional CMS. ( <b><code>&nbsp;&nbsp;&nbsp;510⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [Source Code](https://github.com/flextype/flextype)) `MIT` `PHP`
- [GetSimple CMS](http://get-simple.info/) - The Simplest Content Management System. Ever. ( <b><code>&nbsp;&nbsp;&nbsp;364⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [Source Code](https://github.com/GetSimpleCMS/GetSimpleCMS)) `GPL-3.0` `PHP`
- 🌎 [Joomla!](www.joomla.org/) - Advanced Content Management System (CMS). ( <b><code>&nbsp;&nbsp;4215⭐</code></b> <b><code>&nbsp;&nbsp;3495🍴</code></b> [Source Code](https://github.com/joomla/joomla-cms)) `GPL-2.0` `PHP`
- 🌎 [KeystoneJS](keystonejs.com/) - CMS and Web Application Platform. ( <b><code>&nbsp;&nbsp;6639⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;828🍴</code></b> [Source Code](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
- 🌎 [MODX](modx.com/) - MODX is an advanced content management and publishing platform. The current version is called 'Revolution'. ( <b><code>&nbsp;&nbsp;1303⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;539🍴</code></b> [Source Code](https://github.com/modxcms/revolution)) `GPL-2.0` `PHP`
- 🌎 [Neos](www.neos.io) - Neos or TYPO3 Neos (for version 1) is a modern, open source CMS. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/neos)) `GPL-3.0` `PHP`
- 🌎 [Noosfero](gitlab.com/noosfero/noosfero) - Noosfero is a web platform for social and solidarity economy networks with blog, e-Portfolios, CMS, RSS, thematic discussion, events agenda and collective intelligence for solidarity economy in the same system. `AGPL-3.0` `Ruby`
- 🌎 [Omeka](omeka.org) - Create complex narratives and share rich collections, adhering to Dublin Core standards with Omeka on your server, designed for scholars, museums, libraries, archives, and enthusiasts.  🌎 [Demo](omeka.org/classic/showcase/),  <b><code>&nbsp;&nbsp;&nbsp;396⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;181🍴</code></b> [Source Code](https://github.com/omeka/Omeka)) `GPL-3.0` `PHP`
- 🌎 [Pagekit](pagekit.com/) - New modern CMS to create and share. ( <b><code>&nbsp;&nbsp;5483⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;671🍴</code></b> [Source Code](https://github.com/pagekit/pagekit)) `MIT` `PHP`
- 🌎 [Pico](picocms.org/) - Stupidly simple, blazing fast, flat file CMS. ( <b><code>&nbsp;&nbsp;3581⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;618🍴</code></b> [Source Code](https://github.com/picocms/Pico)) `MIT` `PHP`
- 🌎 [Pimcore](www.pimcore.org/) - Multi-Channel Experience and Engagement Management Platform. ( <b><code>&nbsp;&nbsp;2589⭐</code></b> <b><code>&nbsp;&nbsp;1188🍴</code></b> [Source Code](https://github.com/pimcore/pimcore)) `GPL-3.0-or-later` `PHP`
- 🌎 [Plone](plone.org/) - Powerful open-source CMS system. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/plone)) `ZPL-2.0` `Python`
- 🌎 [ProcessWire](processwire.com/) - ProcessWire is an open source content management system (CMS) and web application framework aimed at the needs of designers, developers and their clients. ( <b><code>&nbsp;&nbsp;&nbsp;733⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;212🍴</code></b> [Source Code](https://github.com/ryancramerdesign/ProcessWire)) `MPL-2.0` `PHP`
- 🌎 [PropertyWebBuilder](propertywebbuilder.com) - Ultimate Ruby on Rails engine for creating real estate websites.  🌎 [Demo](propertywebbuilder.herokuapp.com),  <b><code>&nbsp;&nbsp;&nbsp;449⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [Source Code](https://github.com/etewiah/property_web_builder)) `MIT` `Ruby`
- 🌎 [Publify](publify.github.io/) - Simple but full featured web publishing software. ( <b><code>&nbsp;&nbsp;1783⭐</code></b> <b><code>&nbsp;&nbsp;3792🍴</code></b> [Source Code](https://github.com/publify/publify)) `MIT` `Ruby`
- 🌎 [Rapido](framagit.org/InfoLibre/rapido) - Create your website with Rapido. Edit, publish and share collaborative content. `AGPL-3.0` `Go`
- 🌎 [REDAXO](www.redaxo.org) - Simple, flexible and useful content management system (documentation only available in German). ( <b><code>&nbsp;&nbsp;&nbsp;287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [Source Code](https://github.com/redaxo/redaxo)) `MIT` `PHP`
- 🌎 [Redaxscript](redaxscript.com) - Ultra lightweight CMS for MySQL, SQLite and PostgreSQL.  🌎 [Demo](demo.redaxscript.com/login),  <b><code>&nbsp;&nbsp;&nbsp;248⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [Source Code](https://github.com/redaxscript/redaxscript)) `GPL-3.0` `PHP`
- 🌎 [Roadiz](www.roadiz.io/) - Modern CMS based on a node system which can handle many types of services. ( <b><code>&nbsp;&nbsp;&nbsp;367⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Source Code](https://github.com/roadiz/roadiz)) `MIT` `PHP`
- 🌎 [SilverStripe](www.silverstripe.org) - Easy to use CMS with powerful MVC framework underlying.  🌎 [Demo](demo.silverstripe.org/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- 🌎 [SPIP](www.spip.net/fr) - Publication system for the Internet aimed at collaborative work, multilingual environments, and simplicity of use for web authors.  🌎 [Source Code](git.spip.net/)) `GPL-3.0` `PHP`
- 🌎 [Squidex](squidex.io) - Headless CMS, based on MongoDB, CQRS and Event Sourcing.  🌎 [Demo](cloud.squidex.io),  <b><code>&nbsp;&nbsp;1730⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;369🍴</code></b> [Source Code](https://github.com/Squidex/squidex)) `MIT` `.NET`
- 🌎 [Strapi](strapi.io/) - The most advanced open-source Content Management Framework (headless-CMS) to build powerful API with no effort. ( <b><code>&nbsp;46447⭐</code></b> <b><code>&nbsp;&nbsp;5689🍴</code></b> [Source Code](https://github.com/strapi/strapi)) `MIT` `Nodejs`
- 🌎 [Textpattern](textpattern.com/) - Flexible, elegant and easy-to-use CMS.  🌎 [Demo](textpattern.co/demo),  <b><code>&nbsp;&nbsp;&nbsp;678⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [Source Code](https://github.com/textpattern/textpattern)) `GPL-2.0` `PHP`
- 🌎 [Typemill](typemill.net/) - Author-friendly flat-file-cms with a visual markdown editor based on vue.js. ( <b><code>&nbsp;&nbsp;&nbsp;283⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Source Code](https://github.com/typemill/typemill)) `MIT` `PHP`
- 🌎 [TYPO3](typo3.org/) - Powerful and advanced CMS with a large community. ( <b><code>&nbsp;&nbsp;&nbsp;864⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;572🍴</code></b> [Source Code](https://github.com/TYPO3/TYPO3.CMS)) `GPL-2.0` `PHP`
- 🌎 [Umbraco](umbraco.com/) - The friendly CMS. Free and open source with an amazing community. ( <b><code>&nbsp;&nbsp;3650⭐</code></b> <b><code>&nbsp;&nbsp;2378🍴</code></b> [Source Code](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
- 🌎 [Wagtail](wagtail.io/) - Django content management system focused on flexibility and user experience. ( <b><code>&nbsp;12365⭐</code></b> <b><code>&nbsp;&nbsp;2674🍴</code></b> [Source Code](https://github.com/wagtail/wagtail)) `BSD-3-Clause` `Python`
- 🌎 [WinterCMS](wintercms.com/) - Speedy and secure content management system built on the Laravel PHP framework. ( <b><code>&nbsp;&nbsp;&nbsp;995⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [Source Code](https://github.com/wintercms/winter)) `MIT` `PHP`
- 🌎 [WonderCMS](www.wondercms.com) - WonderCMS is the smallest flat file CMS since 2008.  🌎 [Demo](www.wondercms.com/demo),  <b><code>&nbsp;&nbsp;&nbsp;463⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [Source Code](https://github.com/robiso/wondercms)) `MIT` `PHP`
- 🌎 [WordPress](wordpress.org/) - World's most-used blogging and CMS engine. ( <b><code>&nbsp;16440⭐</code></b> <b><code>&nbsp;11431🍴</code></b> [Source Code](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`
- 🌎 [WriteFreely](writefreely.org) - Writing software for starting a minimalist, federated blog — or an entire community. ( <b><code>&nbsp;&nbsp;2762⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;195🍴</code></b> [Source Code](https://github.com/writefreely/writefreely)) `AGPL-3.0` `Go`


### DNS

**[`^        back to top        ^`](#)**

_See also:  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [awesome-sysadmin/DNS](https://github.com/awesome-foss/awesome-sysadmin#dns)_

-  <b><code>&nbsp;&nbsp;1698⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [blocky](https://github.com/0xERR0R/blocky) - Fast and lightweight DNS proxy (like Pi-hole) as ad-blocker for local network with many features. `Apache-2.0` `Go`
- 🌎 [CoreDNS](coredns.io/) - Plugin driven DNS Server with support for proxying to Google's DNS-over-HTTPS. ( <b><code>&nbsp;&nbsp;9500⭐</code></b> <b><code>&nbsp;&nbsp;1703🍴</code></b> [Source Code](https://github.com/coredns/coredns)) `Apache-2.0` `Go`
- 🌎 [Maza ad blocking](maza-ad-blocking.andros.dev/) - Local ad blocker. Like Pi-hole but local and using your operating system. ( <b><code>&nbsp;&nbsp;1595⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Source Code](https://github.com/tanrax/maza-ad-blocking)) `Apache-2.0` `Bash`
- 🌎 [nsupdate.info](www.nsupdate.info/) - Dynamic DNS service.  🌎 [Demo](www.nsupdate.info/account/register/),  <b><code>&nbsp;&nbsp;&nbsp;852⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [Source Code](https://github.com/nsupdate-info/nsupdate.info)) `BSD-3-Clause` `Python`
- 🌎 [SPF Toolbox](spftoolbox.com) - Application to look up DNS records such as SPF, MX, Whois, and more. ( <b><code>&nbsp;&nbsp;&nbsp;201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Source Code](https://github.com/charlesabarnes/SPFtoolbox)) `MIT` `PHP`


### Document Management

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;&nbsp;459⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [DOCAT](https://github.com/docat-org/docat) - Host your docs. Simple. Versioned. Fancy. `MIT` `Python/Docker`
- 🌎 [Docspell](docspell.org) - Auto-tagging document organizer and archive. ( <b><code>&nbsp;&nbsp;&nbsp;672⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Source Code](https://github.com/eikek/docspell)) `GPL-3.0` `Scala/Java`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [EveryDocs](https://github.com/jonashellmann/everydocs-core) - A simple Document Management System for private use with basic functionality to organize your documents digitally. `GPL-3.0` `Ruby`
- 🌎 [I, Librarian](i-librarian.net) - I, Librarian can organize PDF papers and office documents. It provides a lot of extra features for students and research groups both in industry and academia.  🌎 [Demo](i-librarian.net/demo/),  <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Source Code](https://github.com/mkucej/i-librarian-free)) `GPL-3.0` `PHP`
- 🌎 [Mayan EDMS](www.mayan-edms.com) - Free Open Source Electronic Document Management System. An electronic vault for your documents with preview generation, OCR, and automatic categorization among other features.  🌎 [Source Code](gitlab.com/mayan-edms/mayan-edms)) `Apache-2.0` `Python`
-  <b><code>&nbsp;&nbsp;3589⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) - A fork of paperless, adding a new interface and many other changes under the hood. Scan, index, and archive all of your paper documents.  🌎 [Demo](demo.paperless-ngx.com/)) `GPL-3.0` `Python`
- 🌎 [Papermerge](www.papermerge.com) - Open Source Document Management System focused on scanned documents (electronic archives). Features file browsing in similar way to dropbox/google drive. OCR, full text search, text overlay/selection. ( <b><code>&nbsp;&nbsp;1593⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [Source Code](https://github.com/ciur/papermerge)) `Apache-2.0` `Python`
- 🌎 [paper{s}pace](dedicatedcode.com/projects.html) - Small web application to manage all your offline documents. Provides a searchable storage for your documents and reminds you of upcoming tasks.  🌎 [Source Code](gitlab.com/dedicatedcode/paperspace)) `MIT` `Java`
- 🌎 [Teedy](teedy.io/) - Lightweight document management system packed with all the features you can expect from big expensive solutions (Ex SismicsDocs). ( <b><code>&nbsp;&nbsp;1273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;211🍴</code></b> [Source Code](https://github.com/sismics/docs)) `GPL-2.0` `Java`


### Document Management - E-books

**[`^        back to top        ^`](#)**

- 🌎 [BicBucStriim](projekte.textmulch.de/bicbucstriim/) - Provides web-based access to your Calibre Library's e-book collection. ( <b><code>&nbsp;&nbsp;&nbsp;379⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Source Code](https://github.com/rvolz/BicBucStriim)) `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;7072⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;931🍴</code></b> [Calibre Web](https://github.com/janeczku/calibre-web) - Web app providing a clean interface for browsing, reading and downloading eBooks using an existing Calibre database. `GPL-3.0` `Python`
- 🌎 [Calibre](calibre-ebook.com/) - E-book library manager that can view, convert, and catalog e-books in most of the major e-book formats and provides a built-in Web server for remote clients.  🌎 [Demo](calibre-ebook.com/demo), 🌎 [Source Code](launchpad.net/calibre)) `GPL-3.0` `Python`
- 🌎 [COPS](blog.slucas.fr/en/oss/calibre-opds-php-server) - Lightweight e-book server alternative to Calibre content server or Calibre2OPDS. ([Demo](http://cops-demo.slucas.fr/index.php),  <b><code>&nbsp;&nbsp;1254⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;219🍴</code></b> [Source Code](https://github.com/seblucas/cops)) `GPL-2.0` `PHP`
- 🌎 [Kavita](www.kavitareader.com/) - Cross-platform e-book/manga/comic/pdf server and web reader with user management, ratings and reviews, and metatdata support.  🌎 [Demo](wiki.kavitareader.com/en/kavita-demo),  <b><code>&nbsp;&nbsp;1361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [Source Code](https://github.com/Kareadita/Kavita)) `GPL-3.0` `.NET Core/Docker`
- 🌎 [Komga](komga.org) - Media server for comics/mangas/BDs with API and OPDS support, a modern web interface for exploring your libraries, as well as a web reader. ( <b><code>&nbsp;&nbsp;1526⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [Source Code](https://github.com/gotson/komga)) `MIT` `Java/Docker`
-  <b><code>&nbsp;&nbsp;1127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [Mango](https://github.com/hkalexling/Mango) - Manga server and web reader with a built-in MangaDex downloader. `MIT` `Crystal`
-  <b><code>&nbsp;&nbsp;&nbsp;424⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [pyShelf](https://github.com/th3r00t/pyShelf) - Lightweight Ebook Server. `GPL-3.0` `Python`
- 🌎 [Stump](www.stumpapp.dev) - A fast, free and open source comics, manga and digital book server with OPDS support. ( <b><code>&nbsp;&nbsp;&nbsp;177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Source Code](https://github.com/aaronleopold/stump)) `MIT` `Rust`
-  <b><code>&nbsp;&nbsp;&nbsp;263⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Tanoshi](https://github.com/faldez/tanoshi) - Selfhosted web manga reader with extensions. `MIT` `Rust`
- 🌎 [The Epube](tt-rss.org/the-epube) - Self-hosted web EPUB reader using EPUB.js, Bootstrap, and Calibre.  🌎 [Source Code](git.tt-rss.org/fox/the-epube)) `GPL-3.0` `PHP`


### Document Management - Institutional Repository and Digital Library Software

**[`^        back to top        ^`](#)**

- 🌎 [DSpace](duraspace.org/dspace/) - Turnkey repository application providing durable access to digital resources. ( <b><code>&nbsp;&nbsp;&nbsp;652⭐</code></b> <b><code>&nbsp;&nbsp;1138🍴</code></b> [Source Code](https://github.com/DSpace/DSpace)) `BSD-3-Clause` `Java`
- 🌎 [EPrints](www.eprints.org/) - Digital document management system with a flexible metadata and workflow model primarily aimed at academic institutions. ([Demo](http://tryme.demo.eprints-hosting.org/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [Source Code](https://github.com/eprints/eprints)) `GPL-3.0` `Perl`
- 🌎 [Fedora Commons Repository](fedorarepository.org/) - Robust and modular repository system for the management and dissemination of digital content especially suited for digital libraries and archives, both for access and preservation. ( <b><code>&nbsp;&nbsp;&nbsp;161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [Source Code](https://github.com/fcrepo/fcrepo)) `Apache-2.0` `Java`
- 🌎 [InvenioRDM](inveniordm.docs.cern.ch/) - Highly scalable turn-key research data management platform with a beautiful user experience.  🌎 [Demo](inveniordm.web.cern.ch/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/inveniosoftware/), 🌎 [Clients](inveniosoftware.org/products/rdm/)) `MIT` `Python`
- 🌎 [Islandora](islandora.ca/) - Drupal module for browsing and managing Fedora-based digital repositories. ( <b><code>&nbsp;&nbsp;&nbsp;137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [Source Code](https://github.com/Islandora/islandora)) `GPL-3.0` `PHP`
- 🌎 [Samvera Hyrax](samvera.org/) - Front-end for the Samvera framework, which itself is a Ruby on Rails application for browsing and managing Fedora-based digital repositories. ( <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [Source Code](https://github.com/samvera/hyrax)) `Apache-2.0` `Ruby`


### Document Management - Integrated Library Systems (ILS)

**[`^        back to top        ^`](#)**

_Related: [Content Management Systems (CMS)](#content-management-systems-cms), [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)_

- 🌎 [Evergreen](evergreen-ils.org) - Highly-scalable software for libraries that helps library patrons find library materials, and helps libraries manage, catalog, and circulate those materials. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Source Code](https://github.com/evergreen-library-system/Evergreen)) `GPL-2.0` `PL/pgSQL`
- 🌎 [Koha](koha-community.org/) - Enterprise-class ILS with modules for acquisitions, circulation, cataloging, label printing, offline circulation for when Internet access is not available, and much more.  🌎 [Demo](koha-community.org/demo/),  <b><code>&nbsp;&nbsp;&nbsp;397⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;247🍴</code></b> [Source Code](https://github.com/Koha-Community/Koha)) `GPL-3.0` `Perl`
- 🌎 [RERO ILS](rero21.ch/) - Large-scale ILS that can be run as a service with consortial features, intended primarily for library networks. Includes most standard modules (circulation, acquisitions, cataloging,...) and a web-based public and professional interface.  🌎 [Demo](ils.test.rero.ch/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Source Code](https://github.com/rero/rero-ils)) `AGPL-3.0` `Python/Other`


### E-commerce

**[`^        back to top        ^`](#)**

_Related: [Community-Supported Agriculture (CSA)](#community-supported-agriculture-csa)_

- 🌎 [Aimeos](aimeos.org/) - Ultra fast, Open Source e-commerce framework for building custom online shops, market places and complex B2B applications scaling to billions of items with Laravel.  🌎 [Demo](demo.aimeos.org/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/aimeos)) `LGPL-3.0/MIT` `PHP`
-  <b><code>&nbsp;&nbsp;3428⭐</code></b> <b><code>&nbsp;&nbsp;1004🍴</code></b> [Attendize](https://github.com/attendize/attendize) - Ticket selling and event management platform. `AAL` `PHP`
- 🌎 [Bagisto](bagisto.com/en/) - Leading Laravel open source e-commerce framework with multi-inventory sources, taxation, localization, dropshipping and more exciting features.  🌎 [Demo](demo.bagisto.com/),  <b><code>&nbsp;&nbsp;4582⭐</code></b> <b><code>&nbsp;&nbsp;1513🍴</code></b> [Source Code](https://github.com/bagisto/bagisto)) `MIT` `PHP`
- 🌎 [CoreShop](www.coreshop.org) - CoreShop is a e-commerce plugin for Pimcore. ( <b><code>&nbsp;&nbsp;&nbsp;224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [Source Code](https://github.com/coreshop/CoreShop)) `GPL-3.0` `PHP`
- 🌎 [Drupal Commerce](drupalcommerce.org) - Drupal Commerce is a popular e-commerce module for Drupal CMS, with support for dozens of payment, shipping, and shopping related modules. ( <b><code>&nbsp;&nbsp;&nbsp;351⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;253🍴</code></b> [Source Code](https://github.com/drupalcommerce/commerce)) `GPL-2.0` `PHP`
- 🌎 [Magento](magento.com/) - Leading provider of open omnichannel innovation.  🌎 [Demo](magento.com/schedule-a-demo),  <b><code>&nbsp;10152⭐</code></b> <b><code>&nbsp;&nbsp;8952🍴</code></b> [Source Code](https://github.com/magento/magento2)) `OSL-3.0` `PHP`
- 🌎 [Microweber](microweber.com/) - Drag and Drop CMS and online shop.  🌎 [Demo](demo.microweber.org/),  <b><code>&nbsp;&nbsp;2435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;731🍴</code></b> [Source Code](https://github.com/microweber/microweber)) `Apache-2.0` `PHP`
- 🌎 [Open Source POS](www.opensourcepos.org/) - Open Source Point of Sale is a web based point of sale system. ( <b><code>&nbsp;&nbsp;2578⭐</code></b> <b><code>&nbsp;&nbsp;1832🍴</code></b> [Source Code](https://github.com/opensourcepos/opensourcepos)) `MIT` `PHP`
- 🌎 [OpenCart](www.opencart.com) - Free open source shopping cart solution. ( <b><code>&nbsp;&nbsp;6521⭐</code></b> <b><code>&nbsp;&nbsp;4579🍴</code></b> [Source Code](https://github.com/opencart/opencart)) `GPL-3.0` `PHP`
- 🌎 [OXID eShop](oxidforge.org) - OXID eShop is a flexible open source e-commerce software with a wide range of functionalities. ( <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;197🍴</code></b> [Source Code](https://github.com/OXID-eSales/oxideshop_ce)) `GPL-3.0` `PHP`
- 🌎 [PrestaShop](www.prestashop.com/) - PrestaShop offers a free, open-source and fully scalable e-commerce solution.  🌎 [Demo](demo.prestashop.com/),  <b><code>&nbsp;&nbsp;6543⭐</code></b> <b><code>&nbsp;&nbsp;4405🍴</code></b> [Source Code](https://github.com/PrestaShop/PrestaShop)) `OSL-3.0` `PHP`
- 🌎 [Pretix](pretix.eu/) - Django based ticket sales platform for events. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/pretix)) `Apache-2.0` `Python`
- 🌎 [Reaction Commerce](mailchimp.com/developer/open-commerce/) - Customizable, real-time reactive, Javascript commerce platform. ( <b><code>&nbsp;11774⭐</code></b> <b><code>&nbsp;&nbsp;2136🍴</code></b> [Source Code](https://github.com/reactioncommerce/reaction)) `GPL-3.0` `Nodejs`
- 🌎 [Saleor](saleor.io) - Django based open-sourced e-commerce storefront.  🌎 [Demo](demo.saleor.io/default-channel/en-US),  <b><code>&nbsp;16481⭐</code></b> <b><code>&nbsp;&nbsp;4621🍴</code></b> [Source Code](https://github.com/mirumee/saleor)) `BSD-3-Clause` `Python`
- 🌎 [Shopware Community Edition](shopware.com/community/) - PHP based open source e-commerce software made in Germany.  🌎 [Demo](www.shopware.com/en/test-demo/),  <b><code>&nbsp;&nbsp;1920⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;740🍴</code></b> [Source Code](https://github.com/shopware/platform)) `MIT` `PHP`
- 🌎 [Shuup](www.shuup.com/) - Django powered fully customizable open source e-commerce framework for small and large sites. ( <b><code>&nbsp;&nbsp;1889⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;968🍴</code></b> [Source Code](https://github.com/shuup/shuup)) `AGPL-3.0` `Python`
- 🌎 [Solidus](solidus.io/) - A free, open-source ecommerce platform that gives you complete control over your store. ([Demo](http://demo.solidus.io/),  <b><code>&nbsp;&nbsp;4346⭐</code></b> <b><code>&nbsp;&nbsp;1215🍴</code></b> [Source Code](https://github.com/solidusio/solidus)) `BSD-3-Clause` `Ruby`
- 🌎 [Spree Commerce](spreecommerce.org) - Spree is a complete, modular & API-driven open source e-commerce solution for Ruby on Rails.  🌎 [Demo](new-ux.spreecommerce.org/),  <b><code>&nbsp;11886⭐</code></b> <b><code>&nbsp;&nbsp;4861🍴</code></b> [Source Code](https://github.com/spree/spree)) `BSD-3-Clause` `Ruby`
- 🌎 [Sylius](sylius.com) - Symfony2 powered open source full-stack platform for eCommerce.  🌎 [Demo](sylius.com/try/),  <b><code>&nbsp;&nbsp;6931⭐</code></b> <b><code>&nbsp;&nbsp;1953🍴</code></b> [Source Code](https://github.com/Sylius/Sylius)) `MIT` `PHP`
- 🌎 [Thelia](thelia.net/) - Thelia is an open source and flexible e-commerce solution.  🌎 [Demo](demo.thelia.net/),  <b><code>&nbsp;&nbsp;&nbsp;785⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;285🍴</code></b> [Source Code](https://github.com/thelia/thelia)) `LGPL-3.0` `PHP`
- 🌎 [Vendure](www.vendure.io) - A headless commerce framework.  🌎 [Demo](demo.vendure.io),  <b><code>&nbsp;&nbsp;3614⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;611🍴</code></b> [Source Code](https://github.com/vendure-ecommerce/vendure)) `MIT` `Nodejs`
- 🌎 [WooCommerce](woocommerce.com/) - WordPress based e-commerce solution. ( <b><code>&nbsp;&nbsp;8062⭐</code></b> <b><code>&nbsp;10308🍴</code></b> [Source Code](https://github.com/woocommerce/woocommerce)) `GPL-3.0` `PHP`


### Federated Identity & Authentication

**[`^        back to top        ^`](#)**

**Please visit  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [awesome-sysadmin/Identity Management](https://github.com/awesome-foss/awesome-sysadmin#identity-management)**


### Feed Readers

**[`^        back to top        ^`](#)**

A 🌎 [news aggregator](en.wikipedia.org/wiki/News_aggregator), also termed a feed aggregator, feed reader, news reader, 🌎 [RSS](en.wikipedia.org/wiki/RSS) reader or simply an aggregator, is client software or a web application that aggregates syndicated web content such as online newspapers, blogs/vlogs, podcasts, and other updates in one location for easy viewing. This also section includes RSS/Atom automation tools.

-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Bubo Reader](https://github.com/georgemandis/bubo-rss) - Open source, "irrationally minimal" RSS feed reader.  🌎 [Demo](bubo-rss-demo.netlify.app/)) `MIT` `Nodejs`
- 🌎 [CommaFeed](www.commafeed.com/) - Google Reader inspired self-hosted RSS reader. ( <b><code>&nbsp;&nbsp;1901⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;322🍴</code></b> [Source Code](https://github.com/Athou/commafeed)) `Apache-2.0` `Java`
-  <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Feedpushr](https://github.com/ncarlier/feedpushr) - Powerful RSS aggregator, able to transform and send articles to many outputs. Single binary, extensible with plugins. `GPL-3.0` `Go`
- 🌎 [FreshRSS](freshrss.org/) - Self-hostable RSS feed aggregator.  🌎 [Demo](demo.freshrss.org/i/),  <b><code>&nbsp;&nbsp;4537⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;502🍴</code></b> [Source Code](https://github.com/FreshRSS/FreshRSS),  <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Clients](https://github.com/Alkarex/EasyRSS)) `AGPL-3.0` `PHP`
- 🌎 [Full-Text RSS](fivefilters.org/content-only) - Extract article content from news sites and blogs and convert RSS feeds that contain only extracts of stories to full-text feeds. Developed by FiveFilters.org.  🌎 [Source Code](bitbucket.org/fivefilters/full-text-rss)) `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Goeland](https://github.com/slurdge/goeland) - Reads RSS/Atom feeds and filter/digest them to create beautiful emails. `MIT` `Go`
- 🌎 [JARR](1pxsolidblack.pl/jarr-en.html) - JARR (Just Another RSS Reader) is a web-based news aggregator and reader (fork of Newspipe).  🌎 [Demo](www.jarr.info/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Source Code](https://github.com/jaesivsm/JARR)) `AGPL-3.0` `Python`
- 🌎 [Kriss Feed](tontof.net/kriss/feed/) - Simple and smart (or stupid) feed reader.  🌎 [Demo](tontof.net/feed/),  <b><code>&nbsp;&nbsp;&nbsp;265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Source Code](https://github.com/tontof/kriss_feed)) `CC0-1.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Leed](https://github.com/LeedRSS/Leed) - Leed (for Light Feed) is a Free and minimalist RSS aggregator. `AGPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;230⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Leselys](https://github.com/toxinu/leselys) - Your very elegant RSS reader. `AGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Lite-Reader](https://github.com/cubny/lite-reader) - Read your feeds on your own machine with a simple and lite application. ([Demo](http://cubny.com/lite-reader/)) `BSD-3-Clause` `PHP`
- 🌎 [Miniflux](miniflux.app/) - Miniflux is a minimalist and open source news reader, written in Go and PostgreSQL. ( <b><code>&nbsp;&nbsp;3796⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;395🍴</code></b> [Source Code](https://github.com/miniflux/v2)) `Apache-2.0` `Go`
- 🌎 [Moonmoon](moonmoon.org/) - Simple feed aggregator (planet like): it only aggregates feeds and spits them out in one single page. ( <b><code>&nbsp;&nbsp;&nbsp;149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Source Code](https://github.com/moonmoon/moonmoon)) `BSD-3-Clause` `PHP`
- 🌎 [NewsBlur](www.newsblur.com/) - NewsBlur is a personal news reader that brings people together to talk about the world. A new sound of an old instrument. ( <b><code>&nbsp;&nbsp;6023⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;957🍴</code></b> [Source Code](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [newsdash](https://github.com/buzz/newsdash) - A news dashboard inspired by iGoogle and Netvibes. `AGPL-3.0` `Nodejs`
- 🌎 [Newspipe](git.sr.ht/~cedric/newspipe) - Newspipe is a web news reader.  🌎 [Demo](www.newspipe.org/signup)) `AGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;306⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [PolitePol](https://github.com/taroved/pol) - Online tool for creation of RSS feeds for any web page.  🌎 [Demo](politepol.com)) `MIT` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [reader](https://github.com/lemon24/reader) - A Python feed reader web app and library (so you can use it to build your own), with only standard library and pure-Python dependencies. `BSD-3-Clause` `Python`
-  <b><code>&nbsp;&nbsp;5068⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;907🍴</code></b> [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge) - Generate RSS/ATOM feeds for websites which don't have one. `Unlicense` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [RSS Fulltext Proxy](https://github.com/Kombustor/rss-fulltext-proxy) - Mirrors RSS feeds to return the full content of the items, extracted from the website. `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;366⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - RSS Monster is an easy to use web-based RSS aggregator and reader compatible with the Fever API, created as an alternative for Google Reader. `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [RSS2EMail](https://github.com/rss2email/rss2email) - Fetches RSS/Atom-feeds and pushes new Content to any email-receiver, supports OPML. `GPL-2.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Screaming Liquid Tiger](https://github.com/herrbischoff/screaming-liquid-tiger) - Simple script to automatically generate valid RSS and Atom feeds from a list of media files in the same folder. `MIT` `PHP`
- 🌎 [Selfoss](selfoss.aditu.de/) - New multipurpose rss reader, live stream, mashup, aggregation web application. ( <b><code>&nbsp;&nbsp;2152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;363🍴</code></b> [Source Code](https://github.com/fossar/selfoss)) `GPL-3.0` `PHP`
- 🌎 [Sismics Reader](www.sismics.com/reader/) - Free and open source feeds reader, including all major Google Reader features.  🌎 [Demo](www.sismics.com/reader/#!/demo),  <b><code>&nbsp;&nbsp;&nbsp;371⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [Source Code](https://github.com/sismics/reader)) `GPL-2.0` `Java`
-  <b><code>&nbsp;&nbsp;3470⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;369🍴</code></b> [Stringer](https://github.com/stringer-rss/stringer) - Work-in-progress self-hosted, anti-social RSS reader. `MIT` `Ruby`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Temboz](https://github.com/fazalmajid/temboz) - Two-column feed reader emphasizing filtering capabilities to manage information overload. `MIT` `Python`
- 🌎 [Tiny Tiny RSS](tt-rss.org) - Open source web-based news feed (RSS/Atom) reader and aggregator.  🌎 [Demo](srv.tt-rss.org/tt-rss/), 🌎 [Source Code](git.tt-rss.org/fox/tt-rss)) `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [ttrss-mobile](https://github.com/mboinet/ttrss-mobile) - Mobile webapp for Tiny Tiny RSS. `AGPL-3.0` `Javascript`
- 🌎 [Winds](getstream.io/winds/) `⚠` - Open source and beautiful RSS reader built using React/Redux/Sails/Node and Stream. It showcases personalized feeds powered by the Stream API.  🌎 [Demo](winds.getstream.io/),  <b><code>&nbsp;&nbsp;8627⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;614🍴</code></b> [Source Code](https://github.com/GetStream/Winds)) `BSD-3-Clause` `Nodejs`


### File Transfer & Synchronization

**[`^        back to top        ^`](#)**

_Related: [Groupware](#groupware)_

- 🌎 [Git Annex](git-annex.branchable.com/) - File synchronization between computers, servers, external drives.  🌎 [Source Code](git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- 🌎 [Kinto](kinto.readthedocs.org) - Kinto is a minimalist JSON storage service with synchronisation and sharing abilities. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/Kinto)) `Apache-2.0` `Python`
-  <b><code>&nbsp;&nbsp;2735⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;357🍴</code></b> [myDrive](https://github.com/subnub/myDrive) - Fully featured online storage solution, upload/download files, photo/video viewer, and more, all through the web client.  🌎 [Demo](mydrive-demo.herokuapp.com/)) `GPL-3.0` `Nodejs`
- 🌎 [Nextcloud](nextcloud.com/) - Access and share your files, calendars, contacts, mail and 🌎 [more](apps.nextcloud.com/) from any device, on your terms.  🌎 [Demo](demo.nextcloud.com/),  <b><code>&nbsp;19600⭐</code></b> <b><code>&nbsp;&nbsp;3132🍴</code></b> [Source Code](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP`
- 🌎 [OpenSSH SFTP server](www.openssh.com/) - Secure File Transfer Program.  🌎 [Source Code](cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh)) `BSD-2-Clause` `C`
- 🌎 [ownCloud](owncloud.org/) - All-in-one solution for saving, synchronizing, viewing, editing and sharing files, calendars, address books and more. ( <b><code>&nbsp;&nbsp;7783⭐</code></b> <b><code>&nbsp;&nbsp;2066🍴</code></b> [Source Code](https://github.com/owncloud/core),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Clients](https://github.com/owncloud/core/wiki/Apps)) `AGPL-3.0` `PHP`
- 🌎 [Peergos](peergos.org) - Secure and private space online where you can store, share and view your photos, videos, music and documents. Also includes a calendar, news feed, task lists, chat and email client. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/Peergos)) `AGPL-3.0` `Java`
- 🌎 [Pydio](pydio.com/) - Turn any web server into a powerful file management system and an alternative to mainstream cloud storage providers.  🌎 [Demo](pydio.com/en/demo),  <b><code>&nbsp;&nbsp;1320⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;131🍴</code></b> [Source Code](https://github.com/pydio/cells)) `AGPL-3.0` `Go`
- 🌎 [Samba](www.samba.org/) - Samba is the standard Windows interoperability suite of programs for Linux and Unix. It provides secure, stable and fast file and print services for all clients using the SMB/CIFS protocol.  🌎 [Source Code](git.samba.org/samba.git/)) `GPL-3.0` `C`
- 🌎 [Seafile](www.seafile.com/en/home/) - File hosting and sharing solution primary for teams and organizations. ( <b><code>&nbsp;&nbsp;9884⭐</code></b> <b><code>&nbsp;&nbsp;1452🍴</code></b> [Source Code](https://github.com/haiwen/seafile)) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- 🌎 [SparkleShare](sparkleshare.org/) - Self hosted, instant, secure file sync. ( <b><code>&nbsp;&nbsp;4746⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;599🍴</code></b> [Source Code](https://github.com/hbons/SparkleShare)) `GPL-3.0` `C#`
- 🌎 [Syncany](www.syncany.org/) - Secure file sync software for arbitrary storage backends, an open-source cloud storage and filesharing application. Securely synchronize your files to any kind of storage. `GPL-3.0` `Java`
- 🌎 [Syncthing](syncthing.net/) - Syncthing is an open source peer-to-peer file synchronisation tool. ( <b><code>&nbsp;45729⭐</code></b> <b><code>&nbsp;&nbsp;3472🍴</code></b> [Source Code](https://github.com/syncthing/syncthing)) `MPL-2.0` `Go`
- 🌎 [Unison](www.cis.upenn.edu/~bcpierce/unison/) - Unison is a file-synchronization tool for OSX, Unix, and Windows. `GPL-3.0` `OCaml`
- 🌎 [Z-Push](z-push.org/) - Implementation of Microsoft’s ActiveSync protocol.  🌎 [Source Code](stash.kopano.io/projects/ZHUB/repos/z-push)) `AGPL-3.0` `PHP`


### File Transfer - Distributed Filesystems

**[`^        back to top        ^`](#)**

**Please visit  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [awesome-sysadmin/Distributed Filesystems](https://github.com/awesome-foss/awesome-sysadmin#distributed-filesystems)**


### File Transfer - Object Storage & File Servers

**[`^        back to top        ^`](#)**

- 🌎 [GarageHQ](garagehq.deuxfleurs.fr/) - An open-source geo-distributed storage service you can self-host to fulfill many needs - S3 compatible.  🌎 [Source Code](git.deuxfleurs.fr/Deuxfleurs/garage)) `AGPL-3.0` `Rust`
- 🌎 [Minio](minio.io/) - Minio is an open source object storage server compatible with Amazon S3 APIs. ( <b><code>&nbsp;34243⭐</code></b> <b><code>&nbsp;&nbsp;4046🍴</code></b> [Source Code](https://github.com/minio/minio)) `Apache-2.0` `Go`
-  <b><code>&nbsp;14844⭐</code></b> <b><code>&nbsp;&nbsp;1811🍴</code></b> [SeaweedFS](https://github.com/chrislusf/seaweedfs) - SeaweedFS is an open source distributed file system supporting WebDAV, S3 API, FUSE mount, HDFS, etc, optimized for lots of small files, and easy to add capacity. `Apache-2.0` `Go`
-  <b><code>&nbsp;&nbsp;4537⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;401🍴</code></b> [SFTPGo](https://github.com/drakkan/sftpgo) - Flexible, fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. `AGPL-3.0` `Go`
- 🌎 [Zenko CloudServer](www.zenko.io/cloudserver) - Zenko CloudServer, an open-source implementation of a server handling the Amazon S3 protocol. ( <b><code>&nbsp;&nbsp;1380⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;223🍴</code></b> [Source Code](https://github.com/scality/cloudserver)) `Apache-2.0` `Nodejs`


### File Transfer - Peer-to-peer Filesharing

**[`^        back to top        ^`](#)**

- 🌎 [bittorrent-tracker](webtorrent.io/) - Simple, robust, BitTorrent tracker (client and server) implementation. ( <b><code>&nbsp;&nbsp;1428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [Source Code](https://github.com/webtorrent/bittorrent-tracker)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;5297⭐</code></b> <b><code>&nbsp;&nbsp;1849🍴</code></b> [cloud-torrent](https://github.com/jpillora/cloud-torrent) - Torrent Web Client with HTTP retrievable or streamable downloaded files. `AGPL-3.0` `Go`
- 🌎 [Dat Project](datproject.org) - Powerful decentralized file sharing applications built from a large ecosystem of modules. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/datproject)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;1473⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [exatorrent](https://github.com/varbhat/exatorrent) - BitTorrent client written in Go that can be run locally or hosted on a remote server, and supports streaming via HTTP. `GPL-3.0` `Go`
- 🌎 [FilePizza](file.pizza/) - Peer-to-peer file transfers in your browser. ( <b><code>&nbsp;&nbsp;3826⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;317🍴</code></b> [Source Code](https://github.com/kern/filepizza)) `BSD-3-Clause` `Nodejs`
-  <b><code>&nbsp;&nbsp;3094⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;438🍴</code></b> [instant.io](https://github.com/webtorrent/instant.io) - Streaming file transfer over WebTorrent.  🌎 [Demo](instant.io)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;2755⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;337🍴</code></b> [Magnetico](https://github.com/boramalper/magnetico) - Magnetico is the first autonomous (self-hosted) BitTorrent DHT search engine suite that is designed for end-users. `AGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;2587⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [Magnetissimo](https://github.com/sergiotapia/magnetissimo) - Search engine that indexes all popular torrent sites. `MIT` `Elixir`
- 🌎 [Opentracker](erdgeist.org/arts/software/opentracker/) - Open and free bittorrent tracker. It aims for minimal resource usage and is intended to run at your wlan router.  🌎 [Source Code](erdgeist.org/gitweb/opentracker/)) `Beerware` `C`
-  <b><code>&nbsp;&nbsp;1240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;617🍴</code></b> [peerflix-server](https://github.com/asapach/peerflix-server) - Downloads torrent files and provides a direct link download or a direct link stream. `MIT` `Nodejs`
- 🌎 [qBittorrent](www.qbittorrent.org/) - Free cross-platform bittorrent client with a feature rich Web UI for remote access. ( <b><code>&nbsp;16512⭐</code></b> <b><code>&nbsp;&nbsp;2847🍴</code></b> [Source Code](https://github.com/qbittorrent/qBittorrent)) `GPL-2.0` `C++`
-  <b><code>&nbsp;&nbsp;2363⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [Send](https://github.com/timvisee/send) - Simple, private, end to end encrypted temporary file sharing, originally built by Mozilla. ( <b><code>&nbsp;&nbsp;2363⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [Clients](https://github.com/timvisee/send#clients)) `MPL-2.0` `Nodejs`
- 🌎 [Transmission](transmissionbt.com/) - Fast, easy, Free Bittorrent client. ( <b><code>&nbsp;&nbsp;7034⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;929🍴</code></b> [Source Code](https://github.com/transmission/transmission)) `GPL-3.0` `C`


### File Transfer - Single-click & Drag-n-drop Upload

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;&nbsp;252⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [ass](https://github.com/tycrek/ass) - The superior self-hosted ShareX server. For use with clients such as ShareX (Windows), Flameshot (Linux), & MagicCap (Linux, macOS). `ISC` `Nodejs`
- 🌎 [Chibisafe](lolisafe.moe/) - Blazing fast file uploader and awesome bunker written in node. ( <b><code>&nbsp;&nbsp;1005⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [Source Code](https://github.com/weebdev/chibisafe)) `MIT` `Nodejs`
- 🌎 [Coquelicot](coquelicot.potager.org/) - Coquelicot is a “one-click” file sharing web application with a focus on protecting users’ privacy.  🌎 [Source Code](coquelicot.potager.org/dist/coquelicot-0.9.6.tar.gz)) `AGPL-3.0` `Ruby`
- 🌎 [elixire](elixi.re) - Simple yet advanced screenshot uploading and link shortening service.  🌎 [Source Code](gitlab.com/elixire/elixire), 🌎 [Clients](gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Files Sharing](https://github.com/axeloz/filesharing) - Open Source and self-hosted files sharing application based on unique and temporary links. `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [FileShelter](https://github.com/epoupon/fileshelter) - FileShelter is a self-hosted software that allows you to easily share files over the Internet. `GPL-3.0` `C++`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [FireShare](https://github.com/rockmanvnx6/FireShare) - A full-stack, pub-sub, real-time secure file sharing system.  🌎 [Demo](auspham.dev/FireShare)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;322⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Gokapi](https://github.com/Forceu/gokapi) - Lightweight server to share files, which expire after a set amount of downloads or days. Similar to the discontinued Firefox Send, with the difference that only the admin is allowed to upload files. `GPL-3.0` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [goploader](https://github.com/Depado/goploader) - Easy file sharing with server-side encryption, curl/httpie/wget compliant. `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [GoSƐ](https://github.com/stv0g/gose) - GoSƐ is a modern file-uploader focusing on scalability and simplicity. It only depends on a S3 storage backend and hence scales horizontally without the need for additional databases or caches.  🌎 [Demo](gose.0l.de)) `Apache-2.0` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [image-uploader](https://github.com/daggy1234/image-uploader) - A shareX compatible image uploader built for speed with a web interface and REST API. `AGPL-3.0` `Rust`
-  <b><code>&nbsp;&nbsp;&nbsp;214⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [imgpush](https://github.com/hauxir/imgpush) - Self-hosted file upload service that can easily be integrated into other webapps. `MIT` `Python`
- 🌎 [Jirafeau](gitlab.com/mojo42/Jirafeau) - Jirafeau is a web site permitting to upload a file in a simple way and give an unique link to it. ([Demo](http://jirafeau.net/)) `AGPL-3.0` `PHP`
- 🌎 [Kleeja](kleeja.net/) - File Upload/sharing application, used by thousands of webmasters since 2007. ( <b><code>&nbsp;&nbsp;&nbsp;157⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [Source Code](https://github.com/kleeja-official/kleeja)) `GPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;135⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [linx-server](https://github.com/ZizzyDizzyMC/linx-server) - Simple file sharing and pastebin with API, auto-expiry, deletion keys, and web seed support.  🌎 [Demo](put.icu/)) `GPL-3.0` `Go`
- 🌎 [lufi](framagit.org/fiat-tux/hat-softwares/lufi) - Let's Upload that FIle, client-side encrypted.  🌎 [Demo](demo.lufi.io), 🌎 [Source Code](framagit.org/fiat-tux/hat-softwares/lufi/tree/master)) `AGPL-3.0` `Perl`
-  <b><code>&nbsp;&nbsp;&nbsp;170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [lutim](https://github.com/ldidry/lutim) - Let's Upload That Image. `AGPL-3.0` `Perl`
-  <b><code>&nbsp;&nbsp;5248⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;613🍴</code></b> [OnionShare](https://github.com/onionshare/onionshare) - Securely and anonymously share a file of any size. `GPL-2.0` `Python`
- 🌎 [PicoShare](pico.rocks) - A minimalist, easy-to-host service for sharing images and other files.  🌎 [Demo](demo.pico.rocks),  <b><code>&nbsp;&nbsp;&nbsp;895⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Source Code](https://github.com/mtlynch/picoshare)) `AGPL-3.0` `Go`
- 🌎 [PictShare](www.pictshare.net/) - PictShare is a multi lingual, open source image hosting service with a simple resizing and upload API. ( <b><code>&nbsp;&nbsp;&nbsp;675⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [Source Code](https://github.com/HaschekSolutions/pictshare)) `Apache-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;1014⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [Plik](https://github.com/root-gg/plik) - Plik is a scalable and friendly temporary file upload system.  🌎 [Demo](plik.root.gg/)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;729⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [Pomf](https://github.com/Pomf/Pomf) - Simple file uploading and sharing, source for the now shut down site Pomf.se. `MIT` `PHP`
- 🌎 [ProjectSend](www.projectsend.org/) - Upload files and assign them to specific clients you create. Give access to those files to your clients. ( <b><code>&nbsp;&nbsp;&nbsp;882⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;252🍴</code></b> [Source Code](https://github.com/projectsend/projectsend)) `GPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;985⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [PsiTransfer](https://github.com/psi-4ward/psitransfer) - Simple open source self-hosted file sharing solution with robust up-/download-resume and password protection. `BSD-2-Clause` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;328⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [QuickShare](https://github.com/ihexxa/quickshare) - Quick and simple file sharing between different devices.  🌎 [Demo](hexxa-quickshare.herokuapp.com/)) `LGPL-3.0` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Share](https://github.com/MrDemonWolf/share) - Simple yet advanced uploader - upload files, images and text with moderation tools for admins. Can be used for friends and family or just for you. Integration with ShareX and more. `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;395⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Sharry](https://github.com/eikek/sharry) - Share files easily over the internet between authenticated and anonymous users (both ways) with resumable up- and downloads. `GPL-3.0` `Scala/Java`
- 🌎 [Snapdrop](snapdrop.net/) - Local file sharing in your browser. Inspired by Apple's Airdrop. ( <b><code>&nbsp;12762⭐</code></b> <b><code>&nbsp;&nbsp;1159🍴</code></b> [Source Code](https://github.com/RobinLinus/snapdrop)) `GPL-3.0-only` `Docker`
- 🌎 [transfer.sh](transfer.sh) - Easy file sharing from the command line. ( <b><code>&nbsp;13029⭐</code></b> <b><code>&nbsp;&nbsp;1364🍴</code></b> [Source Code](https://github.com/dutchcoders/transfer.sh)) `MIT` `Go`
- 🌎 [Uguu](uguu.se/) - Stores files and deletes after X amount of time. ( <b><code>&nbsp;&nbsp;&nbsp;513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Source Code](https://github.com/nokonoko/uguu)) `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;118⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Void](https://github.com/AlphaNecron/Void) - Lightweight, fast and elegant file hosting service for ShareX with Web UI and REST API. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/AlphaNecron/Void/)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Web-File-Uploader](https://github.com/femto-apps/web-file-uploader) - A simple tool to let people upload and share images and files. `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;651⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [XBackBone](https://github.com/SergiX44/XBackBone) - A simple, fast and lightweight file manager with instant sharing tools integration, like ShareX (a free and open-source screenshot utility for Windows). `AGPL-3.0` `PHP`
- 🌎 [YouTransfer](www.youtransfer.io) - YouTransfer is a simple but elegant self-hosted file transfer and sharing solution. ( <b><code>&nbsp;&nbsp;1580⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [Source Code](https://github.com/YouTransfer/YouTransfer)) `Apache-2.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Zipline](https://github.com/diced/zipline) - A lightweight, fast and reliable file sharing server that is commonly used with ShareX, offering a react-based Web UI and fast API. `MIT` `Nodejs`


### File Transfer - Web-based File Managers

**[`^        back to top        ^`](#)**

- 🌎 [Apaxy](oupala.github.io/apaxy/) - Theme built to enhance the experience of browsing web directories, using the mod_autoindex Apache module and some CSS to override the default style of a directory listing. ( <b><code>&nbsp;&nbsp;1725⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;264🍴</code></b> [Source Code](https://github.com/oupala/apaxy)) `GPL-3.0` `HTML`
- 🌎 [DirectoryLister](www.directorylister.com/) - Simple PHP based directory lister that lists a directory and all its sub-directories and allows you to navigate there within. ( <b><code>&nbsp;&nbsp;1672⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;483🍴</code></b> [Source Code](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP`
- 🌎 [filebrowser](filebrowser.org/) - Web File Browser with a Material Design web interface. ( <b><code>&nbsp;16582⭐</code></b> <b><code>&nbsp;&nbsp;2083🍴</code></b> [Source Code](https://github.com/filebrowser/filebrowser)) `Apache-2.0` `Go`
- 🌎 [FileGator](filegator.io/) - FileGator is a powerful multi-user file manager with a single page front-end.  🌎 [Demo](demo.filegator.io),  <b><code>&nbsp;&nbsp;1132⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;261🍴</code></b> [Source Code](https://github.com/filegator/filegator)) `MIT` `PHP`
- 🌎 [Filestash](www.filestash.app/) - A web file manager that lets you manage your data anywhere it is located: FTP, SFTP, WebDAV, Git, S3, Minio, Dropbox, or Google Drive .  🌎 [Demo](demo.filestash.app/),  <b><code>&nbsp;&nbsp;6590⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;483🍴</code></b> [Source Code](https://github.com/mickael-kerjean/filestash)) `AGPL-3.0` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [goBrowser](https://github.com/xataz/gobrowser) - Simple http file browser. `GPL-3.0` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;602⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Gossa](https://github.com/pldubouilh/gossa) - Gossa is a light and simple webserver for your files. `MIT` `Go`
- 🌎 [h5ai](larsjung.de/h5ai/) - Modern file indexer for HTTP web servers with focus on your files. Directories are displayed in a appealing way and browsing them is enhanced by different views, a breadcrumb and a tree overview.  🌎 [Demo](larsjung.de/h5ai/demo/),  <b><code>&nbsp;&nbsp;4922⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;575🍴</code></b> [Source Code](https://github.com/lrsjng/h5ai)) `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;254⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [IFM](https://github.com/misterunknown/ifm) - Single script file manager. `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;3447⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [miniserve](https://github.com/svenstaro/miniserve) - CLI tool to serve files and dirs over HTTP. `MIT` `Rust`
- 🌎 [ResourceSpace](www.resourcespace.com) - ResourceSpace open source digital asset management software is the simple, fast, and free way to organise your digital assets.  🌎 [Demo](www.resourcespace.com/trial), 🌎 [Source Code](www.resourcespace.com/svn)) `BSD-4-Clause` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [s3server](https://github.com/jessfraz/s3server) - Simple HTTP interface to index and browse files in a public S3 or Google Cloud Storage bucket. `MIT` `Go`
- 🌎 [Surfer](git.cloudron.io/cloudron/surfer) - Simple static file server with webui to manage files. `MIT` `Nodejs`
- 🌎 [TagSpaces](www.tagspaces.org/) - TagSpaces is an offline, cross-platform file manager and organiser that also can function as a note taking app. The WebDAV version of the application can be installed on top of a WebDAV servers such as Nextcloud or ownCloud.  🌎 [Demo](demo.tagspaces.com),  <b><code>&nbsp;&nbsp;2652⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;349🍴</code></b> [Source Code](https://github.com/tagspaces/tagspaces)) `AGPL-3.0` `Javascript`
-  <b><code>&nbsp;&nbsp;2014⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;213🍴</code></b> [updog](https://github.com/sc0tfree/updog) - Updog is a replacement for Python's SimpleHTTPServer. It allows uploading and downloading via HTTP/S, can set ad hoc SSL certificates and use http basic auth. `MIT` `Python`


### Games

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;5934⭐</code></b> <b><code>&nbsp;&nbsp;1453🍴</code></b> [A Dark Room](https://github.com/doublespeakgames/adarkroom) - Minimalist text adventure game for your browser.  🌎 [Demo](adarkroom.doublespeakgames.com/)) `MPL-2.0` `HTML5`
- 🌎 [elevatorsaga](play.elevatorsaga.com/) - The elevator programming game. ( <b><code>&nbsp;&nbsp;2096⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;285🍴</code></b> [Source Code](https://github.com/magwo/elevatorsaga)) `MIT` `Javascript`
- 🌎 [EmuLinkerSF](emulinker.org) - EmuLinkerSF is an open source Kaillera server. Kaillera is a client/server system that any emulator can implement to enable netplay over the Internet. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/God-Weapon/EmuLinkerSF)) `GPL-2.0` `Java`
-  <b><code>&nbsp;&nbsp;1928⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;720🍴</code></b> [Hextris](https://github.com/Hextris/hextris) - Fast paced HTML5 puzzle game inspired by Tetris.  🌎 [Demo](hextris.github.io/hextris)) `GPL-3.0` `HTML5`
-  <b><code>&nbsp;&nbsp;&nbsp;125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Legend of the Green Dragon](https://github.com/lotgd/core) - Legend of the Green Dragon is a text-based RPG originally developed by Eric Stevens and JT Traub as a remake of and homage to the classic BBS Door game, Legend of the Red Dragon, by Seth Able Robinson. ([Demo](http://lotgd.net/)) `AGPL-3.0` `PHP`
- 🌎 [Lila](lichess.org/) - The forever free, adless and open source chess server powering lichess.org, with official iOS and Android client apps. ( <b><code>&nbsp;11773⭐</code></b> <b><code>&nbsp;&nbsp;1699🍴</code></b> [Source Code](https://github.com/ornicar/lila)) `AGPL-3.0` `Scala`
- 🌎 [Mindustry](mindustrygame.github.io/) - Factorio-like tower defense game. Build production chains to gather more resources, and build complex facilities. ( <b><code>&nbsp;15133⭐</code></b> <b><code>&nbsp;&nbsp;2127🍴</code></b> [Source Code](https://github.com/Anuken/Mindustry)) `GPL-3.0` `Java`
- 🌎 [Minetest](www.minetest.net/) - An open source voxel game engine. Play one of our many games, mod a game to your liking, make your own game, or play on a multiplayer server. ( <b><code>&nbsp;&nbsp;7328⭐</code></b> <b><code>&nbsp;&nbsp;1565🍴</code></b> [Source Code](https://github.com/minetest/minetest)) `LGPL-2.1/CC-BY-SA-3.0/Other` `C++`
- 🌎 [MTA:SA](mtasa.com/) `⚠` - Multi Theft Auto (MTA) is a software project that adds network play functionality to Rockstar North's Grand Theft Auto game series, in which this functionality is not originally found. ( <b><code>&nbsp;&nbsp;&nbsp;962⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;317🍴</code></b> [Source Code](https://github.com/multitheftauto/mtasa-blue)) `GPL-3.0` `C++`
- 🌎 [Net64+](net64-mod.github.io) `⚠` - Net64 aka SM64O allows playing Super Mario 64 in an online multiplayer mode. Net64+ is the official continuation of the program and features an integrated server list. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/Tarnadas/net64plus-server/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Clients](https://github.com/Tarnadas/net64plus/)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;209⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [node-virtual-gamepads](https://github.com/jehervy/node-virtual-gamepads) - Turn your smartphone into a game controller, keyboard, or touchpad for a remote Linux OS machine. `MIT` `Nodejs/CoffeScript`
-  <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [piqueserver](https://github.com/piqueserver/piqueserver) - Server for openspades, the first-person shooter in a destructible voxel world. ( <b><code>&nbsp;&nbsp;&nbsp;939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [Clients](https://github.com/yvt/openspades)) `GPL-3.0` `Python/C++`
-  <b><code>&nbsp;&nbsp;&nbsp;477⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Posio](https://github.com/abrenaut/posio) - Geography multiplayer game. `MIT` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [QuakeJS](https://github.com/begleysm/quakejs) - QuakeJS is a port of ioquake3 to Javascript that can be played in a browser. `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Quizmaster](https://github.com/nymanjens/quizmaster) - A web-app for conducting a quiz, including a page for players to enter their answers. `Apache-2.0` `Scala`
- 🌎 [SourceBans++](sbpp.github.io) - Admin, ban, and communication management system for games running on the Source engine. ( <b><code>&nbsp;&nbsp;&nbsp;258⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;160🍴</code></b> [Source Code](https://github.com/sbpp/sourcebans-pp)) `CC-BY-SA-4.0` `PHP`
- 🌎 [Teeworlds](www.teeworlds.com) - Open source 2D retro multiplayer shooter. ( <b><code>&nbsp;&nbsp;1936⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;557🍴</code></b> [Source Code](https://github.com/teeworlds/teeworlds)) `BSD-3-Clause/Other` `C++`
-  <b><code>&nbsp;&nbsp;4005⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;784🍴</code></b> [The Battle for Wesnoth](https://github.com/wesnoth/wesnoth) - The Battle for Wesnoth is an Open Source, turn-based tactical strategy game with a high fantasy theme, featuring both singleplayer and online/hotseat multiplayer combat. `GPL-2.0` `C++`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Word Mastermind](https://github.com/clupasq/word-mastermind) - Wordle clone. A Mastermind-like game, but instead of colors you need to guess words.  🌎 [Demo](word-mastermind.glitch.me/)) `MIT` `Nodejs`
- 🌎 [Wordle](reactle.vercel.app/) - An Open Source Wordle game. Guess the Wordle in six tries. Each guess must be a valid five-letter word. ( <b><code>&nbsp;&nbsp;2237⭐</code></b> <b><code>&nbsp;&nbsp;1838🍴</code></b> [Source Code](https://github.com/cwackerfuss/react-wordle)) `MIT` `Nodejs`
- 🌎 [Zero-K](zero-k.info/) - Open Source on Springrts engine. Zero-K is a traditional real time strategy game with a focus on player creativity through terrain manipulation, physics, and a large roster of unique units - all while being balanced to support competitive play. ( <b><code>&nbsp;&nbsp;&nbsp;515⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;183🍴</code></b> [Source Code](https://github.com/ZeroK-RTS/Zero-K)) `GPL-2.0` `Lua`


### Games - Administrative Utilities & Control Panels

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [ARRCON](https://github.com/radj307/ARRCON) - Terminal-based RCON client compatible with any game servers using the Source RCON Protocol. `GPL-3.0` `C++`
- 🌎 [LinuxGSM](linuxgsm.com/) - CLI tool for deployment and management of dedicated game servers on Linux: more than 120 games are supported. ( <b><code>&nbsp;&nbsp;3308⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;704🍴</code></b> [Source Code](https://github.com/GameServerManagers/LinuxGSM)) `MIT` `Shell`
- 🌎 [Pterodactyl](pterodactyl.io/) - Management panel for game servers, with an intuitive UI for end users. ( <b><code>&nbsp;&nbsp;3991⭐</code></b> <b><code>&nbsp;&nbsp;1053🍴</code></b> [Source Code](https://github.com/pterodactyl/panel)) `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [RconCli](https://github.com/gorcon/rcon-cli) - CLI for executing queries on a remote Valve Source dedicated server using the RCON Protocol. `MIT` `Go`


### Gateways and Terminal Sharing

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;1942⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;238🍴</code></b> [asciinema](https://github.com/asciinema/asciinema-server) - Web app for hosting asciicasts.  🌎 [Demo](asciinema.org/)) `Apache-2.0` `Elixir/Docker`
- [GateOne](http://liftoffsoftware.com/Products/GateOne) - Gate One is an HTML5 web-based terminal emulator and SSH client. ( <b><code>&nbsp;&nbsp;6112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;959🍴</code></b> [Source Code](https://github.com/liftoff/GateOne)) `AGPL-3.0` `Python`
- 🌎 [Guacamole](guacamole.apache.org) - Guacamole is a clientless remote desktop gateway. It supports standard protocols like VNC and RDP. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/glyptodon/)) `Apache-2.0` `Java/C`
- 🌎 [Neko](neko.m1k1o.net) - A self hosted virtual browser (rabb.it clone) that runs in Docker. ( <b><code>&nbsp;&nbsp;2027⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [Source Code](https://github.com/m1k1o/neko)) `Apache-2.0` `Docker/Go`
- 🌎 [oneye](oneye-project.org/) - Cloud software to access your data from everywhere with any browser.  🌎 [Demo](wiki.oneye-project.org/0.9:demo),  <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [Source Code](https://github.com/oneye/oneye)) `AGPL-3.0` `PHP`
- 🌎 [OS.js](www.os-js.org/) - Desktop implementation for your browser with a fully-fledged window manager, Application APIs, GUI toolkits and filesystem abstraction.  🌎 [Demo](demo.os-js.org/),  <b><code>&nbsp;&nbsp;6038⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;774🍴</code></b> [Source Code](https://github.com/os-js/OS.js)) `BSD-2-Clause` `Nodejs`
- 🌎 [ShellHub](www.shellhub.io) - ShellHub is a modern SSH server for remotely accessing linux devices via command line (using any SSH client) or web-based user interface, designed as an alternative to sshd. Think ShellHub as centralized SSH for the edge and cloud computing. ( <b><code>&nbsp;&nbsp;&nbsp;927⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/shellhub-io/shellhub)) `Apache-2.0` `Go/Other`
-  <b><code>&nbsp;&nbsp;1100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;213🍴</code></b> [Sshwifty](https://github.com/nirui/sshwifty) - Sshwifty is a SSH and Telnet connector made for the Web. `AGPL-3.0` `Go/Docker`
- 🌎 [Teleport](goteleport.com/) - Certificate authority and access plane for SSH, Kubernetes, web applications, and databases. ( <b><code>&nbsp;12231⭐</code></b> <b><code>&nbsp;&nbsp;1219🍴</code></b> [Source Code](https://github.com/gravitational/teleport)) `Apache-2.0` `Go`
- 🌎 [tmate](tmate.io/) - Instant terminal sharing. ( <b><code>&nbsp;&nbsp;4859⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;268🍴</code></b> [Source Code](https://github.com/tmate-io/tmate)) `ISC` `C`


### Genealogy

**[`^        back to top        ^`](#)**

- 🌎 [Genea.app](genea.app/) - Genea is a privacy by design and open source tool anyone can use to author or edit their family tree. Data is stored in the GEDCOM format and all processing is done in the browser. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Source Code](https://github.com/genea-app/genea-app)) `MIT` `Javascript`
- 🌎 [GeneWeb](geneweb.tuxfamily.org/wiki/GeneWeb) - GeneWeb is an open source genealogy software written in OCaml. It comes with a Web interface and can be used off-line or as a Web service.  🌎 [Demo](demo.geneweb.tuxfamily.org/gw7/),  <b><code>&nbsp;&nbsp;&nbsp;224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [Source Code](https://github.com/geneweb/geneweb)) `GPL-2.0` `OCaml`
- 🌎 [webtrees](www.webtrees.net) - Webtrees is the web's leading on-line collaborative genealogy application.  🌎 [Demo](dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo),  <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Source Code](https://github.com/fisharebest/webtrees)) `GPL-3.0` `PHP`


### Groupware

**[`^        back to top        ^`](#)**

- 🌎 [BlueMind](www.bluemind.net/en/) - Groupware with email, calendar, addressbooks, exchange active sync, exchange MAPI protocol support.  🌎 [Source Code](forge.bluemind.net/stash/projects/BM/repos/bluemind-public/browse)) `AGPL-3.0` `Java`
- 🌎 [Citadel](www.citadel.org/) - Groupware including email, calendar/scheduling, address books, forums, mailing lists, IM, wiki and blog engines, RSS aggregation and more.  🌎 [Source Code](www.citadel.org/source.html)) `GPL-3.0` `C`
- 🌎 [Corteza](cortezaproject.org) - CRM including a unified workspace, enterprise messaging and a low code environment for rapidly and securely delivering records-based management solutions.  🌎 [Demo](latest.cortezaproject.org),  <b><code>&nbsp;&nbsp;&nbsp;498⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [Source Code](https://github.com/cortezaproject/corteza-server)) `Apache-2.0` `Go`
- 🌎 [Cozy Cloud](cozy.io) - Personal cloud where you can manage and sync your contact, files and calendars, and manage your budget with an app store full of community contributions. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/cozy)) `GPL-3.0` `Nodejs`
- 🌎 [egroupware](www.egroupware.org/) - Software suite including calendars, address books, notepad, project management tools, client relationship management tools (CRM), knowledge management tools, a wiki and a CMS. ( <b><code>&nbsp;&nbsp;&nbsp;187⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Source Code](https://github.com/EGroupware/egroupware)) `GPL-2.0` `PHP`
- 🌎 [EspoCRM](www.espocrm.com/) - CRM with a frontend designed as a single page application, and a REST API.  🌎 [Demo](demo.espocrm.com/),  <b><code>&nbsp;&nbsp;&nbsp;961⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;394🍴</code></b> [Source Code](https://github.com/espocrm/espocrm)) `GPL-3.0` `PHP`
- 🌎 [Group Office](www.group-office.com) - Group-Office is an enterprise CRM and groupware tool. Share projects, calendars, files and e-mail online with co-workers and clients. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/Intermesh/groupoffice/)) `AGPL-3.0` `PHP`
- 🌎 [Horde](www.horde.org/) - The Horde Project is about creating high quality Open Source applications and libraries, based on PHP and the Horde Framework. ([Demo](http://demo.horde.org/login.php),  <b><code>&nbsp;&nbsp;&nbsp;244⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;134🍴</code></b> [Source Code](https://github.com/horde/horde)) `GPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [HRCloud2](https://github.com/zelon88/HRCloud2) - Full-featured home hosted Cloud Drive, Personal Assistant, App Launcher, File Converter, Streamer, Share Tool and more. `GPL-3.0` `PHP`
- 🌎 [Kolab](kolab.org/) - Kolab community is a unified communication and collaboration system.  🌎 [Source Code](git.kolab.org/)) `GPL-2.0/LGPL-2.1/GPL-3.0` `C++/Python/PHP`
- 🌎 [Kopano](kopano.com/) - Groupware suite including e-mail, calendars, tasks, todos and notes. Featuring a modern WebApp, DeskApp and mobile access over Z-Push/ActiveSync.  🌎 [Demo](demo.kopano.com), 🌎 [Source Code](stash.kopano.io)) `AGPL-3.0` `C/Python/PHP`
- 🌎 [Openmeetings](openmeetings.apache.org/index.html) - Openmeetings provides video conferencing, instant messaging, white board, collaborative document editing and other groupware tools using API functions of the Red5 Streaming Server for Remoting and Streaming.  🌎 [Source Code](openmeetings.apache.org/scm.html)) `Apache-2.0` `Java`
- 🌎 [SOGo](sogo.nu/) - SOGo offers multiple ways to access the calendaring and messaging data. CalDAV, CardDAV, GroupDAV, as well as ActiveSync, including native Outlook compatibility and Web interface.  🌎 [Demo](demo.sogo.nu/SOGo/),  <b><code>&nbsp;&nbsp;1303⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;245🍴</code></b> [Source Code](https://github.com/inverse-inc/sogo)) `LGPL-2.1` `Objective-C`
- 🌎 [SuiteCRM](suitecrm.com) - The award-winning, enterprise-class open source CRM. ( <b><code>&nbsp;&nbsp;3050⭐</code></b> <b><code>&nbsp;&nbsp;1638🍴</code></b> [Source Code](https://github.com/salesagility/SuiteCRM)) `AGPL-3.0` `PHP`
- 🌎 [Tine 2.0](www.tine20.org) - Contacts, Calendar, Tasks, WebDAV, ActiveSync, VOIP, Mail-Client, CRM, Sales, Projects, Timetracker.  🌎 [Demo](demo.tine20.net), 🌎 [Source Code](packages.tine20.com/maintenance/source/)) `AGPL-3.0/Other` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Tracim](https://github.com/tracim/tracim) - Collaborative Platform for team collaboration: file,threads,notes,agenda,etc. `AGPL-3.0/LGPL-3.0/MIT` `Python`
- 🌎 [Zimbra Collaboration](www.zimbra.com/) - Email, calendar, collaboration server with Web interface and lots of integrations. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`


### Human Resources Management (HRM)

**[`^        back to top        ^`](#)**

- 🌎 [admidio](www.admidio.org/) - Admidio is a free open source user management system for websites of organizations and groups. The system has a flexible role model so that it’s possible to reflect the structure and permissions of your organization.  🌎 [Demo](www.admidio.org/demo/),  <b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [Source Code](https://github.com/Admidio/admidio)) `GPL-2.0` `PHP`
- 🌎 [IceHrm](icehrm.com/) - IceHrm employee management system allows companies to centralize confidential employee information.  🌎 [Demo](icehrm.com/demo.php),  <b><code>&nbsp;&nbsp;&nbsp;430⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [Source Code](https://github.com/gamonoid/icehrm)) `Apache-2.0` `PHP`
- 🌎 [OrangeHRM](www.orangehrm.com/) - OrangeHRM is a comprehensive HRM system that captures all the essential functionalities required for any enterprise.  🌎 [Source Code](sourceforge.net/projects/orangehrm/)) `GPL-2.0` `PHP`
- 🌎 [TimeOff.Management](timeoff.management) - Simple yet powerful absence management software for small and medium size business.  🌎 [Demo](app.timeoff.management),  <b><code>&nbsp;&nbsp;&nbsp;751⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;462🍴</code></b> [Source Code](https://github.com/timeoff-management/timeoff-management-application)) `MIT` `Nodejs`


### Internet of Things (IoT)

**[`^        back to top        ^`](#)**

- 🌎 [DeviceHive](www.devicehive.com/) - Open Source IoT Platform with a wide range of integration options.  🌎 [Demo](playground.devicehive.com/),  <b><code>&nbsp;&nbsp;&nbsp;277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [Source Code](https://github.com/devicehive/devicehive-java-server)) `Apache-2.0` `Java`
- 🌎 [Domoticz](www.domoticz.com/) - Home Automation System that lets you monitor and configure various devices like: Lights, Switches, various sensors/meters like Temperature, Rain, Wind, UV, Electra, Gas, Water and much more. ( <b><code>&nbsp;&nbsp;3136⭐</code></b> <b><code>&nbsp;&nbsp;1105🍴</code></b> [Source Code](https://github.com/domoticz/domoticz),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [Clients](https://github.com/domoticz/domoticz-android)) `GPL-3.0` `C/C++`
- 🌎 [FHEM](fhem.de/fhem.html) - FHEM is used to automate common tasks in the household like switching lamps and heating. It can also be used to log events like temperature or power consumption. You can control it via web or smartphone frontends, telnet or TCP/IP directly.  🌎 [Source Code](svn.fhem.de/trac)) `GPL-3.0` `Perl`
- 🌎 [Gladys](gladysassistant.com/) - Gladys is a privacy-first, open-source home assistant. ( <b><code>&nbsp;&nbsp;2156⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [Source Code](https://github.com/GladysAssistant/Gladys)) `Apache-2.0` `Nodejs`
- 🌎 [Home Assistant](home-assistant.io/) - Open-source home automation platform.  🌎 [Demo](home-assistant.io/demo/),  <b><code>&nbsp;54114⭐</code></b> <b><code>&nbsp;18938🍴</code></b> [Source Code](https://github.com/home-assistant/core)) `Apache-2.0` `Python`
- 🌎 [Node RED](nodered.org/) - Browser-based flow editor that helps you wiring hardware devices, APIs and online services to create IoT solutions. ( <b><code>&nbsp;14961⭐</code></b> <b><code>&nbsp;&nbsp;2817🍴</code></b> [Source Code](https://github.com/node-red/node-red)) `Apache-2.0` `Nodejs`
- 🌎 [openHAB](www.openhab.org) - Vendor and technology agnostic open source software for home automation. ( <b><code>&nbsp;&nbsp;&nbsp;679⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;347🍴</code></b> [Source Code](https://github.com/openhab/openhab-core)) `EPL-2.0` `Java`
- 🌎 [OpenRemote](openremote.io) - Open-Source IoT Platform - IoT Asset management, Flow Rules and WHEN-THEN rules, Data visualization, Edge Gateway.  🌎 [Demo](demo.openremote.io/),  <b><code>&nbsp;&nbsp;&nbsp;612⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Source Code](https://github.com/openremote/openremote)) `AGPL-3.0` `Java`
- 🌎 [SIP Irrigation Control](dan-in-ca.github.io/SIP/) - Open source software for sprinkler/irrigation control. ( <b><code>&nbsp;&nbsp;&nbsp;266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Source Code](https://github.com/Dan-in-CA/SIP)) `GPL-3.0` `Python`
- 🌎 [Thingsboard](thingsboard.io/) - Open-source IoT Platform - Device management, data collection, processing and visualization.  🌎 [Demo](demo.thingsboard.io/signup),  <b><code>&nbsp;12050⭐</code></b> <b><code>&nbsp;&nbsp;3829🍴</code></b> [Source Code](https://github.com/thingsboard/thingsboard)) `Apache-2.0` `Java`
- 🌎 [Thingspeak](thingspeak.com/) - Open source “Internet of Things” application and API to store and retrieve data from things using HTTP.  🌎 [Demo](thingspeak.com/channels/public),  <b><code>&nbsp;&nbsp;&nbsp;992⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;315🍴</code></b> [Source Code](https://github.com/iobridge/thingspeak)) `GPL-3.0` `Ruby`
- 🌎 [WebThings Gateway](webthings.io/gateway/) - WebThings is an open source implementation of the Web of Things, including the WebThings Gateway and the WebThings Framework. ( <b><code>&nbsp;&nbsp;2512⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;346🍴</code></b> [Source Code](https://github.com/WebThingsIO/gateway)) `MPL-2.0` `Nodejs`


### Knowledge Management Tools

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;2460⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;559🍴</code></b> [Mindmaps](https://github.com/drichard/mindmaps) - Open source, offline capable, mind mapping application.  🌎 [Demo](www.mindmaps.app)) `AGPL-3.0` `HTML5`
-  <b><code>&nbsp;&nbsp;2972⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;628🍴</code></b> [My Mind](https://github.com/ondras/my-mind) - Web application for creating and managing mind maps.  🌎 [Demo](my-mind.github.io/?url=examples%2Ffeatures.mymind)) `MIT` `Javascript`
- 🌎 [Weaviate](weaviate.io/) - A cloud-native, realtime vector search engine integrating scalable machine learning models (GraphQL and RESTful APIs). ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Demo](https://github.com/semi-technologies/semantic-search-through-wikipedia-with-weaviate/),  <b><code>&nbsp;&nbsp;2576⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Source Code](https://github.com/semi-technologies/weaviate), 🌎 [Clients](weaviate.io/developers/weaviate/current/client-libraries/index.html)) `BSD-3-Clause` `Go`


### Learning and Courses

**[`^        back to top        ^`](#)**

- 🌎 [Canvas LMS](www.canvaslms.com/) - Canvas is the trusted, open-source learning management system (LMS) that is revolutionizing the way we educate.  🌎 [Demo](canvas.instructure.com/register),  <b><code>&nbsp;&nbsp;4461⭐</code></b> <b><code>&nbsp;&nbsp;1962🍴</code></b> [Source Code](https://github.com/instructure/canvas-lms)) `AGPL-3.0` `Ruby`
- 🌎 [Chamilo LMS](chamilo.org/) - Chamilo LMS allows you to create a virtual campus for the provision of online or semi-online training. ( <b><code>&nbsp;&nbsp;&nbsp;631⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;429🍴</code></b> [Source Code](https://github.com/chamilo/chamilo-lms)) `GPL-3.0` `PHP`
- 🌎 [Dalton Plan](daltonplan.com) - Dalton Plan is a modern adoption of a free teaching method developed by Helen Parkhurst in the 20th century.  🌎 [Source Code](git.io/daltonplan)) `AGPL-3.0` `PHP`
- 🌎 [edX](www.edx.org/) - The Open edX platform is open-source code that powers edX.org. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/edx/)) `AGPL-3.0` `Python`
- 🌎 [Gibbon](www.gibbonedu.org/) - The flexible, open source school management platform designed to make life better for teachers, students, parents and leaders. ( <b><code>&nbsp;&nbsp;&nbsp;336⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;244🍴</code></b> [Source Code](https://github.com/GibbonEdu/core)) `GPL-3.0` `PHP`
- 🌎 [ILIAS](www.ilias.de) - ILIAS is the Learning Management System that can cope with anything you throw at it.  🌎 [Demo](demo.ilias.de),  <b><code>&nbsp;&nbsp;&nbsp;301⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;264🍴</code></b> [Source Code](https://github.com/ILIAS-eLearning/ILIAS)) `GPL-3.0` `PHP`
- 🌎 [Mahara](mahara.org/) - Open Source fully featured web application to build students electronic portfolio. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [Source Code](https://github.com/MaharaProject/mahara)) `GPL-3.0` `PHP`
- 🌎 [Moodle](moodle.org/) - Moodle is a learning and courses platform with one of the largest open source communities worldwide.  🌎 [Demo](moodle.org/demo/), 🌎 [Source Code](git.moodle.org/gw)) `GPL-3.0` `PHP`
- 🌎 [Open eClass](www.openeclass.org/) - Open eClass is an advanced e-learning solution that can enhance the teaching and learning process.  🌎 [Demo](demo.openeclass.org/),  <b><code>&nbsp;&nbsp;&nbsp;106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Source Code](https://github.com/gunet/openeclass)) `GPL-2.0` `PHP`
- 🌎 [OpenOLAT](www.openolat.com/?lang=en) - OpenOLAT is a web-based learning management system for teaching, education, assessment and communication.  🌎 [Demo](learn.olat.com),  <b><code>&nbsp;&nbsp;&nbsp;199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [Source Code](https://github.com/OpenOLAT/OpenOLAT)) `Apache-2.0` `Java`
- 🌎 [RELATE](documen.tician.de/relate/) - RELATE is a web-based courseware package, includes features such as: flexible rules, statistics, multi-course support, class calendar. ( <b><code>&nbsp;&nbsp;&nbsp;295⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [Source Code](https://github.com/inducer/relate)) `MIT` `Python`
- 🌎 [RosarioSIS](www.rosariosis.org/) - RosarioSIS, free Student Information System for school management.  🌎 [Demo](www.rosariosis.org/demo/), 🌎 [Source Code](gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`
- 🌎 [Sakai](www.sakaiproject.org/) - The Sakai project provides a flexible and feature-rich environment for teaching, learning, research and other collaboration.  🌎 [Demo](www.sakaiproject.org/try-sakai),  <b><code>&nbsp;&nbsp;&nbsp;862⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;842🍴</code></b> [Source Code](https://github.com/sakaiproject/sakai)) `ECL-2.0` `Java`
- 🌎 [Vocascan](vocascan.com/) - A highly configurable vocabulary trainer. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Source Code](https://github.com/vocascan/vocascan-server),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Clients](https://github.com/vocascan/vocascan-desktop)) `Apache-2.0` `Nodejs`


### Maps and Global Positioning System (GPS)

**[`^        back to top        ^`](#)**

_See also:  <b><code>&nbsp;&nbsp;2931⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;585🍴</code></b> [awesome-gis](https://github.com/sshuair/awesome-gis)_

-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Bicimon](https://github.com/knrdl/bicimon) - Bike Speedometer as Progressive Web App.  🌎 [Demo](knrdl.github.io/bicimon/)) `MIT` `HTML5`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Geo2tz](https://github.com/noandrea/geo2tz) - Get the timezone from geo coordinates (lat, lon). `MIT` `Go/Docker`
- 🌎 [GraphHopper](graphhopper.com/) - Fast routing library and server using OpenStreetMap. ( <b><code>&nbsp;&nbsp;3724⭐</code></b> <b><code>&nbsp;&nbsp;1301🍴</code></b> [Source Code](https://github.com/graphhopper/graphhopper)) `Apache-2.0` `Java`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [H3 Viewer](https://github.com/clupasq/h3-viewer) - View/search Uber H3 (Hexagonal Hierarchical Spatial Index) cells on a map.  🌎 [Demo](wolf-h3-viewer.glitch.me/)) `Apache-2.0` `HTML5`
-  <b><code>&nbsp;&nbsp;&nbsp;408⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Hauk](https://github.com/bilde2910/Hauk) - Easy to setup location sharing platform that lets you temporarily share your location with anyone in real-time. ( <b><code>&nbsp;&nbsp;&nbsp;408⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Demo](https://github.com/bilde2910/Hauk#demo-server)) `Apache-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [MapBBCodeShare](https://github.com/MapBBCode/share.mapbbcode.org) - Tool for sharing custom OSM maps. Support for annotated markers, polygons, lines, multi-format import/export, multiple layers, shortlinks. ([Demo](http://share.mapbbcode.org/)) `WTFPL/Other` `PHP`
- 🌎 [Nominatim](nominatim.org/) - Server application for reverse geocoding (address -> coordinates) on OpenStreetMap data. ( <b><code>&nbsp;&nbsp;2084⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;572🍴</code></b> [Source Code](https://github.com/osm-search/Nominatim)) `GPL-2.0` `C`
- [Open Source Routing Machine (OSRM)](http://project-osrm.org/) - High performance routing engine designed to run on OpenStreetMap data and offering an HTTP API, C++ library interface, and Nodejs wrapper.  🌎 [Demo](map.project-osrm.org/),  <b><code>&nbsp;&nbsp;5058⭐</code></b> <b><code>&nbsp;&nbsp;2748🍴</code></b> [Source Code](https://github.com/Project-OSRM/osrm-backend)) `BSD-2-Clause` `C++`
- [OpenGTS](http://www.opengts.org/) - Entry-level fleet tracking system. Supports variety of tracking devices and protocols. Comes with rich web-interface and reporting features. ([Demo](http://track.opengts.org/track/Track), 🌎 [Source Code](sourceforge.net/projects/opengts/files/server-base/)) `Apache-2.0` `Java`
- 🌎 [OpenStreetMap](www.openstreetmap.org/) - Collaborative project to create a free editable map of the world. ( <b><code>&nbsp;&nbsp;1533⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;786🍴</code></b> [Source Code](https://github.com/openstreetmap/openstreetmap-website), 🌎 [Clients](wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- 🌎 [OpenTripPlanner](www.opentripplanner.org/) - Multimodal trip planning software based on OpenStreetMap data and consuming published GTFS-formatted data to suggest routes using local public transit systems. ( <b><code>&nbsp;&nbsp;1727⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;932🍴</code></b> [Source Code](https://github.com/opentripplanner/OpenTripPlanner)) `LGPL-3.0` `Java/Javascript`
-  <b><code>&nbsp;&nbsp;&nbsp;621⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - Store and access data published by 🌎 [OwnTracks](owntracks.org/) location tracking apps. `GPL-2.0` `C/Lua`
- 🌎 [TileServer GL](tileserver.readthedocs.io/) - Vector and raster maps with GL styles. Server side rendering by Mapbox GL Native. Map tile server for Mapbox GL JS, Android, iOS, Leaflet, OpenLayers, GIS via WMTS, etc. ( <b><code>&nbsp;&nbsp;1513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;521🍴</code></b> [Source Code](https://github.com/maptiler/tileserver-gl)) `BSD-2-Clause` `Nodejs`
- 🌎 [TileServer PHP](www.maptiler.com/server/) - Serve map tiles from any PHP hosting. ( <b><code>&nbsp;&nbsp;&nbsp;508⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;151🍴</code></b> [Source Code](https://github.com/maptiler/tileserver-php)) `BSD-2-Clause` `PHP`
- 🌎 [Traccar](www.traccar.org/) - Java application to track GPS positions. Supports loads of tracking devices and protocols, has an Android and iOS App. Has a web interface to view your trips.  🌎 [Demo](demo.traccar.org/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/traccar)) `Apache-2.0` `Java`
- 🌎 [uMap](umap.openstreetmap.fr/en/) - Create maps with OpenStreetMap layers in a minute and embed them in your site. ( <b><code>&nbsp;&nbsp;&nbsp;741⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [Source Code](https://github.com/umap-project/umap)) `WTFPL` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;398⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [μlogger](https://github.com/bfabiszewski/ulogger-server) - Collect geolocation from users in real-time and display their GPS tracks on a website. ([Demo](http://ulogger.fabiszewski.net/)) `GPL-3.0` `PHP`


### Media Streaming

**[`^        back to top        ^`](#)**

**Please visit [Media streaming - Audio Streaming](#media-streaming---audio-streaming), [Media streaming - Multimedia Streaming](#media-streaming---multimedia-streaming), [Media streaming - Video Streaming](#media-streaming---video-streaming)**

_See also: 🌎 [List of streaming media systems - Wikipedia](en.wikipedia.org/wiki/List_of_streaming_media_systems), 🌎 [Comparison of streaming media systems - Wikipedia](en.wikipedia.org/wiki/Comparison_of_streaming_media_systems)_


### Media Streaming - Audio Streaming

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;&nbsp;693⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [Airsonic Advanced](https://github.com/airsonic-advanced/airsonic-advanced) - Open-source web-based media streamer and jukebox based on Airsonic, with several key performance and feature enhancements. `GPL-3.0` `Java`
- 🌎 [Ampache](ampache.org/) - Web based audio/video streaming application.  🌎 [Demo](play.dogmazic.net/),  <b><code>&nbsp;&nbsp;3070⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;555🍴</code></b> [Source Code](https://github.com/ampache/ampache)) `AGPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Audioserve](https://github.com/izderadicka/audioserve) - Simple personal server to serve audio files from directories (audiobooks, music, podcasts...). Focused on simplicity and supports sync of play position between clients. `MIT` `Rust`
- 🌎 [AzuraCast](www.azuracast.com/) - A modern and accessible self-hosted web radio management suite. ( <b><code>&nbsp;&nbsp;2044⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;462🍴</code></b> [Source Code](https://github.com/AzuraCast/AzuraCast)) `Apache-2.0` `PHP`
- 🌎 [Beets](beets.io/) - Music library manager and MusicBrainz tagger (command-line and Web interface). ( <b><code>&nbsp;11060⭐</code></b> <b><code>&nbsp;&nbsp;1737🍴</code></b> [Source Code](https://github.com/beetbox/beets)) `MIT` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;860⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [Black Candy](https://github.com/blackcandy-org/black_candy) - Music streaming server built with Rails and Stimulus. `MIT` `Ruby`
- 🌎 [euterpe](listen-to-euterpe.eu) - Self-hosted music streaming server with RESTful API and Web interface.  🌎 [Demo](listen-to-euterpe.eu/demo),  <b><code>&nbsp;&nbsp;&nbsp;418⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Source Code](https://github.com/ironsmile/euterpe)) `GPL-3.0` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [FriendsRadio](https://github.com/xouabita/friends-radio) `⚠` - Share music with your friends from Youtube and Soundcloud.  🌎 [Demo](friends-radio.herokuapp.com/)) `MIT` `Nodejs`
- 🌎 [Funkwhale](dev.funkwhale.audio/funkwhale) - Modern, web-based, convivial, multi-user and free music server. `BSD-3-Clause` `Python/Django`
- 🌎 [GNU FM](gnu.io/fm/) - Running music community websites, alternative to last.fm.  🌎 [Source Code](git.savannah.gnu.org/cgit/librefm.git/)) `AGPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;833⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [gonic](https://github.com/sentriz/gonic) - Lightweight music streaming server. Subsonic compatible. `GPL-3.0` `Go`
-  <b><code>&nbsp;&nbsp;1800⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [Groove Basin](https://github.com/andrewrk/groovebasin) - Music player server with a web-based user interface inspired by Amarok 1.4. `MIT` `Nodejs`
- 🌎 [koel](koel.dev/) - Personal music streaming server that works.  🌎 [Demo](demo.koel.dev/),  <b><code>&nbsp;13795⭐</code></b> <b><code>&nbsp;&nbsp;1754🍴</code></b> [Source Code](https://github.com/koel/koel)) `MIT` `PHP`
- 🌎 [KooZic](koozic.net/) - Music server with powerful playlist features and Subsonic compatibility.  🌎 [Demo](demo.koozic.net/public),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/DocMarty84/koozic)) `LGPL-3.0/MIT` `Python`
- 🌎 [LibreTime](libretime.org) - Simple, open source platform that lets you broadcast streaming radio on the web (fork of  <b><code>&nbsp;&nbsp;&nbsp;604⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;268🍴</code></b> [Airtime](https://github.com/sourcefabric/Airtime)). ( <b><code>&nbsp;&nbsp;&nbsp;612⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [Source Code](https://github.com/LibreTime/libretime)) `AGPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;638⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [LMS](https://github.com/epoupon/lms) - Access your self-hosted music using a web interface. `GPL-3.0` `C++`
- 🌎 [moOde Audio](moodeaudio.org/) - Audiophile-quality music playback for the wonderful Raspberry Pi family of single board computers. ( <b><code>&nbsp;&nbsp;&nbsp;618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;140🍴</code></b> [Source Code](https://github.com/moode-player/moode)) `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [Mopidy MusicBox](https://github.com/pimusicbox/mopidy-musicbox-webclient) - Web Client for Mopidy Music Server. `Apache-2.0` `HTML5`
- 🌎 [Mopidy](docs.mopidy.com/) - Extensible music server. Offers a superset of the mpd API, as well as integration with 3rd party services like Spotify, SoundCloud etc. ( <b><code>&nbsp;&nbsp;7440⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;680🍴</code></b> [Source Code](https://github.com/mopidy/mopidy)) `Apache-2.0` `Python`
- 🌎 [mpd](www.musicpd.org/) - Daemon to remotely play music, stream music, handle and organize playlists. Many clients available. ( <b><code>&nbsp;&nbsp;1650⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;286🍴</code></b> [Source Code](https://github.com/MusicPlayerDaemon/MPD), 🌎 [Clients](www.musicpd.org/clients/)) `GPL-2.0` `C++`
- 🌎 [mStream](mstream.io/) - Music streaming server with GUI management tools. Runs on Mac, Windows, and Linux. ( <b><code>&nbsp;&nbsp;1850⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;157🍴</code></b> [Source Code](https://github.com/IrosTheBeggar/mStream)) `GPL-2.0` `Nodejs`
- 🌎 [musikcube](musikcube.com/) - Streaming audio server with Linux/macOS/Windows/Android clients. ( <b><code>&nbsp;&nbsp;3151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [Source Code](https://github.com/clangen/musikcube)) `BSD-3-Clause` `C++`
- 🌎 [Navidrome Music Server](www.navidrome.org) - Modern Music Server and Streamer, compatible with Subsonic/Airsonic.  🌎 [Demo](www.navidrome.org/demo),  <b><code>&nbsp;&nbsp;4051⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;379🍴</code></b> [Source Code](https://github.com/navidrome/navidrome), 🌎 [Clients](www.navidrome.org/docs/overview/#apps)) `GPL-3.0` `Go/Javascript`
-  <b><code>&nbsp;&nbsp;&nbsp;929⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [Polaris](https://github.com/agersant/polaris) - Music browsing and streaming application optimized for large music collections, ease of use and high performance. `MIT` `Rust`
-  <b><code>&nbsp;&nbsp;&nbsp;613⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Raveberry](https://github.com/raveberry/raveberry) - A multi-user music server with a focus on participation.  🌎 [Demo](demo.raveberry.party/)) `LGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;4595⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;394🍴</code></b> [Snapcast](https://github.com/badaix/snapcast) - Synchronous multiroom audio server. `GPL-3.0` `C++`
-  <b><code>&nbsp;&nbsp;&nbsp;567⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Stretto](https://github.com/benkaiser/stretto) - Music player with Youtube/Soundcloud import and iTunes/Spotify discovery.  🌎 [Demo](next.kaiserapps.com),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Clients](https://github.com/benkaiser/stretto-mobile-next)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;221⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Supysonic](https://github.com/spl0k/supysonic) - Python implementation of the Subsonic server API. `AGPL-3.0` `Python`
- 🌎 [Volumio](volumio.org/) - A free and open source linux distribution, designed and fine-tuned exclusively for music playback. ( <b><code>&nbsp;&nbsp;1337⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;332🍴</code></b> [Source Code](https://github.com/volumio/Volumio2)) `GPL-3.0` `Nodejs`
- 🌎 [ympd](ympd.org/) - Standalone MPD Web GUI written in C, utilizing Websockets and Bootstrap/JS. ( <b><code>&nbsp;&nbsp;&nbsp;499⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [Source Code](https://github.com/notandy/ympd)) `GPL-2.0` `C`


### Media Streaming - Multimedia Streaming

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;2893⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [Dim](https://github.com/Dusk-Labs/dim) - Dim is a self-hosted media manager fueled by dark forces. With minimal setup, Dim will organize and beautify your media collections, letting you access and play them anytime from anywhere. `GPL-2.0` `Rust`
- 🌎 [Gerbera](gerbera.io/) - Gerbera is an UPnP Media Server. It allows you to stream your digital media throughout your home network and listen to/watch it on a variety of UPnP compatible devices. ( <b><code>&nbsp;&nbsp;&nbsp;947⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;191🍴</code></b> [Source Code](https://github.com/gerbera/gerbera)) `GPL-2.0` `C++`
-  <b><code>&nbsp;&nbsp;&nbsp;832⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [homehost](https://github.com/ridhwaans/homehost) `⚠` - Self-hosted React + Redux app that streams your media collection (music, movies, books, podcasts, comics etc). `MIT` `Nodejs`
- 🌎 [Icecast 2](icecast.org) - Streaming audio/video server which can be used to create an Internet radio station or a privately running jukebox and many things in between.  🌎 [Source Code](gitlab.xiph.org/xiph/icecast-server), 🌎 [Clients](icecast.org/apps/)) `GPL-2.0` `C`
- 🌎 [Jellyfin](jellyfin.org) - Media server for audio, video, books, comics, and photos with a sleek interface and robust transcoding capabilities. Almost all modern platforms have clients, including Roku, Android TV, iOS, and Kodi.  🌎 [Demo](demo.jellyfin.org/stable),  <b><code>&nbsp;15641⭐</code></b> <b><code>&nbsp;&nbsp;1577🍴</code></b> [Source Code](https://github.com/jellyfin/jellyfin)) `GPL-2.0` `C#`
- 🌎 [Karaoke Eternal](www.karaoke-eternal.com) - Host awesome karaoke parties where everyone can easily find and queue songs from their phone's browser. The player is also fully browser-based with support for MP3+G, MP4 and WebGL visualizations.  🌎 [Source Code](www.karaoke-eternal.com/repo)) `ISC` `Nodejs`
- 🌎 [Kodi](kodi.tv/) - Multimedia/Entertainment center, formerly known as XBMC. Runs on Android, BSD, Linux, macOS, iOS and Windows. ( <b><code>&nbsp;13992⭐</code></b> <b><code>&nbsp;&nbsp;5948🍴</code></b> [Source Code](https://github.com/xbmc/xbmc)) `GPL-2.0` `C++`
- 🌎 [LBRY](lbry.com/) - Is a secure, open, and community-run digital marketplace that aims to replace Youtube and Amazon.  🌎 [Demo](lbry.tv/),  <b><code>&nbsp;&nbsp;&nbsp;246⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;245🍴</code></b> [Source Code](https://github.com/lbryio/lbry.com),  <b><code>&nbsp;&nbsp;3570⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;449🍴</code></b> [Clients](https://github.com/lbryio/lbry-desktop)) `MIT` `PHP`
- 🌎 [MistServer](mistserver.org/) - Streaming media server that works well in any streaming environment. ( <b><code>&nbsp;&nbsp;&nbsp;248⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Source Code](https://github.com/DDVTECH/mistserver)) `AGPL-3.0` `C++`
- [NymphCast](http://nyanko.ws/nymphcast.php) - NymphCast is a Chromecast alternative which turns your choice of Linux-capable hardware into an audio and video source for a television or powered speakers. ( <b><code>&nbsp;&nbsp;2184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [Source Code](https://github.com/MayaPosch/NymphCast)) `BSD-3-Clause` `C++`
- 🌎 [Podify](www.podify.org/) - Allows you to download videos and audio from any source supported by youtube-dl and subscribe to and watch these downloads using your favorite podcast app. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/podify-org/podify/)) `GPL-3.0` `Ruby`
- 🌎 [ReadyMedia](sourceforge.net/projects/minidlna/) - Simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients. Formerly known as MiniDLNA.  🌎 [Source Code](sourceforge.net/p/minidlna/git/ci/master/tree/)) `GPL-2.0` `C`
- 🌎 [Rygel](wiki.gnome.org/action/show/Projects/Rygel) - Rygel is a UPnP AV MediaServer that allows you to easily share audio, video, and pictures. Media player software may use Rygel to become a MediaRenderer that may be controlled remotely by a UPnP or DLNA Controller.  🌎 [Source Code](gitlab.gnome.org/GNOME/rygel/)) `GPL-3.0` `C`
- 🌎 [SheetAble](sheetable.net) - Self-hosted music sheet organizing software for all music enthusiasts. Upload and organize your sheets for any kind of instrument. ( <b><code>&nbsp;&nbsp;&nbsp;165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Source Code](https://github.com/SheetAble/SheetAble)) `AGPL-3.0` `Go`
- 🌎 [Stash](stashapp.cc) - A web-based library organizer and player for your adult media stash, with auto-tagging and metadata scraping support. ( <b><code>&nbsp;&nbsp;2111⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;319🍴</code></b> [Source Code](https://github.com/stashapp/stash)) `AGPL-3.0` `Go`
- 🌎 [üWave](u-wave.net/) `⚠` - Self-hosted collaborative listening platform. Users take turns playing media—songs, talks, gameplay videos, or anything else—from a variety of media sources like YouTube and SoundCloud.  🌎 [Demo](wlk.yt/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/u-wave)) `MIT` `Nodejs`


### Media Streaming - Video Streaming

**[`^        back to top        ^`](#)**

- 🌎 [Bluecherry](www.bluecherrydvr.com/) - Closed-circuit television (CCTV) software application which supports IP and Analog cameras. ( <b><code>&nbsp;&nbsp;&nbsp;137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [Source Code](https://github.com/bluecherrydvr/bluecherry-apps)) `GPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [cmyflix](https://github.com/farfalleflickan/cmyflix) `⚠` - Self-hosted, super lightweight Netflix alternative. `AGPL-3.0` `C`
-  <b><code>&nbsp;&nbsp;1249⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [CyTube](https://github.com/calzoneman/sync) - CyTube is a web application providing media synchronization, chat, and more for an arbitrary number of channels.  🌎 [Demo](cytu.be)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;7823⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;702🍴</code></b> [Invidious](https://github.com/iv-org/invidious) - `⚠` Invidious is an alternative front-end to YouTube.  🌎 [Demo](docs.invidious.io/instances/)) `AGPL-3.0` `Crystal`
- 🌎 [Kerberos.io](kerberos.io) - Kerberos.io is a video surveillance solution, which works with any camera and on every Linux based machine (Raspberry Pi, Docker, Kubernetes cluster).  🌎 [Demo](demo.kerberos.io/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Source Code](https://github.com/kerberos-io/kerberos-docker)) `MIT` `C++`
- 🌎 [MediaCMS](mediacms.io) - MediaCMS is a modern, fully featured open source video and media CMS, written in Python/Django/React, featuring a REST API. ( <b><code>&nbsp;&nbsp;1018⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;188🍴</code></b> [Source Code](https://github.com/mediacms-io/mediacms)) `AGPL-3.0` `Python/Docker`
-  <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Oblecto](https://github.com/robinp7720/Oblecto) `⚠` - Media server for Movies and TV Shows with a responsive Vue.js frontend. It has robust transcoding support as well as federation capabilities to share your library with your friends. `AGPL-3.0` `Nodejs`
- 🌎 [Oddworks](gitlab.com/oddnetworks/oddworks/core) - Oddworks is an open source video distribution platform built to destroy the barriers to streaming television with SDKs for Roku, Apple iOS/tvOS, Google Android, and Amazon FireTV. `MIT` `Nodejs`
- 🌎 [Olaris](gitlab.com/olaris/olaris-server) - Olaris is an open-source, community driven, media manager and transcoding server. `GPL-3.0` `Go`
- 🌎 [Open Streaming Platform](openstreamingplatform.com) - Self-Hosted alternative to Twitch and Youtube Live for live and on-demand video streaming.  🌎 [Source Code](gitlab.com/Deamos/flask-nginx-rtmp-manager)) `MIT` `Python`
- 🌎 [OvenMediaEngine](ovenmediaengine.com) - OvenMediaEngine is a selfhostable Open-Source Streaming Server with Sub-Second Latency.  🌎 [Demo](demo.ovenplayer.com),  <b><code>&nbsp;&nbsp;1531⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;304🍴</code></b> [Source Code](https://github.com/AirenSoft/OvenMediaEngine)) `GPL-3.0` `C++`
-  <b><code>&nbsp;&nbsp;6194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;454🍴</code></b> [Owncast](https://github.com/owncast/owncast) - Owncast is an open source, self-hosted, decentralized, single user live video streaming and chat server for running your own live streams similar in style to the large mainstream options. `MIT` `Go`
- 🌎 [PeerTube](joinpeertube.org/en/) - Decentralized video streaming platform using P2P (BitTorrent) directly in the web browser. ( <b><code>&nbsp;10843⭐</code></b> <b><code>&nbsp;&nbsp;1220🍴</code></b> [Source Code](https://github.com/Chocobozzz/PeerTube)) `AGPL-3.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Radium](https://github.com/Zibbp/Radium) - Synced stream and video playback with VOD capabilities utilizing HLS. Developed for movie nights but has many use cases.  🌎 [Demo](radium-demo.herokuapp.com)) `MIT` `Nodejs/Docker`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Rapidbay](https://github.com/hauxir/rapidbay/) - Self-hosted torrent videostreaming service/torrent client that allows searching and playing videos from torrents in the browser or from a Chromecast/AppleTV/Smart TV. `MIT` `Python/Docker`
- 🌎 [Restreamer](datarhei.github.io/restreamer/) - Restreamer allows you to do h.264 real-time video streaming on your website without a streaming provider. ( <b><code>&nbsp;&nbsp;1861⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;280🍴</code></b> [Source Code](https://github.com/datarhei/restreamer)) `Apache-2.0` `Nodejs/Docker`
- 🌎 [ShinobiCE](gitlab.com/Shinobi-Systems/ShinobiCE) - Open Source CCTV software written in Node with both IP and local camera support. `AGPL-3.0/GPL-3.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;9128⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;990🍴</code></b> [Streama](https://github.com/streamaserver/streama) - Self hosted streaming media server. `MIT` `Java`
-  <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [SyncTube](https://github.com/RblSb/SyncTube) - Lightweight and very simple to setup CyTube alternative to watch videos with friends and chat.  🌎 [Demo](synctube-example.herokuapp.com/)) `MIT` `Nodejs/Haxe`
- 🌎 [Tube](git.mills.io/prologic/tube) - Youtube-like (_without censorship and features you don't need!_) Video Sharing App written in Go which also supports automatic transcoding to MP4 H.265 AAC, multiple collections and RSS feed.  🌎 [Demo](tube.mills.io)) `MIT` `Go`
- 🌎 [VideoLAN Client (VLC)](www.videolan.org/) - Cross-platform multimedia player client and server supporting most multimedia files as well as DVDs, Audio CDs, VCDs, and various streaming protocols. ( <b><code>&nbsp;&nbsp;9227⭐</code></b> <b><code>&nbsp;&nbsp;3116🍴</code></b> [Source Code](https://github.com/videolan/vlc)) `GPL-2.0` `C`
- 🌎 [Zoneminder](www.zoneminder.com/) - Closed-circuit television (CCTV) software application which supports IP, USB and Analog cameras. ( <b><code>&nbsp;&nbsp;3741⭐</code></b> <b><code>&nbsp;&nbsp;1063🍴</code></b> [Source Code](https://github.com/ZoneMinder/ZoneMinder)) `GPL-2.0` `PHP`


### Miscellaneous

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;&nbsp;507⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [2FAuth](https://github.com/Bubka/2FAuth) - A web app to manage your Two-Factor Authentication (2FA) accounts and generate their security codes.  🌎 [Demo](demo.2fauth.app/)) `AGPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;964⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [411](https://github.com/etsy/411) - Alert Management Web Application. `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [AlertHub](https://github.com/Ardakilic/alerthub) `⚠` - AlertHub is a simple tool to get alerted from GitHub releases. `MIT` `Nodejs`
- 🌎 [Anchr](anchr.io) - Anchr is a toolbox for tiny tasks on the internet, including bookmark collections, URL shortening and (encrypted) image uploads. ( <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Source Code](https://github.com/muety/anchr)) `GPL-3.0` `Nodejs`
- 🌎 [asciiflow](asciiflow.com/) - Flow Diagram Drawing Tool. ( <b><code>&nbsp;&nbsp;3130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;276🍴</code></b> [Source Code](https://github.com/lewish/asciiflow)) `MIT` `Nodejs`
- 🌎 [CapRover](caprover.com/) - Build your own PaaS in a few minutes.  🌎 [Demo](captain.server.demo.caprover.com/#/login),  <b><code>&nbsp;&nbsp;8864⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;608🍴</code></b> [Source Code](https://github.com/caprover/caprover)) `Apache-2.0` `Docker/Nodejs`
-  <b><code>&nbsp;&nbsp;4938⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;280🍴</code></b> [changedetection.io](https://github.com/dgtlmoon/changedetection.io) - Self-hosted tool for staying up-to-date with web-site content changes. `Apache-2.0` `Python/Docker`
- 🌎 [CloudBeaver](cloudbeaver.io/) - Self-hosted management of databases, supports PostgreSQL, MySQL, SQLite and more. A web/hosted version of DBeaver. ( <b><code>&nbsp;&nbsp;1715⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [Source Code](https://github.com/dbeaver/cloudbeaver)) `Apache-2.0` `Nodejs`
- 🌎 [CUPS](www.cups.org/) - The Common Unix Print System uses Internet Printing Protocol (IPP) to support printing to local and network printers. ( <b><code>&nbsp;&nbsp;1539⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;416🍴</code></b> [Source Code](https://github.com/apple/cups)) `GPL-2.0` `C`
-  <b><code>&nbsp;17009⭐</code></b> <b><code>&nbsp;&nbsp;2114🍴</code></b> [CyberChef](https://github.com/gchq/CyberChef) - Perform all manner of operations within a web browser such as AES, DES and Blowfish encryption and decryption, creating hexdumps, calculating hashes, and much more.  🌎 [Demo](gchq.github.io/CyberChef)) `Apache-2.0` `Javascript`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [DailyTxT](https://github.com/PhiTux/DailyTxT) - Encrypted Diary Web-App to save your personal memories of each day. Includes a search-function and encrypted file-upload. `MIT` `Python`
- 🌎 [Databunker](databunker.org/) - Network-based, self-hosted, GDPR compliant, secure database for personal data or PII. ( <b><code>&nbsp;&nbsp;&nbsp;994⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Source Code](https://github.com/securitybunker/databunker)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Digital-Currency](https://github.com/Icesofty/Digital-Currency) - Create your own Self-Hosted Digital Currency.  🌎 [Demo](tonken.glitch.me/)) `GPL-3.0` `Nodejs`
- 🌎 [DomainMOD](domainmod.org) - Application to manage your domains and other internet assets in a central location. DomainMOD includes a Data Warehouse framework that allows you to import your WHM/cPanel web server data so that you can view, export, and report on your data.  🌎 [Demo](demo.domainmod.org),  <b><code>&nbsp;&nbsp;&nbsp;325⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Source Code](https://github.com/domainmod/domainmod)) `GPL-3.0` `PHP`
- 🌎 [Firezone](www.firez.one/) - Open-source VPN server and egress firewall for Linux built on WireGuard that makes it simple to manage secure remote access to your company’s private networks. Firezone is easy to set up, secure, performant, and self-hosted. ( <b><code>&nbsp;&nbsp;2459⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Source Code](https://github.com/firezone/firezone)) `Apache-2.0` `Elixir/Ruby`
-  <b><code>&nbsp;&nbsp;1102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [Flox](https://github.com/devfake/flox) `⚠` - Self hosted movie, TV series and anime watch list with a 3-point rating system. Uses The Movie Database backend for information.  🌎 [Demo](flox-demo.pyxl.dev/)) `MIT` `PHP`
- 🌎 [formspree](formspree.io/) `⚠` - Just send your form to our URL and we'll forward it to your email. No PHP, Javascript or sign up required.  🌎 [Demo](test.formspree.io/),  <b><code>&nbsp;&nbsp;2770⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;247🍴</code></b> [Source Code](https://github.com/formspree/formspree)) `AGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;9806⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;348🍴</code></b> [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - Hassle-Free Way to Self-Host Google Fonts. Get eot, ttf, svg, woff and woff2 files + CSS snippets.  🌎 [Demo](google-webfonts-helper.herokuapp.com/)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [graph-vl](https://github.com/verifid/graph-vl) - Identity document verification using Machine Learning and GraphQL. `MIT` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;181⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Journal](https://github.com/inoda/journal) - Simple journaling with encrypted entries and sharing capabilities. `MIT` `Ruby`
-  <b><code>&nbsp;&nbsp;1769⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;487🍴</code></b> [King Phisher](https://github.com/rsmusllp/king-phisher) - King Phisher is a tool for testing and promoting user awareness by simulating real world phishing attacks. `BSD-3-Clause` `Python`
- 🌎 [Koillection](koillection.github.io/) - Koillection is a service allowing users to manage any kind of collections. ( <b><code>&nbsp;&nbsp;&nbsp;124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Source Code](https://github.com/koillection/koillection)) `MIT` `PHP`
- 🌎 [Lancache](lancache.net) `⚠` - LAN Party game caching made easy. ( <b><code>&nbsp;&nbsp;&nbsp;472⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Source Code](https://github.com/lancachenet/monolithic)) `MIT` `Docker/Shell`
- 🌎 [MailyGo](codeberg.org/jlelse/MailyGo) - MailyGo is a small tool written in Go that allows to send HTML forms, for example from static websites without a dynamic backend, via email. `MIT` `Go`
-  <b><code>&nbsp;&nbsp;8835⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;915🍴</code></b> [MindsDB](https://github.com/mindsdb/mindsdb) - MindsDB is an open source self hosted AI layer for existing databases that allows you to effortlessly develop, train and deploy state-of-the-art machine learning models using standard queries. `GPL-3.0` `Python`
- 🌎 [MissionKontrol](www.missionkontrol.io) - Configurable admin panel allowing non-technical users to CRUD data on MySQL/PostGRES databases. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Source Code](https://github.com/Mission-Kontrol/MissionKontrol-rails)) `AGPL-3.0` `Ruby`
- 🌎 [Monica](monicahq.com/) - Personal relationship manager, and a new kind of CRM to organize interactions with your friends and family. ( <b><code>&nbsp;16853⭐</code></b> <b><code>&nbsp;&nbsp;1708🍴</code></b> [Source Code](https://github.com/monicahq/monica)) `AGPL-3.0` `PHP`
- 🌎 [Musical Artifacts](musical-artifacts.com/) - Helping to catalog, preserve and free the artifacts you need to produce music. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Source Code](https://github.com/lfzawacki/musical-artifacts)) `MIT` `Ruby`
-  <b><code>&nbsp;&nbsp;&nbsp;243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [MyPaas](https://github.com/almarklein/mypaas) - Run your own PaaS using Docker, Traefik, and great monitoring. `BSD-2-Clause` `Python/Docker`
-  <b><code>&nbsp;&nbsp;&nbsp;120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Noisedash](https://github.com/kaythomas0/noisedash) - Self-hostable web tool for generating ambient noises/sounds using audio tools and user-uploadable samples. `AGPL-3.0` `Nodejs`
- 🌎 [Notica](notica.us) - Lets you send browser notifications from your terminal to your desktop or phone. No installation or registration is required. ( <b><code>&nbsp;&nbsp;&nbsp;291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Source Code](https://github.com/tannercollin/Notica)) `MIT` `Nodejs`
- 🌎 [Octave Online](octave-online.net/) - Infrastracture behind a web UI for GNU Octave, the libre alternative to MATLAB. ( <b><code>&nbsp;&nbsp;&nbsp;235⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Source Code](https://github.com/octave-online/octave-online-server)) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Ombi](ombi.io/) - A content request system for Plex/Emby, connects to SickRage, CouchPotato, Sonarr, with a growing feature set.  🌎 [Demo](app.ombi.io/),  <b><code>&nbsp;&nbsp;2968⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;372🍴</code></b> [Source Code](https://github.com/Ombi-app/Ombi)) `GPL-2.0` `C#`
- 🌎 [OpenZiti](openziti.github.io/) - Fully-featured, self-hostable, zero trust, full mesh overlay network. Includes a 2FA support out of the box, clients for all major desktop/mobile OS'es. ( <b><code>&nbsp;&nbsp;&nbsp;327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Source Code](https://github.com/openziti/ziti)) `Apache-2.0` `Go`
- 🌎 [Orchest](www.orchest.io/) - A new kind of IDE for Data Science.  🌎 [Demo](cloud.orchest.io),  <b><code>&nbsp;&nbsp;3110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [Source Code](https://github.com/orchest/orchest)) `AGPL-3.0` `Docker`
-  <b><code>&nbsp;&nbsp;&nbsp;696⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [oTranscribe](https://github.com/oTranscribe/oTranscribe) - Free web app to take the pain out of transcribing recorded interviews.  🌎 [Demo](otranscribe.com/)) `MIT` `Javascript`
- 🌎 [PassCheck](passcheck.anhur.xyz/) - A web application featuring some handy password tools, including a password generator, strength checker and HaveIBeenPwned breach checker. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Source Code](https://github.com/apacketofsweets/PassCheck)) `MIT` `Javascript`
- 🌎 [Reactive Resume](rxresu.me/) - A one-of-a-kind resume builder that keeps your privacy in mind. Completely secure, customizable, portable, open-source and free forever.  🌎 [Demo](rxresu.me/app/dashboard/),  <b><code>&nbsp;&nbsp;7352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;909🍴</code></b> [Source Code](https://github.com/AmruthPillai/Reactive-Resume)) `MIT` `Docker/Nodejs`
- 🌎 [ReleaseBell](releasebell.com/) - Send release notifications for starred Github repos.  🌎 [Source Code](git.cloudron.io/cloudron/releasebell)) `MIT` `Nodejs`
- 🌎 [revealjs](revealjs.com) - Framework for easily creating beautiful presentations using HTML.  🌎 [Demo](revealjs.com/),  <b><code>&nbsp;60686⭐</code></b> <b><code>&nbsp;16242🍴</code></b> [Source Code](https://github.com/hakimel/reveal.js)) `MIT` `Javascript`
- 🌎 [Revive Adserver](www.revive-adserver.com/) - World's most popular free, open source ad serving system. Formerly known as OpenX Adserver and phpAdsNew. ( <b><code>&nbsp;&nbsp;1027⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;527🍴</code></b> [Source Code](https://github.com/revive-adserver/revive-adserver)) `GPL-2.0-or-later` `PHP`
- [SANE Network Scanning](http://sane-project.org/) - Allow remote clients to access image acquisition devices (scanners) available on the local host. ([Source Code](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- 🌎 [Apache Solr](lucene.apache.org/solr/) - Solr is the popular, blazing-fast, open source enterprise search platform built on Apache Lucene.  🌎 [Source Code](lucene.apache.org/solr/downloads.html)) `Apache-2.0` `Java`
- 🌎 [string.is](string.is/) - An open-source, privacy-friendly online string toolkit for developers. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/recurser/string-is)) `AGPL-3.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;2928⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;423🍴</code></b> [TeslaMate](https://github.com/adriankumpf/teslamate) - A powerful data logger for Tesla vehicles. `MIT` `Elixir`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Trello Burndown](https://github.com/mtricht/trello-burndown) `⚠` - Easy to use SCRUM burndown chart for Trello boards. `MIT` `Go/Docker`
- 🌎 [ViMbAdmin](www.vimbadmin.net/) - Provides a web based virtual mailbox administration system to allow mail administrators to easily manage domains, mailboxes and aliases. ( <b><code>&nbsp;&nbsp;&nbsp;455⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [Source Code](https://github.com/opensolutions/ViMbAdmin)) `GPL-3.0` `PHP`
- 🌎 [WeeWX](weewx.com/) - Open source software for your weather station.  🌎 [Demo](weewx.com/showcase.html),  <b><code>&nbsp;&nbsp;&nbsp;804⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;273🍴</code></b> [Source Code](https://github.com/weewx/weewx)) `GPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;1397⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [ytdl-webserver](https://github.com/Algram/ytdl-webserver) - Docker-ready webserver for downloading youtube videos. `MIT` `Nodejs`


### Money, Budgeting & Management

**[`^        back to top        ^`](#)**

_See also:  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [awesome-sysadmin/IT Asset Management](https://github.com/awesome-foss/awesome-sysadmin#it-asset-management)_

- 🌎 [Akaunting](akaunting.com/) - Akaunting is a free, online and open source accounting software designed for small businesses and freelancers. ( <b><code>&nbsp;&nbsp;5364⭐</code></b> <b><code>&nbsp;&nbsp;1868🍴</code></b> [Source Code](https://github.com/akaunting/akaunting)) `GPL-3.0` `PHP`
- 🌎 [BTCPay Server](btcpayserver.org/) - A self-hosted Bitcoin and other cryptocurrencies payment processor.  🌎 [Demo](mainnet.demo.btcpayserver.org/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/btcpayserver/)) `MIT` `C#`
-  <b><code>&nbsp;&nbsp;&nbsp;296⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Budget App](https://github.com/paukiatwee/budgetapp) - Budget App is an open source personal budgeting application. `Apache-2.0` `Java`
-  <b><code>&nbsp;&nbsp;&nbsp;428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [budgetzero](https://github.com/budgetzero/budgetzero) - Free, self-hosted, open-source, envelope-budgeting web and desktop app.  🌎 [Demo](app.budgetzero.io/budget)) `AGPL-3.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;6175⭐</code></b> <b><code>&nbsp;&nbsp;1176🍴</code></b> [Crater](https://github.com/crater-invoice/crater) - Free & Open Source Invoice App for Freelancers & Small Businesses.  🌎 [Demo](demo.craterapp.com/)) `AAL` `PHP`
- 🌎 [Dot Ledger](www.dotledger.com/) - Web-based personal finance management tool.  🌎 [Demo](demo.dotledger.com/),  <b><code>&nbsp;&nbsp;&nbsp;223⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Source Code](https://github.com/dotledger/dotledger)) `Apache-2.0` `Ruby`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [EasyQuickImport](https://github.com/karser/EasyQuickImport) `⚠` - A tool that helps you import transactions, invoices and bills into QuickBooks Desktop from Excel or CSV. `MIT` `PHP`
- 🌎 [Economizzer](www.economizzer.org/) - An easy and secure system for you to manage your personal money and achieve your goals, and can be accessed by computer, tablet or smartphone. ( <b><code>&nbsp;&nbsp;&nbsp;396⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [Demo](https://github.com/gugoan/economizzer#live-demo),  <b><code>&nbsp;&nbsp;&nbsp;396⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [Source Code](https://github.com/gugoan/economizzer)) `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [ExMoney](https://github.com/gaynetdinov/ex_money) - Self-hosted personal finance app. `ISC` `Elixir`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Family Accounting Tool](https://github.com/nymanjens/facto) - Web-based finance management tool for partners with partially shared expenses. `Apache-2.0` `Scala`
- 🌎 [Fava](beancount.github.io/fava/) - Fava is the web frontend of Beancount, a text based double-entry accounting system.  🌎 [Demo](fava.pythonanywhere.com/example-with-budgets/income_statement/),  <b><code>&nbsp;&nbsp;1324⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [Source Code](https://github.com/beancount/fava)) `MIT` `Python`
- 🌎 [Firefly III](firefly-iii.org/) - Firefly III is a modern financial manager. It helps you to keep track of your money and make budget forecasts. It supports credit cards, has an advanced rule engine and can import data from many banks.  🌎 [Demo](demo.firefly-iii.org/),  <b><code>&nbsp;&nbsp;8498⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;897🍴</code></b> [Source Code](https://github.com/firefly-iii/firefly-iii)) `AGPL-3.0` `PHP`
- 🌎 [Galette](galette.eu/dc/) - Galette is a membership management web application towards non profit organizations.  🌎 [Source Code](git.tuxfamily.org/galette/galette.git/)) `GPL-3.0` `PHP`
- 🌎 [Ghostfolio](ghostfol.io/) - Wealth management software to keep track of stocks, ETFs and cryptocurrencies. ( <b><code>&nbsp;&nbsp;&nbsp;498⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Source Code](https://github.com/ghostfolio/ghostfolio)) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [GRR](grr.devome.com/?lang=en) - Assets management and booking for small/medium companies. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Source Code](https://github.com/JeromeDevome/GRR)) `GPL-2.0` `PHP`
- 🌎 [Hospital Run](hospitalrun.io/) - Hospital Run is offline enabled hospital management software.  🌎 [Demo](hospitalrun.io/demo/),  <b><code>&nbsp;&nbsp;&nbsp;822⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;543🍴</code></b> [Source Code](https://github.com/HospitalRun/hospitalrun-server)) `GPL-3.0` `Nodejs`
- 🌎 [Hub20](hub20.io/) - A self-hosted payment processor for Ethereum and ERC20 Tokens.  🌎 [Source Code](gitlab.com/mushroomlabs/hub20/)) `AGPL-3.0` `Docker/Python`
- 🌎 [IHateMoney](ihatemoney.org/) - Manage your shared expenses, easily.  🌎 [Demo](ihatemoney.org/demo/),  <b><code>&nbsp;&nbsp;&nbsp;757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;205🍴</code></b> [Source Code](https://github.com/spiral-project/ihatemoney)) `BSD-3-Clause` `Docker/Python`
-  <b><code>&nbsp;&nbsp;&nbsp;108⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [IHateToBudget](https://github.com/bminusl/ihatetobudget) - A simple web app to understand and control your expenses. `GPL-3.0` `Docker/Python`
- 🌎 [Inventaire](inventaire.io/welcome) - Collaborative resources mapper project, while yet only focused on exploring books mapping with wikidata and ISBNs. ( <b><code>&nbsp;&nbsp;&nbsp;346⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Source Code](https://github.com/inventaire/inventaire)) `AGPL-3.0` `Nodejs`
- 🌎 [Inventree](inventree.readthedocs.io/en/latest/) - InvenTree is an open-source inventory management system which provides intuitive parts management and stock control. ( <b><code>&nbsp;&nbsp;1969⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;277🍴</code></b> [Source Code](https://github.com/inventree/InvenTree)) `MIT` `Python`
- 🌎 [Invoice Ninja](www.invoiceninja.org/) - Powerful tool to invoice clients online.  🌎 [Demo](app.invoiceninja.com/invoices/create),  <b><code>&nbsp;&nbsp;6555⭐</code></b> <b><code>&nbsp;&nbsp;1968🍴</code></b> [Source Code](https://github.com/invoiceninja/invoiceninja)) `AAL` `PHP`
-  <b><code>&nbsp;&nbsp;2030⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;707🍴</code></b> [InvoicePlane](https://github.com/InvoicePlane/InvoicePlane) - Manage quotes, invoices, payments and customers for your small business. `MIT` `PHP`
- 🌎 [Kresus](kresus.org/) - Open source personal finance manager.  🌎 [Demo](kresus.org/en/demo.html),  <b><code>&nbsp;&nbsp;&nbsp;232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Source Code](https://github.com/kresusapp/kresus)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;567⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [OnTrack](https://github.com/inoda/ontrack) - A simple app to track spend and set goals. `MIT` `Ruby/React`
- 🌎 [PartKeepr](www.partkeepr.org) - PartKeepr is an electronic part inventory management software. It helps you to keep track of your available parts and assist you with re-ordering parts.  🌎 [Demo](demo.partkeepr.org/),  <b><code>&nbsp;&nbsp;1068⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;364🍴</code></b> [Source Code](https://github.com/partkeepr/PartKeepr)) `GPL-3.0` `PHP`
- 🌎 [REI3](rei3.de/home_en/) - Open source, expandable Business Management Software. Manage tasks, time, assets and much more.  🌎 [Demo](rei3.de/demo_en/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Source Code](https://github.com/r3-team/r3)) `MIT` `Go`
- 🌎 [SilverStrike](silverstrike.org/) - Personal finance management made easy.  🌎 [Demo](demo.silverstrike.org/),  <b><code>&nbsp;&nbsp;&nbsp;306⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [Source Code](https://github.com/agstrike/silverstrike)) `MIT` `Python/Django`
- 🌎 [StockazNG](dev.sigpipe.me/dashie/StockazNG) - Asset Management System. `MIT` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Tabby](https://github.com/bertvandepoel/tabby) - A tool to manage shared expenses across friends, such as restaurant costs or food delivery, without requiring everyone to create an account. Includes email reminders and tracks who has (re)paid what. `AGPL-3.0-only` `PHP`


### Monitoring

**[`^        back to top        ^`](#)**

**Please visit  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [awesome-sysadmin/Monitoring](https://github.com/awesome-foss/awesome-sysadmin#monitoring),  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [awesome-sysadmin/Metric and Metric Collection](https://github.com/awesome-foss/awesome-sysadmin#metric--metric-collection)**


### Note-taking & Editors

**[`^        back to top        ^`](#)**

_Related: [Wikis](#wikis)_

- 🌎 [BulletNotes](bulletnotes.io/) - Workflowy / Dynalist clone with Kanban (Trello) and Calendar functionality. Organize everything.  🌎 [Source Code](gitlab.com/NickBusey/BulletNotes)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;516⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [DailyNotes](https://github.com/m0ngr31/DailyNotes) - App for taking notes and tracking tasks on a daily basis in Markdown. `MIT` `Python`
- 🌎 [dillinger](dillinger.io/) - The last Markdown editor, ever. ( <b><code>&nbsp;&nbsp;7418⭐</code></b> <b><code>&nbsp;&nbsp;1078🍴</code></b> [Source Code](https://github.com/joemccann/dillinger)) `MIT` `Nodejs`
- 🌎 [Dnote](www.getdnote.com) - A simple command line notebook with multi-device sync and web interface. ( <b><code>&nbsp;&nbsp;2328⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [Source Code](https://github.com/dnote/dnote)) `AGPL-3.0` `Go`
- 🌎 [DocPHT](docpht.org/) - With DocPHT you can take notes and quickly document anything and without the use of any database.  🌎 [Demo](demo.docpht.org/),  <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Source Code](https://github.com/docpht/docpht)) `MIT` `PHP`
- 🌎 [draw.io](draw.io) - Diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams. ( <b><code>&nbsp;30435⭐</code></b> <b><code>&nbsp;&nbsp;6123🍴</code></b> [Source Code](https://github.com/jgraph/drawio)) `Apache-2.0` `Javascript`
- 🌎 [HedgeDoc](demo.hedgedoc.org/) - Realtime collaborative markdown notes on all platforms, formerly known as CodiMD and HackMD CE. ( <b><code>&nbsp;&nbsp;3052⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;264🍴</code></b> [Source Code](https://github.com/hedgedoc/hedgedoc)) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Joplin](joplinapp.org/) - Joplin is a note taking application with Markdown editor and encryption support for mobile and desktop platforms. Runs client-side and syncs through self hosted Nextcloud or similar. Consider it like open source alternative to Evernote. ( <b><code>&nbsp;30840⭐</code></b> <b><code>&nbsp;&nbsp;3488🍴</code></b> [Source Code](https://github.com/laurent22/joplin)) `MIT` `Nodejs`
- [Leanote](http://leanote.org/) - Leanote, Not Just A Notepad! Open source cloud notepad.  🌎 [Demo](leanote.com/note),  <b><code>&nbsp;10933⭐</code></b> <b><code>&nbsp;&nbsp;2409🍴</code></b> [Source Code](https://github.com/leanote/leanote)) `GPL-2.0` `Go`
- 🌎 [Livebook](livebook.dev) - Realtime collaborative notebook app based on Markdown that supports running Elixir codesnippets, TeX and Mermaid Diagrams. Easily deployed using Docker or Elixir. ( <b><code>&nbsp;&nbsp;2798⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;229🍴</code></b> [Source Code](https://github.com/livebook-dev/livebook)) `Apache-2.0` `Elixir`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Markdown Edit](https://github.com/georgeOsdDev/markdown-edit/) - Online markdown editor/viewer. `MIT` `HTML5`
- 🌎 [Meemo](meemo.minimal-space.de/) - Personal notes stream with Markdown support. ( <b><code>&nbsp;&nbsp;&nbsp;287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Source Code](https://github.com/nebulade/meemo)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;664⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;205🍴</code></b> [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad) - Minimalist notepad.cc clone.  🌎 [Demo](notes.orga.cat/)) `Apache-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [MiniNote](https://github.com/muety/mininote) - Simple Markdown note-taking app with persistence. `MIT` `Nodejs`
- 🌎 [Notea](cinwell.com/notea/) - Self-hosted note-taking app stored on S3-compatible storage. ( <b><code>&nbsp;&nbsp;1462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;244🍴</code></b> [Source Code](https://github.com/QingWei-Li/notea)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Notes'n'Todos](https://github.com/larspontoppidan/notesntodos) - Write notes and todos online in markdown with tag filtering and date sorting.  🌎 [Demo](lpss.dk/nnt-playground/)) `MIT` `Python`
- 🌎 [Oddmuse](oddmuse.org/) - A simple wiki engine written in Perl. No database required. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Source Code](https://github.com/kensanata/oddmuse)) `GPL-3.0` `Perl`
-  <b><code>&nbsp;&nbsp;1530⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [OpenNote](https://github.com/FoxUSA/OpenNote) - OpenNote was built to be an open web-based alternative to Microsoft OneNote (T) and EverNote.  🌎 [Demo](foxusa.github.io/OpenNote/OpenNote/#/folder)) `MIT` `HTML5`
- 🌎 [Overleaf](www.overleaf.com/) - Web-based collaborative LaTeX editor. ( <b><code>&nbsp;10073⭐</code></b> <b><code>&nbsp;&nbsp;1100🍴</code></b> [Source Code](https://github.com/overleaf/overleaf)) `AGPL-3.0` `Ruby`
- 🌎 [Plainpad](alextselegidis.com/get/plainpad/) - A modern note taking application for the cloud, utilizing the best features of progressive web apps technology.  🌎 [Demo](alextselegidis.com/try/plainpad/),  <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Source Code](https://github.com/alextselegidis/plainpad)) `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [savepad](https://github.com/shelltr/textpad) - Minimalist notepad based on notepad.cc. `MIT` `PHP`
- 🌎 [Standard Notes](standardnotes.com) - Simple and private notes app. Protect your privacy while getting more done. That's Standard Notes.  🌎 [Demo](app.standardnotes.org/),  <b><code>&nbsp;&nbsp;3465⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;285🍴</code></b> [Source Code](https://github.com/standardnotes/app)) `GPL-3.0` `Ruby`
-  <b><code>&nbsp;16800⭐</code></b> <b><code>&nbsp;&nbsp;1085🍴</code></b> [Trilium Notes](https://github.com/zadam/trilium) - Trilium Notes is a hierarchical note taking application with focus on building large personal knowledge bases. `AGPL-3.0` `Nodejs`
- 🌎 [turndown](mixmark-io.github.io/turndown/) - HTML to Markdown converter written in Javascript. ( <b><code>&nbsp;&nbsp;6294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;736🍴</code></b> [Source Code](https://github.com/mixmark-io/turndown)) `MIT` `Javascript`
- 🌎 [Turtl](turtl.it/) - Totally private personal database and note taking app. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- 🌎 [Wreeto](wreeto.com) - Wreeto is an open source note-taking, knowledge management and wiki system built on top of Ruby on Rails framework. ( <b><code>&nbsp;&nbsp;&nbsp;361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Source Code](https://github.com/chrisvel/wreeto_official)) `AGPL-3.0` `Ruby`
- 🌎 [Writing](josephernest.github.io/writing/) - Lightweight distraction-free text editor, in the browser (Markdown and LaTeX supported). No lag when writing. ( <b><code>&nbsp;&nbsp;&nbsp;968⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [Source Code](https://github.com/josephernest/writing)) `MIT` `Javascript`


### Office Suites

**[`^        back to top        ^`](#)**

- 🌎 [Collabora Online Development Edition](www.collaboraoffice.com/code) - Collabora Online Development Edition (CODE) is a powerful LibreOffice-based online office that supports all major document, spreadsheet and presentation file formats, which you can integrate in your own infrastructure.  🌎 [Source Code](cgit.freedesktop.org/libreoffice/online/)) `MPL-2.0` `C++`
- 🌎 [CryptPad](cryptpad.fr/) - CryptPad is the zero knowledge realtime collaborative editor (rich-text, files, source-code, ...). ( <b><code>&nbsp;&nbsp;3782⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;416🍴</code></b> [Source Code](https://github.com/xwiki-labs/cryptpad)) `AGPL-3.0` `Nodejs`
- 🌎 [EtherCalc](ethercalc.net/) - Web spreadsheet. ( <b><code>&nbsp;&nbsp;2791⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;505🍴</code></b> [Source Code](https://github.com/audreyt/ethercalc)) `CPAL-1.0/Other` `Nodejs`
- 🌎 [Etherpad](etherpad.org/) - Etherpad is a highly customizable Open Source online editor providing collaborative editing in really real-time.  🌎 [Demo](demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60),  <b><code>&nbsp;12989⭐</code></b> <b><code>&nbsp;&nbsp;2423🍴</code></b> [Source Code](https://github.com/ether/etherpad-lite)) `Apache-2.0` `Nodejs`
- 🌎 [Grist](getgrist.com/) - Grist is a next-generation spreadsheet with relational structure, formula-based access control, and a portable, self-contained format. Alternative to Airtable.  🌎 [Demo](docs.getgrist.com),  <b><code>&nbsp;&nbsp;3175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [Source Code](https://github.com/gristlabs/grist-core)) `Apache-2.0` `Nodejs/Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Infinoted](https://github.com/gobby/gobby/wiki/Dedicated%20Server) - Server for  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Gobby](https://github.com/gobby/gobby/wiki), a multi-platform collaborative text editor. ( <b><code>&nbsp;&nbsp;&nbsp;537⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [Source Code](https://github.com/gobby/gobby)) `MIT` `C++`
- 🌎 [ONLYOFFICE](helpcenter.onlyoffice.com/faq/server-opensource.aspx) - Office suite that enables you to manage documents, projects, team and customer relations in one place. ( <b><code>&nbsp;&nbsp;2708⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;786🍴</code></b> [Source Code](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [PHPOffice](https://github.com/PHPOffice) - PHPOffice contains libraries which permits to write and read files from most office suites. `LGPL-3.0` `PHP`
- 🌎 [Rustpad](rustpad.io/) - Efficient and minimal collaborative code editor, self-hosted, no database required. ( <b><code>&nbsp;&nbsp;2242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Source Code](https://github.com/ekzhang/rustpad)) `MIT` `Rust`
- 🌎 [WebODF](webodf.org/) - Tools and libraries to view and edit Open Document Format (ODF) files. ( <b><code>&nbsp;&nbsp;&nbsp;764⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [Source Code](https://github.com/webodf/WebODF)) `AGPL-3.0` `HTML5`


### Password Managers

**[`^        back to top        ^`](#)**

- 🌎 [Bitwarden](bitwarden.com/) `⚠` - Password manager with webapp, browser extension, and mobile app. ( <b><code>&nbsp;10122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;868🍴</code></b> [Source Code](https://github.com/bitwarden/server)) `AGPL-3.0` `C#`
- 🌎 [keeweb](keeweb.info/) - This webapp is a browser and desktop password manager compatible with KeePass databases. ( <b><code>&nbsp;11056⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;986🍴</code></b> [Source Code](https://github.com/keeweb/keeweb)) `MIT` `HTML5`
- 🌎 [Padloc](padloc.app/) - A modern, open source password manager for individuals and teams. ( <b><code>&nbsp;&nbsp;1201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [Source Code](https://github.com/padloc/padloc)) `GPL-3.0` `Nodejs`
- 🌎 [Passbolt](www.passbolt.com/) - Password manager dedicated for managing passwords in a collaborative way on any Web server, using a MySQL database backend. ( <b><code>&nbsp;&nbsp;3048⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [Source Code](https://github.com/passbolt/passbolt_api)) `AGPL-3.0` `PHP`
- 🌎 [PassIt](passit.io/) - Simple password manage with sharing features by group and user, but no administration interface.  🌎 [Demo](app.passit.io/), 🌎 [Source Code](gitlab.com/passit)) `AGPL-3.0` `Python`
- 🌎 [Passky](passky.org) - Simple, modern and open source password manager with website, browser extension, android and desktop application.  🌎 [Demo](vault.passky.org),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Source Code](https://github.com/Rabbit-Company/Passky-Server)) `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;652⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [PassWall](https://github.com/passwall/passwall-server) - Open source password manager. `AGPL-3.0` `Go`
- 🌎 [Psono](psono.com/) - A promising password managers fully featured for teams.  🌎 [Demo](www.psono.pw), 🌎 [Source Code](gitlab.com/psono)) `Apache-2.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;438⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Shaark](https://github.com/MarceauKa/shaark) - All in one platform for your links, stories, passwords and albums. Built with Laravel and Vue.js. `MIT` `PHP`
- 🌎 [sysPass](www.syspass.org/) - Multiuser password management system.  🌎 [Demo](demo.syspass.org/),  <b><code>&nbsp;&nbsp;&nbsp;869⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [Source Code](https://github.com/nuxsmin/sysPass)) `GPL-3.0` `PHP`
- 🌎 [Teampass](teampass.net/) - Password manager dedicated for managing passwords in a collaborative way. One symmetric key is used to encrypt all shared/team passwords and stored server side in a file and the database. works on any server Apache, MySQL and PHP. ( <b><code>&nbsp;&nbsp;1423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;480🍴</code></b> [Source Code](https://github.com/nilsteampassnet/TeamPass)) `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [vaults](https://github.com/MatrixEternal/vaults) - Password manager featuring client side AES-256 encryption, PBKDF2 hashing, vaults, password generation & more. `GPL-3.0` `PHP`
-  <b><code>&nbsp;17369⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;934🍴</code></b> [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - Lightweight Bitwarden server API implementation written in Rust. `GPL-3.0` `Rust`


### Pastebins

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;1239⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;207🍴</code></b> [0bin](https://github.com/Tygs/0bin) - Client side encrypted pastebin.  🌎 [Demo](0bin.net/)) `WTFPL` `Python`
- 🌎 [bepasty](bepasty-server.readthedocs.io/en/latest/) - A pastebin for all kinds of files. ( <b><code>&nbsp;&nbsp;&nbsp;135⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Source Code](https://github.com/bepasty/bepasty-server)) `BSD-2-Clause` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [bin](https://github.com/w4/bin) - A paste bin that's actually minimalist. `WTFPL/0BSD` `Rust`
- 🌎 [cryptonote](cryptonote.me/) - Simple open source web application that lets users encrypt and share messages that can only be read once. ( <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Source Code](https://github.com/alainmeier/cryptonote)) `MIT` `Ruby`
-  <b><code>&nbsp;&nbsp;&nbsp;326⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [dogbin](https://github.com/dogbin/dogbin) - The sexiest pastebin and URL shortener ever. `MIT` `Kotlin`
- 🌎 [dpaste](dpaste.org/) - Simple pastebin with multiple text and code option, with short url result easy to remember. ( <b><code>&nbsp;&nbsp;&nbsp;393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Source Code](https://github.com/bartTC/dpaste)) `MIT` `Docker`
-  <b><code>&nbsp;&nbsp;&nbsp;801⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Drift](https://github.com/MaxLeiter/drift) - Self-hosted Github Gist clone.  🌎 [Demo](drift.maxleiter.com/)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [EdPaste](https://github.com/ptnr/EdPaste) - Self-hosted pastebin written in Laravel (PHP Framework). `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [ExBin](https://github.com/m1dnight/exbin) - A pastebin with public/private snippets and netcat server. `MIT` `Elixir`
-  <b><code>&nbsp;&nbsp;1155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [fiche](https://github.com/solusipse/fiche) - Command line pastebin, all you need is netcat.  🌎 [Demo](termbin.com/)) `MIT` `C`
-  <b><code>&nbsp;&nbsp;&nbsp;176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [filite](https://github.com/raftario/filite) - A simple, light and standalone pastebin, URL shortener and file-sharing service. `MIT` `Rust`
-  <b><code>&nbsp;&nbsp;&nbsp;106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [FlashPaper](https://github.com/AndrewPaglusch/FlashPaper) - A one-time encrypted zero-knowledge password/secret sharing application focused on simplicity and security. No database or complicated set-up required.  🌎 [Demo](flashpaper.io)) `MIT` `PHP`
- 🌎 [Hastebin](haste.zneix.eu/about.md) - Open source pastebin. (This is a fork with extended maintenance).  🌎 [Demo](haste.zneix.eu),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Source Code](https://github.com/zneix/haste-server)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;231⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [LogPaste](https://github.com/mtlynch/logpaste) - Minimal pastebin web app that's easy to self-host and persists data to any S3-compatible backend.  🌎 [Demo](logpaste.com/)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [MicroBin](https://github.com/szabodanika/microbin) - Simple, performant, configurable, entirely self-contained pastebin and URL shortener. `BSD-3-Clause` `Rust`
-  <b><code>&nbsp;&nbsp;&nbsp;118⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [mkaczanowski pastebin](https://github.com/mkaczanowski/pastebin) - Simple, fast, feature-rich, standalone pastebin service. `MIT` `Rust`
- 🌎 [mojopaste](metacpan.org/dist/App-mojopaste) - Perl based pastebin.  🌎 [Demo](p.thorsen.pm/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Source Code](https://github.com/jhthorsen/app-mojopaste)) `Artistic-2.0` `Perl`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [MokinToken](https://github.com/nexus-uw/mokintoken) - Clientside encrypted pastebin using tweetnacl. `Unlicense` `PHP`
- 🌎 [paaster](paaster.io) - Paaster is a secure by default end-to-end encrypted pastebin built with the objective of simplicity. ( <b><code>&nbsp;&nbsp;&nbsp;198⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Source Code](https://github.com/WardPearce/paaster)) `GPL-3.0` `Docker`
- 🌎 [Paste](phpaste.sourceforge.io/) - Paste is forked from the original source pastebin.com used before it was bought. ( <b><code>&nbsp;&nbsp;&nbsp;262⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [Source Code](https://github.com/jordansamuel/PASTE)) `GPL-3.0` `PHP`
- 🌎 [Pastefy](pastefy.ga) - Beautiful, simple and easy to deploy Pastebin with optional Client-Encryption, Multitab-Pastes, an API, a highlighted Editor and more. ( <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Source Code](https://github.com/interaapps/pastefy),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Clients](https://github.com/topics/pastefy-addon)) `MIT` `Java`
- 🌎 [Pastila](pastila.nl/) - Minimalistic paste service. Single page, zero click experience. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Source Code](https://github.com/ClickHouse/pastila)) `Apache-2.0` `SQL`
-  <b><code>&nbsp;&nbsp;&nbsp;123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [pasty](https://github.com/lus/pasty) - Pasty is a fast and lightweight code pasting server.  🌎 [Demo](pasty.lus.pm/)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;505⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [pb](https://github.com/ptpb/pb) - Lightweight pastebin (and url shortener) built using flask. `GPL-3.0` `Python`
- 🌎 [PrivateBin](privatebin.info/) - PrivateBin is a minimalist, opensource online pastebin/discussion board where the server has zero knowledge of hosted data.  🌎 [Demo](privatebin.net/),  <b><code>&nbsp;&nbsp;4186⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;579🍴</code></b> [Source Code](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
- 🌎 [prologic pastebin](git.mills.io/prologic/pastebin) - Simple pastebin service with convenient api and CLI.  🌎 [Demo](paste.mills.io)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [PurritoBin](https://github.com/PurritoBin/PurritoBin) - Ultra fast, minimalistic, encrypted command line paste-bin, where the server has no knowledge of the paste data. `ISC` `C++`
-  <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [rustypaste](https://github.com/orhun/rustypaste) - A minimal file upload/pastebin service. `MIT` `Rust`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [SharpPaste](https://github.com/phonicmouse/SharpPaste) - Cross-platform C# pastebin with client-side AES-256 encryption that just works. `MIT` `C#/NancyFX`
- 🌎 [Snibox](snibox.github.io/) - Code snippets manager with attractive tag-oriented interface.  🌎 [Demo](snibox-demo.herokuapp.com/),  <b><code>&nbsp;&nbsp;1458⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [Source Code](https://github.com/snibox/snibox)) `MIT` `Ruby`
-  <b><code>&nbsp;&nbsp;&nbsp;555⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Snippet Box](https://github.com/pawelmalak/snippet-box) - Snippet Box is a simple self-hosted app for organizing your code snippets. It allows you to easily create, edit, browse and manage your snippets in various languages. `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [snipt](https://github.com/nicksergeant/snipt) - Long-term memory for coders. Share and store code snippets. `MIT` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [SocksBin](https://github.com/magnumdingusedu/socksbin) - Simple and fast terminal based pastebin, with optional code highlighting. No specific client required, all you need is netcat. `GPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Spacebin](https://github.com/spacebin-org/spirit) - Text-sharing for the final frontier — Reliable Pastebin server in Golang and Fiber. `Apache-2.0` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;941⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [Stikked](https://github.com/claudehohl/Stikked) - Advanced and beautiful pastebin. `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - Very simple (to deploy and to use) secret message service using Hashicorp Vault as a secrets storage. `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [wantguns/bin](https://github.com/wantguns/bin) - Minimal pastebin for both textual and binary files shipped in a single statically linked binary.  🌎 [Demo](basedbin.fly.dev)) `GPL-3.0` `Rust`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Wastebin](https://github.com/matze/wastebin) - Lightweight, minimal and fast pastebin with an SQLite backend. `MIT` `Rust`


### Personal Dashboards

**[`^        back to top        ^`](#)**

_Related: [Monitoring](#monitoring)_

-  <b><code>&nbsp;&nbsp;1399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;168🍴</code></b> [Baby Buddy](https://github.com/babybuddy/babybuddy) - Helps caregivers track baby sleep, feedings, diaper changes, and tummy time.  🌎 [Demo](demo.baby-buddy.net/login/?next=/)) `BSD-2-Clause` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;619⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Dashboard](https://github.com/phntxx/dashboard) - Minimalist homepage for organizing your web applications and bookmarks using JSON-files. `MIT` `Nodejs/Docker`
-  <b><code>&nbsp;&nbsp;&nbsp;519⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [dashdot](https://github.com/MauriceNino/dashdot) - A simple, modern server dashboard for smaller private servers.  🌎 [Demo](dash.mauz.io)) `MIT` `Nodejs/Docker`
-  <b><code>&nbsp;&nbsp;1094⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [DashMachine](https://github.com/rmountjoy92/DashMachine) - Another web application bookmark dashboard, with fun features. `GPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;6762⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;394🍴</code></b> [Dashy](https://github.com/lissy93/dashy) - Feature-rich homepage for your homelab, with easy YAML configuration.  🌎 [Demo](demo.dashy.to/)) `MIT` `Nodejs/Docker`
-  <b><code>&nbsp;&nbsp;&nbsp;105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Fenrus](https://github.com/revenz/fenrus) - A self hosted personal home page that allows for multiple users, guest access and multiple dashboards for each user. It also has "Smart Apps" which display live data for those apps. `GPL-3.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;2663⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [Flame](https://github.com/pawelmalak/flame) - Flame is self-hosted startpage for your server. Easily manage your apps and bookmarks with built-in editors. `MIT` `Nodejs`
- 🌎 [Habitica](habitica.com/) - Habit tracker app which treats your goals like a Role Playing Game. Previously called HabitRPG. ( <b><code>&nbsp;&nbsp;9180⭐</code></b> <b><code>&nbsp;&nbsp;3492🍴</code></b> [Source Code](https://github.com/HabitRPG/habitica)) `GPL-3.0/CC-BY-NC-SA-3.0/CC-BY-SA-3.0` `Nodejs`
- 🌎 [Heimdall](heimdall.site/) - Heimdall is an elegant solution to organise all your web applications. ( <b><code>&nbsp;&nbsp;4530⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;409🍴</code></b> [Source Code](https://github.com/linuxserver/Heimdall)) `MIT` `PHP`
- 🌎 [Hiccup](designedbyashw.in/test/hiccup/) - A beautiful static homepage to get to your links and services quickly. It has built-in search, editing, PWA support and localstorage caching to easily organize your start page. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Source Code](https://github.com/ashwin-pc/hiccup)) `MIT` `HTML5`
-  <b><code>&nbsp;&nbsp;&nbsp;271⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Homepage](https://github.com/tomershvueli/homepage) - Simple, standalone, self-hosted PHP page that is your window to your server and the web. `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;5347⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;501🍴</code></b> [Homer](https://github.com/bastienwirtz/homer) - A dead simple static homepage to expose your server services, with an easy yaml configuration and connectivity check. `Apache-2.0` `HTML5`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Jmz HomeProxy](https://github.com/jmztaylor/homelab_proxy) - A simple and clean dashboard for self hosted services. `GPL-3.0` `PHP`
- 🌎 [LinkPage](links.zrd.sh) - LinkPage is a FOSS self-hosted alternative to link listing websites such as LinkTree and Campsite.bio. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Source Code](https://github.com/rhnvrm/linkpage)) `BSD-2-Clause` `Go`
- 🌎 [LittleLink Custom](littlelink-custom.com/) - Open-source, customizable, self-hosted alternative to services like Linktree and Manylink with an intuitive, easy to use user/admin interface. LittleLink Custom allows you to link all your social media platforms easily accessible on one page.  🌎 [Demo](demo.littlelink-custom.com/),  <b><code>&nbsp;&nbsp;&nbsp;214⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Source Code](https://github.com/JulianPrieber/littlelink-custom)) `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Newtelco Tab](https://github.com/ndom91/newtelco-tab) - Beautiful dashboard and new tab launcher with support for App Shortcuts as well as GDrive, Contacts, and notes.  🌎 [Demo](portal.newtelco.de/)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;3912⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;274🍴</code></b> [Organizr](https://github.com/causefx/Organizr) - Organizr aims to be your one stop shop for your Servers Frontend. `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;2391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;187🍴</code></b> [Personal management system](https://github.com/Volmarg/personal-management-system) - Central point for managing personal data (billings, payments, job holidays, notes etc.). ([Demo](http://personal-management-system.pl/)) `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [simple-dash](https://github.com/kutyla-philipp/simple-dash) - A simple, fully responsive Dashboard to forward to the services of your choice.  🌎 [Demo](kutyla-philipp.github.io/simple-dash/)) `MIT` `Javascript`
- 🌎 [Smashing](smashing.github.io/) - Smashing, the spiritual successor to Dashing, is a Sinatra based framework that lets you build excellent dashboards. It looks especially great on TVs. ( <b><code>&nbsp;&nbsp;2877⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;323🍴</code></b> [Source Code](https://github.com/Smashing/smashing)) `MIT` `Ruby`
- 🌎 [wger](wger.de/) - Web-based personal workout, fitness and weight logger/tracker. It can also be used as a simple gym management utility and offers a full REST API as well.  🌎 [Demo](wger.de/en/dashboard),  <b><code>&nbsp;&nbsp;1841⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;423🍴</code></b> [Source Code](https://github.com/wger-project/wger)) `AGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;725⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Your Spotify](https://github.com/Yooooomi/your_spotify) `⚠` - Allows you to record your Spotify listening activity and have statistics about them served through a Web application. `MIT` `Nodejs/Docker`


### Photo and Video Galleries

**[`^        back to top        ^`](#)**

- 🌎 [Chevereto Free](chevereto.com/free) - Powerful and fast image hosting script that allows you to create your very own full featured image hosting website in just minutes. ( <b><code>&nbsp;&nbsp;2570⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;458🍴</code></b> [Source Code](https://github.com/Chevereto/Chevereto-Free)) `AGPL-3.0` `PHP`
- 🌎 [Coppermine](coppermine-gallery.net/) - Multilingual photo gallery that integrates with various bulletin boards. Includes upload approval and password protected albums.  🌎 [Demo](coppermine-gallery.net/demo/cpg15x/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Source Code](https://github.com/coppermine-gallery/cpg1.6.x)) `GPL-3.0` `PHP`
- 🌎 [Damselfly](damselfly.info) - Fast server-based photo management system for large collections of images. Includes face detection, face & object recognition, powerful search, and EXIF Keyword tagging. Runs on Linux, MacOS and Windows. `GPL-3.0` `C#/.NET`
-  <b><code>&nbsp;&nbsp;&nbsp;133⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Fussel](https://github.com/cbenning/fussel) - Fussel is a static photo gallery generator. Easily generate a reactive gallery and host the optimized static folder of assets. `MIT` `Python`
- 🌎 [Gallery CSS](benschwarz.github.io/gallery-css/) - Gallery.css is all CSS. Think: Simple, maintainable and understandable galleries without the use of Javascript. ( <b><code>&nbsp;&nbsp;1129⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;310🍴</code></b> [Source Code](https://github.com/benschwarz/gallery-css)) `MIT` `CSS`
- 🌎 [HomeGallery](home-gallery.org) - Self-hosted open-source web gallery to browse personal photos and videos featuring tagging, mobile-friendly, and AI powered image discovery.  🌎 [Demo](demo.home-gallery.org),  <b><code>&nbsp;&nbsp;&nbsp;197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Source Code](https://github.com/xemle/home-gallery)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;596⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [ImageStore](https://github.com/gregordr/ImageStore) - Self-hosted Google Photos alternative, with a very similar UI.  🌎 [Demo](gregordr.github.io/ImageStore/)) `Apache-2.0` `Nodejs/Docker`
-  <b><code>&nbsp;&nbsp;2113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [Immich](https://github.com/alextran1502/immich) - Self-hosted photo and video backup solution directly from your mobile phone. `MIT` `Docker`
-  <b><code>&nbsp;&nbsp;4261⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [LibrePhotos](https://github.com/LibrePhotos/librephotos) - Self hosted wannabe Google Photos clone, with a slight focus on cool graphs. `MIT` `Python`
- 🌎 [Lychee](lycheeorg.github.io/) - Open source grid and album based photo-management-system. ( <b><code>&nbsp;&nbsp;1652⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [Source Code](https://github.com/LycheeOrg/Lychee)) `MIT` `PHP`
- 🌎 [Mediagoblin](mediagoblin.org) - Free software media publishing platform that anyone can run. You can think of it as a decentralized alternative to Flickr, YouTube, SoundCloud, etc.  🌎 [Source Code](savannah.gnu.org/projects/mediagoblin)) `AGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [MediaHut](https://github.com/Fortyseven/MediaHut/) - A truly single-file, no-database, drop-in PHP media gallery.  🌎 [Demo](media.Network47.org/)) `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Mejiro](https://github.com/dmpop/mejiro) - An easy-to-use PHP web application for instant photo publishing. `GPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Photato](https://github.com/trebonius0/Photato) - Self-hosted photo gallery, accessible through a responsive WebUI. Directly uses and indexes a specific folder in the filesystem. `AGPL-3.0` `Java`
-  <b><code>&nbsp;&nbsp;&nbsp;203⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Photo Stream](https://github.com/waschinski/photo-stream) - Minimalist self-hosted photo stream.  🌎 [Demo](floremotion.de/)) `MIT` `Ruby`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [PhotoLight](https://github.com/thibaud-rohmer/PhotoLight) - The easiest photo gallery there is. `GPL-3.0` `PHP`
- 🌎 [Photonix](photonix.org/) - A new web-based photo management application with object recognition, location awareness, color analysis and other ML algorithms.  🌎 [Demo](demo.photonix.org/),  <b><code>&nbsp;&nbsp;1343⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Source Code](https://github.com/photonixapp/photonix)) `AGPL-3.0` `Python`
- 🌎 [PhotoPrism](photoprism.org) - Personal photo management powered by Go and Google TensorFlow.  Browse, organize, and share your personal photo collection, using the latest technologies to automatically tag and find pictures. ( <b><code>&nbsp;21491⭐</code></b> <b><code>&nbsp;&nbsp;1189🍴</code></b> [Source Code](https://github.com/photoprism/photoprism)) `MIT` `Go`
- 🌎 [Photoview](photoview.github.io/) - A simple and user-friendly Photo Gallery for personal servers. It is made for photographers and aims to provide an easy and fast way to navigate directories, with thousands of high resolution photos.  🌎 [Demo](photos.qpqp.dk/),  <b><code>&nbsp;&nbsp;2790⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;216🍴</code></b> [Source Code](https://github.com/photoview/photoview)) `GPL-3.0` `Go`
- 🌎 [PiGallery 2](bpatrik.github.io/pigallery2/) - A directory-first photo gallery website, with a rich UI, optimised for running on low resource servers. ( <b><code>&nbsp;&nbsp;&nbsp;904⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [Source Code](https://github.com/bpatrik/pigallery2)) `MIT` `Docker/Nodejs`
- 🌎 [Piwigo](piwigo.org/) - Photo gallery software for the web, built by an active community of users and developers. ( <b><code>&nbsp;&nbsp;1965⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;303🍴</code></b> [Source Code](https://github.com/Piwigo/Piwigo)) `GPL-2.0` `PHP`
- 🌎 [Quru Image Server](quruimageserver.com/) - High performance dynamically resizing image server offering directory based access control cropping, rotation, color management and other tools.  🌎 [Demo](quruimageserver.com),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Source Code](https://github.com/quru/qis)) `AGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;763⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [sigal](https://github.com/saimn/sigal) - Yet another simple static gallery generator. `MIT` `Python`
- 🌎 [UberGallery](www.ubergallery.net) - UberGallery is an easy to use, simple to manage, web photo gallery. UberGallery does not require a database and supports JPEG, GIF and PNG file types. Simply upload your images and UberGallery will automatically generate thumbnails and output HTML. ( <b><code>&nbsp;&nbsp;&nbsp;199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Source Code](https://github.com/UberGallery/UberGallery)) `MIT` `PHP`
- 🌎 [Zenphoto](www.zenphoto.org/) - Open-source gallery and CMS project. ( <b><code>&nbsp;&nbsp;&nbsp;262⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [Source Code](https://github.com/zenphoto/zenphoto)) `GPL-2.0` `PHP`


### Polls and Events

**[`^        back to top        ^`](#)**

_Related: [Booking and Scheduling](#booking-and-scheduling)_

-  <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Bitpoll](https://github.com/fsinfuhh/Bitpoll) - A web application for scheduling meetings and general polling.  🌎 [Demo](bitpoll.mafiasi.de/)) `GPL-3.0` `Python`
- 🌎 [Calagator](calagator.org/) - Event aggregator. ( <b><code>&nbsp;&nbsp;&nbsp;406⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;219🍴</code></b> [Source Code](https://github.com/calagator/calagator)) `MIT` `Ruby`
- 🌎 [ClearFlask](clearflask.com) - Community-feedback tool for managing incoming feedback and prioritizing a public roadmap. Alternative to Canny, UserVoice, Upvoty.  🌎 [Demo](product.clearflask.com),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Source Code](https://github.com/clearflask/clearflask)) `AGPL-3.0` `Docker`
-  <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Croodle](https://github.com/jelhan/croodle) - Croodle is an end-to-end encrypted web application to schedule a date or to do a poll on any topic. `MIT` `Javascript`
- [dudle](http://primelife.ercim.eu/results/opensource/63-dudle) - Online scheduling application.  🌎 [Demo](dudle.inf.tu-dresden.de/),  <b><code>&nbsp;&nbsp;&nbsp;290⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Source Code](https://github.com/kellerben/dudle)) `AGPL-3.0` `Ruby`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Feedka](https://github.com/drabkirn/feedka) `⚠` - Open-source web application that can serve as a platform to get authentic, kindful, and constructive feedback from your friends, family, and co-workers.  🌎 [Demo](feedka.herokuapp.com)) `AGPL-3.0` `Ruby`
- 🌎 [Fider](getfider.com) - Open source alternative to UserVoice for customer feedback.  🌎 [Demo](demo.fider.io),  <b><code>&nbsp;&nbsp;1989⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;559🍴</code></b> [Source Code](https://github.com/getfider/fider)) `MIT` `Go`
- 🌎 [Framadate](framadate.org/) - Online service for planning an appointment or make a decision quickly and easily: Make a poll, Define dates or subjects to choose, Send the poll link to your friends or colleagues, Discuss and make a decision.  🌎 [Demo](framadate.org/aqg259dth55iuhwm), 🌎 [Source Code](git.framasoft.org/framasoft/framadate)) `CECILL-B` `PHP`
- 🌎 [Gancio](gancio.org/) - A shared agenda for local communities.  🌎 [Demo](demo.gancio.org/), 🌎 [Source Code](framagit.org/les/gancio)) `AGPL-3.0` `Nodejs`
- 🌎 [hitobito](hitobito.com/en) - A web application to manage complex group hierarchies with members, events and a lot more.  🌎 [Demo](demo.hitobito.com/en/users/sign_in),  <b><code>&nbsp;&nbsp;&nbsp;262⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Source Code](https://github.com/hitobito/hitobito)) `AGPL-3.0` `Ruby`
- 🌎 [JD Esurvey](www.jdsoft.com/jd-esurvey.html) - Open source enterprise survey web application. ( <b><code>&nbsp;&nbsp;&nbsp;218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;191🍴</code></b> [Source Code](https://github.com/JD-Software/JDeSurvey)) `AGPL-3.0` `Java`
- 🌎 [Kyélà](kyela.net/) - Participation polls for group events.  🌎 [Demo](kyela.net/concert/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Source Code](https://github.com/abienvenu/Kyela)) `AGPL-3.0` `PHP`
- 🌎 [LimeSurvey](www.limesurvey.org) - Feature-rich Open Source web based polling software. Supports extensive survey logic.  🌎 [Demo](demo.limesurvey.org),  <b><code>&nbsp;&nbsp;2055⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;858🍴</code></b> [Source Code](https://github.com/LimeSurvey/LimeSurvey)) `GPL-2.0` `PHP`
- 🌎 [Meetable](meetable.org) - Event aggregator.  🌎 [Demo](events.indieweb.org),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Source Code](https://github.com/aaronpk/Meetable)) `MIT` `PHP`
- 🌎 [Mobilizon](mobilizon.org) - A federated tool that helps you find, create and organise events and groups.  🌎 [Demo](demo.mobilizon.org/), 🌎 [Source Code](framagit.org/framasoft/mobilizon/)) `GPL-3.0` `Elixir`
-  <b><code>&nbsp;&nbsp;2858⭐</code></b> <b><code>&nbsp;&nbsp;1851🍴</code></b> [Open Event Server](https://github.com/fossasia/open-event-server) - Enables organizers to manage events from concerts to conferences and meet-ups. `GPL-3.0` `Python`
- 🌎 [PHPBack](www.phpback.org) - The open source feedback system.  🌎 [Demo](www.phpback.org/demo/),  <b><code>&nbsp;&nbsp;&nbsp;369⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [Source Code](https://github.com/ivandiazwm/phpback)) `GPL-3.0` `PHP`


### Proxy

**[`^        back to top        ^`](#)**

- 🌎 [imgproxy](imgproxy.net/) - Fast and secure standalone server for resizing and converting remote images. It works great when you need to resize multiple images on the fly without preparing a ton of cached resized images or re-doing it every time the design changes. ( <b><code>&nbsp;&nbsp;6323⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;476🍴</code></b> [Source Code](https://github.com/imgproxy/imgproxy)) `MIT` `Go/Docker`
- 🌎 [inlets](inlets.dev/) - Expose your local endpoints to the Internet - with a Kubernetes integration, Docker image and CLI available. `MIT` `Go/Docker`
- 🌎 [iodine](code.kryo.se/iodine/) - IPv4 over DNS tunnel solution, enabling you to start up a socks5 proxy listener. ( <b><code>&nbsp;&nbsp;4359⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;432🍴</code></b> [Source Code](https://github.com/yarrick/iodine)) `ISC` `C`
-  <b><code>&nbsp;&nbsp;&nbsp;147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [microproxy](https://github.com/thekvs/microproxy) - Lightweight non-caching HTTP/HTTPS proxy server. `MIT` `Go`
- 🌎 [Nginx Proxy Manager](nginxproxymanager.com/) - Nginx Proxy Manager is an easy way to accomplish reverse proxying hosts with SSL termination. ( <b><code>&nbsp;&nbsp;8518⭐</code></b> <b><code>&nbsp;&nbsp;1041🍴</code></b> [Source Code](https://github.com/jc21/nginx-proxy-manager)) `MIT` `Nodejs/Docker`
- 🌎 [PHP-Proxy](www.php-proxy.com/) - Web proxy script built specifically to be fast, easy to modify and to support video sites such as YouTube.  🌎 [Demo](unblockvideos.com/),  <b><code>&nbsp;&nbsp;&nbsp;702⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;373🍴</code></b> [Source Code](https://github.com/Athlon1600/php-proxy-app)) `MIT` `PHP`
- 🌎 [Pomerium](pomerium.io) - An identity-aware reverse proxy, successor to now obsolete oauth_proxy. It inserts an OAuth step before proxying your request to the backend, so that you can safely expose your self-hosted websites to public Internet. ( <b><code>&nbsp;&nbsp;3163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [Source Code](https://github.com/pomerium/pomerium)) `Apache-2.0` `Go`
- 🌎 [Pound](www.apsis.ch/pound.html) - Light-weight reverse proxy and load balancer for HTTP/HTTPS. `GPL-2.0` `C`
- 🌎 [Privoxy](www.privoxy.org) - Non-caching web proxy with advanced filtering capabilities for enhancing privacy, modifying web page data and HTTP headers, controlling access, and removing ads and other obnoxious Internet junk. `GPL-2.0` `C`
-  <b><code>&nbsp;&nbsp;4327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;300🍴</code></b> [Redbird](https://github.com/OptimalBits/redbird) - A modern reverse proxy for node that includes cluster, HTTP2, LetsEncrypt, and Docker support. `BSD-2-Clause` `Javascript`
-  <b><code>&nbsp;&nbsp;2860⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;245🍴</code></b> [sish](https://github.com/antoniomika/sish) - Open source serveo/ngrok alternative providing HTTP(S)/WS(S)/TCP tunnels to localhost using only SSH. `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server) - SOCKS5 proxy server with built-in authentication and Telegram-bot for user management and user statistics on data spent (handy when you pay per GB of data). It is dockerised and simple to install. `Apache-2.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [SOCKS5Engine](https://github.com/VeeSecurity/SOCKS5Engine) - Lightweight & resource-efficient SOCKS5 proxy server, optimized for high-load. `AGPL-3.0` `Go`
- [Squid](http://www.squid-cache.org/) - Caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages.  🌎 [Source Code](code.launchpad.net/squid)) `GPL-2.0` `C`
-  <b><code>&nbsp;&nbsp;1348⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [SWAG (Secure Web Application Gateway)](https://github.com/linuxserver/docker-swag) - Nginx webserver and reverse proxy with PHP support, built-in Certbot (Let's Encrypt) client and fail2ban integration. `GPL-3.0` `Docker`
- 🌎 [Tinyproxy](tinyproxy.github.io/) - Light-weight HTTP/HTTPS proxy daemon. ( <b><code>&nbsp;&nbsp;3332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;544🍴</code></b> [Source Code](https://github.com/tinyproxy/tinyproxy)) `GPL-2.0` `C`
- 🌎 [Traefik](traefik.io/) - Træfɪk is a modern HTTP reverse proxy and load balancer made to deploy microservices with ease. It supports several backends (Docker, Swarm, Mesos/Marathon, …) to manage its configuration automatically and dynamically. ( <b><code>&nbsp;38976⭐</code></b> <b><code>&nbsp;&nbsp;4258🍴</code></b> [Source Code](https://github.com/traefik/traefik)) `MIT` `Go`


### Read-it-later Lists

**[`^        back to top        ^`](#)**

- 🌎 [Readflow](readflow.app) - Lightweight news reader with modern interface and features: full-text search, automatic categorization, archiving, offline support, notifications... ( <b><code>&nbsp;&nbsp;&nbsp;248⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Source Code](https://github.com/ncarlier/readflow)) `MIT` `Go`
- 🌎 [Wallabag](www.wallabag.org) - Wallabag, formerly Poche, is a web application allowing you to save articles to read them later with improved readability. ( <b><code>&nbsp;&nbsp;7172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;674🍴</code></b> [Source Code](https://github.com/wallabag/wallabag)) `MIT` `PHP`


### Recipe Management

**[`^        back to top        ^`](#)**

- 🌎 [Groceri.es](groceri.es/) - Web-based application to manage your recipes and plan your meals ahead. groceri.es keeps track of your menu plans and generates a groceries list for you. ( <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Source Code](https://github.com/juriansluiman/groceri.es)) `MIT` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [kcal](https://github.com/kcal-app/kcal) - Track nutritional information about foods and recipes, set goals, and record a food journal to help along the way. Kcal is a personal system that focuses on direct control of inputs and a minimal, easy to use recipe presentation for preparing meals. ([Demo](http://demo.kcal.cooking/login)) `MPL-2.0` `PHP`
- 🌎 [Mealie](hay-kot.github.io/mealie/) - Material design inspired recipe manager with category and tag management, shopping-lists, meal-planner, and site customizations. Mealie is focused on simple user interactions to keep the whole family using the app. ( <b><code>&nbsp;&nbsp;2230⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;242🍴</code></b> [Source Code](https://github.com/hay-kot/mealie)) `MIT` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;252⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [RecipeSage](https://github.com/julianpoy/recipesage) - A recipe keeper, meal plan organizer, and shopping list manager that can import recipes directly from any URL.  🌎 [Demo](recipesage.com)) `AGPL-3.0` `Nodejs`
- 🌎 [Tandoor Recipes](docs.tandoor.dev/) - Django application to manage, tag and search recipes using either built-in models or external storage providers hosting PDFs, Images or other files.  🌎 [Demo](app.tandoor.dev/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/vabene1111/recipes/)) `MIT` `Python`


### Resource Planning

**[`^        back to top        ^`](#)**

- 🌎 [farmOS](farmos.org/) - Web-based farm record keeping application. ( <b><code>&nbsp;&nbsp;&nbsp;527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [Source Code](https://github.com/farmOS/farmOS)) `GPL-2.0` `PHP`
- 🌎 [grocy](grocy.info/) - ERP beyond your fridge - grocy is a web-based self-hosted groceries & household management solution for your home.  🌎 [Demo](en.demo.grocy.info/),  <b><code>&nbsp;&nbsp;4230⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;397🍴</code></b> [Source Code](https://github.com/grocy/grocy)) `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;562⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [Tania](https://github.com/usetania/tania-core) - Tania is a free and open source farming management system for everyone. You can manage your areas, reservoirs, farm tasks, inventories, and the crop growing progress. `Apache-2.0` `Go`


### Resource Planning - Enterprise Resource Planning

**[`^        back to top        ^`](#)**

- 🌎 [Dolibarr](www.dolibarr.org/) - Dolibarr ERP CRM is a modern software package to manage your company or foundation activity (contacts, suppliers, invoices, orders, stocks, agenda, accounting, ...).  🌎 [Demo](www.dolibarr.org/onlinedemo.php),  <b><code>&nbsp;&nbsp;3336⭐</code></b> <b><code>&nbsp;&nbsp;2090🍴</code></b> [Source Code](https://github.com/Dolibarr/dolibarr)) `GPL-3.0-or-later` `PHP`
- 🌎 [ERPNext](erpnext.com) - Free open source ERP system. ( <b><code>&nbsp;11556⭐</code></b> <b><code>&nbsp;&nbsp;4689🍴</code></b> [Source Code](https://github.com/frappe/erpnext)) `GPL-3.0` `Python`
- 🌎 [LedgerSMB](ledgersmb.org/) - Integrated accounting and ERP system for small and midsize businesses, with double entry accounting, budgeting, invoicing, quotations, projects, orders and inventory management, shipping and more.  🌎 [Demo](demo.cloud.efficito.com/erp/1.5/login.pl),  <b><code>&nbsp;&nbsp;&nbsp;286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;126🍴</code></b> [Source Code](https://github.com/ledgersmb/LedgerSMB)) `GPL-2.0` `Perl`
- 🌎 [Odoo](www.odoo.com) - Free open source ERP system.  🌎 [Demo](demo.odoo.com/),  <b><code>&nbsp;25700⭐</code></b> <b><code>&nbsp;16574🍴</code></b> [Source Code](https://github.com/odoo/odoo)) `LGPL-3.0` `Python`
- 🌎 [OFBiz](ofbiz.apache.org/) - FOSS enterprise resource planning system with a suite of business applications flexible enough to be used across any industry.  🌎 [Source Code](svn.apache.org/viewvc/ofbiz/)) `Apache-2.0` `Java`
- 🌎 [Tryton](www.tryton.org/) - Free open source business solution.  🌎 [Demo](www.tryton.org/download.html), 🌎 [Source Code](hg.tryton.org/)) `GPL-3.0` `Python`


### Search Engines

**[`^        back to top        ^`](#)**

- 🌎 [Gigablast](www.gigablast.com/) - Open-source search engine. ( <b><code>&nbsp;&nbsp;1368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;438🍴</code></b> [Source Code](https://github.com/gigablast/open-source-search-engine)) `Apache-2.0` `C++`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Jina](https://github.com/jina-ai/jina/) - Cloud-native neural search framework for any kind of data. `Apache-2.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [librengine](https://github.com/liameno/librengine) - Private web search engine. `GPL-3.0` `C++`
- 🌎 [MeiliSearch](meilisearch.com) - Ultra relevant, instant and typo-tolerant full-text search API. ( <b><code>&nbsp;28084⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;983🍴</code></b> [Source Code](https://github.com/meilisearch/MeiliSearch)) `MIT` `Rust`
- 🌎 [OpenSearch](opensearch.org) - Open source distributed and RESTful search engine. ( <b><code>&nbsp;&nbsp;5440⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;658🍴</code></b> [Source Code](https://github.com/opensearch-project/OpenSearch)) `Apache-2.0` `Java`
- 🌎 [Searx](searx.github.io/searx/) - Privacy-respecting, hackable metasearch engine.  🌎 [Demo](searx.space/),  <b><code>&nbsp;11653⭐</code></b> <b><code>&nbsp;&nbsp;1623🍴</code></b> [Source Code](https://github.com/searx/searx)) `AGPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;415⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [sist2](https://github.com/simon987/sist2) - Lightning-fast file system indexer and search tool.  🌎 [Demo](sist2.simon987.net/)) `GPL-3.0` `C`
- 🌎 [Typesense](typesense.org) - Blazing fast, typo-tolerant open source search engine optimized for developer happiness and ease of use. ( <b><code>&nbsp;10373⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;299🍴</code></b> [Source Code](https://github.com/typesense/typesense)) `GPL-3.0` `C++`
-  <b><code>&nbsp;&nbsp;5960⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;655🍴</code></b> [Whoogle](https://github.com/benbusby/whoogle-search) `⚠` - A self-hosted, ad-free, privacy-respecting metasearch engine. `MIT` `Python`
- 🌎 [Yacy](yacy.net/en/index.html) - Peer based, decentralized search engine server. ( <b><code>&nbsp;&nbsp;2644⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;371🍴</code></b> [Source Code](https://github.com/yacy/yacy_search_server)) `GPL-2.0` `Java`
- 🌎 [ZincSearch](zincsearch.com) - A lightweight alternative to elasticsearch that requires minimal resources, written in Go. ( <b><code>&nbsp;&nbsp;9736⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;432🍴</code></b> [Demo](https://github.com/zinclabs/zinc#playground-server),  <b><code>&nbsp;&nbsp;9736⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;432🍴</code></b> [Source Code](https://github.com/zinclabs/zinc)) `Apache-2.0` `Go`


### Self-hosting Solutions

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;1927⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;348🍴</code></b> [Ansible-NAS](https://github.com/DaveStephens/ansible-nas) - Build a full-featured home server with this playbook and an Ubuntu box. `MIT` `YAML/Docker`
- 🌎 [Bitsii Bridge](gitlab.com/bitsii/Bitsii/-/wikis/home) `⚠` - Easy to install self-hosting platform for Windows, MacOS, and Linux. Depends on a dynamic DNS provider and Let's Encrypt.  🌎 [Source Code](gitlab.com/edgii/BBridge)) `MPL-2.0` `Java/Other`
- 🌎 [Cloudbox](cloudbox.works) - Ansible-based solution for rapidly deploying a Docker containerized cloud media server. ( <b><code>&nbsp;&nbsp;1958⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;295🍴</code></b> [Source Code](https://github.com/Cloudbox/Cloudbox)) `GPL-3.0` `Shell/Ansible`
- 🌎 [DietPi](dietpi.com/) - Minimal Debian OS optimized for single-board computers, which allows you to easily install and manage several services for selfhosting at home. ( <b><code>&nbsp;&nbsp;3296⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;389🍴</code></b> [Source Code](https://github.com/MichaIng/DietPi)) `GPL-2.0` `Shell`
- 🌎 [DockSTARTer](dockstarter.com/) - DockSTARTer helps you get started with home server apps running in Docker. ( <b><code>&nbsp;&nbsp;1714⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [Source Code](https://github.com/GhostWriters/DockSTARTer)) `MIT` `Shell`
- 🌎 [FLAP](www.flap.cloud) - Low maintenance framework to manage self-hosted services.  🌎 [Source Code](gitlab.com/flap-box/flap)) `AGPL-3.0` `Docker/Shell`
- 🌎 [FreedomBox](freedomboxfoundation.org/) - Community project to develop, design and promote personal servers running free software for private, personal, communications.  🌎 [Source Code](salsa.debian.org/freedombox-team/freedombox)) `AGPL-3.0` `Python/Other`
- 🌎 [HomelabOS](homelabos.com) - Your very own offline-first privacy-centric open-source data-center. Deploy over 100 services with a few commands.  🌎 [Source Code](gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- 🌎 [LibreServer](libreserver.org/) - Home server configuration based on Debian. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Source Code](https://github.com/bashrc2/libreserver)) `AGPL-3.0` `Shell`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Mars Server](https://github.com/borjapazr/mars-server) - Managed home server with Docker, Docker Compose, Make and Bash. `MIT` `Docker`
-  <b><code>&nbsp;&nbsp;1694⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;255🍴</code></b> [NextCloudPi](https://github.com/nextcloud/nextcloudpi) - Nextcloud preinstalled and preconfigured, with a text and web management interface and all the tools needed to self host private data. With installation images for Raspberry Pi, Odroid, Rock64, Docker, and a curl installer for Armbian/Debian. `GPL-2.0-or-later` `Bash/PHP`
- 🌎 [OpenMediaVault](www.openmediavault.org/) - OpenMediaVault is the next generation network attached storage (NAS) solution based on Debian Linux. It contains services like SSH, (S)FTP, SMB/CIFS, DAAP media server, RSync, BitTorrent client and many more. ( <b><code>&nbsp;&nbsp;3149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;383🍴</code></b> [Source Code](https://github.com/openmediavault/openmediavault)) `GPL-3.0` `PHP`
- 🌎 [Sandstorm](sandstorm.io/) - Personal server for running self-hosted apps easily and securely.  🌎 [Demo](demo.sandstorm.io/),  <b><code>&nbsp;&nbsp;6059⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;706🍴</code></b> [Source Code](https://github.com/sandstorm-io/sandstorm)) `Apache-2.0` `C++/Other`
-  <b><code>&nbsp;10233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;851🍴</code></b> [sovereign](https://github.com/sovereign/sovereign) - Set of Ansible playbooks to build and maintain your own private cloud: email, calendar, contacts, file sync, IRC bouncer, VPN, and more. `GPL-3.0` `YAML/Other`
- 🌎 [Syncloud](syncloud.org/) - Your own online file storage, social network or email server. ( <b><code>&nbsp;&nbsp;&nbsp;320⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Source Code](https://github.com/syncloud/platform)) `GPL-3.0` `Python/Other`
- 🌎 [UBOS](ubos.net/) - Linux distro that runs on indie boxes (personal servers and IoT devices). Single-command installation and management of apps - Jenkins, Mediawiki, Owncloud, WordPress, etc., and other features. `GPL-3.0` `Perl/Other`
- 🌎 [WikiSuite](wikisuite.org) - The most comprehensive and integrated Free / Libre / Open Source enterprise software suite.  🌎 [Source Code](wikisuite.org/Source-Code)) `GPL-3.0/LGPL-2.1/Apache-2.0/MPL-2.0/MPL-1.1/MIT/AGPL-3.0` `ClearOS`
- 🌎 [xsrv](xsrv.readthedocs.io/) - Install and manage self-hosted services/applications, on your own server(s). ( <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Source Code](https://github.com/nodiscc/xsrv)) `GPL-3.0` `Shell/Ansible`
- 🌎 [YunoHost](yunohost.org/) - Server operating system aiming to make self-hosting accessible to everyone.  🌎 [Demo](yunohost.org/#/try),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/YunoHost)) `AGPL-3.0` `Python/Other`


### Software Development

**[`^        back to top        ^`](#)**


### Software Development - API Management

**[`^        back to top        ^`](#)**

- 🌎 [DreamFactory](www.dreamfactory.com/) - Turns any SQL/NoSQL/Structured data into Restful API. ( <b><code>&nbsp;&nbsp;1277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;274🍴</code></b> [Source Code](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache-2.0` `PHP`
- 🌎 [form.io](form.io) - A REST API building platform that utilizes a drag & drop form builder, and is application framework agnostic. Contains open source and enterprise version.  🌎 [Demo](portal.form.io),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/formio)) `MIT` `Nodejs`
- 🌎 [Fusio](www.fusio-project.org/) - Open-source API management platform which helps to build and manage REST APIs.  🌎 [Demo](fusio-project.org/demo),  <b><code>&nbsp;&nbsp;1159⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;167🍴</code></b> [Source Code](https://github.com/apioo/fusio)) `AGPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Hapttic](https://github.com/jsoendermann/hapttic) - Simple HTTP server that forwards all requests to a shell script to handle webhooks you receive. `Apache-2.0` `Go`
- 🌎 [Hasura](hasura.io) - Fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also trigger webhooks on database events. ( <b><code>&nbsp;27489⭐</code></b> <b><code>&nbsp;&nbsp;2355🍴</code></b> [Source Code](https://github.com/hasura/graphql-engine)) `Apache-2.0` `Haskell`
- 🌎 [Hoppscotch](hoppscotch.io) - A free, fast and beautiful API request builder. ( <b><code>&nbsp;45214⭐</code></b> <b><code>&nbsp;&nbsp;3062🍴</code></b> [Source Code](https://github.com/hoppscotch/hoppscotch)) `MIT` `Nodejs/Vue/Nuxt`
- 🌎 [Kong](konghq.com/kong/) - The World’s Most Popular Open Source Microservice API Gateway and Platform. ( <b><code>&nbsp;32501⭐</code></b> <b><code>&nbsp;&nbsp;4247🍴</code></b> [Source Code](https://github.com/Kong/kong)) `Apache-2.0` `Lua`
- 🌎 [Lura](luraproject.org/) - Open source High-Performance API Gateway. ( <b><code>&nbsp;&nbsp;5162⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;497🍴</code></b> [Source Code](https://github.com/luraproject/lura)) `Apache-2.0` `Go`
- 🌎 [Para](paraio.org) - Flexible and modular backend framework/server for object persistence, API development and authentication. ( <b><code>&nbsp;&nbsp;&nbsp;440⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;126🍴</code></b> [Source Code](https://github.com/erudika/para)) `Apache-2.0` `Java`
-  <b><code>&nbsp;&nbsp;1023⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [Pizzly](https://github.com/bearer/pizzly) - Open-source API Integrations Manager that provides everything a developer needs to interact with OAuth based APIs. `MIT` `Nodejs`
- 🌎 [Tyk](tyk.io) - Fast and scalable open source API Gateway. Out of the box, Tyk offers an API Management Platform with an API Gateway, API Analytics, Developer Portal and API Management Dashboard. ( <b><code>&nbsp;&nbsp;7562⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;914🍴</code></b> [Source Code](https://github.com/TykTechnologies/tyk)) `MPL-2.0` `Go`


### Software Development - Bug Trackers

**[`^        back to top        ^`](#)**

**Please visit [Ticketing](#ticketing)**


### Software Development - Continuous Integration & Deployment

**[`^        back to top        ^`](#)**

**Please visit  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [awesome-sysadmin/Continuous Integration & Continuous Deployment](https://github.com/awesome-foss/awesome-sysadmin#continuous-integration--continuous-deployment)**


### Software Development - FaaS & Serverless

**[`^        back to top        ^`](#)**
 🌎 [Serverless computing - Wikipedia](en.wikipedia.org/wiki/Serverless_computing)

- 🌎 [Appwrite](appwrite.io) - End to end backend server for web, native, and mobile developers 🚀. ( <b><code>&nbsp;23794⭐</code></b> <b><code>&nbsp;&nbsp;1831🍴</code></b> [Source Code](https://github.com/appwrite/appwrite)) `BSD-3-Clause` `PHP`
-  <b><code>&nbsp;&nbsp;1785⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [fx](https://github.com/metrue/fx) - A tool to help you do Function as a Service with painless on your own servers. `MIT` `Go`
-  <b><code>&nbsp;&nbsp;3030⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;233🍴</code></b> [IronFunctions](https://github.com/iron-io/functions) - The serverless microservices platform by 🌎 [iron.io](www.iron.io/). `Apache-2.0` `Go`
- 🌎 [LocalStack](localstack.cloud/) - LocalStack is a fully functional local AWS cloud stack. This includes Lambda for serverless computation. ( <b><code>&nbsp;42260⭐</code></b> <b><code>&nbsp;&nbsp;3150🍴</code></b> [Source Code](https://github.com/localstack/localstack)) `Apache-2.0` `Python/Other`
- 🌎 [OpenFaaS](www.openfaas.com/) - Serverless Functions Made Simple for Docker & Kubernetes. ( <b><code>&nbsp;21838⭐</code></b> <b><code>&nbsp;&nbsp;1775🍴</code></b> [Source Code](https://github.com/openfaas/faas)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Trusted-CGI](https://github.com/reddec/trusted-cgi) - Lightweight self-hosted lambda/applications/cgi/serverless-functions platform. `MIT` `Go`


### Software Development - IDE & Tools

**[`^        back to top        ^`](#)**

- 🌎 [Appsmith](www.appsmith.com/) - Cloud or self-hosted open-source platform to build admin panels, CRUD apps and workflows. Build everything you need, 10x faster. ( <b><code>&nbsp;19822⭐</code></b> <b><code>&nbsp;&nbsp;1637🍴</code></b> [Source Code](https://github.com/appsmithorg/appsmith)) `Apache-2.0` `Java/Docker`
- 🌎 [Atheos](www.atheos.io) - Web-based IDE framework with a small footprint and minimal requirements, continued from Codiad. ( <b><code>&nbsp;&nbsp;&nbsp;281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Source Code](https://github.com/Atheos/Atheos)) `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Babelfish](https://github.com/bblfsh/bblfshd) - Self-hosted server for source code parsing. It can parse any file, in any supported language, extract an Abstract Syntax Tree from it, and convert it to a Universal Abstract Syntax Tree which can enable further analysis and transformation. `GPL-3.0` `Go`
- 🌎 [Budibase](www.budibase.com) - Build and automate internal tools, admin panels, dashboards, CRUD apps, and more, in minutes. Budibase is the open source alternative to Outsystems, Retool, Mendix, Appian. ( <b><code>&nbsp;14305⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;790🍴</code></b> [Source Code](https://github.com/Budibase/budibase)) `GPL-3.0` `Nodejs`
- 🌎 [Coder](coder.com/) - Visual Studio Code in the browser, hosted on a remote server. ( <b><code>&nbsp;55103⭐</code></b> <b><code>&nbsp;&nbsp;4591🍴</code></b> [Source Code](https://github.com/coder/code-server)) `MIT` `Nodejs/Docker`
- 🌎 [Eclipse Che](www.eclipse.org/che/) - Open source workspace server and cloud IDE. ( <b><code>&nbsp;&nbsp;6695⭐</code></b> <b><code>&nbsp;&nbsp;1209🍴</code></b> [Source Code](https://github.com/eclipse/che)) `EPL-1.0` `Docker/Java`
- 🌎 [Gitpod](gitpod.io/) - Online IDE for GitHub and GitLab.  🌎 [Demo](gitpod.io/#https://github.com/correia-jpv/fucking-awesome-selfhosted),  <b><code>&nbsp;&nbsp;&nbsp;216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [Source Code](https://github.com/gitpod-io/self-hosted)) `EPL-2.0` `Go/Docker`
-  <b><code>&nbsp;&nbsp;&nbsp;338⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Hakatime](https://github.com/mujx/hakatime) - WakaTime server implementation with analytics dashboard. `Unlicense` `Haskell`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [HttPlaceholder](https://github.com/dukeofharen/httplaceholder) - Quickly mock away any webservice using HttPlaceholder. HttPlaceholder lets you specify what the request should look like and what response needs to be returned. `MIT` `C#`
- 🌎 [ICEcoder](icecoder.net/) - ICEcoder is a web IDE / browser based code editor, which allows you to develop websites directly within the web browser. ([Demo](http://demo.icecoder.net/ICEcoder/),  <b><code>&nbsp;&nbsp;1352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;346🍴</code></b> [Source Code](https://github.com/icecoder/ICEcoder)) `MIT` `PHP`
- 🌎 [JS Bin](jsbin.com/) - Open source collaborative web development debugging tool. ( <b><code>&nbsp;&nbsp;4267⭐</code></b> <b><code>&nbsp;&nbsp;1272🍴</code></b> [Source Code](https://github.com/jsbin/jsbin)) `MIT` `Nodejs`
- 🌎 [Judge0 CE](judge0.com) - Open source API to compile and run source code. ( <b><code>&nbsp;&nbsp;1121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;261🍴</code></b> [Source Code](https://github.com/judge0/judge0)) `GPL-3.0` `Ruby`
- 🌎 [JupyterLab](jupyterlab.github.io/jupyterlab/) - Web-based environment for interactive and reproducible computing.  🌎 [Demo](mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/jupyterlab/jupyterlab/)) `BSD-3-Clause` `Python/Docker`
- 🌎 [Lowdefy](www.lowdefy.com/) - Build internal tools, BI dashboards, admin panels, CRUD apps and workflows in minutes using YAML / JSON on an self-hosted, open-source platform. Connect to your data sources, host via Serverless, Netlify or Docker. ( <b><code>&nbsp;&nbsp;1749⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [Source Code](https://github.com/lowdefy/lowdefy)) `Apache-2.0` `Nodejs`
-  <b><code>&nbsp;&nbsp;2652⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;355🍴</code></b> [ML Workspace](https://github.com/ml-tooling/ml-workspace) - All-in-one web-based IDE for machine learning and data science. `Apache-2.0` `Docker`
- 🌎 [Motor Admin](www.getmotoradmin.com/) - No-code admin panel and business intelligence software - search, create, update, and delete data entries, create custom actions, and build reports.  🌎 [Demo](motor-admin.herokuapp.com/demo/),  <b><code>&nbsp;&nbsp;1276⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Source Code](https://github.com/motor-admin/motor-admin)) `AGPL-3.0` `Ruby`
- 🌎 [Regexr](regexr.com/) - RegExr is a HTML/JS based tool for creating, testing, and learning about Regular Expressions. ( <b><code>&nbsp;&nbsp;8530⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;872🍴</code></b> [Source Code](https://github.com/gskinner/regexr)) `MIT` `Nodejs`
- 🌎 [RStudio Server](www.rstudio.com/products/rstudio/#Server) - Web browser based IDE for R. ( <b><code>&nbsp;&nbsp;4005⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;979🍴</code></b> [Source Code](https://github.com/rstudio/rstudio)) `AGPL-3.0` `Java/C++`
- 🌎 [Slingcode](slingcode.net/) - Web app IDE and computing platform in a single static HTML file.  🌎 [Demo](slingcode.net/slingcode.html),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/chr15m/slingcode/)) `MIT` `HTML`
- 🌎 [sourcegraph](sourcegraph.com) - Sourcegraph is a fast, open-source, fully-featured code search and navigation engine written in Go. ( <b><code>&nbsp;&nbsp;6477⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;799🍴</code></b> [Source Code](https://github.com/sourcegraph/sourcegraph)) `Apache-2.0` `Go`
- 🌎 [ToolJet](tooljet.io/) - ToolJet is the open-source low-code framework alternative to Retool & Mendix to build & deploy internal tools with minimal engineering effort. ( <b><code>&nbsp;12467⭐</code></b> <b><code>&nbsp;&nbsp;1012🍴</code></b> [Source Code](https://github.com/ToolJet/ToolJet)) `GPL-3.0` `Nodejs`
- 🌎 [Wakapi](wakapi.dev/) - Tracking tool for coding statistics, compatible with WakaTime. ( <b><code>&nbsp;&nbsp;&nbsp;934⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [Source Code](https://github.com/muety/wakapi)) `GPL-3.0` `Go`


### Software Development - Localization

**[`^        back to top        ^`](#)**

- 🌎 [Accent](www.accent.reviews/) - Open-source, self-hosted, developer-oriented translation tool. ( <b><code>&nbsp;&nbsp;&nbsp;854⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [Source Code](https://github.com/mirego/accent)) `BSD-3-Clause` `Elixir`
- 🌎 [Localizer](localizer.dev) - Free self-hosted open-source crowd-translating service for your product.  🌎 [Demo](localize.todorant.com),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Source Code](https://github.com/backmeupplz/localizer-backend)) `MIT` `Nodejs/Docker`
- 🌎 [Pootle](pootle.translatehouse.org) - Online translation and localization tool. ( <b><code>&nbsp;&nbsp;1423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;294🍴</code></b> [Source Code](https://github.com/translate/pootle)) `GPL-3.0` `Python`
- 🌎 [Tolgee](tolgee.io) - Developer & translator friendly web-based localization platform enabling users to translate directly in the app they develop. ( <b><code>&nbsp;&nbsp;&nbsp;292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Source Code](https://github.com/tolgee/server)) `Apache-2.0` `Docker/Java`
- 🌎 [Traduora](traduora.co) - Translation management platform for teams. ( <b><code>&nbsp;&nbsp;1659⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [Source Code](https://github.com/ever-co/ever-traduora)) `AGPL-3.0` `Docker/Nodejs`
- 🌎 [Weblate](weblate.org) - Web-based translation tool with tight version control integration.  🌎 [Demo](demo.weblate.org),  <b><code>&nbsp;&nbsp;3048⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;721🍴</code></b> [Source Code](https://github.com/WeblateOrg/weblate)) `GPL-3.0` `Python`
- [Zanata](http://zanata.org) - Web-based translation platform for translators, content creators and developers to manage localisation projects. ( <b><code>&nbsp;&nbsp;&nbsp;303⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Source Code](https://github.com/zanata/zanata-platform)) `GPL-2.0` `Java`


### Software Development - Project Management

**[`^        back to top        ^`](#)**

_Related: [Ticketing](#ticketing), [Task management & To-do lists](#task-management--to-do-lists)_

_See also:  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [awesome-sysadmin/Code Review](https://github.com/awesome-foss/awesome-sysadmin#code-review)_

- 🌎 [Bonobo Git Server](bonobogitserver.com/) - Set up your own self hosted git server on IIS for Windows. Manage users and have full control over your repositories with a nice user friendly graphical interface. ( <b><code>&nbsp;&nbsp;1738⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;586🍴</code></b> [Source Code](https://github.com/jakubgarfield/Bonobo-Git-Server)) `MIT` `C#`
- 🌎 [Fossil](www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - Distributed version control system featuring wiki and bug tracker. `BSD-2-Clause-FreeBSD` `C`
-  <b><code>&nbsp;&nbsp;&nbsp;798⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [Git WebUI](https://github.com/alberthier/git-webui) - Standalone web based user interface for git repositories. `Apache-2.0` `Python`
- 🌎 [Gitblit](gitblit.github.io/gitblit/) - Pure Java stack for managing, viewing, and serving Git repositories. ( <b><code>&nbsp;&nbsp;2084⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;647🍴</code></b> [Source Code](https://github.com/gitblit/gitblit)) `Apache-2.0` `Java`
- 🌎 [gitbucket](gitbucket.github.io/gitbucket-news/) - Easily installable GitHub clone powered by Scala. ( <b><code>&nbsp;&nbsp;8687⭐</code></b> <b><code>&nbsp;&nbsp;1236🍴</code></b> [Source Code](https://github.com/gitbucket/gitbucket)) `Apache-2.0` `Scala/Java`
- 🌎 [Gitea](gitea.io) - Community managed fork of Gogs, lightweight code hosting solution.  🌎 [Demo](try.gitea.io),  <b><code>&nbsp;31117⭐</code></b> <b><code>&nbsp;&nbsp;3917🍴</code></b> [Source Code](https://github.com/go-gitea/gitea)) `MIT` `Go`
- 🌎 [GitLab](about.gitlab.com) - Self Hosted Git repository management, code reviews, issue tracking, activity feeds and wikis.  🌎 [Demo](gitlab.com/), 🌎 [Source Code](gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby`
- 🌎 [Gitlist](gitlist.org/) - Web-based git repository browser - GitList allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history and diffs. ( <b><code>&nbsp;&nbsp;2862⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;542🍴</code></b> [Source Code](https://github.com/klaussilveira/gitlist)) `BSD-3-Clause` `PHP`
- 🌎 [Gitolite](gitolite.com/gitolite/index.html) - Gitolite allows you to setup git hosting on a central server, with fine-grained access control and many more powerful features. ( <b><code>&nbsp;&nbsp;8091⭐</code></b> <b><code>&nbsp;&nbsp;1003🍴</code></b> [Source Code](https://github.com/sitaramc/gitolite)) `GPL-2.0` `Perl`
-  <b><code>&nbsp;&nbsp;&nbsp;870⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [GitPrep](https://github.com/yuki-kimoto/gitprep) - Portable Github clone.  🌎 [Demo](perlcodesample.sakura.ne.jp/gitprep/gitprep.cgi)) `Artistic-2.0` `Perl`
- 🌎 [Gogs](gogs.io/) - Painless self-hosted Git Service written in Go.  🌎 [Demo](try.gogs.io/),  <b><code>&nbsp;40543⭐</code></b> <b><code>&nbsp;&nbsp;4596🍴</code></b> [Source Code](https://github.com/gogs/gogs)) `MIT` `Go`
- 🌎 [Kallithea](kallithea-scm.org/) - Source code management system that supports two leading version control systems, Mercurial and Git, with a web interface.  🌎 [Source Code](kallithea-scm.org/repos/kallithea)) `GPL-3.0` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;624⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [Klaus](https://github.com/jonashaag/klaus) - Simple, easy-to-set-up Git web viewer that Just Works. `ISC` `Python`
- 🌎 [Lavagna](lavagna.io) - Lavagna is an open-source issue/project management tool designed for small teams. Lightweight, pure Java, easy to install, easy to use. ( <b><code>&nbsp;&nbsp;&nbsp;589⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [Source Code](https://github.com/digitalfondue/lavagna)) `GPL-3.0` `Java`
- 🌎 [Lazylead](lazylead.org) `⚠` - Eliminate the annoying work within ticketing systems (Jira, GitHub, Trello). Allows to automate daily actions like tickets fields verification, email notifications by JQL/GQL, meeting requests to your (or teammates) calendar. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Source Code](https://github.com/dgroup/lazylead)) `MIT` `Ruby`
- 🌎 [Leantime](leantime.io) - Leantime is a lean project management system for small teams and startups helping to manage projects from ideation through delivery. ( <b><code>&nbsp;&nbsp;1278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;282🍴</code></b> [Source Code](https://github.com/leantime/leantime)) `GPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Microgit](https://github.com/microgit-com/microgit) - Git hosting service made in Crystal and Lucky. `MIT` `Crystal`
- 🌎 [Octobox](octobox.io/) `⚠` - Take back control of your GitHub Notifications. ( <b><code>&nbsp;&nbsp;4190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;368🍴</code></b> [Source Code](https://github.com/octobox/octobox)) `AGPL-3.0` `Ruby`
- 🌎 [OneDev](onedev.io/) - All-In-One DevOps Platform. With Git Management, Issue Tracking, and CI/CD. Simple yet Powerful.  🌎 [Source Code](code.onedev.io/projects/160)) `MIT` `Java`
- 🌎 [OpenProject](www.openproject.org) - OpenProject is a web-based project management system. ( <b><code>&nbsp;&nbsp;5907⭐</code></b> <b><code>&nbsp;&nbsp;1650🍴</code></b> [Source Code](https://github.com/opf/openproject)) `GPL-3.0` `Ruby`
- 🌎 [Pagure](pagure.io/pagure) - A lightweight, powerful, and flexible git-centric forge with features laying the foundation for federated and decentralized development.  🌎 [Demo](pagure.io/)) `GPL-2.0` `Python`
- 🌎 [Phproject](www.phproject.org/) - High performance full-featured project management system. ( <b><code>&nbsp;&nbsp;&nbsp;348⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [Source Code](https://github.com/Alanaktion/phproject)) `GPL-3.0` `PHP`
- 🌎 [ProjeQtOr](www.projeqtor.org/) - A complete, mature, multi-user project management system with extensive functionality for all phases of a project.  🌎 [Demo](demo.projeqtor.org/), 🌎 [Source Code](sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Re:Backlogs](https://github.com/kaishuu0123/rebacklogs) - Project management and collaboration tool powered by Ruby on Rails & VueJS.  🌎 [Demo](rebacklogs.saino.me/users/sign_up)) `MIT` `Ruby`
- 🌎 [Redmine](www.redmine.org/) - Redmine is a flexible project management web application. ([Demo](http://demo.redmine.org/), 🌎 [Source Code](svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- 🌎 [RhodeCode](rhodecode.com/) - RhodeCode is an open source platform for software development teams. It unifies and simplifies repository management for Git, Subversion, and Mercurial.  🌎 [Source Code](code.rhodecode.com/)) `AGPL-3.0` `Python`
- 🌎 [SCM Manager](www.scm-manager.org/) - The easiest way to share and manage your Git, Mercurial and Subversion repositories over http. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Source Code](https://github.com/scm-manager/scm-manager)) `BSD-3-Clause` `Java`
- 🌎 [Taiga](taiga.io/) - Agile Project Management Tool based on the Kanban and Scrum methods. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/taigaio)) `AGPL-3.0` `Python`
- 🌎 [Titra](titra.io/) - Time-tracking solution for freelancers and small teams. ( <b><code>&nbsp;&nbsp;&nbsp;292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Source Code](https://github.com/kromitgmbh/titra)) `GPL-3.0` `Javascript`
- 🌎 [Trac](trac.edgewall.org/) - Trac is an enhanced wiki and issue tracking system for software development projects. `BSD-3-Clause` `Python`
- 🌎 [Tuleap](www.tuleap.org/) - Tuleap is a libre suite to plan, track, code and collaborate on software projects.  🌎 [Source Code](tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- 🌎 [UVDesk](www.uvdesk.com/) - UVDesk community is a service oriented, event driven extensible opensource helpdesk system that can be used by your organization to provide efficient support to your clients effortlessly whichever way you imagine.  🌎 [Demo](demo.uvdesk.com/),  <b><code>&nbsp;&nbsp;&nbsp;891⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;298🍴</code></b> [Source Code](https://github.com/uvdesk/community-skeleton)) `MIT` `PHP`
- 🌎 [ZenTao](www.zentao.pm/) - An agile(scrum) project management system/tool.  🌎 [Demo](demo.zentao.pm/user-login.html),  <b><code>&nbsp;&nbsp;&nbsp;866⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;258🍴</code></b> [Source Code](https://github.com/easysoft/zentaopms)) `ZPL-1.2` `PHP`


### Software Development - UX Testing

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;&nbsp;&nbsp;403⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP) - A web server that uses HTTP dumps as a source for responses. `MIT` `Java`
- 🌎 [Selenoid](aerokube.com/selenoid/latest/) - Lightweight Selenium hub implementation launching browsers within Docker containers. ( <b><code>&nbsp;&nbsp;2191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;295🍴</code></b> [Source Code](https://github.com/aerokube/selenoid)) `Apache-2.0` `Go`
- 🌎 [Sorry Cypress](sorry-cypress.dev) - Alternative open-source dashboard for the Cypress browser automation framework, featuring unlimited parallelization, recording and debugging of tests.  🌎 [Demo](sorry-cypress-demo.herokuapp.com),  <b><code>&nbsp;&nbsp;2029⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [Source Code](https://github.com/sorry-cypress/sorry-cypress)) `MIT` `Typescript`
-  <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Uier](https://github.com/sjoerdvanderhoorn/Uier) - Codeless or low-code User Experience test editing and management using Selenium to perform testing or UI automation. Uier tends to be a free self hostable alternative to Applitools, Endtest, Ghost Inspector, Usetrace, Screenster and many others. `Apache-2.0` `Nodejs`


### Static Site Generators

**[`^        back to top        ^`](#)**

**Static site generators are not listed within this list. Please visit 🌎 [staticsitegenerators.net](staticsitegenerators.net), 🌎 [staticgen.com](www.staticgen.com)**


### Status / Uptime pages

**[`^        back to top        ^`](#)**

**Please visit  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [awesome-sysadmin/Status Pages](https://github.com/awesome-foss/awesome-sysadmin#status-pages)**

-  <b><code>&nbsp;&nbsp;1716⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;164🍴</code></b> [cState](https://github.com/cstate/cstate) - Static status page for hyperfast Hugo. Clean design, minimal JS, super light HTML/CSS, high customization, optional admin panel, read-only API, IE8+. Best used with Netlify, Docker.  🌎 [Demo](cstate.mnts.lt/)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [s.Status](https://github.com/scolastico-dev/s.Status) - Open-source server status page written in java. `MPL-2.0` `Java`
-  <b><code>&nbsp;19530⭐</code></b> <b><code>&nbsp;&nbsp;1542🍴</code></b> [Uptime Kuma](https://github.com/louislam/uptime-kuma) - Self-hosted website monitoring tool like "Uptime Robot".  🌎 [Demo](demo.uptime.kuma.pet)) `MIT` `Nodejs`


### Task Management & To-do Lists

**[`^        back to top        ^`](#)**

_Related: [Software Development - Project Management](#software-development---project-management), [Ticketing](#ticketing)_

- 🌎 [Focalboard](www.focalboard.com/) - An open source, self-hosted alternative to Trello, Notion, and Asana. It helps define, organize, track and manage work across individuals and teams. ( <b><code>&nbsp;11693⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;916🍴</code></b> [Source Code](https://github.com/mattermost/focalboard), 🌎 [Clients](www.focalboard.com/download/personal-edition/desktop/)) `MIT/AGPL-3.0/Apache-2.0` `Nodejs/Go`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Kanbana](https://github.com/SrGMC/kanbana) - Create boards to track users and projects from flat markdown files. Forked from Crepido. `MIT` `Nodejs`
- 🌎 [Kanboard](kanboard.org/) - Simple and open source visual task board. ( <b><code>&nbsp;&nbsp;6672⭐</code></b> <b><code>&nbsp;&nbsp;1621🍴</code></b> [Source Code](https://github.com/kanboard/kanboard)) `MIT` `PHP`
- 🌎 [myTinyTodo](www.mytinytodo.net/) - Simple way to manage your todo list in AJAX style. Uses PHP, jQuery, SQLite/MySQL. GTD compliant.  🌎 [Demo](www.mytinytodo.net/demo/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/maxpozdeev/mytinytodo/)) `GPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;2216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [Nullboard](https://github.com/apankrat/nullboard) - Single-page minimalist kanban board; compact, highly readable and quick to use. `BSD-2-Clause` `Javascript`
- 🌎 [Planka](planka.app/) - Open source Trello alternative.  🌎 [Demo](plankanban.github.io/planka/#/),  <b><code>&nbsp;&nbsp;1962⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;201🍴</code></b> [Source Code](https://github.com/plankanban/planka)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Restyaboard](https://github.com/RestyaPlatform/board/) - Open source Trello-like kanban board. `OSL-3.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Task Keeper](https://github.com/nymanjens/piga) - List editor for power users, backed by a self-hosted server. `Apache-2.0` `Scala`
- 🌎 [TaskBoard](taskboard.matthewross.me/) - Kanban-inspired app for keeping track of things that need to get done.  🌎 [Demo](taskboard.matthewross.me/demo.html),  <b><code>&nbsp;&nbsp;1277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;303🍴</code></b> [Source Code](https://github.com/kiswa/TaskBoard)) `MIT` `PHP`
- 🌎 [Taskfreak](www.taskfreak.com/original) - Simple but efficient web based task manager written in PHP. `GPL-3.0` `PHP`
- 🌎 [Taskord](gitlab.com/yo/taskord) - Get things done socially with community of makers. `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [tasks.php](https://github.com/lgg-archive/tasks.php) - Simple task/todo list that uses a JSON text file for the tasks. `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Tasks](https://github.com/m1guelpf/tasks) - Simple tasks and notes manager written in PHP, jQuery and Bootstrap using a custom flat file database. `MPL-2.0` `PHP`
- 🌎 [Taskwarrior](taskwarrior.org/) - Taskwarrior is Free and Open Source Software that manages your TODO list from your command line. It is flexible, fast, efficient, and unobtrusive. It does its job then gets out of your way.  🌎 [Source Code](taskwarrior.org/download/#git)) `MIT` `C++`
- 🌎 [todo](git.mills.io/prologic/todo) - Simple todo list manager.  🌎 [Demo](todo.mills.io)) `MIT` `Go`
- 🌎 [todoMini](www.todomini.app/) - Mobile friendly zero-feature TODO list web app. Unix philosophy.  🌎 [Demo](appmini.github.io/todoMini/?demo),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Source Code](https://github.com/appMini/todoMini)) `GPL-3.0` `PHP/Java`
- 🌎 [Tracks](www.getontracks.org/) - Web-based application to help you implement David Allen’s 🌎 [Getting Things Done™](en.wikipedia.org/wiki/Getting_Things_Done) methodology. ( <b><code>&nbsp;&nbsp;1089⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;547🍴</code></b> [Source Code](https://github.com/TracksApp/tracks)) `GPL-2.0` `Ruby`
- 🌎 [Vikunja](vikunja.io/) - The to-do app to organize your life.  🌎 [Demo](try.vikunja.io/login), 🌎 [Source Code](kolaente.dev/vikunja/)) `GPL-3.0` `Go`
- 🌎 [Wekan](wekan.github.io/) - Open-source Trello-like kanban. ( <b><code>&nbsp;18109⭐</code></b> <b><code>&nbsp;&nbsp;2748🍴</code></b> [Source Code](https://github.com/wekan/wekan)) `MIT` `Nodejs`


### Ticketing

**[`^        back to top        ^`](#)**

_Related: [Task management & To-do lists](#task-management--to-do-lists), [Software Development - Project Management](#software-development---project-management)_

- 🌎 [Bugzilla](www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project. `MPL-2.0` `Perl`
- 🌎 [Bumpy Booby](bumpy-booby.derivoile.fr/) - Simple, responsive and highly customizable PHP bug tracking system. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Source Code](https://github.com/piero-la-lune/Bumpy-Booby)) `MIT` `PHP`
- [django-todo](http://django-todo.org/) - Pluggable, multi-user, multi-group, multi-list todo and ticketing system - a reusable app designed to be dropped into any existing Django project. ( <b><code>&nbsp;&nbsp;&nbsp;704⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [Source Code](https://github.com/shacker/django-todo)) `BSD-3-Clause` `Python/Django`
- 🌎 [Erxes](erxes.io/install/) - Marketing, sales, and customer service platform designed to help businesses attract more engaged customers.  🌎 [Demo](demo.erxes.io/),  <b><code>&nbsp;&nbsp;2196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;884🍴</code></b> [Source Code](https://github.com/erxes/erxes)) `GPL-3.0` `Javascript`
- 🌎 [Flyspray](www.flyspray.org/) - Uncomplicated, web-based bug tracking system. ( <b><code>&nbsp;&nbsp;&nbsp;359⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [Source Code](https://github.com/Flyspray/flyspray)) `GPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;1557⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;296🍴</code></b> [FreeScout](https://github.com/freescout-helpdesk/freescout) - Open source clone of Help Scout: email-based customer support application, help desk and shared mailbox. `AGPL-3.0` `PHP`
- 🌎 [GlitchTip](glitchtip.com) - Open source error-tracking app. GlitchTip collects errors reported by your app.  🌎 [Source Code](gitlab.com/glitchtip/glitchtip)) `MIT` `Python`
- 🌎 [Helpy](helpy.io) - Helpy is a modern, open source helpdesk customer support application. Features include knowledgebase, community discussions and support tickets integrated with email.  🌎 [Demo](demo.helpy.io),  <b><code>&nbsp;&nbsp;2200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;485🍴</code></b> [Source Code](https://github.com/helpyio/helpy)) `MIT` `Ruby`
-  <b><code>&nbsp;&nbsp;1695⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;283🍴</code></b> [HuBoard](https://github.com/huboard/huboard) `⚠` - Instant project management for your GitHub issues (Connects directly GitHub API). `MIT` `Ruby`
- 🌎 [MantisBT](www.mantisbt.org/) - Self hosted bug tracker, fits best for software development.  🌎 [Demo](www.mantisbt.org/bugs/my_view_page.php),  <b><code>&nbsp;&nbsp;1430⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;669🍴</code></b> [Source Code](https://github.com/mantisbt/mantisbt)) `GPL-2.0` `PHP`
- 🌎 [OpenSupports](www.opensupports.com/) - Multi language ticket system with FAQ, role management, metrics and canned response features.  🌎 [Demo](www.opensupports.com/demo/),  <b><code>&nbsp;&nbsp;&nbsp;685⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [Source Code](https://github.com/opensupports/opensupports)) `GPL-3.0` `PHP`
- 🌎 [osTicket](osticket.com/) - Manage, organize and archive all your support requests and responses in one place. ( <b><code>&nbsp;&nbsp;2466⭐</code></b> <b><code>&nbsp;&nbsp;1447🍴</code></b> [Source Code](https://github.com/osTicket/osTicket)) `GPL-2.0` `PHP`
- 🌎 [OTOBO](otobo.de/en/) - Flexible web-based ticketing system used for Customer Service, Help Desk, IT Service Management.  🌎 [Demo](otobo.de/en/open-source-ticketing-system/#demos),  <b><code>&nbsp;&nbsp;&nbsp;143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Source Code](https://github.com/RotherOSS/otobo)) `GPL-3.0` `Perl`
- 🌎 [Pachno](pach.no/) - Bring your team together to design, build and deliver your project with a tool that works with you and your team, and adapts when you need to. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Source Code](https://github.com/pachno/pachno)) `MPL-2.0` `PHP`
- 🌎 [Request Tracker](www.bestpractical.com/rt/) - An enterprise-grade issue tracking system. ( <b><code>&nbsp;&nbsp;&nbsp;676⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;205🍴</code></b> [Source Code](https://github.com/bestpractical/rt)) `GPL-2.0` `Perl`
- 🌎 [Roundup Issue Tracker](www.roundup-tracker.org/) - A simple-to-use and -install issue-tracking system with command-line, web, REST, XML-RPC, and e-mail interfaces. Designed with flexibility in mind - not just another bug tracker.  🌎 [Source Code](www.roundup-tracker.org/code.html)) `MIT/ZPL-2.0` `Python`
- 🌎 [Trudesk](trudesk.io/) - Trudesk is an open-source help desk/ticketing solution. ( <b><code>&nbsp;&nbsp;&nbsp;834⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;335🍴</code></b> [Source Code](https://github.com/polonel/trudesk)) `Apache-2.0` `Nodejs`
- 🌎 [Zammad](zammad.org/) - Easy to use but powerful open-source support and ticketing system. ( <b><code>&nbsp;&nbsp;3066⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;597🍴</code></b> [Source Code](https://github.com/zammad/zammad)) `AGPL-3.0` `Ruby`


### Time Trackers

**[`^        back to top        ^`](#)**

- 🌎 [ActivityWatch](activitywatch.net) - An app that automatically tracks how you spend time on your devices. ( <b><code>&nbsp;&nbsp;6938⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;335🍴</code></b> [Source Code](https://github.com/ActivityWatch/activitywatch)) `MPL-2.0` `Python`
- 🌎 [Kimai](www.kimai.org/) - Kimai is a free & open source timetracker. It tracks work time and prints out a summary of your activities on demand.  🌎 [Demo](www.kimai.org/demo/),  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Source Code](https://github.com/kevinpapst/kimai2/)) `MIT` `PHP`
- 🌎 [TimeTagger](timetagger.app) - An open source time-tracker based on an interactive timeline and powerful reporting.  🌎 [Demo](timetagger.app/app/demo),  <b><code>&nbsp;&nbsp;&nbsp;485⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Source Code](https://github.com/almarklein/timetagger)) `GPL-3.0` `Python`


### URL Shorteners

**[`^        back to top        ^`](#)**

Before hosting one, please see 🌎 [shortcomings](en.wikipedia.org/wiki/URL_shortening#Shortcomings) of URL shorteners.

- 🌎 [Blink](docs.blink.rest) - Easy-to-host, SSO-integrated, CDN-powered link shortener (+decoupled analytics) for teams. ( <b><code>&nbsp;&nbsp;&nbsp;129⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Source Code](https://github.com/JaneJeon/blink)) `AGPL-3.0` `Nodejs`
- 🌎 [goshorly](git.ucode.space/Phil/goshorly) - An easy self-hosted Link shortener in Golang with Redis <3. `MIT` `Go`
- 🌎 [Kutt](kutt.it) - A modern URL shortener with support for custom domains. ( <b><code>&nbsp;&nbsp;6086⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;715🍴</code></b> [Source Code](https://github.com/thedevs-network/kutt)) `MIT` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [liteshort](https://github.com/132ikl/liteshort) - User-friendly, actually lightweight, and configurable URL shortener.  🌎 [Demo](ls.ikl.sh)) `MIT` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Lstu](https://github.com/ldidry/lstu) - Lightweight URL shortener. `WTFPL` `Perl`
- 🌎 [Polr](project.polr.me/) - Modern, minimalist, modular, and lightweight URL shortener. ( <b><code>&nbsp;&nbsp;4413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;821🍴</code></b> [Source Code](https://github.com/Cydrobolt/polr)) `GPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [reduc.io](https://github.com/ziyasal/reducio) - URL shortener service written in Scala, using Akka-Http and Redis. `MIT` `Scala`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [ReducePy](https://github.com/abdullahselek/ReducePy) - URL shortener service using Tornado and Redis runs on Docker and Kubernetes. `MIT` `Python`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [schort](https://github.com/sqozz/schort) - No login, no javascript, just short links. `CC0-1.0` `Python`
- 🌎 [Shlink](shlink.io) - URL shortener with REST API and command line interface. Includes official progressive web application and docker images. ( <b><code>&nbsp;&nbsp;1478⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [Source Code](https://github.com/shlinkio/shlink), 🌎 [Clients](shlink.io/apps)) `MIT` `PHP`
- 🌎 [shorturl](git.mills.io/prologic/shorturl) - Simple URL shortener with very tiny URLs.  🌎 [Demo](url.mills.io)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener) - KISS URL shortener, public or private (with account). Minimalist and lightweight. No dependencies.  🌎 [Demo](u.azlux.fr)) `MIT` `PHP`
- 🌎 [Simply Shorten](gitlab.com/draganczukp/simply-shorten) - A simple URL shortener that just shortens links. `MIT` `Java`
-  <b><code>&nbsp;&nbsp;&nbsp;160⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [url-shortener](https://github.com/cagataycali/url-shortener) `⚠` - Shitty url shortener, emoji and AI powered. `MIT` `Nodejs`
- 🌎 [YOURLS](yourls.org/) - YOURLS is a set of PHP scripts that will allow you to run Your Own URL Shortener. Features include password protection, URL customization, bookmarklets, statistics, API, plugins, jsonp. ( <b><code>&nbsp;&nbsp;8264⭐</code></b> <b><code>&nbsp;&nbsp;1730🍴</code></b> [Source Code](https://github.com/YOURLS/YOURLS)) `MIT` `PHP`


### VPN

**[`^        back to top        ^`](#)**

**Please visit  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [awesome-sysadmin/VPN](https://github.com/awesome-foss/awesome-sysadmin#vpn)**


### Web Servers

**[`^        back to top        ^`](#)**

**Please visit  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [awesome-sysadmin/Web](https://github.com/awesome-foss/awesome-sysadmin#web)**


### Wikis

**[`^        back to top        ^`](#)**

_Related: [Static site generators](#static-site-generators)_

_See also: 🌎 [Wikimatrix](www.wikimatrix.org/), 🌎 [Wiki Engines - WikiIndex](wikiindex.org/Category:Wiki_Engine), 🌎 [List of wiki software - Wikipedia](en.wikipedia.org/wiki/List_of_wiki_software), 🌎 [Comparison of wiki software - Wikipedia](en.wikipedia.org/wiki/Comparison_of_wiki_software)_

- 🌎 [BookStack](www.bookstackapp.com/) - BookStack is a simple, self-hosted, easy-to-use platform for organizing and storing information. It allows for documentation to be stored in a book like fashion.  🌎 [Demo](www.bookstackapp.com/#demo),  <b><code>&nbsp;&nbsp;9712⭐</code></b> <b><code>&nbsp;&nbsp;1329🍴</code></b> [Source Code](https://github.com/BookStackApp/BookStack)) `MIT` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;818⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [Cowyo](https://github.com/schollz/cowyo) - Cowyo is a feature-rich wiki for minimalists.  🌎 [Demo](cowyo.com)) `MIT` `Go`
-  <b><code>&nbsp;&nbsp;1553⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;535🍴</code></b> [django-wiki](https://github.com/django-wiki/django-wiki) - Wiki system with complex functionality for simple integration and a superb interface. Store your knowledge with style: Use django models.  🌎 [Demo](demo.django-wiki.org/)) `GPL-3.0` `Python`
- 🌎 [Documize](documize.com) - Modern Docs + Wiki software with built-in workflow, single binary executable, just bring MySQL/Percona. ( <b><code>&nbsp;&nbsp;1619⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;168🍴</code></b> [Source Code](https://github.com/documize/community)) `AGPL-3.0` `Go`
- 🌎 [Dokuwiki](www.dokuwiki.org/DokuWiki) - Easy to use, lightweight, standards-compliant wiki engine with a simple syntax allowing reading the data outside the wiki. All data is stored in plain files, therefore no database is required. ( <b><code>&nbsp;&nbsp;3473⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;776🍴</code></b> [Source Code](https://github.com/splitbrain/dokuwiki)) `GPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;2016⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;215🍴</code></b> [Gitit](https://github.com/jgm/gitit) - Wiki program that stores pages and uploaded files in a git repository, which can then be modified using the VCS command line tools or the wiki's web interface. `GPL-2.0` `Haskell`
-  <b><code>&nbsp;12700⭐</code></b> <b><code>&nbsp;&nbsp;1593🍴</code></b> [Gollum](https://github.com/gollum/gollum) - Simple, Git-powered wiki with a sweet API and local frontend. `MIT` `Ruby`
-  <b><code>&nbsp;&nbsp;1017⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [jingo](https://github.com/claudioc/jingo) - Git based wiki engine written for node.js, with a decent design, a search capability and good typography. `MIT` `Nodejs`
- 🌎 [Mediawiki](www.mediawiki.org/wiki/MediaWiki) - MediaWiki is a free and open-source wiki software package written in PHP. It serves as the platform for Wikipedia and the other Wikimedia projects, used by hundreds of millions of people each month.  🌎 [Demo](en.wikipedia.org/wiki/Main_Page), 🌎 [Source Code](phabricator.wikimedia.org/diffusion/MW/)) `GPL-2.0` `PHP`
- 🌎 [MoinMoin](moinmo.in/) - Advanced, easy to use and extensible WikiEngine with a large community of users. ( <b><code>&nbsp;&nbsp;&nbsp;125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Source Code](https://github.com/moinwiki/moin-1.9)) `GPL-2.0` `Python`
- 🌎 [Outline](www.getoutline.com/) `⚠` - An open, extensible, wiki for your team. ( <b><code>&nbsp;16024⭐</code></b> <b><code>&nbsp;&nbsp;1364🍴</code></b> [Source Code](https://github.com/outline/outline)) `BSD-3-Clause` `Nodejs`
-  <b><code>&nbsp;&nbsp;&nbsp;124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Pepperminty Wiki](https://github.com/sbrl/Pepperminty-Wiki) - Complete markdown-powered wiki contained in a single PHP file.  🌎 [Demo](starbeamrainbowlabs.com/labs/peppermint/build/)) `MPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [PineDocs](https://github.com/xy2z/PineDocs) - Simple, fast, customizable and lightweight site for browsing files. `GPL-3.0` `PHP`
- 🌎 [PmWiki](www.pmwiki.org) - Wiki-based system for collaborative creation and maintenance of websites. `GPL-3.0` `PHP`
- [Raneto](http://raneto.com/) - Raneto is an open source Knowledgebase platform that uses static Markdown files to power your Knowledgebase. `MIT` `Nodejs`
- 🌎 [TiddlyWiki](tiddlywiki.com/) - Reusable non-linear personal web notebook. ( <b><code>&nbsp;&nbsp;6858⭐</code></b> <b><code>&nbsp;&nbsp;1077🍴</code></b> [Source Code](https://github.com/Jermolene/TiddlyWiki5)) `BSD-3-Clause` `Nodejs`
- 🌎 [Tiki](tiki.org) - Wiki CMS Groupware with the most built-in features.  🌎 [Demo](tiki.org/Demo), 🌎 [Source Code](sourceforge.net/p/tikiwiki/code/HEAD/tree/)) `LGPL-2.1` `PHP`
- 🌎 [TWiki](twiki.org/) - TWiki is a Perl-based structured wiki application, typically used to run a collaboration platform, knowledge or document management system, a knowledge base, or team portal.  🌎 [Demo](twiki.org/cgi-bin/view/Sandbox/WebHome), [Source Code](http://svn.twiki.org/svn/twiki/)) `GPL-1.0` `Perl`
- 🌎 [WackoWiki](wackowiki.org/) - WackoWiki is a light and easy to install multilingual Wiki-engine. ( <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Source Code](https://github.com/WackoWiki/wackowiki)) `BSD-3-Clause` `PHP`
- 🌎 [Wiki.js](wiki.js.org/) - Modern, lightweight and powerful wiki app using Git and Markdown.  🌎 [Demo](docs.requarks.io),  <b><code>&nbsp;18133⭐</code></b> <b><code>&nbsp;&nbsp;2015🍴</code></b> [Source Code](https://github.com/Requarks/wiki)) `AGPL-3.0` `Nodejs`
- 🌎 [wiki](git.mills.io/prologic/wiki) - Simple Markdown based wiki engine.  🌎 [Demo](wiki.mills.io)) `MIT` `Go`
- 🌎 [WiKiss](wikiss.tuxfamily.org/) - Wiki, simple to use and install.  🌎 [Source Code](svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
-  <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Wikmd](https://github.com/Linbreux/wikmd) - Modern and simple file based wiki that uses Markdown and Git. `MIT` `Python`
- 🌎 [XWiki](www.xwiki.org) - Second generation wiki that allows the user to extend its functionalities with a powerful extension-based architecture.  🌎 [Demo](playground.xwiki.org),  <b><code>&nbsp;&nbsp;&nbsp;724⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;414🍴</code></b> [Source Code](https://github.com/xwiki/xwiki-platform)) `LGPL-2.1` `Java`
- 🌎 [Zim](zim-wiki.org/) - Graphical text editor used to maintain a collection of wiki pages. Each page can contain links to other pages, simple formatting and images. ( <b><code>&nbsp;&nbsp;1549⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;317🍴</code></b> [Source Code](https://github.com/zim-desktop-wiki/zim-desktop-wiki)) `GPL-2.0` `Python`

--------------------

## List of Licenses

**[`^        back to top        ^`](#)**

- `0BSD` - 🌎 [BSD Zero-Clause Licence](opensource.org/licenses/0BSD)
- `AAL` - 🌎 [Attribution Assurance License](opensource.org/licenses/AAL)
- `AGPL-3.0` - 🌎 [GNU Affero General Public License 3.0](www.gnu.org/licenses/agpl-3.0)
- `AGPL-3.0-only` - 🌎 [GNU Affero General Public License 3.0 only](spdx.org/licenses/AGPL-3.0-only.html)
- `Apache-2.0` - 🌎 [Apache, Version 2.0](www.apache.org/licenses/)
- `APSL-2.0` - 🌎 [Apple Public Source License, Version 2.0](opensource.org/licenses/APSL-2.0)
- `Artistic-2.0` - 🌎 [Artistic License Version 2.0](opensource.org/licenses/Artistic-2.0)
- `Beerware` - 🌎 [Beerware License](spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - 🌎 [BSD 2-clause "Simplified"](opensource.org/licenses/BSD-2-Clause)
- `BSD-2-Clause-FreeBSD` - 🌎 [BSD 2-Clause FreeBSD License](www.freebsd.org/copyright/freebsd-license.html)
- `BSD-3-Clause` - 🌎 [BSD 3-Clause "New" or "Revised"](opensource.org/licenses/BSD-3-Clause)
- `BSD-3-Clause-Attribution` - 🌎 [BSD with attribution](fedoraproject.org/wiki/Licensing/BSD_with_Attribution)
- `BSD-4-Clause` - 🌎 [BSD 4-clause "Original"](spdx.org/licenses/BSD-4-Clause.html)
- `CC-BY-SA-3.0` - 🌎 [Creative Commons Attribution-ShareAlike 3.0 International License](creativecommons.org/licenses/by-sa/3.0/)
- `CC-BY-SA-4.0` - 🌎 [Creative Commons Attribution-ShareAlike 4.0 International License](creativecommons.org/licenses/by-sa/4.0/)
- `CC0-1.0` - 🌎 [Public Domain](creativecommons.org/about/cc0/)
- `CDDL-1.0` - 🌎 [Common Development and Distribution License](opensource.org/licenses/CDDL-1.0)
- `CECILL-B` - 🌎 [CEA CNRS INRIA Logiciel Libre](spdx.org/licenses/CECILL-B.html)
- `CPAL-1.0` - 🌎 [Common Public Attribution License Version 1.0](opensource.org/licenses/CPAL-1.0)
- `ECL-2.0` - 🌎 [Educational Community License, Version 2.0](opensource.org/licenses/ECL-2.0)
- `EPL-1.0` - 🌎 [Eclipse Public License, Version 1.0](www.eclipse.org/legal/epl-v10.html)
- `EPL-2.0` - 🌎 [Eclipse Public License, Version 2.0](www.eclipse.org/legal/epl-v20.html)
- `EUPL-1.2` - 🌎 [European Union Public License 1.2](joinup.ec.europa.eu/collection/eupl/eupl-text-11-12)
- `GFDL-1.1-only` - 🌎 [GNU Free Documentation License v1.1](spdx.org/licenses/GFDL-1.1-only.html)
- `GFDL-1.1-or-later` - 🌎 [GNU Free Documentation License v1.1](spdx.org/licenses/GFDL-1.1-or-later.html)
- `GFDL-1.2-only` - 🌎 [GNU Free Documentation License v1.2](spdx.org/licenses/GFDL-1.2-only.html)
- `GFDL-1.2-or-later` - 🌎 [GNU Free Documentation License v1.2](spdx.org/licenses/GFDL-1.2-or-later.html)
- `GFDL-1.3-only` - 🌎 [GNU Free Documentation License v1.3](spdx.org/licenses/GFDL-1.3-only.html)
- `GFDL-1.3-or-later` - 🌎 [GNU Free Documentation License v1.3](spdx.org/licenses/GFDL-1.3-or-later.html)
- `GPL-1.0` - 🌎 [GNU General Public License](www.gnu.org/licenses/gpl-1.0)
- `GPL-2.0` - 🌎 [GNU General Public License 2.0](www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
- `GPL-2.0-or-later` - 🌎 [GNU General Public License v2.0 or later](spdx.org/licenses/GPL-2.0-or-later.html)
- `GPL-3.0-only` - 🌎 [GNU General Public License v3.0 only](spdx.org/licenses/GPL-3.0-only.html)
- `GPL-3.0-or-later` - 🌎 [GNU General Public License v3.0 or later](spdx.org/licenses/GPL-3.0-or-later.html)
- `GPL-3.0` - 🌎 [GNU General Public License 3.0](www.gnu.org/licenses/gpl-3.0.en.html)
- `IPL-1.0` - 🌎 [IBM Public License](opensource.org/licenses/IPL-1.0)
- `ISC` - 🌎 [Internet Systems Consortium License](www.isc.org/downloads/software-support-policy/isc-license/)
- `LIL-1.0` - 🌎 [The Lil License v1](www.lillicense.org/v1.html)
- `LGPL-2.1` - 🌎 [Lesser General Public License 2.1](opensource.org/licenses/LGPL-2.1)
- `LGPL-3.0` - 🌎 [Lesser General Public License 3.0](opensource.org/licenses/LGPL-3.0)
- `MIT` - 🌎 [MIT License](opensource.org/licenses/MIT)
- `MPL-1.1` - 🌎 [Mozilla Public License Version 1.1](www.mozilla.org/media/MPL/1.1/index.txt)
- `MPL-2.0` - 🌎 [Mozilla Public License](www.mozilla.org/MPL/2.0/index.txt)
- `OSL-3.0` - 🌎 [Open Software License 3.0](opensource.org/licenses/osl-3.0.php)
- `Sendmail` - 🌎 [Sendmail License](www.sendmail.com/pdfs/open_source/sendmail_license.pdf)
- `Unlicense` - 🌎 [The Unlicense](unlicense.org/)
- `WTFPL` - [Do What the Fuck You Want to Public License](http://www.wtfpl.net/about/)
- `Zlib` - 🌎 [Zlib/libpng License](opensource.org/licenses/Zlib)
- `ZPL-1.2` - [Zope Public License 1.2](http://zpl.pub/page/zplv12)
- `ZPL-2.0` - 🌎 [Zope Public License 2.0](opensource.org/licenses/ZPL-2.0)


--------------------

## Anti-features

- `⚠ ` - Depends on a proprietary service outside the user's control

--------------------

## External Links

**[`^        back to top        ^`](#)**

-  <b><code>&nbsp;11041⭐</code></b> <b><code>&nbsp;&nbsp;2432🍴</code></b> [Awesome Big Data](https://github.com/0xnr/awesome-bigdata) - Curated list of awesome big data frameworks, resources and other awesomeness.
-  <b><code>&nbsp;49685⭐</code></b> <b><code>&nbsp;&nbsp;8780🍴</code></b> [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) - List of high quality, topic-centric public data sources.
-  <b><code>&nbsp;14489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;954🍴</code></b> [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - Curated list of amazingly awesome open source sysadmin resources.
- Lists of software aimed at privacy and decentralization in some form: 🌎 [PRISM Break](prism-break.org/en/), 🌎 [privacytools.io](www.privacytools.io/), 🌎 [Alternative Internet](redecentralize.github.io/alternative-internet/), 🌎 [Libre Projects](libreprojects.net/)
- 🌎 [Easy Indie App](easyindie.app) - Apps that can be self-hosted in a few clicks.
- Dynamic Domain Name services: 🌎 [Afraid.org](freedns.afraid.org/domain/registry/), 🌎 [Pagekite](pagekite.net/)
- Communities/forums: 🌎 [/r/selfhosted](www.reddit.com/r/selfhosted), 🌎 [IndieWeb](indieweb.org/)
- Mirrors: [GitHub.com](https://github.com/correia-jpv/fucking-awesome-selfhosted), 🌎 [Gitlab.com](gitlab.com/awesome-selfhosted/awesome-selfhosted)
- 🌎 [Track Awesome Selfhosted](www.trackawesomelist.com/awesome-selfhosted/awesome-selfhosted/) - Get the latest updates of awesome-selfhosted.

--------------------

## Contributing

Contributing guidelines can be found in [.github/CONTRIBUTING.md](.github/CONTRIBUTING.md).

## Authors

The list of authors can be found in [AUTHORS.md](AUTHORS.md).

## License

This list is under the [Creative Commons Attribution-ShareAlike 3.0 Unported](LICENSE) License.
