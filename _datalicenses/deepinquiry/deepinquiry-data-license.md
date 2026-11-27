---
api_specs:
- filename: deepinquiry-facts-api-openapi.yml
  format: yaml
  label: DeepInquiry Verified Facts API (Machine Accountability Corp) Facts API
  slug: deepinquiry-facts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepinquiry/openapi/deepinquiry-facts-api-openapi.yml
- filename: deepinquiry-search-api-openapi.yml
  format: yaml
  label: DeepInquiry Verified Facts API (Machine Accountability Corp) Search API
  slug: deepinquiry-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepinquiry/openapi/deepinquiry-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: You must not remove, alter, or obscure the citations that we attach to each fact, and you must not misrepresent the source or verification status of any fact.
  data:
    license: custom
    stance_commercial: conditional
    text: Except for the license in Section 4.1, no rights are granted to you by implication, estoppel, or otherwise.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: use and display Content returned to you in your own products and services
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: DeepInquiry Verified Facts API (Machine Accountability Corp)
output_license: custom
provenance_date: '2026-11-09'
provider_name: DeepInquiry Verified Facts API (Machine Accountability Corp)
provider_slug: deepinquiry
slug: deepinquiry-data-license
source_date: '2026-11-09'
source_filename: deepinquiry-data-license.yml
source_heading: Data License
source_page: https://www.deepinquiry.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: DeepInquiry Verified Facts API (Machine Accountability Corp)\naid: deepinquiry\nurl: https://www.deepinquiry.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: use and display Content returned to you in your own products and services\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Except for the license in Section 4.1, no rights are granted to you by implication, estoppel, or otherwise.\nattribution:\n  required: true\n  text: You must not remove, alter, or obscure the citations that we attach to each fact, and you must not misrepresent\n\
  \    the source or verification status of any fact.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/deepinquiry/data-license/deepinquiry-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from DeepInquiry Verified Facts API (Machine Accountability Corp)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Facts
- Verification
- Data
---
