<p align="center">
  <img src="assets/zexus_icon.png" width="96" height="96" alt="Zexus Pure EC Icon">
</p>

<h1 align="center">Zexus Pure EC</h1>

<p align="center">
  <strong>AI Agent for Autodesk Revit — Pure ExecuteCode Architecture</strong><br>
  Natural language interface for BIM operations. One universal tool (ExecuteCode) handles all Revit tasks via runtime C# compilation.
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
2. Download `ZexusPureEC_Setup_vX.Y.Z.msi`
3. Run the installer — it will deploy the add-in to your Revit Addins folder
4. Launch Revit (2022 / 2023 / 2024 / 2025 / 2026) and find **Zexus Pure EC** in the ribbon

## Supported Revit Versions

| Version | Framework |
|---------|-----------|
| Revit 2022 | .NET Framework 4.8 |
| Revit 2023 | .NET Framework 4.8 |
| Revit 2024 | .NET Framework 4.8 |
| Revit 2025 | .NET 8.0 |
| Revit 2026 | .NET 8.0 |

## Setup

1. Click the Zexus Pure EC button in the Revit ribbon to open the chat window
2. Open **Settings** (gear icon) to configure your AI provider:
   - **Anthropic Claude** (recommended)
   - **OpenAI GPT**
   - **Google Gemini**
3. Enter your API key and select a model
4. Start chatting — e.g., *"List all sheets in this project"*

## What Can Zexus Pure EC Do?

Zexus Pure EC uses a **Pure ExecuteCode architecture** — a single universal tool that compiles and executes C# code at runtime via Roslyn. The LLM writes the code, the system compiles and runs it inside Revit.

This means it can do **anything the Revit API can do**:

- Query model data (elements, parameters, views, sheets, schedules)
- Create and modify elements (walls, sheets, views, schedules, filters)
- Set and batch-modify parameters
- Apply graphic overrides (colors, visibility, view filters)
- Generate documentation (tag elements, create schedules)
- Export and print
- Custom automation workflows

## Feedback & Bug Reports

Found a bug or have a suggestion? Open an [Issue](https://github.com/QuanZ827/Zexus-Releases/issues).

## Disclaimer

Zexus Pure EC is an **independent, personal project** developed and maintained by Zhequan Zhang. It is not affiliated with, endorsed by, or sponsored by Autodesk, Anthropic, OpenAI, Google, or any employer past or present.

**Use at your own risk.** Always save your Revit project before using AI-assisted automation. AI outputs are not guaranteed and should be reviewed by qualified professionals before applying to production models.

## License

Zexus Pure EC is proprietary software. By downloading and using the installer, you agree to the [End User License Agreement (EULA)](LICENSE).

All rights reserved. © 2024-2026 Zhequan Zhang.

---

<p align="center">
  Built by <a href="https://github.com/QuanZ827">Zhequan Zhang</a>
</p>
