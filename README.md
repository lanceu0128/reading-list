# Reading List

A collection of computer science and software engineering articles that I found interesting! 

Organized by technical domain. Favorites marked with ✨.

## Networking

- [Google Cloud - Global Network Principles and Innovations](https://cloud.google.com/blog/products/networking/google-global-network-principles-and-innovations)
- [Cloudflare - What is latency?](https://www.cloudflare.com/learning/performance/glossary/what-is-latency/)
  
### Caching / CDNs

- [Cloudflare - What is caching?](https://www.cloudflare.com/learning/cdn/what-is-caching/)
- [Cloudflare - “Look, Ma, no probes!” — Characterizing CDNs’ latencies with passive measurement](https://blog.cloudflare.com/cdn-latency-passive-measurement/)

### Application Layer

- [Cloudflare - What is HTTP?](https://www.cloudflare.com/learning/ddos/glossary/hypertext-transfer-protocol-http/)
- [Cloudflare - What is DNS?](https://www.cloudflare.com/learning/dns/what-is-dns/)

### Network Layer

- [Cloudflare - What is the network layer?](https://www.cloudflare.com/learning/network-layer/what-is-the-network-layer/)
- [Cloudflare - What is IGMP?](https://www.cloudflare.com/learning/network-layer/what-is-igmp/)
- [Stonecharioteer on Tech - Understanding Traceroute](https://tech.stonecharioteer.com/posts/2026/traceroute/)
- [gekk.info - Traceroute isn't real](https://gekk.info/articles/traceroute.htm)

### Load Balancing

- [The Morning Paper - Maglev: A Fast and Reliable Software Network Load Balancer](https://blog.acolyer.org/2016/03/21/maglev-a-fast-and-reliable-software-network-load-balancer/)
- [Cloudflare - High Availability Load Balancers with Maglev](https://blog.cloudflare.com/high-availability-load-balancers-with-maglev/)
- [Cloudflare - Load Balancing without Load Balancers](https://blog.cloudflare.com/cloudflares-architecture-eliminating-single-p/) ✨

## Distributed Systems

- [The Morning Paper - The Tail at Scale](https://blog.acolyer.org/2015/01/15/the-tail-at-scale/)
- [APNIC - 21 years and counting of ‘eight fallacies of distributed computing’](https://blog.apnic.net/2025/12/08/21-years-and-counting-of-eight-fallacies-of-distributed-computing/)
- [Marc's Blog - What is Scalability Anyway?](https://brooker.co.za/blog/2024/01/18/scalability.html)

### Cluster Management

- [Anant Jain - Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center](https://www.anantjain.xyz/posts/mesos)
- [The Morning Paper - Large-scale cluster management with Borg](https://blog.acolyer.org/2015/05/07/large-scale-cluster-management-at-google-with-borg/) ✨
- [Anant Jain - Omega: flexible, scalable schedulers for large compute clusters](https://www.anantjain.xyz/posts/omega)
- [Kubernetes - Borg: The Predecessor to Kubernetes](https://kubernetes.io/blog/2015/04/borg-predecessor-to-kubernetes/)
- [Anant Jain - Borg, Omega, and Kubernetes](https://www.anantjain.xyz/posts/borg-omega-kubernetes)

### Serverless Computing

- [Cloudflare - Cloud Computing without Containers](https://blog.cloudflare.com/cloud-computing-without-containers/) ✨
- [Cloudflare - Eliminating Cold Starts with Cloudflare Workers](https://blog.cloudflare.com/eliminating-cold-starts-with-cloudflare-workers/)

### Storage Systems

- [PlanetScale - IO devices and latency](https://planetscale.com/blog/io-devices-and-latency) ✨
- [Backblaze - The Life and Times of a Backblaze Hard Drive](https://www.backblaze.com/blog/life-and-times-of-a-backblaze-hard-drive/) ✨
- [The Morning Paper - The Google File System](https://blog.acolyer.org/2014/10/30/the-google-file-system/)
- [All Things Distributed - Building and operating a pretty big storage system called S3](https://www.allthingsdistributed.com/2023/07/building-and-operating-a-pretty-big-storage-system.html) ✨
- [Marc's Blog - Erasure Coding versus Tail Latency](https://brooker.co.za/blog/2023/01/06/erasure.html)
- [Cloudflare - Workers Durable Objects Beta: A New Approach to Stateful Serverless](https://blog.cloudflare.com/introducing-workers-durable-objects/)

### System Design

- [Nick Tikhonov - How I built a sub-500ms latency voice agent from scratch](https://www.ntik.me/posts/voice-agent)
- [AWS - Building a high-performance exchange market data broadcasting platform on AWS](https://aws.amazon.com/blogs/networking-and-content-delivery/building-a-high-performance-exchange-market-data-broadcasting-platform-on-aws/)
- [Google Cloud - Building Scalable Real Time Applications with Firestore](https://cloud.google.com/blog/products/databases/building-scalable-real-time-applications-with-firestore)

## Web Applications

- [Josh W. Comeau - Understanding Layout Algorithms](https://www.joshwcomeau.com/css/understanding-layout-algorithms/)

### JavaScript / TypeScript

- [Josh W. Comeau - The “const” Deception](https://www.joshwcomeau.com/javascript/the-const-deception/)
- [Josh W. Comeau - Promises From The Ground Up](https://www.joshwcomeau.com/javascript/promises/)
- [matklad - TypeScript is Surprisingly OK for Compilers](https://matklad.github.io/2023/08/17/typescript-is-surprisingly-ok-for-compilers.html)

### JavaScript Tooling

- [Sanyam Jain -  CORS: What is it protecting?](https://sanyamserver.online/posts/cors/)
- [Platformatic - We cut Node.js' Memory in half](https://blog.platformatic.dev/we-cut-nodejs-memory-in-half) ✨
- [Bun - Rewriting Bun in Rust](https://bun.com/blog/bun-in-rust)

### Backend API Design

- [Stripe - Designing robust and predictable APIs with idempotency](https://stripe.com/blog/idempotency)
- [Stripe - Scaling your API with rate limiters](https://stripe.com/blog/rate-limiters)
- [Stripe - APIs as infrastructure: future-proofing Stripe with versioning](https://stripe.com/blog/api-versioning)

### Frontend Development

- [React - Keeping Components Pure](https://react.dev/learn/keeping-components-pure)
- [Josh W. Comeau - Why React Re-Renders](https://www.joshwcomeau.com/react/why-react-re-renders/)
- [Josh W. Comeau - Understanding useMemo and useCallback](https://www.joshwcomeau.com/react/usememo-and-usecallback/)
- [Josh W. Comeau - Making Sense of Server Components](https://www.joshwcomeau.com/react/server-components/) ✨
- [TkDodo's Blog - Concurrent Optimistic Updates in React Query](https://tkdodo.eu/blog/concurrent-optimistic-updates-in-react-query)

## Other

Outcasts that don't quite fit in (yet).

### C / C++

- [Calle Luks - The Four Stages of Compiling a C Program](https://www.calleluks.com/the-four-stages-of-compiling-a-c-program/)
- [Shahar Mike's Web Spot - C++ vtables - Part 1 - Basics](https://shaharmike.com/cpp/vtable-part1/)
- [Shahar Mike's Web Spot - C++ vtables - Part 4 - Compiler-Generated Code](https://shaharmike.com/cpp/vtable-part4/)

### Databases
- [PlanetScale - Processes and Threads](https://planetscale.com/blog/processes-and-threads)
- [Clickhouse - OLTP vs. OLAP](https://clickhouse.com/resources/engineering/oltp-vs-olap)
- [PlanetScale - B-Trees and Database Indexes](https://planetscale.com/blog/btrees-and-database-indexes)
- [PlanetScale - Database Sharding](https://planetscale.com/blog/database-sharding)
- [OpenAI - Scaling PostgreSQL to power 800 million ChatGPT users](https://openai.com/index/scaling-postgresql/)
- [PlanetScale - Database Transactions](https://planetscale.com/blog/database-transactions)
- [PlanetScale - MySQL replication: Best practices and considerations](https://planetscale.com/blog/mysql-replication-best-practices-and-considerations)
- [PlanetScale - PlanetScale vs Amazon Aurora replication](https://planetscale.com/blog/planetscale-vs-aws-aurora-replication)

### Data Structures & Algorithms
- [Pragmatic Engineer - Data Structures & Algorithms I Used Working at Tech Companies](https://blog.pragmaticengineer.com/data-structures-and-algorithms-i-actually-used-day-to-day/)

### Optimization
- [Larst of Us - The gold standard of optimization: A look under the hood of RollerCoaster Tycoon](https://larstofus.com/2026/03/22/the-gold-standard-of-optimization-a-look-under-the-hood-of-rollercoaster-tycoon/)

### Developer Education
- [Julia Evans - Who pays to educate developers?](https://jvns.ca/blog/2018/09/01/who-pays-to-educate-developers-/)
- [Martin Kleppmann - Writing a book: is it worth it?](https://martin.kleppmann.com/2020/09/29/is-book-writing-worth-it.html)

### Philosophy of Technology

- [the Garden of Forking Paths - Some Questions Concerning Technology](https://gardenforkingpaths.blogspot.com/2011/11/some-questions-concerning-technology.html)
