# AnotherPiracyGuide

A guide to digital piracy for the novice. [[Git Mirror]]()

Written by arokai on snahp, written for the snahp.it forum. Feel free to message me with questions or if information here can be improved/corrected. When I began pirating, my only way was through the snahp forum. I didn't understand where uploaders found their content. Those currently in the same position are the target audience of this guide. There are countless ways to pirate, this is just a sample for beginners. 

## Important Notes

- As of now, this guide is very Windows-oriented. This should not be a huge issue, as most referenced tools have Linux and OS X varietes. 
- I have no affliiation to any of the services I recommend, this isn't an advertisment.
- Some knowledge of internet safety and privacy is important for pirates. Though I will mention important aspects and tools in the first section of this guide, do more research on it yourself. A few great starting points are:
    - [r/Piracy wiki](https://www.reddit.com/r/Privacy/wiki/index)
    - [PrivacyTools](https://www.privacytools.io/)
    - [That One Privacy Site](https://thatoneprivacysite.net/about/)
    - [PRISM ⚡ BREAK](https://prism-break.org/en/)
- This guide tries to break things down for those with little experience pirating, while referring them to **select** resources. If you'd prefer long, more comprehensize lists of resources, check out:
    - [r/Piracy wiki](https://www.reddit.com/r/Piracy/wiki/index)
    - [Igglybuff's awesome-piracy](https://github.com/Igglybuff/awesome-piracy)   
 
## 1. Protect Yourself

As I'm sure you're aware, digital piracy of copyrighted material is illegal, to varying degrees depending on where you live. I highly recommend reading up on copyright enforcement in your country. But generally speaking, so long as you only intend to download and not upload content, and take precautionary measures, you will be golden. Skip this section if you don't care about internet privacy and safety :(

### Ad-blocking

I make do with the ad-blocker built into the [Brave browser](https://brave.com/), but I cannot recommend enough to you [uBlock Origin](https://github.com/gorhill/uBlock), a browser extension that can block ads. Installation instructions are within the link. It is very feature rich, and so if you are only looking to block ads, do not bother with the many configurations. After installing it should be enabled by default.

### Sandboxes and Virtual Machines

Just downloaded pirated software or a game, and don't entirely trust the source you got it from? While I cannot recommend downloading from sources you don't entirely trust, if you insist on it, sandbox software and virtual machines can make it safer. 

**Sandboxes**

A sandbox creates an isolated environment on your computer. Running programs inside of one prevents the program from effecting other parts of your system. I recommend using [Sandboxie](https://www.sandboxie.com/DownloadSandboxie). After installation, using it is as simple as finding the program you want to run sandboxed, right clicking it, and hitting "Run Sandboxed".

**Virutal Machines**

A virtual machine can run a second, virtual computer within your real computer. Though a different concept, you can use a virtual machine for the same purposes as a sandbox. If you accidentally download and run a program with viruses, only the virtual machine will be infected, not your physical system. It's a bit more technical, and requires more processing power, but could be useful as a dedicated space for pirated software. I recommend [VirtualBox](https://www.virtualbox.org/wiki/Downloads). Here are a few guides to get you started:

- [Official Documentation](https://www.virtualbox.org/manual/UserManual.html)
- [The Beginner's Guide to Creating Virtual Machines with VirtualBox](https://lifehacker.com/the-beginners-guide-to-creating-virtual-machines-with-v-5204434)
- [A Complete Guide to Using VirtualBox](https://www.nakivo.com/blog/use-virtualbox-quick-overview/)

### Virtual Private Networks (VPN)

From Wikipedia:
> ["A virtual private network (VPN) extends a private network across a public network and enables users to send and receive data across shared or public networks as if their computing devices were directly connected to the private network."](https://en.wikipedia.org/wiki/Virtual_private_network)

But that's a little technical for some people. What you need to know, is that a VPN can protect your location and identity from sites and tools you use, by changing your [IP Address](https://simple.wikipedia.org/wiki/IP_address). While it sounds like a godsend, it's crucial to remember that there is no such thing as complete anonymity on the internet. Because your VPN provider can still see your data, a VPN is only as secure as it's provider is trustworthy. However despite it's insecurities, VPNs can still be helpful and even necessary in specific situations. Namely while torrenting, but more on that in the [torrenting section](). Please review [this information](https://www.privacytools.io/providers/vpn/#info) about VPNs before purchasing one or discounting them altogether. 

If you decide a VPN would be useful for you, please purchase one. Free VPN providers are significantly more likely to dishonor no-log policies and sell your data. Refer to That One Privacy Guy's [VPN comparison chart](https://thatoneprivacysite.net/#simle-vpn-comparison) when choosing one. Once you've purchased a VPN and installed the application for it, use is usually as simple as clicking 1 button to enable it.

### The Onion Project (TOR)

Not to be confused with [torrenting](), Tor is a computer network that serves to keep it's users anonymous. When you browse the internet with Tor, your internet traffic is sent through 3 of Tor's computers, called Tor relays, before it reaches it's intended destination. This design ensures that no 2 of the relays know about the other, so that traffic cannot be traced back to you. Rest assured, this is a secure by design system. Issues typically only occur when it's users are careless. Learn more about that [here](https://www.youtube.com/watch?v=-uDYvy2jQzM).

Tor is primarily used with the [Tor browser](https://www.torproject.org/). Please understand that when using the Tor browser, only your browser data is being encrypted. Other data sent through other apps on your device will not be encrypted with Tor. If Tor is blocked in your area, or if you don't want your internet provider to know that you're using Tor, read up on [Tor Bridges](https://tb-manual.torproject.org/bridges/) before you install Tor. 

To learn more about Tor and how it works: [Myth-busting Tor](https://write.privacytools.io/my-thoughts-on-security/slicing-onions-part-1-myth-busting-tor).

## 2. Tools/Methods

### Direct Download Managers

Some pirate sites host content on their own servers, but most simply list links to content stored on file hosters/clouds, such as [MEGA](https://mega.nz/start), [MediaFire](https://www.mediafire.com/), [Google Drive](https://www.google.com/drive/), etc. While you can download content from these file hosters in-browser, there is a better way. Download managers, of course, allow you to manage your downloads (pause, resume, stop, etc.), and can sometimes raise download speeds and bypass download limits. Some of these managers attempt to grab all downloads from any given link, while others were created for specific services. For many of these programs, use is as simple as pasting a link and clicking a button. Here are a few recommendations:

- [JDownloader 2](https://jdownloader.org/jdownloader2) - General download manager.
    - \+ Large support community
    - \+ Extensive set of features and plugins
    - \+ High compatibility
    - \- Outdated gui
- [MegaDownlaoder](https://mega.nz/file/QrJExCAI#jMaDpNUJc68otKJduevyWlTLRI1tKhdyqVykIWAhwio) - Download manager for [MEGA](https://mega.nz/start).
    - \+ Faster than downloading in-browser (in my experience) 
    - \+ Download multiple files at once
    - \+ Can bypass download limits by stopping a download, activating a VPN, and resuming the download
- [Air Explorer](https://www.airexplorer.net/en/download/) - While this isn't exclusively a downloader, it is an easy way to move files to and from your pc and a file hoster, or between file hoster to file hoster. 
    - \+ Windows file manager styled gui
    - \+ Can connect multiple accounts for each file hoster
    - \+ Snahp members can get the pro version [here](https://forum.snahp.it/viewtopic.php?f=40&t=222126&hilit=air+explorer)
- [deemix](https://deemix.app/) - Download manager for [Deezer](https://www.deezer.com/en/).
    - \+ 
    - \+ Clean gui
    - \+ Snahp members can find pre-built versions [here](https://forum.snahp.it/viewtopic.php?f=40&t=226887)
    - \- Barebones, few features
- [4k Video Downloader]() - Download manager for Youtube, Vimeo, Daily Motion, and other video sharing sites.
    - \
    - \
    - \
- [Internet Download Manager]() - General download manager. 
    - \+ Snahp members can find it [here](https://forum.snahp.it/viewtopic.php?f=40&t=222267)

### Torrent/P2P



https://github.com/Bonfire-GTK/newpirates

## 3. Pirate Sites

Sites that list **pirated** content. These sites are where you'll find links to use in download managers and torrent clients. Again, you can find much longer lists on [r/piracy](https://www.reddit.com/r/Piracy/wiki/index) and [awesome-piracy](https://github.com/Igglybuff/awesome-piracy), but here are a handful of recommendations. I consider these some of the better sites, but that's subjective. These labels should be obvious, but just in case:

- [STREAM] A site that allows you to watch/listen/read content, no download necessary.
- [DDL] A sites lists content available to be downloaded directly from the site or through a file hoster/cloud.
- [TORRENT] A site that lists .torrent files and magnet links for content.

### Movies/TV

### Music

### Video Games

## 4. Other Guides

As I've established, this guide is something to start you off, but there are many more guides which delve deep into specific topics within piracy. 
