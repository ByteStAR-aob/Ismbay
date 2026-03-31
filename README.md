# Ismbay
Drop your ideas 
PRISM Library
Personal Knowledge System
PRISM is a high-fidelity, local-first web application designed for the reconstruction and archiving of ideas, frameworks, and insights. It combines a minimalist "Expressive Dark" aesthetic with a robust functional layer for personal knowledge management.
## Core Philosophy
PRISM treats personal data as a spectrum of light—organized, refracted, and preserved. It is built to function as a standalone node, prioritizing speed, visual clarity, and offline availability.
### Technical Stack
 * Frontend: Vanilla HTML5, CSS3 (Modern Flex/Grid, CSS Variables), and ES6+ JavaScript.
 * Authentication: Cloudflare Turnstile for bot protection + local localStorage session management.
 * Design System: Glassmorphic UI featuring Playfair Display and JetBrains Mono for a "Technical-Elegant" contrast.
 * PWA: Service Worker integration for offline persistence and "Add to Home Screen" capability.
### Key Features
 * Refractive UI: Ambient animated orbs and noise textures provide a deep-space atmosphere without sacrificing performance.
 * Smart Content Parser: A custom JS-based renderer that automatically detects and styles:
   * Formulas: Lines containing λ, ×, or θ are rendered in specialized blocks.
   * Key-Value Pairs: Automatic detection of Key → Value patterns.
   * Pull Quotes: Styled blocks for high-impact insights.
   * Section Breaks: Logical separation using --- dividers.
 * Tag-Based Navigation: Dynamic sidebar filtering with color-coded categories (Physics, Perception, Design, etc.).
 * Local-First Security: All entries are stored in the browser's localStorage, ensuring your data stays on your hardware.
 * Portable Exports: One-click "Save" feature to export entries as formatted .txt files for external backup.
## Usage
### Local Development
Simply open index.html in any modern browser (Brave Nightly recommended) or serve via Node.js:
npx serve .

### Adding Content
 * Gate: Complete the Turnstile challenge.
 * Auth: Sign up or Sign in (data is hashed and stored locally).
 * Compose: Use the floating action button (◆) to open the Composer.
 * Format: Use natural language—PRISM will handle the "Refraction" (styling) automatically based on your syntax.
## Architecture Notes
 * Persistence: Data is keyed by user email within localStorage, allowing multiple local profiles.
 * Mobile Optimized: Fully responsive shell that transitions to a bottom-heavy mobile UI for easy thumb access.
 * Asset Loading: Utilizes Google Fonts and Cloudflare APIs for security and typography; core logic remains dependency-free.
