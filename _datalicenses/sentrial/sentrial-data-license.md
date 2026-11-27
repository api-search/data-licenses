---
api_specs:
- filename: sentrial-events-api-openapi.yml
  format: yaml
  label: Sentrial Events API
  slug: sentrial-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentrial/openapi/sentrial-events-api-openapi.yml
- filename: sentrial-sessions-api-openapi.yml
  format: yaml
  label: Sentrial Sessions API
  slug: sentrial-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentrial/openapi/sentrial-sessions-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: You retain ownership of any data you submit to the Service, but grant us a license to use it to provide and improve the Service.
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
name: Sentrial
output_license: null
provenance_date: '2026-11-10'
provider_name: Sentrial
provider_slug: sentrial
slug: sentrial-data-license
source_date: '2026-11-10'
source_filename: sentrial-data-license.yml
source_heading: Data License
source_page: https://www.sentrial.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Sentrial\naid: sentrial\nurl: https://www.sentrial.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: You retain ownership of any data you submit to the Service, but grant us a license to use it to provide\n    and improve the Service.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/sentrial/data-license/sentrial-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Sentrial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- Observability
- Monitoring
- LLM
- Developer Tools
- Tracing
---
