---
api_specs:
- filename: tindie-order-api-openapi.yml
  format: yaml
  label: Tindie Order API
  slug: tindie-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tindie/openapi/tindie-order-api-openapi.yml
- filename: tindie-orderitem-api-openapi.yml
  format: yaml
  label: Tindie Orderitem API
  slug: tindie-orderitem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tindie/openapi/tindie-orderitem-api-openapi.yml
- filename: tindie-product-api-openapi.yml
  format: yaml
  label: Tindie Product API
  slug: tindie-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tindie/openapi/tindie-product-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: By posting content on Tindie, you grant Tindie a worldwide, non-exclusive, royalty-free license to host, reproduce, format, display, distribute, and promote that content for operating and marketing Tindie.
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
name: Tindie
output_license: null
provenance_date: '2026-11-10'
provider_name: Tindie
provider_slug: tindie
slug: tindie-data-license
source_date: '2026-11-10'
source_filename: tindie-data-license.yml
source_heading: Data License
source_page: https://www.tindie.com/about/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Tindie\naid: tindie\nurl: https://www.tindie.com/about/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: By posting content on Tindie, you grant Tindie a worldwide, non-exclusive, royalty-free license to host,\n    reproduce, format, display, distribute, and promote that content for operating and marketing Tindie.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/tindie/data-license/tindie-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Tindie's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Hardware
- Electronics
- Maker
- E-Commerce
- Open Source Hardware
- Order
---
