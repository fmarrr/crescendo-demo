# Crescendo - demo 🎵

A music practice tracker that rewards children with blockchain-based stamps and mini-games.

## What it does

Kids log their practice sessions — instrument and duration. A parent approves with one tap, which triggers a simulated on-chain transaction. The child then opens a mystery reward box to reveal a surprise emoji stamp, and plays a bonus pixel mini-game to celebrate.

**Child view:** Log practice → earn stamps → progress along a journey map → collect emoji rewards → play bonus games

**Parent view:** Review & approve sessions → watch the family wallet grow → see on-chain tx history

## Key features

- **Onboarding** — child name, avatar (30+ choices), multi-instrument selection, parent setup
- **Mystery box rewards** — tap to reveal a randomly selected emoji from 100+ options with spinning animation
- **4 pixel mini-games** — Catch Stars, Pixel Pong, Snake, Dodge Comets — with on-screen d-pad controls
- **Journey map** — snake-path progress tracker with milestone celebrations at stamps 3, 6, 10, 12
- **XP & levelling** — earn XP per practice session, level up over time
- **Blockchain simulation** — simulated ERC-1155 minting on Base Sepolia with fake tx hashes and wallet display

## Tech

This prototype is a single self-contained HTML file — no build step, no dependencies, no server. Just open `index.html`.

**Production target stack:** Next.js 14 · Privy · Base L2 · ERC-1155 · Supabase · Vercel

## Status

Prototype for UX testing. No real transactions, cryptocurrency, or personal data is involved. All blockchain interactions are simulated on Base Sepolia test network.

## Possible Features Next

- **Real Base mainnet deployment** — move from Sepolia testnet to Base mainnet with Privy embedded wallets and actual ERC-1155 minting
- **Token → pocket money** — explore letting children redeem minted stamps for real pocket money, either via parent-set exchange rates or automated allowance top-ups triggered on-chain
- **Tradeable collectibles** — stamps as tradeable NFTs that kids can swap with friends or showcase in a public profile
- **Teacher / tutor integration** — allow music teachers to verify practice and set weekly goals directly in the app
- **Multi-child support** — family dashboard where parents manage multiple children's journeys from one wallet
- **Other reward utility** — yet to be discovered; the on-chain stamps are composable primitives that could unlock future use cases (merch discounts, concert ticket access, scholarship portfolios, etc.)
