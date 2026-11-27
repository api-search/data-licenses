---
api_specs:
- filename: andel-purchases-api-openapi.yml
  format: yaml
  label: Andel Purchases API
  slug: andel-purchases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/andel/openapi/andel-purchases-api-openapi.yml
- filename: andel-webhooks-api-openapi.yml
  format: yaml
  label: Andel Webhooks API
  slug: andel-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/andel/openapi/andel-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: prohibited
    text: Users shall not distribute or otherwise commercialize Our Property.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: prohibited
    text: Users shall not distribute or otherwise commercialize Our Property.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Andel
output_license: null
provenance_date: '2026-11-09'
provider_name: Andel
provider_slug: andel
slug: andel-data-license
source_date: '2026-11-09'
source_filename: andel-data-license.yml
source_heading: Data License
source_page: https://www.andel.org/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Andel\naid: andel\nurl: https://www.andel.org/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: null\n  stance_commercial: prohibited\n  text: Users shall not distribute or otherwise commercialize Our Property.\ndata:\n  license: null\n  stance_commercial: prohibited\n  text: Users shall not distribute or otherwise commercialize Our Property.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/andel/data-license/andel-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Andel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- Pharmacy Benefits
- Drug Pricing
- Specialty Medications
- Data Exchange
- Webhook
---
