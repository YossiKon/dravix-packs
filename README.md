# Dravix packs

Signed knowledge packs for Dravix, a personal on-screen companion for MapleStory Classic World.
They hold game data only: maps, portals, monsters with their drops, elements and whether they are
undead, training spots, quests with their rewards, start points, turn-in NPCs, next quests, what
they ask to bring and defeat and the items they give, jobs with their instructors and towns, skills
with their descriptions and MP costs, items, NPCs, and shops with their prices. There is no code
here, and no game art.

- **Source:** the [MapleClassic Wiki](https://mapleclassic.wiki/), licensed CC BY-NC-SA 4.0.
  These packs adapt it and are shared under the same license: see [LICENSE](LICENSE).
- **Where:** the release tagged `packs` holds `packs.json`, its signature `packs.json.sig`, and
  each `.dravixpack`. Two pack formats are served side by side, so a Dravix that reads only the
  older format keeps its pack: `maplestory-classic-r2` (format 1) for Dravix 0.1.15 and before,
  and `maplestory-classic-r3` (format 2, with the items, NPCs, shops and quest details) from
  Dravix 0.1.16.
- **Trust:** Dravix installs a pack only when its Ed25519 signature and every checksum pass, so
  the host does not matter, and a changed copy is refused.

This repository serves Dravix's own downloads and takes no issues or contributions.
