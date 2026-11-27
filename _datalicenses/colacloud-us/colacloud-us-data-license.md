---
api_specs:
- filename: colacloud-us-colas-api-openapi.yml
  format: yaml
  label: COLA Cloud COLAs API
  slug: colacloud-us-colas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/colacloud-us/openapi/colacloud-us-colas-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: null
    text: Where reasonable in customer-facing displays, reports, or approved External Use, we may require attribution such as "Data powered by COLA Cloud" or similar language.
  data:
    license: custom
    stance_commercial: conditional
    text: Bulk Data access, large-scale exports, warehouse shares, customer-specific datasets, redistribution rights, public display rights, sublicensing rights, and competing-product carveouts require a separate signed Data License Agreement, order form, or written addendum unless expressly included in your plan.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Unless your plan or a signed agreement says otherwise, you may make limited External Use of COLA Cloud Output when the use is incidental to your product or workflow and does not expose COLA Cloud as a substitute data service.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: COLA Cloud
output_license: custom
provenance_date: '2026-11-09'
provider_name: COLA Cloud
provider_slug: colacloud-us
slug: colacloud-us-data-license
source_date: '2026-11-09'
source_filename: colacloud-us-data-license.yml
source_heading: Data License
source_page: https://colacloud.us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: COLA Cloud\naid: colacloud-us\nurl: https://colacloud.us/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Unless your plan or a signed agreement says otherwise, you may make limited External Use of COLA Cloud Output\n    when the use is incidental to your product or workflow and does not expose COLA Cloud as a substitute data service.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Bulk Data access, large-scale exports, warehouse shares, customer-specific datasets, redistribution rights,\n    public display rights, sublicensing rights,\
  \ and competing-product carveouts require a separate signed Data License\n    Agreement, order form, or written addendum unless expressly included in your plan.\nattribution:\n  required: null\n  text: Where reasonable in customer-facing displays, reports, or approved External Use, we may require attribution\n    such as \"Data powered by COLA Cloud\" or similar language.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/colacloud-us/data-license/colacloud-us-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from COLA Cloud's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Alcohol
- Compliance
- Open Data
---
