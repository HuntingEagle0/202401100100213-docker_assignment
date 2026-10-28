# FestPass - Docker & Container Security Assessment

## Student Details
- **Student Name:** Sachin Sood
- **Registration Number (REGNO):** 202401100100213
- **Port:** 8013 (80 + last two digits: 13)
- **Docker Hub Username:** sachin184
- **Docker Hub Repository:** https://hub.docker.com/r/sachin184/fest-backend

---

## AI Tools Declaration
- **Tool Used:** Gemini / Antigravity AI Assistant
- **Purpose / Usage:** Used for assistance in code generation, Dockerfile vulnerability remediation guidance, compose network segregation design, and command structuring according to assessment specifications.

---

## Image Digest
- **Backend Image (`1.0.0`):** `sachin184/fest-backend:1.0.0`
- **Digest:** `sha256:a3ce5d25660d504299644c02c365ebb709fdf7d2b340adc37b94aaa4a402df11`

---

## Vulnerability Remediation Summary (Trivy Scan)

| Stage | Image | Base Image | Size | CRITICAL | HIGH |
|---|---|---|---|---|---|
| **Before (3.1)** | `fest-backend:0.1` | `python:3.9` | 1.61 GB | 234 | 2249 |
| **After (3.3)** | `fest-backend:0.2` | `python:3.11-slim` (non-root) | 223 MB | 0 | 0 |

---

## Uncompleted Steps
None. All stages (1 to 5) completed as specified.
