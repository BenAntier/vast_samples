# Frequency VAST Samples

Test VAST ad responses for Frequency in-show advertising QA. All URLs below return valid XML with `Content-Type: application/xml`.

**Base URL:** `https://benantier.github.io/vast_samples/`

---

## VAST Samples per format

| Ad Format | Specifications | URL |
|-----------|-------------|-----|
| L-Bar Video | **Mediafile Mime-Type:** video/mp4<br>**Size (width):** 1080 x 432 px<br>**Size (height):** 1920 x 243 px | `https://benantier.github.io/vast_samples/L-Bar%20Video.xml` |
| L-Bar Image | **Mediafile Mime-Type:** image/png, image/jpg<br>**Size (width):** 1080 x 432 px<br>**Size (height):** 1920 x 243 px | `https://benantier.github.io/vast_samples/L-Bar%20Image.xml` |
| Double-Box Video + Background | **Mediafile Mime-Type:** video/mp4<br>**Mediafile Size:** 1920 x 1080 px | `https://benantier.github.io/vast_samples/Double-Box%20Composite.xml` |
| Overlay | **Mediafile Mime-Type:** video/webm<br>**Mediafile Size:** 1920 x 1080 px<br>**Creative Size:** 480 x 270 px<br>**Position:** Bottom-left (5% padding) | `https://benantier.github.io/vast_samples/Overlay.xml` |

---

## Notes

- Tracking pixels point to `https://track.frequency.com/...` — these are stubs and will return 404, which is expected in a test environment.
- Media files are real hosted assets
