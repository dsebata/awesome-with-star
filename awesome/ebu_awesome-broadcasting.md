# Information comes from [ebu/awesome-broadcasting](https://github.com/ebu/awesome-broadcasting)
# Awesome Broadcasting [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of amazingly awesome open source resources for broadcasters.

* [Awesome Broadcasting](#awesome-broadcasting)
  * [Codecs](#codecs)
  * [Companion Screens](#companion-screens)
  * [Connected TVs](#connected-tvs)
  * [Distributed Media Processing](#distributed-media-processing)
  * [Documentation](#documentation)
  * [DVB & WiFi](#dvb--wifi)
  * [Animation, Graphics & Video Playout](#animation-graphics--video-playout)
  * [Hybrid Radio](#hybrid-radio)
  * [LiveIP](#liveip)
  * [Media Players](#media-players)
  * [Metadata](#metadata)
  * [Monitoring & Quality Control](#monitoring--quality-control)
  * [Multimedia content processing](#multimedia-content-processing)
  * [Network & Storage Testing](#network--storage-testing)
  * [Radio Production](#radio-production)
  * [Software-defined radio](#software-defined-radio)
  * [Subtitling](#subtitling)
  * [Video Production](#video-production)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Websites](#websites)
* [Contributing](#contributing)

<!-- This page is available on https://ebu.io/opensource -->
## Codecs

* [FLAC](https://www.xiph.org/flac/) - Free Lossless Audio Coding, used by some broadcasters for audio exchange, storage.
* [Lame](http://lame.sourceforge.net/) - A high quality MPEG Audio Layer III (MP3) encoder.
* [opencore-amr](https://sourceforge.net/projects/opencore-amr/) - Audio codecs extracted from Android Open Source Project, including AAC.
* [Opus](http://www.opus-codec.org) - A totally open, royalty-free, highly versatile audio codec.
* [Turing Codec](http://turingcodec.org/) - An H.265/HEVC open source software encoder designed for fast and efficient video compression.
* [TwoLame](http://www.twolame.org/) - An MPEG Audio Layer 2 (MP2) encoder.

## Companion Screens

* [dial-discovery-ios](https://github.com/bbc/dial-discovery-ios) - A library for the discovery of devices via the DIAL protocol on the iOS platform. :star:1
* [dvbcss-synckit-ios](https://github.com/bbc/dvbcss-synckit-ios) - iOS libraries for companion screen applications that are synchronised frame-accurately to a TV. :star:8
* [dvbcss-synctiming](https://github.com/BBC/dvbcss-synctiming) - A system for measuring how accurately a TV or companion are synchronised. :star:11
* [pydvbcss](https://github.com/BBC/pydvbcss) - Implementation of the DVB Companion Screens and Streams protocols for synchronised media playback. :star:20

## Connected TVs

* [Cross-Platform Authentication](https://ebu.io/project/cpa) - CPA offers an open standard for associating any media device with an online identity.
* [HbbPlayer](https://github.com/Samsung/HbbPlayer) - An HbbTV and W3C specifications compliant application that can playback media from a URL. :star:38
* [TAL](http://bbc.github.io/tal/) - The TV Application Layer (TAL) is an open source library for building applications for Connected TV devices.

## Distributed Media Processing

* [StormCV](https://github.com/sensorstorm/StormCV) - Apache Storm + OpenCV = large scale distributed image and video analysis. :star:155

## Documentation

* [Kronekeeper](https://github.com/nick-prater/kronekeeper) - A web based application for recording and managing Krone frame records. :star:5

## DVB & WiFi

* [DTT 2 IP](https://github.com/ebu/dtt2ip) - Broadcast to IP conversion for Wifi indoor coverage. :star:18
* [DVB Inspector](https://sourceforge.net/projects/dvbinspector/) - An open-source DVB analyzer.
* [DVBlast](http://www.videolan.org/projects/dvblast.html) - A simple and powerful MPEG-2/TS demux and streaming application.
* [dvbshout](https://github.com/njh/dvbshout) - Tool to send DVB audio to a shoutcast server or a RTP stream. :star:6
* [Opencaster](http://www.avalpa.com/the-key-values/15-free-software/33-opencaster) - A free and open source MPEG2 transport stream data generator and packet manipulator.
* [Project X](https://sourceforge.net/projects/project-x/) - DVB demux tool.
* [ts2mpa](https://github.com/njh/ts2mpa) - Simple tool to extract MPEG Audio from a MPEG Transport Stream (TS). :star:3
* [TSDuck](https://tsduck.github.io/) - Extensible toolkit for MPEG/DVB transport streams testing, monitoring, integration, debugging, and more.
* [WiFiBroadcast](https://befinitiv.wordpress.com/wifibroadcast-analog-like-transmission-of-live-video-data/) - Analog-like transmission of live video data.

## Animation, Graphics & Video Playout

* [Aurena](https://github.com/thaytan/aurena) - A network distributed media playback system. :star:90
* [Blender](https://developer.blender.org/diffusion/) - 3D creation suite supporting 3D modelling, animation, motion tracking, video editing, and more.
* [CasparCG](http://www.casparcg.com/) - A professional graphics and video play-out software, proven in 24/7 broadcasts since 2006.
* [Macadam](https://github.com/Streampunk/macadam) - Blackmagic Node.js bindings that support HTML/CSS (via [Electron](https://electronjs.org/)) and SVG (via [Sevruga](https://github.com/Streampunk/sevruga)) graphics. :star:44
* [Open Playout Automation](https://github.com/jaskie/PlayoutAutomation) - A CasparCG-based MCR play-out system. :star:64
* [ossia](https://ossia.io/) - A free and open-source intermedia sequencer.
* [Sofie - TV Automation](https://github.com/nrkno/Sofie-TV-automation) - MOS-driven automation system for news casts, with many libraries for e.g. device control. :star:54

## Hybrid Radio

* [RadioDNS for Node.js](https://github.com/bbc/node-radiodns) - Perform RadioDNS resolutions and service lookups in node.js. :star:3
* [RadioDNS Manager](https://github.com/ebu/radiodns-manager) - Platform to manage Hybrid Radio services, e.g. RadioVIS, RadioEPG and Service Following. :star:13
* [RadioTag.js](https://github.com/ebu/radiotag.js) - RadioTag client library in JavaScript. :star:6
* [RadioVIS Demo](https://github.com/bbc/RadioVisDemo) - RadioVIS client application in Python. :star:15
* [RadioVIS Html Player](https://github.com/ebu/radiovis-html5player) - RadioVIS Player using WebSocket. :star:11
* [RadioVIS Stomp Server](https://github.com/bbc/node-radiovis-stomp-server) - RadioVIS STOMP server written in node.js. :star:5

## LiveIP
*Audio/Video over IP & Streaming*

* [butt](https://danielnoethen.de/) - broadcast using this tool (butt) is an easy to use, multi OS streaming tool. It supports SHOUTcast and Icecast.
* [Cool Mic](https://coolmic.net/) - Android audio livestreaming Icecast source client app.
* [DarkIce](http://www.darkice.org/) - Live audio streamer that records and encodes from an audio interface and sends to a streaming server.
* [Icecast](http://icecast.org/) - Streaming media (audio/video) server which supports Ogg (Vorbis and Theora), Opus, WebM and MP3.
* [IRIS Broadcast](https://github.com/IrisBroadcast/irisbroadcast.github.io/) - A project founded in Sweden to publish Open Source software for professional radio broadcasts.
* [Kamailio](http://www.kamailio.org/) - Open SIP server, commonly used for Audio contribution over IP using SIP (EBU ACIP).
* [OpenOB](https://jamesharrison.github.io/openob/) - Open Outside Broadcast project for radio contribution links and studio-transmitter links based on Opus.
* [PJSIP](https://www.pjsip.org/) - Open Source multimedia library implementing SIP, SDP, RTP, STUN, TURN, and ICE.
* [trx](http://www.pogo.org.uk/~mark/trx/) - A simple toolset for broadcasting live audio from Linux.

## Media Players

* [Dash.js](https://github.com/ebu/dash.js) - A reference client implementation for the playback of MPEG DASH via Javascript and compliant browsers. :star:8
* [GPAC](https://gpac.wp.imt.fr/home/) - Multimedia player, packager and tools.
* [IDJC](http://idjc.sourceforge.net/) - A GTK+ Shoutcast/Icecast client with two main media players.
* [Kodi](https://github.com/xbmc/xbmc) - A software media player and entertainment hub for digital media. :star:9399
* [Media4DPlayer](https://github.com/ebu/media4Dplayer) - HTML5 player focused on accessibility. :star:4
* [MPD](https://www.musicpd.org/) - A flexible, powerful, server-side application for playing music.
* [mpg123](https://www.mpg123.de/) - A fast console MPEG Audio Player and decoder library.
* [Mixxx](https://www.mixxx.org/) - A free, open source DJ software.
* [Peaks.js](https://waveform.prototyping.bbc.co.uk/) - Browser-based audio waveform visualisation.
* [rx-player](https://github.com/canalplus/rx-player) - HTML5/Javascript video player that supports MPEG-DASH and SmoothStreaming. :star:414
* [VLC](http://www.vlc.org) - Simple, fast and powerful media player.

## Metadata

* [BMXlib](https://sourceforge.net/projects/bmxlib/) - Library and utilities to read and write broadcasting media files. Primarily supports the MXF file format.
* [EBUCore](https://github.com/ebu/ebucore) - The Github for maintenance of the [EBUCore schema](https://tech.ebu.ch/docs/tech/tech3293.pdf). :star:14
* [AMWA IS-04 and IS-05](https://github.com/bbc/nmos-joint-ri) - NMOS Registration & Discovery and Device Connection Management in Python. :star:4
* [jebu-core](https://github.com/mikrosimage/jebu-core) - Java port of [EBU Tech 3293](https://tech.ebu.ch/publications/tech3293) EBU Core metadata, including the [Audio Definition Model](https://tech.ebu.ch/publications/tech3364). :star:1
* [libadm](https://github.com/irt-open-source/libadm) - Audio Definition Model (ITU-R BS.2076) handling C++11 library. :star:9
* [MAJ API](https://github.com/AMWA-TV/maj) - Pure Java library for reading and writing MXF and AAF files. :star:7
* [NMOS](https://github.com/sony/nmos-cpp) - An NMOS (Networked Media Open Specifications) Registry and Node in C++ (IS-04, IS-05). :star:22
* [SDPoker](https://github.com/Streampunk/sdpoker) - CLI tool and library for testing SMPTE ST2110 SDP files. :star:7
* [TV-Anytime](https://github.com/ebu/tvanytime) - The TV-Anytime schema github maintenance page. :star:9

## Monitoring & Quality Control

* [BeaqleJS](https://github.com/HSU-ANT/beaqlejs) - A framework to create browser based listening tests for subjective audio quality assessment. :star:53
* [Jack Meter](https://github.com/njh/jackmeter) - Text console based DPM (Digital Peak Meter) for JACK. :star:31
* [JACK Meterbridge](http://plugin.org.uk/meterbridge/) - A collection of graphical Audio meters for JACK (ballistics may be incorrect).
* [Jmeters](http://kokkinizita.linuxaudio.org/linuxaudio/downloads/index.html) - A collection of graphical audio meters for JACK, including VU, PPM and [EBU R 128](https://tech.ebu.ch/publications/r128) Loudness meters.
* [LTC-tools](https://github.com/x42/ltc-tools) - A collection of tools to handle Linear Timecode (LTC) and convert to MIDI Timecode (MTC). :star:33
* [MediaConch](https://mediaarea.net/MediaConch) - Implementation checker, policy checker, & reporter for Matroska, FFV1, & PCM.
* [MediaInfo](https://mediaarea.net/en/MediaInfo) - A convenient unified display of the most relevant technical and tag data for video and audio files.
* [MXF Inspect](https://www.myriadbits.com/) - A Windows tool to display the internal structure of an MXF (Material eXchange Format) file.
* [Pi Audio Monitor](https://github.com/martim01/pam) - Audio Monitoring for Raspberry Pi, supports S/PDIF, AES3, AES67, Livewire and Ravenna. :star:8
* [Photon](https://github.com/Netflix/photon) - Implementation of the SMPTE Interoperable Master Format (IMF) standard. :star:145
* [QCTools](https://github.com/bavc/qctools) - Quality Control tools for video preservation to analyse digitized video files. :star:160
* [Rotter](https://github.com/njh/rotter) - Recording of Transmissions / Audio Logger for JACK. :star:29
* [silan](https://github.com/x42/silan) -  Audiofile silence analyzer. :star:27
* [SilentJack](https://github.com/njh/silentjack) - Dead-air / Silence detector for JACK. :star:16
* [Sonic Visualiser](https://www.sonicvisualiser.org/) - An application for viewing and analysing the contents of music audio files.
* [VMAF](https://github.com/Netflix/vmaf) - Perceptual video quality assessment based on multi-method fusion. :star:1191
* [Wisual](https://github.com/MarcAntoine-Arnaud/wisual) - A web service for Visual Quality Assessment, which supports PSNR, SSIM, VQM, etc. :star:11

## Multimedia content processing

* [AvTranscoder](https://github.com/avTranscoder/avTranscoder) - FFmpeg/LibAV-based high-level API to re-wrap or transcode media, with bindings for Java and Python. :star:86
* [Beam Coder](https://github.com/Streampunk/beamcoder) - Node.js native bindings to FFmpeg, with support for asynchronous processing via promises and streams. :star:44
* [Bento4](https://github.com/axiomatic-systems/Bento4) - Full-featured MP4 format and MPEG DASH C++ class library and tools. :star:672
* [Codem-isoboxer](https://github.com/madebyhiro/codem-isoboxer) A small browser-based MPEG-4 (ISOBMFF) parser.
* [Dynamorse](https://github.com/Streampunk/node-red-contrib-dynamorse-core) - IT swiss army knife - a Node-RED media pipeline builder, adding professional media processing nodes. :star:27
* [EBU ADM Renderer](https://github.com/ebu/ebu_adm_renderer) - Reference implementation of the EBU ADM Renderer ([EBU Tech 3388](https://tech.ebu.ch/publications/tech3388))
* [FFmbc](https://github.com/bcoudurier/FFmbc) - FFmpeg customized for broadcast and professional usage. :star:109
* [FFmpeg](http://ffmpeg.org) - A cross-platform solution to record, convert and stream audio and video. Supports SMPTE ST 2110.
* [Flowblade](https://github.com/jliljebl/flowblade) - A multitrack non-linear video editor. :star:1131
* [GStreamer](https://gstreamer.freedesktop.org/) - A library for constructing graphs of media-handling components.
* [Kelvinadon](https://github.com/Streampunk/kelvinadon) - Node.JS pure Javascript module for streaming MXF files to and from JSON. :star:10
* [KFR](https://www.kfrlib.com/) - Fast, modern C++ DSP framework, DFT/FFT, Audio resampling, FIR/IIR, Biquad, EBU R 128.
* [L-SMASH](https://github.com/l-smash/l-smash/) - A rigidly spec-compliant ISOBMFF library, which has full DASH muxing support. :star:147
* [LibAV](https://libav.org/) - Open source audio and video processing tools.
* [libbw64](https://github.com/irt-open-source/libbw64) – Header-only Broadcast Wave 64 (ITU-R BS.2088) C++11 library.
* [Libebur128](https://github.com/jiixyj/libebur128) - A library that implements the EBU R 128 standard for loudness normalisation. :star:197
* [Loudness Validator](https://github.com/mikrosimage/loudness_validator) - A set of applications to analyse, visualise and correct the loudness. :star:8
* [MP4Box.js](https://github.com/gpac/mp4box.js) - JavaScript library to process MP4 files in the browser (and in NodeJS). :star:647
* [MXFLib](https://sourceforge.net/projects/mxflib/) - A multi-platform C++ library for reading and writing MXF files.
* [OBS-Studio](https://github.com/obsproject/obs-studio) - Software for live streaming and screen recording. :star:14169
* [Open Broadcast Encoder](https://github.com/ob-encoder) - Broadcast encoder built from Open Source components.
* [rgain](https://bitbucket.org/fk/rgain) - Tools and Python library to read, write and calculate Replay Gain.
* [rtmp](https://github.com/c-bata/rtmp) - Server implementation of Adobe's RTMP 1.0 protocol in Go. :star:96
* [Snowmix](https://sourceforge.net/projects/snowmix/) - Live Video Mixer.
* [SoX](http://sox.sourceforge.net/) - The Swiss Army knife of sound processing programs.
* [TuttleOFX](https://github.com/tuttleofx/TuttleOFX) - An open source image processing framework based on OpenFX plugin standard. :star:134
* [UPipe](https://github.com/cmassiot/upipe/) - Primarily designed to be the core of a multimedia player, transcoder or streamer.
* [VideoContext](https://github.com/bbc/videocontext) - Experimental HTML5/WebGL library for creating interactive and responsive web videos. :star:738
* [Voctomix](https://github.com/voc/voctomix) - Customizable conference recording/mixing/streaming software based on Python and GStreamer. :star:356

## Network & Storage Testing

* [BBC Media Storage Meter](https://sourceforge.net/projects/msmeter/) - An application for the testing of network attached  (professional media) storage.
* [Fio](https://github.com/axboe/fio) - Flexible I/O Tester :star:1803
* [iPerf3](https://iperf.fr/) - The TCP, UDP and SCTP network bandwidth measurement tool.
* [SMPTE 2110-20 Analyzer](https://github.com/ebu/smpte2110-analyzer) - Analyzer to inspect network packets generated in accordance with SMPTE ST 2110. :star:19

## Radio Production

* [Airtime](https://github.com/sourcefabric/airtime) - Radio management application for remote broadcast automation (via web-based schedule). :star:552
* [Ardour](https://ardour.org/) - A digital audio workstation.
* [Audacity](https://www.audacityteam.org/) - Cross-platform software for recording and editing sounds.
* [AzuraCast](https://github.com/AzuraCast/AzuraCast) - A self-hosted web radio management suite. :star:587
* [LibreTime](http://libretime.org/) - Radio broadcast & automation platform (fork of Airtime).
* [Liquidsoap](https://github.com/savonet/liquidsoap) - A Swiss army knife for multimedia streaming ([documentation](https://www.liquidsoap.info/doc.html)). :star:492
* [OpenBroadcaster](https://openbroadcaster.com/) Open Source LPFM IPTV Broadcast Automation. [Server and Player code here](https://github.com/openbroadcaster).
* [RAAR](https://github.com/radiorabe/raar) - A ruby application to manage and browse an audio archive. :star:12
* [Rivendell](https://github.com/ElvishArtisan/rivendell) - Complete radio broadcast automation solution, translated to many languages and used worldwide.  :star:77

## Software-defined radio

* [GNU Radio](https://www.gnuradio.org/) - A software development toolkit that provides signal processing blocks to implement software radios.
* [Gqrx SDR](http://gqrx.dk/) - An open source software defined radio receiver (SDR).
* [ODR-mmbTools](https://www.opendigitalradio.org) - Fork of CRC-mmbTools. Adds live, DAB+, associated data, distributed infrastructure, SFN.
* [rtl-sdr](https://osmocom.org/projects/rtl-sdr/wiki/rtl-sdr) - Turns a Realtek RTL2832 based DVB dongle into a SDR receiver.
* [welle.io](https://www.welle.io/) - An open source DAB and DAB+ software defined radio (SDR) with support for airspy and rtlsdr.

## Subtitling

* [CCExtractor](http://ccextractor.sourceforge.net/about-ccextractor.html) - A tool that analyzes video files and produces stand-alone subtitle files.
* [EBU-TT-D Subtitling within dash.js](https://github.com/ebu/dash.js/tree/ebu-subtitling-dev) - dash.js fork with EBU-TT-D subtitles in HTML/CSS overlay. Later added to [dash.js](https://github.com/ebu/dash.js). :star:8
* [EBU-TT-D W3C XML Schema](https://github.com/ebu/ebu-tt-d-xsd/) - Informative EBU-TT-D XML Schema to support the implementation of EBU Tech 3380. :star:6
* [EBU-TT Live Interoperability Toolkit](https://github.com/ebu/ebu-tt-live-toolkit) - Components for generating, testing and distributing [EBU-TT Live](https://tech.ebu.ch/publications/tech3370) subtitles. :star:16
* [GStreamer TTML subtitling package](https://github.com/bbc/gst-ttml-subtitles) - A means for GStreamer pipelines to parse and render EBU-TT-D (TTML) subtitles. :star:11
* [imscJS](https://github.com/sandflow/imscJS) - JavaScript library for rendering IMSC1 Text and Image Profile documents to HTML5. :star:41
* [IRT EBU-TT-D Application Samples](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples) - EBU-TT-D sample files, PNG images and mp4 videos as rendering references. :star:10
* [Subtitle Edit](https://www.nikse.dk/SubtitleEdit) - An editor for subtitles.
* [Subtitling Conversion Framework (SCF)](https://github.com/Irt-Open-Source/scf) - Modules for converting subtitle formats, incl. EBU STL and EBU-TT files. :star:27
* [Timed Text Toolkit (ttt)](https://github.com/skynav/ttt) - Tools that support/use the W3C Timed Text Markup Language (TTML). :star:48

## Video Production

* [MIDIMonster](https://github.com/cbdevnet/midimonster) - Lightweight adapter tool for common show control protocols. :star:146
* [MOS-connection](https://github.com/nrkno/tv-automation-mos-connection) - A JavaScript library for connection and MOS messaging either as MOS device or NRCS. :star:7
* [Open Lighting Architecture (OLA)](https://www.openlighting.org/ola/) - Travel adaptor for the lighting industry, for interconnecting DMX-512, IP and USB.
* [PiClock](https://github.com/simonhyde/PiClock) - Customisable network based displays of clocks, on-air, mic live and other studio indicators. :star:7
* [Q Light Controller+ (QLC+)](https://www.qlcplus.org/) - Cross-platform control of DMX or analogue lighting systems (heads, dimmers, etc.).
* [Teleprompter](https://github.com/ImaginarySense/Teleprompter-Core) - Web browser and standalone Electron app prompter. :star:50

# Resources
Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

* [BBC News Labs](https://github.com/BBC-News-Labs) - Open Source projects from BBC News Labs.
* [BBC R&D](https://www.bbc.co.uk/rd) - BBC Research and Development. Checkout the weekly notes.
* [3D CineCast](http://3dcinecast.blogspot.com/) - A curation about new media technologies.
* [Canal+](https://developers.canal-plus.com/) - CANAL+ Open Source Community.
* [IRT Lab](https://lab.irt.de/) - IRT blog posting developments and demos for all digital audiovisual media technology.
* [The Netflix Tech Blog](http://techblog.netflix.com/) - A Netflix blog focused on technology and technology issues.
* [Youtube Engineering and Developers Blog](https://youtube-eng.googleblog.com/) - What's happening with engineering and developers at YouTube.

<!-- This page is available on https://ebu.io/opensource -->

# Contributing
Please see [CONTRIBUTING](https://github.com/ebu/awesome-broadcasting/blob/master/CONTRIBUTING.md) for details.

