---
api_specs:
- filename: namegender-account-api-openapi.yml
  format: yaml
  label: NameGender Account API
  slug: namegender-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-account-api-openapi.yml
- filename: namegender-batches-api-openapi.yml
  format: yaml
  label: NameGender Batches API
  slug: namegender-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-batches-api-openapi.yml
- filename: namegender-gender-api-openapi.yml
  format: yaml
  label: NameGender Gender API
  slug: namegender-gender-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-gender-api-openapi.yml
- filename: namegender-webhooks-api-openapi.yml
  format: yaml
  label: NameGender Webhooks API
  slug: namegender-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: Open data and open-source components remain governed by their own licences.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: You may use API results in your lawful internal workflows and customer-facing products, subject to these terms.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: NameGender
output_license: custom
provenance_date: '2026-11-10'
provider_name: NameGender
provider_slug: namegender
slug: namegender-data-license
source_date: '2026-11-10'
source_filename: namegender-data-license.yml
source_heading: Data License
source_page: https://namegender.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: NameGender\naid: namegender\nurl: https://namegender.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: You may use API results in your lawful internal workflows and customer-facing products, subject to these\n    terms.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: Open data and open-source components remain governed by their own licences.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/namegender/data-license/namegender-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from NameGender's own page on 2026-11-10.
synthetic: false
tags:
- Gender
- Name
- Data Enrichment
- Demographics
- Bulk
---
