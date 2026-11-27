---
api_specs:
- filename: nominatim-deletable-api-openapi.yml
  format: yaml
  label: Nominatim Deletable API
  slug: nominatim-deletable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-deletable-api-openapi.yml
- filename: nominatim-details-api-openapi.yml
  format: yaml
  label: Nominatim Details API
  slug: nominatim-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-details-api-openapi.yml
- filename: nominatim-lookup-api-openapi.yml
  format: yaml
  label: Nominatim Lookup API
  slug: nominatim-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-lookup-api-openapi.yml
- filename: nominatim-polygons-api-openapi.yml
  format: yaml
  label: Nominatim Polygons API
  slug: nominatim-polygons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-polygons-api-openapi.yml
- filename: nominatim-reverse-api-openapi.yml
  format: yaml
  label: Nominatim Reverse API
  slug: nominatim-reverse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-reverse-api-openapi.yml
- filename: nominatim-search-api-openapi.yml
  format: yaml
  label: Nominatim Search API
  slug: nominatim-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-search-api-openapi.yml
- filename: nominatim-status-api-openapi.yml
  format: yaml
  label: Nominatim Status API
  slug: nominatim-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nominatim/openapi/nominatim-status-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: Clearly display attribution as suitable for your medium.
  data:
    license: ODbL-1.0
    stance_commercial: conditional
    text: Data is provided under the ODbL license which requires to share alike
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
name: Nominatim
output_license: null
provenance_date: '2026-11-10'
provider_name: Nominatim
provider_slug: nominatim
slug: nominatim-data-license
source_date: '2026-11-10'
source_filename: nominatim-data-license.yml
source_heading: Data License
source_page: https://operations.osmfoundation.org/policies/nominatim/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Nominatim\naid: nominatim\nurl: https://operations.osmfoundation.org/policies/nominatim/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: ODbL-1.0\n  stance_commercial: conditional\n  text: Data is provided under the ODbL license which requires to share alike\nattribution:\n  required: true\n  text: Clearly display attribution as suitable for your medium.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/nominatim/data-license/nominatim-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from Nominatim's own page on 2026-11-10.
synthetic: false
tags:
- Geocoding
- OpenStreetMap
- Maps
- Location Services
- Open Source
- Public APIs
---
