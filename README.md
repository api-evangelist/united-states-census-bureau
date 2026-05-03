# United States Census Bureau

The U.S. Census Bureau is the nation's leading provider of quality data about its people and economy. The Census Bureau provides programmatic access to its datasets through the Census Data API, covering demographic, economic, housing, and social statistics. Key datasets include the American Community Survey (ACS), Decennial Census, Population Estimates, County Business Patterns, and International Trade data, accessible at geographic levels from national down to census tract and block group.

**Website:** [https://www.census.gov/](https://www.census.gov/)
**Developer Portal:** [https://www.census.gov/data/developers.html](https://www.census.gov/data/developers.html)

## APIs

### Census Data API

- **Base URL:** `https://api.census.gov/data`
- **Documentation:** [census.gov/data/developers](https://www.census.gov/data/developers.html)
- **API Key Signup:** [api.census.gov/data/key_signup.html](https://api.census.gov/data/key_signup.html)
- **Discovery Tool:** [New Discovery Tool](https://www.census.gov/data/developers/updates/new-discovery-tool.html)

### TIGERweb GeoServices REST API

- **Base URL:** `https://tigerweb.geo.census.gov/arcgis/rest/services`
- **Documentation:** [TIGERweb Main](https://tigerweb.geo.census.gov/tigerwebmain/TIGERweb_main.html)

### Census Geocoding Services

- **Base URL:** `https://geocoding.geo.census.gov/geocoder`
- **Documentation:** [Census Geocoder](https://geocoding.geo.census.gov/geocoder/)

## Artifacts

### OpenAPI Specifications

- [census-data-api-openapi.yml](openapi/census-data-api-openapi.yml) — OpenAPI 3.1 specification covering the Census Data API including ACS, Decennial Census, Population Estimates, County Business Patterns, Economic Census, International Trade, and Geocoding endpoints.

### Examples

- [census-data-api-getACS5Year-example.json](examples/census-data-api-getACS5Year-example.json) — Example ACS 5-Year query for population, income, and home values by county.
- [census-data-api-geocodeAddress-example.json](examples/census-data-api-geocodeAddress-example.json) — Example geocoding request returning coordinates and census geography for an address.
- [census-data-api-getCountyBusinessPatterns-example.json](examples/census-data-api-getCountyBusinessPatterns-example.json) — Example County Business Patterns query for technology industry by state.

### Spectral Rules

- [census-data-api-rules.yml](rules/census-data-api-rules.yml) — Spectral ruleset enforcing Census API documentation standards including required parameters, geography documentation, and response schema definitions.

### Capabilities

- [demographic-research.yaml](capabilities/demographic-research.yaml) — Naftiko workflow capability for Census Bureau demographic research, providing unified REST and MCP access to ACS, population estimates, decennial census, and economic data.
- [capabilities/shared/census-data-api.yaml](capabilities/shared/census-data-api.yaml) — Shared per-API Naftiko capability definition for the Census Data API.

### JSON Schema

- [census-data-api-response-schema.json](json-schema/census-data-api-response-schema.json) — JSON Schema for the standard Census 2D array API response format.
- [census-data-api-geocode-schema.json](json-schema/census-data-api-geocode-schema.json) — JSON Schema for Census Geocoder API responses.

### JSON Structure

- [census-data-api-response-structure.json](json-structure/census-data-api-response-structure.json) — Structure documentation for the Census Data API 2D array response format.

### JSON-LD Context

- [united-states-census-bureau-context.jsonld](json-ld/united-states-census-bureau-context.jsonld) — Linked data context aligning Census Bureau vocabulary with schema.org, SDMX statistical standards, and GeoSPARQL geographic ontologies.

### Vocabulary

- [united-states-census-bureau-vocabulary.yml](vocabulary/united-states-census-bureau-vocabulary.yml) — Domain vocabulary covering Census surveys, geographic hierarchy, statistical variables, API data structures, and demographic classification concepts.

## Additional Resources

| Resource | Link |
|---|---|
| Data Explorer | [data.census.gov](https://data.census.gov/) |
| GitHub | [github.com/uscensusbureau](https://github.com/uscensusbureau) |
| Developer Forum | [apiforum.uscensusbureau.com](https://apiforum.uscensusbureau.com/) |
| Example Queries | [Example API Queries](https://www.census.gov/data/developers/guidance/api-user-guide/example-api-queries.html) |

**Maintained by:** [API Evangelist](https://apievangelist.com)
