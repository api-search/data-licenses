---
api_specs:
- filename: opensanctions-data-access-api-openapi.yml
  format: yaml
  label: OpenSanctions Data access API
  slug: opensanctions-data-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-data-access-api-openapi.yml
- filename: opensanctions-matching-api-openapi.yml
  format: yaml
  label: OpenSanctions Matching API
  slug: opensanctions-matching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-matching-api-openapi.yml
- filename: opensanctions-reconciliation-api-openapi.yml
  format: yaml
  label: OpenSanctions Reconciliation API
  slug: opensanctions-reconciliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-reconciliation-api-openapi.yml
- filename: opensanctions-system-information-api-openapi.yml
  format: yaml
  label: OpenSanctions System information API
  slug: opensanctions-system-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-system-information-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: CC-BY-NC-4.0
    stance_commercial: prohibited
    text: The data is licensed under the terms of Creative Commons 4.0 Attribution NonCommercial
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
name: OpenSanctions
output_license: null
provenance_date: '2026-11-10'
provider_name: OpenSanctions
provider_slug: opensanctions
slug: opensanctions-data-license
source_date: '2026-11-10'
source_filename: opensanctions-data-license.yml
source_heading: Data License
source_page: https://www.opensanctions.org/docs/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: OpenSanctions\naid: opensanctions\nurl: https://www.opensanctions.org/docs/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: CC-BY-NC-4.0\n  stance_commercial: prohibited\n  text: The data is licensed under the terms of Creative Commons 4.0 Attribution NonCommercial\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/opensanctions/data-license/opensanctions-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from OpenSanctions's own page on 2026-11-10.
synthetic: false
tags:
- Sanctions Screening
- AML
- Politically Exposed Persons
- Compliance
- Financial Crime
- KYC
- Entity Resolution
- Open Data
- Risk Data
- Due Diligence
- Public APIs
- Agent-Native
---
