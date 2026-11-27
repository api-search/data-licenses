---
api_specs:
- filename: weatherai-io-openapi.json
  format: json
  label: Decision API
  slug: decision-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherai-io/openapi/weatherai-io-openapi.json
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: The widget must keep the “Powered by weatherAI.io” link
  data:
    license: null
    stance_commercial: unstated
    text: We, or our licensors, own all rights in the Service, the website, our documentation, the decision rules and the weatherAI.io name and logo.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: to use and display its output within your own apps, websites and services in line with these terms
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: weatherAI.io
output_license: custom
provenance_date: '2026-11-10'
provider_name: weatherAI.io
provider_slug: weatherai-io
slug: weatherai-io-data-license
source_date: '2026-11-10'
source_filename: weatherai-io-data-license.yml
source_heading: Data License
source_page: https://www.weatherai.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: weatherAI.io\naid: weatherai-io\nurl: https://www.weatherai.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: to use and display its output within your own apps, websites and services in line with these terms\ndata:\n  license: null\n  stance_commercial: unstated\n  text: We, or our licensors, own all rights in the Service, the website, our documentation, the decision rules\n    and the weatherAI.io name and logo.\nattribution:\n  required: true\n  text: The widget must keep the “Powered by weatherAI.io” link\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/weatherai-io/data-license/weatherai-io-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from weatherAI.io's own page on 2026-11-10.
synthetic: false
tags:
- Weather
- Artificial Intelligence
- Decisions
- Forecast
---
