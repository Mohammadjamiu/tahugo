---
title: "The Seven Layers of the OSI Model Explained"
postdate: February 13, 2022
image: ""
description: "OSI Model which is termed as Open System Interconnection is a model which is used for standardizing communication across network. It consist of seven layers. The Application, Presentation, Session, Transport, Network, Data link and Physical Layer"
alt: ""
weight: "40"
author: Mohammad Abdul
categorylink: /categories/networking-and-communication
categories: ["Networking and Communication"]
type: posts
Google_Ads: false
wordcount: false
mathjax: false
draft: false
---

{{< ste >}} OSI Model {{</ ste >}} which is termed as Open System Interconnection is a model which is used for standardizing communication across network.

It helps to make troubleshooting of network problem easily as it breaks a complex network into several manageable segments. The OSI model consist of 7 layers.

Even though the OSI model is obsolete, it is still considered to be a reference model to understand how a network works.

The seven layers of an OSI model is as follows;

7). Application Layer

6). Presentation Layer

5). Session Layer

4). Transport Layer

3). Network Layer

2). Data link Layer

1). Physical Layer

The layers can be memorized or remembered with a mnemonics starting from top to bottom as {{< ste >}} (All People Seems To Need Data Processing) {{</ ste >}} or from bottom to top as {{< ste >}} (Please Do Not Throw Sausage Pie Away) {{</ ste >}}.

## Physical Layer

The physical layer is the lowest layer and it is called layer 1. It is responsible for transferring or conveying of streams of bits across a network. The means of transferring the bits across a network may be either electrical or wireless (radio wave).

This layer consists of devices and mediums such as cables, hubs, repeaters, network interface cards etc.

## Data link Layer

The data link layer is the second layer and it is responsible for putting the streams of bit (called packets) into frames.

The data link layer is also responsible for attaching a physical address (MAC address) to a device.

The types of devices that are in layer 2 include
Switches and bridges as they work with MAC address.

## Network Layer

This is the third layer in the OSI model and it is responsible for addressing and routing of packets or data.

It uses an IP address and a MAC address.

The device that can be found in layer 3 is a router.

## Transport layer

The transport layer is the fourth layer in the OSI Model and it is responsible for managing the delivery of packets. In other words, it sends an acknowledgement when data is received (Yey! it is successful) or when data is lost or missing.

This layer uses a TCP and UDP protocols. The TCP is quite similar to the UDP and it is used for error handling and sequencing to ensure that there is no missing packets or data.

## Session Layer

The session layer is the fifth layer in the OSI model which is responsible for starting and stopping of sessions. In other words, it is responsible for setting up and terminating of communication between local and remote application.

## Presentation Layer

The presentation layer is the sixth layer of the OSI model and it is responsible for formatting or translation of data so that the receiving application can process the packet sent.

It is also used for encryption/decryption and compression/decompression of data.

## Application Layer

The application layer which is the top layer and it is the layer that allows users and applications to communicate. In other words, it is responsible for managing the communication between applications.

This layer supports different protocols such as SMTP (which allows sending of email), HTTP, FTP etc.
