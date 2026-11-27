---
api_specs:
- filename: candor-money-conversations-api-openapi.yml
  format: yaml
  label: Candor Finance Conversations API
  slug: candor-money-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/candor-money/openapi/candor-money-conversations-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: sell, rent, or disclose Candor financial data except as allowed by law and by the user who owns the data
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: Candor returns factual data, query results, deterministic calculations, freshness and coverage information, caveats, source information
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Candor Finance
output_license: custom
provenance_date: '2026-11-09'
provider_name: Candor Finance
provider_slug: candor-money
slug: candor-money-data-license
source_date: '2026-11-09'
source_filename: candor-money-data-license.yml
source_heading: Data License
source_page: https://candor.money/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Candor Finance\naid: candor-money\nurl: https://candor.money/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Candor returns factual data, query results, deterministic calculations, freshness and coverage information,\n    caveats, source information\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: sell, rent, or disclose Candor financial data except as allowed by law and by the user who owns the data\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/candor-money/data-license/candor-money-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Candor Finance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Artificial Intelligence
- Personal Finance
- Budgeting
---
