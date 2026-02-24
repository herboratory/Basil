<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/logo.png">
    <source media="(prefers-color-scheme: light)" srcset="./assets/logo_dark.png">
    <img src="./assets/logo-dark.png" width="240" alt="Bassanite logo">
  </picture>
</p>

<h1 align="center">Bassanite</h1>

<p align="center">
  Privacy-first multi-format schema builder
</p>

[Bassinate](https://bassanite.dev) is a browser-based web app for creating, editing, and converting data schemas across multiple formats — all in one place.  
It is designed for developers who want **fast iteration**, **cross-tool consistency**, and **less friction** when working with schemas.

---

## ✨ Why Bassanite?

Schema definitions often get duplicated, rewritten, or drift out of sync across tools like JSON, JS Object, Zod, Yup, TypeScript, and Prisma. Bassanite enables developers to visually construct and transform data schemas across these formats.

Bassanite helps you:
- Define a schema **once**
- Convert it into the formats you need
- Iterate quickly without juggling multiple tools or files

No installs. No config files. All schema processing is performed locally within the browser. Just open the app and build.

---

## 🚀 Key Features

- **Multi-format schema builder**
- **Instant conversion** between formats
- **Live preview & editable content**
- **Guest / Pro access model**
- **Runs entirely in the browser**
- **No data lock-in**

---

## 🧩 Supported Formats

| Format | Build | Import | Export |
|------|------|--------|--------|
| JSON Schema | ✅ | ✅ | ✅ |
| JavaScript Object | ✅ | ✅ | ✅ |
| Zod | ✅ (Pro) | ✅ (Pro) | ✅ (Pro) |
| Yup | ✅ (Pro) | ✅ (Pro) | ✅ (Pro) |
| TypeScript | ✅ (Pro) | ✅ (Pro) | ✅ (Pro) |
| Prisma | ✅ (Pro) | ✅ (Pro) | ✅ (Pro) |

> **Guest users** can fully use JSON and JavaScript Object features.  
> **Pro users** unlock all formats and advanced conversions.

---

## 🧩 Field Type Support

| Field Type | JSON | JS Object | TypeScript | Zod | Yup | Prisma |
|-----------|------|-----------|------------|-----|-----|--------|
| String    | ✅   | ✅        | ✅         | ✅  | ✅  | ✅     |
| Number    | ✅   | ✅        | ✅         | ✅  | ✅  | ✅     |
| Boolean   | ✅   | ✅        | ✅         | ✅  | ✅  | ✅     |
| Date      | ⚠️   | ⚠️        | ✅         | ✅  | ✅  | ✅     |
| Object    | ✅   | ✅        | ✅         | ✅  | ✅  | ✅     |
| Array     | ✅   | ✅        | ✅         | ✅  | ✅  | ✅     |
| Enum      | ⚠️   | ⚠️        | ✅         | ✅  | ✅  | ✅     |

**Legend:**  
✅ Full support  ⚠️ Limited support

> **Note:**  
> Limited support means the field type is represented using a compatible or simplified structure rather than a native primitive (e.g. `Date` or `Enum` in JSON).


---

## 🔐 Pricing & Access
Bassanite is a web-based tool with a simple access model:

- **Free (Guest)**
  - JSON Schema
  - JavaScript Object Schema
  - Import / edit / export basic schemas

- **Pro**
  - Zod
  - Yup
  - TypeScript
  - Prisma
  - Advanced validation and export formats

Bassanite runs directly in the browser — no installation required.

> Pro access is available via a monthly subscription.

👉 For current pricing and subscription details, visit [here](https://bassanite.dev).

---

## 🌐 Live App

👉 [**Bassanite Web App**](https://bassanite.dev)

The web app itself is the product — no downloads or local setup required.

---

## 🧠 Design Philosophy

- **Schema-first**: One source of truth
- **Tool-agnostic**: Not locked to a single ecosystem
- **Minimal friction**: No setup, no downloads
- **Progressive access**: Free core, paid advanced features

Bassanite is intentionally focused — it does not try to replace your IDE or framework, only to remove friction around schemas.

---

## 🔒 Privacy & Data

- Bassanite runs primarily in the browser
- Your schemas remain yours
- No intentional inspection or reuse of user data
- You are responsible for backing up important schemas

See **Privacy & Terms** in the app for details.

---

## 🛠 Tech Stack

- HTML / Tailwind CSS
- Alpine.js
- Client-side schema generation
- Cloudflare Pages
- Firebase (auth & access control)
- Stripe (subscriptions)

---

## 📬 Contact

For support, feedback, or collaboration inquiries, feel free to contact through email. Contact information can be found in the website.

---

## 🧭 Project Status

Bassanite is actively developed and evolving.  
Feature requests and feedback are welcome, but the project intentionally prioritizes **clarity and stability over feature bloat**.

---

## 📄 License

Bassanite is proprietary software developed by **Herboratory**.  
All rights are reserved. No part of this software may be copied, modified, distributed, or used for commercial purposes without explicit written permission.

---

Built with care by [Herboratory](https://herboratory.ai) 🌿
