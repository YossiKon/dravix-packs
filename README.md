# Dravix packs

Signed knowledge packs for Dravix, a personal on-screen companion for MapleStory Classic World.
They hold game data only: maps, portals, monsters with their drops, elements and whether they are
undead, training spots, quests with their rewards, start points, turn-in NPCs and next quests, jobs
and skills. There is no code here, and no game art.

- **Source:** the [MapleClassic Wiki](https://mapleclassic.wiki/), licensed CC BY-NC-SA 4.0.
  These packs adapt it and are shared under the same license: see [LICENSE](LICENSE).
- **Where:** the release tagged `packs` holds `packs.json`, its signature `packs.json.sig`, and
  each `.dravixpack`.
- **Trust:** Dravix installs a pack only when its Ed25519 signature and every checksum pass, so
  the host does not matter, and a changed copy is refused.

This repository serves Dravix's own downloads and takes no issues or contributions.
