# Yoshi Tribe Offline Archive

A preservation workspace for the **Yoshi Tribe**, its **EZBoard community**, **Yoshi Valley**, **Alzabo**, and related member sites.

This repository section is intended to preserve both recovered historical material and the research/navigation layer created to make that material usable offline. Recovered originals, reconstructed presentation, and known missing material are deliberately distinguished rather than presented as if they were all original files.

## Visual preview

[![Restored original Yoshi Tribe homepage](screenshots/original-homepage.jpg)](screenshots/original-homepage.jpg)

*Compressed GitHub preview made from the actual recovered/restored-site screenshot. See the [screenshot catalog](screenshots/README.md) for source/status details.*

## Archive at a glance

| Collection | Recovered / indexed |
|---|---:|
| News posts | 42 |
| Board posts | 187 |
| Board members | 14 |
| Board topics | 28 |
| Readable captures | 134 |
| Gallery images | 66 |
| Raw files | 357 |
| Source URLs | 2,348 |

## What the original offline workspace contains

The recovered archive landing page exposes a much larger preservation system than a single restored website. Its navigation includes **Search, Timeline, Gallery, News, Board, Members, Versions, Raw Files, Missing Materials, and Help**.

The archive also links directly to the restored original homepage, the Yoshi Valley companion site, the Alzabo archive, provenance documentation, a complete URL/source ledger, and SHA-256 checksums.

### Search
Searches recovered pages, message-board posts, news, members, and readable captures.

### Timeline
Provides a chronological route through recovered activity and captured site history.

### Gallery
Collects recovered media while retaining source/metadata information and placeholders for referenced images that could not be recovered.

### News archive
Provides the recovered news collection with filtering by author, year, and subject.

### EZBoard preservation
The offline workspace contains a board explorer plus a separate member browser, allowing preserved community material to be navigated by member, topic, year, and keyword.

### Site versions and captures
Recovered captures can be opened in sequence so historical versions and text differences can be studied rather than collapsing everything into a single modernized page.

### Missing-material research
The archive records referenced material that was not recovered and preserves the original URLs/recovery outcomes where available. Missing items remain explicitly marked instead of being silently replaced.

### Provenance and integrity
The source workspace includes provenance notes, a complete URL/source ledger, and a `SHA256SUMS.txt` manifest for integrity checking.

## Preservation labels

- **Recovered** — original bytes or text recovered from a historical source/capture.
- **Reconstructed** — new offline navigation, presentation, indexes, or research tooling created to make the archive usable.
- **Missing** — historically referenced material that was unavailable during recovery.

These labels are important: a reconstructed archive browser is not represented as an original Yoshi Tribe webpage.

## Known source files

Confirmed source material includes `archive-home.html`, `search.html`, `timeline.html`, `gallery.html`, `news-browser.html`, `raw-files.html`, `site-versions.html`, `captures.html`, `missing-materials.html`, `research-report.html`, `provenance.html`, `help.html`, `SHA256SUMS.txt`, and supporting JSON/CSS/data files.

See [`docs/ADDITIONAL-ARCHIVE-FILES.md`](docs/ADDITIONAL-ARCHIVE-FILES.md) and [`CONTENT-INVENTORY.md`](CONTENT-INVENTORY.md) for migration tracking.

## Screenshot gallery

The [`screenshots`](screenshots/README.md) directory tracks actual recovered captures and the remaining archive-interface capture queue. Screenshot entries identify whether they represent period/restored pages or reconstructed preservation tooling.

## Migration status

The archive documentation, landing-page work, and first verified visual capture are present in GitHub. The larger source collection remains a staged migration: files should be copied source-faithfully where possible instead of rebuilt from truncated search results.

Some generated builds report slightly different counts (for example gallery/raw-file totals). Those differences are retained as build/version evidence rather than silently normalized.

## Preservation goals

1. Preserve original historical material without silently rewriting it.
2. Keep provenance attached to recovered content.
3. Make large collections searchable and understandable.
4. Keep missing-material research visible for future recovery work.
5. Preserve checksums and source ledgers where possible.
6. Clearly separate original content from archive-created navigation and research.
7. Add screenshots of actual pages as visual documentation during migration.

---

**Project:** Yoshi Tribe Offline Archive  
**Repository:** Graalians-Archives  
**Purpose:** Historical preservation, research, indexing, and recovery documentation.