# MUSE — Personal AI Fashion Stylist

MUSE is a responsive front-end prototype for a personal styling app inspired by the character-creation feel of The Sims and the calm polish of a luxury fashion product.

## Prototype features

- A stylized, 3D-inspired digital-self illustration with selectable style presets.
- Outfit edit controls for occasion, mood, style direction, weather, and dress code.
- Outfit recommendations that change when you generate a new edit.
- Save/unsave looks and a saved-favourites counter.
- Wardrobe photo picker with local previews and an item counter.
- Responsive desktop and mobile layout.

## Run locally

No build step or dependencies are required. Open `index.html` in a modern browser, or serve the repository root with any static web server.

## Prototype limitations

This is a front-end demonstration, not a production AI or virtual try-on engine. Outfit suggestions are rule-based sample content; the weather selector is a manual demo control rather than a live weather API. Wardrobe photos are previewed in the browser and are not uploaded or persisted to a backend. Avatar controls currently change the presentation style rather than editing a real 3D model.

## Suggested next steps

1. Deploy as a static site with Cloudflare Pages.
2. Add persistent wardrobe storage and image upload handling.
3. Connect live weather and a real recommendation service.
4. Replace the illustrative avatar with an interactive 3D model and garment fitting pipeline.
5. Add authentication, privacy controls, and saved looks synced across devices.
