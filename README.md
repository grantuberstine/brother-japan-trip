# Japan · Oct 23 – Nov 1, 2026

Working itinerary page for my brother's Japan trip. Kept deliberately broad — hotels, food and activity suggestions get slotted in as Grant provides them.

**Live site**: https://grantuberstine.github.io/brother-japan-trip/

Plain static `index.html`, no build step, GitHub Pages (branch `main`, root).

- `index.html` — the live page
- `notes/full-draft-v1.html` — an earlier fully-filled draft, kept only as a source of ideas (not linked)

## Updating

```bash
./update.sh
```

## Adding a food or activity

Each list is a `.flights` box of `.flight-row` entries. Copy one and change the three parts:

```html
<div class="flight-row">
  <div class="num"><strong>★</strong></div>                 <!-- emoji or star -->
  <div class="route">
    <div class="cities">Name of the place</div>
    <div class="note">One line about it</div>
  </div>
  <div class="airports">Neighborhood</div>
</div>
```

Paste it above the dashed "add more … here" row in the right list, then `./update.sh`.
