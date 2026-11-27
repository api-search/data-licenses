---
api_specs:
- filename: filevine-identity-api-openapi.yml
  format: yaml
  label: Filevine Identity API
  slug: filevine-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-identity-api-openapi.yml
- filename: filevine-projects-api-openapi.yml
  format: yaml
  label: Filevine Projects API
  slug: filevine-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-projects-api-openapi.yml
- filename: filevine-contacts-api-openapi.yml
  format: yaml
  label: Filevine Contacts API
  slug: filevine-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-contacts-api-openapi.yml
- filename: filevine-documents-api-openapi.yml
  format: yaml
  label: Filevine Documents API
  slug: filevine-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-documents-api-openapi.yml
- filename: filevine-notes-api-openapi.yml
  format: yaml
  label: Filevine Notes API
  slug: filevine-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-notes-api-openapi.yml
- filename: filevine-deadlines-api-openapi.yml
  format: yaml
  label: Filevine Deadlines API
  slug: filevine-deadlines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-deadlines-api-openapi.yml
- filename: filevine-tasks-api-openapi.yml
  format: yaml
  label: Filevine Tasks API
  slug: filevine-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-tasks-api-openapi.yml
- filename: filevine-webhooks-api-openapi.yml
  format: yaml
  label: Filevine Webhooks API
  slug: filevine-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-webhooks-api-openapi.yml
- filename: filevine-time-entries-api-openapi.yml
  format: yaml
  label: Filevine Time Entries API
  slug: filevine-time-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-time-entries-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Filevine may use Subscriber’s Data in de-identified, aggregated form (“Anonymized Data”) to improve and enhance the Services and for other development, diagnostic, and corrective purposes
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: Subscriber owns all right, title, and interest in Subscriber’s Data, including Output generated from that Data.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Filevine
output_license: custom
provenance_date: '2026-11-09'
provider_name: Filevine
provider_slug: filevine
slug: filevine-data-license
source_date: '2026-11-09'
source_filename: filevine-data-license.yml
source_heading: Data License
source_page: https://www.filevine.com/legal/subscription-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Filevine\naid: filevine\nurl: https://www.filevine.com/legal/subscription-agreement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.filevine.com/legal/subscription-agreement/\n  - https://www.filevine.com/legal/terms-of-service/\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Subscriber owns all right, title, and interest in Subscriber’s Data, including Output generated from that\n    Data.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Filevine may use Subscriber’s Data in de-identified, aggregated form (“Anonymized Data”) to improve and\n    enhance the Services\
  \ and for other development, diagnostic, and corrective purposes\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/filevine/data-license/filevine-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Filevine's own page on 2026-11-09.
synthetic: false
tags:
- Legal
- Case Management
- Matter
- Intake
- Documents
- LOIS
- Webhook
- Legal AI
- Personal Injury
- Mass Torts
---
