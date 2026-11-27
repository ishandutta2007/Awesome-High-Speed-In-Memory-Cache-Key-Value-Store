# Awesome-High-Speed-In-Memory-Cache-Key-Value-Store

# Awesome-High-Speed-In-Memory-Cache-Key-Value-Store



Top High Speed In Memory Cache Key Value Store (Opensource) 🌟 Star if you like it! 🌟



A curated list of top high-speed in-memory caches, distributed key-value stores, ultra-low-latency data grids, and embedded cache engines—featuring commercial SaaS/Hosted platforms alongside their open-source equivalents.



---



## Table of Contents



- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)

  - [Redis-Compatible & Multi-Threaded In-Memory Stores](#redis-compatible--multi-threaded-in-memory-stores)

  - [Distributed In-Memory Data Grids & Low-Latency Stores](#distributed-in-memory-data-grids--low-latency-stores)

  - [High-Throughput Memcached-Protocol & Sharded Caches](#high-throughput-memcached-protocol--sharded-caches)

  - [Embedded & In-Process High-Speed Key-Value Libraries](#embedded--in-process-high-speed-key-value-libraries)

  - [Persistent & Hybrid Flash/RAM Key-Value Engines](#persistent--hybrid-flashram-key-value-engines)

- [Contributing](#contributing)



---



## SaaS/Hosted Platforms



Commercial, fully managed, and cloud-hosted in-memory caching services, serverless key-value stores, and enterprise data grids.



* **[Redis Cloud](https://redis.io)** - Fully managed enterprise cloud service for Redis offering active-active geo-distribution, sub-millisecond latency, and multi-model modules.

* **[Memcached Cloud](https://redis.io)** - Enterprise managed cloud service providing scalable, zero-ops Memcached clusters with high availability.

* **[Dragonfly Cloud](https://dragonflydb.io)** - Managed cloud service for DragonflyDB delivering multi-threaded, ultra-high-throughput Redis-compatible caching.

* **[Hazelcast Viridian Cloud](https://hazelcast.com)** - Fully managed serverless cloud platform for real-time stream processing and distributed in-memory data grids.

* **[AWS ElastiCache](https://amazon.com)** - Managed in-memory caching service supporting Valkey, Redis OSS, and Memcached with serverless autoscaling.

* **[Azure Cache for Redis](https://microsoft.com)** - Microsoft's fully managed, in-memory data store based on Redis for high-throughput cloud applications.

* **[Google Cloud Memorystore](https://google.com)** - Fully managed, highly available in-memory service for Redis, Valkey, and Memcached on Google Cloud.

* **[Couchbase Capella](https://couchbase.com)** - Managed cloud NoSQL database featuring a built-in memory-first architecture for sub-millisecond key-value operations.

* **[Aerospike Cloud](https://aerospike.com)** - Fully managed real-time database service engineered for predictable sub-millisecond performance at petabyte scale using Hybrid Memory Architecture.

* **[Momento Cache](https://gomomento.com)** - Truly serverless, pay-per-request cloud cache service requiring zero cluster provisioning or capacity planning.



---



## Open-Source Equivalents & Tools



Free and open-source software (FOSS) in-memory caches, multi-threaded key-value servers, distributed data grids, and embedded caching libraries.



### Redis-Compatible & Multi-Threaded In-Memory Stores



* **[Valkey](https://github.com)** - High-performance, Linux Foundation-backed open-source fork of Redis supporting multi-threaded I/O, clustering, and rich data structures.

* **[Dragonfly](https://github.com)** - Modern, multi-threaded, shared-nothing in-memory datastore fully compatible with Redis and Memcached APIs at 25x throughput.

* **[KeyDB](https://github.com)** - High-performance, multi-threaded drop-in replacement for Redis maintained by Snap with active replication and FLASH storage support.

* **[Garnet (Microsoft Research)](https://github.com)** - Remote cache-store written in C#/.NET offering extreme throughput, ultra-low tail latency, and full Redis RESP protocol compatibility.

* **[Kvrocks (Apache)](https://github.com)** - Distributed key-value NoSQL database compatible with the Redis protocol that uses RocksDB to scale beyond RAM limits.

* **[Redict](https://redict.io)** - Copyleft, community-driven distributed key-value store maintaining compatibility with the Redis ecosystem.



### Distributed In-Memory Data Grids & Low-Latency Stores



* **[Hazelcast Platform](https://github.com)** - Open-source distributed in-memory compute and storage platform providing partitioned key-value maps, queues, and stream processing.

* **[Apache Ignite](https://github.com)** - Distributed, memory-centric database and caching platform supporting SQL, key-value APIs, and ACID transactions at in-memory speed.

* **[Apache Geode](https://github.com)** - Mature, low-latency, distributed in-memory data management system designed for high-concurrency transactional applications.

* **[Infinispan](https://github.com)** - Open-source, distributed in-memory key-value data store and cache written in Java with multi-protocol support (REST, Memcached, Hot Rod).

* **[Tarantool](https://github.com)** - High-performance in-memory computing platform combining an application server with a transactional key-value/document database.



### High-Throughput Memcached-Protocol & Sharded Caches



* **[Memcached](https://github.com)** - Industry-standard, free, high-performance, distributed memory object caching system engineered for simplicity and speed.

* **[Pelikan (Twitter/X)](https://github.com)** - Unified, modular cache framework written in C/Rust designed for extreme performance, predictable latency, and hardware efficiency.

* **[Mcrouter (Meta)](https://github.com)** - High-performance Memcached protocol router used at massive scale for connection pooling, sharding, and multi-cluster replication.

* **[Groupcache](https://github.com)** - Distributed caching and cache-filling library in Go designed as a zero-configuration replacement for a pool of Memcached nodes.



### Embedded & In-Process High-Speed Key-Value Libraries



* **[Magpie (yetone)](https://github.com)** - Lightweight, high-speed in-memory cache and key-value store engineered for low-latency data access.

* **[Moka](https://github.com)** - Fast, concurrent, Caffeine-inspired in-memory cache library for Rust supporting TinyLFU eviction and time-to-live expiration.

* **[Caffeine](https://github.com)** - High-performance, near-optimal in-memory caching library for Java utilizing Window TinyLFU eviction policies.

* **[Ristretto](https://github.com)** - High-performance, memory-bound concurrent cache in Go built for high hit ratios and contention-free throughput.

* **[BigCache](https://github.com)** - Fast, concurrent, evicting in-memory cache written in Go capable of storing millions of entries without GC overhead.

* **[DashMap](https://github.com)** - Blazingly fast concurrent associative array/key-value map for Rust outperforming standard `RwLock<HashMap>`.



### Persistent & Hybrid Flash/RAM Key-Value Engines



* **[Aerospike Community Edition](https://github.com)** - High-speed, distributed key-value database utilizing a hybrid memory architecture (RAM indexes + direct NVMe SSD storage).

* **[FASTER (Microsoft)](https://github.com)** - Concurrent key-value store and log in C++/C# supporting larger-than-memory datasets with latch-free cache-line performance.

* **[Pebble (Cockroach Labs)](https://github.com)** - RocksDB-inspired key-value storage engine written in Go optimized for high-throughput read/write workloads.

* **[RocksDB (Meta)](https://github.com)** - Embeddable, persistent key-value store written in C++ engineered for fast storage media (NVMe/Flash) and high-speed server workloads.

* **[LMDB (Lightning Memory-Mapped Database)](https://github.com)** - Ultra-fast, zero-copy, B+tree memory-mapped key-value store with full ACID semantics and minimal overhead.

* **[TiKV](https://github.com)** - Open-source, distributed, and transactional key-value database built in Rust offering horizontal scalability and low latency.



---



## Contributing



Contributions are welcome! Feel free to open a Pull Request to add more open-source in-memory caches, distributed key-value stores, or high-speed storage engines.



1. Fork the repository.

2. Add your project under the appropriate category with a concise description.

3. Submit a Pull Request.
