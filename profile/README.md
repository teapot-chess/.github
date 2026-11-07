# The stars of Sagittarius

Software for running chess tournaments, from the first pairing to the last
printed result. Every program is named after a star in Sagittarius; a few of
them sit in the Teapot, which is where the name of this organization comes
from. Nobody asked the stars.

| | Program | What it does | Licence |
|---|---|---|---|
| <img src="marks/openpairings.svg" width="32" alt=""> | **[OpenPairings](https://pairings.cloud)** | The tournament manager: players, pairings, results, standings, FIDE rating reports. Runs on your PC or at [pairings.cloud](https://pairings.cloud). Manual: [pairings.cloud/help](https://pairings.cloud/help), changes: [pairings.cloud/changelog](https://pairings.cloud/changelog). | Closed source, hosted service |
| <img src="marks/ainalrami.svg" width="32" alt=""> | **[Ainalrami](https://github.com/teapot-chess/Ainalrami)** | The pairing engine underneath: the FIDE Dutch system (with Baku acceleration) and team Swiss, checked against hundreds of millions of reference pairings. | Ms-RSL (read-only reference source) |
| | **[OpenResults](https://openresults.cloud)** | The public results site: pairings, standings and crosstables for spectators, at [openresults.cloud](https://openresults.cloud). | Closed source, hosted service |
| <img src="marks/alnasl.svg" width="32" alt=""> | **[Alnasl](https://github.com/teapot-chess/Alnasl)** | Live boards: collects the moves from the electronic boards in the hall and shows them to the world. | Ms-RSL (reference source; our builds free to use) |
| <img src="marks/arkab.svg" width="32" alt=""> | **[Arkab](https://github.com/teapot-chess/Arkab)** | The hall bridge: reads the boards on site and sends them to Alnasl. | Ms-RSL (reference source; our builds free to use) |
| <img src="marks/polis.svg" width="32" alt=""> | **[Polis](https://github.com/teapot-chess/Polis)** | The print station: pairings and place cards come out of the hall printer the moment a round is published. | Ms-RSL (reference source; our builds free to use) |
| <img src="marks/nunki.svg" width="32" alt=""> | **[Nunki](https://github.com/teapot-chess/Nunki)** | The hall announcer: round countdown, and the pairings read aloud. | Ms-RSL (reference source; our builds free to use) |
| | **[Manubrium](https://github.com/teapot-chess/Manubrium)** | The arbiter's phone app for OpenPairings: run a tournament from the hall floor (iOS and Android). | Ms-RSL (reference source; our builds free to use) |
| <img src="marks/ascella.svg" width="32" alt=""> | **[Ascella](https://github.com/teapot-chess/Ascella)** | Installs, updates, starts and stops all of the above on one machine, so the arbiter doesn't have to. | Ms-RSL (reference source; our builds free to use) |

[alnasl-image](https://github.com/teapot-chess/alnasl-image) holds the signed
system-image releases for the Alnasl hall box.

Ms-RSL is the Microsoft Reference Source License: the source may be read for
reference only. For the hall programs, the Manubrium phone app and alnasl-image
(Ms-RSL, reference source; our builds free to use), the builds we publish
(downloads, app stores, the Pi image) may be used free of charge to run chess
events; that permission covers our builds, not builds you make yourself.
Ainalrami is read-only reference source, with no such permission. OpenPairings
and OpenResults are closed source and run as a hosted service.

Windows, macOS (Apple Silicon) and Linux builds of the open programs are on
each program's Releases page.
