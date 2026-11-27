---
api_specs:
- filename: opentopography-api-public-api-openapi.yml
  format: yaml
  label: OpenTopography API Public API
  slug: opentopography-api-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opentopography-api/openapi/opentopography-api-public-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Users of the data are responsible for license compliance and should attribute the source of the data as well as OpenTopography for providing access to those data.
  data:
    license: custom
    stance_commercial: allowed
    text: Data obtained from OpenTopography are free of all copyright restrictions and made fully and freely available for both non-commercial and commercial uses. Certain datasets may have open data licenses (e.g., Creative Common CC BY 4.0) associated with them.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: Data obtained from OpenTopography APIs are free of all copyright restrictions and made fully and freely available for both non-commercial and commercial uses.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: OpenTopography API
output_license: custom
provenance_date: '2026-11-10'
provider_name: OpenTopography API
provider_slug: opentopography-api
slug: opentopography-api-data-license
source_date: '2026-11-10'
source_filename: opentopography-api-data-license.yml
source_heading: Data License
source_page: https://opentopography.org/usageterms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: OpenTopography API\naid: opentopography-api\nurl: https://opentopography.org/usageterms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: Data obtained from OpenTopography APIs are free of all copyright restrictions and made fully and freely\n    available for both non-commercial and commercial uses.\ndata:\n  license: custom\n  stance_commercial: allowed\n  text: Data obtained from OpenTopography are free of all copyright restrictions and made fully and freely available\n    for both non-commercial and commercial uses. Certain datasets may have open data licenses\
  \ (e.g., Creative Common\n    CC BY 4.0) associated with them.\nattribution:\n  required: true\n  text: Users of the data are responsible for license compliance and should attribute the source of the data as\n    well as OpenTopography for providing access to those data.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/opentopography-api/data-license/opentopography-api-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from OpenTopography API's own page on 2026-11-10.
synthetic: false
tags:
- DEM
- Data
- Elevation
- Geospatial
- LiDAR
- Topographical
- Topography
---
