---
api_specs:
- filename: overview
  format: yaml
  label: Tracxn API
  slug: tracxn-api
  spec_type: Postman
  url: https://www.postman.com/tracxnapi/tracxn-api/overview
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: is properly attributed
  data:
    license: custom
    stance_commercial: prohibited
    text: Copying, modifying, or commercially exploiting any part of the Platform is not permitted.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: All usage must be for internal business purposes only.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Tracxn
output_license: custom
provenance_date: '2026-11-10'
provider_name: Tracxn
provider_slug: tracxn
slug: tracxn-data-license
source_date: '2026-11-10'
source_filename: tracxn-data-license.yml
source_heading: Data License
source_page: https://tracxn.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Tracxn\naid: tracxn\nurl: https://tracxn.com/termsofuse\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: All usage must be for internal business purposes only.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Copying, modifying, or commercially exploiting any part of the Platform is not permitted.\nattribution:\n  required: true\n  text: is properly attributed\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/tracxn/data-license/tracxn-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Tracxn's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Market Intelligence
- Private Markets
- Venture Capital
- Startups
- Company Data
- Investor
- Funding
---
