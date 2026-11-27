---
api_specs:
- filename: prometeo-account-validation-api-openapi.yml
  format: yaml
  label: Prometeo Account Validation API
  slug: prometeo-account-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prometeo/openapi/prometeo-account-validation-api-openapi.yml
- filename: prometeo-banking-api-openapi.yml
  format: yaml
  label: Prometeo Banking API
  slug: prometeo-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prometeo/openapi/prometeo-banking-api-openapi.yml
- filename: prometeo-cross-border-api-openapi.yml
  format: yaml
  label: Prometeo Cross-Border API
  slug: prometeo-cross-border-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prometeo/openapi/prometeo-cross-border-api-openapi.yml
- filename: prometeo-identity-api-openapi.yml
  format: yaml
  label: Prometeo Identity API
  slug: prometeo-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prometeo/openapi/prometeo-identity-api-openapi.yml
- filename: prometeo-payment-api-openapi.yml
  format: yaml
  label: Prometeo Payment API
  slug: prometeo-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prometeo/openapi/prometeo-payment-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: The Customer can’t share, resell, or distribute any data from the Services to third parties unless we give written permission in advance.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: conditional
    text: The data services may be used solely for the purpose of validating bank account details of payees or beneficiaries in connection with payments or transfers to be made by the Customer.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Prometeo
output_license: null
provenance_date: '2026-11-10'
provider_name: Prometeo
provider_slug: prometeo
slug: prometeo-data-license
source_date: '2026-11-10'
source_filename: prometeo-data-license.yml
source_heading: Data License
source_page: https://prometeoapi.com/en/legal/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Prometeo\naid: prometeo\nurl: https://prometeoapi.com/en/legal/msa\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: conditional\n  text: The data services may be used solely for the purpose of validating bank account details of payees or beneficiaries\n    in connection with payments or transfers to be made by the Customer.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: The Customer can’t share, resell, or distribute any data from the Services to third parties unless we give\n    written permission in advance.\nattribution:\n  required: null\n  text: null\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/prometeo/data-license/prometeo-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Prometeo's own page on 2026-11-10.
synthetic: false
tags:
- Open Banking
- Payments
- Fintech
- Latin America
- Financial Data
- Account Validation
- Cross-Border
---
