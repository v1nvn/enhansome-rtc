# Awesome Real Time Communications [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

> Protocols and methodology for near simultaneous exchange of media and data.

## Contents

* [Server Software](#server-software)
  * [General Purpose](#general-purpose)
  * [SIP Servers](#sip-servers)
  * [Media Servers](#media-servers)
  * [STUN/TURN](#stunturn)
* [Operations](#operations)
  * [Monitoring](#monitoring)
  * [Testing](#testing)
  * [Deployment](#deployment)
  * [Web/API Interfaces](#webapi-interfaces)
  * [Billing](#billing)
* [Developer Resources](#developer-resources)
  * [Tutorials](#tutorials)
  * [JavaScript Libraries](#javascript-libraries)
  * [C/C++ Libraries](#cc-libraries)
  * [Go Libraries](#go-libraries)
  * [PHP Libraries](#php-libraries)
  * [Python Libraries](#python-libraries)
  * [Erlang Libraries](#erlang-libraries)
  * [Rust Libraries](#rust-libraries)
  * [Dart Libraries](#dart-libraries)
* [Blogs](#blogs)
* [Discussion](#discussion)
* [Events](#events)
* [Related Lists](#related-lists)
* [Contribute](#contribute)

## Server Software

### General Purpose

* [FreeSWITCH](http://freeswitch.org) - Open source multi-protocol, cross-platform and software switch.
* [Asterisk](http://asterisk.org) - PBX framework supporting multiple protocols and platforms.

### SIP Servers

* [Sippy B2BUA](https://github.com/sippy/b2bua) ⭐ 195 | 🐛 28 | 🌐 Python | 📅 2026-02-26 - Back-to-back user agent server written in Python.
* [Flexisip](https://github.com/BelledonneCommunications/flexisip) ⭐ 177 | 🐛 21 | 🌐 C++ | 📅 2026-03-03 - SIP server suite comprising proxy, presence and group chat functions.
* [Kamailio](http://www.kamailio.org) - Open source SIP server widely deployed by carriers and providers. Formerly known as OpenSER.
* [OpenSIPS](http://www.opensips.org) - Open source SIP server, tracing its roots in OpenSER (presently Kamailio).
* [Routr](https://routr.io) - Lightweight SIP proxy, location server, and registrar written in Node.js.

### Media Servers

* [RTP:Engine](https://github.com/sipwise/rtpengine) ⭐ 915 | 🐛 113 | 🌐 C | 📅 2026-03-06 - RTP and UDP based media traffic proxy, usable as a kernel module.
* [SEMS](https://github.com/sems-server/sems) ⭐ 182 | 🐛 10 | 🌐 C++ | 📅 2026-03-04 - Open source media and application server for SIP based VoIP services.
* [Janus](https://janus.conf.meetecho.com) - Lightweight open source, general purpose, WebRTC gateway.
* [LiveKit](https://livekit.io) - Open-source WebRTC infrastructure for building scalable real-time audio and video applications.
* [RTPProxy](https://www.rtpproxy.org) - General purpose high performance RTP proxy.
* [mediasoup](https://mediasoup.org) - Specialized WebRTC conferencing system.
* [Jitsi](https://jitsi.org/projects) - A collection of RTC open source projects, with a focus on conferencing software.

### STUN/TURN

* [coturn](https://github.com/coturn/coturn) ⭐ 13,694 | 🐛 378 | 🌐 C | 📅 2026-03-07 - Fully featured TURN/STUN server supporting multiple platforms.
* [STUNTMAN](https://github.com/jselbie/stunserver) ⭐ 1,587 | 🐛 12 | 🌐 C++ | 📅 2026-02-13 - RFC compliant open source STUN implementation.

  ## Operations
* [eturnal](https://eturnal.net/) - Modern and scalable STUN/TURN server written in Erlang.

### Monitoring

* [HOMER](https://github.com/sipcapture/homer) ⭐ 1,908 | 🐛 44 | 🌐 Shell | 📅 2026-02-10 - Multi-protocol capturing and monitoring framework for RTC.
* [sngrep](https://github.com/irontec/sngrep) ⭐ 1,166 | 🐛 77 | 🌐 C | 📅 2026-01-26 - Terminal based SIP flow viewer.
* [WebRTC Troubleshooter](https://github.com/webrtc/testrtc) ⚠️ Archived - Self-hosted one stop client-side WebRTC troubleshooter.
* [sipgrep](https://github.com/sipcapture/sipgrep) ⭐ 172 | 🐛 6 | 🌐 C | 📅 2025-09-10 - Console tool for sniffing, capturing and exploring SIP traffic.
* [rtpbreak](https://github.com/Naishy/rtpsplit) ⭐ 22 | 🐛 0 | 🌐 C | 📅 2017-02-02 - Detect, reconstruct and analyze RTP sessions.
* [Trickle ICE](https://webrtc.github.io/samples/src/content/peerconnection/trickle-ice) - Exposes client-side NAT traversal debug data.
* [SIP3](https://sip3.io) - VoIP & RTC traffic monitoring and analysis platform.

### Testing

* [SIPVicious](https://github.com/EnableSecurity/sipvicious) ⭐ 1,046 | 🐛 0 | 🌐 Python | 📅 2026-03-06 - Suite of security tools that can be used to audit SIP based VoIP systems.
* [sipexer](https://github.com/miconda/sipexer) ⭐ 379 | 🐛 2 | 🌐 Go | 📅 2026-01-05 - Modern and flexible SIP command line tool.
* [sipsak](https://github.com/nils-ohlmeier/sipsak) ⭐ 170 | 🐛 24 | 🌐 C | 📅 2025-05-26 - SIP stress and diagnostics utility.
* [SIPp](http://sipp.sourceforge.net) - Traffic generator for the SIP protocol.

### Deployment

* [slimswitch](https://github.com/rtckit/slimswitch) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2023-11-28 - Tooling for creating lean secure FreeSWITCH Docker images.

### Web/API Interfaces

* [Fonoster](https://github.com/fonoster/fonoster) ⭐ 7,708 | 🐛 15 | 🌐 TypeScript | 📅 2026-02-28 - Telecommunication stack built with Node.js.
* [IVOZ Provider](https://github.com/irontec/ivozprovider) ⭐ 221 | 🐛 89 | 🌐 PHP | 📅 2026-03-06 - Multitenant solution for VoIP telephony providers.
* [Sayna](https://github.com/SaynaAI/sayna) ⭐ 157 | 🐛 0 | 🌐 Rust | 📅 2026-02-08 - Real-time speech infrastructure for voice AI with WebSocket streaming, SIP telephony and pluggable STT/TTS providers.
* [Eqivo](https://eqivo.org) - Open source programmable-voice/telephony API platform.
* [Kazoo](https://www.2600hz.org) - Carrier-grade VoIP API platform using FreeSWITCH and Kamailio.
* [FusionPBX](https://www.fusionpbx.com) - Multitenant system built on top of FreeSWITCH.
* [FreePBX](https://www.freepbx.org) - Web Manager for Asterisk.
* [Wazo](https://wazo-platform.org) - VoIP API platform built on top of Asterisk, Kamailio and RTPEngine.
* [jambonz](https://www.jambonz.org) - Open source CPaaS built for communications service providers.

### Billing

* [CGRateS](http://cgrates.org) - Carrier grade open source billing/rating server.
* [A2Billing](http://www.asterisk2billing.org) - Billing system for Asterisk for multiple applications.
* [PyFreeBilling](https://github.com/mwolff44/pyfreebilling) ⭐ 110 | 🐛 5 | 🌐 Shell | 📅 2026-03-07 - Wholesale billing platform for Kamailio and FreeSWITCH.

## Developer Resources

### Tutorials

* [Official Website](https://webrtc.org) - Entry level WebRTC resources.
* [Getting Started With WebRTC](https://www.html5rocks.com/en/tutorials/webrtc/basics) - WebRTC tutorial by HTML5 Rocks.
* [WebRTC Samples](https://webrtc.github.io/samples) - Collection of samples demonstrating various parts of the WebRTC APIs.
* [WebRTC Experiments](https://www.webrtc-experiment.com) - Comprehensive list of samples by Muaz Khan.
* [Interactive Codelab](https://codelabs.developers.google.com/codelabs/webrtc-web) - 30 minutes step by step live tutorial by Google.

### JavaScript Libraries

* [simple-peer](https://github.com/feross/simple-peer) ⭐ 7,791 | 🐛 127 | 🌐 JavaScript | 📅 2024-06-26 - WebRTC video, voice, and data channels abstraction for Node.js and the browser.
* [adapter.js](https://github.com/webrtcHacks/adapter) ⭐ 3,738 | 🐛 10 | 🌐 JavaScript | 📅 2026-03-07 - JavaScript shim for abstracting WebRTC spec changes and inconsistencies.
* [Netflux](https://github.com/coast-team/netflux) ⭐ 216 | 🐛 5 | 🌐 TypeScript | 📅 2022-01-18 - Isomorphic JavaScript peer to peer transport API for client and server.
* [Socio](https://github.com/Rolands-Laucis/Socio) ⭐ 126 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-22 - A WebSocket Real-Time Communication (RTC) API framework. Realtime Front-end, Back-end reactivity.
* [drachtio](https://drachtio.org) - Node.js SIP server framework.
* [JsSIP](http://jssip.net) - Lightweight open source JavaScript SIP library.
* [sipML5](https://www.doubango.org/sipml5) - Open source JavaScript SIP client with WebRTC media stack.
* [PeerJS](https://peerjs.com) - Data and media peer-to-peer connection API implemented over WebRTC.

### C/C++ Libraries

* [libdatachannel](https://github.com/paullouisageneau/libdatachannel) ⭐ 2,506 | 🐛 140 | 🌐 C++ | 📅 2026-03-06 - Standalone WebRTC DataChannels C++ implementation.
* [libSRTP](https://github.com/cisco/libsrtp) ⭐ 1,365 | 🐛 32 | 🌐 C | 📅 2026-03-06 - Secure Real-time Transport Protocol (SRTP) library for C.
* [usrsctp](https://github.com/sctplab/usrsctp) ⭐ 744 | 🐛 167 | 🌐 C | 📅 2025-10-16 - Portable Stream Control Transmission Protocol (SCTP) user-land stack.
* [libre](https://github.com/creytiv/re) ⭐ 544 | 🐛 19 | 🌐 C | 📅 2024-02-06 - Portable SIP Stack along with companion libraries for media handling, STUN/TURN and a modular user agent.
* [rawrtc](https://github.com/rawrtc/rawrtc) ⭐ 390 | 🐛 59 | 🌐 C | 📅 2021-12-23 - WebRTC and ORTC library with a small footprint.
* [Sofia-SIP](https://github.com/freeswitch/sofia-sip) ⭐ 325 | 🐛 111 | 🌐 C | 📅 2026-03-06 - Open source SIP library used by FreeSWITCH.
* [OSS Core](https://github.com/joegen/oss_core) ⭐ 26 | 🐛 0 | 🌐 C++ | 📅 2021-11-18 - General purpose C++ library for Real Time Communications.
* [PJSIP](https://www.pjsip.org) - Multi-protocol RTC library written in C.
* [eXosip](http://savannah.nongnu.org/projects/exosip) - eXtended osip is a mature C library for abstracting the SIP protocol.
* [Open WebRTC Toolkit](https://01.org/open-webrtc-toolkit) - WebRTC development toolkit with bindings for multiple platforms.

### Go Libraries

* [gossip](https://github.com/StefanKopieczek/gossip) ⭐ 346 | 🐛 18 | 🌐 Go | 📅 2020-02-21 - SIP stack for stateful user agents written in Go.
* [go-diameter](https://github.com/fiorix/go-diameter) ⭐ 283 | 🐛 39 | 🌐 Go | 📅 2025-07-15 - RFC compliant Diameter protocol library.
* [siprocket](https://github.com/marv2097/siprocket) ⭐ 74 | 🐛 1 | 🌐 Go | 📅 2022-08-23 - Fast SIP and SDP packet parser.
* [Pion](https://pion.ly) - Extensive software stack for WebRTC written in Go.

### PHP Libraries

* [RTCKit/SIP](https://github.com/rtckit/php-sip) ⭐ 43 | 🐛 1 | 🌐 PHP | 📅 2024-11-11 - RFC 3261 compliant SIP parsing and rendering library for PHP 7.4+.

### Python Libraries

* [aiortc](https://github.com/aiortc/aiortc) ⭐ 5,023 | 🐛 28 | 🌐 Python | 📅 2025-11-29 - WebRTC and ORTC implementation for Python using asyncio.
* [peerjs-python](https://github.com/ambianic/peerjs-python) ⭐ 97 | 🐛 6 | 🌐 Python | 📅 2024-01-31 - Python port of the PeerJS peer-to-peer connection library.
* [Katari](https://github.com/hyperioxx/Katari) ⭐ 4 | 🐛 4 | 🌐 Python | 📅 2022-12-25 - SIP stack application framework.

### Erlang Libraries

* [NkSIP](https://github.com/NetComposer/nksip) ⭐ 363 | 🐛 18 | 🌐 Erlang | 📅 2024-05-23 - Extendable SIP server framework.
* [ersip](https://github.com/poroh/ersip) ⭐ 128 | 🐛 8 | 🌐 Erlang | 📅 2024-09-25 - Library comprising building blocks for SIP applications.

### Rust Libraries

* [rtcrs/webrtc](https://github.com/rtcrs/webrtc) ⭐ 4,969 | 🐛 9 | 🌐 Rust | 📅 2026-03-08 - WebRTC stack, supporting SDP, RTP, RTCP and SRTP.
* [sipcore](https://github.com/armatusmiles/sipcore) ⭐ 31 | 🐛 5 | 🌐 Rust | 📅 2021-03-14 - Rust framework for creating SIP applications.
* [libsip](https://docs.rs/libsip/0.2.4/libsip) - SIP implementation, with a focus towards softphone clients.

### Dart Libraries

* [dart-sip-ua](https://github.com/cloudwebrtc/dart-sip-ua) ⭐ 371 | 🐛 164 | 🌐 Dart | 📅 2025-12-10 - Dart-lang port of JsSIP, capable of SIP over WebSocket.

## Blogs

* [BlogGeekMe](https://bloggeek.me/blog) - Blog by Tsahi Levent-Levi with a strong focus on WebRTC.
* [SIP Adventures](https://andrewjprokop.wordpress.com) - Unified communications blog by Andrew Prokop.
* [WebRTCHacks](https://webrtchacks.com) - WebRTC blog by independent technologists.

## Discussion

* [FreeSWITCH Slack](https://signalwire.community) - Join #freeswitch and #freeswitch-dev for user and developer support.
* [discuss-webrtc](https://groups.google.com/forum/?fromgroups#!forum/discuss-webrtc) - Developer oriented Google Group for WebRTC discussions.

## Events

* [ClueCon](http://cluecon.com) - Annual conference held in Chicago for telecommunications developers. Birthplace of FreeSWITCH.
* [Kamailio World](https://www.kamailioworld.com) - Berlin hosted annual event focused on Kamailio as well as VoIP, WebRTC, IMS, VoLTE and more.
* [AstriCon](https://www.asterisk.org/community/astricon-user-conference) - Asterisk focus event held every year across the US.
* [CommCon](https://commcon.xyz) - Annual conference held in the UK focused on telecommunications in general and WebRTC in particular.
* [OpenSIPS Summit](https://www.opensips.org/events) - Meeting place for the OpenSIPS community.
* [Kranky Geek](https://krankygeek.com) - AI and RTC event in San Francisco.
* [FOSDEM](https://fosdem.org) - Free event for software developers, with a RTC component, held every year in Europe.
* [JanusCon](https://www.januscon.it) - JanusCon is a live event for Janus and RTC implementers.
* [TADHack](https://tadhack.com) - Global hackathon focused on programmable communications.

## Related Lists

* [Awesome Cellular Hacking](https://github.com/W00t3k/Awesome-Cellular-Hacking) ⭐ 3,640 | 🐛 1 | 📅 2025-06-08 - Research resources in the 3G/4G/5G Cellular security space.
* [Awesome Telco](https://github.com/ravens/awesome-telco) ⭐ 907 | 🐛 1 | 🌐 Python | 📅 2026-03-06 - Telco resources and projects.
* [Awesome 5G](https://github.com/calee0219/awesome-5g) ⭐ 872 | 🐛 4 | 🌐 Shell | 📅 2026-02-03 - 5G frameworks, libraries, software and resources.
* [Awesome RTC Hacking](https://github.com/EnableSecurity/awesome-rtc-hacking) ⭐ 520 | 🐛 0 | 📅 2025-07-25 - Real Time Communications hacking and penetration testing resources.
* [SIP Resources](https://github.com/miconda/sip-resources) ⭐ 253 | 🐛 2 | 📅 2025-09-09 - Useful SIP resources curated by Kamailio's head developer.
* [Awesome RIPT](https://github.com/rtckit/awesome-ript) ⭐ 29 | 🐛 0 | 📅 2020-10-30 - Real Time Internet Peering for Telephony.

## Contribute

Contributions welcome! Read the [contribution guidelines](origin/CONTRIBUTING.md) first.
