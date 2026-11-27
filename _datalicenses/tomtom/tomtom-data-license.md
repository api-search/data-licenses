---
api_specs:
- filename: tomtom-additional-data-api-openapi.yml
  format: yaml
  label: TomTom Additional Data API
  slug: tomtom-additional-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-additional-data-api-openapi.yml
- filename: tomtom-batch-routing-api-openapi.yml
  format: yaml
  label: TomTom Batch Routing API
  slug: tomtom-batch-routing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-batch-routing-api-openapi.yml
- filename: tomtom-copyrights-api-openapi.yml
  format: yaml
  label: TomTom Copyrights API
  slug: tomtom-copyrights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-copyrights-api-openapi.yml
- filename: tomtom-filters-api-openapi.yml
  format: yaml
  label: TomTom Filters API
  slug: tomtom-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-filters-api-openapi.yml
- filename: tomtom-geocoding-api-openapi.yml
  format: yaml
  label: TomTom Geocoding API
  slug: tomtom-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-geocoding-api-openapi.yml
- filename: tomtom-raster-api-openapi.yml
  format: yaml
  label: TomTom Raster API
  slug: tomtom-raster-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-raster-api-openapi.yml
- filename: tomtom-reachable-range-api-openapi.yml
  format: yaml
  label: TomTom Reachable Range API
  slug: tomtom-reachable-range-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-reachable-range-api-openapi.yml
- filename: tomtom-reverse-geocoding-api-openapi.yml
  format: yaml
  label: TomTom Reverse Geocoding API
  slug: tomtom-reverse-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-reverse-geocoding-api-openapi.yml
- filename: tomtom-routing-api-openapi.yml
  format: yaml
  label: TomTom Routing API
  slug: tomtom-routing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-routing-api-openapi.yml
- filename: tomtom-search-api-openapi.yml
  format: yaml
  label: TomTom Search API
  slug: tomtom-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-search-api-openapi.yml
- filename: tomtom-traffic-flow-api-openapi.yml
  format: yaml
  label: TomTom Traffic Flow API
  slug: tomtom-traffic-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-traffic-flow-api-openapi.yml
- filename: tomtom-traffic-incidents-api-openapi.yml
  format: yaml
  label: TomTom Traffic Incidents API
  slug: tomtom-traffic-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-traffic-incidents-api-openapi.yml
- filename: tomtom-traffic-tiles-api-openapi.yml
  format: yaml
  label: TomTom Traffic Tiles API
  slug: tomtom-traffic-tiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-traffic-tiles-api-openapi.yml
- filename: tomtom-vector-api-openapi.yml
  format: yaml
  label: TomTom Vector API
  slug: tomtom-vector-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-vector-api-openapi.yml
- filename: tomtom-wms-wmts-api-openapi.yml
  format: yaml
  label: TomTom WMS / WMTS API
  slug: tomtom-wms-wmts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomtom/openapi/tomtom-wms-wmts-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: you agree to implement to the TomTom Copyright API in order to generate the applicable copyright and logo attribution.
  data:
    license: custom
    stance_commercial: conditional
    text: to use the Licensed Products (including, where applicable, via an Authorized Distribution Channel) for Evaluation Use only.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: to use the Maps APIs, directly or in conjunction with a SDK, in connection with your Permitted Solution
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: TomTom
output_license: custom
provenance_date: '2026-11-10'
provider_name: TomTom
provider_slug: tomtom
slug: tomtom-data-license
source_date: '2026-11-10'
source_filename: tomtom-data-license.yml
source_heading: Data License
source_page: https://docs.tomtom.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: TomTom\naid: tomtom\nurl: https://docs.tomtom.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: to use the Maps APIs, directly or in conjunction with a SDK, in connection with your Permitted Solution\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: to use the Licensed Products (including, where applicable, via an Authorized Distribution Channel) for Evaluation\n    Use only.\nattribution:\n  required: true\n  text: you agree to implement to the TomTom Copyright API in order to generate the applicable copyright\
  \ and logo\n    attribution.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/tomtom/data-license/tomtom-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from TomTom's own page on 2026-11-10.
synthetic: false
tags:
- Maps
- Traffic
- Transportation
- Navigation
- Location
- Geospatial
- Routing
- Geocoding
- Mobility
---
