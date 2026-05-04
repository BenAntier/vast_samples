# Frequency VAST Samples

Test VAST ad responses for Frequency in-show advertising QA. All URLs below return valid XML with `Content-Type: application/xml`.

**Base URL:** `https://raw.githubusercontent.com/BenAntier/vast_samples/main/`

---

## VAST Samples per format

| Ad Format | Specifications | URL |
|-----------|-------------|-----|
| L-Bar Video | Mime-Type: video/mp4; Duration: 10s | `https://raw.githubusercontent.com/BenAntier/vast_samples/main/L-Bar%20Video.xml` |
| L-Bar Image | Mime-Type: image/png; Duration: 10s | `https://raw.githubusercontent.com/BenAntier/vast_samples/main/L-Bar%20Image.xml` |

---

## Error Handling

- If an unsupported Vast response, the Frequency Proxy URL will return an empty vast with an error pixel with the following error codes:
  1. Unsupported Mediafile
  2. Unsupported duration
  3. Unsupported creative size
  4. Broken VAST
  5. New creative

---

## Notes

- Tracking pixels point to `https://track.frequency.com/...` — these are stubs and will return 404, which is expected in a test environment.
- Media files are real hosted assets
