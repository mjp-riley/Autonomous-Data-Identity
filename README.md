# Autonomous Modular Identity & Data

## Overview

The aim of this repository is to find causation and potential solutions to the issue of proliferation of personal data (hereafter referred to as simply ‘PD’) amongst an increasing range of 3rd party actors. This repository is a living document that serves essentially as a digital whiteboard for inspiration, ideas and implementations related (but not limited) to digital identity & data ownership. This introductory overview, despite how many times I look back on it and cringe upon realising how poorly it was written, shall remain unchanged.I hope it will serve as an immutable reminder of my initial thoughts and intentions before the process of learning undoubtedly narrows the scope and optimism with which I currently approach this topic. I hold a firm belief that approaching a problem with as little understanding of existing solutions as possible can be invaluable in identifying truly unique alternatives. To sum it up in a pseudo-intellectual one-liner:

> “It is easiest to think outside the box before you’ve thought about the box“

I am at this date 25/04/2024 not approaching this subject completely blind. I have researched various topics related to the subject at hand mostly regarding networking, cryptography as well as protocols falling under the banner of ‘web3’, a term that I hope will fall out of use long before this repository does. A few examples would be IPLD, IPFS, P2P networking, WebRTC, NAT, GRPC, Identity Wallets (in particular the European Union Identity Wallet reference framework). I have some understanding of data governance structures and legislation, good understanding of how data passes across the internet and how it is often used by companies for the benefit of its customers as well as how it is often used for the benefit of the company.

---

## The Problem

### Duplicate Data

Stakeholders/parties in a transaction/system receive more personal data than is required to fulfill their obligations/role within the transaction/system. The lowest amount of personal data required in order for a stakeholder to fulfil their role will from hereon known as the Minimum Required Data (MRD). A first principle for any reimagining of the internet as it relates to data ownership should proceed on the basis that all stakeholders should only provide or request the MRD for the transaction/service in/with which they are engaging.
Customer X visits the website of company A to buy product P using payment processing company B and is shipped to X by Company C, a courier. A

---

## Cornerstones

> ### Local first
>
> - The internet should be primarily a means of communication between individual actors.
> - Web applications should serve as a UI to view/manipulate local data and data of other actors to which one holds read/write permissions. Data held by application developers should ideally be limited to pointers to data stored by individual actors locally.

---
