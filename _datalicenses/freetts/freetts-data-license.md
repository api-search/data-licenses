---
claim_count: 3
description: ''
doc:
  attribution:
    required: false
    text: No credit required (though appreciated).
  data:
    license: null
    stance_commercial: prohibited
    text: You can't clone the service or scrape our interface to build a competing product.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: PRO and Creator plans include a commercial use license that permits use of generated audio in any legal commercial context.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: FreeTTS
output_license: custom
provenance_date: '2026-11-09'
provider_name: FreeTTS
provider_slug: freetts
slug: freetts-data-license
source_date: '2026-11-09'
source_filename: freetts-data-license.yml
source_heading: Data License
source_page: https://freetts.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: FreeTTS\naid: freetts\nurl: https://freetts.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: PRO and Creator plans include a commercial use license that permits use of generated audio in any legal\n    commercial context.\ndata:\n  license: null\n  stance_commercial: prohibited\n  text: You can't clone the service or scrape our interface to build a competing product.\nattribution:\n  required: false\n  text: No credit required (though appreciated).\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/freetts/data-license/freetts-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from FreeTTS's own page on 2026-11-09.
synthetic: false
tags:
- Text-to-Speech
- Speech Synthesis
- AI-voice
- Audio
- Media
- Accessibility
- Speech-to-Text
- Content Creation
- Developer Tools
---
