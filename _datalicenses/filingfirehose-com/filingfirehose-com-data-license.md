---
api_specs:
- filename: filingfirehose-com-billing-api-openapi.yml
  format: yaml
  label: filingfirehose-com Billing API
  slug: filingfirehose-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-billing-api-openapi.yml
- filename: filingfirehose-com-filings-api-openapi.yml
  format: yaml
  label: filingfirehose-com Filings API
  slug: filingfirehose-com-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-filings-api-openapi.yml
- filename: filingfirehose-com-meta-api-openapi.yml
  format: yaml
  label: filingfirehose-com Meta API
  slug: filingfirehose-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-meta-api-openapi.yml
- filename: filingfirehose-com-public-api-openapi.yml
  format: yaml
  label: filingfirehose-com Public API
  slug: filingfirehose-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-public-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: you may not republish bulk structured datasets except as expressly permitted
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: 'You may use the parsed data internally and in published research that cites the source ("data: FilingFirehose")'
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: filingfirehose-com
output_license: custom
provenance_date: '2026-11-09'
provider_name: filingfirehose-com
provider_slug: filingfirehose-com
slug: filingfirehose-com-data-license
source_date: '2026-11-09'
source_filename: filingfirehose-com-data-license.yml
source_heading: Data License
source_page: https://filingfirehose.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: filingfirehose-com\naid: filingfirehose-com\nurl: https://filingfirehose.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: 'You may use the parsed data internally and in published research that cites the source (\"data: FilingFirehose\")'\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: you may not republish bulk structured datasets except as expressly permitted\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/filingfirehose-com/data-license/filingfirehose-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from filingfirehose-com's own page on 2026-11-09.
synthetic: false
tags:
- SEC
- EDGAR
- Finance
- Data API
- JSON
---
