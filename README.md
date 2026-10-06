# GramNexa Premium Multipage

A polished, static HTML/CSS/JavaScript digital village and farmer portal.

## Pages

- `index.html` — premium home dashboard with only the main entry features
- `crop-market.html` — crop reference prices and official market links
- `farm-tools.html` — crop-value calculator and Teachable Machine pest-analysis page
- `stubble-exchange.html` — residue exchange board
- `marketplace.html` — farmer marketplace and local selling form
- `trends.html` — agriculture trend themes
- `resources.html` — official government and institutional resources
- `map.html` — interactive fictional Sundarpur village map

## Included

- English / Hindi switch across the interface, with language persistence
- Light / dark theme with dedicated contrast rules
- Glassmorphism panels, layered depth, hover interactions and smooth scrolling
- Moving crop carousel and custom SVG agricultural graphics
- Remote photo tiles on the home page with local SVG fallbacks if an image cannot load
- Voice navigation using browser speech recognition where supported
- Clickable cards and detail dialogs
- Crop-value calculator with multiple crop options
- Teachable Machine model integration using the supplied model URL
- Farmer marketplace with local browser-only draft listings
- Stubble exchange with local browser-only listings
- Interactive village map with clickable pins and keyboard support
- Responsive navigation and reduced-motion support

## Run

Use VS Code Live Server or a local static server:

```text
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Scope note

Some prices, trends and listings are reference content. The Sundarpur map is fictional. Local forms are stored only on the current device. Verify important information with official sources.

The Teachable Machine classifier and remote photography require an internet connection. The portal includes local SVG fallbacks for the photographic tiles so the visual layout does not break when remote photos are unavailable.
