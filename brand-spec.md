# Brand spec — Mobile Photobooth (Ban Công | Mộc)

Source: 6 production screenshots of the live "Ban Công | Mộc Photobooth" web app
(`1789065910243`…`781d4871….jpg`) + 1 QR code (`mobile-photobooth.png`), all in
`C:\Users\P1 Gen 4\Downloads\mobile photobooth`. Values sampled directly from
pixels (12px grid histogram), then converted to OKLch.

## Color tokens

| Token       | Hex       | OKLch                  | Use |
|-------------|-----------|------------------------|-----|
| `--bg`      | `#F7EEDD` | `oklch(95.2% 0.025 83)`  | page canvas (warm cream) |
| `--surface` | `#FCFDF7` | `oklch(99.2% 0.008 114)` | cards / sheets |
| `--fg`      | `#3B2A1A` | `oklch(30.1% 0.037 64)`  | ink / body / headings |
| `--muted`   | `#8F836D` | `oklch(61.5% 0.035 83)`  | secondary text / meta |
| `--border`  | `#E7D9BE` | `oklch(89.0% 0.039 84)`  | hairlines, card edges |
| `--accent`  | `#B5532E` | `oklch(55.9% 0.137 40)`  | CTAs ("Gửi in", "Đặt in"), price |
| `--gold`    | `#E8C6A3` | `oklch(84.7% 0.061 68)`  | warm wash, frame motifs |

The warm cream canvas is brand-mandated (it is the live product's canvas), so it
is used deliberately — not a default beige fallback.

## Typography

- **Display / headings:** warm high-contrast serif (app renders a Georgia-like
  serif). Stack: `'Iowan Old Style', 'Palatino Linotype', Georgia, 'Times New Roman', serif`.
- **Body / UI:** humanist sans. Stack: `-apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif`.
- **Mono / numbers / order IDs:** `ui-monospace, 'SFMono-Regular', Menlo, monospace` with `tabular-nums`.
- Big display weight 600–700; body 400; UI labels 550–600.

## Layout posture

- Paper-first: cards sit on cream, separated by 1px `--border` hairlines and soft
  elevation — never heavy shadow.
- Radii: generous (12–20px on cards, pill on chips/steppers) — matches app sheets.
- Accent budget: terracotta `--accent` used sparingly — one primary action per
  view plus price text. Gold is a wash/motif, never a button fill.
- Vertical rhythm: airy 24–48px gutters; content centered in a ~720–880px column
  for the app mocks, wider for the infographic narrative.
- Motifs: Hanoi / Vietnam (flag bunting, Old Quarter line-art), "Rước đèn" mid-autumn
  moon, hand-drawn storefront. Warm, nostalgic, hospitality-toned.

## Brand marks

- Wordmark lockup: `Ban Công | Mộc Photobooth` set in the display serif, `|` in `--muted`.
- Present "Mộc" and "Ban Công" as serif wordmarks (no standalone logo raster was
  supplied beyond the app header); QR is placed as `mobile-photobooth.png`.
