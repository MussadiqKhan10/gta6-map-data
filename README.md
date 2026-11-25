# GTA 6 Map Data: Leonida Locations, Secrets and Vehicles

Open data for the **GTA 6 map of Leonida**: 109 pinned locations from Grand Theft Auto VI (secrets, Easter eggs, vehicles, collectibles, landmarks, businesses and the six regions), as used on the [Leonida Players interactive GTA 6 map](https://leonidaplayers.com/map).

Each pin links to a full guide page on [Leonida Players](https://leonidaplayers.com), the GTA 6 answer engine built by players.

## What's inside

| File | Format |
|---|---|
| `data/pins.json` | Array of pins (title, category, region, x, y, precision, url) |
| `data/pins.csv` | The same data as a spreadsheet |

| Category | Pins |
|---|---|
| Secrets and Easter eggs | 51 |
| Vehicles | 22 |
| Collectibles | 9 |
| Landmarks | 9 |
| Regions | 6 |
| Businesses | 6 |
| Activities | 6 |

## The six regions of Leonida

Vice City, Leonida Keys, Grassrivers, Port Gellhorn, Ambrosia and Mount Kalaga. Each has its own page in the [GTA 6 wiki](https://leonidaplayers.com/wiki).

## Coordinates

`x` and `y` run from 0 to 1000 across the width and height of Rockstar's official printable map of Leonida (0,0 is the top-left corner).

`precision` says how exact a pin is:

- `exact`: the spot itself
- `approximate`: within a short drive
- `region`: placed in the right region, see the linked page for the exact route

## Example

```json
{
  "title": "Allied Crystal sugar refinery",
  "category": "business",
  "region": "ambrosia",
  "x": 549,
  "y": 374,
  "precision": "approximate",
  "url": "https://leonidaplayers.com/wiki/businesses/allied-crystal-sugar-refinery"
}
```

## Updates

New pins are added as players find new things in Leonida. The live, always up-to-date version is the [interactive map](https://leonidaplayers.com/map), and players can submit their own finds there.

Popular guides: [GTA 6 cheats and cheat codes](https://leonidaplayers.com/guides/gta-6-cheat-codes-guide-how-to-unlock-and-enter-cheats-on-ps5-and-xbox) · [GTA 6 Easter eggs and secrets](https://leonidaplayers.com/guides/gta-6-easter-eggs-and-secrets-every-one-found)

## License

The data is free to use under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please credit "Leonida Players (leonidaplayers.com)" with a link.

Grand Theft Auto VI, Leonida and all related names are trademarks of Take-Two Interactive and Rockstar Games. This is an unofficial fan project and is not affiliated with or endorsed by Rockstar Games.
