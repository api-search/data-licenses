---
api_specs:
- filename: idrive-reseller-api-openapi.yml
  format: yaml
  label: IDrive Reseller API
  slug: idrive-reseller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idrive/openapi/idrive-reseller-api-openapi.yml
- filename: idrive-subusers-api-openapi.yml
  format: yaml
  label: IDrive Subusers API
  slug: idrive-subusers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idrive/openapi/idrive-subusers-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: The data you upload to your Account is owned by you
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: null
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: IDrive
output_license: null
provenance_date: '2026-11-09'
provider_name: IDrive
provider_slug: idrive
slug: idrive-data-license
source_date: '2026-11-09'
source_filename: idrive-data-license.yml
source_heading: Data License
source_page: https://www.idrive.com/s3-storage-e2/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: IDrive\naid: idrive\nurl: https://www.idrive.com/s3-storage-e2/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: null\n  stance_commercial: unstated\n  text: The data you upload to your Account is owned by you\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/idrive/data-license/idrive-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from IDrive's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Object Storage
- S3 Compatible
- Cloud Storage
- Backup
- Reseller
- MCP
---
