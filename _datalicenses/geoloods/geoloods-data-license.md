---
api_specs:
- filename: geoloods-agent-api-openapi.yml
  format: yaml
  label: Geoloods Agent API
  slug: geoloods-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-agent-api-openapi.yml
- filename: geoloods-bbox-api-openapi.yml
  format: yaml
  label: Geoloods Bbox API
  slug: geoloods-bbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-bbox-api-openapi.yml
- filename: geoloods-countries-api-openapi.yml
  format: yaml
  label: Geoloods Countries API
  slug: geoloods-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-countries-api-openapi.yml
- filename: geoloods-geocode-api-openapi.yml
  format: yaml
  label: Geoloods Geocode API
  slug: geoloods-geocode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-geocode-api-openapi.yml
- filename: geoloods-nearby-api-openapi.yml
  format: yaml
  label: Geoloods Nearby API
  slug: geoloods-nearby-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-nearby-api-openapi.yml
- filename: geoloods-search-api-openapi.yml
  format: yaml
  label: Geoloods Search API
  slug: geoloods-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-search-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: You retain all rights to the data you submit to the Service. By using the Service, you grant us a license to process your data solely for the purpose of providing the Service.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: null
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Geoloods
output_license: null
provenance_date: '2026-11-09'
provider_name: Geoloods
provider_slug: geoloods
slug: geoloods-data-license
source_date: '2026-11-09'
source_filename: geoloods-data-license.yml
source_heading: Data License
source_page: https://geoloods.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Geoloods\naid: geoloods\nurl: https://geoloods.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: You retain all rights to the data you submit to the Service. By using the Service, you grant us a license\n    to process your data solely for the purpose of providing the Service.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/geoloods/data-license/geoloods-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Geoloods's own page on 2026-11-09.
synthetic: false
tags:
- Geocoding
- Place Search
- Location
- Coordinates
- Mapping
- Geospatial
- Agents
- OpenAPI
- Llms.txt
---
