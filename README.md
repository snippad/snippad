<div align="center">

<img src="public/icon.png" alt="SnipPad logo" width="120" />

# SnipPad

A fast, polished desktop client for managing your code snippets like a pro.

</div>

> [!NOTE]
> SnipPad is still in active development; you may encounter bugs or breaking changes.

## Features

- **Snippet & Tag Management**: Create unlimited snippets and tags with filtered listing support.
- **Editor Workspace**: Built-in Monaco Editor for a first-class code editing experience.
- **Interactive Panel**: Action row for saving, editing, starring, and deleting snippets, plus tabbed navigation between open snippet files.
- **Custom Themes**: Client UI themes and Monaco editor themes via `~/.snippad/themes.json`.
- **Custom Settings**: Configure application behavior and editor preferences via `~/.snippad/settings.json`.
- **Auto-Updates**: Automated update checks to keep you on the latest features and patches.
- **In-App Announcements**: News, updates, and community notes on startup.

## Tech Stack

| Library          | Purpose                          |
| :--------------- | :------------------------------- |
| React            | UI Component Library             |
| Electron         | Cross-platform Desktop Framework |
| Vite             | Next-gen Frontend Tooling        |
| TypeScript       | Static Type Checking             |
| Tailwind CSS     | Utility-first CSS Framework      |
| Monaco Editor    | In-app Code Editor Core          |
| Zustand          | Minimal React State Management   |
| Electron Builder | Desktop App Installer & Bundler  |
| Electron Store   | Persistent App Data & Settings   |
| React Markdown   | Markdown Renderer                |

## Getting Started

### Prerequisites

- [Bun](https://bun.sh/) (or npm/pnpm/yarn) and Node.js 18+

### Development

```bash
bun install
bun run dev
```

### Build

```bash
bun run build
```

## License

SnipPad is licensed under the [GPL-3.0-only](LICENSE).

The project name, logos, and branding assets are not open-source. See [BRANDING.md](BRANDING.md) for branding usage guidelines.
