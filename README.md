# VANTARA 2050

**[Play VANTARA 2050](https://arnefranz-del.github.io/vantara-2050/)**

The tide took the streets. Vantara built over them. Tonight, the old city is broadcasting again.

VANTARA 2050 is a browser-based 3D exploration game set in a waterfront megacity. Start at West Pier, walk the streets or glide across the delta, and tune in to six radio relays to hear what happened beneath the waterline. The city runs from a single self-contained HTML file.

## Play

Open the live link above, or download [index.html](https://raw.githubusercontent.com/arnefranz-del/vantara-2050/main/index.html) and open it in a current browser. WebGL 2 provides the full effects, and a Canvas renderer keeps the city playable on machines without it. The file works offline. The intro, interface, and radio logs are in German. Touch controls appear on touch devices.

| Control | Action |
| --- | --- |
| W A S D | Move |
| Mouse or drag the view | Look around |
| Shift / Space | Sprint / jump |
| F | Toggle glide mode |
| Space / C in glide mode | Ascend / descend |
| E | Read a nearby radio relay |
| M | Open the map, set a waypoint, or fast-travel |
| T | Cycle sunset, night, and morning |
| Esc | Release the mouse, skip the intro, or close a panel |

## The city

- **West Pier** · The arrival deck above the old shoreline.
- **The Halo** · A tidal power ring suspended over the delta.
- **Lotus Exchange** · A night market below the elevated transit line.
- **Sky Gardens** · Rooftop greenhouses and a seed bank.
- **Signal Spire** · A radio tower with a viewing platform.
- **Undertow** · The pump district and its abandoned ferries.

The city mesh, animated traffic, sky, water reflections, signage, and optional audio are generated in the browser. Discovered relays are saved locally when browser storage is available. There are no runtime libraries, network calls, or external assets.
