# Revolutio

Revolutio provides smart structural engineering software and the Hazard API — a web service delivering site-specific wind, snow, ice, and seismic load parameters for structural engineering and construction projects. Trusted by 750+ companies and 5000+ users across 40+ countries.

**Website:** https://www.revolutio.com.au/  
**API:** https://www.revolutio.com.au/software/hazardapi/  
**Support:** https://www.revolutio.com.au/support/hazardapi/  
**Swagger:** https://api.revolutio.com.au/swagger/index.html

## APIs

### Revolutio Hazard API (v4)

Site-specific structural load parameters for wind, snow, ice, and seismic analysis.

**Base URL:** https://api.revolutio.com.au  
**Authentication:** API Key (query parameter `apiKey` for GET; header for POST)  
**Standards:** AS/NZS 1170.2, AS 4055, ASCE 7, and others  
**Coverage:** 40+ countries

## Artifacts

### OpenAPI Specs

| File | Description |
|------|-------------|
| [revolutio-hazard-api-openapi.yml](openapi/revolutio-hazard-api-openapi.yml) | Hazard API covering wind, snow, ice, seismic, and combined endpoints |

### Rules

| File | Description |
|------|-------------|
| [revolutio-rules.yml](rules/revolutio-rules.yml) | Spectral ruleset enforcing Revolutio API conventions |

### Capabilities

| File | Description |
|------|-------------|
| [structural-engineering.yaml](capabilities/structural-engineering.yaml) | Structural engineering hazard assessment workflow |
| [shared/revolutio-hazard-api.yaml](capabilities/shared/revolutio-hazard-api.yaml) | Shared per-API capability definition |

### JSON Schema

| File | Description |
|------|-------------|
| [revolutio-wind-result-schema.json](json-schema/revolutio-wind-result-schema.json) | Wind hazard analysis result schema |

### JSON Structure

| File | Description |
|------|-------------|
| [revolutio-wind-result-structure.json](json-structure/revolutio-wind-result-structure.json) | Wind result field documentation |

### JSON-LD

| File | Description |
|------|-------------|
| [revolutio-context.jsonld](json-ld/revolutio-context.jsonld) | JSON-LD context for structural engineering hazard vocabulary |

### Examples

| File | Description |
|------|-------------|
| [revolutio-get-wind-hazard-example.json](examples/revolutio-get-wind-hazard-example.json) | Wind hazard GET request/response example |
| [revolutio-combined-hazard-example.json](examples/revolutio-combined-hazard-example.json) | Combined multi-hazard POST request/response example |

### Vocabulary

| File | Description |
|------|-------------|
| [revolutio-vocabulary.yml](vocabulary/revolutio-vocabulary.yml) | Structural engineering hazard domain vocabulary |

## Key Features

- **Wind Analysis** — Region, terrain category, topographic and shielding class per AS/NZS 1170.2
- **Snow and Ice** — Region, elevation class, and ground load parameters
- **Seismic** — Hazard class and site classification
- **ML Detection** — Machine learning terrain/exposure algorithm for improved accuracy
- **Combined Hazard** — All parameters in a single API call
- **Credit-Based Billing** — Pay only for successful requests

## Maintainers

- Kin Lane — kin@apievangelist.com
