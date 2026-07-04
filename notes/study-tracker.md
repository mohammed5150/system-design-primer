# System Design Primer — Study Tracker

_Personal progress tracker for [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer). Started 2026-07-04._

Tick boxes as you go. Link each topic to your own note in this folder (see `_topic-template.md`).

**Legend:** `[ ]` not started · `[~]` in progress · `[x]` done · 🟢 short-timeline priority · 🟠 medium · 🔴 deep-dive

---

## 0. The framework (learn this cold — used in every interview)
- [ ] **4-step approach:** ① use cases, constraints & assumptions → ② high-level design → ③ core components → ④ scale it
- [ ] **Back-of-the-envelope calculations** (know how to estimate QPS, storage, bandwidth)
- [ ] Memorize **latency numbers every programmer should know**
- [ ] Memorize **powers of two** table
- [ ] Availability in **"nines"** (99.9% vs 99.99% downtime/year)

## 1. Principles 🟢
- [ ] Performance vs scalability
- [ ] Latency vs throughput
- [ ] Availability vs consistency — **CAP theorem** (CP vs AP)
- [ ] Consistency patterns: weak · eventual · strong
- [ ] Availability patterns: fail-over (active-passive / active-active) · replication

## 2. Building blocks 🟢
- [ ] DNS
- [ ] CDN — push vs pull
- [ ] Load balancer — Layer 4 vs Layer 7 · horizontal scaling
- [ ] Reverse proxy (and how it differs from a load balancer)
- [ ] Application layer — microservices · service discovery

## 3. Data 🟠
- [ ] **RDBMS** — replication (master-slave, master-master) · federation · sharding · denormalization · SQL tuning
- [ ] **NoSQL** — key-value · document · wide-column · graph
- [ ] **SQL vs NoSQL** — when to pick which

## 4. Caching 🟠
- [ ] Cache levels: client · CDN · web server · database · application
- [ ] Query-level vs object-level caching
- [ ] Update strategies: cache-aside · write-through · write-behind · refresh-ahead
- [ ] Cache disadvantages / invalidation pitfalls

## 5. Asynchronism 🟠
- [ ] Message queues
- [ ] Task queues
- [ ] Back pressure

## 6. Communication 🟠
- [ ] HTTP
- [ ] TCP vs UDP
- [ ] RPC vs REST

## 7. Security 🔴
- [ ] Basics (encrypt in transit/rest, sanitize input, least privilege, rate limiting)

---

## 8. System design questions — with solutions (highest ROI for interviews)
- [ ] Design Pastebin.com / Bit.ly
- [ ] Design the Twitter timeline & search
- [ ] Design a web crawler
- [ ] Design Mint.com
- [ ] Design the data structures for a social network
- [ ] Design a key-value store for a search engine
- [ ] Design Amazon's sales ranking by category
- [ ] Design a system that scales to millions of users on AWS

## 9. Object-oriented design questions — with solutions
- [ ] Design a hash map
- [ ] Design an LRU cache
- [ ] Design a call center
- [ ] Design a deck of cards
- [ ] Design a parking lot
- [ ] Design an online chat
- [ ] Design a circular array

---

## Suggested plan by timeline
| Timeline | Focus |
|---|---|
| **Short** | §0 framework + §1 principles + §2 building blocks; skim 2–3 solutions (§8) |
| **Medium** | Above + §3 data + §4 caching + §5 async + §6 comms; work through most of §8 + a few §9 |
| **Long** | Everything, incl. §7 security + real-world/company architectures (README appendix); all §8 and §9 |

## Log
| Date | Topic | Notes / takeaways |
|---|---|---|
| 2026-07-04 | (setup) | Forked repo, seeded notes folder + tracker |
