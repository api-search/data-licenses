---
api_specs:
- filename: nutrientsdb-foods-api-openapi.yml
  format: yaml
  label: NutrientsDB Foods API
  slug: nutrientsdb-foods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nutrientsdb/openapi/nutrientsdb-foods-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Reproduce the attribution notices required by each applicable Source License in any product or publication that exposes Source Data to end users.
  data:
    license: custom
    stance_commercial: conditional
    text: Licensee is responsible for complying with each applicable Source License, including any attribution, share-alike, no-endorsement, or other source-specific requirements.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: Incorporation of the data into commercial end-products (e.g., mobile applications, websites, software platforms, AI/ML systems, printed materials)
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: NutrientsDB
output_license: custom
provenance_date: '2026-11-10'
provider_name: NutrientsDB
provider_slug: nutrientsdb
slug: nutrientsdb-data-license
source_date: '2026-11-10'
source_filename: nutrientsdb-data-license.yml
source_heading: Data License
source_page: https://www.nutrientsdb.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: NutrientsDB\naid: nutrientsdb\nurl: https://www.nutrientsdb.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: Incorporation of the data into commercial end-products (e.g., mobile applications, websites, software platforms,\n    AI/ML systems, printed materials)\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Licensee is responsible for complying with each applicable Source License, including any attribution, share-alike,\n    no-endorsement, or other source-specific requirements.\nattribution:\n  required: true\n  text: Reproduce the\
  \ attribution notices required by each applicable Source License in any product or publication\n    that exposes Source Data to end users.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/nutrientsdb/data-license/nutrientsdb-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from NutrientsDB's own page on 2026-11-10.
synthetic: false
tags:
- Nutrition
- Food
- Nutrients
- food-composition
- Data
- Search
- Sample Data
- Datasets
- ai-builders
- Reference Data
- Open Data
- keyless-api
---
