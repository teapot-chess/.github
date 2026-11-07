# The stars of Sagittarius

Software for running chess tournaments, from the first pairing to the last
printed result. Every program is named after a star in Sagittarius; a few of
them sit in the Teapot, which is where the name of this organization comes
from. Nobody asked the stars.

| | Program | What it does | Licence |
|---|---|---|---|
| <img src="marks/openpairings.svg" width="32" alt=""> | **[OpenPairings](https://pairings.cloud)** | The tournament manager: players, pairings, results, standings, FIDE rating reports. Runs on your PC or at [pairings.cloud](https://pairings.cloud). Manual: [pairings.cloud/help](https://pairings.cloud/help), changes: [pairings.cloud/changelog](https://pairings.cloud/changelog). | Hosted service, closed source |
| <img src="marks/ainalrami.svg" width="32" alt=""> | **[Ainalrami](https://github.com/teapot-chess/Ainalrami)** | The pairing engine underneath: the FIDE Dutch system (with Baku acceleration) and team Swiss, checked against hundreds of millions of reference pairings. | Ms-RSL (read-only reference source) |
| | **[OpenResults](https://openresults.cloud)** | The public results site: pairings, standings and crosstables for spectators, at [openresults.cloud](https://openresults.cloud). | Hosted service, closed source |
| <img src="marks/alnasl.svg" width="32" alt=""> | **[Alnasl](https://github.com/teapot-chess/Alnasl)** | Live boards: collects the moves from the electronic boards in the hall and shows them to the world. | FSL-1.1-ALv2 |
| <img src="marks/arkab.svg" width="32" alt=""> | **[Arkab](https://github.com/teapot-chess/Arkab)** | The hall bridge: reads the boards on site and sends them to Alnasl. | FSL-1.1-ALv2 |
| <img src="marks/polis.svg" width="32" alt=""> | **[Polis](https://github.com/teapot-chess/Polis)** | The print station: pairings and place cards come out of the hall printer the moment a round is published. | FSL-1.1-ALv2 |
| <img src="marks/nunki.svg" width="32" alt=""> | **[Nunki](https://github.com/teapot-chess/Nunki)** | The hall announcer: round countdown, and the pairings read aloud. | FSL-1.1-ALv2 |
| | **[Manubrium](https://github.com/teapot-chess/Manubrium)** | The arbiter's phone app for OpenPairings: run a tournament from the hall floor (iOS and Android). | FSL-1.1-ALv2 |
| <img src="marks/ascella.svg" width="32" alt=""> | **[Ascella](https://github.com/teapot-chess/Ascella)** | Installs, updates, starts and stops all of the above on one machine, so the arbiter doesn't have to. | FSL-1.1-ALv2 |

[alnasl-image](https://github.com/teapot-chess/alnasl-image) holds the signed
system-image releases for the Alnasl hall box.

FSL-1.1-ALv2 is the Functional Source License with an Apache 2.0 future
licence. Ms-RSL is the Microsoft Reference Source License: the source may be
read for reference only.

Windows, macOS (Apple Silicon) and Linux builds of the open programs are on
each program's Releases page.
