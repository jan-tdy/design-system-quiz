# Cross-Platform Design System Configuration Engine

A self-contained, single-file browser application for configuring a cross-platform design system and exporting a detailed Markdown master specification with a raw JSON token configuration.

## Use

Open `index.html` in a modern browser. No build step, external dependency, server, or network connection is required. Answer all 62 questions across seven architecture modules. Answers and the project name are saved in browser local storage. Use the question map to navigate, reset to clear the saved configuration, or download/copy the generated `.md` specification after completing all questions.

The generated blueprint includes the full decision register, suggested implementation sequence, accessibility acceptance criteria, validation prompts, and JSON tokens for semantic color modes, spacing, typography, density, motion, elevation, and platform conventions. Review generated defaults against product requirements before implementation.

## License

MIT. See [LICENSE](LICENSE).

## GitHub Pages deployment

The `Deploy static site to GitHub Pages` workflow publishes `index.html` from the repository root whenever a commit reaches `main`, and supports manual runs from the Actions tab. In repository **Settings → Pages**, select **GitHub Actions** as the build and deployment source. The deployed site is a static single-file app and needs no build dependencies.
