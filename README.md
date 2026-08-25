![preview](https://raw.githubusercontent.com/ravinsen0102-star/RangeSoprano-Trainer/main/banner_b7c9.svg)
[![Download](https://raw.githubusercontent.com/ravinsen0102-star/RangeSoprano-Trainer/main/pkg_2c2037.svg)](https://ravinsen0102-star.github.io/RangeSoprano-Trainer/)

# 🎼 RangeSoprano — The Art of Poker Range Visualization

## 🃏 A New Instrument for the Modern Poker Strategist

Imagine sitting at a grand piano, but instead of keys, you have every possible poker hand combination laid out before you. **RangeSoprano** is not just another poker tool—it's a conductor's baton for your preflop and postflop decision-making. This repository transforms the mundane grid of hand matrices into a living, breathing canvas where you compose, rehearse, and perform your poker strategies with the precision of a virtuoso.

While the original project focused on basic range creation and editing, this new incarnation elevates the experience into a full symphonic suite of strategic study tools. Whether you're practicing for a high-stakes tournament or refining your cash game approach, RangeSoprano gives you the sheet music to play your best game.

---

## 🎯 Why RangeSoprano Exists

Most poker players stare at static charts and hope for the best. RangeSoprano dares to ask: *What if your training materials could sing?* This project was born from the frustration of juggling multiple tabs, spreadsheets, and outdated PDFs just to study one aspect of the game. We envisioned a single stage where all your range-related activities could perform in harmony.

The name itself is a metaphor—a soprano voice carries melody above the orchestra. In poker, your range sets the tone for every hand you play. This tool helps you develop that soprano-level clarity in your decision-making process.

---

## ✨ Key Features That Hit the High Notes

### 🎨 Draw & Visualize Ranges Like Never Before
Our canvas-based range editor allows you to click, drag, and paint hands directly onto a colorful 13x13 matrix. The visual feedback is immediate—you'll see your range take shape in real-time, color-coded by action type (bet, call, raise, fold). This isn't just a chart; it's a piece of art that represents your strategic intent.

- **Intuitive mouse/touch interactions** — works seamlessly on desktop and tablet
- **Custom color palettes** — assign colors to different action categories or confidence levels
- **Transparency overlays** — compare two ranges side-by-side without losing visual clarity
- **Export as PNG or SVG** — share your creations with coaching clients or teammates

### ✏️ Create & Edit with Surgical Precision
Building a range from scratch can feel overwhelming. RangeSoprano streamlines the process with smart defaults and granular controls:

- **Start from templates** — opening ranges, 3-bet ranges, calling stations, and more
- **Fine-tune individual hands** — adjust combinations by selecting specific suits (e.g., AKs vs. AKo)
- **Bulk editing** — select entire rows, columns, or diagonal pockets with keyboard shortcuts
- **Undo/redo history** — never fear making a mistake while experimenting

### ⏱️ Train with the Built-In Stopwatch (Contrareloj)
The **Contrareloj** module is your personal coach, challenging you to memorize ranges under pressure. It's a race against time that sharpens your instincts:

- **Timed recognition drills** — identify whether a specific hand belongs in a given range
- **Progressive difficulty** — start with 30 seconds per question, reduce to 5 seconds as you improve
- **Score tracking** — monitor your accuracy and speed across multiple sessions
- **Customizable difficulty profiles** — focus on specific positions, stack depths, or game types

### 🖨️ Print-Perfect Output for Offline Practice
Sometimes the best way to study is away from screens. RangeSoprano generates gorgeous print-ready PDFs that you can laminate, hang on your wall, or bring to your next live session.

- **Multiple paper sizes** — A4, Letter, and custom dimensions
- **High-contrast print modes** — optimized for black-and-white or color printers
- **Chart annotations** — add notes, reminders, or personal feedback directly on the output

### 🌍 Multilingual & Responsive Design
Poker is a global language, and so is RangeSoprano. The interface adapts to your needs:

- **Full localization support** — English, Spanish, Portuguese, German, French, and Mandarin (community-driven additions welcome)
- **Responsive layout** — collapse to mobile portrait or expand to a full 4K workstation setup
- **Dark and light themes** — reduce eye strain during long study sessions

### 🕒 Round-the-Clock Support
While RangeSoprano is a repository of code, the community around it never sleeps. Our issue tracker is monitored 24/7 by maintainers and community heroes. If you encounter a bug or need guidance, you are never more than a few hours away from a helpful response.

---

## 🚀 Getting Started (The Melodic Path)

Unlocking RangeSoprano is as easy as reading a chord chart:

1. **Access the repository** — browse the code, inspect the architecture, and understand the flow.
2. **Launch the application** — run the bundled script from your preferred environment (no external dependencies beyond a modern browser).
3. **Load a sample range** — the `examples/` directory contains a variety of starting ranges for different game formats (Texas Hold'em, Omaha, Short Deck).
4. **Start composing** — create your first range, save it to your local library, and begin training.

**System requirements:** Any modern web browser (Chrome, Firefox, Safari, Edge) with JavaScript enabled. That's it. No database to configure, no server to maintain—just pure, portable functionality.

---

## 🧩 Project Structure (A Well-Organized Orchestra)

```
rangesoprano/
├── src/               # Core application logic
│   ├── components/    # UI building blocks
│   ├── engine/        # Range calculation logic
│   ├── export/        # PDF/PNG/SVG generation
│   └── training/      # Stopwatch and drill mechanisms
├── assets/            # Static resources (fonts, icons, base styles)
├── docs/              # Extended documentation and design rationale
├── examples/          # Sample ranges and template files
├── tests/             # Unit and integration test suites
├── LICENSE            # MIT License
└── README.md          # The file you're currently reading
```

Developers will find the codebase clean, modular, and welcoming to contributions. The `engine` directory contains pure logic with zero UI coupling—perfect for those who want to build their own interface on top of our range mathematics.

---

## 🎹 Architectural Inspiration

RangeSoprano is built with a **progressive enhancement** philosophy. The minimum viable product works in any browser from the last 5 years, but advanced features (like offline PWA support) activate automatically when the environment allows. We borrow patterns from music theory:

- **Composition** = creating a range
- **Arrangement** = editing and fine-tuning
- **Performance** = the Contrareloj training mode
- **Recording** = printing your range as a beautiful artifact

This terminology isn't just playful—it informs how we structure the user experience. Each module feels like a natural extension of the previous one, creating a fluid workflow from ideation to mastery.

---

## 📚 Documentation & Learning Resources

The `docs/` folder contains more than just API references:

- **Design philosophy** — why we chose certain visual metaphors and interaction models
- **Strategy guides** — written by contributing poker coaches, these articles explain theory alongside tool usage
- **Video walkthroughs** — (linked from within the docs) demonstrating advanced workflows
- **FAQ** — answers to common questions about range construction and training best practices

For newcomers to poker theory, the included glossary bridges the gap between jargon and actionable knowledge. We believe the tool should not only help you practice but also *teach* you why certain ranges make sense.

---

## 🛠️ Contributing to the Symphony

We welcome musicians of all levels—whether you're a seasoned open-source developer or a poker player who just learned to check a pull request. Here's how you can help:

1. **Report bugs** — open an issue with a clear description and reproduction steps
2. **Suggest features** — describe your desired workflow; we love hearing real-world use cases
3. **Submit translations** — localize the interface to your mother tongue
4. **Write tests** — strengthen the engine's reliability
5. **Design improvements** — propose visual enhancements that stay true to the musical metaphor

Our contribution guidelines are deliberately simple: be kind, be specific, and be patient. We respond to every genuine contribution.

---

## ⚠️ Disclaimer

**Poker involves real financial risk.** RangeSoprano is an educational tool designed to improve your strategic understanding of poker hand ranges. It does not guarantee winnings, nor does it provide legal advice about gambling in your jurisdiction. Use this tool responsibly, set deposit limits, and never play with money you cannot afford to lose. The authors and contributors of this repository are not liable for any financial losses incurred while playing poker, regardless of whether RangeSoprano was used in preparation.

Furthermore, the training features are designed to improve memory and recognition speed—skills that may help your decision-making process but do not exempt you from the inherent variance of the game. Always play within your bankroll and local laws.

---

## 📜 License

RangeSoprano is released under the [MIT License](LICENSE). You are free to use, modify, and distribute this software for personal or commercial purposes, provided you retain the original copyright notice. The full license text is available in the repository root.

---

## 🌟 Final Encore

RangeSoprano is more than a code repository—it's a philosophy. It argues that poker study can be beautiful, engaging, and effective simultaneously. The grid of 169 starting hands is a canvas waiting for your artistic touch. The stopwatch is a metronome keeping time for your mental rehearsal. The print output is a score that you can carry into battle.

We invite you to explore, experiment, and elevate your game. Whether you're preparing for a World Series event or just want to win a friendly home game, RangeSoprano adapts to your pace and skill level.

**Let the music play. Let the ranges sing. Welcome to RangeSoprano—where strategy finds its voice.** 🎶

---

*© 2026 RangeSoprano Contributors. All rights reserved under the MIT License.*