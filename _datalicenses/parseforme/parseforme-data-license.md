---
api_specs:
- filename: parseforme-webhooks-api-openapi.yml
  format: yaml
  label: ParseForMe Webhooks API
  slug: parseforme-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-webhooks-api-openapi.yml
- filename: parseforme-document-types-api-openapi.yml
  format: yaml
  label: ParseForMe Document Types API
  slug: parseforme-document-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-document-types-api-openapi.yml
- filename: parseforme-documents-api-openapi.yml
  format: yaml
  label: ParseForMe Documents API
  slug: parseforme-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-documents-api-openapi.yml
- filename: parseforme-me-api-openapi.yml
  format: yaml
  label: ParseForMe Me API
  slug: parseforme-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-me-api-openapi.yml
- filename: parseforme-meta-api-openapi.yml
  format: yaml
  label: ParseForMe Meta API
  slug: parseforme-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-meta-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: We keep all rights to the Service itself — the software, interfaces, and branding.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: You keep all rights to the documents you upload and to the data we extract from them.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: ParseForMe
output_license: custom
provenance_date: '2026-11-10'
provider_name: ParseForMe
provider_slug: parseforme
slug: parseforme-data-license
source_date: '2026-11-10'
source_filename: parseforme-data-license.yml
source_heading: Data License
source_page: https://parseforme.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: ParseForMe\naid: parseforme\nurl: https://parseforme.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: You keep all rights to the documents you upload and to the data we extract from them.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: We keep all rights to the Service itself — the software, interfaces, and branding.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/parseforme/data-license/parseforme-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from ParseForMe's own page on 2026-11-10.
synthetic: false
tags:
- Document Parsing
- OCR
- Data Extraction
- Document AI
- Intelligent Document Processing
- Invoices
- Bank Statements
- Receipts
- Resume
- PDF
- Webhook
- REST
---
