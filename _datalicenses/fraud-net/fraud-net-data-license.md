---
api_specs:
- filename: fraud-net-banking-fintech-api-openapi.yml
  format: yaml
  label: Fraud.net Banking / Fintech API
  slug: fraud-net-banking-fintech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fraud-net/openapi/fraud-net-banking-fintech-api-openapi.yml
- filename: fraud-net-commerce-api-openapi.yml
  format: yaml
  label: Fraud.net Commerce API
  slug: fraud-net-commerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fraud-net/openapi/fraud-net-commerce-api-openapi.yml
- filename: fraud-net-identity-api-openapi.yml
  format: yaml
  label: Fraud.net Identity API
  slug: fraud-net-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fraud-net/openapi/fraud-net-identity-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: You agree not to license, rent, sell, lease, transfer, assign, distribute, display, host, outsource, disclose, or otherwise commercially exploit or make the Fraud.net Services available to any third party
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: You are not permitted to copy, reproduce, distribute, republish, display, post or transmit, in any form or by any means, any part of the Fraud.net Services, including the Analytical Results.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Fraud.net
output_license: custom
provenance_date: '2026-11-09'
provider_name: Fraud.net
provider_slug: fraud-net
slug: fraud-net-data-license
source_date: '2026-11-09'
source_filename: fraud-net-data-license.yml
source_heading: Data License
source_page: https://www.fraud.net/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Fraud.net\naid: fraud-net\nurl: https://www.fraud.net/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: You are not permitted to copy, reproduce, distribute, republish, display, post or transmit, in any form\n    or by any means, any part of the Fraud.net Services, including the Analytical Results.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You agree not to license, rent, sell, lease, transfer, assign, distribute, display, host, outsource, disclose,\n    or otherwise commercially exploit or make the Fraud.net Services available\
  \ to any third party\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/fraud-net/data-license/fraud-net-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Fraud.net's own page on 2026-11-09.
synthetic: false
tags:
- Fraud Prevention
- Risk Management
- Commerce
- Payments
- Security
- Compliance
- Identity
- Banking
- Machine Learning
---
