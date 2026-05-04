# Frequency VAST Samples

Test VAST ad responses for Frequency in-show advertising QA. All URLs below return valid XML with `Content-Type: application/xml`.

**Base URL:** `https://raw.githubusercontent.com/BenAntier/vast_samples/main/`

---

## Available Samples

| Ad Format | Specifications | URL |
|-----------|-------------|-----|
| L-Bar Video | Mime-Type: video/mp4; Duration: 10s | `https://raw.githubusercontent.com/BenAntier/vast_samples/main/L-Bar%20Video.xml` |
| L-Bar Image | 3.0 | `https://raw.githubusercontent.com/BenAntier/vast_samples/main/L-Bar%20Image.xml` |

---

## Notes

- Tracking pixels fire to `https://track.frequency.com/...` — these are stubs and will return 404, which is expected in a test environment.
- Media files are real hosted MP4s and will play.
- If a player enforces strict VAST validation, ensure it supports VAST 3.0.
