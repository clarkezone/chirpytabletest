---
layout: post
title: "MacOS software setup 2025"
date: 2023-10-17
categories: [macos, setup, software]
---

I use Mac's, PC's and Linux machines and from time to time i "repave" with a clean OS and clean app installs.  It can be interesting to track how the "initial install" changes for an any given OS over time, hence I decided to document this for next time both as a record for myself as well as to share it with you in case there is anything interesting.

## Core Productivity Tools

| Install Order | Application | Description | App Web Link |
|--------------|-------------|-------------|-------------|
| 1 | <img src="https://tailscale.com/favicon.ico" width="64" alt="Tailscale"><br>[Tailscale](https://tailscale.com) | A zero-config VPN for building secure networks, connecting your devices and securing your services without the hassle of traditional VPNs. **Clarkezone Take:** Tailscale is the first install for me on all devices as it's how all my devices connect to each other and to private services I self host at home. |n|
| 2 | <img src="https://bitwarden.com/favicon.ico" width="64" alt="Bitwarden"><br>[Bitwarden](https://bitwarden.com) | A secure open-source password manager that helps you store, generate, and autofill passwords across all your devices. **Clarkezone Take:** My prefered password manager. |y|
| 3 | <img src="https://www.craft.do/favicon.ico" width="64" alt="Craft"><br>[Craft](https://www.craft.do) | A beautiful and powerful document editor that helps you organize your thoughts, projects, and ideas with rich formatting options. **Clarkezone Take:** I have tried many note taking and task management apps. Craft is the best one I've found so far if you are primarily on a Mac. If I could have only one app on a Mac it would be this. |y|
| 4 | <img src="https://flexibits.com/favicon.ico" width="64" alt="Fantastical"><br>[Fantastical](https://flexibits.com) | A powerful calendar app with natural language processing, allowing you to quickly add events and manage your schedule. **Clarkezone Take:** Fantastical is what a calendar app should be. Native UI, thoughtful handling of multiple services and calendars e.g. from iCloud and Google calendar, and natural language input for events.  This recently came out for Windows and is on my list to try there. |y|
| 5 | <img src="https://dayoneapp.com/wp-content/themes/day-one-app/assets/img/day-one-app-logo.svg"  alt="Day One"><br>[Day One](https://dayoneapp.com) | A journaling app that helps you record your life with text, photos, and location data in a beautiful interface. **Clarkezone Take:** Prefered diarying solution. |y|

## Core Development GUI Tools

| Install Order | Application | Description | App Web Link |
|--------------|-------------|-------------|-------------|
| 1 | <img src="https://zed.dev/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo_icon.d67dc948.webp&w=32&q=100" width="64" alt="Zed"><br>[Zed](https://zed.dev/) | A high-performance, collaborative code editor designed for speed and modern collaboration. **Clarkezone Take:** Even though it's early in the development timeline I love Zed because its a modern editor written in Rust using native UI and hence is lightnig fast.  It's being developed by Nathan Sobo and some of the folks who did the [Atom code editor](https://atom-editor.cc) as well as folks like Max Brunsfeld who did [Tree Sitter](https://tree-sitter.github.io/tree-sitter/).  Zed is evolving rapidly and I have no doubt it will continue to gain adoption and popularity. |n|
| 2 | <img src="https://developer.apple.com/assets/elements/icons/xcode-12/xcode-12-96x96_2x.png" width="64" alt="Xcode"><br>[Xcode](https://developer.apple.com) | Apple's integrated development environment for creating apps for macOS, iOS, watchOS, and tvOS. **Clarkezone Take:** The more I use XCode the more I like it even though it took a lot of getting used to initially when coming from Visual Studio. |y|
| 3 | <img src="https://ghostty.org/favicon.ico" width="64" alt="Ghostty"><br>[Ghostty](https://ghostty.org) | A fast, feature-rich terminal emulator designed for developers with modern UI elements. **Clarkezone Take:** I came across Ghostty as part of my quest to learn the Zig programming language.  It was written by [Mitchell Hashimoto](https://mitchellh.com/) of Hashicorp fame and is [lives up to the promise of being fast and feature rich](https://ghostty.org/docs/about). Certainly significantly better option than Alacritty. |n|
| 4 | <img src="https://ghostty.org/favicon.ico" width="64" alt="Ghost remote"><br>Ghost remote | Terminal connection utility using the command: `infocmp -x \| ssh YOUR-SERVER -- tic -x -` **Clarkezone Take:** Needed to support Linux servers correctly. |n|
| 5 | <img src="https://wakatime.com/apple-touch-icon.png" width="64" alt="Wakatime"><br>[Wakatime for Mac](https://wakatime.com) | An automatic time tracking tool that measures your programming activity across different editors and projects. **Clarkezone Take:** Wakatime integrates with all of my code editors to give me stats on how long I spend working on different projects. |n|
| 6 | <img src="https://lmstudio.ai/favicon.ico" width="64" alt="LM Studio"><br>[LM Studio](https://lmstudio.ai) | A desktop app for running and experimenting with large language models locally on your device. **Clarkezone Take:** LM Studio is a tool for running open source AI models locally which is a good way of experimenting with the rapidly evolving space.  I like it because it uses [Apple's MLX framework](https://github.com/lmstudio-ai/mlx-engine) to leverage the full hardware acceleration of Apple Silicon |n|
| 7 | <img src="https://code.visualstudio.com/favicon.ico" width="64" alt="VSCode"><br>[VSCode](https://code.visualstudio.com) | Microsoft's powerful code editor with support for debugging, syntax highlighting, and thousands of extensions. **Clarkezone Take:** VS Code is required for any modern dev environment.  I'm not a fan of [electron-based](https://www.electronjs.org) software in general but have to make an exception here. |n|

## Core Development CLI Tools

| Install Order | Tool | Description | App Web Link |
|--------------|------|-------------|-------------|
| 1 | <img src="https://atuin.sh/_astro/atuin.4e0ff728.png" width="64" alt="Atuin"><br>[atuin](https://atuin.sh) | A magical shell history that synchronizes across all your machines. **Clarkezone Take:** For those of us who use CLI history as a way of saving time and recalling obscure parameters we know we used to start a container proviously, Atuin is great and a big step up from bash or zsh's default ctrl-r menu, for example session or directory based recall as well as some neat stats visualizations. It also solves a major pain point with using multiple dev-boxes by enabling syncing either via an encrypted cloud service or a selfhostable version. |n|
| 2 | <img src="https://brew.sh/assets/img/homebrew-256x256.png" width="64" alt="Homebrew"><br>[brew](https://brew.sh) | The missing package manager for macOS, allowing easy installation of software and tools. **Clarkezone Take:** Brew is mandatory for development on MacOS. |n|
| 3 | <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="64" alt="GitHub CLI"><br>[gh](https://cli.github.com) | GitHub's official command-line tool to interact with GitHub repositories from the terminal. **Clarkezone Take:** gh is the best way to interact with GitHub from the CLI. |n|
| 4 | <img src="https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png" width="64" alt="Git"><br>[git](https://git-scm.com) | Distributed version control system for tracking changes in source code during development. |n|
| 5 | git completions | Command-line completions for git commands for faster workflow. |n|
| 6 | gh completions | Command-line completions for GitHub CLI commands. |n|
| 7 | <img src="https://raw.githubusercontent.com/containers/podman/main/logo/podman-logo.png" width="64" alt="Podman"><br>[podman](https://podman.io) | A daemonless container engine for developing, managing, and running OCI containers. **Clarkezone Take:** Podman is better than docker and not encumbered by restrictive licensing terms. |n|
| 8 | podman completions | Command-line completions for Podman commands. |n|
| 9 | <img src="https://raw.githubusercontent.com/kubernetes/kubernetes/master/logo/logo.png" width="64" alt="Kubernetes"><br>[kubectl](https://kubernetes.io/docs/reference/kubectl/) | Command-line tool for running commands against Kubernetes clusters. **Clarkezone Take:** Since my home infra uses self-hosted Kubernetes clusters I need this. |n|
| 10 | kubectl completions | Command-line completions for Kubernetes commands. |n|
| 11 | Kubeconfig for cluster4 | Configuration file for accessing the Kubernetes cluster4. |n|
| 12 | NAS | Access configuration for NASMKii storage system. |n|
| 13 | SSH key for Linux devbox | SSH authentication keys for accessing the devbox. |n|

## Video Production & Creative

| Install Order | Application | Description | App Web Link |
|--------------|-------------|-------------|-------------|
| 1 | <img src="https://pro-cdn.pixelmator.com/web-assets/app-icons/navigation/icon_pro-2.0--v6.png" width="64" alt="Pixelmator"><br>[Pixelmator](https://www.pixelmator.com) | A powerful, full-featured image editor with tools for enhancing photos, drawing, and creating graphic designs. | |y|
| 2 | <img src="https://www.blackmagicdesign.com/favicon.ico" width="64" alt="Blackmagic ATEM"><br>Blackmagic Cloud Store Setup | Cloud collaboration tools for DaVinci Resolve projects, allowing teams to work together remotely. | |n|
| 3 | <img src="https://www.blackmagicdesign.com/favicon.ico" width="64" alt="Blackmagic ATEM"><br>Blackmagic Converters | Blackmagic Design's software for configuring video conversion hardware. | |n|
| 4 | <img src="https://www.blackmagicdesign.com/favicon.ico" width="64" alt="Blackmagic ATEM"><br>Blackmagic Hyperdeck | Control software for Blackmagic Design's HyperDeck video recorders. | |n|
| 5 | <img src="https://www.blackmagicdesign.com/favicon.ico" width="64" alt="Blackmagic ATEM"><br>Blackmagic Desktop Video | Blackmagic Design's software for configuring capture and playback devices. | |n|
| 6 | <img src="https://www.blackmagicdesign.com/favicon.ico" width="64" alt="Blackmagic ATEM"><br>[Blackmagic Atem software control](https://www.blackmagicdesign.com/products/atemproduction) | Control software for Blackmagic Design's ATEM video switchers. | |n|
| 7 | <img src="https://www.blackmagicdesign.com/favicon.ico" width="64" alt="DaVinci Resolve"><br>[Resolve Studio](https://www.blackmagicdesign.com/products/davinciresolve) | Professional video editing, color correction, visual effects, and audio post-production software. | |n|
| 9 | <img src="https://www.midasconsoles.com/.resources/musictribe-templates/webresources/logos/header-logo-midas.svg" width="64" alt="Midas M32"><br>[Midas M32 edit](https://www.midasconsoles.com/product.html?modelCode=P0B3I) | Control software for the Midas M32 digital mixing console. | |n|
| 10 | [Dante controller](https://www.audinate.com/products/software/dante-controller) | Network configuration and routing software for Dante audio networking. | |n|
| 11 | <img src="https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/92/35/81/923581a4-895b-843f-9324-7af9cbd1a302/AppIcon-0-0-1x_U007epad-0-0-0-1-0-85-220.png/512x512bb.jpg" width="64" alt="Mixeffect Pro"><br>[Mixeffect pro](https://mixeffect.app) | Advanced control software for Blackmagic Design ATEM switchers. | |y|
| 12 | <img src="https://www.insta360.com/favicon.ico" width="64" alt="Insta360 Studio"><br>[Insta360 Studio](https://www.insta360.com/download/insta360-studio) | Editing software for 360° content from Insta360 cameras. | |n|
| 13 | <img src="https://cdn.sanity.io/images/sv8q1vrl/production/0d14c744641528511db506ce61c28d7b43174bcd-800x800.png?w=1440&q=90&auto=format" width="64" alt="Sidas Link Pro"><br>[Sidas Link Pro](https://www.sidas.com) | Professional video linking and synchronization software. | |y|
| 14 | <img src="https://rive.app/favicon.ico" width="64" alt="Rive"><br>[Rive](https://rive.app) | Create interactive animations for apps, games, and websites. | |y|
| 15 | <img src="https://help.apple.com/assets/6679A72E92E641B6D907CD0C/6679A72FE32D2BB3610F762B/en_US/97f5f4dfe6df84d78caacff68ec63538.png" width="64" alt="Final Cut Pro"><br>[Final Cut Pro](https://www.apple.com/final-cut-pro/) | Apple's Final Cut Pro, a professional video editing software for macOS. | |y|
| 16 | <img src="https://help.apple.com/assets/6679A6C176DE195EB80B2223/6679A6C476DE195EB80B2229/en_US/0744c3b7afa6c7476e97365930e89917.png" width="64" alt="Compressor"><br>[Compressor](https://www.apple.com/final-cut-pro/compressor/) | Apple's advanced video and audio encoding tool for Final Cut Pro projects. | |y|
| 17 | <img src="https://cdn.jim-nielsen.com/macos/512/motion-2013-05-22.png?rf=512" width="64" alt="Motion"><br>[Motion](https://www.apple.com/final-cut-pro/motion/) | Apple's motion graphics software for creating stunning visual effects and animations. | |y|
| 18 | <img src="https://help.apple.com/assets/65564B8E462A5E4F0E03C9BF/65564B949E2FD3ED2404CF23/en_US/390711ce08c61bf054d3dc4dfb9080ae.png" width="64" alt="Logic Pro"><br>[Logic Pro](https://www.apple.com/logic-pro/) | Apple's professional digital audio workstation for recording, editing, and mixing music. | |y|
| 19 | <img src="https://www.adobe.com/content/dam/cc/icons/Adobe_Corporate_Horizontal_Red_HEX.svg" width="64" alt="Adobe Creative Cloud"><br>[Adobe Creative Cloud](https://www.adobe.com/creativecloud.html) | Suite of apps for graphic design, video editing, web development, photography, and more. | |n|

## Communication

| Install Order | Application | Description | App Web Link |
|--------------|-------------|-------------|-------------|
| 1 | <img src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/636e0a6a49cf127bf92de1e2_icon_clyde_blurple_RGB.png" width="64" alt="Discord"><br>[Discord for MacOS](https://discord.com/download) | A communication platform designed for creating communities with text, voice, and video chat. | |y|
| 2 | <img src="https://bsky.app/static/apple-touch-icon.png" width="64" alt="Bluesky"><br>[Bluesky](https://bsky.app) | A decentralized social network focused on customizability and user control. | |y|
| 3 | <img src="https://telegram.org/img/t_logo.png" width="64" alt="Telegram"><br>[Telegram for MacOS](https://macos.telegram.org) | A cloud-based messaging app with a focus on speed, security, and cross-platform availability. | |y|
| 4 | <img src="https://tapbots.com/img/appicon_ivory@2x.png" width="64" alt="Ivory"><br>[Ivory](https://tapbots.com/ivory/) | An elegant Mastodon client for the decentralized social web. | |y|
| 5 | <img src="https://abs.twimg.com/responsive-web/client-web/icon-default.ee534d8a.png" width="64" alt="X"><br>[X for MacOS](https://twitter.com/download) | The platform formerly known as Twitter for news, entertainment, sports, and social conversation. | |y|
| 6 | <img src="https://static.whatsapp.net/rsrc.php/v3/yP/r/rYZqPCBaG70.png" width="64" alt="WhatsApp"><br>[Whatsapp for MacOS](https://www.whatsapp.com/download) | A cross-platform messaging app for sending text, voice messages, media, and making calls. | |y|
| 7 | <img src="https://scontent-sea1-1.xx.fbcdn.net/v/t39.8562-6/473331855_950586116633330_4827030958030583698_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=f537c7&_nc_ohc=x8JEsE_RTukQ7kNvgHjn0k7&_nc_oc=AdiHJoSPeJ5V60C9pr_HLRdxv9WVVcE97ElRS2-j6b-2UY_dP33MAJ5VkKYhyYCP2kA&_nc_zt=14&_nc_ht=scontent-sea1-1.xx&_nc_gid=ATNuVwfhQlzSxZgO7rhgIEt&oh=00_AYFsKa2sfIfF_AJCpWIlyHgncPo41oVSHLUopSJaA-Kc0A&oe=67D60DCC" width="64" alt="FB Messenger"><br>[FB Messenger for MacOS](https://www.messenger.com/desktop) | Facebook's messaging platform for text, voice, and video communication. | |y|
| 8 | <img src="https://signal.org/assets/images/favicon/favicon-32x32.png" width="64" alt="Signal"><br>[Signal for MacOS](https://signal.org/download/) | A privacy-focused messaging app with end-to-end encryption for secure communications. | |n|
| 9 | <img src="https://st1.zoom.us/zoom.ico" width="64" alt="Zoom"><br>[Zoom for MacOS](https://zoom.us/download) | A video conferencing platform for virtual meetings, webinars, and online events. | |n|
| 10 | <img src="https://mimestream.com/assets/icons/app-icon_96x96.png" width="64" alt="Mimestream"><br>[Mimestream for MacOS](https://mimestream.com) | A native macOS email client specifically designed for Gmail accounts with a modern interface. | |n|

## Content

| Install Order | Application | Description | App Web Link |
|--------------|-------------|-------------|-------------|
| 1 | <img src="https://macautomationtips.com/wp-content/uploads/2020/06/kindle-icon-png-28.jpg.png" width="64" alt="Kindle"><br>[Kindle for MacOS](https://www.amazon.com/kindle-dbs/fd/kcp) | Amazon's e-reader app giving access to millions of books, magazines, and documents. | |y|
| 2 | <img src="https://us1.discourse-cdn.com/flex026/uploads/firecore/original/3X/4/6/46ffd8cb3893cfaffeb5d66c3a5ced7ecc2cd37b.png" width="64" alt="Infuse"><br>[Infuse](https://firecore.com/infuse) | A beautiful media player that organizes and plays video files from various sources. | |y|
| 3 | <img src="https://cdn.jim-nielsen.com/macos/1024/reeder-5-2021-02-24.png?rf=1024" width="64" alt="Reeder"><br>[Reeder for MacOS](https://www.reederapp.com) | An elegant RSS reader application for following websites and news sources. | |y|

## Utilities

| Install Order | Application | Description | App Web Link |
|--------------|-------------|-------------|-------------|
| 1 | <img src="https://downloads.econtechnologies.com/media/ProductLogos/CS/ChronoSync-4.6-Logo-256.png" width="64" alt="Chronosync"><br>[Chronosync](https://www.econtechnologies.com/chronosync/overview.html) | A robust file synchronization and backup tool for macOS with scheduling capabilities. | |n|
| 2 | <img src="https://software.charliemonroe.net/favicon.ico" width="64" alt="Downie"><br>[Downie](https://software.charliemonroe.net/downie/) | A video downloader that can extract videos from thousands of websites. | |n|
| 3 | <img src="https://rogueamoeba.com/global/images/icons/128/fission@2x.png" width="64" alt="Fission"><br>[Fission](https://rogueamoeba.com/fission/) | A fast and efficient audio editor for trimming, joining, and converting audio files. | |n|
| 4 | <img src="https://edovia.com/en/screens/images/s5-icon@2x.png" width="64" alt="Screens 5"><br>[Screens 5](https://edovia.com/en/screens-mac/) | A remote desktop application that allows controlling other computers from your Mac. | |n|

## Crypto

| Install Order | Application | Description | App Web Link |
|--------------|-------------|-------------|-------------|
| 1 | <img src="https://play-lh.googleusercontent.com/mHjR3KaAMw3RGA15-t8gXNAy_Onr4ZYUQ07Z9fG2vd51IXO5rd7wtdqEWbNMPTgdqrk=s96" width="64" alt="Ledger Live"><br>[Ledger Live](https://www.ledger.com/ledger-live) | Companion app for Ledger hardware wallets to manage crypto assets securely. | |n|
| 2 | Phantom and Backpack Wallets | Cryptocurrency wallet applications for storing and managing digital assets. | | |
| 3 | <img src="https://brave.com/static-assets/images/brave-favicon.png" width="64" alt="Brave Browser"><br>[Brave Browser](https://brave.com) | A privacy-focused web browser with built-in ad blocking and cryptocurrency features. | |n|

## Additional Development Tools

| Install Order | Tool | Description | App Web Link |
|--------------|------|-------------|-------------|
| 1 | <img src="https://cdn.prod.website-files.com/63f9f100025c058594957cca/678aaa797078b2df8e171b2d_mojo-chip.png" width="64" alt="Mojo Lang"><br>[Mojo Lang](https://www.modular.com/mojo) | Modern programming language for AI development with Python compatibility. **Clarkezone Take:** Mojo is a super interesting emerging language conceived by [[Chris Lattner](https://en.wikipedia.org/wiki/Chris_Lattner)]() and based on [[LLVM](https://llvm.org)]() and [MLIR]([https://mlir.llvm.org](https://mlir.llvm.org)). It is syntax compatible with Python but offers static typing, compilation to native binaries, memory safety and supports not only CPU but also targets such as GPU, NPU. It is interesting to me because it eliminates the need for models to have a mix of Python (for ease of development and iteration), C++ (for deploying performance-critical kernels) and CUDA for targeting GPUs. |n|
| 2 | Mojo completions | Command-line completions for Magic Mojo commands. |n|
| 3 | <img src="https://neovim.io/favicon.ico" width="64" alt="NeoVim"><br>[NeoVim](https://neovim.io) | Hyperextensible Vim-based text editor focused on extensibility and usability. **Clarkezone Take:** VIM is the best terminal based editor (clearly :-)) and Neovim is the modern evolving offshoot of this classic with great extensibility via [lua]([https://www.lua.org](https://www.lua.org)). My config uses [Lazy](https://lazy.folke.io) and can be found [here.](https://github.com/clarkezone/neovimconfig/tree/lazyport) I love [the Primagen's hilarious YouTube channel](https://youtube.com/@thevimeagen?si=vjynJNCEYKynPSUs) about the merits of VIM. |n|
| 4 | <img src="https://starship.rs/icon.png" width="64" alt="Starship"><br>[Starship](https://starship.rs) | A minimal, blazing-fast, and customizable prompt for any shell. **Clarkezone Take:** A better prompt written in Rust. |n|
| 5 | <img src="https://zellij.dev/img/logo.png" width="64" alt="Zellij"><br>[Zelij](https://zellij.dev) | A terminal workspace with batteries included, featuring multiplexer capabilities. **Clarkezone Take:** Experimenting with this as a replacement for [TMUX]([https://github.com/tmux/tmux/wiki](https://github.com/tmux/tmux/wiki)). |n|
| 6 | <img src="https://astro.build/favicon.svg" width="64" alt="Astro"><br>[TryAstro](https://astro.build) | A tool for exploring and testing applications built with the Astro web framework. **Clarkezone Take:** Analytics for the Apple AppStore that help research for indi-dev app ideas. |n|
| 7 | <img src="https://developer.apple.com/assets/elements/icons/testflight/testflight-64x64.png" width="64" alt="TestFlight"><br>[TestFlight for MacOS](https://developer.apple.com/testflight/) | Apple's platform for testing beta versions of apps before they're released on the App Store. |n|
| 8 | <img src="https://developer.apple.com/favicon.ico" width="64" alt="Apple Developer"><br>[Apple Developer for MacOS](https://developer.apple.com/download/) | Apple's developer app providing access to documentation, videos, and developer news. |n|
| 9 | <img src="https://developer.apple.com/assets/elements/icons/sf-symbols-2/sf-symbols-2-96x96_2x.png" width="64" alt="SF Symbols"><br>[SF Symbols for MacOS](https://developer.apple.com/sf-symbols/) | Apple's library of iconography designed to integrate with San Francisco, the system font for Apple platforms. |n|
| 10 | <img src="https://ziglang.org/zig-logo-dark.svg" width="64" alt="Zig"><br>[Zig](https://ziglang.org/) | A general-purpose programming language and toolchain designed for robustness, optimality, and maintainability. **Clarkezone Take:** Ziglang is another emerging language by [Andrew Kelly](https://andrewkelley.me) that I have been learning. Simpler than Rust, compiler can be used as a drop-in replacement for C/C++ compilers, comptime is an interesting take on metaprogramming. |n|
| 11 | <img src="https://docs.cline.bot/~gitbook/image?url=https%3A%2F%2F4166387734-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Forganizations%252FrgVlhNxyw0L04cM3O4Jf%252Fsites%252Fsite_dW8OB%252Flogo%252FrXSlzT3Gv2BIozlxKe8s%252Fnew_cline_icon.webp%3Falt%3Dmedia%26token%3Dad888ddb-a2e7-499e-9991-33df7ef37da3&width=260&dpr=2&quality=100&sign=21d3575c&sv=2" width="64" alt="Cline"><br>[Cline](https://github.com/clarkezone/cline) | A command-line interface tool for enhancing developer productivity. **Clarkezone Take:** Cline takes agentic AI to the next level and has been a game changer for me. It uses openrouter to abstract different LLM backend services and associated token purchasing, supports Anthropic's [Model Contaxt Protocol]([https://www.anthropic.com/news/model-context-protocol](https://www.anthropic.com/news/model-context-protocol)) to reach into and reason over different tools and environments. It can also leverage local tools on your devbox as part of it's multi-stage reasoning. |n|
| 12 | <img src="https://dotnet.microsoft.com/favicon.ico" width="64" alt=".NET"><br>[.NET 9](https://dotnet.microsoft.com/) | Microsoft's cross-platform development framework for building various types of applications. **Clarkezone Take:** I mainly use this on Linux and Windows installs so typically only install on the Mac via [devcontainers](https://code.visualstudio) |n|
