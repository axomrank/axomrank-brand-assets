# AxomRank Brand Assets: brand kit, illustrations and social media library

> AxomRank brand kit (logos, colours, fonts, templates), 36 master illustrations, social media carousels, campaign plans and asset-rights records.

[Part of AxomRank](https://github.com/axomrank)

## At a glance

- **Brand kit v1:** logos, wordmarks, colour tokens (maroon `#80151A`, ivory `#F7F2EC`, gold `#A77B37`), Noto Sans and Noto Sans Bengali, and English/Assamese social templates
- **36 master illustrations** with a searchable gallery
- **Instagram carousels, reel scripts** and the content strategy
- **Rights records:** permissions, clearance and consent templates for every asset

## Quick start

```bash
python3 scripts/validate_library.py
```

## Overview

AxomRank is currently a learning app. Its wider ambition is a trusted starting point for information about Assam: learning, education opportunities, places, culture and everyday information. This repository stores the brand assets, editorial plans, research references and production records supporting that journey. Expanded services in the roadmap are proposals, not launched capabilities.

## Start here

- [36-master illustration collection](illustrations/collection-v1/README.md): Assam learning scenes, regional concepts, livelihoods, history reconstructions and campaign backgrounds, with a searchable gallery and editable concept diagrams.
- [Proprietor, about/contact copy and FAQ](docs/about-contact/ABOUT_AND_CONTACT.md): Angsuman Das, sole proprietor, with supplied public contacts.
- [Asset rights and contributor records](rights/README.md): inventoried permissions, editable clearance records and consent templates.

- [Developed brand kit v1](brand-kit/v1/README.md): source-traced logos, wordmark lockups, tokens, fonts and editable English/Assamese social templates.

- [Brand foundation and expansion](docs/brand/BRAND_FOUNDATION.md): present positioning, proposed wider identity, voice and visual authority.
- [Development roadmap](docs/strategy/DEVELOPMENT_ROADMAP.md): phased work, responsible roles, dependencies and completion gates.
- [Assets still required](docs/strategy/ASSET_REQUIREMENTS.md): prioritised AI illustrations, real media, maps, templates, audio and information records.
- [Organised asset catalog](catalog/README.md): existing campaigns and references, plus the imported project.
- [Publication workflow](docs/operations/CONTENT_WORKFLOW.md): evidence, language review, rights, corrections and expiration.
- [Project import report](docs/operations/PROJECT_IMPORT.md): all available files, checksums and known missing assets.

## Repository map

| Location | Purpose |
|---|---|
| `docs/brand/` | Current interpretation and proposed broader positioning |
| `docs/strategy/` | Development roadmap and production requirements |
| `docs/operations/` | Import, review and maintenance procedures |
| `catalog/` | Searchable legacy inventory and project provenance |
| `templates/` | Content briefs, notices and metadata examples |
| `projects/ahom-history/` | All 163 available original project files, with their internal layout preserved |
| `outputs/` | Existing carousel exports, plans, reel scripts and research references |
| `AI_AHOM/` | Existing historical illustration collection |
| `style_work/`, `reel_work/` | Existing campaign production code and design references |
| Root DOCX guides and heritage artwork | Original brand authorities and supplied marks |

Existing assets retain their paths so campaign references and production scripts continue to resolve. New strategy, operations, templates and project material have dedicated folders. Use the catalog to navigate legacy content; do not infer that an export or a draft is approved simply because it is present.

## Current brand rules

Use AxomRank in prose, maroon/ivory colours, the supplied Rang Ghar artwork and the applicable supplied gold insignia. [Later carousel decisions](CAROUSEL_PREFERENCES.md) supersede the original guide where relevant: finished cards are square 1:1, with aesthetic 3D treatment and no gamosa/textile borders. Preserve historical delivered campaigns unless a revision is requested. Keep internal evidence records even where sources are omitted from finished cards/captions.

## Ahom history project

The chosen series is **From Sukaphaa to Gomdhar Konwar**. [Master plan](projects/ahom-history/Insta_Angsumi/book/Ahom_Dynasty_Book_Plan_1228_to_Gomdhar_Konwar.md), [chapter overview](projects/ahom-history/Insta_Angsumi/book/Ahom_Dynasty_Chapter_Overview.md) and [Volume I working folder](projects/ahom-history/Insta_Angsumi/book/volume_01/README.md) are preserved. Five opening chapters and initial research registers exist; the book is unfinished and factual disputes remain open. PDF covers and Chapter 1 layout exports are included.

## Validate the library

Run `python3 scripts/validate_library.py` from the repository root. It checks imported files against their SHA-256 manifest and parses repository JSON files. Existing draft-link gaps and unavailable upstream assets are documented in the import report. New planning quantities are proposals, not completed artwork.

The original documents and third-party references retain their own ownership and rights status. This import does not grant a blanket licence to the asset library. Record rights before publishing or redistributing an individual asset.

## Source-based pilot assets

[Downloaded real media, dated GIS masters and official-source records](source-assets/pilot-v1/README.md), with [portable gallery](source-assets/pilot-v1/gallery.html) and explicit review/acquisition gaps.

## Roadmap: future improvements

- [ ] Make one approved "current" folder per campaign, separate from drafts
- [ ] Add Open Graph and blog header templates generated from the brand tokens
- [ ] Write a Telegram and WhatsApp channel kit (banners, post templates)
- [ ] Move large media to R2 or Git LFS
- [ ] Get a real proprietor photo, with recorded permission

## For AI agents and contributors

Read [AGENTS.md](AGENTS.md). Never treat a draft or export as approved just because it is present, and record rights before publishing any asset.

Commit as the `axomrank` account. Keep changes small and reviewable, and run the repository's checks before pushing.

## Part of AxomRank

[AxomRank](https://axomrank.pages.dev) offers free, bilingual preparation for Assam government exams. Related repositories:

- **Learn:** [AxomRank app](https://axomrank.pages.dev) (the learning app; private code), [axomrank.github.io](https://github.com/axomrank/axomrank.github.io) (the home page), [floor-test-simulator](https://github.com/axomrank/floor-test-simulator) (parliamentary majority simulator)
- **Explore Assam history:** [ahom-kingdom-history](https://github.com/axomrank/ahom-kingdom-history) (illustrated Ahom kingdom website and 41 reign lessons), [assam-history-map](https://github.com/axomrank/assam-history-map) (year-by-year historical map), [assam-history-characters](https://github.com/axomrank/assam-history-characters) (character sheets for Assam's history), [assam-visual-archive](https://github.com/axomrank/assam-visual-archive) (gallery of Assam scenes and photographs), [assam-heritage-ai-art](https://github.com/axomrank/assam-heritage-ai-art) (AI art gallery of Assamese heritage)
- **Open data:** [assam-exam-pyq](https://github.com/axomrank/assam-exam-pyq) (2,398 previous-year questions with answers), [assam-exam-syllabus](https://github.com/axomrank/assam-exam-syllabus) (syllabi for 12 recruitment boards), [assam-maps](https://github.com/axomrank/assam-maps) (map portal and GIS layers), [assam-history-sources](https://github.com/axomrank/assam-history-sources) (Kamarupa inscriptions and primary sources)
- **Publishing and brand:** [axomrank-blog](https://github.com/axomrank/axomrank-blog) (exam guides built from real papers), [assam-history-books](https://github.com/axomrank/assam-history-books) (13-book history of Assam)

## License and contact

No blanket license. Each asset's rights are recorded in `rights/`.

Corrections and questions: open an issue in this repository. AxomRank is run by Angsuman Das (sole proprietor).
