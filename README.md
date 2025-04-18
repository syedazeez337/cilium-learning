# 🚀 Cilium Learning Repository

This repository is a hands-on guide and documentation of my journey to learn [Cilium](https://github.com/cilium/cilium) — an eBPF-based networking, observability, and security layer for cloud-native environments.

---

## 📘 What is Cilium?

Cilium is a Kubernetes CNI plugin that uses eBPF to provide:
- High-performance networking
- Transparent security policies (L3–L7)
- Load balancing
- Deep observability and flow visibility using Hubble

Learn more: https://docs.cilium.io/en/stable/overview/what-is-cilium/

---

## 📚 Learning Roadmap

| Phase | Focus | Deliverables |
|-------|-------|--------------|
| 1 | Basics of Cilium and eBPF | `week1/what-is-cilium.md` |
| 2 | Local Cluster Setup (kind + cilium) | `week2/local-setup.md` |
| 3 | CiliumNetworkPolicy Testing | `policies/` |
| 4 | Architecture Internals | `week4-5/architecture.md` |
| 5 | Gateway API, Egress Gateway | `advanced-features/` |
| 6 | Codebase + Hive Framework | `week8/codebase-notes.md` |

---

## 🔗 Official Resources

- 📖 Docs: https://docs.cilium.io/
- 🧠 eBPF Intro: https://ebpf.io/
- 🧪 Playground: https://play.cilium.io/
- 📺 Talks: [YouTube: Isovalent / Cilium](https://www.youtube.com/c/Isovalent)
- 💬 Community Slack: https://cilium.herokuapp.com/

---

## 📦 Repo Structure

```
cilium-learning/
├── Cilium-Learning-Plan.md       # Master learning plan with phases
├── week1/                        # Basics: What is Cilium
├── week2/                        # Local setup with kind
├── policies/                     # Policy YAMLs and experiments
├── week4-5/                      # Architecture internals
├── advanced-features/           # Gateway API, LB, etc.
├── week8/                        # Hive and code contribution notes
└── README.md                     # You're here!
```

---

## 📌 Goal

Build a complete knowledge base + demos to understand, contribute to, and possibly work with Cilium in production.

PRs and suggestions welcome!
