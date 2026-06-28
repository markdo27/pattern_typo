# ✦ Pattern Studio

Pattern Studio is a browser-based, high-performance generative vector design tool. It allows designers and developers to create bold geometric patterns, neo-Memphis / Risograph-inspired visuals, and modular typographic card overlays.

Built as a single-page reactive application with raw HTML5 and inline SVG, it features advanced layouts, a dynamic color preset system, and a robust user-experience workflow.

---

## 🚀 Features

### 🎨 Generative Patterns
- **24 Distinct Vector Patterns** including Vertical/Horizontal/Diagonal stripes, Plaids, Checkerboards, Honeycomb dots, Scallops, Variable grids, Sunbursts, Emblems, and custom Risograph series (*Chevron, Tetris, Ovolo, Arch*).
*   **Color Role System:** Interactively map colors to specific elements in the pattern simply by clicking swatches in the sidebar.

### ✍️ Typography & Card Layouts
- **Text on Pattern overlays:** Frost glass cards, solid color panels, or clean transparent backdrops.
- **Responsive design:** Automatically tracks sizes, positions, alignments, and padding.
- **Text alignment controls:** Align text left, center, or right.
- **Generative text pool:** Quickly shuffle random literature quotes and credits.
- **Custom font loader:** Upload `.ttf`, `.otf`, or `.woff2` files directly.

### 🛠️ Professional Workspace & UX Polish
- **Undo & Redo (Cmd+Z / Cmd+Shift+Z):** A 30-state design stack tracks your adjustments.
- **Retina PNG Export:** Export designs at **2x pixel resolution** for high-res social sharing or print.
- **Canvas Presets:** Choose from Square, Instagram Portrait/Story, Twitter card, A4, A3, or custom formats.
- **Focus Mode (`F` key):** Collapse all panels for a distraction-free review.
- **Interactive Search:** Quickly filter through the 24 pattern grids.
- **Slider Click-to-Edit:** Click any slider value to type a precise value.
- **Hex Copy:** Double-click any color swatch in the palette grid to copy it to your clipboard.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Cmd/Ctrl + Z` | Undo |
| `Cmd/Ctrl + Shift + Z` | Redo |
| `Cmd/Ctrl + Shift + E` | Export SVG |
| `Cmd/Ctrl + Shift + P` | Export PNG (2x High-Res) |
| `F` | Toggle Focus Mode |
| `R` | Randomize Pattern Layout |
| `C` | Randomize Color Palette |
| `T` | Toggle Tile Preview |
| `&larr;` / `&rarr;` | Switch previous / next pattern |
| `?` | Toggle shortcuts help overlay |
| `Esc` | Close overlays / exit focus mode |

---

## 💻 Local Development

Run the app locally with no installation or build step:

```bash
# Clone the repository
git clone https://github.com/markdo27/pattern_typo.git
cd pattern_typo

# Run a simple local server
python3 -m http.server 8080
```

Open `http://localhost:8080` in your web browser.
