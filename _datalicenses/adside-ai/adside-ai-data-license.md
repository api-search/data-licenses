---
api_specs:
- filename: adside-ai-openapi.yaml
  format: yaml
  label: Multi-Source Ads API
  slug: multi-source-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adside-ai/openapi/adside-ai-openapi.yaml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: you grant Adside a limited, non-exclusive, worldwide license to use, process, and display your Customer Data solely to provide and improve the Service for your account.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: You retain all rights to the Customer Data you upload or create through the Service.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Adside
output_license: null
provenance_date: '2026-11-09'
provider_name: Adside
provider_slug: adside-ai
slug: adside-ai-data-license
source_date: '2026-11-09'
source_filename: adside-ai-data-license.yml
source_heading: Data License
source_page: https://www.adside.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Adside\naid: adside-ai\nurl: https://www.adside.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: You retain all rights to the Customer Data you upload or create through the Service.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: you grant Adside a limited, non-exclusive, worldwide license to use, process, and display your Customer\n    Data solely to provide and improve the Service for your account.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/adside-ai/data-license/adside-ai-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Adside's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Artificial Intelligence
- Marketing
- Software-as-a-Service
- Automation
---
