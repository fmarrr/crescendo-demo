# Crescendo Kids 🎵

A music practice tracker for children. Kids log their daily practice sessions, a parent approves with one tap, and the child earns surprise emoji stamps and plays bonus mini-games to celebrate.

## What it does

Kids log a practice session — instrument and duration. A parent approves it with one tap. The child then opens a mystery reward box to reveal a surprise emoji stamp, and plays a bonus pixel mini-game to celebrate.

**Child view:** Log practice → earn stamps → progress along a journey map → collect emoji rewards → play bonus games

**Parent view:** Review & approve sessions → track history

## Key features

- **Onboarding** — child name, avatar (30+ choices), multi-instrument selection, parent setup
- **9 instruments** — Piano, Cello, Violin, Drums, Guitar, Trumpet, Flute, Clarinet, Recorder (+ more)
- **Mystery box rewards** — tap to reveal a randomly selected emoji from 100+ options with spinning animation
- **4 pixel mini-games** — Catch Stars, Pixel Pong, Snake, Dodge Comets — with on-screen d-pad controls
- **Journey map** — snake-path progress tracker with milestone celebrations every 10 stamps
- **XP & levelling** — earn XP per approved session, level up over time
- **100% local** — all data stored on device, no account needed, no server

## Tech

Single self-contained HTML file — no build step, no dependencies, no server. Open `index.html` in any browser or run as a Capacitor iOS app.

**iOS:** Capacitor · Bundle ID `com.crescendokids.app` · Deployment target iOS 16+

## Status

Heading to App Store submission. Kids category compliant — no third-party SDKs, no analytics, no external links, no in-app purchases. COPPA & UK GDPR compliant.

## Possible Features Next

- **Teacher / tutor integration** — allow music teachers to verify practice sessions and set weekly goals
- **Multi-child support** — family dashboard where parents manage multiple children from one place
- **Backend practice ledger + fintech rewards** — a possible future direction: record each approved practice session on a blockchain backend as a verifiable proof of effort, then integrate with a fintech/open banking layer so that hitting a milestone (e.g. 10 sessions approved) automatically triggers a real pocket money reward into the child's account. Keeps the fun of earning stamps while giving them real-world value — without any crypto exposure for the child.
