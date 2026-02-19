# Profile README ideas & icons

Quick reference for dressing up your GitHub profile README.

---

## Fun add-ons (from across GitHub)

| Add-on | What it does | Repo / link |
|--------|----------------|--------------|
| **Typing SVG** | Animated typing/deleting text (e.g. "Front-end dev", "React, TypeScript...") | [DenverCoder1/readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg) — use [demo](https://readme-typing-svg.demolab.com/demo/) to build URL |
| **Snake (contributions)** | Snake game eating your contribution graph (animated SVG/GIF) | [Platane/snk](https://github.com/Platane/snk) — add GitHub Action, outputs to repo |
| **Streak stats** | Current streak, longest streak, total contributions | [DenverCoder1/github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) — image URL with `?user=IndigoW0lf` |
| **Profile trophy** | Trophies for stars, commits, PRs, etc. | [ryo-ma/github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) — image URL |
| **WakaTime** | Coding time per language (if you use WakaTime) | Same workflow as stats — card type `wakatime` |
| **Random dev joke** | New joke on each load | [ABSphreak/readme-jokes](https://github.com/ABSphreak/readme-jokes) |
| **Random dev quote** | Inspirational dev quote | [PiyushSuthar/github-readme-quotes](https://github.com/PiyushSuthar/github-readme-quotes) |
| **Spotify “now playing”** | Current track (needs Spotify API setup) | [kittinan/spotify-github-profile](https://github.com/kittinan/spotify-github-profile) |
| **Shields.io badges** | Custom badges (version, links, stats) | [shields.io](https://shields.io) — works with Simple Icons |

---

## Icons in Markdown

GitHub README doesn’t support custom CSS or icon fonts. You can still use icons in these ways:

### 1. Emoji (built-in)

Use any emoji directly: 🐺 ✦ 🔹 ⚛️ 🌎 🚀 💡

### 2. Simple Icons (brands / tech)

Use as **images** via jsDelivr CDN. Replace `[slug]` with the [icon slug](https://github.com/simple-icons/simple-icons/blob/master/slugs.md) (e.g. `react`, `linkedin`, `spotify`):

```markdown
<img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/[slug].svg" width="20" height="20" alt="Name" />
```

With a custom color (e.g. your pink `ff69b4`):

```markdown
<img src="https://cdn.simpleicons.org/react/ff69b4" width="20" height="20" alt="React" />
```

Browse slugs: [simpleicons.org](https://simpleicons.org)

### 3. Phosphor Icons

**In this repo:** Curated Phosphor icons (regular weight) live in `assets/icons/`. Use them in the README like this:

```markdown
<img src="https://raw.githubusercontent.com/IndigoW0lf/IndigoW0lf/main/assets/icons/heart.svg" width="20" height="20" alt="Heart" />
```

Available in `assets/icons/`: `code`, `heart`, `coffee`, `rocket-launch`, `music-notes`, `book-open`, `leaf`, `palette`, `lightning`, `star`, `github-logo`, `link`, `terminal`, `terminal-window`. To add more, download from [phosphor-icons/core](https://github.com/phosphor-icons/core) (MIT) and drop the SVG into `assets/icons/`.

**From upstream:** You can also link to Phosphor’s raw SVGs: `https://raw.githubusercontent.com/phosphor-icons/core/main/assets/regular/[icon-name].svg` (use `bold`, `fill`, etc. instead of `regular` for other weights). Browse: [phosphoricons.com](https://phosphoricons.com).

---

## Curated list

More examples and tools: [awesome-github-profile-readme](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
