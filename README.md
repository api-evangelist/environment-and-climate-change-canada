# Environment and Climate Change Canada

Environment and Climate Change Canada (ECCC) is the federal department responsible for weather, climate, water and environmental protection in Canada, and operates the Meteorological Service of Canada. It runs an OGC-standard GeoServer at geo.ec.gc.ca which responds correctly to WMS, WFS and OGC API - Features requests but, when probed on 2026-08-20, published no layers, no feature types and no collections through it.

Profiled 2026-08-20 as part of the [OGC](../ogc/) standards-body pass — this organization is an
**OGC Explorer member** (Government, Canada), found in OGC's own
active-member roster and confirmed to serve a live OGC surface on its own host.

## APIs

| aid | name | base | contract |
|---|---|---|---|
| `environment-and-climate-change-canada:ogc-web-services` | Environment and Climate Change Canada OGC Web Services (WMS / WFS) | https://geo.ec.gc.ca/geoserver/ows | 1 GetCapabilities |
| `environment-and-climate-change-canada:ogc-api-features` | Environment and Climate Change Canada OGC API - Features | https://geo.ec.gc.ca/geoserver/ogc/features/v1 | 0 GetCapabilities |

## Provenance

Every GetCapabilities document under `openapi/` was retrieved **anonymously, with HTTP 200, on
2026-08-20** and is stored verbatim — it is the machine-readable contract for a classic OGC service,
which has no OpenAPI. Nothing here is derived from documentation.

Membership facts come from `https://portal.ogc.org/services/srv_active_members_csv_new.php`.
