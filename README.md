# lnk.sh

Zero-dependency, client-side link manager. Single HTML file.

## Features
- CRUD with URL, title, tags, notes, and timestamps
- Real-time search across all metadata
- Filtered views: all, unread, starred, broken
- Tag navigation with dynamic count aggregation
- Bulk selection and batch operations
- JSON export for backup/migration
- Keyboard shortcuts: `/` search, `Ctrl/Cmd+N` new, `Esc` dismiss
- Local-only persistence via `localStorage`

## Run
```bash
open index.html
# or
python3 -m http.server 8080
```

## Storage
State is stored in browser `localStorage` under `lnksh_links`. No network calls. No external dependencies.

## License
MIT