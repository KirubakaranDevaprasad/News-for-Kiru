# Kiru News Network 📡

My personal 24-hour news channel. It pulls global headlines into one broadcast-style screen and ranks them by what I care about, how much time I have, and how a story could affect me.

## What's on air
- **Breaking ticker, world clocks and an anchor desk** with the top story
- **Your briefing:** pick 5, 10, 20 or 30 minutes and get a playlist that fits
- **▶ Anchor mode:** a TV-style auto-advancing run through your briefing
- **✦ Surprise me:** a story from a beat you rarely read, plus an "on this day" moment
- **Today's wall:** one tile per beat with the 24h count, a 3-day trend, the top headline, and how much of it touches your life
- **Around the globe:** a live map and region counts; **Economy pulse:** GDP growth and forecast
- **Beats:** Geopolitics · War & Conflict · Elections (with US Election Day countdown) · US Government · Global Economy · Tech & Innovation · Big Tech · Science & Space · Medicine & Health · Aliens & the Unexplained · World Events
- **"Why it matters to you"** hints: wallet, work, travel, close to home, health, vote, investments

## How it learns
Interest levels per beat, plus what it observes: stories you open, how long you're away reading, what you linger on while scrolling, and 👍 / 👎. Reading-time estimates adapt to your actual pace. Everything stays in `localStorage`.

## Sources (free, no keys)
Wikipedia Current Events portal & featured feed · Federal Register API · Hacker News (Algolia) · Spaceflight News API · BBC News RSS · IMF WEO / World Bank. Refreshes every 15 minutes.

## v2: lighter, tech-first, impact lens
- Light studio theme. **Tech & Innovation** and **Tech Companies** lead, then **Geopolitics**
- Every story shows a short **headline** plus an **"In one line"** summary trimmed from the source
- **🔊 Read it to me:** your briefing is read aloud (browser speech), highlighting each item as it plays
- **Impact on you board:** High / Medium / Big picture, with lenses for visa & immigration, career & jobs, India connection, wallet, travel, close to home, health, people's lives, political decisions, war & security, environment, protests & unrest, government change, markets
- **Tech company radar:** OpenAI, Anthropic, Google, Microsoft, Apple, Nvidia, Meta, Amazon, Tesla, Salesforce, HubSpot, Infosys/TCS and more
- Feed views: **Headlines**, **Cards**, **Full**
- **✦ Surprise me:** a high-impact story, a hot tech pick, a beat you rarely read, and a moment from history, in anchor mode
