---
api_specs:
- filename: riskified-automation-endpoints-api-openapi.yml
  format: yaml
  label: Riskified Automation Endpoints API
  slug: riskified-automation-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-automation-endpoints-api-openapi.yml
- filename: riskified-customer-actions-api-openapi.yml
  format: yaml
  label: Riskified Customer Actions API
  slug: riskified-customer-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-customer-actions-api-openapi.yml
- filename: riskified-customer-management-api-openapi.yml
  format: yaml
  label: Riskified Customer Management API
  slug: riskified-customer-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-customer-management-api-openapi.yml
- filename: riskified-order-pre-auth-review-and-psd2-3ds-cvv-recommendations-api-openapi.yml
  format: yaml
  label: Riskified Order Pre-Auth Review and PSD2/3DS/CVV Recommendations API
  slug: riskified-order-pre-auth-review-and-psd2-3ds-cvv-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-order-pre-auth-review-and-psd2-3ds-cvv-recommendations-api-openapi.yml
- filename: riskified-otp-recover-sync-flow-api-openapi.yml
  format: yaml
  label: Riskified OTP Recover (Sync flow) API
  slug: riskified-otp-recover-sync-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-otp-recover-sync-flow-api-openapi.yml
- filename: riskified-post-authorization-flow-api-openapi.yml
  format: yaml
  label: Riskified Post-Authorization Flow API
  slug: riskified-post-authorization-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-post-authorization-flow-api-openapi.yml
- filename: riskified-pre-authorization-flow-api-openapi.yml
  format: yaml
  label: Riskified Pre-Authorization Flow API
  slug: riskified-pre-authorization-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-pre-authorization-flow-api-openapi.yml
- filename: riskified-refunds-api-openapi.yml
  format: yaml
  label: Riskified Refunds API
  slug: riskified-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-refunds-api-openapi.yml
- filename: riskified-returns-api-openapi.yml
  format: yaml
  label: Riskified Returns API
  slug: riskified-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-returns-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: allowed
    text: Client consents to and grants Riskified and its Affiliates the worldwide, non-exclusive, royalty-free, perpetual, sub-licensable, fully-paid-up, and irrevocable, right to
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: (ii) transfer, sell, rent, lease or share the Services or the results, including recommendations
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Riskified
output_license: custom
provenance_date: '2026-11-10'
provider_name: Riskified
provider_slug: riskified
slug: riskified-data-license
source_date: '2026-11-10'
source_filename: riskified-data-license.yml
source_heading: Data License
source_page: https://www.riskified.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Riskified\naid: riskified\nurl: https://www.riskified.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: (ii) transfer, sell, rent, lease or share the Services or the results, including recommendations\ndata:\n  license: custom\n  stance_commercial: allowed\n  text: Client consents to and grants Riskified and its Affiliates the worldwide, non-exclusive, royalty-free, perpetual,\n    sub-licensable, fully-paid-up, and irrevocable, right to\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/riskified/data-license/riskified-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Riskified's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- Chargebacks
- E-Commerce
- Payments
- Risk Management
- Machine Learning
- Account Takeover
- Policy Abuse
- 3D
- PSD2
- Returns
---
