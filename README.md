<p align="center">
  <img src="assets/zexus_icon.png" width="96" height="96" alt="Zexus Icon">
</p>

<h1 align="center">Zexus</h1>

<p align="center">
  <strong>AI Agent for Autodesk Revit</strong><br>
  Natural language interface for BIM operations — query models, automate tasks, QA/QC workflows, and more.
</p>

<p align="center">
  <a href="https://github.com/QuanZ827/Zexus-Releases/releases/latest">
    <img src="https://img.shields.io/github/v/release/QuanZ827/Zexus-Releases?label=Download&style=for-the-badge&color=4285F4" alt="Latest Release">
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/license-Proprietary-red" alt="License">
</p>

---

## Download & Install

1. Go to **[Releases](https://github.com/QuanZ827/Zexus-Releases/releases/latest)**
2. Download `Zexus_Setup_vX.Y.Z.msi`
3. Run the installer — it will deploy the add-in to your Revit Addins folder
4. Launch Revit (2022 / 2023 / 2024 / 2025 / 2026) and find **Zexus** in the ribbon

## Supported Revit Versions

| Version | Framework |
|---------|-----------|
| Revit 2022 | .NET Framework 4.8 |
| Revit 2023 | .NET Framework 4.8 |
| Revit 2024 | .NET Framework 4.8 |
| Revit 2025 | .NET 8.0 |
| Revit 2026 | .NET 8.0 |

## Setup

1. Click the Zexus button in the Revit ribbon to open the chat window
2. Open **Settings** (gear icon) to configure your AI provider:
   - **Anthropic Claude** (recommended)
   - **OpenAI GPT**
   - **Google Gemini**
3. Enter your API key and select a model
4. Start chatting — e.g., *"List all sheets in this project"*

## What Can Zexus Do?

Zexus provides **29 tools** (28 predefined + ExecuteCode) with a **Code-First + Smart Tool Hybrid** architecture — smart tools handle high-implicit-rule operations, while ExecuteCode (Roslyn) covers everything else:

| Category | Tools |
|----------|-------|
| **Query** | Model overview, search elements, get parameters, get selection, get warnings |
| **Action** | Select/isolate/color elements, set parameters (single & batch), activate views, set category visibility, create view filters |
| **Schedule & Param** | Create schedules & project parameters, add/format fields, filters, sorting |
| **Output** | List sheets & views, print sheets, export documents |
| **Documentation** | Tag elements, dimension elements |
| **QA/QC** | Check workset assignments, create QC evidence packs |
| **MEP** | Show disconnects |
| **Universal** | Execute custom C# code via Roslyn — with PolicyGate write safety enforcement |

## Feedback & Bug Reports

Found a bug or have a suggestion? Open an [Issue](https://github.com/QuanZ827/Zexus-Releases/issues).

## Disclaimer

Zexus is an **independent, personal project** developed and maintained by Zhequan Zhang. It is not affiliated with, endorsed by, or sponsored by Autodesk, Anthropic, OpenAI, Google, or any employer past or present.

**Use at your own risk.** Always save your Revit project before using AI-assisted automation. AI outputs are not guaranteed and should be reviewed by qualified professionals before applying to production models.

## License

Zexus is proprietary software. By downloading and using the installer, you agree to the [End User License Agreement (EULA)](LICENSE).

All rights reserved. © 2024-2026 Zhequan Zhang.

---

<p align="center">
  Built by <a href="https://github.com/QuanZ827">Zhequan Zhang</a>
</p>
