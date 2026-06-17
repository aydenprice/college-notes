# Chapter 3 - Cloud Computing

> **Note:** Figures are screenshots from lecture slides.

## Table of Contents

* [Overview](#overview)
* [Q3-1: What Do Business Professionals Need to Know About Networks and the Internet?](#q3-1-what-do-business-professionals-need-to-know-about-networks-and-the-internet)

  * Network Types
  * Wireless Network Options
  * Connecting a LAN to the Internet
  * Common Internet Connection Types
* [How Does Data Move Over a Network?](#how-does-data-move-over-a-network)

  * Protocols
  * TCP/IP Protocol Architecture
  * Addressing
  * Languages
  * SOA, Carriers, and IoT
* [How Does a Typical Web Server Move Data on a Network?](#how-does-a-typical-web-server-move-data-on-a-network)

  * Three-Tier Architecture
  * Web Servers and Web Farms
* [Why Is the Cloud the Future for Most Organizations?](#why-is-the-cloud-the-future-for-most-organizations)

  * Characteristics of Cloud Computing
  * Cloud vs. In-House Hosting
  * Why Now?
  * Outsourcing
* [What Are the Typical Cloud Options?](#what-are-the-typical-cloud-options)

  * Software as a Service (SaaS)
  * Platform as a Service (PaaS)
  * Infrastructure as a Service (IaaS)
  * Private Cloud
* [Ethics Guide](#ethics-guide)
* [Chapter Summary](#chapter-summary)

---

## Overview

This chapter examines how computer networks, the Internet, and cloud computing support modern organizations. Understanding how devices communicate, how web applications operate, and how cloud services are delivered is essential for business professionals working in today's technology-driven environment.

The chapter explores:

* Network fundamentals
* Internet communication
* Data movement across networks
* Web server architecture
* Cloud computing
* Cloud service models
* Outsourcing and ethical considerations

---

# Q3-1: What Do Business Professionals Need to Know About Networks and the Internet?

## Network Types

Organizations use several types of networks depending on the size and scope of communication required.

### Personal Area Network (PAN)

A **Personal Area Network (PAN)** connects devices around a single person.

Examples:

* Smartphone and smartwatch
* Smartphone and wireless earbuds
* Laptop and Bluetooth mouse

---

### Local Area Network (LAN)

A **Local Area Network (LAN)** connects devices within a single location.

Examples:

* Home network
* School network
* Office network

LANs are typically fast and managed by a single organization.

---

### Wide Area Network (WAN)

A **Wide Area Network (WAN)** connects devices across multiple locations.

Examples:

* Corporate offices in different cities
* University campuses connected across regions

WANs allow organizations to share information over large geographic areas.

---

### Internet

The **Internet** is a network of networks.

It connects:

* Individuals
* Businesses
* Governments
* Educational institutions

The Internet allows communication and information sharing worldwide.

---

### Figure 3-1: Basic Network Types

*(Insert lecture screenshot)*

---

## Wireless Network Options

Many networks use wireless technologies to connect devices.

### Bluetooth

* Short-range wireless communication
* Commonly used for accessories and personal devices

Examples:

* Wireless headphones
* Smartwatches
* Keyboards

---

### Wi-Fi

* Provides wireless access to a LAN
* Most common method of Internet access in homes and businesses

Benefits:

* Mobility
* Convenience
* High-speed connectivity

---

### Cellular

* Uses mobile carrier networks
* Provides Internet access without Wi-Fi

Examples:

* 4G
* 5G

---

### Figure 3-2: Typical Small Office/Home Office

*(Insert lecture screenshot)*

---

## Connecting a LAN to the Internet

Organizations connect local networks to the Internet through an **Internet Service Provider (ISP).**

### Internet Service Provider (ISP)

An ISP:

* Provides Internet access
* Assigns a unique Internet address
* Serves as a gateway to the Internet
* Maintains and pays for Internet infrastructure

Examples include:

* Comcast
* AT&T
* Spectrum

---

## Common Internet Connection Types

### Digital Subscriber Line (DSL)

DSL:

* Uses traditional telephone lines
* Allows Internet access without disrupting phone calls

Advantages:

* Widely available
* Relatively inexpensive

---

### Cable/Fiber Internet

Cable and fiber connections:

* Deliver high-speed Internet access
* Commonly use fiber-optic technology

Advantages:

* Faster speeds
* Greater reliability
* Better performance for streaming and gaming

---

### WAN Wireless

WAN wireless connections:

* Use cellular networks
* Provide Internet access when wired connections are unavailable

Examples:

* Mobile hotspots
* Cellular routers

---

### Figure 3-5: Summary of LAN Networks

*(Insert lecture screenshot)*

---

# How Does Data Move Over a Network?

Several technologies work together to move information between devices.

## Key Concepts

* Protocols
* Addressing
* Languages
* Service-Oriented Architecture (SOA)
* Carriers
* Internet of Things (IoT)

---

## Protocols

Protocols are rules that govern communication between devices on a network.

Without protocols, devices would not understand how to exchange information.

### IEEE 802.3 (Ethernet)

Ethernet is the standard protocol used for wired LAN communication.

Benefits:

* Reliability
* Speed
* Standardization

---

### Figure 3-6: You, the Internet, and Instagram

*(Insert lecture screenshot)*

---

## TCP/IP Protocol Architecture

The Internet relies on the TCP/IP protocol suite.

### Transmission Control Protocol (TCP)

TCP:

* Breaks information into packets
* Ensures packets arrive correctly
* Reassembles packets at the destination

### Internet Protocol (IP)

IP:

* Identifies devices using IP addresses
* Routes packets across networks

### Hypertext Transfer Protocol (HTTP)

HTTP:

* Transfers web pages and web content
* Allows browsers and web servers to communicate
