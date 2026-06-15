# Language Gateways: Social Image Builder

A unified, single-interface tool for creating professional, on-brand social media posts. Choose your template type, customize, and download as PNG—all in one place.

## One Builder, Four Templates

**Language Gateways: Social Image Builder** (`language-gateways-builder.html`) replaces the previous three separate template files. It includes:

### 1. **Quote**
- Feature an inspirational or thought-provoking quote
- Optional attribution (name)
- Customizable text size
- Uses `Quote-BG.png` background

**Example:**
> "If you don't know other languages you don't know your own."  
> GOETHE

### 2. **Statistic**
- Large impact number + supporting description
- Separate sizing controls for number and description text
- Built-in spacing between elements
- Uses `Stat-BG.png` background

**Example:**
> **7,000**  
> Languages in the world. 7,000 ships laden with worlds.

### 3. **Concept**
- Conceptual text (headline + insight)
- Purple text on light background
- Customizable text size
- Uses `Concept-BG.png` background

**Example:**
> The Rose: Same flower, twelve different ways of seeing it. What perspectives are you missing?

### 4. **Image**
- Upload your own image
- `Image-BG.png` overlays on top (gold bar foreground)
- Optional text overlay with colour choice
- Customizable text size

**Example:**  
Your image + optional white/purple/magenta/gold text on top

---

## Setup

### GitHub Directory Structure

```
language_gateways/
├── language-gateways-builder.html
├── README.md
└── images/
    ├── Quote-BG.png
    ├── Stat-BG.png
    ├── Concept-BG.png
    └── Image-BG.png
```

### 1. Upload Files to GitHub

1. Go to your repo: https://github.com/timfnash/language_gateways
2. Delete the old `template-quote.html`, `template-concept.html`, `template-stat.html` files (optional, but recommended to avoid confusion)
3. Upload `language-gateways-builder.html` to the **repo root**
4. Upload your four `-BG.png` files to the `/images/` folder:
   - `Quote-BG.png`
   - `Stat-BG.png`
   - `Concept-BG.png`
   - `Image-BG.png`

### 2. Enable GitHub Pages

If not already done:
1. Settings → Pages
2. Branch: `main`
3. Root folder: `/ (root)`
4. Save

### 3. Access Your Builder

```
https://timfnash.github.io/language_gateways/language-gateways-builder.html
```

**Bookmark this link!**

---

## How to Use

### Step 1: Choose Template Type
Select from the dropdown: **Quote**, **Statistic**, **Concept**, or **Image**

### Step 2: Fill in Content
- **Quote:** Text + name (auto-uppercase)
- **Stat:** Number + description
- **Concept:** Concept text
- **Image:** Upload image + optional text + text colour

### Step 3: Adjust Font Sizes
Each template type has a **font size slider**:
- Drag to increase/decrease size
- Real-time preview shows current size (e.g., "3.2rem")
- Range varies by template (e.g., Quote: 1–5rem)

### Step 4: Preview
The preview on the right updates instantly as you type and adjust.

### Step 5: Download
Click **⬇️ Download PNG** to save as 1080×1080px PNG file.

---

## Font Sizes

Each template includes a font size slider:

| Template | Control | Range | Default |
|----------|---------|-------|---------|
| **Quote** | Quote Text Size | 1–5rem | 3.2rem |
| **Stat** | Description Text Size | 0.8–3rem | 1.5rem |
| **Concept** | Concept Text Size | 1–5rem | 3.2rem |
| **Image** | Text Overlay Size | 1–4rem | 2.5rem |

---

## Image Template Details

The **Image** template layers elements in this order (bottom to top):

1. **Uploaded image** (your background photo)
2. **Image-BG.png** (gold bar overlay)
3. **Text overlay** (optional, on top)

This creates the gold-bar-in-front effect. If you upload no image, the builder shows a black background with just the Image-BG.png on top.

---

## Social Media Specs

All exports are **1080×1080px PNG**, optimized for:

- **Instagram Feed** (square posts)
- **Facebook** (square format)
- **TikTok** (use as vertical by cropping)
- **LinkedIn Feed** (stretch to 1200×628px landscape)

**Tip:** For landscape formats, take a 1080×1080px export and stretch it in Canva or your design tool. The text and elements scale gracefully.

---

## Brand Foundation

**Theme:** Language Gateways  
**Tagline:** "How the languages you don't speak reveal what you're missing in those you do."  
**Brand Colours:** Deep Purple (#49016F) | Magenta (#DE0183) | Antique Gold (#C3A14E)  
**Typography:** Jost (loaded from Google Fonts)  
**Watermark:** #languagegateways (automatically included on downloaded images)

---

## Tips

- **Quote:** Keep to 1–2 sentences; line breaks are preserved
- **Stat:** Use round numbers (7,000 not 7,234) for maximum impact
- **Concept:** 3–5 word headlines + 1–2 lines of supporting text works best
- **Image:** Test text colour against your background photo for legibility

---

## Posting Checklist

Before uploading to social:

- ✅ Download PNG from builder (1080×1080px)
- ✅ Include **#languagegateways** in caption
- ✅ Link to relevant TEDx talk (if quote-based)
- ✅ Mention @timfnash (if relevant)
- ✅ Use consistent posting time/day (2–3 per week recommended)

**Example Caption:**
```
"If you don't know other languages you don't know your own." — Goethe

Discover why language is a gateway to thinking differently.

Watch the full talk: [TEDx link]

#languagegateways
```

---

## Troubleshooting

**Images not loading?**
- Ensure `/images/` folder exists in your repo
- Check filenames match exactly (case-sensitive): `Quote-BG.png`, `Stat-BG.png`, etc.
- Images should have transparent backgrounds (PNG)

**Preview looks different from download?**
- This is normal due to browser rendering. The download is the source of truth.
- Always test one download before posting multiple.

**Font not loading?**
- Jost is loaded from Google Fonts. Check your internet connection.
- The builder will fall back to system fonts if unavailable (still readable).

**Text overlay not appearing on Image?**
- Make sure you've entered text in the "Text Overlay" field
- The text preview should show immediately

---

## Next Steps

1. **Upload files to GitHub** (builder + 4 BG images)
2. **Test with one template** (open the builder, fill in text, download)
3. **Bookmark the builder URL** for quick access
4. **Start creating posts** (rotate through your 20 post ideas)
5. **Schedule across LinkedIn + Instagram** (2–3 per week)

---

## Deleting Old Template Files

If you uploaded the previous three template files (`template-quote.html`, `template-concept.html`, `template-stat.html`), you can now delete them:

1. Go to your GitHub repo
2. Click each old template file
3. Click **⋯** (more options) → Delete

The unified builder replaces all three, so they're no longer needed.

---

**Created for:** Tim F Nash | Language Gateways  
**Brand thesis:** Language is a gateway to thinking differently, not just a tool for communication.  
**Last updated:** June 2026
