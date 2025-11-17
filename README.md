# Lex-Ex
**Linux For Legal WorkFlows**


Lex-Ex is a Debian-based desktop operating system purpose-built for lawyers, law firms, and legal researchers. Designed with stability, privacy, and professional workflows in mind, it merges the reliability of Debian with a curated suite of open-source applications optimized for document management, communication, research, and productivity.

**Core Philosophy**
Freedom. Focus. Forensics.

Lex-Ex brings the legal desktop into the open-source age — replacing bloatware and fragmentation with a unified, secure, and well-structured environment. Every element — from PDF handling to time tracking and encrypted communication — is configured out of the box for real legal practice.

**Key Features**
1. Law-Ready Workspace
A fully curated “LawWare” stack pre-installed and pre-configured:
Email & Calendar: Geary + GNOME Calendar with online account integration.
Office Suite: OnlyOffice for Word, Excel, PowerPoint, and ODF files (set as default).
PDF & Scanning: OCRmyPDF, NAPS2, PDF Mix Tool, and PDF4Qt for scan, merge, OCR, and split workflows.
Document Review Tools: Eloquent (Bible-style viewer), FocusWriter, Planify, SuperProductivity, and TimeTracker for drafting and workflow tracking.
Multimedia & Reference: VLC, Eye of GNOME, Upscayl, Warp, and Pictures Converter GTK for exhibits and evidence preparation.

2. Lightweight and Bloat-Free
All non-essential packages (games, chat clients, redundant media tools, etc.) are purged.
Lex-Ex starts clean and professional — no distractions, no trialware, no unnecessary services.

3. Secure and Managed
Webmin pre-installed for web-based system administration. (accessable at Port 10000 type Hostname -I on your terminal to see your local IP)
UFW Firewall auto-enabled with preconfigured rules for local access and SSH management.
VPN Ready: Full OpenVPN, WireGuard, IPsec, and L2TP support preloaded.

4. Built for Productivity
Dark Mode toggle applet pre-installed for quick theme switching.
Sticky Notes Desklet active on the desktop for case memos and daily notes.
Preloaded Cinnamon desktop with optimized Orchis theme + Papirus icon set.
One-click access to Flathub and Snap for easy software expansion.

5. Branding and Professional Polish
System branding proudly identifies Lex-Ex:
Custom splash screen, GRUB background, wallpapers, and lock screens.
Unified icon and logo across Cinnamon menus and system UI.
Themed defaults applied globally (root, live, and user environments).

**System Architecture & Base**

Base: Debian 13 (“Trixie”)
Desktop: Cinnamon + LightDM
Kernel: Linux 6.x (non-free firmware enabled)
Theme: Orchis GTK with Papirus icons


**Installation and Deployment**

Lex-Ex can be booted as a Live ISO or installed to disk using the standard Debian installer. The ISO may be found at our SourceForge page: https://sourceforge.net/projects/lex-ex/files/alpha_amd64/ 


All system defaults, themes, and branding are embedded for persistence across all user profiles 
Developers and administrators can re-create or customize the distro using the build sequence outlined below:
Enable Flathub and Snap support
Purge bloatware
Install LawWare stack (Apt, Flatpak, and custom repos)
Apply theme and branding
Configure defaults (office, browser, calendar, mail, media)
Activate Webmin, UFW, and VPN tools

**License & Credits::
License: GNU/GPL (Other Applications distributed under compatible open-source or permissive licenses)
Author / Maintainer: Ajay Kumar
Homepage: (https://github.com/thatlawyerfellow/Lex-Ex/)

**Mission**
To empower lawyers, legal researchers, and policy professionals with a complete, private, and open computing environment — one that’s fast, elegant, and built to serve the modern legal mind.
