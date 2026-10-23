# Dravix packs

Signed knowledge packs for Dravix, a personal on-screen companion for MapleStory Classic World.
They hold game data: maps, portals, monsters with their drops, elements and whether they are
undead, training spots, quests with their rewards, start points, turn-in NPCs, next quests, what
they ask to bring and defeat and the items they give, jobs with their instructors and towns, skills
with their descriptions and MP costs, items, NPCs, and shops with their prices. From format 3 on,
a pack also carries a small picture of each monster, item, NPC and skill, as the wiki shows it, so
that Dravix can show what it names; from format 3.1 on, every drop the wiki lists for a monster,
with its rate where the wiki's players counted one; from format 3.2 on, after the wiki's rows, the
items the GMS v83 drop table of HeavenMS lists for the monster, names only, marked as that table's.
There is no code here.

- **Source:** the [MapleClassic Wiki](https://mapleclassic.wiki/), licensed CC BY-NC-SA 4.0.
  These packs adapt its data and are shared under the same license. The GMS v83 drop rows are a
  separate work derived from [HeavenMS](https://github.com/ronancpl/HeavenMS)'s `sql/db_drops.sql`,
  licensed AGPL-3.0 and shared under the same license: its source form is
  [gms-v83-drops.json](gms-v83-drops.json), the table's rows matched by name to the wiki's
  monsters and items and reviewed, and the license text is in [AGPL-3.0.txt](AGPL-3.0.txt). The
  pictures are NEXON's game art, included for identification and covered by none of these
  licenses: see [LICENSE](LICENSE).
- **Where:** the release tagged `packs` holds `packs.json`, its signature `packs.json.sig`, and
  each `.dravixpack`. Three pack formats are served side by side, so a Dravix that reads only an
  older format keeps its pack: `maplestory-classic-r2` (format 1) for Dravix 0.1.15 and before,
  `maplestory-classic-r3` (format 2, with the items, NPCs, shops and quest details) for Dravix
  0.1.16, and `maplestory-classic-r7` (format 3.2, with the pictures, the whole drop lists and the
  GMS v83 rows, from the wiki of 2026-10-23) from Dravix 0.1.17, which keeps the five likeliest
  drops of each monster, while Dravix 0.1.18 shows them all, the GMS v83 rows under their own
  heading.
- **Trust:** Dravix installs a pack only when its Ed25519 signature and every checksum pass, so
  the host does not matter, and a changed copy is refused.

This repository serves Dravix's own downloads and takes no issues or contributions.
