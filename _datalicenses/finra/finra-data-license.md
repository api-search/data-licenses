---
api_specs:
- filename: finra-async-api-openapi.yml
  format: yaml
  label: FINRA Async API
  slug: finra-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-async-api-openapi.yml
- filename: finra-datasets-api-openapi.yml
  format: yaml
  label: FINRA Datasets API
  slug: finra-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-datasets-api-openapi.yml
- filename: finra-metadata-api-openapi.yml
  format: yaml
  label: FINRA Metadata API
  slug: finra-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-metadata-api-openapi.yml
- filename: finra-partitions-api-openapi.yml
  format: yaml
  label: FINRA Partitions API
  slug: finra-partitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-partitions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: Developer shall identify FINRA as the owner and source of that Licensed Data
  data:
    license: null
    stance_commercial: unstated
    text: null
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: Unless otherwise specified in the Specific Terms, as between the Parties, and subject to FINRA’s rights in the Licensed Materials, Developer will own all rights in and to Resultant Data.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: FINRA
output_license: custom
provenance_date: '2026-11-09'
provider_name: FINRA
provider_slug: finra
slug: finra-data-license
source_date: '2026-11-09'
source_filename: finra-data-license.yml
source_heading: Data License
source_page: https://developer.finra.org/finra-api-terms-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: FINRA\naid: finra\nurl: https://developer.finra.org/finra-api-terms-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Unless otherwise specified in the Specific Terms, as between the Parties, and subject to FINRA’s rights\n    in the Licensed Materials, Developer will own all rights in and to Resultant Data.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: true\n  text: Developer shall identify FINRA as the owner and source of that Licensed Data\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/finra/data-license/finra-data-license.yml
stated_fields:
- outputs
- attribution
summary_line: 2 quoted statements, read from FINRA's own page on 2026-11-09.
synthetic: false
tags:
- Compliance
- Finance
- Regulations
- Securities
- Market Data
---
