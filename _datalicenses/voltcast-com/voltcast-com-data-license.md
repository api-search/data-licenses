---
api_specs:
- filename: voltcast-com-prices-api-openapi.yml
  format: yaml
  label: voltcast-com Prices API
  slug: voltcast-com-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltcast-com/openapi/voltcast-com-prices-api-openapi.yml
- filename: voltcast-com-public-api-openapi.yml
  format: yaml
  label: voltcast-com Public API
  slug: voltcast-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltcast-com/openapi/voltcast-com-public-api-openapi.yml
- filename: voltcast-com-zones-api-openapi.yml
  format: yaml
  label: voltcast-com Zones API
  slug: voltcast-com-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltcast-com/openapi/voltcast-com-zones-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: conditional
    text: Verbatim prices for other bidding zones may require a NEMO license for redistribution
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: Forecasts, optimization results and derived statistics are Voltcast's own output.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: voltcast-com
output_license: null
provenance_date: '2026-11-10'
provider_name: voltcast-com
provider_slug: voltcast-com
slug: voltcast-com-data-license
source_date: '2026-11-10'
source_filename: voltcast-com-data-license.yml
source_heading: Data License
source_page: https://voltcast.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: voltcast-com\naid: voltcast-com\nurl: https://voltcast.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: Forecasts, optimization results and derived statistics are Voltcast's own output.\ndata:\n  license: null\n  stance_commercial: conditional\n  text: Verbatim prices for other bidding zones may require a NEMO license for redistribution\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/voltcast-com/data-license/voltcast-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from voltcast-com's own page on 2026-11-10.
synthetic: false
tags:
- Video
- Streaming
- Media
- Platform
---
