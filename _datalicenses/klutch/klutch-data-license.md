---
api_specs:
- filename: postman.yaml
  format: yaml
  label: Klutch Public API
  slug: klutch-public-api
  spec_type: Postman
  url: https://api-docs.klutchcard.com/
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
    text: You will not act as a payment facilitator or otherwise resell the Payment Services to any third party.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Klutch
output_license: custom
provenance_date: '2026-11-09'
provider_name: Klutch
provider_slug: klutch
slug: klutch-data-license
source_date: '2026-11-09'
source_filename: klutch-data-license.yml
source_heading: Data License
source_page: https://www.klutchcard.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Klutch\naid: klutch\nurl: https://www.klutchcard.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: You will not act as a payment facilitator or otherwise resell the Payment Services to any third party.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/klutch/data-license/klutch-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from Klutch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Credit Cards
- Payments
- Card Issuing
- Virtual Cards
- Transaction
- Spend Management
- Personal Finance
- GraphQL
- Embedded Finance
- Agents
---
