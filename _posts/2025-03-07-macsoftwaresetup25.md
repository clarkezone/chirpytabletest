---
layout: post
title: "MacOS software setup 2025"
date: 2023-10-17
categories: [macos, setup, software]
---

I use Mac's, PC's and Linux machines and from time to time i "repave" with a clean OS and clean app installs.  It can be interesting to track how the "initial install" changes for an any given OS over time, hence I decided to document this for next time both as a record for myself as well as to share it with you in case there is anything interesting.

## Core Productivity Tools

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | [Tailscale](https://tailscale.com) | <img src="https://tailscale.com/favicon.ico" width="64" alt="Tailscale"> | A zero-config VPN for building secure networks, connecting your devices and securing your services without the hassle of traditional VPNs. | Tailscale is the first install for me on all devices as it's how all my devices connect to each other and to private services I self host at home. |y|
| 2 | [Bitwarden](https://bitwarden.com) | <img src="https://bitwarden.com/favicon.ico" width="64" alt="Bitwarden"> | A secure open-source password manager that helps you store, generate, and autofill passwords across all your devices. | My prefered password manager. |y|
| 3 | [Craft](https://www.craft.do) | <img src="https://www.craft.do/favicon.ico" width="64" alt="Craft"> | A beautiful and powerful document editor that helps you organize your thoughts, projects, and ideas with rich formatting options. | I have tried many note taking and task management apps. Craft is the best one I've found so far if you are primarily on a Mac. If I could have only one app on a Mac it would be this. |y|
| 4 | [Fantastical](https://flexibits.com) | <img src="https://flexibits.com/favicon.ico" width="64" alt="Fantastical"> | A powerful calendar app with natural language processing, allowing you to quickly add events and manage your schedule. | Fantastical is what a calendar app should be. Native UI, thoughtful, centralized place for all my calendars from iCloud and Google calendar. |y|
| 5 | [Day One](https://dayoneapp.com) | <img src="https://dayoneapp.com/wp-content/themes/day-one-app/assets/img/day-one-app-logo.svg"  alt="Day One"> | A journaling app that helps you record your life with text, photos, and location data in a beautiful interface. | In order to funciton day to day, I lean on my journal as a place I can capture thoughts and feelings. Day one is my prefered solution. |y|

## Core Development GUI Tools

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | [Zed](https://zed.dev/) | <img src="https://zed.dev/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo_icon.d67dc948.webp&w=32&q=100" width="64" alt="Zed"> | A high-performance, collaborative code editor designed for speed and modern collaboration. | |y|
| 2 | [Xcode](https://developer.apple.com) | <img src="https://developer.apple.com/assets/elements/icons/xcode-12/xcode-12-96x96_2x.png" width="64" alt="Xcode"> | Apple's integrated development environment for creating apps for macOS, iOS, watchOS, and tvOS. | |y|
| 3 | [Ghostty](https://ghostty.org) | <img src="https://ghostty.org/favicon.ico" width="64" alt="Ghostty"> | A fast, feature-rich terminal emulator designed for developers with modern UI elements. | |y|
| 4 | Ghost remote | <img src="https://ghostty.org/favicon.ico" width="64" alt="Ghost remote"> | Terminal connection utility using the command: `infocmp -x \| ssh YOUR-SERVER -- tic -x -` | | |
| 5 | [Wakatime for Mac](https://wakatime.com) | <img src="https://wakatime.com/apple-touch-icon.png" width="64" alt="Wakatime"> | An automatic time tracking tool that measures your programming activity across different editors and projects. | |y|
| 6 | [LM Studio](https://lmstudio.ai) | <img src="https://lmstudio.ai/favicon.ico" width="64" alt="LM Studio"> | A desktop app for running and experimenting with large language models locally on your device. | |y|
| 7 | [VSCode](https://code.visualstudio.com) | <img src="https://code.visualstudio.com/favicon.ico" width="64" alt="VSCode"> | Microsoft's powerful code editor with support for debugging, syntax highlighting, and thousands of extensions. | |y|

## Core Development CLI Tools

| Install Order | Tool | Screenshot | Description | Why | App Web Link |
|--------------|------|------------|-------------|-----|-------------|
| 1 | [atuin](https://atuin.sh) | <img src="https://atuin.sh/_astro/atuin.4e0ff728.png" width="64" alt="Atuin"> | A magical shell history that synchronizes across all your machines. | |y|
| 2 | [brew](https://brew.sh) | <img src="https://brew.sh/assets/img/homebrew-256x256.png" width="64" alt="Homebrew"> | The missing package manager for macOS, allowing easy installation of software and tools. | Brew is mandatory for development on MacOS. |y|
| 3 | [gh](https://cli.github.com) | <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="64" alt="GitHub CLI"> | GitHub's official command-line tool to interact with GitHub repositories from the terminal. | gh is the best way to interact with GitHub from the CLI. |y|
| 4 | [git](https://git-scm.com) | <img src="https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png" width="64" alt="Git"> | Distributed version control system for tracking changes in source code during development. | |y|
| 5 | git completions | | Command-line completions for git commands for faster workflow. | Needs no explanation. |y|
| 6 | gh completions | | Command-line completions for GitHub CLI commands. | |y|
| 7 | [podman](https://podman.io) | <img src="https://raw.githubusercontent.com/containers/podman/main/logo/podman-logo.png" width="64" alt="Podman"> | A daemonless container engine for developing, managing, and running OCI containers. | Podman is better than docker and not encumbered by restrictive licensing terms. |y|
| 8 | podman completions | | Command-line completions for Podman commands. | | |
| 9 | [kubectl](https://kubernetes.io/docs/reference/kubectl/) | <img src="https://raw.githubusercontent.com/kubernetes/kubernetes/master/logo/logo.png" width="64" alt="Kubernetes"> | Command-line tool for running commands against Kubernetes clusters. | Since my home infra uses self-hosted Kubernetes clusters I need this. |y|
| 10 | kubectl completions | | Command-line completions for Kubernetes commands. | | |
| 11 | Kubeconfig for cluster4 | | Configuration file for accessing the Kubernetes cluster4. | | |
| 12 | NAS | | Access configuration for NASMKii storage system. | | |
| 13 | SSH key for Linux devbox | | SSH authentication keys for accessing the devbox. | | |

## Video Production & Creative

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | [Pixelmator](https://www.pixelmator.com) | <img src="https://pro-cdn.pixelmator.com/web-assets/app-icons/navigation/icon_pro-2.0--v6.png" width="64" alt="Pixelmator"> | A powerful, full-featured image editor with tools for enhancing photos, drawing, and creating graphic designs. | |y|
| 2 | Blackmagic Cloud Store Setup | | Cloud collaboration tools for DaVinci Resolve projects, allowing teams to work together remotely. | | |
| 3 | Blackmagic Converters | | Blackmagic Design's software for configuring video conversion hardware. | | |
| 4 | Blackmagic Hyperdeck | | Control software for Blackmagic Design's HyperDeck video recorders. | | |
| 5 | Blackmagic Desktop Video | | Blackmagic Design's software for configuring capture and playback devices. | | |
| 6 | [Blackmagic Atem software control](https://www.blackmagicdesign.com/products/atemproduction) | <img src="https://www.blackmagicdesign.com/favicon.ico" width="64" alt="Blackmagic ATEM"> | Control software for Blackmagic Design's ATEM video switchers. | |y|
| 7 | [Resolve Studio](https://www.blackmagicdesign.com/products/davinciresolve) | <img src="https://www.blackmagicdesign.com/favicon.ico" width="64" alt="DaVinci Resolve"> | Professional video editing, color correction, visual effects, and audio post-production software. | |y|
| 9 | [Midas M32 edit](https://www.midasconsoles.com/product.html?modelCode=P0B3I) | <img src="https://www.midasconsoles.com/.resources/musictribe-templates/webresources/logos/header-logo-midas.svg" width="64" alt="Midas M32"> | Control software for the Midas M32 digital mixing console. | |y|
| 10 | [Dante controller](https://www.audinate.com/products/software/dante-controller) | <img src="https://www.audinate.com/sites/default/files/favicon.ico" width="64" alt="Dante Controller"> | Network configuration and routing software for Dante audio networking. | |y|
| 11 | [Mixeffect pro](https://mixeffect.app) | <img src="https://mixeffect.app/favicon.ico" width="64" alt="Mixeffect Pro"> | Advanced control software for Blackmagic Design ATEM switchers. | |y|
| 12 | [Insta360 Studio](https://www.insta360.com/download/insta360-studio) | <img src="https://www.insta360.com/favicon.ico" width="64" alt="Insta360 Studio"> | Editing software for 360° content from Insta360 cameras. | |y|
| 13 | [Sidas Link Pro](https://www.sidas.com) | <img src="https://cdn.sanity.io/images/sv8q1vrl/production/0d14c744641528511db506ce61c28d7b43174bcd-800x800.png?w=1440&q=90&auto=format" width="64" alt="Sidas Link Pro">| Professional video linking and synchronization software. | |y|
| 14 | [Rive](https://rive.app) | <img src="https://rive.app/favicon.ico" width="64" alt="Rive"> | Create interactive animations for apps, games, and websites. | |y|
| 15 | [Final Cut Pro](https://www.apple.com/final-cut-pro/) | <img src="https://www.apple.com/v/final-cut-pro/l/images/overview/icon_fcpx__d3q8crehfvqq_large.png" width="64" alt="Final Cut Pro"> | Apple's Final Cut Pro, a professional video editing software for macOS. | |y|
| 16 | [Compressor](https://www.apple.com/final-cut-pro/compressor/) | <img src="https://www.apple.com/v/final-cut-pro/l/images/overview/icon_compressor__fxfvx3qqcz6q_large.png" width="64" alt="Compressor"> | Apple's advanced video and audio encoding tool for Final Cut Pro projects. | |y|
| 17 | [Motion](https://www.apple.com/final-cut-pro/motion/) | <img src="https://www.apple.com/v/final-cut-pro/l/images/overview/icon_motion__f0lj9wlqgy6q_large.png" width="64" alt="Motion"> | Apple's motion graphics software for creating stunning visual effects and animations. | |y|
| 18 | [Logic Pro](https://www.apple.com/logic-pro/) | <img src="https://www.apple.com/v/logic-pro/j/images/overview/hero_icon__c0xut3azleeu_large.png" width="64" alt="Logic Pro"> | Apple's professional digital audio workstation for recording, editing, and mixing music. | |y|
| 19 | [Adobe Creative Cloud](https://www.adobe.com/creativecloud.html) | <img src="https://www.adobe.com/content/dam/cc/icons/Adobe_Corporate_Horizontal_Red_HEX.svg" width="64" alt="Adobe Creative Cloud"> | Suite of apps for graphic design, video editing, web development, photography, and more. | |y|

## Communication

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | [Discord for MacOS](https://discord.com/download) | <img src="https://discord.com/assets/favicon.ico" width="64" alt="Discord"> | A communication platform designed for creating communities with text, voice, and video chat. | |y|
| 2 | [Bluesky](https://bsky.app) | <img src="https://bsky.app/favicon.ico" width="64" alt="Bluesky"> | A decentralized social network focused on customizability and user control. | |y|
| 3 | [Telegram for MacOS](https://macos.telegram.org) | <img src="https://telegram.org/img/favicon.ico" width="64" alt="Telegram"> | A cloud-based messaging app with a focus on speed, security, and cross-platform availability. | |y|
| 4 | [Ivory](https://tapbots.com/ivory/) | <img src="https://tapbots.com/favicon.ico" width="64" alt="Ivory"> | An elegant Mastodon client for the decentralized social web. | |y|
| 5 | [X for MacOS](https://twitter.com/download) | <img src="https://abs.twimg.com/responsive-web/client-web/icon-default.ee534d8a.png" width="64" alt="X"> | The platform formerly known as Twitter for news, entertainment, sports, and social conversation. | |y|
| 6 | [Whatsapp for MacOS](https://www.whatsapp.com/download) | <img src="https://static.whatsapp.net/rsrc.php/v3/yP/r/rYZqPCBaG70.png" width="64" alt="WhatsApp"> | A cross-platform messaging app for sending text, voice messages, media, and making calls. | |y|
| 7 | [FB Messenger for MacOS](https://www.messenger.com/desktop) | <img src="https://static.xx.fbcdn.net/rsrc.php/v3/y8/r/R_1BAhxMP5I.png" width="64" alt="FB Messenger"> | Facebook's messaging platform for text, voice, and video communication. | |y|
| 8 | [Signal for MacOS](https://signal.org/download/) | <img src="https://signal.org/assets/images/favicon/favicon-32x32.png" width="64" alt="Signal"> | A privacy-focused messaging app with end-to-end encryption for secure communications. | |y|
| 9 | [Zoom for MacOS](https://zoom.us/download) | <img src="https://st1.zoom.us/zoom.ico" width="64" alt="Zoom"> | A video conferencing platform for virtual meetings, webinars, and online events. | |y|
| 10 | [Mimestream for MacOS](https://mimestream.com) | <img src="https://mimestream.com/assets/img/favicon.png" width="64" alt="Mimestream"> | A native macOS email client specifically designed for Gmail accounts with a modern interface. | |y|

## Content

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | [Kindle for MacOS](https://www.amazon.com/kindle-dbs/fd/kcp) | <img src="https://m.media-amazon.com/images/G/01/kindle/merch/2019/KPW/kpw-2019-gw-feature-1344x526._CB437317395_.jpg" width="64" alt="Kindle"> | Amazon's e-reader app giving access to millions of books, magazines, and documents. | |y|
| 2 | [Infuse](https://firecore.com/infuse) | <img src="https://firecore.com/favicon.ico" width="64" alt="Infuse"> | A beautiful media player that organizes and plays video files from various sources. | |y|
| 3 | [Reeder for MacOS](https://www.reederapp.com) | <img src="https://www.reederapp.com/mac5/assets/img/reeder5-mac-icon.png" width="64" alt="Reeder"> | An elegant RSS reader application for following websites and news sources. | |y|

## Utilities

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | [Chronosync](https://www.econtechnologies.com/chronosync/overview.html) | | A robust file synchronization and backup tool for macOS with scheduling capabilities. | | |
| 2 | [Downie](https://software.charliemonroe.net/downie/) | | A video downloader that can extract videos from thousands of websites. | | |
| 3 | [Fission](https://rogueamoeba.com/fission/) | | A fast and efficient audio editor for trimming, joining, and converting audio files. | | |
| 4 | [Screens 5](https://edovia.com/en/screens-mac/) | | A remote desktop application that allows controlling other computers from your Mac. | | |

## Crypto

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | [Ledger Live](https://www.ledger.com/ledger-live) | <img src="https://www.ledger.com/wp-content/uploads/2022/04/cropped-Ledger-favicon-32x32.png" width="64" alt="Ledger Live"> | Companion app for Ledger hardware wallets to manage crypto assets securely. | |y|
| 2 | Phantom and Backpack Wallets | | Cryptocurrency wallet applications for storing and managing digital assets. | | |
| 3 | [Brave Browser](https://brave.com) | <img src="https://brave.com/static-assets/images/brave-favicon.png" width="64" alt="Brave Browser"> | A privacy-focused web browser with built-in ad blocking and cryptocurrency features. | |y|

## Additional Development Tools

| Install Order | Tool | Screenshot | Description | Why | App Web Link |
|--------------|------|------------|-------------|-----|-------------|
| 1 | [Mojo Lang](https://www.modular.com/mojo) | <img src="https://www.modular.com/static/favicon.ico" width="64" alt="Mojo Lang"> | Modern programming language for AI development with Python compatibility. | Mojo is a super interesting emerging language conceived by [[Chris Lattner](https://en.wikipedia.org/wiki/Chris_Lattner)]() and based on [[LLVM](https://llvm.org)]() and [MLIR]([https://mlir.llvm.org](https://mlir.llvm.org)). It is syntax compatible with Python but offers static typing, compilation to native binaries, memory safety and supports not only CPU but also targets such as GPU, NPU. It is interesting to me because it eliminates the need for models to have a mix of Python (for ease of development and iteration), C++ (for deploying performance-critical kernels) and CUDA for targeting GPUs. |y|
| 2 | Mojo completions | | Command-line completions for Magic Mojo commands. | | |
| 3 | [NeoVim](https://neovim.io) | <img src="https://neovim.io/favicon.ico" width="64" alt="NeoVim"> | Hyperextensible Vim-based text editor focused on extensibility and usability. | VIM is the best terminal based editor (clearly :-)) and Neovim is the modern evolving offshoot of this classic with great extensibility via [lua]([https://www.lua.org](https://www.lua.org)). My config uses [Lazy](https://lazy.folke.io) and can be found [here.](https://github.com/clarkezone/neovimconfig/tree/lazyport) I love [the Primagen's hilarious YouTube channel](https://youtube.com/@thevimeagen?si=vjynJNCEYKynPSUs) about the merits of VIM. |y|
| 4 | [Starship](https://starship.rs) | <img src="https://starship.rs/favicon.ico" width="64" alt="Starship"> | A minimal, blazing-fast, and customizable prompt for any shell. | A better prompt written in Rust. |y|
| 5 | [Zelij](https://zellij.dev) | <img src="https://zellij.dev/img/logo.png" width="64" alt="Zellij"> | A terminal workspace with batteries included, featuring multiplexer capabilities. | Experimenting with this as a replacement for [TMUX]([https://github.com/tmux/tmux/wiki](https://github.com/tmux/tmux/wiki)). |y|
| 6 | [TryAstro](https://astro.build) | <img src="https://astro.build/favicon.svg" width="64" alt="Astro"> | A tool for exploring and testing applications built with the Astro web framework. | Analytics for the Apple AppStore that help research for indi-dev app ideas. |y|
| 7 | [TestFlight for MacOS](https://developer.apple.com/testflight/) | <img src="https://developer.apple.com/assets/elements/icons/testflight/testflight-64x64.png" width="64" alt="TestFlight"> | Apple's platform for testing beta versions of apps before they're released on the App Store. | |y|
| 8 | [Apple Developer for MacOS](https://developer.apple.com/download/) | <img src="https://developer.apple.com/favicon.ico" width="64" alt="Apple Developer"> | Apple's developer app providing access to documentation, videos, and developer news. | |y|
| 9 | [SF Symbols for MacOS](https://developer.apple.com/sf-symbols/) | <img src="https://developer.apple.com/design/human-interface-guidelines/foundations/sf-symbols/images/sf-symbols-intro_2x.png" width="64" alt="SF Symbols"> | Apple's library of iconography designed to integrate with San Francisco, the system font for Apple platforms. | |y|
| 10 | [Zig](https://ziglang.org/) | <img src="https://ziglang.org/zig-logo-dark.svg" width="64" alt="Zig"> | A general-purpose programming language and toolchain designed for robustness, optimality, and maintainability. | Ziglang is another emerging language by [Andrew Kelly](https://andrewkelley.me) that I have been learning. Simpler than Rust, compiler can be used as a drop-in replacement for C/C++ compilers, comptime is an interesting take on metaprogramming. |y|
| 11 | [Cline](https://github.com/clarkezone/cline) | <img src="https://raw.githubusercontent.com/clarkezone/cline/main/assets/cline.png" width="64" alt="Cline"> | A command-line interface tool for enhancing developer productivity. | Cline takes agentic AI to the next level and has been a game changer for me. It uses openrouter to abstract different LLM backend services and associated token purchasing, supports Anthropic's [Model Contaxt Protocol]([https://www.anthropic.com/news/model-context-protocol](https://www.anthropic.com/news/model-context-protocol)) to reach into and reason over different tools and environments. It can also leverage local tools on your devbox as part of it's multi-stage reasoning. |y|
| 12 | [.NET 9](https://dotnet.microsoft.com/) | <img src="https://dotnet.microsoft.com/favicon.ico" width="64" alt=".NET"> | Microsoft's cross-platform development framework for building various types of applications. | I mainly use this on Linux and Windows installs so typically only install on the Mac via [devcontainers]([https://code.visualstudio.com/docs/devcontainers/containers](https://code.visualstudio.com/docs/devcontainers/containers)) or as a last resort if needed. |y|

## Additional Productivity

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | [Goodnotes](https://www.goodnotes.com) | <img src="https://www.goodnotes.com/favicon.ico" width="64" alt="Goodnotes"> | A digital note-taking app that allows you to write, draw, annotate PDFs, and organize your notes. | |y|
| 2 | [MindNode](https://www.mindnode.com) | <img src="https://mindnode.com/static/favicon.ico" width="64" alt="MindNode"> | A mind mapping app that helps you organize your thoughts and visualize your ideas. | |y|
