# Deutscher Wetterdienst

Deutscher Wetterdienst (DWD) is Germany's national meteorological service, a federal agency under the Ministry for Digital and Transport, responsible for weather and climate services, warnings, and the national climate archive. Its geospatial surface is an OGC-standard GeoServer at maps.dwd.de serving forecast, radar, warning and climate layers to any WMS or WFS client without a key.

Profiled 2026-08-20 as part of the [OGC](../ogc/) standards-body pass — this organization is an
**OGC Catalyst member** (Government, Germany), found in OGC's own
active-member roster and confirmed to serve a live OGC surface on its own host.

## APIs

| aid | name | base | contract |
|---|---|---|---|
| `deutscher-wetterdienst:ogc-web-services` | Deutscher Wetterdienst OGC Web Services (WMS / WFS) | https://maps.dwd.de/geoserver/ows | 2 GetCapabilities |

## Provenance

Every GetCapabilities document under `openapi/` was retrieved **anonymously, with HTTP 200, on
2026-08-20** and is stored verbatim — it is the machine-readable contract for a classic OGC service,
which has no OpenAPI. Nothing here is derived from documentation.

Membership facts come from `https://portal.ogc.org/services/srv_active_members_csv_new.php`.
