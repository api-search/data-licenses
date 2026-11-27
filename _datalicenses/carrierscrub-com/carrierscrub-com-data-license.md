---
api_specs:
- filename: carrierscrub-com-authority-history-api-openapi.yml
  format: yaml
  label: CarrierScrub Authority History API
  slug: carrierscrub-com-authority-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-authority-history-api-openapi.yml
- filename: carrierscrub-com-batch-api-openapi.yml
  format: yaml
  label: CarrierScrub Batch API
  slug: carrierscrub-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-batch-api-openapi.yml
- filename: carrierscrub-com-fmcsa-activity-api-openapi.yml
  format: yaml
  label: CarrierScrub Fmcsa Activity API
  slug: carrierscrub-com-fmcsa-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-fmcsa-activity-api-openapi.yml
- filename: carrierscrub-com-lookup-api-openapi.yml
  format: yaml
  label: CarrierScrub Lookup API
  slug: carrierscrub-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-lookup-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: CarrierScrub owns the software, the verdict engine, the verdict rules, and the site content. Nothing here transfers any of that to you.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: prohibited
    text: Do not resell, redistribute, or bulk-export CarrierScrub results, reason codes or Shield results as a data product.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: CarrierScrub
output_license: null
provenance_date: '2026-11-09'
provider_name: CarrierScrub
provider_slug: carrierscrub-com
slug: carrierscrub-com-data-license
source_date: '2026-11-09'
source_filename: carrierscrub-com-data-license.yml
source_heading: Data License
source_page: https://carrierscrub.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: CarrierScrub\naid: carrierscrub-com\nurl: https://carrierscrub.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: prohibited\n  text: Do not resell, redistribute, or bulk-export CarrierScrub results, reason codes or Shield results as a data\n    product.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: CarrierScrub owns the software, the verdict engine, the verdict rules, and the site content. Nothing here\n    transfers any of that to you.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/carrierscrub-com/data-license/carrierscrub-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from CarrierScrub's own page on 2026-11-09.
synthetic: false
tags:
- carrier-vetting
- Freight Brokerage
- FMCSA Data
---
