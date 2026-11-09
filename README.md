### Igor Sheko

**WebRTC & Real-Time Media Architect · Head of Engineering (Dev/SRE/DevOps)**
Watford / London, UK · [irbisadm.dev](https://irbisadm.dev)

Software architect and hands-on engineer, building software since **2007**. My focus is real-time communications: I design and develop a commercial WebRTC SFU and work deep in libwebrtc internals, down to the RFC level.

I lead an engineering department spanning development, SRE and DevOps, and I still ship code myself. My day-to-day stack is TypeScript and Go on the media-server side.

Current areas of work: WebCodecs, SVC / temporal scalability, AV1, ScreamV2 / L4S, WebTransport.

**Core expertise:** WebRTC & SFU architecture · SIP · RTP/RTCP · FEC · bandwidth estimation & congestion control · libwebrtc internals · real-time media at scale

#### webrtc.page
**[webrtc.page](https://webrtc.page/)** is a set of browser tools and MCP servers for WebRTC and SIP.

- **MCP servers** give AI assistants version-aware access to eleven WebRTC and VoIP codebases: [libwebrtc](https://webrtc.googlesource.com/src/), [Pion](https://github.com/pion/webrtc), libdatachannel, coturn, Janus, Jitsi Videobridge, Kamailio, rtpengine, Asterisk, FreeSWITCH and sipXcom. Each one supports semantic code search, symbol navigation, diffs between versions and RFC lookup.
- **Browser tools** run locally, and nothing is uploaded: an SDP inspector and editor, a SIP ladder diagram built from a pcap, and a codec string decoder.

#### Talks
Invited expert at VideoTech 2025.

- [How Chromium Manages WebRTC Bitrate](https://www.youtube.com/watch?v=4G6Cv1xN-aI) - VideoTech, 2024 (RU)
- [Panel host: How to Prepare for High Load in a Video Service?](https://vtconf.com/en/archive/2024/talks/20006146-how-to-prepare-for-high-load-in-a-video-service/) - VideoTech, 2024 (RU)
- [Interview: Quality Control of WebRTC Sessions](https://www.youtube.com/watch?v=UwTD7axZ8KM) - VideoTech, 2023 (RU)
- [Panel: Is WebRTC Half Alive or Half Dead?](https://vtconf.com/en/archive/2023/talks/20003549-is-webrtc-half-alive-or-half-dead/) - VideoTech, 2023 (RU)
- [Architecture kata: a video-calling platform](https://www.youtube.com/watch?v=ngfrZzdz-uU) - with Vadim Kleba, «{ между скобок }», 2025 (RU)
- [Making Friends with WebRTC Statistics and Saving Thousands of Debugging Hours](https://www.youtube.com/watch?v=Lv1iVwlnqTk) - TechTrain, 2022 (RU)
- [Modern UGC: Collecting Video Testimonials in the Browser without WebRTC](https://www.youtube.com/watch?v=ZY9AcASx2mc) - TechTrain, 2022 (RU)
- [WebRTC Conferencing: the Interesting and Hard Parts](https://www.youtube.com/watch?v=EouVG6fW4xM) - GDG Rostov-on-Don, 2021 (RU)

#### Open source
- [goog-cc-as](https://github.com/irbisadm/goog-cc-as): a port of libwebrtc's GoogCC send-side congestion control (M154) to AssemblyScript/WebAssembly. CI checks its output against upstream C++ on simulated scenarios and on real RtcEventLog recordings, and the outputs match exactly.
- [rtc-event-log](https://github.com/irbisadm/rtc-event-log) ([npm](https://www.npmjs.com/package/@irbisadm/rtc-event-log)): a TypeScript port of libwebrtc's RtcEventLog parser for the legacy, new and v3 formats. Tests check it against the upstream parser. Work in progress.
- [simple-sdp](https://github.com/irbisadm/simple-sdp) ([npm](https://www.npmjs.com/package/@irbisadm/simple-sdp)): parses, modifies, writes and validates SDP (RFC 8866) for WebRTC and SIP.
- [sip-pcap](https://github.com/irbisadm/sip-pcap) ([npm](https://www.npmjs.com/package/@irbisadm/sip-pcap)): extracts SIP calls, hops and the SDP offer/answer on each hop from pcap and pcapng captures. Works in Node.js and in browsers.
- [iso-codec-string](https://github.com/irbisadm/iso-codec-string) ([npm](https://www.npmjs.com/package/@irbisadm/iso-codec-string)): parses and generates RFC 6381 codec strings (e.g. `avc1.64001f`, `av01.0.04M.08`).

#### Contact
[irbisadm.dev](https://irbisadm.dev) · [i@irbisadm.dev](mailto:i@irbisadm.dev) · [LinkedIn](https://www.linkedin.com/in/irbisadm)
