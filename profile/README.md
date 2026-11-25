<p align="center">
  <img src="https://raw.githubusercontent.com/EVtivity/evtivity-csms/main/assets/evtivity-logo.svg" alt="EVtivity" width="80" height="80" />
</p>

<h1 align="center">EVtivity</h1>

<h3 align="center">Freedom in EV Charging Management</h3>

<p align="center">
  An AI-powered, OCPP-compliant charging station management system.<br />
  Run your stations, sessions, drivers, billing and site power from one platform.
</p>

<p align="center">
  <a href="https://evtivity.com">Website</a> &middot;
  <a href="https://evtivity.com/docs/getting-started/introduction">Get Started</a> &middot;
  <a href="https://evtivity.com/api-reference">API Reference</a> &middot;
  <a href="https://github.com/EVtivity/evtivity-csms/releases">Releases</a> &middot;
  <a href="https://discord.gg/kKdJxFRksz">Discord</a>
</p>

---

### What EVtivity does

**OCPP 1.6, 2.0.1 and 2.1.** Every version at once, with handlers tested against the Open Charge Alliance OCTT conformance suite.

**Operator dashboard.** Stations, sessions, drivers, fleets, billing, reports and analytics in six languages, with live updates.

**AI assistant.** Ask about your network in plain language, attach a photo or a log, and confirm every change it proposes. Works with Anthropic, OpenAI, Google Gemini or DeepSeek.

**Load management.** Share site power across transformers, panels and circuits, per phase, with battery and solar supply and departure-aware fleet charging.

**Billing and payments.** Stripe and Adyen, time-of-day pricing, split billing, idle fees, guest charging and fleet invoicing.

**Plug and Charge and roaming.** ISO 15118 Plug and Charge, and OCPI 2.2.1 and 2.3.0 with CPO and eMSP roles.

**Drivers.** A web portal and a mobile app to find stations, start sessions, pay, and follow their charging.

**Deploy anywhere.** Docker Compose for development, a Helm chart with Istio or Envoy Gateway for Kubernetes, and AWS CDK for ECS Fargate.

### Projects

| Repository | What it is |
|---|---|
| [evtivity-csms](https://github.com/EVtivity/evtivity-csms) | The charging station management system: OCPP, OCPI and REST servers, operator dashboard and driver portal |
| [evtivity-mobile-app](https://github.com/EVtivity/evtivity-mobile-app) | The driver app for iOS and Android |
| [evtivity-csms-helm](https://github.com/EVtivity/evtivity-csms-helm) | Helm chart for Kubernetes |
| [evtivity-csms-cdk](https://github.com/EVtivity/evtivity-csms-cdk) | AWS CDK infrastructure: ECS Fargate, Aurora PostgreSQL, ElastiCache, ALB with WAF |
| [evtivity-skills](https://github.com/EVtivity/evtivity-skills) | Agent Skills that teach coding agents to set up, use and troubleshoot EVtivity |
| [evtivity-ev-tester](https://github.com/EVtivity/evtivity-ev-tester) | An open-source EV-side simulator for bench testing AC chargers and CSMS backends |
| [evtivity-iot-panel](https://github.com/EVtivity/evtivity-iot-panel) | A Wi-Fi touch-screen control panel for the CSMS on an ESP32-S3 |

### License

The CSMS is source available under the Business Source License 1.1. You may run it in production for free as a single operator, or for a single end customer. See [LICENSE.md](https://github.com/EVtivity/evtivity-csms/blob/main/LICENSE.md) for the full terms.
