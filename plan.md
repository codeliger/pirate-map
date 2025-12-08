Help me build a comprehensive plan for this PLAN.md project. Use basic markdown and no fancy formatting. Use minimal markdown features like lists and headers:

```
# VSCodium Theme Color Differ

Automated tool to detect VSCodium theme changes and attach screenshots to pull requests for human review.

## Requirements
1. Use plain Node.js for GitHub Actions compatibility
2. Use browser automation (Playwright) for VSCodium control
3. Minimal, fast execution suitable for CI/CD

## Implementation

### Setup
1. Install VSCodium + code-server in GitHub Actions runner
2. Install Pirate Map Light Theme
3. Open sample workspace with various file types

### Process
For each theme property:
1. Take baseline screenshot
2. Change property to #FF00FF in theme file
3. Reload theme in VSCodium
4. Take new screenshot
5. Diff images and extract changed regions
6. Save diff and slice images

### Output
- Comment on PR with property changes
- Attach before/after/diff images
- Focus on clearly visible changes only
```

## Technical Stack

- **Playwright** - Browser automation for VSCodium control
- **VSCodium + code-server** - Headless editor with web access
- **Node.js** - GitHub Actions compatible runtime
- **Image diff library** - Detect changed regions automatically
- **Sharp** - Image processing and region extraction

## File Structure

```
theme-differ/
├── src/
│   ├── analyzer/
│   │   ├── theme-parser.js
│   │   ├── property-mapper.js
│   │   └── change-detector.js
│   ├── automation/
│   │   ├── vscodium-controller.js
│   │   ├── ui-triggers.js
│   │   └── screenshot-capture.js
│   ├── analysis/
│   │   ├── image-differ.js
│   │   ├── region-extractor.js
│   │   └── change-mapper.js
│   ├── reporting/
│   │   ├── markdown-generator.js
│   │   ├── image-processor.js
│   │   └── pr-commenter.js
│   └── utils/
│       ├── file-manager.js
│       ├── color-utils.js
│       └── config.js
├── tests/
│   ├── unit/
│   ├── integration/
│   └── fixtures/
├── screenshots/
│   ├── baseline/
│   ├── current/
│   └── comparisons/
├── docker/
│   ├── Dockerfile.vscodium
│   └── docker-compose.yml
├── scripts/
│   ├── install-vscodium.sh
│   └── setup-code-server.sh
├── package.json
├── action.yml
└── README.md
```

