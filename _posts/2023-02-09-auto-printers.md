---
layout: post
title: Disable network printer discovery
date: 2023-02-09 12:15:00
categories: [linux, printer]
tags: [linux,ubuntu,mint,printer,network]
---

## Disable Auto-adding of Network Printers

&nbsp;

![printer discovered](/assets/img/printers.png "Printers discovered")

&nbsp;

You just have to disble `cups-browsed` service.

### Run the following commands in terminal:

- To stop the service:
```bash
sudo systemctl stop cups-browsed
```
- To disable the service:
```bash
sudo systemctl disable cups-browsed
```

### The command should look like this:

![Printer terminal](/assets/img/printer-terminal.png "Printer terminal")

### After these setting the printers on the local network won't be discovered.

&nbsp;

![printers disabled](/assets/img/printer-disabled.png "Printers disabled")

