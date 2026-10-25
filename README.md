<div align="center">

<br>

[![SikuliX](https://raw.githubusercontent.com/oculix-org/SikuliX1/master/Support/sikulix-red.png)](https://github.com/oculix-org/Oculix)

<br>

# SikuliX1

### *Historical SikuliX1 codebase — mirrored under oculix-org.*

<br>

![Status](https://img.shields.io/badge/status-archived%20mirror-555?style=for-the-badge)
![Active fork](https://img.shields.io/badge/active%20fork-OculiX-1f883d?style=for-the-badge&logo=github)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge)

</div>

---

## 🎯 Where you probably want to go

| You want to… | Go to |
|---|---|
| **Use SikuliX today** | 👉 **[oculix-org/Oculix](https://github.com/oculix-org/Oculix)** — the active successor. Java 17+, current releases on the [releases page](https://github.com/oculix-org/Oculix/releases). |
| **Report a bug or request a feature** | 👉 **[oculix-org/Oculix/issues](https://github.com/oculix-org/Oculix/issues)** |
| **Read the public documentation** | 👉 **[docs.oculix.org](https://docs.oculix.org)** |
| **See RaiMan's original upstream** | 👉 [RaiMan/SikuliX1](https://github.com/RaiMan/SikuliX1) — archived March 2026 by its creator |
| **Browse the legacy SikuliX1 code** | You're here. Read-only mirror, frozen at SikuliX 2.0.5. |

---

## What is SikuliX (briefly)

SikuliX uses **computer vision** ([OpenCV](https://opencv.org/)) to identify and interact with anything visible on a screen — Windows, macOS, Linux. It locates GUI elements through image recognition, then drives them with simulated mouse and keyboard input. No access to source code, DOM, or accessibility APIs required.

The original motto, still valid : *"If you can see it, you can automate it."*

For the modern continuation with OpenCV 4.x (via Apertix), Java 17+, working VNC stack, Android ADB, PaddleOCR option, an MCP server and 22 native-reviewed locales → **[oculix-org/Oculix](https://github.com/oculix-org/Oculix)**.

Migrating from SikuliX ? Same API, new coordinates :

```xml
<!-- before -->
<groupId>com.sikulix</groupId>
<artifactId>sikulixapi</artifactId>

<!-- after -->
<groupId>io.github.oculix-org</groupId>
<artifactId>oculixapi</artifactId>
```

---

## 🙏 Heritage

A 23-year lineage of MIT-licensed open work :

- **2003 · MIT CSAIL** — Rob Miller's UI Design Group launches the visual automation research project that would become Sikuli.
- **2009 · UIST paper** — [**@doubleshow**](https://github.com/doubleshow) (Tom Yeh) and [**@vgod**](https://github.com/vgod) (Tsung-Hsiang Chang) formally introduce Sikuli at the ACM Symposium on User Interface Software and Technology. The codebase eventually lands under the [sikuli](https://github.com/sikuli) GitHub organization.
- **2010–2026 · SikuliX1** — [**@RaiMan**](https://github.com/RaiMan) (Raimund Hocke) takes over as sole maintainer, evolving the project through Java 8 → 11, multi-platform fixes, OCR integration, and sixteen years of patient stewardship, up to the final SikuliX 2.0.5.
- **March 2026 · oculix-org** — RaiMan archives the upstream and transmits stewardship; active development continues as **OculiX**.

Massive gratitude to all four — without them, this project simply doesn't exist. The MIT license they chose 23 years ago is still in place today, and that's not an accident.

---

<div align="center">
<sub>MIT-licensed. The torch is carried forward at <a href="https://github.com/oculix-org/Oculix">oculix-org/Oculix</a>.</sub>
</div>
