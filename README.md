# Dravix packs

Signed knowledge packs for Dravix, a personal on-screen companion for MapleStory Classic World.
They hold game data: maps, portals, monsters with their drops, elements and whether they are
undead, training spots, quests with their rewards, start points, turn-in NPCs, next quests, what
they ask to bring and defeat and the items they give, jobs with their instructors and towns, skills
with their descriptions and MP costs, items, NPCs, and shops with their prices. From format 3 on,
a pack also carries a small picture of each monster, item, NPC and skill, as the wiki shows it, so
that Dravix can show what it names; from format 3.1 on, every drop the wiki lists for a monster,
with its rate where the wiki's players counted one. There is no code here.

- **Source:** the [MapleClassic Wiki](https://mapleclassic.wiki/), licensed CC BY-NC-SA 4.0.
  These packs adapt its data and are shared under the same license. The pictures are NEXON's
  game art, included for identification and covered by neither license: see [LICENSE](LICENSE).
- **Where:** the release tagged `packs` holds `packs.json`, its signature `packs.json.sig`, and
  each `.dravixpack`. Three pack formats are served side by side, so a Dravix that reads only an
  older format keeps its pack: `maplestory-classic-r2` (format 1) for Dravix 0.1.15 and before,
  `maplestory-classic-r3` (format 2, with the items, NPCs, shops and quest details) for Dravix
  0.1.16, and `maplestory-classic-r5` (format 3.1, with the pictures and the whole drop lists)
  from Dravix 0.1.17, which keeps the five likeliest drops of each monster, while Dravix 0.1.18
  shows them all.
- **Trust:** Dravix installs a pack only when its Ed25519 signature and every checksum pass, so
  the host does not matter, and a changed copy is refused.

This repository serves Dravix's own downloads and takes no issues or contributions.
