# Photos

Drop your own JPEGs in here with these exact names and they'll appear on the page.
Until a file exists, the page shows a tidy dashed placeholder in its slot — nothing breaks.

| Filename            | Where it shows            | Suggested shot                          |
|---------------------|---------------------------|-----------------------------------------|
| `1881-1.jpg`        | Base camp (left frame)    | The 1881 house / exterior               |
| `1881-2.jpg`        | Base camp (right frame)   | A room / interior                       |
| `1812.jpg`          | Friday — Bathgate leg     | The 1812 restaurant, Bathgate           |
| `loch-ness.jpg`     | The Loch Ness monster day | Loch Ness / Urquhart Castle             |

Tips:
- Landscape orientation works best. Roughly 1200–1600px wide is plenty.
- Keep them reasonably compressed (a few hundred KB each) so the page stays quick.
- After adding files: `git add img/ && git commit -m "Add photos" && git push`.

The ferry, house, dining, Nessie and castle artwork on the page are drawn in SVG
right in `index.html`, so they need no image files.
