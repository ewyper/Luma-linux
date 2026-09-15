# Luma Linux

**Linux for everyone.**

Luma Linux is a beginner-friendly Linux distribution designed to be easy to use without requiring deep Linux knowledge.

## Vision

Luma Linux aims to make Linux accessible to everyone.

Users should be able to install the system, choose their preferred desktop environment, install software, update the system, connect hardware, play games, and get things done without needing to understand every technical detail of Linux.

## Built from the ground up

Luma Linux is being developed from the ground up, following the principles of Linux From Scratch.

The system is built from source with its own toolchain, configuration, package infrastructure, and system design.

## Desktop environments

Luma Linux is planned to support multiple desktop environments, including:

- KDE Plasma
- GNOME
- XFCE

The user will be able to choose a desktop environment during installation.

## Software compatibility

Luma Linux aims to make software installation simple for beginners.

The long-term goal is to provide a unified way to install software from different Linux package formats, including:

- `.deb`
- `.rpm`
- `.pkg.tar.zst`
- AppImage
- Flatpak
- Luma packages

Users should not need to understand which package manager or distribution a piece of software was originally made for.

## Luma Package System

Luma will eventually have its own native package system and repositories.

The package system will provide:

- Installation
- Removal
- Updates
- Dependency management
- Repository management
- Security and integrity verification

## Current status

Luma Linux is currently in early development.

The initial goal is to build a minimal self-hosting Linux system from source before working on the desktop environment, installer, package ecosystem, and graphical user experience.

## Roadmap

### Phase 0 — Bootstrap

- [x] Build target binutils
- [x] Build initial GCC
- [x] Install Linux userspace headers
- [ ] Build and integrate glibc
- [ ] Complete the initial toolchain

### Phase 1 — Minimal Luma

- [ ] Core userspace
- [ ] Basic system utilities
- [ ] Shell
- [ ] Filesystem layout
- [ ] System initialization
- [ ] Basic boot process

### Phase 2 — Self-hosting

- [ ] Complete compiler toolchain
- [ ] Build Luma using Luma
- [ ] Remove dependency on the Arch host for normal builds

### Phase 3 — Luma OS

- [ ] Linux kernel
- [ ] Networking
- [ ] Storage
- [ ] Audio
- [ ] USB
- [ ] Bluetooth
- [ ] Printing
- [ ] Hardware support

### Phase 4 — Desktop

- [ ] KDE Plasma
- [ ] GNOME
- [ ] XFCE
- [ ] Display manager
- [ ] Graphics stack
- [ ] Desktop integration

### Phase 5 — Software ecosystem

- [ ] Luma package format
- [ ] Package manager
- [ ] Official repositories
- [ ] Graphical software center
- [ ] Package updates
- [ ] Cross-format software installation

### Phase 6 — Installer

- [ ] Graphical installer
- [ ] Disk partitioning
- [ ] User creation
- [ ] Desktop selection
- [ ] System configuration
- [ ] Bootloader setup

### Phase 7 — Luma 1.0

- [ ] Stable release
- [ ] Installation ISO
- [ ] Documentation
- [ ] Security updates
- [ ] Update infrastructure
- [ ] Beginner-friendly default experience

## Development

Luma Linux is currently developed using an Arch Linux host system.

Build artifacts, downloaded sources, and generated root filesystems are intentionally kept outside the Git repository.

## Contributing

Luma Linux is an open-source project.

Contributions, ideas, testing, documentation, and feedback will be welcome as the project develops.

## Long-term goal

The goal of Luma Linux is simple:

> Make Linux easy enough that anyone can use it.

**Linux for everyone.**
