---
api_specs:
- filename: semscraper-com-openapi-generated.yml
  format: yaml
  label: semscraper-com API
  slug: semscraper-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semscraper-com/openapi/_ae-authored/semscraper-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: The data provided (SERPs) remains the exclusive property of the Provider.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: The Client is authorized to integrate and use the data within their own tools, dashboards, reports, software, or services, including in commercial solutions provided to their end customers.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: semscraper-com
output_license: custom
provenance_date: '2026-11-10'
provider_name: semscraper-com
provider_slug: semscraper-com
slug: semscraper-com-data-license
source_date: '2026-11-10'
source_filename: semscraper-com-data-license.yml
source_heading: Data License
source_page: https://www.semscraper.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: semscraper-com\naid: semscraper-com\nurl: https://www.semscraper.com/en/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: The Client is authorized to integrate and use the data within their own tools, dashboards, reports, software,\n    or services, including in commercial solutions provided to their end customers.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: The data provided (SERPs) remains the exclusive property of the Provider.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/semscraper-com/data-license/semscraper-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from semscraper-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SERP
- Google Maps
- AI-Overviews
- Bulk Processing
---
