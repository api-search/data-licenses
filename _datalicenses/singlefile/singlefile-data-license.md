---
api_specs:
- filename: singlefile-documents-api-openapi.yml
  format: yaml
  label: SingleFile Documents API
  slug: singlefile-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-documents-api-openapi.yml
- filename: singlefile-entities-api-openapi.yml
  format: yaml
  label: SingleFile Entities API
  slug: singlefile-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-entities-api-openapi.yml
- filename: singlefile-jurisdictions-api-openapi.yml
  format: yaml
  label: SingleFile Jurisdictions API
  slug: singlefile-jurisdictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-jurisdictions-api-openapi.yml
- filename: singlefile-orders-api-openapi.yml
  format: yaml
  label: SingleFile Orders API
  slug: singlefile-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-orders-api-openapi.yml
- filename: singlefile-organizations-api-openapi.yml
  format: yaml
  label: SingleFile Organizations API
  slug: singlefile-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-organizations-api-openapi.yml
- filename: singlefile-schemas-api-openapi.yml
  format: yaml
  label: SingleFile Schemas API
  slug: singlefile-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-schemas-api-openapi.yml
- filename: singlefile-tasks-api-openapi.yml
  format: yaml
  label: SingleFile Tasks API
  slug: singlefile-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-tasks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: Customer retains all right, title, and interest in and to Entity Data
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: Customer may use Ordered Services deliverables (including filing receipts, status messages, structure charts etc.) for all lawful business purposes
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: SingleFile
output_license: custom
provenance_date: '2026-11-10'
provider_name: SingleFile
provider_slug: singlefile
slug: singlefile-data-license
source_date: '2026-11-10'
source_filename: singlefile-data-license.yml
source_heading: Data License
source_page: https://www.singlefile.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: SingleFile\naid: singlefile\nurl: https://www.singlefile.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: Customer may use Ordered Services deliverables (including filing receipts, status messages, structure charts\n    etc.) for all lawful business purposes\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: Customer retains all right, title, and interest in and to Entity Data\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/singlefile/data-license/singlefile-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from SingleFile's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compliance
- Legal
- Entity Management
- Corporate Compliance
- Registered Agent
- Business Filings
- Regulatory
- Webhook
- OAuth
- Authentication
---
