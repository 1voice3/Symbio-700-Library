# Symbio 700 Document Library — Coverage Notes

**Source:** Trane Support knowledge center — https://support.trane.com/hc/en-us (Zendesk-hosted)
**Collected:** October 18-19, 2026 (UTC)
**Scope:** Knowledge-base articles related to the **Symbio 700** unit controller, focused on **Precedent Symbio 700**, **Voyager Symbio 700**, and **Odyssey Symbio 700** units — including troubleshooting, airflow, compressor proving, VFD, wire pairing / wiring, bulletins / service alerts, firmware, and more.

## What is included

- **349 unique articles** — full text saved as offline HTML pages under `articles/`
- **1,910 attachment references** across those articles; **1,245 files saved** under `attachments/` (exact duplicate files were removed by content hash; the saved set includes the handful of inline-only images referenced by article bodies)
- **147 document-class attachment references** (PDF, PPTX, XLSX, DOCX, ZIP, TXT); file signatures were validated for every saved file (1,067 PNG, 37 JPEG, 1 GIF, 132 PDF, 7 OOXML/ZIP, 1 file in Trane's .xif format) — no HTML error pages saved as documents
- `manifest.csv` — full inventory (article ID, title, original URL, category/section, equipment tags, topic tags, dates, attachment count)
- `index.html` — searchable / filterable catalog (search box + equipment and topic filter chips)

## How the articles were found

The site's own search API was queried with **44 searches** covering: "symbio 700"; "precedent / voyager / odyssey symbio 700"; symbio 700 combined with airflow, compressor proving, compressor, VFD, variable frequency drive, wire pairing, wiring, troubleshooting, bulletin, service, alarm, fault, configuration, setup, startup, commissioning, firmware, installation, maintenance, BACnet, communication, sensor, economizer, RTU open, condenser fan, blower, EXV, defrost, dehumidification, discharge, network, tech tips, alert, APP, bluetooth, password; plus broad "precedent", "voyager", and "odyssey" sweeps.

This produced **1,163 search candidates**, each retrieved in full and then filtered. The library contains:

- every candidate whose title or body references Symbio 700;
- every article filed in the site's dedicated Symbio 700 sections;
- **35 additional articles** added after two follow-up passes: (a) following every internal article link from included articles and adding the relevant ones (e.g., Odyssey Symbio VFD parameters, wiring/startup and charging charts, Precedent Symbio ERM fault, Symbio communication wire, firmware update guide, Precedent/Odyssey IOM manual indexes), and (b) reviewing excluded candidates for equipment-tied Symbio titles (e.g., Symbio Precedent barometric relief damper manuals, drain pan removal, supply fan locations, low ambient control, Odyssey twinning/pairing examples, economizer actuator control).

Dedicated Symbio 700 sections swept in full:

- Symbio 700 (Light Commercial Rooftops / Splits)
- Symbio 700 (Equipment Literature / Apps Guides)
- Symbio 700 [LCU]
- Symbio 700 Precedent [LCU]
- Symbio 700 (Field Service Alerts / Known Product Issues)
- Resolved Symbio 700 Service Alerts
- V3 w/Symbio 700 controls (Large Commercial RTUs)

## Equipment / topic tagging

Each article was auto-tagged by scanning its title and body:

- **Equipment:** Precedent, Voyager, Odyssey, or General Symbio 700
- **Topics:** Airflow/Fans, Compressor/Compressor Proving, VFD/Drives, Wiring/Wire Pairing, Troubleshooting, Bulletins/Service Alerts, Firmware/Software, Sensors/Modules, Economizer/Ventilation, Communications/BACnet, Installation/Startup, Heating, Refrigeration/Charging, Dehumidification, Safety/Emergency Stop, Manuals/Literature

Tags are a best-effort filtering aid — confirm applicability to your specific unit before acting on any procedure.

## Known gaps / limitations

- **9 linked articles are login-restricted** on Trane's site (HTTP 401 to anonymous access) — they are linked from included articles but their content could not be retrieved.
- **One inline image is dead upstream** (HTTP 404 at Trane); that single image link is left pointing at the original URL.
- Articles about other controllers (Symbio 400/500/800, Reliatel, UCP, IntelliPak) are excluded unless they specifically mention Symbio 700.
- **Trane eLibrary links are kept as online links.** The Precedent/Odyssey/Foundation IOM index articles link to search queries on Trane's separate eLibrary site (elibrary.tranetechnologies.com), which hosts the full manuals; those manuals are outside this help center and are not downloaded.
- Links inside article bodies that point to other web resources are kept as online links, not downloaded.
- Content is a snapshot as of the collection date; use the "Original online" link on each page for the live version.

## File layout

```
Symbio-700-Library/
  index.html            <- start here (search + filters)
  articles/
    Precedent/          <- 127 articles
    Voyager/            <- 24 articles
    Odyssey/            <- 49 articles
    General/            <- 149 general Symbio 700 articles
  attachments/          <- 1,245 saved files (shared across all articles)
  manifest.csv         <- full inventory
  coverage.md           <- this file
```

Articles are filed under the first matching equipment folder (Precedent > Voyager > Odyssey); an article mentioning several families appears in one folder but keeps all of its equipment badges and can be found via the index filters. Attachments are shared in one folder because many files are referenced by multiple articles.
