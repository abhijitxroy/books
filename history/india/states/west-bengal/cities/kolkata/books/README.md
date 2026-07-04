# Kolkata Books Collection

## Purpose

This directory contains the curated book collection for the history, culture, heritage, and development of Kolkata (formerly Calcutta).

The collection includes both Bengali and English works and serves as the primary source material for research.

---

## Directory Structure

```text
books/
├── architecture/
├── art-culture/
├── biographies/
├── colonial-history/
├── economy/
├── general-history/
├── heritage/
├── historical-fiction/
├── memoirs/
├── photography/
├── primary-sources/
├── streets/
├── travelogues/
└── urban-development/
```

---

## Naming Convention

Books use the following naming convention:

```text
KOL-<LANG>-<ID> - <Book Title> - <Author>.pdf
```

Examples:

- `KOL-BN-001 - Kolikatar Katha (Aadi Kando) - Pramathanath Mallik.pdf`
- `KOL-EN-001 - Calcutta Old and New - H.E.A. Cotton.pdf`

Where:

- `KOL` = Kolkata
- `BN` = Bengali
- `EN` = English
- `ID` = Permanent collection identifier

---

## Identifier Ranges

### Bengali

| Range | Category |
|------:|----------|
| 001–099 | General History |
| 100–199 | Historical Fiction |
| 200–299 | Memoirs |
| 300–399 | Biographies |
| 400–449 | Heritage & Architecture |
| 450–499 | Art & Culture |
| 500–549 | Economy & Trade |
| 550–599 | Photography |
| 600–649 | Travelogues |

### English

| Range | Category |
|------:|----------|
| 001–099 | History |
| 100–199 | Heritage |
| 200–299 | Urban Development |
| 300–399 | Architecture |
| 400–499 | Memoirs |
| 500–599 | Primary Sources |
| 600–699 | Gazetteers |
| 700–799 | Maps |

---

## Collection Principles

- Maintain original scans whenever possible.
- Use consistent file names.
- Assign permanent identifiers only once.
- Organize books by subject rather than author.
- Keep placeholder directories with a `README.md` until the corresponding book is acquired.
- Do not duplicate the same edition unless there is a clear archival reason.

---

## Book Acquisition Workflow

```text
Discover Book
      ↓
CANDIDATE-BOOKS.md
      ↓
Research & Verification
      ↓
Acquire Book
      ↓
Assign Permanent ID
      ↓
Rename File
      ↓
Place in Appropriate Category
      ↓
Update MASTER-BOOKS.md
```

Every book added to the collection should follow this workflow to ensure consistent cataloging, naming, and documentation.

---


---

## Category Definitions

| Category | Description |
|----------|-------------|
| `general-history` | Comprehensive histories of Kolkata covering multiple periods or broad historical themes. |
| `colonial-history` | Books focusing on the East India Company, British administration, and colonial Calcutta. |
| `primary-sources` | Original historical records, official documents, correspondence, government publications, and archival source material. |
| `heritage` | Heritage buildings, traditional neighbourhoods, notable families, monuments, and conservation. |
| `architecture` | Architecture, urban design, and significant public or private buildings. |
| `urban-development` | City planning, municipal development, infrastructure, and urban growth. |
| `streets` | Roads, neighbourhoods, place names, and locality histories. |
| `historical-fiction` | Fictional works that portray Kolkata through historical settings or events. |
| `memoirs` | Personal reminiscences, autobiographical accounts, and eyewitness narratives. |
| `biographies` | Biographies of significant personalities associated with Kolkata. |
| `art-culture` | Literature on art, music, theatre, festivals, and cultural history. |
| `economy` | Trade, commerce, finance, industry, and economic history. |
| `photography` | Historical photographs, photographic collections, and visual documentation. |
| `travelogues` | Travel narratives and visitor accounts describing Kolkata. |


## Relationship with the Bibliography

This directory stores the books themselves.

Bibliographic metadata, acquisition tracking, reading order, research notes, and wanted lists are maintained under:

```text
../bibliography/
```

The bibliography is the authoritative catalog, while this directory contains the physical collection.