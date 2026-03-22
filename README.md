# Converra
**A privacy-first architecture for reconnecting real-world encounters through consent-gated matching.**

Converra explores a new model for digital social discovery. Instead of browsing profiles or sharing continuous location data, the system enables people to reconnect after real-world encounters using privacy-preserving proximity sensing and reflection-based semantic matching.

Status: Research architecture • Prototype exploration • Contributions welcome

## The Problem

Many meaningful connections happen in passing.

On a train.  
At a café.  
During a conference.  
On a daily commute.

People notice each other but do not act in the moment.  
Once the moment passes, the connection disappears.

Existing tools do not solve this problem well because:

- People hesitate to approach strangers in real time
- Dating apps require continuous profile browsing
- Location-based apps rely on persistent tracking
- "Missed connections" posts are public and socially awkward

Despite living in highly connected cities, real-world encounters are rarely recoverable once they pass.

## The Solution

Converra introduces a privacy-first architecture for **asynchronous social reconnection**.

Instead of real-time discovery, users can reflect on a shared moment later and attempt reconnection through mutual description and consent.

Core components:

1. Passive Co-location Sensing  
2. Local Encrypted Moment Storage  
3. Bidirectional Semantic Matching  
4. Dual Consent Identity Reveal
5. Privacy-Minimized Coordination Layer

## How It Works
BLE Detection → Moment Creation → Reflection → Encoding → Matching → Consent → Identity Exchange

All processing occurs locally until both participants explicitly consent.

## How It's Different

| Traditional Apps | Converra |
|------------------|----------|
| Real-time browsing | Asynchronous reflection |
| Centralized servers | Local-first computation |
| Continuous location tracking | Passive moment detection |
| Unilateral contact | Dual consent required |
| Profile-based matching | Encounter-based matching |

This repository contains research architecture and documentation related to the Converra system, created by Peter Umukoro.

The project is released under the Apache 2.0 License to encourage research collaboration and responsible development.

Elements of the architecture are described in UK Patent Application filed on 22 October 2025.

This repository does not grant a license to the patent beyond what is required by the Apache 2.0 license for contributions.
