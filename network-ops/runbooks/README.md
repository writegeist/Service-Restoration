# Network Operations Runbooks: A Docs-as-Code Approach

Welcome to the **Network Operations (NetOps) Runbook Repository**. This project demonstrates how to manage critical infrastructure documentation using modern software engineering workflows.

## 🚀 The Philosophy: Docs-as-Code
Instead of static PDFs or siloed Wiki pages, these runbooks are treated as **living code**. This approach provides several key benefits:
* **Version Control:** Every change is tracked via Git, providing a clear audit trail of who updated a procedure and why.
* **Peer Review:** Updates are proposed through **Merge Requests (MRs)**, ensuring technical accuracy through collaborative review.
* **Automation-Ready:** Markdown files are easily parsed by CI/CD tools to generate internal documentation sites or searchable knowledge bases.
* **Technical Clarity:** Complex workflows are visualized using **Mermaid.js** diagrams, rendered natively within GitLab.

---

## 📂 Repository Structure

```text
.
├── runbooks/           # Actionable procedures for specific network events
│   ├── connectivity/   # VPN, BGP, and Layer 2/3 troubleshooting
│   └── security/       # Firewall rules and Access Control List (ACL) updates
├── templates/          # Standardized Markdown templates for new runbooks
└── README.md           # You are here
