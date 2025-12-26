# Mana Pod
Licensed under the Mana Pod License (Philippine LGS Tournament Use). See LICENSE.

A lightweight tournament manager for pod-based events (great for MTG Commander-style pods). It supports admin workflows (games, rounds, pairings, timers, reporting) and player views (standings, stats, decks), plus a secondary display screen for live round status.

## Features
- Game/round management with multiple pairing methods
- Pod scoring with validation and lock controls
- Round timer with overtime tracking
- Reports: ranking, Top 20, alphabetical standing, pod records, game stats
- Player portal: My Games, My Stats, My Deck
- Secondary display screen for pods/timer/results

## Tech
- PHP (no framework)
- JSON file storage under `storage/`
- Bootstrap 5 UI

## Local setup (XAMPP)
1. Place the project in `C:\xampp\htdocs\pod-tournament`.
2. Start Apache in XAMPP.
3. Open `http://localhost/pod-tournament/public/`.

## Default test data
- Sample players can be seeded from **Admin → Players**.
- Test player password: `user123456` (created via **Admin → Players → Create Logins**).

## Notes
- Data is stored as JSON files in `storage/`.
- The secondary display is accessed via the Round view.

## Attribution (Required)
Please keep the in-app attribution intact:
- **“Mana Pod — Created by: BMS”**

Removing, hiding, or obscuring attribution/credit footers violates the license terms.

## License (Philippine LGS Tournament Use)
This project is released under the **Mana Pod License (Philippine LGS Tournament Use)** — it is **not** an open-source license.

### You MAY (with full compliance)
- Use Mana Pod for tournaments run by **Philippine Local Game Stores (LGS)**, whether tournaments are **free or paid**.
- Install and run Mana Pod on your own devices/servers for internal store operations.
- Modify the app **for internal use only** (no sharing of modified builds).

### You MAY NOT
- **Redistribute** the software in any form (source code, compiled builds, uploads to repositories, sharing installers, etc.), whether free or paid.
- Offer **services based on the application**, including hosted access/SaaS, paid setup/operation for third parties, or “tournament management as a service” where Mana Pod is part of the service value.
- Remove or alter copyright/credit notices or attribution footers.

For the full terms, see the `LICENSE` file.

## Support / Donations
If you find Mana Pod useful and would like me to create more free, helpful applications for the community, you can support my work through donations.

For donation details, please contact me at:
- **Email:** bobmathew.sunga@gmail.com

Or you may directly deposit any amount at:
- **GCash:** 09954510216

## Author
Bob Mathew Sunga (BMS)
