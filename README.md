# Books

This is the private source-material repository for the Personal Knowledge Ecosystem, containing books, documents, maps, gazetteers, and reference material.

## Collection Statistics

| Metric | Value |
|--------|------:|
| History PDFs | 82 |
| History Summary Files | 82 |
| Kolkata Books | 80 |
| India Reference Books | 2 |
| Kolkata Bibliography Entries | 79 |
| Repository Status | Active |

## Purpose
- Preserve source material.
- Organize a scalable digital library.
- Support historical and technical research.
- Maintain standardized metadata and bibliographies.

## Repository Structure
```text
finance/
growth/
history/
├── archives/
├── asia/
├── gazetteers/
├── maps/
├── primary-sources/
├── world/
└── india/
    ├── books/
    │   ├── IND-EN-001 - History of India - Vol 1 - John Marshman/
    │   ├── IND-EN-002 - History of India - Vol 2 - John Marshman/
    │   └── ...
    └── states/
        └── west-bengal/
            ├── districts/
            └── cities/
                └── kolkata/
                    ├── bibliography/
                    ├── books/
                    ├── gazetteers/
                    ├── maps/
                    ├── templates/
                    └── notes/

life/
mind/
spiritual/
stories/
tech/
docs/
reading/
notes/
```

## Kolkata Book Structure

Each managed book follows a standardized folder layout:

```text
KOL-BN-001 - Book Title - Author/
├── KOL-BN-001 - Book Title - Author.pdf
└── KOL-BN-001 - Book Title - Author.summary.md
```

The `.summary.md` file stores bibliographic metadata, research notes, historical context, and reading progress for the corresponding book.

## Book ID Convention

```
KOL-BN-001  → Kolkata Bengali
KOL-EN-001  → Kolkata English
IND-EN-001  → India Reference
```

### Repository Workflow

This repository manages the acquisition, organization, and bibliographic management of source material. Historical research and knowledge extraction are performed in downstream repositories.

### Library Management Workflow

```text
Discover Book
      ↓
Evaluate Relevance
      ↓
Acquire Source
      ↓
Verify Bibliographic Metadata
      ↓
Classify Collection
      ↓
Assign Book ID
      ↓
Organize Repository
      ↓
Create / Update Summary
      ↓
Update Bibliography
      ↓
Ready for Downstream Research
```

## Documentation
- **CHANGELOG.md**: Record of changes and updates to the repository.  
- **ROADMAP.md**: Strategic plan outlining repository milestones and goals.  
- **TODO.md**: List of tasks and planned improvements.  
- **docs/**: Supporting documentation and guides.  
- **reading/**: Reading status, workflows, and tracking.

## Kolkata Documentary Project

This repository contains a structured historical source library centered on Kolkata and supplemented by India-level reference works. It includes bibliographies, books, gazetteers, historical maps, documentary resources, and standardized per-book research summaries.

The collection is organized into specialized subject areas including General History, Colonial History, Heritage, Urban Development, Primary Sources, Art & Culture, Biographies, Economy, Streets, Memoirs, and Historical Fiction. It is designed to preserve authoritative source material and provide a solid foundation for long-term historical research and documentary projects.

## Repository Principles

- Preserve original source material.
- One directory per book.
- One summary file per book.
- Maintain a single authoritative bibliography.
- Separate source material from synthesized knowledge.
- Keep folder names and Book IDs consistent.

## Relationship with Other Repositories
```text
books
(Source Material Repository)
        │
        ▼
india
(Historical Research Repository)
        │
        ▼
essentials
(Knowledge Repository)
```

This repository stores curated source material and associated research metadata. Historical analysis, synthesized knowledge, timelines, documentary preparation, and other derived research are maintained in downstream repositories.

## Current Status

**Current Release:** v1.4.0 — Expanded Kolkata Historical Research Library

This release expands the historical source collection, introduces India-level reference books, and further strengthens the repository as a structured historical source library.

- ✅ 82 managed history books
- ✅ 82 research summary files
- ✅ 80 organized Kolkata books
- ✅ 2 India reference books
- ✅ Expanded subject-based organization
- ✅ Master bibliography maintained
- 🚧 Bibliographic verification and metadata enrichment ongoing
- 🎯 Next milestone: Historical Knowledge Extraction