---
api_specs:
- filename: garner-facilities-api-openapi.yml
  format: yaml
  label: Garner Facilities API
  slug: garner-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-facilities-api-openapi.yml
- filename: garner-professionals-api-openapi.yml
  format: yaml
  label: Garner Professionals API
  slug: garner-professionals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-professionals-api-openapi.yml
- filename: garner-provider-annotations-api-openapi.yml
  format: yaml
  label: Garner Provider Annotations API
  slug: garner-provider-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-provider-annotations-api-openapi.yml
- filename: garner-providers-api-openapi.yml
  format: yaml
  label: Garner Providers API
  slug: garner-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-providers-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: null
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: The Service is solely for your personal, non-commercial use.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Garner
output_license: custom
provenance_date: '2026-11-09'
provider_name: Garner
provider_slug: garner
slug: garner-data-license
source_date: '2026-11-09'
source_filename: garner-data-license.yml
source_heading: Data License
source_page: https://garnerhealth.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Garner\naid: garner\nurl: https://garnerhealth.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: The Service is solely for your personal, non-commercial use.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/garner/data-license/garner-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from Garner's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Healthcare
- Provider Data
- Care Navigation
- Health Insurance
- Claims Analytics
- Provider Search
- Doctor Quality
---
