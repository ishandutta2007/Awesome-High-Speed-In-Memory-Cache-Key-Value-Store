<p align="center">
  <img src="assets/banner.svg" alt="Awesome High Speed In Memory Cache Key Value Store Banner" width="100%" />
</p>

# ⚡ Awesome High-Speed In-Memory Cache & Key-Value Store

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-High-Speed-In-Memory-Cache-Key-Value-Store/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-High-Speed-In-Memory-Cache-Key-Value-Store?style=social" alt="GitHub_Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-High-Speed-In-Memory-Cache-Key-Value-Store/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-High-Speed-In-Memory-Cache-Key-Value-Store?style=social" alt="GitHub Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-High-Speed-In-Memory-Cache-Key-Value-Store/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-High-Speed-In-Memory-Cache-Key-Value-Store" alt="Open Issues" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-High-Speed-In-Memory-Cache-Key-Value-Store/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-High-Speed-In-Memory-Cache-Key-Value-Store" alt="License" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

> 🚀 **A curated, battle-tested directory of high-speed in-memory caches, distributed key-value stores, ultra-low-latency data grids, embedded storage engines, and managed cloud caching platforms.**

Whether you are scaling high-throughput APIs, slashing database tail latencies, designing real-time financial trading systems, or building distributed microservices, this repository covers the best-of-breed open-source tools and fully-managed SaaS platforms.

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS & Hosted Platforms](#️-saas--hosted-platforms)
- [🔓 Open-Source Equivalents & Tools](#-open-source-equivalents--tools)
  - [⚡ Redis-Compatible & Multi-Threaded In-Memory Stores](#-redis-compatible--multi-threaded-in-memory-stores)
  - [🌐 Distributed In-Memory Data Grids & Low-Latency Stores](#-distributed-in-memory-data-grids--low-latency-stores)
  - [📨 High-Throughput Memcached-Protocol & Sharded Caches](#-high-throughput-memcached-protocol--sharded-caches)
  - [📦 Embedded & In-Process High-Speed Key-Value Libraries](#-embedded--in-process-high-speed-key-value-libraries)
  - [💾 Persistent & Hybrid Flash/RAM Key-Value Engines](#-persistent--hybrid-flashram-key-value-engines)
- [📈 Star History](#-star-history)
- [🤝 Contributing](#-contributing)
- [💖 Support & Sponsorship](#-support--sponsorship)

---

## 📊 Sector Overview & Market Dynamics

The global in-memory database and caching market is estimated at **$7.5 billion to $8.2 billion in 2024**, projected to surpass **$21 billion by 2030** at an annual CAGR exceeding 19%. The sector exhibits **moderate fragmentation with strong hyperscaler concentration**: hyperscalers (AWS, Microsoft Azure, Google Cloud) command roughly 55–65% of managed deployments, while specialized independent vendors (Redis, Aerospike, Hazelcast, Couchbase) and high-performance open-source entrants (Valkey, Dragonfly, Garnet) capture the remainder driven by ultra-low tail latency, open-governance requirements, and high-density hardware efficiency.

---

## ☁️ SaaS & Hosted Platforms

Below is a comparison of commercial, fully managed, and serverless in-memory caching solutions, sorted in descending order by **company market capitalization / enterprise valuation**.

| Provider / Product 🏢 | Valuation / Market Size 💰 | Pricing Model & Starting Tier 💳 | Free Tier / Free Trial Limits 🎁 | Description 📝 |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Azure Cache for Redis](https://azure.microsoft.com/en-us/products/cache/)** | ~$3.1 Trillion *(Market Cap)* | From $0.022/hour (~$16.06/month) for Basic C0 (250 MB cache instance) | $200 free credit across first 30 days + 12 months access to selected free services | Fully managed, secure Redis cache service featuring enterprise active-active geo-replication, sub-millisecond latency, and Redis Enterprise modules. |
| **[Google Cloud Memorystore](https://cloud.google.com/memorystore)** | ~$2.1 Trillion *(Alphabet Market Cap)* | From $0.0247/GB-hour (~$17.78/month) for Basic M1 (1 GB Redis/Valkey tier) | $300 free trial credit valid for 90 days across Google Cloud services | Highly available, fully managed in-memory data store service for Redis, Valkey, and Memcached with automatic patching and 99.9% SLA. |
| **[AWS ElastiCache](https://aws.amazon.com/elasticache/)** | ~$2.0 Trillion *(Amazon Market Cap)* | From $0.016/hour (~$11.52/month) for `cache.t4g.micro` node (0.5 GiB RAM) | 750 hours/month of `cache.t2.micro` or `cache.t3.micro` free for 12 months under AWS Free Tier | Scalable in-memory data store supporting Valkey, Redis OSS, and Memcached with microsecond latency and serverless autoscaling modes. |
| **[Redis Cloud](https://redis.io/cloud/)** | ~$4.0 Billion *(Private Valuation)* | From $5.00/month for Fixed 100 MB Plan (or $0.881/GB-hour on Flexible pay-as-you-go) | Free Forever: 1 database, 30 MB storage limit, maximum 30 concurrent client connections | Fully managed multi-cloud enterprise Redis service with multi-region 99.999% availability, Vector Search, and JSON capabilities. |
| **[Aerospike Cloud](https://aerospike.com/products/cloud/)** | ~$1.2 Billion *(Private Valuation)* | From $0.21/hour (~$150/month) for starter managed cluster deployment | 14-day free trial with full feature access and up to 50 GB data allocation | Managed real-time NoSQL database using Hybrid Memory Architecture (HMA) combining in-memory speed with NVMe flash capacity. |
| **[Couchbase Capella](https://www.couchbase.com/products/capella/)** | ~$800 Million *(Market Cap)* | From $0.258/hour (~$185/month) per node for developer / evaluation instances | 30-day free trial including 1 hosted cluster, pre-loaded sample datasets, no credit card required | Fully managed, memory-first cloud NoSQL document and key-value database providing sub-millisecond data access and built-in caching. |
| **[Hazelcast Viridian Cloud](https://hazelcast.com/products/viridian/)** | ~$350 Million *(Private Valuation)* | From $0.08/GB-hour on pay-as-you-go serverless cluster configurations | Free Forever: 1 serverless cluster with up to 1 GB memory capacity and 250k operations/month | Serverless distributed in-memory compute and storage platform engineered for streaming event processing and real-time operational caching. |
| **[Dragonfly Cloud](https://www.dragonflydb.io/cloud)** | ~$150 Million *(Venture Backed)* | From $0.038/hour (~$28/month) for 1 GB dedicated instance | 14-day free trial on dedicated cloud clusters with up to 4 GB instance capacity | Fully managed cloud service for Dragonfly, running ultra-high-throughput multi-threaded Redis/Memcached compatible engines. |
| **[Momento Cache](https://www.gomomento.com/)** | ~$60 Million *(Venture Backed)* | True serverless pay-per-use at $0.0000005 per request ($0.50 per 1M requests) + $0.15/GB-month storage | Free Forever: 5 GB-months of data cache storage and up to 50 million read/write operations each month | Instant, truly serverless distributed cache with zero cluster configuration, automatic elasticity, and global edge points of presence. |

---

## 🔓 Open-Source Equivalents & Tools

High-performance open-source caching servers, multi-threaded key-value stores, distributed data grids, and embedded memory engines. Sorted within each category by **GitHub Stargazers** (descending).

### ⚡ Redis-Compatible & Multi-Threaded In-Memory Stores

| Project 🛠️ | GitHub_Stars ⭐ | Description 📝 |
| :--- | :--- | :--- |
| **[Redis](https://github.com/redis/redis)** | [![Stars](https://img.shields.io/github/stars/redis/redis?style=social&color=white)](https://github.com/redis/redis/stargazers) | The quintessential in-memory data structure store used as a cache, message broker, and streaming engine. |
| **[Dragonfly](https://github.com/dragonflydb/dragonfly)** | [![Stars](https://img.shields.io/github/stars/dragonflydb/dragonfly?style=social&color=white)](https://github.com/dragonflydb/dragonfly/stargazers) | Modern multi-threaded, shared-nothing in-memory datastore fully compatible with Redis & Memcached APIs at up to 25x throughput. |
| **[Valkey](https://github.com/valkey-io/valkey)** | [![Stars](https://img.shields.io/github/stars/valkey-io/valkey?style=social&color=white)](https://github.com/valkey-io/valkey/stargazers) | High-performance open-source fork of Redis curated under the Linux Foundation supporting multi-threaded I/O, clustering, and rich data types. |
| **[KeyDB](https://github.com/Snapchat/KeyDB)** | [![Stars](https://img.shields.io/github/stars/Snapchat/KeyDB?style=social&color=white)](https://github.com/Snapchat/KeyDB/stargazers) | High-performance, multithreaded drop-in replacement for Redis maintained by Snap with active-active replication and FLASH storage support. |
| **[Garnet](https://github.com/microsoft/garnet)** | [![Stars](https://img.shields.io/github/stars/microsoft/garnet?style=social&color=white)](https://github.com/microsoft/garnet/stargazers) | Remote cache-store written by Microsoft Research in C#/.NET offering extreme throughput, microsecond tail latencies, and RESP compatibility. |
| **[Apache Kvrocks](https://github.com/apache/kvrocks)** | [![Stars](https://img.shields.io/github/stars/apache/kvrocks?style=social&color=white)](https://github.com/apache/kvrocks/stargazers) | Distributed key-value NoSQL database compatible with the Redis protocol that leverages RocksDB on flash storage to dramatically reduce memory costs. |
| **[Redict](https://redict.io)** | [![Codeberg](https://img.shields.io/badge/Codeberg-FOSS-white?style=social)](https://codeberg.org/redict/redict) | Independent, copyleft-licensed (LGPL-3.0) community-driven in-memory database maintaining reliable Redis protocol compatibility. |

---

### 🌐 Distributed In-Memory Data Grids & Low-Latency Stores

| Project 🛠️ | GitHub_Stars ⭐ | Description 📝 |
| :--- | :--- | :--- |
| **[etcd](https://github.com/etcd-io/etcd)** | [![Stars](https://img.shields.io/github/stars/etcd-io/etcd?style=social&color=white)](https://github.com/etcd-io/etcd/stargazers) | Strongly consistent, distributed in-memory key-value store providing reliable shared configuration and service discovery across clusters. |
| **[Hazelcast](https://github.com/hazelcast/hazelcast)** | [![Stars](https://img.shields.io/github/stars/hazelcast/hazelcast?style=social&color=white)](https://github.com/hazelcast/hazelcast/stargazers) | Open-source distributed in-memory compute and storage platform providing partitioned key-value maps, queues, and streaming pipelines. |
| **[Apache Ignite](https://github.com/apache/ignite)** | [![Stars](https://img.shields.io/github/stars/apache/ignite?style=social&color=white)](https://github.com/apache/ignite/stargazers) | Distributed, memory-centric database, caching, and computational grid supporting SQL, key-value APIs, and ACID transactions. |
| **[Tarantool](https://github.com/tarantool/tarantool)** | [![Stars](https://img.shields.io/github/stars/tarantool/tarantool?style=social&color=white)](https://github.com/tarantool/tarantool/stargazers) | Ultra-fast in-memory computing platform combining a Lua application server with transactional key-value/document persistence. |
| **[Apache Geode](https://github.com/apache/geode)** | [![Stars](https://img.shields.io/github/stars/apache/geode?style=social&color=white)](https://github.com/apache/geode/stargazers) | Low-latency, distributed in-memory data management system providing high-concurrency transactional data access across memory pools. |
| **[Infinispan](https://github.com/infinispan/infinispan)** | [![Stars](https://img.shields.io/github/stars/infinispan/infinispan?style=social&color=white)](https://github.com/infinispan/infinispan/stargazers) | Open-source distributed in-memory key-value data store and cache in Java with multi-protocol support (REST, Hot Rod, Memcached). |

---

### 📨 High-Throughput Memcached-Protocol & Sharded Caches

| Project 🛠️ | GitHub_Stars ⭐ | Description 📝 |
| :--- | :--- | :--- |
| **[Memcached](https://github.com/memcached/memcached)** | [![Stars](https://img.shields.io/github/stars/memcached/memcached?style=social&color=white)](https://github.com/memcached/memcached/stargazers) | The industry-standard, lightweight, distributed memory object caching system engineered for raw performance and simplicity. |
| **[Groupcache](https://github.com/golang/groupcache)** | [![Stars](https://img.shields.io/github/stars/golang/groupcache?style=social&color=white)](https://github.com/golang/groupcache/stargazers) | Distributed caching and cache-filling Go library engineered as a coordinated peer-to-peer replacement for a pool of Memcached nodes. |
| **[Mcrouter](https://github.com/facebook/mcrouter)** | [![Stars](https://img.shields.io/github/stars/facebook/mcrouter?style=social&color=white)](https://github.com/facebook/mcrouter/stargazers) | Meta's high-performance Memcached protocol router used for connection pooling, sharding, failover routing, and multi-cluster scaling. |
| **[Pelikan](https://github.com/pelikan-io/pelikan)** | [![Stars](https://img.shields.io/github/stars/pelikan-io/pelikan?style=social&color=white)](https://github.com/pelikan-io/pelikan/stargazers) | Unified, modular cache framework in C/Rust developed by Twitter/X for predictable microsecond latency and hardware efficiency. |

---

### 📦 Embedded & In-Process High-Speed Key-Value Libraries

| Project 🛠️ | GitHub_Stars ⭐ | Description 📝 |
| :--- | :--- | :--- |
| **[Caffeine](https://github.com/ben-manes/caffeine)** | [![Stars](https://img.shields.io/github/stars/ben-manes/caffeine?style=social&color=white)](https://github.com/ben-manes/caffeine/stargazers) | High-performance, near-optimal in-memory caching library for Java utilizing Window TinyLFU eviction policies. |
| **[BigCache](https://github.com/allegro/bigcache)** | [![Stars](https://img.shields.io/github/stars/allegro/bigcache?style=social&color=white)](https://github.com/allegro/bigcache/stargazers) | Fast, concurrent, evicting in-memory cache written in Go capable of holding millions of entries without garbage collection pauses. |
| **[Ristretto](https://github.com/dgraph-io/ristretto)** | [![Stars](https://img.shields.io/github/stars/dgraph-io/ristretto?style=social&color=white)](https://github.com/dgraph-io/ristretto/stargazers) | High-performance, memory-bound concurrent cache in Go designed for high hit ratios, TinyLFU admission, and contention-free concurrency. |
| **[FreeCache](https://github.com/coocood/freecache)** | [![Stars](https://img.shields.io/github/stars/coocood/freecache?style=social&color=white)](https://github.com/coocood/freecache/stargazers) | Zero-GC Go cache library capable of storing hundreds of millions of entries in memory with ring-buffer storage and ring hashing. |
| **[DashMap](https://github.com/xacrimon/dashmap)** | [![Stars](https://img.shields.io/github/stars/xacrimon/dashmap?style=social&color=white)](https://github.com/xacrimon/dashmap/stargazers) | Blazingly fast concurrent hash map implementation for Rust providing fine-grained sharded locking outperforming `RwLock<HashMap>`. |
| **[Moka](https://github.com/moka-rs/moka)** | [![Stars](https://img.shields.io/github/stars/moka-rs/moka?style=social&color=white)](https://github.com/moka-rs/moka/stargazers) | Fast, concurrent cache library for Rust inspired by Caffeine, featuring TinyLFU eviction, async runtime support, and TTL expiration. |

---

### 💾 Persistent & Hybrid Flash/RAM Key-Value Engines

| Project 🛠️ | GitHub_Stars ⭐ | Description 📝 |
| :--- | :--- | :--- |
| **[RocksDB](https://github.com/facebook/rocksdb)** | [![Stars](https://img.shields.io/github/stars/facebook/rocksdb?style=social&color=white)](https://github.com/facebook/rocksdb/stargazers) | High-performance embedded key-value storage engine in C++ based on LSM-trees, engineered for fast flash storage and server workloads. |
| **[TiKV](https://github.com/tikv/tikv)** | [![Stars](https://img.shields.io/github/stars/tikv/tikv?style=social&color=white)](https://github.com/tikv/tikv/stargazers) | CNCF-graduated distributed, transactional key-value database built in Rust providing horizontal scalability, Raft consensus, and ACID transactions. |
| **[BadgerDB](https://github.com/dgraph-io/badger)** | [![Stars](https://img.shields.io/github/stars/dgraph-io/badger?style=social&color=white)](https://github.com/dgraph-io/badger/stargazers) | Embeddable, persistent, fast key-value store in Go implementing WiscKey paper architecture with separated keys and values for SSD optimization. |
| **[FASTER](https://github.com/microsoft/FASTER)** | [![Stars](https://img.shields.io/github/stars/microsoft/FASTER?style=social&color=white)](https://github.com/microsoft/FASTER/stargazers) | Concurrent, latch-free key-value store and log in C++/C# from Microsoft Research supporting larger-than-memory datasets with epoch synchronization. |
| **[Pebble](https://github.com/cockroachdb/pebble)** | [![Stars](https://img.shields.io/github/stars/cockroachdb/pebble?style=social&color=white)](https://github.com/cockroachdb/pebble/stargazers) | High-throughput, RocksDB-compatible LSM-tree key-value store in Go developed by Cockroach Labs for distributed database storage backends. |
| **[LMDB](https://github.com/LMDB/lmdb)** | [![Stars](https://img.shields.io/github/stars/LMDB/lmdb?style=social&color=white)](https://github.com/LMDB/lmdb/stargazers) | Lightning Memory-Mapped Database: ultra-fast, zero-copy, embeddable B+tree key-value engine with full ACID compliance and lockless reads. |
| **[Aerospike Community Edition](https://github.com/aerospike/aerospike-server)** | [![Stars](https://img.shields.io/github/stars/aerospike/aerospike-server?style=social&color=white)](https://github.com/aerospike/aerospike-server/stargazers) | High-speed distributed real-time NoSQL key-value database utilizing RAM index pointers alongside direct NVMe block flash storage. |

---

## 📈 Star History

[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-High-Speed-In-Memory-Cache-Key-Value-Store&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-High-Speed-In-Memory-Cache-Key-Value-Store&type=date&legend=top-left)

---

## 🤝 Contributing

Contributions are warmly welcomed! Help keep this curated resource fresh, comprehensive, and accurate.

1. 🍴 Fork the repository.
2. 🌿 Create a feature branch (`git checkout -b feature/awesome-cache-addition`).
3. ✏️ Add your open-source cache or high-speed storage engine with a concise description and correct Stars_Badge.
4. 🚀 Commit your changes (`git commit -m 'Add awesome cache project'`).
5. 📬 Open a Pull Request.

Please check that submissions are actively maintained, relevant to in-memory caching or high-speed key-value storage, and categorized appropriately.

---

## 💖 Support & Sponsorship

If you found this curated list helpful for benchmarking, engineering design, or infrastructure research, please consider supporting the project:

- ⭐ **Star this repository** to help others discover it!
- 🍴 **Fork it** to bookmark and experiment with your own stack.
- 📢 **Share it** with fellow backend, systems, and DevOps engineers.
- ☕ **Support & Buy a Coffee:** You can sponsor ongoing maintenance and open-source research via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007). Your support is greatly appreciated!
