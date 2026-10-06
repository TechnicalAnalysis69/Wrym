# Wyrmforge

A dark medieval launchpad for self-running coins on Solana. Every coin is bound to an animated mythical beast with its own AI mind, and every beast trades against **$WYRM**, so all liquidity flows back into one shared pool.

> **Status: front-end prototype.** Market numbers on the page are simulated. Summoning signs a free message with Phantom but does not create a token yet.

## What works now
- Animated site: dragon-eye hero, live chronicle feed, bestiary of 9 creature types, Wyrm Pool, ritual loop, tithes, dragonfire burn
- Phantom wallet: connect, auto-reconnect, account switching, disconnect, sign a summoning message
- Demo wallet for people without Phantom
- Works on desktop, tablet and phone

## Run it
Open `index.html` in a browser, or publish with GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).
Phantom only connects on a real `https://` site (like GitHub Pages), not from a local file.

## Config
In `index.html`, search for `const RPC=` and replace the public Solana RPC with your own (Helius, QuickNode) so wallet balances load.

## Roadmap to launch
1. Launch $WYRM
2. Create the Wyrmforge config on Meteora Dynamic Bonding Curve ($WYRM quote, 2M ascension, 100% LP locked)
3. Wire Summon to Jupiter swap + DBC create-and-buy
4. Metadata/image upload endpoint
5. Fee claim + 20% $WYRM burn job
6. Live on-chain data
7. Beast AI backend
8. Devnet testing, code review, multisig treasury, legal review
