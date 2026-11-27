---
api_specs:
- filename: quantsonar-com-default-api-openapi.yml
  format: yaml
  label: quantsonar-com 分红送股 API
  slug: quantsonar-com-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quantsonar-com/openapi/quantsonar-com-default-api-openapi.yml
- filename: quantsonar-com-etf-api-openapi.yml
  format: yaml
  label: quantsonar-com ETF API
  slug: quantsonar-com-etf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quantsonar-com/openapi/quantsonar-com-etf-api-openapi.yml
- filename: quantsonar-com-health-api-openapi.yml
  format: yaml
  label: quantsonar-com Health API
  slug: quantsonar-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quantsonar-com/openapi/quantsonar-com-health-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: FREE, PRO and Expert license the individual subscriber to use retrieved data for non-commercial study, research, backtests and personal tools.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Companies, institutions and other organisations using data in internal commercial systems, business operations or client deliverables must purchase Business and restrict access to the authorised team named in the order.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: quantsonar-com
output_license: custom
provenance_date: '2026-11-10'
provider_name: quantsonar-com
provider_slug: quantsonar-com
slug: quantsonar-com-data-license
source_date: '2026-11-10'
source_filename: quantsonar-com-data-license.yml
source_heading: Data License
source_page: https://quantsonar.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: quantsonar-com\naid: quantsonar-com\nurl: https://quantsonar.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Companies, institutions and other organisations using data in internal commercial systems, business operations\n    or client deliverables must purchase Business and restrict access to the authorised team named in the order.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: FREE, PRO and Expert license the individual subscriber to use retrieved data for non-commercial study, research,\n    backtests and personal tools.\n\
  attribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/quantsonar-com/data-license/quantsonar-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from quantsonar-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Data
- China
- Stock Market
---
