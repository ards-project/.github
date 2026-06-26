# Agentic Resource Discovery (ARD) Standard Project

Welcome to the official home of the **Agentic Resource Discovery (ARD)** standards project. We are a collaborative, open-source initiative dedicated to establishing an open, federated discovery protocol for **agentic resources**—any external capability an AI client can call on to perform a task (including agents, MCP servers, Skills, APIs, or workflows).

Our mission is to enable secure, decentralized, and interoperable discovery by solving the **discovery, context limit, and trust bottleneck** at scale.

---

## 🧭 What is ARD?

As the agentic ecosystem scales, AI clients must dynamically discover and invoke external capabilities across organizational boundaries. **ARD** sits entirely *before* invocation: it helps the client find the right resource, which is then invoked through its own native mechanism.

The ARD standard is built around several core pillars:

*   **Search-First Discovery:** Moves away from static "app store" install models, allowing AI clients to query discovery services dynamically (*"What is available for this task?"*) based on natural-language needs.
*   **Context Window Optimization:** Solves context limit bottlenecks by offloading candidate selection to dedicated discovery registries, eliminating the need to inject thousands of tool descriptions into the LLM context window.
*   **Artifact-Agnostic Envelope:** Serves as a clean metadata envelope using IANA media types to wrap MCP servers, A2A agents, and static Skills without prescribing internal protocol schemas.
*   **Decoupled Cryptographic Trust:** Decouples logical discovery names (`urn:air`) from mutable physical workload identities (SPIFFE, DIDs), protecting enterprise network topologies while enabling security via progressive trust verification.


---

## 🗂️ Key Repositories

*   📚 **[ard-spec](https://github.com/ards-project/ard-spec)** — The canonical, single source of truth for the ARD specification, CDDL/JSON/OpenAPI schemas, and architecture decision records (ADRs).
*   📖 **[ard-docs](https://github.com/ards-project/ard-docs)** — The source code and content for the official project documentation site and developer guides.
*   🔌 **[ard-connectors](https://github.com/ards-project/ard-connectors)** — Reference connectors, adapter templates, and SDK integration layers for major agent platforms and protocols.


---

## 🤝 Industry Collaboration

The ARD standard is currently developed as an open-source collaboration among engineers and architects from major industry organizations. We collaborate closely with contributors from **Cisco, Databricks, GitHub, GoDaddy, Google, Hugging Face, Microsoft, Nvidia, Salesforce, ServiceNow, and Snowflake** to prevent industry fragmentation and drive global standards harmonization.


---

## 💬 Join the Community

*   **Discord:** Join our channel @ https://discord.gg/VpcmAzsfT.


---

## 🤝 Contributing

We welcome contributions of all types! To get started:
1. Read the contribution guidelines in [ard-spec/README.md](https://github.com/ards-project/ard-spec#contributing).
2. For normative spec changes, please open an issue first to discuss the design.
3. For non-normative contributions (bug fixes, tooling, examples, reference code), feel free to open a Pull Request directly!

---

*Securing and standardizing the future of decentralized AI agent collaboration.*
