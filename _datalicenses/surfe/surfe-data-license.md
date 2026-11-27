---
api_specs:
- filename: surfe-account-api-openapi.yml
  format: yaml
  label: Surfe Account API
  slug: surfe-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-account-api-openapi.yml
- filename: surfe-companies-api-openapi.yml
  format: yaml
  label: Surfe Companies API
  slug: surfe-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-companies-api-openapi.yml
- filename: surfe-people-api-openapi.yml
  format: yaml
  label: Surfe People API
  slug: surfe-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-people-api-openapi.yml
- filename: surfe-recommendations-api-openapi.yml
  format: yaml
  label: Surfe Recommendations API
  slug: surfe-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-recommendations-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: You are granted a non-exclusive license right to host and use the business contact data provided by Surfe in connection with the Services for internal business purposes exclusively.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: you shall not resell, sublicense, distribute or otherwise communicate said data to any third-party without the express written consent of Surfe.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Surfe
output_license: custom
provenance_date: '2026-11-10'
provider_name: Surfe
provider_slug: surfe
slug: surfe-data-license
source_date: '2026-11-10'
source_filename: surfe-data-license.yml
source_heading: Data License
source_page: https://www.surfe.com/terms-and-conditions-api
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Surfe\naid: surfe\nurl: https://www.surfe.com/terms-and-conditions-api\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: you shall not resell, sublicense, distribute or otherwise communicate said data to any third-party without\n    the express written consent of Surfe.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You are granted a non-exclusive license right to host and use the business contact data provided by Surfe\n    in connection with the Services for internal business purposes exclusively.\nattribution:\n  required: null\n  text:\
  \ null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/surfe/data-license/surfe-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Surfe's own page on 2026-11-10.
synthetic: false
tags:
- B2B Data
- Contact Data
- Sales Intelligence
- Data Enrichment
- Lead Generation
- CRM
- Prospecting
---
