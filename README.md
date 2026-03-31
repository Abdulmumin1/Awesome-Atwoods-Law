# Awesome Atwood's Law [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> "Any application that can be written in JavaScript, will eventually be written in JavaScript." — [Jeff Atwood](https://blog.codinghorror.com/the-principle-of-least-power/), 2007

A curated list of projects that prove Atwood's Law — things you wouldn't expect to be written in JavaScript, but are.

---

## Contents

- [Operating Systems](#operating-systems)
- [Databases](#databases)
- [Emulators & Virtual Machines](#emulators--virtual-machines)
- [Compilers & Interpreters](#compilers--interpreters)
- [Language Interpreters](#language-interpreters)
- [Game Engines & Physics](#game-engines--physics)
- [3D Graphics & CAD](#3d-graphics--cad)
- [GPU & Parallel Computing](#gpu--parallel-computing)
- [Machine Learning & AI](#machine-learning--ai)
- [OCR & Computer Vision](#ocr--computer-vision)
- [Desktop Applications](#desktop-applications)
- [Mobile Applications](#mobile-applications)
- [Text Editors & IDEs](#text-editors--ides)
- [Terminal Emulators](#terminal-emulators)
- [Spreadsheets](#spreadsheets)
- [Word Processors & Rich Text](#word-processors--rich-text)
- [Presentation Software](#presentation-software)
- [PDF Tools](#pdf-tools)
- [Image & Video Editing](#image--video-editing)
- [Audio Codecs & Music](#audio-codecs--music)
- [Video Streaming & Codecs](#video-streaming--codecs)
- [Compression & Archives](#compression--archives)
- [Font Engines & Typography](#font-engines--typography)
- [Format Parsers](#format-parsers)
- [Email Servers & Clients](#email-servers--clients)
- [Chat & Communication](#chat--communication)
- [Video Conferencing](#video-conferencing)
- [Torrent Clients & P2P](#torrent-clients--p2p)
- [Blockchain & Cryptocurrency](#blockchain--cryptocurrency)
- [Cryptography](#cryptography)
- [Networking & Protocols](#networking--protocols)
- [File Systems & Version Control](#file-systems--version-control)
- [Containers & Sandboxes](#containers--sandboxes)
- [Hardware & IoT](#hardware--iot)
- [Robotics](#robotics)
- [Scientific Computing](#scientific-computing)
- [Data Visualization](#data-visualization)
- [Maps & GIS](#maps--gis)
- [Barcode & QR](#barcode--qr)
- [Server-Side Runtimes](#server-side-runtimes)
- [Web Servers & Frameworks](#web-servers--frameworks)
- [Bundlers & Build Tools](#bundlers--build-tools)
- [Package Managers](#package-managers)
- [Testing Frameworks](#testing-frameworks)
- [CLI Frameworks](#cli-frameworks)
- [Static Site Generators](#static-site-generators)
- [CMS & Wiki](#cms--wiki)
- [ERP & Business Software](#erp--business-software)
- [Agent Operating Systems](#agent-operating-systems)

---

## Operating Systems

- [OS.js](https://github.com/os-js/OS.js) - JavaScript web desktop platform with window manager, application APIs, and a full desktop environment in the browser.
- [NodeOS](https://github.com/NodeOS/NodeOS) - Operating system built entirely in Node.js, using the Linux kernel with npm as its package manager.
- [Puter](https://github.com/HeyPuter/puter) - Internet OS — a full desktop environment that runs in the browser, complete with a file system, apps, and cloud storage.
- [daedalOS](https://github.com/DustinBrett/daedalOS) - Desktop environment in the browser with file system, app support, and a Windows-like UI.
- [lifo](https://github.com/lifo-sh/lifo) - Browser-native operating system. Unix/Linux reimagined where the browser IS the kernel and Web APIs ARE syscalls. 60+ commands, bash-like shell, virtual filesystem, and IndexedDB persistence.
- [macintosh.js](https://github.com/felixrieseberg/macintosh.js) - A virtual Apple Macintosh with System 8, running in Electron. "I'm sorry."
- [1j01/98](https://github.com/1j01/98) - Web-based Windows 98 desktop recreation in the browser.

## Databases

- [PouchDB](https://github.com/pouchdb/pouchdb) - Pocket-sized database inspired by CouchDB, runs in the browser and syncs with CouchDB-compatible servers.
- [RxDB](https://github.com/pubkey/rxdb) - Reactive, offline-first database for JavaScript applications with real-time replication.
- [LevelUp](https://github.com/Level/levelup) - Node.js wrapper around Google's LevelDB, providing a fast key-value store.
- [LowDB](https://github.com/typicode/lowdb) - Simple JSON database powered by Lodash, with a flat file as the storage backend.
- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent or in-memory database for Node.js, with a MongoDB-like API.
- [AlaSQL](https://github.com/AlaSQL/alasql) - JavaScript SQL database for browser and Node.js, supporting traditional relational tables and nested JSON data.
- [sql.js](https://github.com/sql-js/sql.js) - SQLite compiled to JavaScript via Emscripten, runs a full SQLite database entirely in the browser. (13.6k stars)
- [Dexie.js](https://github.com/dexie/Dexie.js) - Minimalistic wrapper for IndexedDB with a straightforward API.
- [OrbitDB](https://github.com/orbitdb/orbitdb) - Serverless, distributed, peer-to-peer database built on IPFS.

## Emulators & Virtual Machines

- [v86](https://github.com/copy/v86) - x86 PC emulator and x86-to-wasm JIT, running in the browser — boots Linux, Windows 98, FreeDOS, and more. (22.3k stars)
- [jslinux](https://bellard.org/jslinux/) - PC emulator written in JavaScript that boots Linux in the browser (by Fabrice Bellard).
- [JSNES](https://github.com/bfirsh/jsnes) - Nintendo Entertainment System (NES) emulator written in JavaScript.
- [EmulatorJS](https://github.com/EmulatorJS/EmulatorJS) - Web-based frontend for RetroArch — play NES, SNES, GBA, N64, PS1 and more in the browser. (3.4k stars)
- [jor1k](https://github.com/s-macke/jor1k) - Online OR1K Emulator running Linux in the browser. (1.8k stars)
- [PCjs](https://github.com/jeffpar/pcjs) - IBM PC Model 5150 and other machine emulations in JavaScript, runs original PC software in the browser.
- [Schweigi/assembler-simulator](https://github.com/Schweigi/assembler-simulator) - Simple 8-bit Assembler Simulator with Angular.js. (991 stars)
- [Octo](https://github.com/JohnEarnest/Octo) - A Chip-8 IDE — assembler, debugger, and emulator in JavaScript. (852 stars)
- [taniarascia/chip8](https://github.com/taniarascia/chip8) - Chip-8 emulator written in JavaScript for web, CLI, and native UI. (472 stars)
- [quadplay](https://github.com/morgan3d/quadplay) - The quadplay fantasy console — a retro game development environment in JS. (961 stars)

## Compilers & Interpreters

- [TypeScript](https://github.com/microsoft/TypeScript) - Typed superset of JavaScript that compiles to plain JavaScript — the compiler itself is JavaScript.
- [Babel](https://github.com/babel/babel) - JavaScript compiler / transpiler that transforms modern JS into backwards-compatible versions.
- [SWC](https://github.com/swc-project/swc) - Super-fast TypeScript/JavaScript compiler (core in Rust, but JS API and plugins).
- [CoffeeScript](https://github.com/jashkenas/coffeescript) - Language that compiles into JavaScript, compiler written in CoffeeScript/JavaScript.
- [Acorn](https://github.com/acornjs/acorn) - Small, fast JavaScript parser written in JavaScript.
- [Nearley](https://github.com/kach/nearley) - Streaming parser toolkit for JavaScript, parse any grammar.
- [Ohm](https://github.com/ohmjs/ohm) - Library and language for building parsers, interpreters, and compilers in JavaScript.
- [GopherJS](https://github.com/nicedayfor/gopherjs) - Compiler from Go to JavaScript.
- [Opal](https://github.com/opal/opal) - Ruby to JavaScript compiler.
- [Sucrase](https://github.com/alangpierce/sucrase) - Super-fast alternative to Babel for when you can target modern JS runtimes.
- [Lebab](https://github.com/lebab/lebab) - Turn your ES5 code into readable ES6 — the opposite of what Babel does.
- [Prettier](https://github.com/prettier/prettier) - Opinionated code formatter with parsers for JS, TS, CSS, HTML, JSON, Markdown, and more. (51.7k stars)
- [Shiki](https://github.com/shikijs/shiki) - Beautiful syntax highlighter powered by TextMate grammars — the same engine as VS Code. (13.1k stars)
- [just-bash](https://github.com/vercel-labs/just-bash) - Virtual bash environment with in-memory filesystem, written in TypeScript. Full shell syntax (pipes, redirections, loops, functions), 50+ Unix commands (`grep`, `sed`, `awk`, `jq`, etc.), optional Python/JS runtimes — designed for AI agents. [justbash.dev](https://justbash.dev/) (2.3k stars)
- [pascal.js](https://github.com/kanaka/pascal.js) - Pascal compiler implemented in JavaScript.

## Language Interpreters

*Other languages, interpreted in JavaScript:*

- [BiwaScheme](https://github.com/biwascheme/biwascheme) - Scheme interpreter written in JavaScript. (778 stars)
- [LIPS](https://github.com/jcubic/lips) - Scheme-based powerful Lisp interpreter in JavaScript. (487 stars)
- [miniMAL](https://github.com/kanaka/miniMAL) - A delightfully diminutive Lisp, implemented in < 1 KB of JavaScript with JSON source, macros, tail-calls, and JS interop. (638 stars)
- [littlelisp](https://github.com/maryrosecook/littlelisp) - A small Lisp interpreter in JavaScript. (617 stars)
- [WAForth](https://github.com/remko/waforth) - Small but complete dynamic Forth interpreter/compiler for and in WebAssembly. (580 stars)
- [Brython](https://github.com/brython-dev/brython) - Python 3 implementation for client-side web programming (JavaScript-based).
- [Transcrypt](https://github.com/TranscryptOrg/Transcrypt) - Python 3.9 to JavaScript compiler.

## Game Engines & Physics

- [Phaser](https://github.com/phaserjs/phaser) - Fast, free, and fun HTML5 game framework for desktop and mobile browsers.
- [Babylon.js](https://github.com/BabylonJS/Babylon.js) - Powerful, beautiful, and simple 3D game engine built in TypeScript.
- [PlayCanvas](https://github.com/playcanvas/engine) - Fast and lightweight 3D game engine built on WebGL and WebGPU.
- [Excalibur.js](https://github.com/excaliburjs/Excalibur) - Easy-to-use 2D game engine written in TypeScript.
- [Matter.js](https://github.com/liabru/matter-js) - 2D rigid body physics engine for the web.
- [Kaboom.js](https://github.com/replit/kaboom) - JavaScript library for making games fast and fun.

## 3D Graphics & CAD

- [Three.js](https://github.com/mrdoob/three.js) - The most popular 3D library for the web, making WebGL approachable.
- [PixiJS](https://github.com/pixijs/pixijs) - Fast 2D rendering engine using WebGL with a canvas fallback.
- [OpenJSCAD](https://github.com/jscad/OpenJSCAD.org) - Solid 3D CAD modeling in JavaScript — design parametric 3D models with code.
- [A-Frame](https://github.com/aframevr/aframe) - Web framework for building VR/AR experiences using HTML and JavaScript.
- [Deck.gl](https://github.com/visgl/deck.gl) - WebGL-powered framework for visual exploratory data analysis of large datasets.
- [Regl](https://github.com/regl-project/regl) - Functional WebGL abstraction layer.

## GPU & Parallel Computing

- [gpu.js](https://github.com/gpujs/gpu.js) - GPU-accelerated JavaScript — run mathematical computations on the GPU. (15.4k stars)

## Machine Learning & AI

- [TensorFlow.js](https://github.com/tensorflow/tfjs) - Google's TensorFlow machine learning library ported to JavaScript — train and run ML models in the browser and Node.js.
- [Brain.js](https://github.com/BrainJS/brain.js) - GPU-accelerated neural networks in JavaScript.
- [ml5.js](https://github.com/ml5js/ml5-library) - Friendly machine learning for the web, built on TensorFlow.js.
- [Transformers.js](https://github.com/xenova/transformers.js) - Run Hugging Face transformer models (BERT, GPT-2, etc.) directly in the browser.
- [Synaptic](https://github.com/cazala/synaptic) - Architecture-free neural network library for Node.js and the browser.
- [ConvNetJS](https://github.com/karpathy/convnetjs) - Deep learning in the browser (by Andrej Karpathy).

## OCR & Computer Vision

- [Tesseract.js](https://github.com/naptha/tesseract.js) - Pure JavaScript OCR for more than 100 languages — Tesseract reimplemented in JS. (38k stars)
- [jsQR](https://github.com/cozmo/jsQR) - Pure JavaScript QR code reading library — locates, extracts, and parses QR codes from raw images. (4k stars)
- [QuaggaJS](https://github.com/serratus/quaggaJS) - Advanced barcode scanner written in JavaScript. (5.2k stars)

## Desktop Applications

*Thanks to frameworks like Electron and Tauri, JavaScript powers full desktop apps:*

- [Electron](https://github.com/electron/electron) - Build cross-platform desktop apps with JavaScript, HTML, and CSS.
- [VS Code](https://github.com/microsoft/vscode) - Microsoft's code editor — one of the most popular desktop apps ever, built with Electron/TypeScript.
- [Hyper](https://github.com/vercel/hyper) - Terminal emulator built on Electron.
- [Discord](https://discord.com) - Popular chat platform built with Electron.
- [Slack](https://slack.com) - Business messaging app built with Electron.
- [Notion](https://notion.so) - All-in-one workspace, built with Electron.
- [Obsidian](https://obsidian.md) - Knowledge base / note-taking app built with Electron.
- [Bitwarden Desktop](https://github.com/bitwarden/clients) - Open-source password manager desktop client, built with Electron.
- [Tauri](https://github.com/tauri-apps/tauri) - Build smaller, faster desktop apps with a Rust backend and JS frontend.

## Mobile Applications

- [React Native](https://github.com/facebook/react-native) - Build native mobile apps using JavaScript and React.
- [Expo](https://github.com/expo/expo) - Framework and platform for universal React Native apps.
- [Ionic](https://github.com/ionic-team/ionic-framework) - Cross-platform mobile app development with web technologies.
- [Capacitor](https://github.com/ionic-team/capacitor) - Cross-platform native runtime for web apps (Ionic's successor to Cordova).
- [Framework7](https://github.com/framework7io/framework7) - Full-featured mobile HTML framework for building iOS & Android apps.

## Text Editors & IDEs

- [Monaco Editor](https://github.com/microsoft/monaco-editor) - The code editor that powers VS Code, available as a standalone component.
- [CodeMirror](https://github.com/codemirror/codemirror5) - Versatile text editor implemented in JavaScript for the browser.
- [Ace](https://github.com/ajaxorg/ace) - High-performance code editor for the web.
- [StackBlitz](https://stackblitz.com) - Online IDE that runs Node.js entirely in the browser (WebContainers).
- [CodeSandbox](https://codesandbox.io) - Online code editor tailored for web application development.
- [Theia](https://github.com/eclipse-theia/theia) - Cloud & desktop IDE framework implemented in JavaScript/TypeScript.

## Terminal Emulators

- [xterm.js](https://github.com/xtermjs/xterm.js) - Terminal component for the web — powers VS Code's integrated terminal, Hyper, and more.
- [Hyper](https://github.com/vercel/hyper) - Beautiful, extensible terminal built on Electron.
- [Tabby](https://github.com/Eugeny/tabby) - Modern terminal for the modern age, built with Electron and TypeScript.

## Spreadsheets

- [SheetJS](https://github.com/SheetJS/sheetjs) - Spreadsheet data toolkit — parse, generate, and process Excel/CSV/ODS files in JavaScript. (36.2k stars)
- [HyperFormula](https://github.com/handsontable/hyperformula) - Excel-like calculation engine written in TypeScript.
- [Handsontable](https://github.com/handsontable/handsontable) - JavaScript data grid with spreadsheet-like UX.

## Word Processors & Rich Text

- [ProseMirror](https://github.com/ProseMirror/prosemirror) - Toolkit for building rich-text editors, used by the New York Times, Atlassian, and more.
- [Quill](https://github.com/quilljs/quill) - Modern rich text editor built for compatibility and extensibility.
- [TipTap](https://github.com/ueberdosis/tiptap) - Headless, framework-agnostic rich text editor based on ProseMirror.
- [Slate](https://github.com/ianstormtaylor/slate) - Completely customizable framework for building rich text editors.
- [Lexical](https://github.com/facebook/lexical) - Extensible text editor framework from Meta, successor to Draft.js.
- [Editor.js](https://github.com/codex-team/editor.js) - Block-styled editor with a clean JSON output.

## Presentation Software

- [Reveal.js](https://github.com/hakimel/reveal.js) - The HTML presentation framework — create stunning presentations with web technologies.
- [Impress.js](https://github.com/impress/impress.js) - Presentation framework based on CSS3 transforms and transitions, inspired by Prezi.
- [Slidev](https://github.com/slidevjs/slidev) - Presentation slides for developers, powered by Markdown and Vue.
- [Marp](https://github.com/marp-team/marp) - Markdown presentation ecosystem.
- [Spectacle](https://github.com/FormidableLabs/spectacle) - React-based presentation library.

## PDF Tools

- [PDF.js](https://github.com/mozilla/pdf.js) - Mozilla's PDF viewer built with JavaScript and HTML5 — the default PDF reader in Firefox. (53k stars)
- [jsPDF](https://github.com/parallax/jsPDF) - Client-side PDF generation in JavaScript.
- [pdf-lib](https://github.com/Hopding/pdf-lib) - Create and modify PDF documents in JavaScript.
- [PDFKit](https://github.com/foliojs/pdfkit) - JavaScript PDF generation library for Node and the browser. (10.6k stars)
- [pdfmake](https://github.com/bpampuch/pdfmake) - Client/server-side PDF printing in pure JavaScript.

## Image & Video Editing

- [Fabric.js](https://github.com/fabricjs/fabric.js) - Powerful and simple JavaScript HTML5 canvas library, often used for image editors.
- [Konva.js](https://github.com/konvajs/konva) - 2D canvas framework for desktop and mobile applications.
- [Sharp](https://github.com/lovell/sharp) - High-performance image processing in Node.js.
- [Jimp](https://github.com/jimp-dev/jimp) - JavaScript image manipulation library with zero native dependencies.
- [gif.js](https://github.com/jnordberg/gif.js) - JavaScript GIF encoding library. (4.9k stars)

## Audio Codecs & Music

*Audio codecs and synthesizers, reimplemented in JavaScript:*

- [Tone.js](https://github.com/Tonejs/Tone.js) - Web Audio framework for creating interactive music in the browser.
- [Howler.js](https://github.com/goldfire/howler.js) - Audio library for the modern web.
- [Wavesurfer.js](https://github.com/katspaugh/wavesurfer.js) - Navigable waveform audio visualization.
- [Tonal](https://github.com/tonaljs/tonal) - Music theory library for JavaScript.
- [jsmad](https://github.com/nicedayfor/jsmad) - JavaScript MPEG-1 Audio Layer III (MP3) and ID3v2 decoder. (757 stars)
- [mp3.js](https://github.com/audiocogs/mp3.js) - A JavaScript MP3 decoder. (269 stars)

## Video Streaming & Codecs

- [hls.js](https://github.com/video-dev/hls.js) - HLS (HTTP Live Streaming) player in JavaScript — plays HLS in browsers with MSE. (16.6k stars)
- [flv.js](https://github.com/bilibili/flv.js) - HTML5 FLV player — FLV demuxer and H.264/AAC decoder in JavaScript (by Bilibili). (23.2k stars)
- [dash.js](https://github.com/Dash-Industry-Forum/dash.js) - Reference MPEG-DASH client implementation via JavaScript. (5.5k stars)

## Compression & Archives

*zlib, gzip, deflate, zip — all reimplemented in JavaScript:*

- [pako](https://github.com/nodeca/pako) - High-speed zlib port to JavaScript, works in browser & Node.js. (6k stars)
- [fflate](https://github.com/101arrowz/fflate) - High-performance (de)compression in an 8kB package. (2.8k stars)
- [JSZip](https://github.com/Stuk/jszip) - Create, read, and edit .zip files with JavaScript. (10.3k stars)

## Font Engines & Typography

- [opentype.js](https://github.com/opentypejs/opentype.js) - Read and write OpenType fonts using JavaScript. (4.9k stars)
- [fontkit](https://github.com/foliojs/fontkit) - Advanced font engine for Node and the browser. (1.6k stars)

## Format Parsers

*File format parsers, all in pure JavaScript:*

- [Marked](https://github.com/markedjs/marked) - Markdown parser and compiler, built for speed. (36.7k stars)
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser, done right. 100% CommonMark support. (21.2k stars)
- [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - Validate, parse, and build XML without C/C++ libraries. (3k stars)
- [js-yaml](https://github.com/nodeca/js-yaml) - JavaScript YAML parser and dumper. (6.5k stars)
- [Papa Parse](https://github.com/mholt/PapaParse) - Fast and powerful CSV parser that gracefully handles large files. (13.4k stars)
- [Cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible library for parsing and manipulating HTML and XML. (30.2k stars)
- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings in pure JavaScript. (3.1k stars)

## Email Servers & Clients

*SMTP servers and email infrastructure, in JavaScript:*

- [Haraka](https://github.com/haraka/Haraka) - Fast, highly extensible, event-driven SMTP server in JavaScript. (5.6k stars)
- [smtp-server](https://github.com/nodemailer/smtp-server) - Create custom SMTP servers on the fly in Node.js. (907 stars)

## Chat & Communication

- [Mattermost](https://github.com/mattermost/mattermost) - Open-source Slack alternative with a JavaScript/React front-end.
- [Socket.IO](https://github.com/socketio/socket.io) - Real-time bidirectional event-based communication library.

## Video Conferencing

- [Jitsi Meet](https://github.com/jitsi/jitsi-meet) - Open-source video conferencing solution, front-end built with React.
- [LiveKit](https://github.com/livekit/livekit) - Open-source WebRTC infrastructure with JavaScript/TypeScript SDKs.
- [PeerJS](https://github.com/peers/peerjs) - Simple peer-to-peer with WebRTC.

## Torrent Clients & P2P

- [WebTorrent](https://github.com/webtorrent/webtorrent) - Streaming torrent client for the web and Node.js — torrents in your browser.
- [PeerJS](https://github.com/peers/peerjs) - Simplifies WebRTC peer-to-peer data, video, and audio calls.
- [IPFS (Helia)](https://github.com/ipfs/helia) - IPFS implementation in JavaScript.
- [libp2p](https://github.com/libp2p/js-libp2p) - Modular peer-to-peer networking stack in JavaScript.
- [Gun](https://github.com/amark/gun) - Decentralized database for building P2P apps.

## Blockchain & Cryptocurrency

- [ethers.js](https://github.com/ethers-io/ethers.js) - Complete Ethereum library and wallet implementation in JavaScript.
- [web3.js](https://github.com/web3/web3.js) - Ethereum JavaScript API.
- [bcoin](https://github.com/bcoin-org/bcoin) - Full Bitcoin implementation in JavaScript for Node.js and browsers. (3k stars)
- [Bitcore](https://github.com/bitpay/bitcore) - Full stack for Bitcoin and blockchain-based applications. (5k stars)

## Cryptography

*Cryptographic algorithms, reimplemented in pure JavaScript:*

- [OpenPGP.js](https://github.com/openpgpjs/openpgpjs) - OpenPGP implementation for JavaScript. (5.9k stars)
- [node-forge](https://github.com/digitalbazaar/forge) - Native implementation of TLS in JavaScript and tools for crypto-based webapps. (5.3k stars)
- [crypto-js](https://github.com/brix/crypto-js) - JavaScript library of crypto standards (AES, SHA, HMAC, etc.).
- [noble-curves](https://github.com/paulmillr/noble-curves) - Audited, high-performance JavaScript implementation of elliptic curve cryptography.
- [aes-js](https://github.com/ricmoo/aes-js) - Pure JavaScript implementation of AES block cipher and all modes of operation. (1.5k stars)
- [jsrsasign](https://github.com/kjur/jsrsasign) - RSA/ECDSA/DSA signing, ASN.1, PKCS, X.509, CRL, OCSP, CMS, JWS/JWT — all in pure JavaScript. (3.4k stars)
- [bcrypt.js](https://github.com/dcodeIO/bcrypt.js) - Optimized bcrypt in JavaScript with zero dependencies. (3.8k stars)

## Networking & Protocols

*Network protocols reimplemented in JavaScript — SSH, DNS, FTP, HTTP proxies:*

- [ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server modules written in pure JavaScript. (5.8k stars)
- [node-dns](https://github.com/lsongdev/node-dns) - DNS server and client implementation in pure JavaScript with no dependencies. (580 stars)
- [dns-packet](https://github.com/mafintosh/dns-packet) - Encode/decode DNS packets in JavaScript.
- [multicast-dns](https://github.com/mafintosh/multicast-dns) - Low-level multicast-DNS implementation in pure JavaScript. (532 stars)
- [ftp-srv](https://github.com/QuorumDMS/ftp-srv) - Modern FTP server in JavaScript. (395 stars)
- [node-http-proxy](https://github.com/http-party/node-http-proxy) - Full-featured HTTP proxy in JavaScript.
- [Hoppscotch](https://github.com/hoppscotch/hoppscotch) - Open-source API development ecosystem (Postman alternative), built with JavaScript.
- [mqtt.js](https://github.com/mqttjs/MQTT.js) - MQTT client for Node.js and the browser.
- [ws](https://github.com/websockets/ws) - Simple, blazing-fast WebSocket implementation for Node.js.

## File Systems & Version Control

- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - A pure JavaScript implementation of Git for Node.js and browsers. (8.1k stars)
- [memfs](https://github.com/nicedayfor/memfs) - In-memory Node.js `fs` API implementation.

## Containers & Sandboxes

- [WebContainers](https://webcontainers.io) - Node.js runtime that runs entirely in the browser (powers StackBlitz).
- [just-bash](https://github.com/vercel-labs/just-bash) - Sandboxed virtual bash with in-memory filesystem, overlay FS, and configurable network access — runs entirely in-process with no VM overhead. (2.3k stars)
- [Sandpack](https://github.com/codesandbox/sandpack) - Component toolkit for creating live-running code editing experiences (by CodeSandbox).

## Hardware & IoT

- [Johnny-Five](https://github.com/rwaldron/johnny-five) - JavaScript robotics and IoT framework — control Arduinos, Raspberry Pis, and more with JS.
- [Node-RED](https://github.com/node-red/node-red) - Low-code programming for event-driven IoT applications.
- [Firmata.js](https://github.com/firmata/firmata.js) - Firmata protocol implementation in JavaScript for communicating with microcontrollers.

## Robotics

- [Johnny-Five](https://github.com/rwaldron/johnny-five) - The original JavaScript robotics framework.

## Scientific Computing

- [math.js](https://github.com/josdejong/mathjs) - Extensive math library for JavaScript and Node.js — matrices, complex numbers, units, and more.
- [stdlib](https://github.com/stdlib-js/stdlib) - Standard library for JavaScript with numerical and scientific computing utilities.
- [simple-statistics](https://github.com/simple-statistics/simple-statistics) - Statistical methods in JavaScript.
- [JSBI](https://github.com/nicedayfor/nicedayfor) - Pure-JavaScript implementation of BigInt by Google Chrome Labs. (958 stars)

## Data Visualization

- [D3.js](https://github.com/d3/d3) - The gold standard for data visualization on the web.
- [Chart.js](https://github.com/chartjs/Chart.js) - Simple yet flexible JavaScript charting.
- [ECharts](https://github.com/apache/echarts) - Apache's feature-rich interactive charting library.
- [Plotly.js](https://github.com/plotly/plotly.js) - Open-source JavaScript graphing library.
- [Observable Plot](https://github.com/observablehq/plot) - The JavaScript library for exploratory data visualization.
- [Vega](https://github.com/vega/vega) - Visualization grammar — a declarative language for interactive visualization.
- [Sigma.js](https://github.com/jacomyal/sigma.js) - JavaScript library for graph drawing.

## Maps & GIS

- [Leaflet](https://github.com/Leaflet/Leaflet) - The leading open-source JavaScript library for interactive maps.
- [MapLibre GL JS](https://github.com/maplibre/maplibre-gl-js) - Open-source map rendering library using WebGL.
- [OpenLayers](https://github.com/openlayers/openlayers) - High-performance map library for the web.
- [Turf.js](https://github.com/Turfjs/turf) - Advanced geospatial analysis for browsers and Node.js.
- [CesiumJS](https://github.com/CesiumGS/cesium) - JavaScript library for 3D globes and maps.
- [Deck.gl](https://github.com/visgl/deck.gl) - WebGL-powered geospatial visualization.

## Barcode & QR

- [JsBarcode](https://github.com/lindell/JsBarcode) - Barcode generation library written in JavaScript for browser and Node.js. (5.8k stars)
- [jsQR](https://github.com/cozmo/jsQR) - Pure JavaScript QR code reading library. (4k stars)
- [QuaggaJS](https://github.com/serratus/quaggaJS) - Advanced barcode scanner written in JavaScript. (5.2k stars)

## Server-Side Runtimes

- [Node.js](https://github.com/nodejs/node) - The runtime that started it all — JavaScript on the server.
- [Deno](https://github.com/denoland/deno) - Modern JavaScript/TypeScript runtime with security by default (by Node's creator).
- [Bun](https://github.com/oven-sh/bun) - All-in-one JavaScript runtime and toolkit, built for speed.
- [Cloudflare Workers](https://workers.cloudflare.com) - JavaScript at the edge — run JS on Cloudflare's global network.

## Web Servers & Frameworks

- [Express](https://github.com/expressjs/express) - Fast, minimalist web framework for Node.js.
- [Fastify](https://github.com/fastify/fastify) - Fast and low-overhead web framework for Node.js.
- [Hono](https://github.com/honojs/hono) - Ultrafast web framework for the edge.
- [Koa](https://github.com/koajs/koa) - Expressive middleware framework by the Express team.
- [NestJS](https://github.com/nestjs/nest) - Progressive Node.js framework for building scalable server-side applications.
- [Next.js](https://github.com/vercel/next.js) - The React framework for production.
- [Nuxt](https://github.com/nuxt/nuxt) - The Vue framework for production.
- [SvelteKit](https://github.com/sveltejs/kit) - The Svelte framework for production.
- [Astro](https://github.com/withastro/astro) - The web framework for content-driven websites.
- [Remix](https://github.com/remix-run/remix) - Full-stack web framework with nested routing.
- [Hapi](https://github.com/hapijs/hapi) - Framework for building applications and services.
- [AdonisJS](https://github.com/adonisjs/core) - Full-featured web framework for Node.js.

## Bundlers & Build Tools

- [Webpack](https://github.com/webpack/webpack) - The bundler that defined modern JavaScript build tooling.
- [Vite](https://github.com/vitejs/vite) - Next-generation frontend tooling with lightning-fast HMR.
- [Rollup](https://github.com/rollup/rollup) - ES module bundler for JavaScript.
- [esbuild](https://github.com/evanw/esbuild) - Extremely fast bundler (Go core, but JavaScript API and ecosystem).
- [Parcel](https://github.com/parcel-bundler/parcel) - Zero-configuration build tool for the web.
- [Turbopack](https://github.com/vercel/turborepo) - Incremental bundler optimized for JavaScript and TypeScript (by Vercel).
- [Terser](https://github.com/terser/terser) - JavaScript mangler and compressor toolkit.
- [PostCSS](https://github.com/postcss/postcss) - Tool for transforming CSS with JavaScript.

## Package Managers

- [npm](https://github.com/npm/cli) - The default package manager for Node.js.
- [Yarn](https://github.com/yarnpkg/berry) - Fast, reliable package manager (Berry/v2+ is written in JavaScript).
- [pnpm](https://github.com/pnpm/pnpm) - Fast, disk space efficient package manager.
- [Bun](https://github.com/oven-sh/bun) - Also a blazing-fast package manager in addition to being a runtime.

## Testing Frameworks

- [Jest](https://github.com/jestjs/jest) - Delightful JavaScript testing framework by Meta.
- [Vitest](https://github.com/vitest-dev/vitest) - Blazing-fast unit test framework powered by Vite.
- [Mocha](https://github.com/mochajs/mocha) - Simple, flexible JavaScript test framework for Node.js and the browser.
- [Cypress](https://github.com/cypress-io/cypress) - Fast, easy, and reliable E2E testing for anything that runs in a browser.
- [Playwright](https://github.com/microsoft/playwright) - Framework for cross-browser web automation and testing.
- [Puppeteer](https://github.com/puppeteer/puppeteer) - Headless Chrome Node.js API.
- [Storybook](https://github.com/storybookjs/storybook) - Frontend workshop for building UI components and pages in isolation.

## CLI Frameworks

- [Commander.js](https://github.com/tj/commander.js) - The complete solution for Node.js command-line interfaces.
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Collection of common interactive command-line user interfaces.
- [oclif](https://github.com/oclif/oclif) - Framework for building CLIs in Node.js (by Heroku/Salesforce).
- [yargs](https://github.com/yargs/yargs) - Pirate-themed argument parser for Node.js.
- [chalk](https://github.com/chalk/chalk) - Terminal string styling for Node.js.
- [Ink](https://github.com/vadimdemedes/ink) - Build CLI apps with React components.
- [Clack](https://github.com/bombshell-dev/clack) - Effortless, beautiful command-line app components.

## Static Site Generators

- [Gatsby](https://github.com/gatsbyjs/gatsby) - React-based static site generator.
- [Eleventy](https://github.com/11ty/eleventy) - Simpler static site generator, zero client-side JS by default.
- [Hexo](https://github.com/hexojs/hexo) - Fast, simple, and powerful blog framework.
- [VuePress](https://github.com/vuejs/vuepress) - Vue-powered static site generator.
- [Docusaurus](https://github.com/facebook/docusaurus) - Easy to maintain open-source documentation websites (by Meta).

## CMS & Wiki

- [Strapi](https://github.com/strapi/strapi) - Leading open-source headless CMS, fully built in JavaScript.
- [Ghost](https://github.com/TryGhost/Ghost) - Independent publishing platform built in Node.js.
- [Payload](https://github.com/payloadcms/payload) - Headless CMS and application framework built with TypeScript.
- [KeystoneJS](https://github.com/keystonejs/keystone) - Powerful headless CMS for Node.js.
- [Wiki.js](https://github.com/requarks/wiki) - Modern, lightweight, and powerful wiki built on Node.js.
- [Outline](https://github.com/outline/outline) - Fast, collaborative team knowledge base built with React and Node.js.
- [TiddlyWiki](https://github.com/Jermolene/TiddlyWiki5) - Non-linear personal web notebook, entirely in JavaScript.

## ERP & Business Software

- [ERPNext](https://github.com/frappe/erpnext) - Open-source ERP with significant JavaScript front-end (Frappe framework).

---

## Agent Operating Systems

*A new frontier: operating systems purpose-built for AI agents, written in JavaScript.*

- [Rivet agentOS](https://github.com/rivet-dev/agent-os) - Portable open-source operating system for AI agents. ~6 ms cold starts, 32x cheaper than sandboxes. Powered by WebAssembly and V8 isolates. Supports Claude Code, Codex, OpenCode, and more — distributed as a single npm package (`rivetkit`). [rivet.dev/agent-os](https://www.rivet.dev/agent-os/)

---

## Contributing

Contributions welcome! If you know of a project that proves Atwood's Law, open a PR.

## What Qualifies?

A project belongs on this list if:

1. It is primarily written in JavaScript (or TypeScript / compile-to-JS languages)
2. It implements something that was traditionally done in a "lower-level" or different language (e.g., operating systems, databases, compilers, hardware control)
3. It is open-source or at least widely known and notable

---

*If you can think of it, someone has probably already written it in JavaScript.*
