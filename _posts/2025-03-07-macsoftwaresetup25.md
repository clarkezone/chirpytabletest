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
| 1 | brew | | The missing package manager for macOS, allowing easy installation of software and tools. | Brew is mandatory for development on MacOS. |y|
| 2 | gh | | GitHub's official command-line tool to interact with GitHub repositories from the terminal. | gh is the best way to interact with GitHub from the CLI. |y|
| 3 | git | | Distributed version control system for tracking changes in source code during development. | |y|
| 4 | git completions | | Command-line completions for git commands for faster workflow. | Needs no explanation. |y|
| 5 | gh completions | | Command-line completions for GitHub CLI commands. | |y|
| 6 | podman | | A daemonless container engine for developing, managing, and running OCI containers. | Podman is better than docker and not encumbered by restrictive licensing terms. |y|
| 7 | podman completions | | Command-line completions for Podman commands. | | |
| 8 | kubectl | | Command-line tool for running commands against Kubernetes clusters. | Since my home infra uses self-hosted Kubernetes clusters I need this. |y|
| 9 | kubectl completions | | Command-line completions for Kubernetes commands. | | |
| 10 | Kubeconfig for cluster4 | | Configuration file for accessing the Kubernetes cluster4. | | |
| 11 | NASMKii access | | Access configuration for NASMKii storage system. | | |
| 12 | SSH key for devbox5 | | SSH authentication keys for accessing the devbox5 development machine. | | |

## Video Production & Creative

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | Pixelmator | | A powerful, full-featured image editor with tools for enhancing photos, drawing, and creating graphic designs. | |y|
| 2 | Blackmagic Cloud Store Setup | | Cloud collaboration tools for DaVinci Resolve projects, allowing teams to work together remotely. | | |
| 3 | Blackmagic Converters | | Blackmagic Design's software for configuring video conversion hardware. | | |
| 4 | Blackmagic Hyperdeck | | Control software for Blackmagic Design's HyperDeck video recorders. | | |
| 5 | Blackmagic Desktop Video | | Blackmagic Design's software for configuring capture and playback devices. | | |
| 6 | Blackmagic Atem software control | | Control software for Blackmagic Design's ATEM video switchers. | |y|
| 7 | Resolve Studio | | Professional video editing, color correction, visual effects, and audio post-production software. | |y|
| 9 | Midas M32 edit | | Control software for the Midas M32 digital mixing console. | |y|
| 10 | Dante controller | | Network configuration and routing software for Dante audio networking. | |y|
| 11 | Mixeffect pro | | Advanced control software for Blackmagic Design ATEM switchers. | |y|
| 12 | Insta360 Studio | | Editing software for 360° content from Insta360 cameras. | |y|
| 13 | Sidas Link Pro | | Professional video linking and synchronization software. | |y|
| 14 | Rive | | Create interactive animations for apps, games, and websites. | |y|
| 15 | Final Cut Pro | | Apple's Final Cut Pro, a professional video editing software for macOS. | |y|
| 16 | Compressor | | Apple's advanced video and audio encoding tool for Final Cut Pro projects. | |y|
| 17 | Motion | | Apple's motion graphics software for creating stunning visual effects and animations. | |y|
| 18 | Logic Pro | | Apple's professional digital audio workstation for recording, editing, and mixing music. | |y|
| 19 | Adobe Creative Cloud | | Suite of apps for graphic design, video editing, web development, photography, and more. | |y|

## Communication

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | Discord for MacOS | | A communication platform designed for creating communities with text, voice, and video chat. | |y|
| 2 | Bluesky | | A decentralized social network focused on customizability and user control. | |y|
| 3 | Telegram for MacOS | | A cloud-based messaging app with a focus on speed, security, and cross-platform availability. | |y|
| 4 | Ivory | | An elegant Mastodon client for the decentralized social web. | |y|
| 5 | X for MacOS | | The platform formerly known as Twitter for news, entertainment, sports, and social conversation. | |y|
| 6 | Whatsapp for MacOS | | A cross-platform messaging app for sending text, voice messages, media, and making calls. | |y|
| 7 | FB Messenger for MacOS| | Facebook's messaging platform for text, voice, and video communication. | |y|
| 8 | Signal for MacOS | | A privacy-focused messaging app with end-to-end encryption for secure communications. | |y|
| 9 | Zoom for MacOS | | A video conferencing platform for virtual meetings, webinars, and online events. | |y|
| 10 | Mimestream for MacOS | | A native macOS email client specifically designed for Gmail accounts with a modern interface. | |y|

## Content

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | Kindle for MacOS | | Amazon's e-reader app giving access to millions of books, magazines, and documents. | |y|
| 2 | Infuse | | A beautiful media player that organizes and plays video files from various sources. | |y|
| 3 | Reeder for MacOS | | An elegant RSS reader application for following websites and news sources. | |y|

## Utilities

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | Chronosync | | A robust file synchronization and backup tool for macOS with scheduling capabilities. | | |
| 2 | Downie | | A video downloader that can extract videos from thousands of websites. | | |
| 3 | Fission | | A fast and efficient audio editor for trimming, joining, and converting audio files. | | |
| 4 | Screens 5 | | A remote desktop application that allows controlling other computers from your Mac. | | |

## Crypto

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | Ledger Live | | Companion app for Ledger hardware wallets to manage crypto assets securely. | |y|
| 2 | Phantom and Backpack Wallets | | Cryptocurrency wallet applications for storing and managing digital assets. | | |
| 3 | Brave Browser | | A privacy-focused web browser with built-in ad blocking and cryptocurrency features. | |y|

## Additional Development 

| Install Order | Tool | Screenshot | Description | Why | App Web Link |
|--------------|------|------------|-------------|-----|-------------|
| 1 | Mojo Lang | | Modern programming language for AI development with Python compatibility. | |y|
| 2 | Mojo completions | | Command-line completions for Magic Mojo commands. | | |
| 3 | NeoVim | | Hyperextensible Vim-based text editor focused on extensibility and usability. | |y|
| 4 | Atuin | | A magical shell history that synchronizes across all your machines. | |y|
| 5 | Starship | | A minimal, blazing-fast, and customizable prompt for any shell. | |y|
| 6 | Zelij | | A terminal workspace with batteries included, featuring multiplexer capabilities. | |y|
| 7 | TryAstro | | A tool for exploring and testing applications built with the Astro web framework. | |y|
| 8 | TestFlight for MacOS | | Apple's platform for testing beta versions of apps before they're released on the App Store. | |y|
| 9 | Apple Developer for MacOS | | Apple's developer app providing access to documentation, videos, and developer news. | |y|
| 10 | SF Symbols for MacOS | | Apple's library of iconography designed to integrate with San Francisco, the system font for Apple platforms. | |y|

## Additional Productivity

| Install Order | Application | Screenshot | Description | Why | App Web Link |
|--------------|-------------|------------|-------------|-----|-------------|
| 1 | Goodnotes | | A digital note-taking app that allows you to write, draw, annotate PDFs, and organize your notes. | |y|
| 2 | MindNode | | A mind mapping app that helps you organize your thoughts and visualize your ideas. | |y|
