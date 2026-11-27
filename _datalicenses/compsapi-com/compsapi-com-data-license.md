---
api_specs:
- filename: compsapi-com-comps-api-openapi.yml
  format: yaml
  label: compsapi-com Comps API
  slug: compsapi-com-comps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsapi-com/openapi/compsapi-com-comps-api-openapi.yml
- filename: compsapi-com-health-api-openapi.yml
  format: yaml
  label: compsapi-com Health API
  slug: compsapi-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsapi-com/openapi/compsapi-com-health-api-openapi.yml
- filename: compsapi-com-sold-api-openapi.yml
  format: yaml
  label: compsapi-com Sold API
  slug: compsapi-com-sold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsapi-com/openapi/compsapi-com-sold-api-openapi.yml
- filename: compsapi-com-usage-api-openapi.yml
  format: yaml
  label: compsapi-com Usage API
  slug: compsapi-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsapi-com/openapi/compsapi-com-usage-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: false
    text: We do not require you to credit CompsAPI.
  data:
    license: custom
    stance_commercial: conditional
    text: Do not redistribute raw sold listings data in bulk as a dataset, a feed or an API, whether served live or from your own storage.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: display it inside your own product, including per item sale history and customer facing portfolio or collection views. Statistics and valuations you derive from it are yours.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: compsapi-com
output_license: custom
provenance_date: '2026-11-09'
provider_name: compsapi-com
provider_slug: compsapi-com
slug: compsapi-com-data-license
source_date: '2026-11-09'
source_filename: compsapi-com-data-license.yml
source_heading: Data License
source_page: https://compsapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: compsapi-com\naid: compsapi-com\nurl: https://compsapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: display it inside your own product, including per item sale history and customer facing portfolio or collection\n    views. Statistics and valuations you derive from it are yours.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Do not redistribute raw sold listings data in bulk as a dataset, a feed or an API, whether served live or\n    from your own storage.\nattribution:\n  required: false\n  text: We do not require you to credit\
  \ CompsAPI.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/compsapi-com/data-license/compsapi-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from compsapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- eBay
- Data
- Pricing
- Marketplace
---
