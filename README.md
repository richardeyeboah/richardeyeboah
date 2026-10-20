<p align="center">
  <img src="./assets/profile-banner.svg" alt="Richard Effah Yeboah — full-stack developer building software for real businesses" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/richyeff"><strong>LinkedIn</strong></a> &nbsp; / &nbsp;
  <a href="https://kintampoafricanmarket.com"><strong>Live storefront</strong></a> &nbsp; / &nbsp;
  <a href="https://prince-inventory-manager.vercel.app"><strong>POS demo</strong></a>
</p>

## Hey, I'm Richard 👋

I'm a **Computer Science student at Grambling State University, graduating in May 2028**, building full-stack applications for commerce and everyday business operations.

I enjoy the engineering behind the interface: validating payments, keeping inventory consistent, making offline retries safe, and testing the workflows people rely on.

**My focus:** Java distributed systems · TypeScript & React applications · Reliable data and recovery

---

## Selected builds

### QuantaFs - distributed storage that recovers from server failure

**Java, Raft, gRPC, RocksDB, Docker, and Kubernetes.** A key-value store with majority-committed
writes, retry-safe sequential sessions, snapshots, and persistent recovery.

https://github.com/user-attachments/assets/dc12ddce-c965-4ef6-9ab4-46bf61bf3366

- **526 automated tests** plus a repeatable local Kubernetes failure/recovery demonstration.
- Replaced the leader Pod, reused its persistent volume, and verified the saved data.
- Demonstrated majority-loss refusal and recovery; published benchmark methodology and raw samples.

[Watch the 70-second demo](https://github.com/user-attachments/assets/dc12ddce-c965-4ef6-9ab4-46bf61bf3366) · [Explore the code](https://github.com/richardeyeboah/QuantaFs) · [Read the evidence](https://github.com/richardeyeboah/QuantaFs/blob/main/docs/benchmarks.md)

*Video: edited replay of a real local Kubernetes run; waits shortened. Three voters share one host.*

### 🛒 Kintampo African Market
**A production storefront for an African and Caribbean grocery store in Columbus, Ohio.**

- A catalog of **150+ products**, customer accounts, Stripe checkout, local pickup, and nationwide shipping.
- Server-side price validation, payment webhooks, refunds, and staff tools for inventory and fulfillment.
- **61 Playwright tests across 13 files** covering checkout, payment handling, receipts, navigation, and administrative APIs.

`Next.js` `TypeScript` `PostgreSQL` `Supabase` `Stripe` `Playwright`

[Visit the store →](https://kintampoafricanmarket.com) · [Explore the code](https://github.com/richardeyeboah/kintampo-african-market)

### 🔧 Prince Auto Inventory & POS
**Inventory and checkout built around the way a mechanic shop works.**

- Shared stock, parts and labor sales, customer balances, receipts, and reporting.
- Atomic database operations keep sales, stock changes, and financial records together.
- Offline sales sync after reconnection; idempotent retries prevent duplicate sales.

`React` `TypeScript` `Vite` `PostgreSQL` `Supabase` `Vitest`

[Open the demo →](https://prince-inventory-manager.vercel.app) · [Explore the code](https://github.com/richardeyeboah/prince-inventory-manager)

### 🌮 Item7 Food Truck
**Customer ordering and staff operations in one Flask application.**

- Menu browsing, ordering, and order tracking.
- Staff scheduling, shift tracking, and menu management.
- Role-based access for customers, staff, and administrators.

`Python` `Flask` `PostgreSQL` `SQLAlchemy` `JavaScript`

[Open the demo →](https://foodtruckk.vercel.app) · [Explore the code](https://github.com/richardeyeboah/project-foodtruck)

---

## Tools I work with

**Languages**  
TypeScript · JavaScript · Python · Java · SQL · HTML/CSS

**Applications & APIs**  
React · Next.js · Node.js · Flask · FastAPI · REST APIs · gRPC · Protocol Buffers

**Data & services**  
PostgreSQL · Supabase · Redis · RocksDB · SQLAlchemy · Stripe

**Testing & delivery**  
Playwright · Vitest · JUnit · Git · GitHub Actions · Docker · Kubernetes · Vercel

## Beyond the code

- Built **5 full-stack AI applications in 7 weeks** during the Headstarter fellowship.
- Worked on distributed storage with **Java, gRPC, RocksDB, and Raft**.
- Support peers through **ColorStack and NSBE** study groups, coding workshops, and interview preparation.

---

<p align="center">
  <strong>Interested in full-stack and backend software engineering internships.</strong><br />
  <a href="https://www.linkedin.com/in/richyeff">Let's connect on LinkedIn ↗</a>
</p>
