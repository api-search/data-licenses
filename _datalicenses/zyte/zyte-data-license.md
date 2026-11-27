---
api_specs:
- filename: zyte-extract-api-openapi.yml
  format: yaml
  label: Zyte Extract API
  slug: zyte-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zyte/openapi/zyte-extract-api-openapi.yml
- filename: zyte-stats-api-openapi.yml
  format: yaml
  label: Zyte Stats API
  slug: zyte-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zyte/openapi/zyte-stats-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: The Services do not provide any copyright or permissions to you with regard to use of the Service Data or Data Feeds
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You represent and warrant that you will utilize the Services legally and ethically for your internal intelligence gathering and internal business purposes
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Zyte
output_license: custom
provenance_date: '2026-11-10'
provider_name: Zyte
provider_slug: zyte
slug: zyte-data-license
source_date: '2026-11-10'
source_filename: zyte-data-license.yml
source_heading: Data License
source_page: https://www.zyte.com/terms-policies/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Zyte\naid: zyte\nurl: https://www.zyte.com/terms-policies/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You represent and warrant that you will utilize the Services legally and ethically for your internal intelligence\n    gathering and internal business purposes\ndata:\n  license: null\n  stance_commercial: unstated\n  text: The Services do not provide any copyright or permissions to you with regard to use of the Service Data or\n    Data Feeds\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/zyte/data-license/zyte-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Zyte's own page on 2026-11-10.
synthetic: false
tags:
- Crawling
- Data Extraction
- Web Scraping
- Proxies
- Browser Automation
- Anti-Ban
- SERP
- Agent Skills
- Developer Tools
---
