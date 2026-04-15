# Zexus — AI Agent Family for Autodesk Revit

Three products, one mission: bring AI-powered automation to Revit.

| Product | Description | Latest | Download |
|---------|-------------|--------|----------|
| **Zexus** | Full AI agent — 29 tools + ExecuteCode | v0.4.5.1 | [Download](../../releases/tag/zexus-v0.4.5.1) |
| **Zexus Pure EC** | Lightweight — single ExecuteCode tool | v0.1.3.1 | [Download](../../releases/tag/pure-ec-v0.1.3.1) |
| **ZexusQAQC** | BIM QAQC checker — bring your own Knowledge Base | v0.2.0 | [Download](../../releases/tag/qaqc-v0.2.0) |

---

## Zexus (Full Version)
Full-featured AI agent with 29 registered tools covering element queries,
parameter editing, view creation, documentation, and more. Plus ExecuteCode
for unlimited Revit API access via runtime C# compilation.

**Latest:** [v0.4.5.1](../../releases/tag/zexus-v0.4.5.1)

## Zexus Pure EC
Lightweight architecture with a single universal tool (ExecuteCode).
The LLM writes C# code, Roslyn compiles it, and it runs inside Revit.
Anything the Revit API can do, Pure EC can do.

**Latest:** [v0.1.3](../../releases/tag/pure-ec-v0.1.3.1)

## ZexusQAQC
AI-powered BIM QAQC checker driven by a structured Knowledge Base **you author**.
The plugin engine is domain-agnostic: swap the KB to check any BIM standard.
Ships with schema templates; **no rules bundled** — adapt it to your own standard.
Provider-agnostic: works identically with Claude, Gemini, or GPT.

**Latest:** [v0.2.0](../../releases/tag/qaqc-v0.2.0)

---

## Setup (All Products)
1. Download the MSI from the release page
2. Run the installer
3. Open Revit → find the product in the ribbon
4. Configure your LLM API key (Anthropic / Google / OpenAI)

## Supported Revit Versions
| Version | Framework |
|---------|-----------|
| Revit 2022-2024 | .NET Framework 4.8 |
| Revit 2025-2026 | .NET 8.0 |

## License
Proprietary software. All rights reserved. © 2024-2026 Zhequan Zhang.
