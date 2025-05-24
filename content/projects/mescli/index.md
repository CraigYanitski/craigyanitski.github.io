---
title: "mescli"
showDate: false
draft: false
tags: ["Golang", "messaging", "end-to-end encryption", "TUI"]
---

This is a project I started to practice implementing encrypted messaging.
To that end, it is a messaging service CLI (hence mes-cli; even though it is technically a TUI) 
that performs end-to-end encryption using the 
[double-ratchet protocol](https://signal.org/docs/specifications/doubleratchet/) developed by Signal.
It is written in Golang and intended to be open-source.
I am still tweaking the server code as well as implementing websockets, plus other QOL fixes.

{{< github repo="CraigYanitski/mescli" >}}
