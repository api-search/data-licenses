---
api_specs:
- filename: zenlytic-embedding-api-openapi.yml
  format: yaml
  label: Zenlytic Embedding API
  slug: zenlytic-embedding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenlytic/openapi/zenlytic-embedding-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: By making Content available to the Service, you grant Zenlytic a worldwide, royalty-free, and non-exclusive license to reproduce, view, and use the Content for the purpose of providing the Service to you
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: Customer owns all right, title and interest in and to its Content, the Configurations, and the Output
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Zenlytic
output_license: custom
provenance_date: '2026-11-10'
provider_name: Zenlytic
provider_slug: zenlytic
slug: zenlytic-data-license
source_date: '2026-11-10'
source_filename: zenlytic-data-license.yml
source_heading: Data License
source_page: https://docs.zenlytic.com/legal-and-support/legal/terms-of-service-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Zenlytic\naid: zenlytic\nurl: https://docs.zenlytic.com/legal-and-support/legal/terms-of-service-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Customer owns all right, title and interest in and to its Content, the Configurations, and the Output\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: By making Content available to the Service, you grant Zenlytic a worldwide, royalty-free, and non-exclusive\n    license to reproduce, view, and use the Content for the purpose of providing the Service to you\nattribution:\n  required: null\n\
  \  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/zenlytic/data-license/zenlytic-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Zenlytic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- Business Intelligence
- Analytics
- Artificial Intelligence
- Data
- Embedded Analytics
- MCP
---
