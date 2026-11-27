---
api_specs:
- filename: postfinder-io-nearby-api-openapi.yml
  format: yaml
  label: Postfinder Nearby API
  slug: postfinder-io-nearby-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-nearby-api-openapi.yml
- filename: postfinder-io-places-api-openapi.yml
  format: yaml
  label: Postfinder Places API
  slug: postfinder-io-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-places-api-openapi.yml
- filename: postfinder-io-postcodes-api-openapi.yml
  format: yaml
  label: Postfinder Postcodes API
  slug: postfinder-io-postcodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-postcodes-api-openapi.yml
- filename: postfinder-io-reference-api-openapi.yml
  format: yaml
  label: Postfinder Reference API
  slug: postfinder-io-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-reference-api-openapi.yml
- filename: postfinder-io-search-api-openapi.yml
  format: yaml
  label: Postfinder Search API
  slug: postfinder-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: including the obligation to credit them.
  data:
    license: custom
    stance_commercial: conditional
    text: The underlying data is not ours and we do not claim it. It is licensed from OpenStreetMap, GeoNames, Geoscape and others, and those licences travel with it
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: take the data from here and you take their conditions too
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Postfinder
output_license: custom
provenance_date: '2026-11-10'
provider_name: Postfinder
provider_slug: postfinder-io
slug: postfinder-io-data-license
source_date: '2026-11-10'
source_filename: postfinder-io-data-license.yml
source_heading: Data License
source_page: https://postfinder.io/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Postfinder\naid: postfinder-io\nurl: https://postfinder.io/en/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: take the data from here and you take their conditions too\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: The underlying data is not ours and we do not claim it. It is licensed from OpenStreetMap, GeoNames, Geoscape\n    and others, and those licences travel with it\nattribution:\n  required: true\n  text: including the obligation to credit them.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/postfinder-io/data-license/postfinder-io-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Postfinder's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Address
- Autocomplete
- Logistics
- Australia
---
