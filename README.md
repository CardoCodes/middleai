# Job Application Assistant (Chrome/Firefox)

AI-powered browser extension that automates job applications with smart form filling and document generation.

## Key Features

- Smart form auto-fill
- AI-generated cover letters
- Resume customization
- Application tracking
- Cross-browser support

## Quick Start

1. Clone and install:
```bash
git clone https://github.com/cardocodes/middleai.git
cd middleai/extension
npm install
```

2. Set up environment:
```bash
cp .env.example .env  # Add your API keys
```

3. Start development:
```bash
npm run dev
```

## Loading the Extension

1. Build production version:
```bash
npm run build:extension
```

2. Load in browser:
- **Chrome:** `chrome://extensions/` → Enable dev mode → Load `dist/`
- **Firefox:** `about:debugging` → Load Temporary Add-on → Select `manifest.json`

## Development

| Command               | Description                  |
|-----------------------|------------------------------|
| `npm run dev`         | Start development server     |
| `npm test`            | Run frontend tests           |
| `npm run build`       | Create production build      |

## Tech Stack

- React + TypeScript
- OpenAI API
- MongoDB
- Docker (optional)

## Contributing

PRs welcome! Please follow standard GitHub workflow:
1. Fork repo
2. Create feature branch
3. Submit PR
