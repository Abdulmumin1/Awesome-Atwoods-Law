# Awesome Atwood's Law [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> "Any application that can be written in JavaScript, will eventually be written in JavaScript." — [Jeff Atwood](https://blog.codinghorror.com/the-principle-of-least-power/), 2007

A curated list of projects that prove Atwood's Law — things you'd never expect to be written in JavaScript, but someone did it anyway.

---

## Contents

- [Operating Systems](#operating-systems)
- [Databases](#databases)
- [Emulators & Virtual Machines](#emulators--virtual-machines)
- [Compilers & Language Interpreters](#compilers--language-interpreters)
- [Shell & Bash](#shell--bash)
- [Game Engines & Physics](#game-engines--physics)
- [3D Graphics & CAD](#3d-graphics--cad)
- [GPU Computing](#gpu-computing)
- [Machine Learning & AI](#machine-learning--ai)
- [OCR & Computer Vision](#ocr--computer-vision)
- [PDF Renderers](#pdf-renderers)
- [Audio Codecs](#audio-codecs)
- [Video Codecs & Streaming](#video-codecs--streaming)
- [Image Codecs](#image-codecs)
- [Compression](#compression)
- [Font Engines](#font-engines)
- [Cryptography & TLS](#cryptography--tls)
- [Networking Protocols](#networking-protocols)
- [Version Control](#version-control)
- [Containers & Sandboxes](#containers--sandboxes)
- [Blockchain & Cryptocurrency](#blockchain--cryptocurrency)
- [Torrent Clients & P2P](#torrent-clients--p2p)
- [Hardware & Robotics](#hardware--robotics)


---

## Operating Systems

- [v86](https://github.com/copy/v86) - x86 PC emulator and x86-to-wasm JIT — boots Linux, Windows 98, FreeDOS, and more entirely in the browser. (22.3k stars)
- [OS.js](https://github.com/os-js/OS.js) - Full web desktop platform with window manager, application APIs, and desktop environment.
- [NodeOS](https://github.com/NodeOS/NodeOS) - Operating system built entirely in Node.js, using the Linux kernel with npm as its package manager.
- [Puter](https://github.com/HeyPuter/puter) - Internet OS — full desktop environment in the browser with file system, apps, and cloud storage.
- [daedalOS](https://github.com/DustinBrett/daedalOS) - Desktop environment in the browser with file system, app support, and Windows-like UI.
- [lifo](https://github.com/lifo-sh/lifo) - Browser-native OS. Unix/Linux reimagined where the browser IS the kernel and Web APIs ARE syscalls. 60+ commands, shell, virtual filesystem, IndexedDB persistence. (473 stars)
- [macintosh.js](https://github.com/felixrieseberg/macintosh.js) - A virtual Apple Macintosh with System 8, running in Electron. "I'm sorry." (8.5k stars)
- [1j01/98](https://github.com/1j01/98) - Web-based Windows 98 desktop recreation. (1.4k stars)
- [Rivet agentOS](https://github.com/rivet-dev/agent-os) - Portable OS for AI agents. ~6 ms cold starts, 32x cheaper than sandboxes. Powered by WebAssembly and V8 isolates. Ships as a single npm package (`rivetkit`). [rivet.dev/agent-os](https://www.rivet.dev/agent-os/)

## Databases

- [sql.js](https://github.com/sql-js/sql.js) - Full SQLite compiled to JavaScript — runs an entire relational database in the browser. (13.6k stars)
- [PouchDB](https://github.com/pouchdb/pouchdb) - CouchDB-inspired database that runs in the browser and syncs with CouchDB servers.
- [RxDB](https://github.com/pubkey/rxdb) - Reactive, offline-first database with real-time replication.
- [AlaSQL](https://github.com/AlaSQL/alasql) - SQL database engine for browser and Node.js, supports relational tables and nested JSON.
- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent database for Node.js with MongoDB-like API.
- [OrbitDB](https://github.com/orbitdb/orbitdb) - Serverless, distributed, peer-to-peer database built on IPFS.

## Emulators & Virtual Machines

- [jslinux](https://bellard.org/jslinux/) - PC emulator that boots Linux in the browser (by Fabrice Bellard).
- [JSNES](https://github.com/bfirsh/jsnes) - Nintendo Entertainment System (NES) emulator in JavaScript.
- [EmulatorJS](https://github.com/EmulatorJS/EmulatorJS) - Web frontend for RetroArch — play NES, SNES, GBA, N64, PS1 and more in the browser. (3.4k stars)
- [jor1k](https://github.com/s-macke/jor1k) - OpenRISC 1000 emulator running Linux in the browser. (1.8k stars)
- [PCjs](https://github.com/jeffpar/pcjs) - IBM PC Model 5150 and other vintage machine emulations in JavaScript.
- [assembler-simulator](https://github.com/Schweigi/assembler-simulator) - 8-bit assembler simulator with CPU visualization. (991 stars)
- [Octo](https://github.com/JohnEarnest/Octo) - Chip-8 IDE — assembler, debugger, and emulator. (852 stars)
- [quadplay](https://github.com/morgan3d/quadplay) - Fantasy console — retro game development environment in JS. (961 stars)

## Compilers & Language Interpreters

*Compilers for other languages, and interpreters of non-JS languages — written in JavaScript:*

- [TypeScript](https://github.com/microsoft/TypeScript) - The compiler itself is written in JavaScript/TypeScript.
- [Babel](https://github.com/babel/babel) - JavaScript compiler/transpiler — parsing, transforming, and generating code.
- [Acorn](https://github.com/acornjs/acorn) - Small, fast JavaScript parser written in JavaScript.
- [Ohm](https://github.com/ohmjs/ohm) - Library for building parsers, interpreters, and compilers.
- [pascal.js](https://github.com/kanaka/pascal.js) - Pascal compiler implemented in JavaScript. (50 stars)
- [Brython](https://github.com/brython-dev/brython) - Python 3 implementation for client-side web programming.
- [Transcrypt](https://github.com/TranscryptOrg/Transcrypt) - Python 3.9 to JavaScript compiler.
- [BiwaScheme](https://github.com/biwascheme/biwascheme) - Scheme interpreter in JavaScript. (778 stars)
- [LIPS](https://github.com/jcubic/lips) - Powerful Lisp interpreter in JavaScript. (487 stars)
- [miniMAL](https://github.com/kanaka/miniMAL) - A Lisp in < 1 KB of JavaScript — macros, tail-calls, JS interop, error-handling. (638 stars)
- [WAForth](https://github.com/remko/waforth) - Complete Forth interpreter/compiler in WebAssembly. (580 stars)

## Shell & Bash

- [just-bash](https://github.com/vercel-labs/just-bash) - Virtual bash environment written in TypeScript. Full shell syntax (pipes, redirections, loops, functions), 50+ Unix commands (`grep`, `sed`, `awk`, `jq`, etc.), optional Python/JS runtimes. Designed for AI agents. (2.3k stars)

## Game Engines & Physics

- [Babylon.js](https://github.com/BabylonJS/Babylon.js) - Powerful 3D game engine in TypeScript.
- [Phaser](https://github.com/phaserjs/phaser) - HTML5 game framework for desktop and mobile.
- [PlayCanvas](https://github.com/playcanvas/engine) - 3D game engine on WebGL and WebGPU.
- [Matter.js](https://github.com/liabru/matter-js) - 2D rigid body physics engine.

## 3D Graphics & CAD

- [Three.js](https://github.com/mrdoob/three.js) - The dominant 3D library for the web.
- [OpenJSCAD](https://github.com/jscad/OpenJSCAD.org) - Solid 3D CAD modeling in JavaScript — design parametric models with code.
- [A-Frame](https://github.com/aframevr/aframe) - Web framework for building VR/AR experiences.

## GPU Computing

- [gpu.js](https://github.com/gpujs/gpu.js) - GPU-accelerated JavaScript — run mathematical computations on the GPU from JS. (15.4k stars)

## Machine Learning & AI

- [TensorFlow.js](https://github.com/tensorflow/tfjs) - Google's TensorFlow ported to JavaScript — train and run ML models in the browser.
- [Transformers.js](https://github.com/xenova/transformers.js) - Run Hugging Face transformer models (BERT, GPT-2, etc.) directly in the browser.
- [Brain.js](https://github.com/BrainJS/brain.js) - GPU-accelerated neural networks in JavaScript.
- [ConvNetJS](https://github.com/karpathy/convnetjs) - Deep learning in the browser (by Andrej Karpathy).

## OCR & Computer Vision

- [Tesseract.js](https://github.com/naptha/tesseract.js) - Pure JavaScript OCR for 100+ languages — Tesseract reimplemented in JS. (38k stars)
- [jsQR](https://github.com/cozmo/jsQR) - Pure JavaScript QR code reader — locates, extracts, and parses QR codes from raw images. (4k stars)
- [QuaggaJS](https://github.com/serratus/quaggaJS) - Advanced barcode scanner in JavaScript. (5.2k stars)

## PDF Renderers

- [PDF.js](https://github.com/mozilla/pdf.js) - Mozilla's full PDF renderer in JavaScript — the default PDF reader in Firefox. (53k stars)
- [PDFKit](https://github.com/foliojs/pdfkit) - PDF generation library in JavaScript. (10.6k stars)

## Audio Codecs

- [jsmad](https://github.com/fasterthanlime/jsmad) - MPEG-1 Audio Layer III (MP3) decoder in JavaScript. (757 stars)
- [mp3.js](https://github.com/audiocogs/mp3.js) - MP3 decoder in JavaScript. (269 stars)

## Video Codecs & Streaming

- [flv.js](https://github.com/bilibili/flv.js) - FLV demuxer and H.264/AAC decoder in JavaScript (by Bilibili). (23.2k stars)
- [hls.js](https://github.com/video-dev/hls.js) - HLS streaming player — HTTP Live Streaming in pure JavaScript. (16.6k stars)
- [dash.js](https://github.com/Dash-Industry-Forum/dash.js) - MPEG-DASH reference client in JavaScript. (5.5k stars)

## Image Codecs

- [gif.js](https://github.com/jnordberg/gif.js) - GIF encoder in JavaScript. (4.9k stars)

## Compression

- [pako](https://github.com/nodeca/pako) - zlib (deflate/inflate) ported to JavaScript. (6k stars)
- [fflate](https://github.com/101arrowz/fflate) - High-performance compression/decompression in 8kB. (2.8k stars)
- [JSZip](https://github.com/Stuk/jszip) - Create, read, and edit .zip files in JavaScript. (10.3k stars)

## Font Engines

- [opentype.js](https://github.com/opentypejs/opentype.js) - Read and write OpenType fonts in JavaScript. (4.9k stars)
- [fontkit](https://github.com/foliojs/fontkit) - Advanced font engine for Node and the browser. (1.6k stars)

## Cryptography & TLS

*Crypto protocols and algorithms that are normally implemented in C — reimplemented in pure JavaScript:*

- [node-forge](https://github.com/digitalbazaar/forge) - TLS protocol implementation in JavaScript. (5.3k stars)
- [OpenPGP.js](https://github.com/openpgpjs/openpgpjs) - OpenPGP in JavaScript. (5.9k stars)
- [noble-curves](https://github.com/paulmillr/noble-curves) - Audited elliptic curve cryptography in JavaScript.
- [aes-js](https://github.com/ricmoo/aes-js) - AES block cipher and all modes of operation in pure JavaScript. (1.5k stars)
- [jsrsasign](https://github.com/kjur/jsrsasign) - RSA/ECDSA/DSA, ASN.1, PKCS, X.509, JWS/JWT — all in pure JavaScript. (3.4k stars)
- [bcrypt.js](https://github.com/dcodeIO/bcrypt.js) - bcrypt in JavaScript, zero dependencies. (3.8k stars)

## Networking Protocols

*Network protocols that are traditionally in C/C++ — reimplemented in JavaScript:*

- [ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server in pure JavaScript. (5.8k stars)
- [Haraka](https://github.com/haraka/Haraka) - Full SMTP server in JavaScript. (5.6k stars)
- [node-dns](https://github.com/lsongdev/node-dns) - DNS server and client in pure JavaScript, zero dependencies. (580 stars)
- [multicast-dns](https://github.com/mafintosh/multicast-dns) - mDNS in pure JavaScript. (532 stars)
- [ftp-srv](https://github.com/QuorumDMS/ftp-srv) - FTP server in JavaScript. (395 stars)
- [mqtt.js](https://github.com/mqttjs/MQTT.js) - MQTT client for Node.js and the browser.

## Version Control

- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - Pure JavaScript implementation of Git — clone, commit, push, pull in the browser. (8.1k stars)

## Containers & Sandboxes

- [WebContainers](https://webcontainers.io) - Full Node.js runtime that runs entirely in the browser (powers StackBlitz).
- [just-bash](https://github.com/vercel-labs/just-bash) - Sandboxed virtual bash with in-memory filesystem, overlay FS, and network control — no VM overhead. (2.3k stars)

## Blockchain & Cryptocurrency

- [bcoin](https://github.com/bcoin-org/bcoin) - Full Bitcoin node implementation in JavaScript. (3k stars)
- [Bitcore](https://github.com/bitpay/bitcore) - Full stack for Bitcoin and blockchain applications in JS. (5k stars)
- [ethers.js](https://github.com/ethers-io/ethers.js) - Complete Ethereum library and wallet in JavaScript.

## Torrent Clients & P2P

- [WebTorrent](https://github.com/webtorrent/webtorrent) - BitTorrent client in JavaScript — stream torrents in the browser.
- [IPFS (Helia)](https://github.com/ipfs/helia) - IPFS implementation in JavaScript.
- [libp2p](https://github.com/libp2p/js-libp2p) - Modular P2P networking stack in JavaScript.

## Hardware & Robotics

- [Johnny-Five](https://github.com/rwaldron/johnny-five) - Control Arduinos, Raspberry Pis, and other hardware with JavaScript.
- [Node-RED](https://github.com/node-red/node-red) - Low-code programming for IoT.
- [Firmata.js](https://github.com/firmata/firmata.js) - Firmata protocol for communicating with microcontrollers in JavaScript.

---

## Contributing

Contributions welcome! If you know of a project that proves Atwood's Law, open a PR.

## What Qualifies?

A project belongs here if it makes you say "wait, someone wrote THAT in JavaScript?" Specifically:

1. It implements something traditionally done in C, C++, or another "systems" language
2. It is primarily written in JavaScript or TypeScript
3. It is a real, usable project (not a toy demo)

Things that **don't** qualify: JS frameworks, libraries, build tools, package managers, test runners, CLI tools, web apps, etc. — those are JavaScript's natural habitat, not proof of Atwood's Law.

---

*If you can think of it, someone has probably already written it in JavaScript.*
