# West Bengal History Collection

## Purpose

The **West Bengal** collection contains books and historical reference material related to the history, culture, society, politics, economy, geography, heritage, and notable people of West Bengal. It serves as the primary source library for documentary and historical research conducted in the `india` repository.

---

## Scope

The collection includes:

- General history of West Bengal
- Pre-colonial and colonial Bengal
- Partition of Bengal
- Freedom movement in Bengal
- Kolkata history
- District histories
- Culture, literature, and society
- Architecture and heritage
- Historical biographies
- Government publications and reports

---

## Collection Structure

```text
west-bengal/
├── README.md
├── cities/
│   └── kolkata/
│       ├── bibliography/
│       ├── books/
│       ├── gazetteers/
│       └── maps/
└── districts/
```

---

## Bibliography

Each city or region maintains its own bibliography that acts as the research catalog for the collection.

For Kolkata, the bibliography contains:

- `MASTER-BOOKS.md` — Canonical list of verified books.
- `BENGALI-BOOKS.md` — Verified Bengali bibliography.
- `ENGLISH-BOOKS.md` — Verified English bibliography.
- `CANDIDATE-BOOKS.md` — Acquisition pipeline for newly discovered books.
- `AUTHORS.md` — Major authors and their bibliography.
- `RESEARCH-NOTES.md` — Research notes, verification, edition comparison, and unresolved questions.
- `WANTED.md` — Verified books still missing from the collection.
- `PUBLIC-DOMAIN.md` — Legally available public-domain resources.
- `READING-ORDER.md` — Recommended learning roadmap.

---

## Organization Principles

- Organize books by subject first, then by location where appropriate.
- Keep Kolkata as a dedicated collection due to its historical significance.
- Preserve multi-volume works together.
- Keep primary sources under `history/primary-sources/` when applicable.

---

## Collection Workflow

```text
New Book
    ↓
Candidate List
    ↓
Research & Verification
    ↓
Verified
    ↓
Master Books
    ├── Bengali Books
    ├── English Books
    ├── Wanted
    ├── Public Domain
    └── Reading Order
```

Workflow principles:

- Every discovered book is recorded before acquisition.
- Only verified books become part of the master bibliography.
- Language-specific bibliographies are derived from the master list.
- Reading order is maintained independently from acquisition order.
- Research notes capture verification history and edition differences.
