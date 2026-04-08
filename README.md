# Iguidado — DevOps Engineer

> Student at École 42 Paris · Looking for a DevOps internship

I build and break infrastructure to understand how it actually works —
containerized stacks, automated environments, and the glue that keeps
services running and reproducible.
Security-minded by default: I think about hardening and least-privilege
as part of the build, not as an afterthought.

---

## Stack

**Infra & Orchestration**
Kubernetes · Docker · Vagrant · k3s

**Automation & IaC**
Ansible · Bash · Python · Makefile

**Observability**
ELK Stack (Elasticsearch · Logstash · Kibana)

**CI/CD & Security**
GitHub Actions · Vault · 

**Systems**
Linux (Debian/Alpine) · Networking (BGP, EVPN, VXLAN)

---

## Featured Projects

| Project | What it is | Stack |
|---|---|---|
| [ft_transcendence](https://github.com/iguidado/ft_transcendence) | Final 42 project — containerized full-stack app (Pong). I owned infra: NGINX reverse proxy, ELK logging stack (Logstash grok pipelines, Elasticsearch ILM/SLM, Kibana), microservices architecture, security hardening, and SSL under rootless Docker constraints. | Docker · NGINX · ELK · Django · PostgreSQL · JWT |
| [Inception of Things](https://github.com/iguidado/Inception_of_things) | Kubernetes environments from zero — k3s two-node cluster, multi-app Ingress routing, then k3d + ArgoCD GitOps pipeline. Includes a custom auto-provisioned Debian ISO (preseed + SSH key injection) to bootstrap the whole setup. | k3s · k3d · ArgoCD · Vagrant · Kubernetes |
| [Inception](https://github.com/iguidado/Inception) | Docker microservices stack built from scratch — NGINX (TLS 1.2/1.3), WordPress + PHP-FPM, MariaDB, Adminer, Redis. No pre-built images, custom Dockerfiles only. | Docker · NGINX · WordPress · MariaDB · PHP-FPM |
| [BADASS](https://github.com/iguidado/BADASS) | Data center network from scratch — BGP EVPN spine-leaf topology with containerized FRR routers, dynamic MAC learning, OSPF underlay. No static config, no physical hardware. | GNS3 · Docker · FRRouting · VXLAN · BGP EVPN |
| [ft_libasm](https://github.com/iguidado/ft_libasm) | Reimplementation of libc functions in x86_64 NASM Assembly — covers the full compilation pipeline, System V AMD64 calling convention, and Linux syscall interface. | x86_64 Assembly · NASM · Linux ABI |
| [ft_linear_regression](https://github.com/iguidado/ft_linear_regression) | Supervised learning pipeline from scratch — gradient descent with configurable loss functions (MSE/RMSE/MAE), weight serialization, and inference. No ML framework in the core logic. | Python · NumPy · pandas · matplotlib |

---

## Currently Learning

- Kubernetes internals (working toward CKAD)
- Ansible roles and Vault integration
- GitHub Actions — CI/CD pipelines
- Supply chain security (SBOM, image signing)

---

## Contact

[LinkedIn](https://www.linkedin.com/in/isma%C3%ABl-guidadou-584b62153/) · ismael.guidadou.pro@gmail.com

<!--
**iguidado/iguidado** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
