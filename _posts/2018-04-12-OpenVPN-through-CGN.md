---
layout: post
title: OpenVPN through CGN
---

As I wrote in January 2018 I got a new ISP. The are routing me through a Carrier Grade NAT (CGN). So I
got no public IPv4 address. And I got a 2 € vServer with a stable 100 MBit connection.

So my idea is, to establish a connection from my pfSense to my vServer and from my mobile devices to
my vServer. So I can reach my homenet and got a tunneled connection for spooky access points :)

Recently I configured autossh as systemd user service to map a ssh-port through the CGN on the
vServer.

But back to the OpenVPN topic. In the lack of own documentation (this time I write this post FTW!),
I have to redo some steps that where already made.

I'll stick to the [Video|https://www.youtube.com/watch?v=XcsQdtsCS1U] made by Darren Kitchen and Shaonnon Morse by Hak5. Thanks to you :)

pit
