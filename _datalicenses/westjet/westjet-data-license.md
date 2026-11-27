---
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: prohibited
    text: Unless otherwise approved in writing by WestJet, an Agent shall not redistribute, share or in any other manner, make any of WestJet Inventory available to any 3rd party
  interface_license:
    url: null
  outputs:
    license: custom
    source: https://www.westjet.com/en-ca/legal/terms-use
    stance_commercial: prohibited
    text: WestJet grants to you a non-exclusive, limited and revocable license to download and view the Data and other content available on this Website on your computer for the purposes stated in this Agreement and no other purposes.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: WestJet
output_license: custom
provenance_date: '2026-11-10'
provider_name: WestJet
provider_slug: westjet
slug: westjet-data-license
source_date: '2026-11-10'
source_filename: westjet-data-license.yml
source_heading: Data License
source_page: https://westjettravelagents.com/policy-library/ticketing-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: WestJet\naid: westjet\nurl: https://westjettravelagents.com/policy-library/ticketing-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://westjettravelagents.com/policy-library/ticketing-policy/\n  - https://www.westjet.com/en-ca/legal/terms-use\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: WestJet grants to you a non-exclusive, limited and revocable license to download and view the Data and other\n    content available on this Website on your computer for the purposes stated in this Agreement and no other purposes.\n  source: https://www.westjet.com/en-ca/legal/terms-use\ndata:\n\
  \  license: null\n  stance_commercial: prohibited\n  text: Unless otherwise approved in writing by WestJet, an Agent shall not redistribute, share or in any other\n    manner, make any of WestJet Inventory available to any 3rd party\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/westjet/data-license/westjet-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from WestJet's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Canada
- Aviation
- Airlines
- Distribution
- NDC
- Booking
- Cargo
- Loyalty
---
