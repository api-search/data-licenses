---
api_specs:
- filename: dott-discovery-api-openapi.yml
  format: yaml
  label: Dott Discovery API
  slug: dott-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dott/openapi/dott-discovery-api-openapi.yml
- filename: dott-stations-api-openapi.yml
  format: yaml
  label: Dott Stations API
  slug: dott-stations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dott/openapi/dott-stations-api-openapi.yml
- filename: dott-system-api-openapi.yml
  format: yaml
  label: Dott System API
  slug: dott-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dott/openapi/dott-system-api-openapi.yml
- filename: dott-vehicles-api-openapi.yml
  format: yaml
  label: Dott Vehicles API
  slug: dott-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dott/openapi/dott-vehicles-api-openapi.yml
- filename: dott-zones-api-openapi.yml
  format: yaml
  label: Dott Zones API
  slug: dott-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dott/openapi/dott-zones-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: use the databases or the individual data you access via the API for any purpose other than to connect to the Dott Product including, competitive analysis, benchmarking or aggregation of such data with competitors of Dott
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: obtain any commercial or financial benefit from the API or the data provided by the API
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Dott
output_license: custom
provenance_date: '2026-11-09'
provider_name: Dott
provider_slug: dott
slug: dott-data-license
source_date: '2026-11-09'
source_filename: dott-data-license.yml
source_heading: Data License
source_page: https://ridedott.com/api-licence/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Dott\naid: dott\nurl: https://ridedott.com/api-licence/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: obtain any commercial or financial benefit from the API or the data provided by the API\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: use the databases or the individual data you access via the API for any purpose other than to connect to\n    the Dott Product including, competitive analysis, benchmarking or aggregation of such data with competitors\n    of Dott\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/dott/data-license/dott-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Dott's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transportation
- Micromobility
- Mobility
- E-Scooter
- E-Bikes
- GBFS
- Shared Mobility
- Smart City
- Sustainability
---
