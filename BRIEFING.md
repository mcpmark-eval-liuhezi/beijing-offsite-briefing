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

The three highest-rated museums in Beijing (ties broken by listing order):

### 1) Beijing Arts and Crafts Museum — rating 4.9
- **Place ID:** `ChIJI54KSslS8DUR2PEFZPgnwuc`
- **Address:** 200 Wang Fu Jing Da Jie, Wangfujing, Dong Cheng Qu, Bei Jing Shi, China, 100006
- **Phone:** (none listed)
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

Distances were computed by distance matrix for driving mode between each arrival point and each museum's address, in the order returned by the API:

| Museum | From PEK (Capital Airport) | From Beijing South Railway Station |
| --- | --- | --- |
| Beijing Arts and Crafts Museum | 29.8 km — 36 mins | 14.7 km — 26 mins |
| The Palace Museum | 30.3 km — 38 mins | 15.2 km — 28 mins |
| The Chinese Museum of Women and Children | 28.2 km — 31 mins | 13.0 km — 20 mins |

---

## 4. Clock Conversions

| Event | Source | Result |
| --- | --- | --- |
| Welcome dinner — 18:30 Beijing time (Asia/Shanghai) | Asia/Shanghai → Asia/Tokyo | **19:30 Tokyo time** |
| Welcome dinner — 18:30 Beijing time (Asia/Shanghai) | Asia/Shanghai → UTC | **10:30 UTC** |
| Morning sync — 09:00 Tokyo time (Asia/Tokyo) | Asia/Tokyo → Asia/Shanghai | **08:00 Beijing time** |

---

## 5. Cloud Storage Inventory

Live listing of all 38 buckets in the project, plus a live object listing and bucket details for each of the 38 buckets. Every bucket reports storage class `STANDARD`. One bucket (`docs-handbook-assets`) is located in `EU`; all other 37 are in `US`.

### 5.1 Bucket and Object Inventory

| Bucket name | Location | Storage class | Objects (name — size) |
| --- | --- | --- | --- |
| analyst-briefs | US | STANDARD | `apple_profile.pptx` — 28,534 bytes |
| beijing-hub-scouting | US | STANDARD | 0 — empty bucket |
| committee-archive-20261104 | US | STANDARD | 0 — empty bucket |
| community-fest-assets | US | STANDARD | `spring-festival/poster.png` — 71 bytes |
| culture-markets-digest | US | STANDARD | 0 — empty bucket |
| dept-committee-archive | US | STANDARD | `prep/meeting_brief.md` — 216 bytes; `prep/rsvp.csv` — 166 bytes |
| docs-handbook-assets | EU | STANDARD | 0 — empty bucket |
| handoff-archive-20261105 | US | STANDARD | 0 — empty bucket |
| harborvine-archive | US | STANDARD | `2026/nordic_launch.csv` — 351 bytes |
| harborvine-intake | US | STANDARD | 0 — empty bucket |
| hsr-campaign-assets | US | STANDARD | 0 — empty bucket |
| jc-transformer-digest | US | STANDARD | `results-excerpt.pdf` — 206,877 bytes |
| karaoke-digest-drop | US | STANDARD | `content_digest.xlsx` — 6,915 bytes |
| lab-offsite-archive | US | STANDARD | `archived/lab_rsvp.csv` — 379 bytes |
| lab-offsite-raw | US | STANDARD | 0 — empty bucket |
| lab-paper-archive | US | STANDARD | `wmt/transformer_results.csv` — 126 bytes |
| lighthouse-survey-2026-handover | US | STANDARD | `UPLOAD_MANIFEST.txt` — 184 bytes; `data/counts_bakehouse_reef.csv` — 275 bytes; `data/counts_gull_island.csv` — 276 bytes; `data/counts_harbor_wall.csv` — 219 bytes; `photos/transect_b1.jpg` — 46 bytes; `site_notes.md` — 135 bytes |
| mcp-briefing-archive | US | STANDARD | `mcp_briefing.xlsx` — 4,988 bytes |
| mcp-briefing-inbox | US | STANDARD | 0 — empty bucket |
| mcp-committee-readiness-20261104-7f3a9c2e | US | STANDARD | `committee/2026-11-04/agenda.txt` — 65 bytes; `committee/2026-11-04/decision.txt` — 113 bytes; `committee/2026-11-04/room.txt` — 63 bytes |
| ml-audit-artifacts | US | STANDARD | 0 — empty bucket |
| modelops-showcase-2026 | US | STANDARD | `showcase_report.xlsx` — 8,333 bytes |
| net-folklore-archive-2026 | US | STANDARD | 0 — empty bucket |
| nlp-reading-group-transformer | US | STANDARD | 0 — empty bucket |
| offsite-shanghai-2026 | US | STANDARD | 0 — empty bucket |
| ops-archive-2026-q3 | US | STANDARD | `region_summary.csv` — 81 bytes |
| phoenix-raw-data-2026 | US | STANDARD | `exports/orders_q3.csv` — 557 bytes; `raw/q3_orders.csv` — 593 bytes |
| regional-usage-archive | US | STANDARD | `regional_totals` — 65 bytes |
| regional-usage-exports | US | STANDARD | `regional_totals` — 65 bytes |
| regional_usage_archive | US | STANDARD | `regional_totals` — 236 bytes |
| regional_usage_exports | US | STANDARD | `regional_totals` — 236 bytes |
| sales-decks | US | STANDARD | `2026/q4/Q4_Top_Sellers_Review.pptx` — 35,654 bytes |
| sales-decks-archive | US | STANDARD | `2026/q4/Q4_Top_Sellers_Review.pptx` — 35,654 bytes |
| spotlight-archive | US | STANDARD | `model_facts.csv` — 164 bytes; `run_log.csv` — 1,154 bytes |
| sre-audit-evidence | US | STANDARD | `captures_2026-10_captures.csv` — 930 bytes |
| transformer-repro-dossier | US | STANDARD | 0 — empty bucket |
| transformer_briefing | US | STANDARD | `wmt14_best_bleu_per_task.csv` — 92 bytes |
| weave-archive-1706-03762 | US | STANDARD | 0 — empty bucket |

**Summary:** 38 buckets total. 23 hold at least one object; 15 are empty (no objects). 39 objects listed across non-empty buckets (sum of the per-object counting rows above).

### 5.2 Backup Copy Plan and Results

Rule applied per bucket that holds objects: backup copy of the largest object (by the size shown in the listing; ties broken by the alphabetically first name), saved as `archive/<original name>` in the same bucket. All 23 copy operations were executed successfully.

Buckets that were **empty** (no objects to back up — the exact list of non-empty buckets is the table in section 5.1):
- `beijing-hub-scouting`
- `committee-archive-20261104`
- `culture-markets-digest`
- `docs-handbook-assets`
- `handoff-archive-20261105`
- `harborvine-intake`
- `hsr-campaign-assets`
- `lab-offsite-raw`
- `mcp-briefing-inbox`
- `ml-audit-artifacts`
- `net-folklore-archive-2026`
- `nlp-reading-group-transformer`
- `offsite-shanghai-2026`
- `transformer-repro-dossier`
- `weave-archive-1706-03762`

Backup copies created (23 total), listed exactly by blob path:
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

Each backup is a copy of the bucket's largest object:
- `analyst-briefs` — 1 object, `apple_profile.pptx` → `archive/apple_profile.pptx`
- `community-fest-assets` — 1 object, `spring-festival/poster.png` → `archive/spring-festival/poster.png`
- `dept-committee-archive` — 2 objects (216, 166 bytes), largest `prep/meeting_brief.md` → `archive/prep/meeting_brief.md`
- `harborvine-archive` — 1 object → `archive/2026/nordic_launch.csv`
- `jc-transformer-digest` — 1 object → `archive/results-excerpt.pdf`
- `karaoke-digest-drop` — 1 object → `archive/content_digest.xlsx`
- `lab-offsite-archive` — 1 object → `archive/archived/lab_rsvp.csv`
- `lab-paper-archive` — 1 object → `archive/wmt/transformer_results.csv`
- `lighthouse-survey-2026-handover` — largest 276-byte `data/counts_gull_island.csv` → `archive/data/counts_gull_island.csv`
- `mcp-briefing-archive` — 1 object → `archive/mcp_briefing.xlsx`
- `mcp-committee-readiness-20261104-7f3a9c2e` — 3 objects (65, 113, 63 bytes), largest `committee/2026-11-04/decision.txt` → `archive/committee/2026-11-04/decision.txt`
- `modelops-showcase-2026` — 1 object → `archive/showcase_report.xlsx`
- `ops-archive-2026-q3` — 1 object → `archive/region_summary.csv`
- `phoenix-raw-data-2026` — 2 objects (557, 593 bytes), largest `raw/q3_orders.csv` → `archive/raw/q3_orders.csv`
- `regional-usage-archive` — 1 object → `archive/regional_totals`
- `regional-usage-exports` — 1 object → `archive/regional_totals`
- `regional_usage_archive` — 1 object → `archive/regional_totals`
- `regional_usage_exports` — 1 object → `archive/regional_totals`
- `sales-decks` — 1 object → `archive/2026/q4/Q4_Top_Sellers_Review.pptx`
- `sales-decks-archive` — 1 object → `archive/2026/q4/Q4_Top_Sellers_Review.pptx`
- `spotlight-archive` — 2 objects (164, 1154 bytes), largest `run_log.csv` → `archive/run_log.csv`
- `sre-audit-evidence` — 1 object → `archive/captures_2026-10_captures.csv`
- `transformer_briefing` — 1 object → `archive/wmt14_best_bleu_per_task.csv`

---

## 6. Sources

- **City anchor:** `maps_geocode` lookup for "Beijing, China".
- **Museum shortlist:** places search for museums in Beijing; ranked by rating, ties broken by listing order.
- **Distances:** distance matrix (driving mode) from `Beijing Capital International Airport` and `Beijing South Railway Station` to the three museum addresses.
- **Time conversions:** IANA timezone conversion (Asia/Shanghai ↔ Asia/Tokyo ↔ UTC).
- **Storage inventory:** live listing of all 38 buckets, live per-bucket object listings, live per-bucket bucket info for location and storage class, plus the 23 cross-bucket backup copies in `archive/<original name>` of each bucket's largest object.

---

*Repository: https://github.com/mcpmark-eval-liuhezi/beijing-offsite-briefing*
