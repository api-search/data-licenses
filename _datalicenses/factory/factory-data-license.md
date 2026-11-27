---
api_specs:
- filename: factory-automations-api-openapi.yml
  format: yaml
  label: Factory Automations API
  slug: factory-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factory/openapi/factory-automations-api-openapi.yml
- filename: factory-computers-api-openapi.yml
  format: yaml
  label: Factory Computers API
  slug: factory-computers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factory/openapi/factory-computers-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: Factory may (i) internally use and modify (but not disclose) Customer Data for the purposes of (A) providing the Service to Customer and (B) generating Aggregated De-Identified Data
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: As between the parties, (i) Customer retains all right, title and interest in and to the Customer Data (as defined below) and Customer Outputs (as defined below)
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Factory
output_license: custom
provenance_date: '2026-11-09'
provider_name: Factory
provider_slug: factory
slug: factory-data-license
source_date: '2026-11-09'
source_filename: factory-data-license.yml
source_heading: Data License
source_page: https://factory.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Factory\naid: factory\nurl: https://factory.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: As between the parties, (i) Customer retains all right, title and interest in and to the Customer Data (as\n    defined below) and Customer Outputs (as defined below)\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: Factory may (i) internally use and modify (but not disclose) Customer Data for the purposes of (A) providing\n    the Service to Customer and (B) generating Aggregated De-Identified Data\nattribution:\n  required: null\n  text: null\n\
  interface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/factory/data-license/factory-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Factory's own page on 2026-11-09.
synthetic: false
tags:
- Manufacturing
- Software-as-a-Service
- Cloud
- Automation
- Supply Chain
- Company
---
