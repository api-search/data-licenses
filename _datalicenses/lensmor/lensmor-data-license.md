---
api_specs:
- filename: lensmor-actions-api-openapi.yml
  format: yaml
  label: Lensmor Actions API
  slug: lensmor-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-actions-api-openapi.yml
- filename: lensmor-contacts-api-openapi.yml
  format: yaml
  label: Lensmor Contacts API
  slug: lensmor-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-contacts-api-openapi.yml
- filename: lensmor-credits-api-openapi.yml
  format: yaml
  label: Lensmor Credits API
  slug: lensmor-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-credits-api-openapi.yml
- filename: lensmor-events-api-openapi.yml
  format: yaml
  label: Lensmor Events API
  slug: lensmor-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-events-api-openapi.yml
- filename: lensmor-exhibitors-api-openapi.yml
  format: yaml
  label: Lensmor Exhibitors API
  slug: lensmor-exhibitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-exhibitors-api-openapi.yml
- filename: lensmor-personnel-api-openapi.yml
  format: yaml
  label: Lensmor Personnel API
  slug: lensmor-personnel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-personnel-api-openapi.yml
- filename: lensmor-profile-matching-api-openapi.yml
  format: yaml
  label: Lensmor Profile Matching API
  slug: lensmor-profile-matching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-profile-matching-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Sell, rent, or lease the data obtained from Lensmor to third parties.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Subject to applicable law and any provider restrictions, you may use Enrichment Results for your internal business purposes.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Lensmor
output_license: custom
provenance_date: '2026-11-09'
provider_name: Lensmor
provider_slug: lensmor
slug: lensmor-data-license
source_date: '2026-11-09'
source_filename: lensmor-data-license.yml
source_heading: Data License
source_page: https://www.lensmor.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Lensmor\naid: lensmor\nurl: https://www.lensmor.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Subject to applicable law and any provider restrictions, you may use Enrichment Results for your internal\n    business purposes.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Sell, rent, or lease the data obtained from Lensmor to third parties.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/lensmor/data-license/lensmor-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Lensmor's own page on 2026-11-09.
synthetic: false
tags:
- Event Intelligence
- B2B
- Software-as-a-Service
- Lead Generation
- Trade Shows
---
