# System Architecture Portfolio

This portfolio showcases my work as a System Architect, focusing on designing simple, scalable, and resilient distributed systems.  
Each project includes architectural decisions (ADRs), diagrams, trade-offs, and production-style reasoning — not just code.

## Purpose

To demonstrate my ability to:
- Think and design like a system architect  
- Model distributed systems clearly  
- Evaluate trade-offs under real-world constraints  
- Apply simplicity as a design principle  
- Build small but high-quality architectural components  
- Document and justify decisions professionally  

## Portfolio Structure

```sql
/projects
/project-name
README.md
/docs
architecture.md
adr/
diagrams/
```

## Completed Projects

- **go-sharding-basic** — Example Go system implementing hash(username) % N to distribute users across multiple PostgreSQL shards. Clean separation (API/Handler/Service/Router/Storage/Shards), deterministic routing for reads/writes, horizontal scale ready. Includes C4 Level 1/2 diagrams and an ADR for the sharding approach.  
  Repo: https://github.com/Nehonar/go-sharding-basic

## In Progress

- **Consistent Hashing Router (routerd)** — dynamic routing with minimal data movement  

## Roadmap

- Event-driven dispatcher  
- Distributed lock service  
- In-memory coordination service  
- Telemetry and observability pipeline  
- Queue-based work balancer  
- Replication & leader election module  
- Config + feature flag distributed system  

##  About Me

I design systems by:
- Eliminating accidental complexity  
- Making constraints explicit  
- Focusing on load, failure, flow, and boundaries  
- Prioritizing clarity and operational simplicity  

## Contact

(You will fill this later)

## Web Portfolio Preview

- Open `index.html` in your browser to see the retro landing.
- Anchors use smooth scrolling and the UI respects `prefers-reduced-motion`.
- Sections included: hero intro, manifesto, focus areas, workbench, and contact.
