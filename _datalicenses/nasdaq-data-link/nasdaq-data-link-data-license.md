---
api_specs:
- filename: postman
  format: yaml
  label: Nasdaq Data Link REST API for Real-Time or Delayed Data
  slug: nasdaq-data-link-rest-api-for-real-time-or-delayed-data
  spec_type: Postman
  url: https://github.com/Nasdaq/NasdaqCloudDataService-REST-API/tree/main/restapi/postman
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Such usage shall be for internal business purposes only unless otherwise detailed in the applicable Service Order.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: Client shall exclusively own all rights and title in the Derived Data; provided such Derived Data can only be used for internal business purposes
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Nasdaq Data Link
output_license: custom
provenance_date: '2026-11-10'
provider_name: Nasdaq Data Link
provider_slug: nasdaq-data-link
slug: nasdaq-data-link-data-license
source_date: '2026-11-10'
source_filename: nasdaq-data-link-data-license.yml
source_heading: Data License
source_page: https://data.nasdaq.com/termsandconditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Nasdaq Data Link\naid: nasdaq-data-link\nurl: https://data.nasdaq.com/termsandconditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: Client shall exclusively own all rights and title in the Derived Data; provided such Derived Data can only\n    be used for internal business purposes\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Such usage shall be for internal business purposes only unless otherwise detailed in the applicable Service\n    Order.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/nasdaq-data-link/data-license/nasdaq-data-link-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Nasdaq Data Link's own page on 2026-11-10.
synthetic: false
tags:
- Financial Data
- Stock Market
- Market Data
- Economic Data
- Alternative Data
- Time Series
- Open Data
- Public APIs
---
