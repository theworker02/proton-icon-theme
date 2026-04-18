# Proton Icons

Proton Icons is a clean, futuristic Visual Studio Code icon theme built around a compact purple-and-white design system inspired by the Proton mark and your recently built Proton language. Every icon in the theme uses valid SVG geometry only, with rounded forms and a unified tile-based silhouette so the theme feels consistent across files and folders.

## Included Icons

- Default file
- Folder
- Open folder
- Proton files (`.proton`)
- JavaScript (`.js`, `.mjs`, `.cjs`)
- TypeScript (`.ts`, `.mts`, `.cts`)
- JSON (`.json`, `.jsonc`)
- HTML (`.html`, `.htm`)
- CSS and preprocessors (`.css`, `.scss`, `.sass`, `.less`)
- Markdown (`.md`, `.markdown`, `.mdx`)
- Python (`.py`, `.pyw`)
- Java (`.java`)
- C and headers (`.c`, `.h`)
- C++ (`.cpp`, `.cxx`, `.cc`, `.hpp`, `.hxx`, `.hh`)
- C# (`.cs`, `.csx`)
- PHP (`.php`, `.phtml`)
- Go (`.go`)
- Rust (`.rs`)
- YAML (`.yml`, `.yaml`)
- XML (`.xml`, `.xsd`, `.xsl`, `.xslt`, `.plist`)
- SVG (`.svg`)
- Images (`.png`, `.jpg`, `.jpeg`, `.gif`, `.webp`, `.avif`, `.ico`, `.bmp`)
- SQL (`.sql`)
- Shell scripts (`.sh`, `.bash`, `.zsh`, `.fish`, `.ps1`)
- Docker files (`Dockerfile`, `docker-compose.yml`, `.dockerignore`)
- Git files (`.gitignore`, `.gitattributes`, `.gitmodules`)
- Environment files (`.env*`)
- TOML (`.toml`)
- Vue (`.vue`)
- React (`.jsx`, `.tsx`)
- Lockfiles (`package-lock.json`, `yarn.lock`, `pnpm-lock.yaml`, `Cargo.lock`, and more)

## Development

1. Open this folder in Visual Studio Code.
2. Press `F5` to launch an Extension Development Host.
3. In the new window, run `Preferences: File Icon Theme`.
4. Select `Proton Icons`.

You can also package or install the extension directly from this folder using standard VS Code extension tooling.

## File Layout

```text
proton-icons/
├── icons/
│   ├── default-file.svg
│   ├── folder.svg
│   ├── folder-open.svg
│   ├── proton.svg
│   ├── js.svg
│   ├── ts.svg
│   ├── json.svg
│   └── ...additional file-type icons
├── icon-theme.json
├── package.json
├── README.md
└── .vscodeignore
```

## Design Notes

- Primary color: `#8B5CF6`
- Foreground accent: `#FFFFFF`
- Rounded geometry
- Stroke weight: `1.1` to `1.5`
- No text nodes, placeholders, or raster assets
