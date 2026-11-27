---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Letterboxd API
  slug: letterboxd-api
  spec_type: OpenAPI
  url: https://api-docs.letterboxd.com/
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: We do not give you any right or license to use any of our intellectual property rights (including our copyright or the right to use any of our trademarks, brands or logos), except as expressly set out in these Terms.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You grant us a non-exclusive, royalty-free, irrevocable, worldwide, perpetual, fully transferable and sub-licensable license to use, reproduce, distribute and display (including for commercial purposes)
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Letterboxd
output_license: custom
provenance_date: '2026-11-09'
provider_name: Letterboxd
provider_slug: letterboxd
slug: letterboxd-data-license
source_date: '2026-11-09'
source_filename: letterboxd-data-license.yml
source_heading: Data License
source_page: https://letterboxd.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Letterboxd\naid: letterboxd\nurl: https://letterboxd.com/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You grant us a non-exclusive, royalty-free, irrevocable, worldwide, perpetual, fully transferable and sub-licensable\n    license to use, reproduce, distribute and display (including for commercial purposes)\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: We do not give you any right or license to use any of our intellectual property rights (including our copyright\n    or the right to use any of\
  \ our trademarks, brands or logos), except as expressly set out in these Terms.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/letterboxd/data-license/letterboxd-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Letterboxd's own page on 2026-11-09.
synthetic: false
tags:
- Film
- Movies
- Social
- Reviews
- Watchlist
- Ratings
- Diary
- Film Festival
- Entertainment
---
