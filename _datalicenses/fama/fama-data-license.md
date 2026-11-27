---
api_specs:
- filename: fama-public-endpoints-api-openapi.yml
  format: yaml
  label: Fama Public Endpoints API
  slug: fama-public-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fama/openapi/fama-public-endpoints-api-openapi.yml
- filename: fama-publicapi-api-openapi.yml
  format: yaml
  label: Fama Public API
  slug: fama-publicapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fama/openapi/fama-publicapi-api-openapi.yml
- filename: fama-report-api-openapi.yml
  format: yaml
  label: Fama Report API
  slug: fama-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fama/openapi/fama-report-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Customer grants to Company a non-exclusive license, during the term of this Agreement, to use Data for the purposes of performing its obligations under this Agreement.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: conditional
    text: Company grants to Customer a nonexclusive, personal and nontransferable license, during the term of this Agreement, to allow its Authorized Users to access and use the Company Service on its behalf solely for Customer’s internal use
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Fama
output_license: null
provenance_date: '2026-11-09'
provider_name: Fama
provider_slug: fama
slug: fama-data-license
source_date: '2026-11-09'
source_filename: fama-data-license.yml
source_heading: Data License
source_page: https://fama.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Fama\naid: fama\nurl: https://fama.io/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: conditional\n  text: Company grants to Customer a nonexclusive, personal and nontransferable license, during the term of this\n    Agreement, to allow its Authorized Users to access and use the Company Service on its behalf solely for Customer’s\n    internal use\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Customer grants to Company a non-exclusive license, during the term of this Agreement, to use Data for the\n    purposes of performing its obligations\
  \ under this Agreement.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/fama/data-license/fama-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Fama's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Employment Screening
- Background Checks
- Human Resources
- Social Media
- Risk Management
- Compliance
- Artificial Intelligence
---
