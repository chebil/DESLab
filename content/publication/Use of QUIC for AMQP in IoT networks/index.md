---
title: Use of QUIC for AMQP in IoT networks
publication_types:
  - article-journal
authors:
  - walid-karamti
doi: https://doi.org/10.1016/j.comnet.2023.109640
abstract: The use of IoT devices is expanding every day in today’s environment. An interoperable protocol like AMQP is essential for supporting multiple IoT use cases and interconnecting IoT devices from different vendors. Many IoT applications are sensitive to delays, which researchers are working to avoid as much as possible. One of the main sources of the delay is the underlying transport layer protocol, such as TCP or UDP. TCP is more reliable than UDP, although it is slower due to the three-way handshake and the use of TLS for security. QUIC, a new transport layer protocol standardized by the Internet Engineering Task Force, combines the finest aspects of UDP and TCP to provide quick and reliable communication. We use the Go programming language to integrate AMQP 1.0 with QUIC to reduce latency and improve battery life. The Docker tool is used to containerize the AMQP 1.0 Broker, Sender, and Receiver implementations, and various scenarios are tested in the NS3 simulator. The findings demonstrated that even though Round Trip Time was 71% higher for QUIC, using QUIC at the transport level improved Startup Latency and Total Communication Time by 62% and 22%, respectively. The proposed scheme (AMQP 1.0 over QUIC) transported 3.5 times more data than the existing scheme (AMQP 1.0 over TCP), but QUIC’s throughput was 7 times higher, which shorten the communication time and 31% less energy was consumed. Furthermore, metrics including Packet Loss, Delay, and Channel Bandwidth were used to compare the two schemes. The results showed that, with the exception of the low channel bandwidth scenario, the proposed scheme consistently outperformed the existing scheme.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-04-01T23:56:47.136Z
tags:
  - QUIC
  - AMQP
  - AMQP 1.0
  - Internet of Things (IoT)
  - Performance analysis
  - Docker
  - TCP
  - Energy analysis
  - Network layer
# url_pdf: 
---
