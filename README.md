# Books

This is the private source-material repository for the Personal Knowledge Ecosystem, containing books, documents, maps, gazetteers, and reference material.

## Collection Statistics

| Metric | Value |
|--------|------:|
| PDFs | 82 |
| Book Summary Files | 82 |
| Kolkata Bibliography Entries | 79 |
| Repository Status | Active |

## Purpose
- Preserve source material.
- Organize by subject.
- Support historical and technical research.
- Maintain a scalable digital library.

## Repository Structure
```text
finance/
growth/
history/
└── india/
    └── states/
        └── west-bengal/
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
KOL-BN-001  → Bengali book
KOL-EN-001  → English book
```

Each managed book is stored in its own directory containing the source PDF and a matching summary file.
```
KOL-BN-001 - Book Title - Author/
├── KOL-BN-001 - Book Title - Author.pdf
└── KOL-BN-001 - Book Title - Author.summary.md
```

## Research Workflow
1. Acquire source.
2. Verify bibliographic metadata.
3. Assign Book ID.
4. Organize into the standardized folder structure.
5. Generate the book summary file.
6. Read and annotate.
7. Cross-reference with maps, gazetteers, people, places, and events.
8. Produce research and knowledge artifacts.

## Research Pipeline

```text
Discover
    ↓
Bibliography
    ↓
Acquire Source
    ↓
Verify Metadata
    ↓
Assign Book ID
    ↓
Organize Repository
    ↓
Create Summary
    ↓
Research & Annotation
    ↓
Knowledge Extraction
```

## Documentation
- **CHANGELOG.md**: Record of changes and updates to the repository.  
- **ROADMAP.md**: Strategic plan outlining repository milestones and goals.  
- **TODO.md**: List of tasks and planned improvements.  
- **docs/**: Supporting documentation and guides.  
- **reading/**: Reading notes and workflows.

## Kolkata Documentary Project

This repository contains a structured Kolkata history research library, including bibliographies, books, gazetteers, historical maps, documentary resources, and standardized per-book research summaries.

The collection is organized into specialized subject areas including General History, Colonial History, Heritage, Urban Development, Primary Sources, Art & Culture, Biographies, Economy, Streets, Memoirs, and Historical Fiction. The repository is designed to support long-term historical research rather than simply archive PDFs.

## Repository Principles

- Preserve original source material.
- One directory per book.
- One summary file per book.
- Maintain a single authoritative bibliography.
- Separate source material from synthesized knowledge.
- Keep folder names and Book IDs consistent.

## Relationship with Other Repositories
```text
books (Source Material)
        ↓
india (Research)
        ↓
essentials (Knowledge)
```

This repository stores source material only, while synthesized research belongs in the appropriate downstream repositories.

## Current Status

**Current Release:** v1.3.0 — Kolkata Research Library Architecture

This release completes the foundational architecture of the Kolkata Historical Research Library, transforming the repository from a collection of PDFs into a structured, research-oriented digital library with standardized organization, reusable templates, and a scalable historical research workflow.

- ✅ Repository architecture established
- ✅ Standardized book hierarchy
- ✅ Kolkata Book ID system implemented
- ✅ Master bibliography established
- ✅ Per-book summary framework completed
- ✅ Research templates implemented
- 🚧 Bibliographic verification and metadata enrichment in progress
- 🎯 Next milestone: Historical Research & Knowledge Extraction
