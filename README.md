# StalFe Cloud Skills Hub

[![Total Skills](https://img.shields.io/badge/skills-2%2C737-blue.svg)](catalog.json)
[![Domains](https://img.shields.io/badge/domains-8%20core%20categories-green.svg)](#categories)
[![License](https://img.shields.io/badge/license-MIT-purple.svg)](LICENSE)

A comprehensive, production-ready library of **2,737 curated AI Agent Skills** for autonomous coding agents, cybersecurity operations, cloud orchestration, enterprise workflows, and frontend design.

Compatible with **Google Antigravity**, **Claude Code / Claude Desktop**, **Cursor**, **Codex / OpenCode**, **GitHub Copilot**, **Windsurf**, and **Cline**.

---

## 📑 Table of Contents

- [Overview & Statistics](#-overview--statistics)
- [Categories](#-categories)
- [Quickstart & Installation](#-quickstart--installation)
  - [Google Antigravity](#1-google-antigravity)
  - [Claude Desktop / Claude Code](#2-claude-desktop--claude-code)
  - [Cursor](#3-cursor)
  - [GitHub Copilot & VS Code](#4-github-copilot--vs-code)
- [Skill Specification](#-skill-specification)
- [Programmatic Catalog Access](#-programmatic-catalog-access)
- [Featured Skills Directory](#-featured-skills-directory)
- [License](#-license)

---

## 📊 Overview & Statistics

| Category | Skills Count | Primary Focus |
| :--- | :--- | :--- |
| **Integrations & SaaS** | `832` | Composio tool integrations (GitHub, Slack, Jira, Salesforce, AWS, Discord, Stripe, etc.) |
| **Cybersecurity** | `816` | Threat hunting, DFIR, SIEM detection rules, red teaming, exploit analysis, malware triage |
| **Copilot & Dev Workflows** | `422` | Codebase onboarding, refactoring, agentic testing, CI/CD, review flows |
| **Software Engineering** | `395` | System architecture, backend APIs, databases, microservices, cloud infra |
| **Corporate & Operations** | `166` | Executive decision making, finance, HR, legal, sales ops, supply chain |
| **Marketing & Growth** | `49` | A/B testing, ad copy, SEO optimization, growth funnels, customer acquisition |
| **Design & UI/UX** | `38` | Taste standards, Stitch design systems, GSAP animations, Tailwind, Radix, Shadcn |
| **Core Office & Tools** | `19` | Document processing (PDF, DOCX, XLSX, PPTX), MCP builder, Claude API, Themes |
| **Total Usable Skills** | **2737** | **Production-grade Agent Skills** |

---

## 🚀 Quickstart & Installation

### 1. Google Antigravity
Clone or symlink the skills into your global or workspace configuration root:
```bash
# Global skills location
git clone https://github.com/StalFe-Cloud/skills.git ~/.gemini/config/skills/stalfe-skills

# Or copy specific skill folders into your workspace
cp -r skills/cybersecurity/analyzing-active-directory-acl-abuse .agents/skills/
```

### 2. Claude Desktop / Claude Code
Add to your Claude skills directory:
```bash
git clone https://github.com/StalFe-Cloud/skills.git ~/.claude/skills/stalfe-skills
```

### 3. Cursor
Install into `.cursor/skills/` within your workspace root:
```bash
mkdir -p .cursor/skills
cp -r skills/design-and-ui/stitch-design-taste .cursor/skills/
```

### 4. GitHub Copilot & VS Code
Place into `.github/skills/` for workspace-level skill recognition:
```bash
mkdir -p .github/skills
cp -r skills/copilot-dev/* .github/skills/
```

---

## 🧩 Skill Specification

Each skill adheres strictly to the Open Agent Skill specification:

```markdown
---
name: <unique-skill-slug>
description: <precise trigger condition and capabilities>
---

# Skill Title
Detailed workflow instructions, execution rules, and command patterns...
```

---

## 📖 Programmatic Catalog Access

All skills are indexed in [`catalog.json`](catalog.json) with JSON schema:

```json
{
  "id": "cybersecurity.abusing-dpapi-for-credential-access",
  "name": "abusing-dpapi-for-credential-access",
  "category": "cybersecurity",
  "description": "Trigger and usage instructions...",
  "path": "skills/cybersecurity/abusing-dpapi-for-credential-access/SKILL.md",
  "size_bytes": 10895
}
```

---

## 🌟 Featured Skills Directory

### 🛡️ Cybersecurity (Sample)
| Skill Name | Description | Path |
| :--- | :--- | :--- |
| [`abusing-dpapi-for-credential-access`](skills/cybersecurity/abusing-dpapi-for-credential-access/SKILL.md) | Extract and decrypt Windows DPAPI-protected secrets (Credential Manager, browser logins/cookies, Wi-... | [`skills/cybersecurity/abusing-dpapi-for-credential-access/SKILL.md`](skills/cybersecurity/abusing-dpapi-for-credential-access/SKILL.md) |
| [`abusing-shadow-credentials-for-privesc`](skills/cybersecurity/abusing-shadow-credentials-for-privesc/SKILL.md) | Take over Active Directory accounts by writing attacker-controlled public keys to msDS-KeyCredential... | [`skills/cybersecurity/abusing-shadow-credentials-for-privesc/SKILL.md`](skills/cybersecurity/abusing-shadow-credentials-for-privesc/SKILL.md) |
| [`achieving-cmmc-level-2-compliance`](skills/cybersecurity/achieving-cmmc-level-2-compliance/SKILL.md) | >- Prepare a defense-contractor environment for CMMC Level 2 certification: scope CUI and FCI, imple... | [`skills/cybersecurity/achieving-cmmc-level-2-compliance/SKILL.md`](skills/cybersecurity/achieving-cmmc-level-2-compliance/SKILL.md) |
| [`acquiring-disk-image-with-dd-and-dcfldd`](skills/cybersecurity/acquiring-disk-image-with-dd-and-dcfldd/SKILL.md) | Create forensically sound bit-for-bit disk images with dd or dcfldd on a Linux forensic workstation,... | [`skills/cybersecurity/acquiring-disk-image-with-dd-and-dcfldd/SKILL.md`](skills/cybersecurity/acquiring-disk-image-with-dd-and-dcfldd/SKILL.md) |
| [`analyzing-active-directory-acl-abuse`](skills/cybersecurity/analyzing-active-directory-acl-abuse/SKILL.md) | Detect dangerous ACL misconfigurations in Active Directory using ldap3 to identify GenericAll, Write... | [`skills/cybersecurity/analyzing-active-directory-acl-abuse/SKILL.md`](skills/cybersecurity/analyzing-active-directory-acl-abuse/SKILL.md) |
| [`analyzing-android-malware-with-apktool`](skills/cybersecurity/analyzing-android-malware-with-apktool/SKILL.md) | Perform static analysis of Android APK malware using apktool for resource decompilation, jadx for Ja... | [`skills/cybersecurity/analyzing-android-malware-with-apktool/SKILL.md`](skills/cybersecurity/analyzing-android-malware-with-apktool/SKILL.md) |
| [`analyzing-api-gateway-access-logs`](skills/cybersecurity/analyzing-api-gateway-access-logs/SKILL.md) | 'Parses API Gateway access logs (AWS API Gateway, Kong, Nginx) to detect BOLA/IDOR attacks, rate lim... | [`skills/cybersecurity/analyzing-api-gateway-access-logs/SKILL.md`](skills/cybersecurity/analyzing-api-gateway-access-logs/SKILL.md) |
| [`analyzing-apt-group-with-mitre-navigator`](skills/cybersecurity/analyzing-apt-group-with-mitre-navigator/SKILL.md) | Query ATT&CK data with attackcti, mitreattack-python, and stix2, then build MITRE ATT&CK Navigator l... | [`skills/cybersecurity/analyzing-apt-group-with-mitre-navigator/SKILL.md`](skills/cybersecurity/analyzing-apt-group-with-mitre-navigator/SKILL.md) |
| [`analyzing-azure-activity-logs-for-threats`](skills/cybersecurity/analyzing-azure-activity-logs-for-threats/SKILL.md) | 'Queries Azure Monitor activity logs and sign-in logs via azure-monitor-query to detect suspicious a... | [`skills/cybersecurity/analyzing-azure-activity-logs-for-threats/SKILL.md`](skills/cybersecurity/analyzing-azure-activity-logs-for-threats/SKILL.md) |
| [`analyzing-bootkit-and-rootkit-samples`](skills/cybersecurity/analyzing-bootkit-and-rootkit-samples/SKILL.md) | 'Analyzes bootkit and advanced rootkit malware infecting the Master Boot Record (MBR), Volume Boot R... | [`skills/cybersecurity/analyzing-bootkit-and-rootkit-samples/SKILL.md`](skills/cybersecurity/analyzing-bootkit-and-rootkit-samples/SKILL.md) |

### 🎨 Design & UI/UX Standards
| Skill Name | Description | Path |
| :--- | :--- | :--- |
| [`gsap-core`](skills/design-and-ui/gsap-core/SKILL.md) | Official GSAP skill for the core API — gsap.to(), from(), fromTo(), easing, duration, stagger, defau... | [`skills/design-and-ui/gsap-core/SKILL.md`](skills/design-and-ui/gsap-core/SKILL.md) |
| [`gsap-frameworks`](skills/design-and-ui/gsap-frameworks/SKILL.md) | Official GSAP skill for Vue, Svelte, and other non-React frameworks — lifecycle, scoping selectors, ... | [`skills/design-and-ui/gsap-frameworks/SKILL.md`](skills/design-and-ui/gsap-frameworks/SKILL.md) |
| [`gsap-performance`](skills/design-and-ui/gsap-performance/SKILL.md) | Official GSAP skill for performance — prefer transforms, avoid layout thrashing, will-change, batchi... | [`skills/design-and-ui/gsap-performance/SKILL.md`](skills/design-and-ui/gsap-performance/SKILL.md) |
| [`gsap-plugins`](skills/design-and-ui/gsap-plugins/SKILL.md) | Official GSAP skill for GSAP plugins — registration, ScrollToPlugin, ScrollSmoother, Flip, Draggable... | [`skills/design-and-ui/gsap-plugins/SKILL.md`](skills/design-and-ui/gsap-plugins/SKILL.md) |
| [`gsap-react`](skills/design-and-ui/gsap-react/SKILL.md) | Official GSAP skill for React — useGSAP hook, refs, gsap.context(), cleanup. Use when the user wants... | [`skills/design-and-ui/gsap-react/SKILL.md`](skills/design-and-ui/gsap-react/SKILL.md) |
| [`gsap-scrolltrigger`](skills/design-and-ui/gsap-scrolltrigger/SKILL.md) | Official GSAP skill for ScrollTrigger — scroll-linked animations, pinning, scrub, triggers. Use when... | [`skills/design-and-ui/gsap-scrolltrigger/SKILL.md`](skills/design-and-ui/gsap-scrolltrigger/SKILL.md) |
| [`gsap-timeline`](skills/design-and-ui/gsap-timeline/SKILL.md) | Official GSAP skill for timelines — gsap.timeline(), position parameter, nesting, playback. Use when... | [`skills/design-and-ui/gsap-timeline/SKILL.md`](skills/design-and-ui/gsap-timeline/SKILL.md) |
| [`gsap-utils`](skills/design-and-ui/gsap-utils/SKILL.md) | Official GSAP skill for gsap.utils — clamp, mapRange, normalize, interpolate, random, snap, toArray,... | [`skills/design-and-ui/gsap-utils/SKILL.md`](skills/design-and-ui/gsap-utils/SKILL.md) |
| [`fix`](skills/design-and-ui/fix/SKILL.md) | Take a GitHub issue, an open PR, or a plan file from plans/ and drive it to a merge-ready PR — repro... | [`skills/design-and-ui/fix/SKILL.md`](skills/design-and-ui/fix/SKILL.md) |
| [`improve`](skills/design-and-ui/improve/SKILL.md) | Survey any codebase as a senior advisor and produce prioritized, self-contained implementation plans... | [`skills/design-and-ui/improve/SKILL.md`](skills/design-and-ui/improve/SKILL.md) |

### 💼 Corporate & Executive Workflows
| Skill Name | Description | Path |
| :--- | :--- | :--- |
| [`skill-creator`](skills/corporate/00-meta/skill-creator/SKILL.md) | "This skill provides guidance for creating effective skills." | [`skills/corporate/00-meta/skill-creator/SKILL.md`](skills/corporate/00-meta/skill-creator/SKILL.md) |
| [`board-meeting-prep`](skills/corporate/01-executive-leadership/board-meeting-prep/SKILL.md) | "Board meetings are critical touchpoints where executives report on business performance, seek direc... | [`skills/corporate/01-executive-leadership/board-meeting-prep/SKILL.md`](skills/corporate/01-executive-leadership/board-meeting-prep/SKILL.md) |
| [`change-management`](skills/corporate/01-executive-leadership/change-management/SKILL.md) | "Help plan and execute changes that affect people, processes, or technology." | [`skills/corporate/01-executive-leadership/change-management/SKILL.md`](skills/corporate/01-executive-leadership/change-management/SKILL.md) |
| [`competitive-analysis`](skills/corporate/01-executive-leadership/competitive-analysis/SKILL.md) | "When source files (Excel/CSV) are provided:" | [`skills/corporate/01-executive-leadership/competitive-analysis/SKILL.md`](skills/corporate/01-executive-leadership/competitive-analysis/SKILL.md) |
| [`deep-research`](skills/corporate/01-executive-leadership/deep-research/SKILL.md) | "Run autonomous research tasks that plan, search, read, and synthesize information into comprehensiv... | [`skills/corporate/01-executive-leadership/deep-research/SKILL.md`](skills/corporate/01-executive-leadership/deep-research/SKILL.md) |
| [`executive-communication`](skills/corporate/01-executive-leadership/executive-communication/SKILL.md) | "Executive communication is how leadership sets culture, builds trust, maintains alignment, and mana... | [`skills/corporate/01-executive-leadership/executive-communication/SKILL.md`](skills/corporate/01-executive-leadership/executive-communication/SKILL.md) |
| [`internal-comms`](skills/corporate/01-executive-leadership/internal-comms/SKILL.md) | "To write internal communications, use this skill for:" | [`skills/corporate/01-executive-leadership/internal-comms/SKILL.md`](skills/corporate/01-executive-leadership/internal-comms/SKILL.md) |
| [`knowledge-synthesis`](skills/corporate/01-executive-leadership/knowledge-synthesis/SKILL.md) | "The last mile of enterprise search. Takes raw results from multiple sources and produces a coherent... | [`skills/corporate/01-executive-leadership/knowledge-synthesis/SKILL.md`](skills/corporate/01-executive-leadership/knowledge-synthesis/SKILL.md) |
| [`kpi-dashboard`](skills/corporate/01-executive-leadership/kpi-dashboard/SKILL.md) | "Executive dashboards are the pulse of the organization—they provide real-time visibility into busin... | [`skills/corporate/01-executive-leadership/kpi-dashboard/SKILL.md`](skills/corporate/01-executive-leadership/kpi-dashboard/SKILL.md) |
| [`ma-due-diligence`](skills/corporate/01-executive-leadership/ma-due-diligence/SKILL.md) | "M&A transactions are among the highest-stakes decisions an executive makes. This skill enables you ... | [`skills/corporate/01-executive-leadership/ma-due-diligence/SKILL.md`](skills/corporate/01-executive-leadership/ma-due-diligence/SKILL.md) |

### 🛠️ Core Office & Productivity Tools
| Skill Name | Description | Path |
| :--- | :--- | :--- |
| [`notebooklm`](skills/core-tools/notebooklm/SKILL.md) | Use this skill to query your Google NotebookLM notebooks directly from Claude Code for source-ground... | [`skills/core-tools/notebooklm/SKILL.md`](skills/core-tools/notebooklm/SKILL.md) |
| [`algorithmic-art`](skills/core-tools/algorithmic-art/SKILL.md) | Creating algorithmic art using p5.js with seeded randomness and interactive parameter exploration. U... | [`skills/core-tools/algorithmic-art/SKILL.md`](skills/core-tools/algorithmic-art/SKILL.md) |
| [`brand-guidelines`](skills/core-tools/brand-guidelines/SKILL.md) | Applies Anthropic's official brand colors and typography to any sort of artifact that may benefit fr... | [`skills/core-tools/brand-guidelines/SKILL.md`](skills/core-tools/brand-guidelines/SKILL.md) |
| [`canvas-design`](skills/core-tools/canvas-design/SKILL.md) | Create beautiful visual art in .png and .pdf documents using design philosophy. You should use this ... | [`skills/core-tools/canvas-design/SKILL.md`](skills/core-tools/canvas-design/SKILL.md) |
| [`claude-api`](skills/core-tools/claude-api/SKILL.md) | \|- Reference for the Claude API / Anthropic SDK — model ids, pricing, params, streaming, tool use, M... | [`skills/core-tools/claude-api/SKILL.md`](skills/core-tools/claude-api/SKILL.md) |
| [`doc-coauthoring`](skills/core-tools/doc-coauthoring/SKILL.md) | Guide users through a structured workflow for co-authoring documentation. Use when user wants to wri... | [`skills/core-tools/doc-coauthoring/SKILL.md`](skills/core-tools/doc-coauthoring/SKILL.md) |
| [`docx`](skills/core-tools/docx/SKILL.md) | "Use this skill whenever the user wants to create, read, edit, or manipulate Word documents (.docx f... | [`skills/core-tools/docx/SKILL.md`](skills/core-tools/docx/SKILL.md) |
| [`frontend-design`](skills/core-tools/frontend-design/SKILL.md) | Guidance for distinctive, intentional visual design when building new UI or reshaping an existing on... | [`skills/core-tools/frontend-design/SKILL.md`](skills/core-tools/frontend-design/SKILL.md) |
| [`internal-comms`](skills/core-tools/internal-comms/SKILL.md) | A set of resources to help me write all kinds of internal communications, using the formats that my ... | [`skills/core-tools/internal-comms/SKILL.md`](skills/core-tools/internal-comms/SKILL.md) |
| [`mcp-builder`](skills/core-tools/mcp-builder/SKILL.md) | Guide for creating high-quality MCP (Model Context Protocol) servers that enable LLMs to interact wi... | [`skills/core-tools/mcp-builder/SKILL.md`](skills/core-tools/mcp-builder/SKILL.md) |
| [`pdf`](skills/core-tools/pdf/SKILL.md) | Use this skill whenever the user wants to do anything with PDF files. This includes reading or extra... | [`skills/core-tools/pdf/SKILL.md`](skills/core-tools/pdf/SKILL.md) |
| [`pptx`](skills/core-tools/pptx/SKILL.md) | "Use this skill any time a .pptx or .potx file is involved in any way — as input, output, or both. T... | [`skills/core-tools/pptx/SKILL.md`](skills/core-tools/pptx/SKILL.md) |
| [`skill-creator`](skills/core-tools/skill-creator/SKILL.md) | Create new skills, modify and improve existing skills, and measure skill performance. Use when users... | [`skills/core-tools/skill-creator/SKILL.md`](skills/core-tools/skill-creator/SKILL.md) |
| [`slack-gif-creator`](skills/core-tools/slack-gif-creator/SKILL.md) | Knowledge and utilities for creating animated GIFs optimized for Slack. Provides constraints, valida... | [`skills/core-tools/slack-gif-creator/SKILL.md`](skills/core-tools/slack-gif-creator/SKILL.md) |
| [`theme-factory`](skills/core-tools/theme-factory/SKILL.md) | Toolkit for styling artifacts with a theme. These artifacts can be slides, docs, reportings, HTML la... | [`skills/core-tools/theme-factory/SKILL.md`](skills/core-tools/theme-factory/SKILL.md) |
| [`web-artifacts-builder`](skills/core-tools/web-artifacts-builder/SKILL.md) | Suite of tools for creating elaborate, multi-component claude.ai HTML artifacts using modern fronten... | [`skills/core-tools/web-artifacts-builder/SKILL.md`](skills/core-tools/web-artifacts-builder/SKILL.md) |
| [`webapp-testing`](skills/core-tools/webapp-testing/SKILL.md) | Toolkit for interacting with and testing local web applications using Playwright. Supports verifying... | [`skills/core-tools/webapp-testing/SKILL.md`](skills/core-tools/webapp-testing/SKILL.md) |
| [`xlsx`](skills/core-tools/xlsx/SKILL.md) | "Use this skill any time a spreadsheet file is the primary input or output. This means any task wher... | [`skills/core-tools/xlsx/SKILL.md`](skills/core-tools/xlsx/SKILL.md) |
| [`template-skill`](skills/core-tools/template/SKILL.md) | Replace with description of the skill and when Claude should use it. | [`skills/core-tools/template/SKILL.md`](skills/core-tools/template/SKILL.md) |

---

## 📄 License

This library is open-sourced under the [MIT License](LICENSE).

© 2026 StalFe Cloud. Maintained by the StalFe AI Engineering team.
