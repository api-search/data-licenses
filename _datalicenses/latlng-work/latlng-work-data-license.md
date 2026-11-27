---
api_specs:
- filename: latlng-work-geocoding-api-openapi.yml
  format: yaml
  label: latlng-work Geocoding API
  slug: latlng-work-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/latlng-work/openapi/latlng-work-geocoding-api-openapi.yml
- filename: latlng-work-places-api-openapi.yml
  format: yaml
  label: latlng-work Places API
  slug: latlng-work-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/latlng-work/openapi/latlng-work-places-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: You must include appropriate attribution ("© OpenStreetMap contributors") in any public-facing application using our map or geocoding services.
  data:
    license: ODbL
    stance_commercial: unstated
    text: Geographic and map data is provided under the Open Database License (ODbL) from OpenStreetMap contributors.
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
name: latlng-work
output_license: null
provenance_date: '2026-11-09'
provider_name: latlng-work
provider_slug: latlng-work
slug: latlng-work-data-license
source_date: '2026-11-09'
source_filename: latlng-work-data-license.yml
source_heading: Data License
source_page: https://www.latlng.work/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: latlng-work\naid: latlng-work\nurl: https://www.latlng.work/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: ODbL\n  stance_commercial: unstated\n  text: Geographic and map data is provided under the Open Database License (ODbL) from OpenStreetMap contributors.\nattribution:\n  required: true\n  text: You must include appropriate attribution (\"© OpenStreetMap contributors\") in any public-facing application\n    using our map or geocoding services.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/latlng-work/data-license/latlng-work-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from latlng-work's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Geocoding
- Mapping
- Location
---
