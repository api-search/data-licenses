---
api_specs:
- filename: prereason-com-agent-access-api-openapi.yml
  format: yaml
  label: prereason-com Agent access API
  slug: prereason-com-agent-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-agent-access-api-openapi.yml
- filename: prereason-com-company-briefings-api-openapi.yml
  format: yaml
  label: prereason-com Company Briefings API
  slug: prereason-com-company-briefings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-company-briefings-api-openapi.yml
- filename: prereason-com-context-api-openapi.yml
  format: yaml
  label: prereason-com Context API
  slug: prereason-com-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-context-api-openapi.yml
- filename: prereason-com-metrics-api-openapi.yml
  format: yaml
  label: prereason-com Metrics API
  slug: prereason-com-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-metrics-api-openapi.yml
- filename: prereason-com-short-urls-api-openapi.yml
  format: yaml
  label: prereason-com Short URLs API
  slug: prereason-com-short-urls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-short-urls-api-openapi.yml
- filename: prereason-com-system-api-openapi.yml
  format: yaml
  label: prereason-com System API
  slug: prereason-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-system-api-openapi.yml
- filename: prereason-com-treasury-holdings-api-openapi.yml
  format: yaml
  label: prereason-com Treasury Holdings API
  slug: prereason-com-treasury-holdings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-treasury-holdings-api-openapi.yml
- filename: prereason-com-webhooks-api-openapi.yml
  format: yaml
  label: prereason-com Webhooks API
  slug: prereason-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: When displaying data obtained through the Service in public-facing applications, you must provide reasonable attribution to PreReason.
  data:
    license: custom
    stance_commercial: unstated
    text: you may not claim ownership of the underlying data or the Service itself.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: A Business subscription includes a licence, while it is active, to show PreReason's output (briefings, metrics or parts of them) to the users of a product you own and operate.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: prereason-com
output_license: custom
provenance_date: '2026-11-10'
provider_name: prereason-com
provider_slug: prereason-com
slug: prereason-com-data-license
source_date: '2026-11-10'
source_filename: prereason-com-data-license.yml
source_heading: Data License
source_page: https://www.prereason.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: prereason-com\naid: prereason-com\nurl: https://www.prereason.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: A Business subscription includes a licence, while it is active, to show PreReason's output (briefings, metrics\n    or parts of them) to the users of a product you own and operate.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: you may not claim ownership of the underlying data or the Service itself.\nattribution:\n  required: true\n  text: When displaying data obtained through the Service in public-facing applications, you\
  \ must provide reasonable\n    attribution to PreReason.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/prereason-com/data-license/prereason-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from prereason-com's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Markets
- Artificial Intelligence
- Data
- MCP
---
