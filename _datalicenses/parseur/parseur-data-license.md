---
api_specs:
- filename: parseur-async-api-openapi.yml
  format: yaml
  label: Parseur Async API
  slug: parseur-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-async-api-openapi.yml
- filename: parseur-bootstrap-api-openapi.yml
  format: yaml
  label: Parseur Bootstrap API
  slug: parseur-bootstrap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-bootstrap-api-openapi.yml
- filename: parseur-document-api-openapi.yml
  format: yaml
  label: Parseur Document API
  slug: parseur-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-document-api-openapi.yml
- filename: parseur-parser-api-openapi.yml
  format: yaml
  label: Parseur Parser API
  slug: parseur-parser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-parser-api-openapi.yml
- filename: parseur-template-api-openapi.yml
  format: yaml
  label: Parseur Template API
  slug: parseur-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-template-api-openapi.yml
- filename: parseur-webhook-api-openapi.yml
  format: yaml
  label: Parseur Webhook API
  slug: parseur-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-webhook-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: The Customer shall retain sole ownership of all rights, title and interest in and to Customer Data and its pre-existing IPRs
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: may export all Customer Data, including uploaded documents and extracted results, in structured, commonly used and machine readable formats (such as JSON, CSV and XLSX) free of charge
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Parseur
output_license: custom
provenance_date: '2026-11-10'
provider_name: Parseur
provider_slug: parseur
slug: parseur-data-license
source_date: '2026-11-10'
source_filename: parseur-data-license.yml
source_heading: Data License
source_page: https://parseur.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Parseur\naid: parseur\nurl: https://parseur.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: may export all Customer Data, including uploaded documents and extracted results, in structured, commonly\n    used and machine readable formats (such as JSON, CSV and XLSX) free of charge\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: The Customer shall retain sole ownership of all rights, title and interest in and to Customer Data and its\n    pre-existing IPRs\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/parseur/data-license/parseur-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Parseur's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Document Parsing
- Document Processing
- Document Extraction
- Email Parsing
- OCR
- Data Extraction
- Vision AI
- Automation
- Webhook
- Mailboxes
- Software-as-a-Service
---
