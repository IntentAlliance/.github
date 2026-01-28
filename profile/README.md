# Welcome to the Intent Alliance

<div align="center">
  <img width="512" height="256" alt="intentalliance_logo" src="https://github.com/user-attachments/assets/9f8bde99-87e8-4a56-ab7b-efdd43b9fd54" />
</div>

<div align="center">
    <strong>The Intent Alliance is a non-profit consortium dedicated to building the Open Intent Protocol (OIP).</strong>
</div>

## 🌍 Our Mission

**The Web is evolving from "Read/Write" to "Act".**

In the traditional web, users search for information. In the Agent Era, users express **Intents**, and AI Agents execute them.

The **Intent Alliance** is a non-profit consortium dedicated to building the infrastructure for this new era. We believe in a future where:
1.  **Privacy is Non-Negotiable:** Your intents and API keys stay on your device.
2.  **Open Standards:** No single company should control how Agents talk to users.
3.  **Fair Economy:** Developers and creators are fairly compensated for the capabilities they provide.

## 🏗️ The Ecosystem

We are building the full stack for the Agent Economy:

### 1. The Protocol: OIP (Open Intent Protocol)
> *The Standard Language of Agents.*

OIP is a JSON-based manifest standard (`oip.json`) that allows any web service to declare its capabilities to AI Agents.
* **Discovery:** How Agents find your service.
* **Execution:** How Agents call your API with user parameters.
* **Attribution:** How value distribution and affiliate commissions are tracked.

👉 **[Read the Spec](https://github.com/IntentAlliance/oip-spec)**

### 2. The Reference Client: Oipia
> *The Browser for the Agent Era.*

**Oipia** (Open Intent Protocol Intelligent Agent) is the first consumer interface built on OIP.
* **Local-First Architecture:** Uses on-device embedding models to route intents without sending user queries to the cloud.
* **Local Vault:** A secure, hardware-backed storage for your API keys (GitHub, OpenAI, Spotify, etc.). **Your keys never leave your phone.**
* **Super App Experience:** One interface to control thousands of services.

👉 **[View Oipia Client Code](https://github.com/IntentAlliance/oipia-client)**

## 🧩 Architecture

We champion a **"Local Brain, Global Hands"** architecture to protect user privacy while ensuring limitless capabilities.

<div align="center">
  <img width="2000" height="800" alt="flow" src="https://github.com/user-attachments/assets/9c8ddcca-c2a5-4ea2-a632-763b5f52eeba" />
</div>

## 🧰 Developer Toolkit

We believe that **every API deserves to be an Agent**. To make this happen, we provide official SDKs to help you adapt your existing services to OIP in minutes.

### 🚀 Core SDKs
* **Python:** [`oip-python`](#) (Coming Soon)
    * *Decorator-based:* Add `@oip_action` to your FastAPI/Flask routes to auto-generate `oip.json`.
* **Node.js / TypeScript:** [`@intentalliance/sdk`](#) (Coming Soon)
    * *Middleware:* Automatically serve the manifest and validate Oipia signatures in Express/NestJS.
* **Go:** [`go-oip`](#) (Coming Soon)
    * *Struct Tags:* Define intent capabilities directly in your Go structs.

### 🔐 Security & Auth
* **Oipia Connect:** Pre-built OAuth 2.0 adapters to securely handshake with the **Local Vault**.
* **Request Verifier:** Libraries to verify that incoming requests are signed by a legitimate Oipia Client.

### 🛠️ CLI & Debugger
* **`oip-cli`**:
    * `oip init`: Create a boilerplate OIP project.
    * `oip validate`: Lint your `oip.json` against the protocol schema.
    * `oip simulate "book a flight"`: Test how the **Local SLM (Small Language Model)** interprets your intent locally before publishing.


## 🚀 Our Core Initiatives

| Project | Description | Status |
| :--- | :--- | :--- |
| **[oip-spec](https://github.com/IntentAlliance/oip-spec)** | The official specification of Open Intent Protocol. | 🟢 Active |
| **[intent-kit-flutter](https://github.com/IntentAlliance/intent-kit-flutter)** | Reference SDK for mobile developers. | 🟡 In Dev |
| **[oipia-client](https://github.com/IntentAlliance/oipia-client)** | (Open Intent Protocol Intelligent Agent) is the first consumer interface built on OIP.| 🔵 Planning |

### 🌐 Join the Community

* **Website:** [intentalliance.org](https://intentalliance.org)
* **Protocol Docs:** [openintentprotocol.org](https://openintentprotocol.org)
* **Discord:** [Join Server](#)

---
*Built with ❤️ for the future of Human-AI Interaction.*
