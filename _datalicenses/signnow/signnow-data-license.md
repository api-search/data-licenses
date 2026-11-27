---
api_specs:
- filename: signnow-authentication-api-openapi.yml
  format: yaml
  label: SignNow Authentication API
  slug: signnow-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-authentication-api-openapi.yml
- filename: signnow-documents-api-openapi.yml
  format: yaml
  label: SignNow Documents API
  slug: signnow-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-documents-api-openapi.yml
- filename: signnow-envelopes-api-openapi.yml
  format: yaml
  label: SignNow Envelopes API
  slug: signnow-envelopes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-envelopes-api-openapi.yml
- filename: signnow-signing-api-openapi.yml
  format: yaml
  label: SignNow Signing API
  slug: signnow-signing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-signing-api-openapi.yml
- filename: signnow-templates-api-openapi.yml
  format: yaml
  label: SignNow Templates API
  slug: signnow-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-templates-api-openapi.yml
- filename: signnow-users-api-openapi.yml
  format: yaml
  label: SignNow Users API
  slug: signnow-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-users-api-openapi.yml
- filename: signnow-webhooks-api-openapi.yml
  format: yaml
  label: SignNow Webhooks API
  slug: signnow-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: Between you and Provider, Provider owns all rights to Provider Content.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Between you and Provider, you own all rights to Your Content.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: SignNow
output_license: custom
provenance_date: '2026-11-10'
provider_name: SignNow
provider_slug: signnow
slug: signnow-data-license
source_date: '2026-11-10'
source_filename: signnow-data-license.yml
source_heading: Data License
source_page: https://legal.signnow.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: SignNow\naid: signnow\nurl: https://legal.signnow.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Between you and Provider, you own all rights to Your Content.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: Between you and Provider, Provider owns all rights to Provider Content.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/signnow/data-license/signnow-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from SignNow's own page on 2026-11-10.
synthetic: false
tags:
- E-Signature
- Document Management
- Workflow Automation
---
