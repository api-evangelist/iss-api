# ISS Location API (Open Notify)

APIs.json 0.19 provider profile for the Open Notify ISS API — a free, open-source REST service that exposes real-time International Space Station data.

## APIs Cataloged

| API | Base URL | Description |
|-----|----------|-------------|
| ISS Current Location | `http://api.open-notify.org/iss-now.json` | Real-time ISS latitude and longitude with Unix timestamp |
| People in Space | `http://api.open-notify.org/astros.json` | Count and roster of all humans currently in space |

## Key Facts

- **Authentication**: None required
- **Pricing**: Free, no registration needed
- **License**: Source code under GPL-3.0-or-later; documentation under CC BY 3.0
- **Source**: [github.com/open-notify/Open-Notify-API](https://github.com/open-notify/Open-Notify-API)
- **Maintainer**: Nathan Bergey / Open Notify

## Files

```
apis.yml                          # APIs.json 0.19 provider manifest
plans/iss-api-plans.yml           # API Commons Plans — single free tier
rate-limits/iss-api-rate-limits.yml  # API Commons Rate Limits — best-practice guidance
finops/iss-api-finops.yml         # FOCUS-aligned FinOps profile (consumer-side cost only)
```

## Notes

The ISS pass-time prediction endpoint (`/iss-pass.json`) has been permanently retired. Only the location and astronaut endpoints remain active.

Because the service is community-operated with no SLA, production workloads should implement client-side caching (minimum 5-second TTL for position data, 1-hour TTL for crew data) and consider self-hosting the open-source code for reliability-critical applications.
