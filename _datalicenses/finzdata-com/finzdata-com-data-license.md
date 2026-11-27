---
api_specs:
- filename: finzdata-com-finzdata-api-openapi.yml
  format: yaml
  label: FinzData API
  slug: finzdata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finzdata-com/openapi/finzdata-com-finzdata-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Licensed third-party series carry their owner's source credit in each download and must keep it.
  data:
    license: custom
    stance_commercial: conditional
    text: Use for, or on behalf of, any business, fund, firm or employer is commercial use and needs the Institutional plan.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You may create your own analysis, research, charts, models, signals and trading decisions from the data, and share those results, provided the data cannot reasonably be extracted or reconstructed from what you share.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: FinzData
output_license: custom
provenance_date: '2026-11-09'
provider_name: FinzData
provider_slug: finzdata-com
slug: finzdata-com-data-license
source_date: '2026-11-09'
source_filename: finzdata-com-data-license.yml
source_heading: Data License
source_page: https://finzdata.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: FinzData\naid: finzdata-com\nurl: https://finzdata.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You may create your own analysis, research, charts, models, signals and trading decisions from the data,\n    and share those results, provided the data cannot reasonably be extracted or reconstructed from what you share.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Use for, or on behalf of, any business, fund, firm or employer is commercial use and needs the Institutional\n    plan.\nattribution:\n  required: true\n  text: Licensed\
  \ third-party series carry their owner's source credit in each download and must keep it.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/finzdata-com/data-license/finzdata-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from FinzData's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- Historical Data
- Python
---
