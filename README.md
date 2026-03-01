# AI-Assisted Development Simulator

**Watch AI build your startup in real-time.**

An interactive browser-based simulator that recreates the experience of AI-assisted software development — complete with animated code windows, a live terminal, synthwave music, achievement badges, and hidden easter eggs. Built by [Evolution Labs](https://www.evolutionlabs.dev).

**[Launch the Simulator](https://evolutionlabs-dev.github.io/ai-coding-simulator/)**

---

## What Is This?

This is a novelty web app that simulates what it looks like when an AI pair-programs with a human developer. Four code windows type out Python, JavaScript, SQL, and build logs simultaneously, personalized with your name, company, role, and zodiac sign. It's part demo, part toy, part conversation starter about AI-assisted development.

It was built entirely by Claude (Anthropic's AI) in collaboration with Evolution Labs.

## Features

- **Live Typing Animation** — Four code windows with realistic character-by-character typing, variable speed, and burst patterns
- **9 Color Themes** — Matrix, Cyberpunk, Ocean, Sunset, Evolution, plus 4 accessibility themes (Red-Green Safe, Blue-Yellow Safe, Monochrome, High Contrast)
- **Interactive Terminal** — 18+ commands including `hack`, `dance`, `cowsay`, `neofetch`, `deploy`, and `reset`
- **Achievement System** — 16 unlockable badges (Stylist, YOLO, Hacker, Speed Demon, Night Owl, etc.)
- **Synthwave Music** — Original ambient beat built from scratch with the Web Audio API (kick, hi-hat, bass, arpeggio, warm pad)
- **Zodiac Personalities** — Pick your sign for custom horoscopes, stat labels, and coding-themed fortunes
- **Deploy to Prod** — Countdown sequence with confetti and physics-based fireworks
- **Easter Eggs** — Long-press deploy, shake your phone, tap the CPU bar 5x, triple-tap the header, and more
- **Shareable Links** — All settings encode into URL parameters so you can share your personalized simulator
- **Full Customization** — Name, company, role, zodiac sign, favorite AI model
- **Mobile-First** — Horizontal swipe between code windows, touch-friendly controls, iOS-optimized
- **Keyboard Shortcuts** — T (theme), S (sound), R (rain), M (music), D (deploy), and more
- **Accessibility** — `prefers-reduced-motion` support, colorblind-safe themes, WCAG AAA high-contrast option
- **Persistent State** — Settings and achievements saved to localStorage

## Tech Stack

This is a **zero-dependency, single-file application**. No frameworks, no build tools, no bundler.

| Layer | Technology |
|-------|-----------|
| Structure | Semantic HTML5 |
| Styling | CSS3 with Custom Properties (theming), Flexbox, Grid, scroll-snap |
| Logic | Vanilla JavaScript (async/await typing engine) |
| Audio | Web Audio API (oscillators, filters, gain nodes, buffer sources) |
| Graphics | Canvas API (Matrix rain), CSS animations (confetti, fireworks, glitch effects) |
| Sensors | Device Motion API (shake detection with iOS permission handling) |
| Persistence | localStorage |
| Fonts | Google Fonts (JetBrains Mono, Inter) |
| Hosting | GitHub Pages |

## Quick Start

No install required. Just open the file:

```bash
git clone https://github.com/evolutionlabs-dev/ai-coding-simulator.git
open index.html
```

Or visit the [live demo](https://evolutionlabs-dev.github.io/ai-coding-simulator/).

### Personalize via URL

```
https://evolutionlabs-dev.github.io/ai-coding-simulator/?n=YourName&c=YourCompany&r=CTO&z=Scorpio&t=purple
```

| Param | Description | Example |
|-------|------------|---------|
| `n` | Your name | `n=Jane` |
| `c` | Company name | `c=Acme` |
| `r` | Role | `r=CTO` |
| `z` | Zodiac sign | `z=Scorpio` |
| `m` | AI model | `m=Claude` |
| `t` | Theme | `t=purple` |

## Terminal Commands

Swipe to the `> term` tab on mobile (or the 4th window on desktop) and type:

| Command | What It Does |
|---------|-------------|
| `help` | List all commands |
| `status` | System status report |
| `whoami` | Your identity |
| `fortune` | Zodiac-powered fortune |
| `hack` | Fullscreen glitch effect |
| `dance` | Confetti + color trip |
| `deploy` | Deploy to production |
| `cowsay` | ASCII cow wisdom |
| `neofetch` | System info |
| `matrix` | Enable Matrix rain |
| `overclock` | CPU overdrive mode |
| `selfdestruct` | ...just kidding |
| `reset` | Clear all achievements |
| `coffee` | Brew a cup |
| `uptime` | Session stats |
| `ping` | PONG! |
| `clear` | Clear terminal |

## Easter Eggs

There are several hidden interactions. Here are hints:

- Hold down the deploy button for a while
- Shake your phone
- Tap the CPU indicator rapidly
- Triple-tap the header
- Triple-tap the footer
- Try the Konami code on a keyboard

## About Evolution Labs

[Evolution Labs](https://www.evolutionlabs.dev) explores the intersection of AI and software development. This simulator is a playful demonstration of what AI-assisted development looks like — and a showcase for what can be built with AI as a collaborator rather than a replacement.

## License

MIT License. Free to use, fork, and modify — just keep the copyright notice and attribution to [Evolution Labs](https://www.evolutionlabs.dev). See [LICENSE](LICENSE) for details.
