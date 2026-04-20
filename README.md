# ClipOn

A lightweight clipboard manager built with Tauri + React + TypeScript.

## Features

- 📋 Auto-record clipboard history
- 📌 Pin frequently used items
- 🔍 Quick search
- 🌙 Dark/Light theme
- 🌍 Multi-language support (Chinese/English)
- 🚀 Auto-start on system boot
- ⚙️ Configurable maximum record count

## Development

### Prerequisites

- Node.js >= 20
- Rust >= 1.75

### Install Dependencies

```bash
npm install
```

### Development Mode

```bash
npm run tauri dev
```

### Build for Production

```bash
npm run tauri build
```

### Release New Version

Automated releases with release-it:

```bash
# Interactive release
npm run release

# Auto-increment versions
npm run release:patch  # 0.1.0 -> 0.1.1
npm run release:minor  # 0.1.0 -> 0.2.0
npm run release:major  # 0.1.0 -> 1.0.0
```

Requires GitHub Token:
```bash
export GITHUB_TOKEN="your_token"
```

## Tech Stack

- **Frontend**: React + TypeScript + Vite
- **UI**: HeroUI v3 + Tailwind CSS
- **Backend**: Tauri (Rust)
- **Release**: release-it + conventional-changelog

## License

MIT
