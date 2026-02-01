# Class Discussion: SDLC Effectiveness and Agile in the Enterprise

**Question 1:** Which software development life cycle (SDLC) model is most effective for different types of projects, and why?  
**Question 2:** Do you believe Agile has failed in many corporate implementations?

---

## Article Summary

The readings argue that **no single SDLC is universally “best.”** Effectiveness depends less on methodology preference and more on **team size and the resulting communication complexity**. The number of potential communication links between people grows quadratically with team size (n × (n − 1) / 2). That coordination overhead is the main constraint that determines which process can work and which will break down.

**SDLC by context:**

- **Solo / two-person teams:** Lightweight flow works best—e.g., Kanban for solo work, or a hybrid of adapted Scrum (e.g., 1-week sprints, minimal ceremonies), Kanban, prototyping, DevOps, and RAD for two-person teams. Waterfall and full Scrum are poor fits (documentation and role overhead with little benefit).
- **Small teams (3–9):** This is Agile’s natural range. Scrum, XP, and Kanban are effective because communication links stay manageable; ceremonies add structure without overwhelming the team. Choice among them depends on requirements clarity, technical risk, customer availability, and delivery cadence.
- **Medium teams (10–30):** Informal, single-team Agile starts to strain. Coordination (e.g., 105 links for 15 people) demands more structure: Scaled Agile (SAFe), Spiral, or V-Model, depending on need for flexibility vs. traceability and regulation.
- **Large teams (30+):** Pure Agile “by the book” is not viable. Success requires either heavy process (Waterfall phase gates, SAFe), architectural decomposition (e.g., microservices so the org behaves like many small teams), or hybrids (e.g., Waterfall governance with Agile delivery). The analysis cites microservices/DevOps-style decomposition as achieving the highest success rate by turning a large-team problem into many small-team problems.

So **the most effective SDLC is the one that matches the communication reality of the team and project**—not the one that is trendy or “best practice” in the abstract.

---

## Has Agile Failed in Corporate Implementations?

The material does **not** say Agile itself has failed. It explains why Agile often **underperforms or feels broken in many corporate settings**.

Agile (Scrum, XP) is designed for **small, co-located or tightly coupled teams** with few communication links. In that context, it structures collaboration and reduces overhead. In corporations, Agile is frequently applied to:

- **Medium or large teams** without scaling (e.g., SAFe) or decomposition (e.g., microservices),
- **Cross-team programs** where dependencies and handoffs multiply,
- **Governance-heavy or regulated environments** where informal, ceremony-light Agile clashes with compliance and audit needs.

In those situations, the same practices that help small teams—daily standups, sprint planning, informal alignment—can become **overhead**: more meetings, more alignment work, and slower delivery as link count grows. So the “failure” is often **misapplication**—using a small-team Agile model in a context where communication complexity has already made that model a bad fit.

The conclusion from the readings: **Agile has not failed as an idea; it is often applied in the wrong context.** Success depends on aligning the SDLC (whether Agile, Waterfall, SAFe, or hybrid) with team size, structure, and organizational reality, rather than treating one model as the default for every project.
