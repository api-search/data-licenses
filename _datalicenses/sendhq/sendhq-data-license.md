---
api_specs:
- filename: sendhq-account-and-billing-api-openapi.yml
  format: yaml
  label: SendHQ Account and billing API
  slug: sendhq-account-and-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-account-and-billing-api-openapi.yml
- filename: sendhq-deliverability-api-openapi.yml
  format: yaml
  label: SendHQ Deliverability API
  slug: sendhq-deliverability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-deliverability-api-openapi.yml
- filename: sendhq-domains-api-openapi.yml
  format: yaml
  label: SendHQ Domains API
  slug: sendhq-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-domains-api-openapi.yml
- filename: sendhq-drafts-and-attachments-api-openapi.yml
  format: yaml
  label: SendHQ Drafts and attachments API
  slug: sendhq-drafts-and-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-drafts-and-attachments-api-openapi.yml
- filename: sendhq-emails-and-threads-api-openapi.yml
  format: yaml
  label: SendHQ Emails and threads API
  slug: sendhq-emails-and-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-emails-and-threads-api-openapi.yml
- filename: sendhq-hosted-templates-api-openapi.yml
  format: yaml
  label: SendHQ Hosted templates API
  slug: sendhq-hosted-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-hosted-templates-api-openapi.yml
- filename: sendhq-inbound-email-api-openapi.yml
  format: yaml
  label: SendHQ Inbound email API
  slug: sendhq-inbound-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-inbound-email-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: You retain ownership of the content you send through the Service. You grant us a limited license to process that content solely to provide the Service
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
name: SendHQ
output_license: null
provenance_date: '2026-11-10'
provider_name: SendHQ
provider_slug: sendhq
slug: sendhq-data-license
source_date: '2026-11-10'
source_filename: sendhq-data-license.yml
source_heading: Data License
source_page: https://sendhq.cc/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: SendHQ\naid: sendhq\nurl: https://sendhq.cc/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: You retain ownership of the content you send through the Service. You grant us a limited license to process\n    that content solely to provide the Service\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/sendhq/data-license/sendhq-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from SendHQ's own page on 2026-11-10.
synthetic: false
tags:
- Email API
- Transactional Email
- Inbound Email
- Deliverability
---
