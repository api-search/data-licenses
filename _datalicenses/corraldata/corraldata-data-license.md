---
api_specs:
- filename: corraldata-openapi-generated.yml
  format: yaml
  label: CorralData API
  slug: corraldata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corraldata/openapi/_ae-authored/corraldata-openapi-generated.yml
- filename: corraldata-kb-api-openapi.yml
  format: yaml
  label: CorralData Kb API
  slug: corraldata-kb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corraldata/openapi/corraldata-kb-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: The Customer owns the data, content and materials it submits to the Service ("Customer Data").
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: conditional
    text: Using reports and dashboards built from your own data in your normal business is fine.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: CorralData
output_license: null
provenance_date: '2026-11-09'
provider_name: CorralData
provider_slug: corraldata
slug: corraldata-data-license
source_date: '2026-11-09'
source_filename: corraldata-data-license.yml
source_heading: Data License
source_page: https://corraldata.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: CorralData\naid: corraldata\nurl: https://corraldata.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: conditional\n  text: Using reports and dashboards built from your own data in your normal business is fine.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: The Customer owns the data, content and materials it submits to the Service (\"Customer Data\").\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/corraldata/data-license/corraldata-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from CorralData's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Analytics
- Healthcare
- Artificial Intelligence
- Platform
---
