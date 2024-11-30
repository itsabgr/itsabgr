# ENG. A. BAGHERI

[📧 abgr@duck.com](mailto:abgr@duck.com)

[🔗 Github/itsabgr](https://github.com/itsabgr)

[💬 Telegram/itsabgr](https://t.me/itsabgr)

I started programming at 16 by learning Lua in a self-study manner.
I am known as an eager researcher and enjoy studying, designing, and building systems, especially network-based ones.
I have knowledge of low-level network programming on Linux, and for this, Ubuntu is my OS.
I built 15+ projects, some within a team but mostly on my own as a software engineer and a backend developer.

## SKILLS

* DevOps and Server Administration (Debian, Ubuntu)
* Containerization (Docker, Snap) and Orchestration (Swarm)
* C, Go, NodeJS+TypeScript, and Solidity
* Microservices architecture
* Parallel and concurrent processing
* TCP/IP networks
* Blockchain L1 and L2
* Load balancers and Proxies (Nginx)
* RDBMSs and SQL
* Message Queues (AMQP, Rabbit MQ)
* Stateful Stream Processing
* NoSQL (MongoDB, Redis)
* P2P, Decentralized, and Distributed systems
* CI/CD
* Git and Github flow
* Smart Contract and Oracle development

## NOTABLE PROJECTS

### Network Policy Verifier

Developed and implemented a comprehensive and scalable internet (WWW) monitoring system leveraging technologies such as Golang, RabbitMQ, Selenium (WebDriver), Elasticsearch, and PostgreSQL. The system integrated a web crawler, developed by another team, to extract domains and feed them into a stateful stream processing pipeline. Designed the pipeline to handle real-time data propagation and transformation using RabbitMQ and Golang. Selenium was employed for data extraction and processing, while the results were aggregated and indexed in Elasticsearch for analytics and stored in PostgreSQL for long-term storage and optimized querying. One of the main challenges of the project was managing Selenium’s heavy and slow operations while handling a high input load in the stream processing system to ensure no data was lost. Additionally, it required precise and accurate data processing with stateful operations, necessitating careful management of the system state for reliability and performance.

### Decentralized Bandwidth Sharing Network

Developed a truly decentralized and permissionless bandwidth-sharing network. This innovative solution leverages
the power of Go, C, and a custom HTTP/2-based protocol for efficient data transfer and a Decentralized App (DApp)
for a trustless and secure network.

### Cryptocurrency Payment Gateway

Designed and developed a modular and efficient Crypto Payment Gateway (CPG) that supports a wide range of
cryptocurrencies. The CPG utilizes a Go-based Oracle for robust functionality and performance.
Supports major cryptocurrencies like Bitcoin (BTC) and Ethereum (ETH).
Extensible to integrate with Ethereum-compatible coins and ERC20 tokens.
Modular design for scalability and maintainability.

### Ethereum-compatible blockchain

A sequential PoS Ethereum-compatible chain
on top of the Tendermint / Cosmos SDK with some optimizations.
I understood how Ethereum and EVM work in depth to make it Ethereum-compatible and expose the same API as Ethereum.
To improve the throughput, I added some optimizations in the processing and consensus parts.
I also used a method to solve the blockchain big data size problem.

### Watch-to-Earn system

This system incentivizes users to watch videos on a VOD platform by rewarding them with tokens while they engage
with content using Solidity and Go.
The dapp side was an ERC20 to store balances and mint tokens, and the backend side (Oracle) was responsible for
watch time verification and distribution.

### Decentralized Messenger

A federated and decentralized end-to-end encrypted messenger by Go in a very simple but fast and secure architecture inspired by email was developed.
A DHT was developed for its peer discovery to store users' information in it, like what IPNS does, and also a special blockchain was made in order to register and assign unique names to users.
Moreover, a DNS proxy and resolver were crafted to integrate into current networks.
Finally, a cross-platform client library was made in Dart.

### Live Streaming

A scalable live-streaming service in Go with CDN capabilities was developed for an online classroom system.

### Course Management System

An educational course management system for a university was developed using NodeJS.
MongoDB was used for the main database, and the challenge was that some complicated time overlaps and conflicts had to be managed.

### Asset Management App

An asset management system was made using NodeJS for a province that needed to manage and record the repair history of its pylons and wires between them.
There were a lot of 4K images that were stored in GridFS, and due to complex relationships and queries, MySQL was used as the main Database.

### Ride-sharing App

An online-taxi project was done using NodeJS+TypeScript.
MongoDB was the main database mainly because of its geo-special and schema-less capabilities and GridFS.
I also used MySQL for financial transactions.
There was no use of WebSockets for notifications; instead, I used a queue and HTTP polling method for those cases.
Its architecture was also used for a massage reservation app and e-commerce, but GRPC was replaced by REST.

## LANGUAGES

* Farsi/Persian
* English
