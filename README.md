# Japan · Oct 23 – Nov 1, 2026

Tokyo · Hakone · Kyoto · Nara — 8 nights. Draft itinerary page for my brother's trip.

**Live site**: https://grantuberstine.github.io/brother-japan-trip/

Same format as `parents-japan-trip` and `grantlina-asia-trip`: one static `index.html`, no build step, hosted on GitHub Pages (branch `main`, root).

## Updating

After editing `index.html`, run:

```bash
./update.sh
```

Or manually:

```bash
git add . && git commit -m "update" && git push
```

Site updates within ~30 seconds.

## When bookings come in

Add `data-img="file.png"` to any row in the Flights / Hotels tables and drop the confirmation screenshot in `images/bookings/`. The row becomes clickable and opens the screenshot. Swap the amber "Not booked" labels for the green `.booked` badge as things get locked in.
