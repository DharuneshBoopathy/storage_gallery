# The Gallery — Private Archival Media Storage

This repository acts as the secure, version-controlled cold storage vault for **The Gallery** digital archive application.

## Directory Structure

```text
storage_gallery/
├── groups/                     # Circle & Group Vaults
│   └── <group-slug>/
│       ├── group.json          # Circle metadata (ID, title, description, owner)
│       ├── README.md           # Visual circle archive manifest
│       ├── photos/             # Full-resolution original photos
│       ├── videos/             # Master videos
│       └── derivatives/        # High-speed WebP thumbnails & optimized variants
├── public/                     # Public batch media
│   ├── photos/
│   ├── videos/
│   └── derivatives/
└── private/                    # Private creator vaults
```

## Automation

- Folder structures, metadata manifests, and assets are automatically synchronized and version-controlled on group creation and file ingestion.
- Commits are structured to maintain transparent audit logs of uploads, member circles, and archive activity.
