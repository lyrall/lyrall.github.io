# Internet Privacy and Safety

## Required Reading

- Check out my [Basic Pirate Literacy Guide](bpl-guide.md), it is the second pre-requisite guide of the set. 
- As with the rest of these guides, this will be very Windows 10 oriented. 
- Internet privacy and safety is a bigger topic than I can get my head around. What I am laying out here are very basic tools that will keep you out of trouble as a pirate, but that's about it. I beg that you invest more time into the topic for yourself:
    - [PrivacyTools](https://www.privacytools.io/) (Visit this site first!)
    - [r/Piracy wiki](https://www.reddit.com/r/Privacy/wiki/index)
    - [That One Privacy Site](https://thatoneprivacysite.net/about/)
    - [PRISM ⚡ BREAK](https://prism-break.org/en/)
- If you learn better from videos, check out [this guide]() on securing your devices and internet traffic.

As I'm sure you're aware, digital piracy of copyrighted material is illegal, to varying degrees depending on where you live. I highly recommend reading up on copyright enforcement in your country. But generally speaking, so long as you only intend to download and not upload content, and take precautionary measures, you will be golden. Copyright enforcement is sparce for end-users such as you and I, with the exception of torrenting. But I give proper [warning about torrenting](bpl-guide.md#WARNING) in my Basic Pirate Literacy Guide.

## Ad-blocking

I make do with the ad-blocker built into the [Brave browser](https://brave.com/), but I cannot recommend enough to you [uBlock Origin](https://github.com/gorhill/uBlock), a browser extension that can block ads. Installation instructions are within the link. It is very feature rich, and so if you are only looking to block ads, do not bother with the many configurations. After installing, it should be enabled by default.

## Sandboxes and Virtual Machines

Just downloaded pirated software or a game, and don't entirely trust the source you got it from? While I cannot recommend downloading from sources you don't entirely trust, if you insist on it, sandbox software and virtual machines can make it safer. 

### Sandboxes

A sandbox creates an isolated environment on your computer. Running programs inside of one prevents the program from effecting other parts of your system. I recommend using [Sandboxie](https://www.sandboxie.com/DownloadSandboxie). After installation, using it is as simple as finding the program you want to run sandboxed, right clicking it, and hitting "Run Sandboxed".

### Virutal Machines

A virtual machine can run a second, virtual computer within your real computer. Though a different concept, you can use a virtual machine for the same purposes as a sandbox. If you accidentally download and run a program with viruses, only the virtual machine will be infected, not your physical system. It's a bit more technical, and requires more processing power, but could be useful as a dedicated space for pirated software. I recommend [VirtualBox](https://www.virtualbox.org/wiki/Downloads). Here are a few guides to get you started:

- [Official Documentation](https://www.virtualbox.org/manual/UserManual.html)
- [The Beginner's Guide to Creating Virtual Machines with VirtualBox](https://lifehacker.com/the-beginners-guide-to-creating-virtual-machines-with-v-5204434)
- [A Complete Guide to Using VirtualBox](https://www.nakivo.com/blog/use-virtualbox-quick-overview/)

## Virtual Private Networks (VPN)

From Wikipedia:
> ["A Virtual Private Network, or VPN is a set of technologies which are used to link computers to create a private network. Another network is used to carry the data, which is encrypted."](https://simple.wikipedia.org/wiki/Virtual_private_network)

But that's a little technical for some people. What you need to know, is that a VPN can protect your location and identity from sites and tools you use, by changing your [IP Address](https://simple.wikipedia.org/wiki/IP_address). While it sounds like a godsend, it's crucial to remember that there is no such thing as complete anonymity on the internet. Because your VPN provider can still see your data, a VPN is only as secure as it's provider is trustworthy. Despite it's insecurities, VPNs can still be helpful and even necessary in specific situations. Namely while torrenting, more on that [here](bpl-guide.md#torrenting). Please review [this information](https://www.privacytools.io/providers/vpn/#info) about VPNs before purchasing one or discounting them altogether. 

If you decide a VPN would be useful for you, please purchase one. Free VPN providers are significantly more likely to dishonor no-log policies and sell your data. Refer to That One Privacy Guy's [VPN comparison chart](https://thatoneprivacysite.net/#simle-vpn-comparison) when choosing one. Once you've purchased a VPN and installed the application for it, use is usually as simple as clicking 1 button to enable it. Personally, I recommend [ProtonVPN](https://protonvpn.com).

## The Onion Project (TOR)

Not to be confused with [torrenting](bpl-guide.md#torrenting), Tor is a computer network that serves to keep it's users anonymous. When you browse the internet with Tor, your internet traffic is sent through 3 of Tor's computers, called Tor relays, before it reaches it's intended destination. This design ensures that no 2 of the relays know about the other, so that traffic cannot be traced back to you. Rest assured, this is a secure by design system. Issues typically only occur when it's users are careless. When used properly, Tor is an extremely rare case where near complete anonymity can be achieved. If you want to use Tor, you MUST be conscious of how to use it properly. Learn more about that [here](https://www.youtube.com/watch?v=-uDYvy2jQzM).

Tor is primarily used with the [Tor browser](https://www.torproject.org/). Please understand that when using the Tor browser, only your browser data is being encrypted. Other data sent through other apps on your device will not be encrypted with Tor. If Tor is blocked in your area, or if you don't want your internet provider to know that you're using Tor, read up on [Tor Bridges](https://tb-manual.torproject.org/bridges/) before you install Tor. 

To learn more about Tor and how it works: [Myth-busting Tor](https://write.privacytools.io/my-thoughts-on-security/slicing-onions-part-1-myth-busting-tor).
