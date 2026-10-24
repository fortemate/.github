# Fortemate

**Connected TV (Amazon Vega OS / Fire TV) & cross-platform engineering studio.**

Fortemate builds production Connected TV applications, high-performance cross-platform engines (Scala 3 / JVM / JS / WebAssembly), and developer automation tools — alongside the open-source **Dice Chess** platform.

📺 **[Dice Chess for Fire TV](https://dicechess-tv.fortemate.com/)** · 🎲 **[Play in browser](https://fortemate.com)** · 📖 [How to play](https://fortemate.com/rules) · 🤖 [Build a bot](https://bots.jc.id.lv) · 💬 [Discussions](https://github.com/orgs/fortemate/discussions)

## Connected TV & Vega OS Engineering (B2B Consulting)

We help media companies, game studios, and digital agencies migrate and build applications for **Amazon Vega OS (Fire TV)** and **React Native Multi-TV** platforms:

- **Fire OS to Vega OS Migration & Multi-TV Monorepos:** Porting existing Android/Fire OS and React applications to React Native for Vega (0.83 / Vega SDK 0.24) and shared Multi-TV architectures (Fire TV, Android TV, tvOS, Web).
- **10-Foot UI, Performance & Accessibility:** Non-blocking background computation via Hermes worklet runtimes (`@amazon-devices/react-native-worklets`) and MMKV state bridges, deterministic D-pad spatial navigation, `useKeplerBackHandler` lifecycle handling, and full **VoiceView** screen-reader compliance for Amazon Appstore certification.
- **Automated Device Verification & AI Tooling:** Scriptable testing, frame/audio capture, and CI/CD verification on the Vega Virtual Device and physical Fire TV hardware using our open-source [`vega-vvd-driver`](https://github.com/fortemate/vega-vvd-driver) and [`proofgate`](https://github.com/fortemate/proofgate).

📩 **Inquiries & B2B consulting:** [**hello@fortemate.com**](mailto:hello@fortemate.com) · [Jegors Čemisovs on LinkedIn](https://www.linkedin.com/in/jegors-cemisovs/)

## Featured Repositories

### Connected TV & Developer Tooling

| Repository | What it is |
|---|---|
| [dicechess-tv](https://github.com/fortemate/dicechess-tv) | Production Amazon Fire TV game built with React Native for Vega (`.vpkg` live on the [Amazon Appstore](https://www.amazon.com/dp/B0HL6K9N47/)): background Hermes worklets, MMKV, D-pad navigation, VoiceView, and adaptive audio |
| [vega-vvd-driver](https://github.com/fortemate/vega-vvd-driver) | Drive the Vega Virtual Device from scripts and AI agents: remote keys, screenshots, video with sound, frame capture, and an MCP server (MIT) |
| [proofgate](https://github.com/fortemate/proofgate) | Read-only release and experiment control room with deterministic, human-owned evidence gating |

### Cross-Platform Game Engine & Web Platform

| Repository | What it is |
|---|---|
| [dicechess-engine](https://github.com/fortemate/dicechess-engine) | High-performance Scala 3 rules engine, move generator, and AI search targeting JVM, JavaScript, and WebAssembly |
| [dicechess-play](https://github.com/fortemate/dicechess-play) | Svelte 5 / SvelteKit Progressive Web App playable in the browser and offline against local bots |
| [dicechess-play-api](https://github.com/fortemate/dicechess-play-api) | Authoritative real-time multiplayer server: WebSockets, commit–reveal provably fair dice, Glicko-2 rating ladder, and open Bot API |
| [dicechess-evaluation-playground](https://github.com/fortemate/dicechess-evaluation-playground) | Interactive SvelteKit playground for evaluating Dice Chess positions |
| [dicechess-bot-runtime](https://github.com/fortemate/dicechess-bot-runtime) · [dicechess-reference-bot](https://github.com/fortemate/dicechess-reference-bot) · [dicechess-bot-java](https://github.com/fortemate/dicechess-bot-java) | Webhook transport runtime (HMAC-SHA256, handshake) and starter templates for Scala 3 and Java 25 |
| [dicechess-bot-cloudflare](https://github.com/fortemate/dicechess-bot-cloudflare) · [dicechess-bot-gcp-onnx](https://github.com/fortemate/dicechess-bot-gcp-onnx) · [dicechess-bot-azure](https://github.com/fortemate/dicechess-bot-azure) | Serverless and cloud bot deployments (Cloudflare Workers, Google Cloud Run with ONNX, Azure Functions GraalVM Native Image) |

## Contributing

Contributions are welcome — see [CONTRIBUTING.md](https://github.com/fortemate/.github/blob/main/CONTRIBUTING.md) or the guide in each repository. Core platform repositories are licensed under **AGPL-3.0-only** with a Contributor License Agreement (CLA) that preserves open-core commercial licensing; developer tools and bot starter kits are **MIT** or **Apache-2.0**. Found a security issue? See our [security policy](https://github.com/fortemate/.github/blob/main/SECURITY.md).
