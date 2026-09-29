# Awesome-Broadcast-Management

## Top Broadcast Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Broadcast Automation, Traffic Scheduling & Media Asset Management*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Broadcast Management**. These tools manage program scheduling, traffic and billing, media asset management, playout automation, and live production workflows for radio stations, television broadcasters, and streaming operations.



**Examples** include WideOrbit, Imagine Communications, Marketron, TrafficLive, BroadView, Myriad Playout, Radio.co, RCS Zetta, ENCO DAD, and PlayBox Neo (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom broadcast automation, and transparent media workflows — ideal for community radio stations, television broadcasters, and developers building vendor-independent broadcast solutions. The open-source ecosystem for radio automation is notably mature, with production-grade systems deployed in real broadcast environments worldwide.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[WideOrbit](https://www.wideorbit.com/)**  

  Comprehensive broadcast management platform covering traffic, billing, sales, and program scheduling for radio and television.



- **[Imagine Communications](https://www.imaginecommunications.com/)**  

  Broadcast and media software solutions covering playout, automation, and advertising management.



- **[Marketron](https://marketron.com/)**  

  Radio and television traffic, billing, and revenue management platform for broadcasters.



- **[TrafficLive](https://www.trafficlive.com/)**  

  Cloud-based traffic and scheduling system for radio and television broadcasters.



- **[BroadView](https://www.broadviewsoftware.com/)**  

  Broadcast management software for traffic, billing, and scheduling.



- **[Myriad Playout](https://www.myriadplayout.com/)**  

  Radio playout and automation software with scheduling, music rotation, and live assist capabilities.



- **[Radio.co](https://radio.co/)**  

  Cloud-based radio broadcasting platform with automation, scheduling, and streaming.



- **[RCS Zetta](https://www.rcsworks.com/)**  

  Radio automation and playout system with scheduling, music rotation, and live production tools.



- **[ENCO DAD](https://www.enco.com/)**  

  Radio and television automation system with playout, scheduling, and live assist capabilities.



- **[PlayBox Neo](https://www.playboxneo.com/)**  

  Broadcast playout and channel-in-a-box solutions for television operations.



## Open-Source GitHub Projects



- **[Rivendell](https://github.com/ElvishArtisan/rivendell)**  

  A full-featured radio automation system targeted for use in professional broadcast and media environments, with 224+ stars on GitHub . Provides a complete suite of tools including RDAdmin for administration, RDLibrary for production audio, RDCatch for automatic recording, RDLogEdit for air log creation, RDLogManager for automatic log generation from templates, and RDAirPlay for on-air playout . Supports importation of schedule information from third-party traffic and music scheduling systems, and includes podcast posting via RDCastManager. GPL licensed with active development.



- **[LibreTime](https://github.com/libretime/libretime)**  

  Radio Broadcast & Automation Platform, a community-maintained fork of Airtime with 941+ stars and AGPL-3.0 license . PHP-based with Liquidsoap for audio playout, supporting scheduled playlists, live shows, and remote contribution. Actively maintained with recent commits as of August 2026.



- **[OpenBroadcaster](https://github.com/openbroadcaster/)**  

  Broadcast automation and emergency alerting platform with two main components: OBServer for automation, scheduling, media library, and player management, and OBPlayer for streaming automation playout with CAP EAS Alerting . Used in production by community broadcasters including New North Networks, Tellie TV, CJUC Radio Whitehorse, and Nuxalk Radio . AGPL-3.0 licensed with 185+ stars on OBServer and 143+ on OBPlayer.



- **[Nebula](https://github.com/nebulabroadcast/nebula)**  

  Open-source broadcast automation and media asset management system for television, radio, and VOD platforms, with 214+ stars and active development . In production since 2012 and used by TV and production companies worldwide including Czech Television, Sport 5, Radio Free Europe, and Hope TV . Features EBU Core-compliant media catalog, automatic low-res proxy transcoding, linear scheduling with drag-and-drop, playout control for CasparCG, and publishing to web/social platforms. Python/React based with Docker deployment.



- **[Sofie TV Automation](https://github.com/Sofie-Automation/Sofie-TV-automation)**  

  Web-based TV automation system for studios and live shows, used in daily live TV news productions by Norwegian public service broadcaster NRK since September 2018 . Also deployed at BBC and TV 2 Norway . Features state-based device control for video, audio, and graphics; modular device-control and data-ingest architecture with MOS and Google Spreadsheets support; and plugin architecture for programming shows. 313+ stars on GitHub .



- **[XFB](https://github.com/netpack/XFB)**  

  Cross-platform, open-source radio automation suite for broadcasters, GPL-3.0 licensed . Features scheduled playlists, jingle and advertising rotation, a live audio FX engine (10-band equalizer, compressor, tempo-preserving reference-pitch retuning), DJ decks with scratchable jog wheels, Icecast/Shoutcast streaming client, playlist waveform views with crossfade preparation, gapless playback, and comprehensive accessibility support including screen-reader integration and full keyboard navigation. Qt-based for cross-platform deployment.



- **[Autoradio](https://sources.debian.org/src/autoradio/)**  

  Radio automation software designed to be simple to use, starting from digital audio files to manage on-air broadcasting over a radio station or web-radio . Features integrated GStreamer or external Xmms/Audacious player, real-time manager for jingles, spots, playlist and programs, and a web interface to monitor the player and scheduler and admin schedules. Supports podcast publishing conforming to RSS 2.0 and iTunes RSS specifications. GNU GPL v2 licensed.



- **[Radiotomate](https://sr.ht/~martink/radiotomate/)**  

  Radio automation in a web app for community radios, currently in active development (work in progress) . Python-based with Liquidsoap for playout, featuring a web interface, scheduler API, and support for jingles cart and music library management. Requires Linux, Poetry, Liquidsoap, and npm for development deployment.



- **[EXStreamTV](https://github.com/roto31/EXStreamTV)**  

  Platform that creates custom live TV channels from online sources (YouTube, Archive.org) and local media (Plex, Jellyfin, Emby, local folders) . Emulates HDHomeRun for Plex DVR discovery and tuning, provides M3U/EPG for IPTV players, and features hardware transcoding (NVENC, QSV, VAAPI, VideoToolbox, AMF), advanced scheduling with block scheduling and templates, and session management with throttling. Python-based with macOS menu bar app and Docker support.



- **[Dispatcharr](https://www.myqnap.org/product/dispatcharr-qmultimedia-q6-postgresql17/)**  

  Open-source powerhouse for managing IPTV streams, EPG data, and VOD content . Consolidates multiple IPTV sources, integrates with media centers via HDHomeRun emulation, merges live TV with custom EPG guides, supports FFmpeg transcoding for output profiles, and centralizes VPN access. Features real-time monitoring, automatic failover, multi-user accounts with granular permissions, and plugin system for custom integrations.



### Additional Strong Open-Source Options



- **Comrad** — Open-source web application for radio stations to manage show schedules, traffic and compliance .

- **django-radio / RadioCo** — Radio management application for easy scheduling, live recording, and publishing .

- **Vinyl** — Pending evolution for how campus and community radio manage and interact with their music libraries .

- **CasparCG Server** — Open-source playout server developed at SVT (Sweden), in 24/7 broadcast operation since 2006, used or evaluated by SVT, BBC, DR, NRK, and VRT .



**Frameworks for building custom broadcast management solutions**: For professional radio automation, **Rivendell** provides the most complete open-source suite with full production, scheduling, and playout workflow . For television broadcast automation, **Nebula** offers production-grade MAM and playout control with real-world deployments . For live TV studio automation, **Sofie** provides state-based device control used by NRK and BBC . For community radio, **LibreTime** or **OpenBroadcaster** offer accessible starting points . For IPTV and streaming channel creation, **EXStreamTV** and **Dispatcharr** provide modern web-based platforms .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Broadcast management tools must comply with broadcasting regulations, music licensing requirements (ASCAP, BMI, SESAC, etc.), and emergency alerting standards.

- Self-hosted open-source solutions require proper infrastructure, audio hardware configuration, and ongoing maintenance. Broadcast environments demand high reliability and disaster recovery planning.



---



**Made for radio stations, television broadcasters, community media, and broadcast engineers.**  

Let's make broadcast management more open, transparent, and accessible.
