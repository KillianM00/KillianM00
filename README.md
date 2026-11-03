# Killian Miller

**Independent security research · Bug bounty hunting · Systems programming**

I investigate trust boundaries in developer tools and build systems software. My work includes a responsible disclosure recognized by Anthropic, virtualization research, pre-boot authentication, and reproducible security evaluation.

[Technical portfolio](https://kmiller.dev/) · [Contact](mailto:killianmiller6@gmail.com)

## Featured research — Anthropic

**Independent bug bounty research · Developer-tool security · May 2026**

Investigated how repository-provided hooks and MCP configuration interact with workspace trust and noninteractive execution in Anthropic’s coding-agent CLI.

- Prepared reproduction cases, permission-mode comparisons, and startup timing evidence.
- Submitted the research and followed up with Anthropic’s security team to examine alternative explanations.
- **Outcome:** Anthropic recognized the submission as informative and said it aided the discovery of other vulnerabilities.

**Skills:** threat modeling, controlled experiments, reproduction design, evidence analysis, and technical disclosure writing.

[Read the research summary →](https://kmiller.dev/research/anthropic/)

## Selected security and systems work

| Project | Engineering focus | Read more |
| --- | --- | --- |
| **Wraith** | Linux KVM host, ELF32 guest loading, freestanding C/assembly kernel, and a separate UEFI/AMD SVM research path. | [Case study](https://kmiller.dev/projects/wraith/) |
| **BootGate** | UEFI authentication, PBKDF2 password derivation, persistent lockout state, recovery credentials, and optional TPM PCR checks. | [Case study](https://kmiller.dev/projects/bootgate/) |
| **Polysec Harness** | Python orchestration, bounded parallel investigation, typed evidence, independent verification, and reproduction workflows. | [Case study](https://kmiller.dev/projects/polysec-harness/) |
| **Redteam Harness** | Separate evaluation roles, structured attempt records, drift audits, and clearly labeled synthetic replay. | [Case study](https://kmiller.dev/projects/redteam-harness/) |
| **Hostcheck / Leakcheck** | Native host-posture adapters and VPN diagnostics with structured findings and explicit inconclusive outcomes. | [Hostcheck](https://kmiller.dev/projects/hostcheck/) · [Leakcheck](https://kmiller.dev/projects/leakcheck/) |

These repositories are currently private. Their public case studies describe implementation choices, threat boundaries, and validation limits.

## Selected public source

- **[RLBOTSLOT](https://github.com/KillianM00/RLBOTSLOT)** — simulation-based reinforcement learning with object-centric observations, recurrent policy state, PPO, and vectorized rollout infrastructure. Research prototype; [current evidence and limitations](https://kmiller.dev/projects/rlbotslot/).
- **[Gmail Manager](https://github.com/KillianM00/gmail-manager)** — OAuth-backed API integration, batch workflows, and shared Python services behind a CLI and local FastAPI UI.
- **[BL2 Save Editor](https://github.com/KillianM00/bl2-save-editor)** — binary-format integration, bit-packed item serialization, per-file locking, atomic replacement, and optional 3D asset visualization.
- **[flaggle.lofi](https://github.com/KillianM00/flaggle-lofi)** — deterministic daily state, geospatial/color algorithms, versioned browser persistence, and procedural Web Audio.
- **[RL Map Manager](https://github.com/KillianM00/rl-map-manager)** — PySide6 catalog integration, metadata caching, and content-installation workflows.
- **[Roblox Multi-Instance](https://github.com/KillianM00/roblox-multi-instance)** — C# / WPF, native resource lifetime, DPAPI-backed storage, MVVM, and DWM window previews.

## Technical focus

| Area | Evidence in the projects |
| --- | --- |
| Systems programming | C, x86 assembly, ELF loading, Linux KVM, UEFI/EDK II, AMD SVM |
| Security engineering | Threat models, authentication policy, host/network diagnostics, evidence-based evaluation |
| Python tooling | Typed schemas, subprocess orchestration, filesystem IPC, CLI/API services, test fixtures |
| Application systems | TypeScript/JavaScript, relational persistence, state machines, browser APIs, C#/.NET |
| Applied ML | PyTorch, PPO, recurrent state, rollout collection, synthetic pipeline validation |

For security, systems, and computer-science engineering opportunities: [killianmiller6@gmail.com](mailto:killianmiller6@gmail.com).
