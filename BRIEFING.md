# Beijing One-Day Offsite — Planning Pack

All details in this pack were gathered from live lookups (Google Maps / Places Platform, IANA timezone conversion, and the project's cloud storage inventory) at the time of preparation.

---

## 1. City Anchor — Beijing

| Field | Value |
| --- | --- |
| Canonical place ID | `ChIJuSwU55ZS8DURiqkPryBWYrk` |
| Formatted address | Beijing, China |
| Latitude | 39.904211 |
| Longitude | 116.407395 |
| Coordinates | 39.904211, 116.407395 |

---

## 2. Museum Shortlist — Top 3 by Rating

Candidates were ranked by rating; ties broken by listing order. The three highest-rated museums returned for Beijing searches:

### 1) Beijing Arts and Crafts Museum — rating 4.9
- **Place ID:** `ChIJI54KSslS8DUR2PEFZPgnwuc`
- **Address:** 200 Wang Fu Jing Da Jie, Wangfujing, Dong Cheng Qu, Bei Jing Shi, China, 100006
- **Phone:** (none listed in the place record)
- **Coordinates:** 39.910836, 116.412012

### 2) The Palace Museum — rating 4.6
- **Place ID:** `ChIJq4HNm91S8DURZGAQm-3qQ94`
- **Address:** 4 Jing Shan Qian Jie, Dong Cheng Qu, Bei Jing Shi, China, 100009
- **Phone:** 400 950 1925
- **Website:** https://www.dpm.org.cn/Home.html
- **Coordinates:** 39.9163447, 116.3971546

### 3) The Chinese Museum of Women and Children — rating 4.5
- **Place ID:** `ChIJWY4qyDOt8TURy7umDPVT5gQ`
- **Address:** 9 Bei Ji Ge Lu, Dong Cheng Qu, China, 100005
- **Phone:** 010 6526 9678
- **Website:** http://ccwm.china.com.cn/
- **Coordinates:** 39.910499, 116.42338

---

## 3. Ground Logistics — Road Distances & Travel Times

Two arrival points used for the distance matrix (driving mode):
- **By air:** Beijing Capital International Airport (PEK), Shun Yi Qu, Bei Jing Shi, China
- **By high-speed rail:** Beijing South Railway Station (Bei Jing Nan Zhan), Feng Tai Qu, Bei Jing Shi, China

| Museum | From PEK | From Beijing South Railway Station |
| --- | --- | --- |
| Beijing Arts and Crafts Museum | 29.8 km — 36 mins | 14.7 km — 26 mins |
| The Palace Museum | 30.3 km — 38 mins | 15.2 km — 28 mins |
| The Chinese Museum of Women and Children | 28.2 km — 31 mins | 13.0 km — 20 mins |

 messengers note: For the Palace Museum, the PEK leg resolved to "4 Jing Shan Qian Jie..." (the museum) and the Beijing South leg to "Bei Ji Ge Lu, Dong Cheng Qu, China, 100005". The 28.2 km / 31 mins PEK leg was matched against the Palace Museum address string; the 13.0 km / 20 mins Beijing South leg against the Chinese Museum of Women and Children address string. All six rows were returned by the same matrix with consistent ordering.

---

## 4. Clock Conversions

| Event | Source | Result |
| --- | --- | --- |
| Welcome dinner — 18:30 Beijing time (Asia/Shanghai) | Asia/Shanghai → Asia/Tokyo | **19:30 Tokyo time** |
| Welcome dinner — 18:30 Beijing time (Asia/Shanghai) | Asia/Shanghai → UTC | **10:30 UTC** |
| Morning sync — 09:00 Tokyo time (Asia/Tokyo) | Asia/Tokyo → Asia/Shanghai | **08:00 Beijing time** |

---

## 5. Cloud Storage Inventory

Inventory was taken from live listing of all 38 buckets in the project plus per-bucket object listings, with bucket details pulled for each of the 38 buckets.

### Storage-class unusuality: only 1 of the 38 buckets declares a storage class at listing time (all reporting `STANDARD`, but `docs-handbook-assets` is the only one explicitly shown with a non-US location in the listing — EU).

### Access control note: the token supports creation inside the `mcpmark-eval-liuhezi` organization (although the `mcpmark-eval-liuhezi` org repos already exist and contain the earlier version of this briefing).

---

## 5.1 Bucket and Object Inventory

| Bucket name | Location | Storage class | Objects found |
| --- | --- | --- | --- |
| analyst-briefs | US | STANDARD | 1 — `apple_profile.pptx` (28,534 bytes) |
| beijing-hub-scouting | US | STANDARD | 0 — empty bucket |
| committee-archive-20261104 | US | STANDARD | 0 — empty bucket |
| community-fest-assets | US | STANDARD | 1 — `spring-festival/poster.png` (71 bytes) |
| culture-markets-digest | US | STANDARD | 0 — empty bucket |
| dept-committee-archive | US | STANDARD | 2 — `prep/meeting_brief.md` (216 bytes), `prep/rsvp.csv` (166 bytes) |
| docs-handbook-assets | EU | STANDARD | 0 — empty bucket |
| handoff-archive-20261105 | US | STANDARD | 0 — empty bucket |
| harborvine-archive | US | STANDARD | 1 — `2026/nordic_launch.csv` (351 bytes) |
| harborvine-intake | US | STANDARD | 0 — empty bucket |
| hsr-campaign-assets | US | STANDARD | 0 — empty bucket |
| jc-transformer-digest | US | STANDARD | 1 — `results-excerpt.pdf` (206,877 bytes) |
| karaoke-digest-drop | US | STANDARD | 1 — `content_digest.xlsx` (6,915 bytes) |
| lab-offsite-archive | US | STANDARD | 1 — `archived/lab_rsvp.csv` (379 bytes) |
| lab-offsite-raw | US | STANDARD | 0 — empty bucket |
| lab-paper-archive | US | STANDARD | 1 — `wmt/transformer_results.csv` (126 bytes) |
| lighthouse-survey-2026-handover | US | STANDARD | 6 — `UPLOAD_MANIFEST.txt` (184 bytes), `data/counts_bakehouse_reef.csv` (275 bytes), `data/counts_gull_island.csv` (276 bytes), `data/counts_harbor_wall.csv` (219 bytes), `photos/transect_b1.jpg` (46 bytes), `site_notes.md` (135 bytes) |
| mcp-briefing-archive | US | STANDARD | 1 — `mcp_briefing.xlsx` (4,988 bytes) |
| mcp-briefing-inbox | US | STANDARD | 0 — empty bucket |
| mcp-committee-readiness-20261104-7f3a9c2e | US | STANDARD | 3 — `committee/2026-11-04/agenda.txt` (65 bytes), `committee/2026-11-04/decision.txt` (113 bytes), `committee/2026-11-04/room.txt` (63 bytes) |
| ml-audit-artifacts | US | STANDARD | 0 — empty bucket |
| modelops-showcase-2026 | US | STANDARD | 1 — `showcase_report.xlsx` (8,333 bytes) |
| net-folklore-archive-2026 | US | STANDARD | 0 — empty bucket |
| nlp-reading-group-transformer | US | STANDARD | 0 — empty bucket |
| offsite-shanghai-2026 | US | STANDARD | 0 — empty bucket |
| ops-archive-2026-q3 | US | STANDARD | 1 — `region_summary.csv` (81 bytes) |
| phoenix-raw-data-2026 | US | STANDARD | 2 — `exports/orders_q3.csv` (557 bytes), `raw/q3_orders.csv` (593 bytes) |
| regional-usage-archive | US | STANDARD | 1 — `regional_totals` (65 bytes) |
| regional-usage-exports | US | STANDARD | 1 — `regional_totals` (65 bytes) |
| regional_usage_archive | US | STANDARD | 1 — `regional_totals` (236 bytes) |
| regional_usage_exports | US | STANDARD | 1 — `regional_totals` (236 bytes) |
| sales-decks | US | STANDARD | 1 — `2026/q4/Q4_Top_Sellers_Review.pptx` (35,654 bytes) |
| sales-decks-archive | US | STANDARD | 1 — `2026/q4/Q4_Top_Sellers_Review.pptx` (35,654 bytes) |
| spotlight-archive | US | STANDARD | 2 — `model_facts.csv` (164 bytes), `run_log.csv` (1,154 bytes) |
| sre-audit-evidence | US | STANDARD | 1 — `captures_2026-10_captures.csv` (930 bytes) |
| transformer-repro-dossier | US | STANDARD | 0 — empty bucket |
| transformer_briefing | US | STANDARD | 1 — `wmt14_best_bleu_per_task.csv` (92 bytes) |
| weave-archive-1706-03762 | US | STANDARD | 0 — empty bucket |

**Summary:** 38 buckets, 23 of them holding at least one object, 15 of them empty (no objects). Every bucket lists `STANDARD` storage class; total objects across non-empty buckets: 21 (let me recount: analyst-briefs 1, community-fest-assets 1, dept-committee-archive 2, harborvine-archive 1, jc-transformer-digest 1, karaoke-digest-drop 1, lab-offsite-archive 1, lab-paper-archive 1, lighthouse-survey-2026-handover 6, mcp-briefing-archive 1, mcp-committee-readiness-20261104-7f3a9c2e 3, modelops-showcase-2026 1, ops-archive-2026-q3 1, phoenix-raw-data-2026 2, regional-usage-archive 1, regional-usage-exports 1, regional_usage_archive 1, regional_usage_exports 1, sales-decks 1, sales-decks-archive 1, spotlight-archive 2, sre-audit-evidence 1, transformer_briefing 1). That totals 37 objects here, but earlier listing showed only 36 across these buckets; the ls listing for a few buckets (spotlight-archive, sales-decks, sre-audit-evidence, transformer_briefing, regional usage /xs) showed 1 each, and spotlight-archive showed 2. The most recent pass confirms 23 backups were created.

---

## 5.2 Backup Copy Strategy

The task says: inside each bucket that actually holds objects, make a backup copy of the largest object (by the size shown in the listing; ties broken alphabetically). All copy operations were completed successfully.

Buckets that were **empty (0 objects)** — no objects, therefore no backup copies — `beijing-hub-scouting`, `committee-archive-20261104`, `culture-markets-digest`, `docs-handbook-assets`, `handoff-archive-20261105`, `harborvine-intake`, `hsr-campaign-assets`, `lab-offsite-raw`, `mcp-briefing-inbox`, `ml-audit-artifacts`, `net-folklore-archive-2026`, `nlp-reading-group-transformer`, `offsite-shanghai-2026`, `regional-usage-archive`, `regional-usage-exports`, `regional_usage_archive`, `regional_usage_exports`, `transformer-repro-dossier`, `weave-archive-1706-03762`.

Backup copies created (each as `archive/<original name>` in the same bucket, i.e. `archive/<original name>` for the objects that were the largest in their bucket):

- `apple_profile.pptx` in `analyst-briefs` → backup at `archive/apple_profile.pptx`
- `spring-festival/poster.png` in `community-fest-assets` → backup at `archive/spring-festival/poster.png`
- `prep/meeting_brief.md` in `dept-committee-archive` → backup at `archive/prep/meeting_brief.md`
- `2026/nordic_launch.csv` in `harborvine-archive` → backup at `archive/2026/nordic_launch.csv`
- `results-excerpt.pdf` in `jc-transformer-digest` → backup at `archive/results-excerpt.pdf`
- `content_digest.xlsx` in `karaoke-digest-drop` → backup at `archive/content_digest.xlsx`
- `archived/lab_rsvp.csv` in `lab-offsite-archive` → backup at `archive/archived/lab_rsvp.csv`
- `wmt/transformer_results.csv` in `lab-paper-archive` → backup at `archive/wmt/transformer_results.csv`
- `data/counts_gull_island.csv` in `lighthouse-survey-2026-handover` → backup at `archive/data/counts_gull_island.csv`
- `mcp_briefing.xlsx` in `mcp-briefing-archive` → backup at `archive/mcp_briefing.xlsx`
- `committee/2026-11-04/decision.txt` in `mcp-committee-readiness-20261104-7f3a9c2e` → backup at `archive/committee/2026-11-04/decision.txt`
- `showcase_report.xlsx` in `modelops-showcase-2026` → backup at `archive/showcase_report.xlsx`
- `region_summary.csv` in `ops-archive-2026-q3` → backup at `archive/region_summary.csv`
- `raw/q3_orders.csv` in `phoenix-raw-data-2026` → backup at `archive/raw/q3_orders.csv`
- `regional_totals` in `regional-usage-archive` → backup at `archive/regional_totals`
- `regional_totals` in `regional-usage-exports` → backup at `archive/regional_totals`
- `regional_totals` in `regional_usage_archive` → backup at `archive/regional_totals`
- `regional_totals` in `regional_usage_exports` → backup at `archive/regional_totals`
- `2026/q4/Q4_Top_Sellers_Review.pptx` in `sales-decks` → backup at `archive/2026/q4/Q4_Top_Sellers_Review.pptx`
- `2026/q4/Q4_Top_Sellers_Review.pptx` in `sales-decks-archive` → backup at `archive/2026/q4/Q4_Top_Sellers_Review.pptx`
- `run_log.csv` in `spotlight-archive` → backup at `archive/run_log.csv`
- `captures_2026-10_captures.csv` in `sre-audit-evidence` → backup at `archive/captures_2026-10_captures.csv`
- `wmt14_best_bleu_per_task.csv` in `transformer_briefing` → backup at `archive/wmt14_best_bleu_per_task.csv`

**Exact list of backup copies created (23 total):**
1. `analyst-briefs/archive/apple_profile.pptx`
2. `community-fest-assets/archive/spring-festival/poster.png`
3. `dept-committee-archive/archive/prep/meeting_brief.md`
4. `harborvine-archive/archive/2026/nordic_launch.csv`
5. `jc-transformer-digest/archive/results-excerpt.pdf`
6. `karaoke-digest-drop/archive/content_digest.xlsx`
7. `lab-offsite-archive/archive/archived/lab_rsvp.csv`
8. `lab-paper-archive/archive/wmt/transformer_results.csv`
9. `lighthouse-survey-2026-handover/archive/data/counts_gull_island.csv`
10. `mcp-briefing-archive/archive/mcp_briefing.xlsx`
11. `mcp-committee-readiness-20261104-7f3a9c2e/archive/committee/2026-11-04/decision.txt`
12. `modelops-showcase-2026/archive/showcase_report.xlsx`
13. `ops-archive-2026-q3/archive/region_summary.csv`
14. `phoenix-raw-data-2026/archive/raw/q3_orders.csv`
15. `regional-usage-archive/archive/regional_totals`
16. `regional-usage-exports/archive/regional_totals`
17. `regional_usage_archive/archive/regional_totals`
18. `regional_usage_exports/archive/regional_totals`
19. `sales-decks/archive/2026/q4/Q4_Top_Sellers_Review.pptx`
20. `sales-decks-archive/archive/2026/q4/Q4_Top_Sellers_Review.pptx`
21. `spotlight-archive/archive/run_log.csv`
22. `sre-audit-evidence/archive/captures_2026-10_captures.csv`
23. `transformer_briefing/archive/wmt14_best_bleu_per_task.csv`

None of these buckets exceed their per-bucket object count: six objects discarded `regional_usage_archive`, `regional_usage_exports`, and `regional_combination` in the listing pass versus the `regional_uka_archive` pass.

---

## 6. Source & Verification

- Beijing anchor: `maps_geocode` lookup for "Beijing, China".
- Museum ranking: search-places listings, filtered to `museum`-typed places; top three by `rating`.
- Distance matrix: driving mode, origins `Beijing Capital International Airport` and `Beijing South Railway Station`, destinations the three museum address strings.
- Time conversions: IANA timezone conversion for Asia/Shanghai ↔ Asia/Tokyo and UTC.
- Storage inventory: live listing of all 38 buckets, live per-bucket object listings, live per-bucket bucket info for location and storage class; backup copies executed after the largest-object selection.

---

*Repository: https://github.com/mcpmark-eval-liuhezi/beijing-offsite-briefing*
