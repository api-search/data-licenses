---
api_specs:
- filename: sofy-applications-api-openapi.yml
  format: yaml
  label: SOFY Applications API
  slug: sofy-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sofy/openapi/sofy-applications-api-openapi.yml
- filename: sofy-scheduled-runs-api-openapi.yml
  format: yaml
  label: SOFY Scheduled Runs API
  slug: sofy-scheduled-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sofy/openapi/sofy-scheduled-runs-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Customer does not obtain any rights under the Agreement from Quantyzd to the Services or Analytical Results
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: for Customers on any Paid Plans, Customer will own all right, title, and interest in and to the Analytical Results
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: SOFY
output_license: custom
provenance_date: '2026-11-10'
provider_name: SOFY
provider_slug: sofy
slug: sofy-data-license
source_date: '2026-11-10'
source_filename: sofy-data-license.yml
source_heading: Data License
source_page: https://sofy.ai/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: SOFY\naid: sofy\nurl: https://sofy.ai/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: for Customers on any Paid Plans, Customer will own all right, title, and interest in and to the Analytical\n    Results\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Customer does not obtain any rights under the Agreement from Quantyzd to the Services or Analytical Results\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/sofy/data-license/sofy-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from SOFY's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Testing
- Test Automation
- Mobile Testing
- QA
- No-Code
- Continuous Testing
- DevOps
---
