# Frequency VAST Samples

Test VAST ad responses for Frequency in-show advertising QA. All URLs below return valid XML with `Content-Type: application/xml`.

**Base URL:** `https://benantier.github.io/vast_samples/`

---

## VAST Samples per format

| Ad Format | VAST Specifications | Creative Specifications | URL |
|-----------|-------------------|------------------------|-----|
| L-Bar Video | **Mime-Type:** video/mp4<br>**Size (width):** 1080 x 432 px<br>**Size (height):** 1920 x 243 px | **Layout:** L-shape (bottom + right)<br>**Coverage:** ~40% of screen<br>**Bottom strip:** 1920 x 243 px<br>**Right column:** 432 x 837 px<br>**Animation:** 1s linear scale (100% → 77.5%) | `https://benantier.github.io/vast_samples/L-Bar%20Video.xml` |
| L-Bar Image | **Mime-Type:** image/png, image/jpg<br>**Size (width):** 1080 x 432 px<br>**Size (height):** 1920 x 243 px | **Layout:** L-shape (bottom + right)<br>**Coverage:** ~40% of screen<br>**Bottom strip:** 1920 x 243 px<br>**Right column:** 432 x 837 px<br>**Animation:** 1s linear scale (100% → 77.5%) | `https://benantier.github.io/vast_samples/L-Bar%20Image.xml` |
| Double-Box Video + Background | **Mime-Type:** video/mp4<br>**Size:** 1920 x 1080 px | **Canvas:** 1920 x 1080 px<br>**Ad video:** 960 x 540 px, right half, vertically centered<br>**Background:** Full-frame brand image | `https://benantier.github.io/vast_samples/Double-Box%20Composite.xml` |
| Overlay | **Mime-Type:** video/webm<br>**Size:** 1920 x 1080 px | **Canvas:** 1920 x 1080 px, transparent (VP9 alpha)<br>**Ad video:** 480 x 270 px<br>**Position:** Bottom-left, 5% padding | `https://benantier.github.io/vast_samples/Overlay.xml` |

---

## Notes

- Tracking pixels point to `https://track.frequency.com/...` — these are stubs and will return 404, which is expected in a test environment.
- Media files are real hosted assets
