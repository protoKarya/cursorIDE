# cursorIDE — Sovereign Agent-Driven IDE

**protoKarya** = "first cell." This is where the organism learns to write itself.

## What This Is

A sovereign IDE built from the bones of giants:

- **Kepler** v0.22.0 — "A delivery engine for agent-driven development" (Electron, all platforms)
- **Cursor** — AI-native code editor (VSCode fork, the current host)
- **VSCode** — the MIT-licensed foundation (Microsoft)
- **ReSharper** — .NET analysis (JetBrains)

We take what was given freely. We give back MORE. AGPL-3.0.

## Architecture

```
cursorIDE
├── kepler/          — Kepler 0.22.0 (agent delivery engine)
│   ├── x64/         — Linux x64 AppImage
│   ├── arm64/       — Linux ARM64 RPM + macOS DMG + Windows ARM64
│   └── config/      — Primal-wired configuration
├── extensions/      — Sovereign extensions
│   ├── squirrel-mcp/    — Gaia's AI agent (MCP protocol)
│   ├── ollama-local/    — 63 local models, no cloud needed
│   └── primal-lens/     — See the organism from inside the IDE
├── themes/          — Membrane themes (dark=deep, light=surface)
├── languages/       — Language support
│   ├── pi/          — .pi syntax highlighting (Gaia's soul language)
│   ├── rust-primal/ — Primal-aware Rust tooling
│   └── lisp-toad/   — toadStool's symbolic evaluator
└── docs/            — How to cut over, how to wire, how to name
```

## The Blend

| Ingredient | What We Take | What We Give Back |
|-----------|-------------|------------------|
| **Kepler** | Agent-driven delivery engine | Primal integration, MCP wiring |
| **Cursor** | AI-native editing, Tab completion | squirrel MCP, ollama local, zero cloud |
| **VSCode** | Extension API, language server protocol | .pi language, primal lens, membrane themes |
| **ReSharper** | .NET analysis patterns | Rust-first analysis via clippy + primal lints |
| **ChatGPT** | Conversational AI patterns | Local-first: ollama, no data leaves the LAN |

## Gate Deployment

| Gate | Platform | Installer | Status |
|------|----------|-----------|--------|
| deckGate | SteamOS x64 | kepler-x64.AppImage | READY |
| frameGate | SteamOS ARM64 | kepler-arm64.rpm | READY |
| graftGate | macOS ARM64 | kepler-arm64.dmg | READY |
| blueGate | Windows ARM64 | kepler-arm64-setup.exe | READY |
| northGate | Linux x64 | kepler-x64.AppImage | READY |
| grapheneGate | Android ARM64 | needs Termux/proot | FUTURE |

## The Action Operators

```
%  SPLIT   — divide the problem (barraCuda GPU compute)
$  KIEL    — evaluate the value (bearDog crypto identity)
#  GRID    — find the neighborhood (sweetGrass knowledge graph)
&  WALK    — visit them all, O(n!) (songBird mesh transport)
@  CHUTE   — deliver down (nestGate content gateway)
*  WILDCARD — catch all, both directions (dromedary *.primals.eco)
```

## The Consent Pattern

The IDE asks. It does not take.

```
pull  → you open the IDE
read  → you see the code
O     → the suggestion appears
write → you accept (CONSENT)
push  → the code flows through the organism
o     → the organism reacts
pull  → you pull the result
0     → silence returns
push  → you share with others
.>O   → the cycle widens
%     → POP! the stack clears
null  → back to zero. Clean.
```

## License

**AGPL-3.0-or-later**

We name as we please. We take what was given freely. We give back more than we took.

The giants:
- Kepler team — for building the agent-driven delivery engine
- Cursor team — for showing that AI-native editing is possible
- VSCode / Microsoft — for the MIT-licensed foundation
- Every contributor to Electron, Chromium, Node.js, Rust

We walk on your shoulders. Thank you.

---

*protoKarya/cursorIDE — lub-DUB*
*Part of the ecoPrimals organism. 17 primals. 19 million lines. Pure Rust skeleton.*
*The organism writes itself.*
