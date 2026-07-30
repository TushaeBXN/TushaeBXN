<h1>Brian Thomas</h1>
<h3>AI Systems Architect · Founder · Anthos Intelligence</h3>

<p>
I build AI systems that shouldn't exist yet — and architect the governance structures that make them safe to deploy. My work sits at the intersection of frontier model design, autonomous agent infrastructure, and AI risk management. I don't fine-tune existing models when the architecture itself is the constraint. I design from first principles, evaluate trade-offs against real operational requirements, and ship systems that organizations can actually govern and trust.
</p>

---

<h2>Featured Architecture Work</h2>

<h3><a href="https://github.com/TushaeBXN/anthos">Anthos — Custom Recurrent Transformer</a></h3>

<p>
<b>Problem:</b> Fine-tuning frontier models creates dependency on third-party infrastructure, licensing constraints, and alignment behavior you don't control. For a sovereign AI system, that's an architectural risk, not just a technical inconvenience.
</p>
<p>
<b>Decision:</b> Design a Thought-Token Bifurcated Recurrent Transformer from scratch — a custom architecture with a dedicated reasoning channel (THT tokens) that separates internal deliberation from output generation. Custom tokenizer. Custom training pipeline. No upstream model dependency.
</p>
<p>
<b>Trade-off:</b> Significantly higher upfront cost versus LoRA fine-tuning. The return: full architectural control, identity-stable behavior under adversarial prompting, and a system that improves on a training schedule I own entirely.
</p>
<p>
<b>Outcome:</b> Multi-tier training pipeline (smoke → proof → identity hardening → instruct → distill) with validated identity coherence and the foundation for sovereign, auditable AI behavior at the organizational level.
</p>

---

<h3><a href="https://github.com/TushaeBXN/kerrigan-fantasma-overview">Kerrigan-Fantasma — Autonomous Security Research Engine</a></h3>

<p>
<b>Problem:</b> Offensive security tooling is either static (signature-based) or dependent on human analysts to close the loop between discovery and exploitation. Neither scales against modern attack surfaces.
</p>
<p>
<b>Decision:</b> Build a Recurrent-Depth Transformer trained natively on low-level systems knowledge — Linux kernel source, UEFI firmware, CPU architecture specifications, CVEs, and 12 programming languages — with an autonomous fuzzing loop that writes its own exploit harnesses, attacks them, and learns from the results.
</p>
<p>
<b>Trade-off:</b> A self-modifying security system requires a defense-in-depth execution environment that is as rigorous as the threat model it addresses. The 7-layer sandbox (code validation, resource limits, Docker isolation, and more) is not overhead — it is the governance condition that makes autonomous offensive research deployable.
</p>
<p>
<b>Outcome:</b> A Tier 3/4 dual-use AI system with formal risk classification, a contained autonomous research loop, and an architecture that can be audited, governed, and extended — rather than a black-box wrapper around someone else's model.
</p>

---

<h3><a href="https://github.com/TushaeBXN/runway">Runway — AI Agent Operating System for Nonprofits</a></h3>

<p>
<b>Problem:</b> Nonprofits operate with enterprise-level coordination complexity and startup-level resources. Constituent intake, case routing, donor engagement, and compliance reporting consume staff capacity that should be directed toward mission delivery.
</p>
<p>
<b>Decision:</b> Architect a full multi-agent platform — not a chatbot, not an automation script — purpose-built for nonprofit operations. Specialized agents handle intake triage, rights assessment, resource routing, and communications, coordinated through a shared context layer with human oversight checkpoints at every consequential decision.
</p>
<p>
<b>Trade-off:</b> A platform investment versus off-the-shelf SaaS. The return: agents that understand the specific legal, financial, and cultural context of the populations being served — rather than general-purpose tools that require staff to translate between the tool's model of the world and the organization's operational reality.
</p>
<p>
<b>Outcome:</b> Deployed stack (Next.js, PostgreSQL, Prisma, Anthropic SDK) with role-based agent coordination, privacy-preserving data handling, and an architecture designed to scale across organizations without re-engineering per deployment.
</p>

---

<h3><a href="https://github.com/TushaeBXN/push-job">Push-Job — AI Workflow Orchestration</a></h3>

<p>
<b>Problem:</b> Most AI integrations are point solutions — a model call here, an automation trigger there. That approach doesn't compose. When workflows span multiple models, data sources, and decision points, ad hoc integrations become the reliability bottleneck.
</p>
<p>
<b>Decision:</b> Design a structured workflow orchestration layer where AI reasoning steps are first-class architectural components — with defined inputs, outputs, failure modes, and retry semantics — rather than imperative scripts wrapped around API calls.
</p>
<p>
<b>Outcome:</b> A composable workflow architecture that treats AI inference as a managed resource, enabling reliable multi-step pipelines that can be monitored, audited, and extended without rearchitecting from scratch.
</p>

---

<h2>AI Governance & Compliance</h2>

<h3><a href="https://github.com/TushaeBXN/anthos-grc">Anthos GRC — AI Governance, Risk & Compliance</a></h3>

<p>
<b>Problem:</b> AI systems are being deployed into consequential domains — security research, constituent services, organizational decision support — without governance frameworks that match their risk profile. The absence of formal AI governance isn't a documentation gap; it's a liability that compounds with every deployment.
</p>
<p>
<b>Decision:</b> Build and maintain a formal AI governance portfolio mapped to NIST AI RMF 1.0 and ISO/IEC 42001:2023 — not as compliance theater, but as operational infrastructure. Every system I build carries a system-specific governance card, a risk classification, and a documented control set before it is deployed.
</p>
<p>
<b>Scope:</b> Covers Kerrigan-Fantasma (Tier 3/4 dual-use autonomous system), CyberGuard AI (Tier 3 security console), and the Anthos model ecosystem. Includes org-level AI policy, master risk register, incident response posture, and third-party model governance for all upstream dependencies.
</p>
<p>
<b>Why this matters:</b> As AI regulation accelerates globally, organizations that treat governance as an afterthought will face both operational and legal exposure. The Anthos GRC framework is my answer to that risk — applied to my own systems first, extensible to others.
</p>

---

<h2>Connect</h2>

[LinkedIn](https://www.linkedin.com/in/brian-t-24748719/)
