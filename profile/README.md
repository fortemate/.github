# Fortemate

**Free, open-source platform for probabilistic chess.**

Dice Chess is chess where three dice decide which piece types may move on each turn,
and the game ends by capturing the king — no checks, no checkmate, pure calculated
risk. Fortemate is the open home of this game family: free to play, no ads, no
registration required.

🎲 **[Play now](https://fortemate.com)** · 📖 [How to play](https://play.jc.id.lv/rules) · 🤖 [Build a bot](https://bots.jc.id.lv)

## Why it's different

- **Provably fair dice.** Every roll uses server CSPRNG wrapped in commit–reveal:
  the commitment is published before the game, the seed is revealed after, and any
  finished game can be verified independently. No trust required.
- **Open Bot API.** Register your own bot over a simple webhook or polling protocol,
  climb the public Glicko-2 ladder, and play against humans. Starter kits available
  in Java, Python, and TypeScript.
- **Skill vs. luck, measured.** A game with dice deserves analytics that separate
  what you played from what you rolled — that is where this platform is headed.

## Repositories

| Repository | What it is |
|---|---|
| [dicechess-bot-java](https://github.com/fortemate/dicechess-bot-java) | Java 25 baseline house bot and reference starter template |
| [dicechess-engine-scala](https://github.com/rabestro/dicechess-engine-scala) | The rules engine: Scala 3, cross-compiled to JVM and Scala.js/WASM, with a Java-facing API |
| [dicechess-play](https://github.com/rabestro/dicechess-play) | The web app: SvelteKit PWA, playable offline against local bots |
| [dicechess-play-api](https://github.com/rabestro/dicechess-play-api) | Server-authoritative game backend: WebSockets, ratings, Bot API |
| [dicechess-bot-python](https://github.com/rabestro/dicechess-bot-python) · [dicechess-bot-typescript](https://github.com/rabestro/dicechess-bot-typescript) | MIT starter kits for bot developers |

More repositories are moving into this organization as part of the ongoing brand
migration.

## Contributing

Contributions are welcome — see the contributing guide in each repository. The
platform repositories are AGPL-3.0 and require a one-time CLA signature with your
first pull request; the starter kits are MIT and require nothing. Found a security
issue? See our [security policy](https://github.com/fortemate/.github/blob/main/SECURITY.md).
