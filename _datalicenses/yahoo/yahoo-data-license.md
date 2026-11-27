---
api_specs:
- filename: public
  format: yaml
  label: Yahoo DSP Traffic API
  slug: dsp-traffic-api
  spec_type: Postman
  url: https://www.postman.com/yahoodsp/workspace/public
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: The Yahoo Developer Network Attribution Policy located at http://developer.yahoo.com/attribution/
  data:
    license: null
    stance_commercial: unstated
    text: null
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Yahoo's rights apply to the Yahoo APIs and all output and executables of the Yahoo APIs
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Yahoo
output_license: custom
provenance_date: '2026-11-10'
provider_name: Yahoo
provider_slug: yahoo
slug: yahoo-data-license
source_date: '2026-11-10'
source_filename: yahoo-data-license.yml
source_heading: Data License
source_page: https://legal.yahoo.com/us/en/yahoo/terms/product-atos/apiforydn/index.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Yahoo\naid: yahoo\nurl: https://legal.yahoo.com/us/en/yahoo/terms/product-atos/apiforydn/index.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Yahoo's rights apply to the Yahoo APIs and all output and executables of the Yahoo APIs\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: true\n  text: The Yahoo Developer Network Attribution Policy located at http://developer.yahoo.com/attribution/\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/yahoo/data-license/yahoo-data-license.yml
stated_fields:
- outputs
- attribution
summary_line: 2 quoted statements, read from Yahoo's own page on 2026-11-10.
synthetic: false
tags:
- Advertising
- Programmatic Advertising
- DSP
- Fantasy Sports
- Sports Data
- Identity
- OpenID Connect
- OAuth
- Audience Data
- Media
- Reporting
- Conversion Tracking
- Authentication
---
