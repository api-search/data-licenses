---
api_specs:
- filename: kaiko-canton-oracle-api-openapi.yml
  format: yaml
  label: Kaiko Canton Oracle API
  slug: kaiko-canton-oracle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-canton-oracle-api-openapi.yml
- filename: kaiko-index-reference-data-api-openapi.yml
  format: yaml
  label: Kaiko Index Reference Data API
  slug: kaiko-index-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-index-reference-data-api-openapi.yml
- filename: kaiko-indices-api-openapi.yml
  format: yaml
  label: Kaiko Indices API
  slug: kaiko-indices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-indices-api-openapi.yml
- filename: kaiko-supply-api-openapi.yml
  format: yaml
  label: Kaiko Supply API
  slug: kaiko-supply-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiko/openapi/kaiko-supply-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: any permitted display of the Data by Client shall credit, Supplier or any other source of the Data specified by Supplier as the source.
  data:
    license: custom
    stance_commercial: conditional
    text: non-exclusive, non-transferable, worldwide, limited license to “Use” certain Supplier data products and materials
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: To the extent, Client seeks to commercialize any derived works into a client-facing product, Client shall contact Supplier to seek consent and execute additional terms and conditions.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Kaiko
output_license: custom
provenance_date: '2026-11-09'
provider_name: Kaiko
provider_slug: kaiko
slug: kaiko-data-license
source_date: '2026-11-09'
source_filename: kaiko-data-license.yml
source_heading: Data License
source_page: https://www.kaiko.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Kaiko\naid: kaiko\nurl: https://www.kaiko.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: To the extent, Client seeks to commercialize any derived works into a client-facing product, Client shall\n    contact Supplier to seek consent and execute additional terms and conditions.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: non-exclusive, non-transferable, worldwide, limited license to “Use” certain Supplier data products and\n    materials\nattribution:\n  required: true\n  text: any permitted display of the Data by Client shall\
  \ credit, Supplier or any other source of the Data specified\n    by Supplier as the source.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/kaiko/data-license/kaiko-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Kaiko's own page on 2026-11-09.
synthetic: false
tags:
- Web3
- Cryptocurrency
- Market Data
- Institutional
- Foreign Exchange
- Indices
- Onchain
- Streaming
---
