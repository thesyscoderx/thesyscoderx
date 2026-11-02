![Engineering notebook: from first principles to reliable systems.](assets/banner.svg)

# Hi, I'm Pruthviraj Sonawane.

I build backend projects and learn how to make systems easier to understand, operate, and trust. This is my engineering notebook: small experiments, deliberate practice, and projects that connect the pieces.

**Backend systems. Practical automation. Reliability by design.**

[Website](https://thesyscoder.com) &nbsp; / &nbsp; [On the workbench](#on-the-workbench) &nbsp; / &nbsp; [Learning in public](#learning-in-public)

---

## On the workbench

| Project | The idea | Current focus |
| :--- | :--- | :--- |
| **Meridian** | A multi-tenant backend built with Go microservices. | Tenant boundaries, identity, authorization, and reusable service libraries. |
| **Beacon** | A small Go project for learning service availability checks. | Building the prober incrementally, one working concept at a time. |
| **Bifrost** | A structured workspace for automation and SRE learning. | Commented exercises, small projects, and a roadmap from fundamentals to infrastructure. |

These repositories are currently **private**. The descriptions reflect work in progress, not claims of production scale.

## My technical direction

| Area | Tools and concepts |
| :--- | :--- |
| **Backend projects** | Go, gRPC, PostgreSQL, Redis, Kafka |
| **Automation practice** | Python, Go, shell, Make |
| **Infrastructure roadmap** | Azure, Terraform, Ansible |
| **Platform roadmap** | Docker, Compose, Kubernetes, AKS, Helm, Kind |
| **Delivery and reliability roadmap** | GitHub Actions, Azure DevOps, observability, SLOs, runbooks |

**A tool on the roadmap is a learning goal, not a proficiency claim.**

## Learning in public

My approach is simple: understand a concept, write a focused exercise, then use it in a small project.

**Current checkpoint:** Python fundamentals completed; practicing lists, logic, and loops.

<details>
<summary><strong>Open the learning map</strong></summary>

```mermaid
flowchart TD
    A["01 / Foundations<br/>Linux, networking, Git"] --> B["02 / Programming<br/>Python and Go"]
    B --> C["03 / Local systems<br/>Docker, Compose, Kind"]
    C --> D["04 / Infrastructure<br/>Azure, Terraform, Ansible"]
    C --> E["05 / Orchestration<br/>Kubernetes, AKS, Helm"]
    D --> F["06 / Delivery<br/>GitHub Actions, Azure DevOps"]
    E --> F
    F --> G["07 / Reliability<br/>Observe, diagnose, recover"]

    classDef foundations fill:#172554,stroke:#60a5fa,color:#eff6ff
    classDef building fill:#134e4a,stroke:#2dd4bf,color:#f0fdfa
    classDef delivery fill:#3b2357,stroke:#c4b5fd,color:#faf5ff
    classDef reliability fill:#4a3014,stroke:#fbbf24,color:#fffbeb
    class A,B foundations
    class C,D,E building
    class F delivery
    class G reliability
```

This is a direction of travel, not a completed checklist. I add implementation only as I work through the topics.

</details>

<details>
<summary><strong>What good practice looks like to me</strong></summary>

- Explain the code instead of just making it run.
- Prefer a small working example over an impressive empty scaffold.
- Separate focused **exercises** from **projects** that combine concepts.
- Make failures understandable and recovery repeatable.
- Keep credentials out of Git and cloud experiments within a budget.
- Document what is implemented, what is being explored, and what is still planned.

</details>

---

**Understand the system. Build with intent. Leave a useful trail.**
