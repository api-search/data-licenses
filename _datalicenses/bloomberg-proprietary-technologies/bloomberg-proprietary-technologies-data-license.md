---
api_specs:
- filename: openapi.json
  format: json
  label: Bloomberg FIGI API
  slug: figi-api
  spec_type: OpenAPI
  url: https://api.openfigi.com/schema/openapi.json
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
    text: Such download is licensed to you by Bloomberg ONLY for your own personal, noncommercial use in accordance with the TOS
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Bloomberg Proprietary Technologies
output_license: custom
provenance_date: '2026-11-09'
provider_name: Bloomberg Proprietary Technologies
provider_slug: bloomberg-proprietary-technologies
slug: bloomberg-proprietary-technologies-data-license
source_date: '2026-11-09'
source_filename: bloomberg-proprietary-technologies-data-license.yml
source_heading: Data License
source_page: https://www.bloomberg.com/notices/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Bloomberg Proprietary Technologies\naid: bloomberg-proprietary-technologies\nurl: https://www.bloomberg.com/notices/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: Such download is licensed to you by Bloomberg ONLY for your own personal, noncommercial use in accordance\n    with the TOS\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/bloomberg-proprietary-technologies/data-license/bloomberg-proprietary-technologies-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from Bloomberg Proprietary Technologies's own page on 2026-11-09.
synthetic: false
tags:
- Proprietary Technology
- BLPAPI
- BQL
- FIGI
- B-PIPE
- Financial Technology
- Bloomberg
---
