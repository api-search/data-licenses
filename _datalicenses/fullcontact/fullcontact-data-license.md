---
api_specs:
- filename: fullcontact-address-api-openapi.yml
  format: yaml
  label: FullContact Address API
  slug: fullcontact-address-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-address-api-openapi.yml
- filename: fullcontact-audience-api-openapi.yml
  format: yaml
  label: FullContact Audience API
  slug: fullcontact-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-audience-api-openapi.yml
- filename: fullcontact-enrich-api-openapi.yml
  format: yaml
  label: FullContact Enrich API
  slug: fullcontact-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-enrich-api-openapi.yml
- filename: fullcontact-identity-api-openapi.yml
  format: yaml
  label: FullContact Identity API
  slug: fullcontact-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-identity-api-openapi.yml
- filename: fullcontact-permission-api-openapi.yml
  format: yaml
  label: FullContact Permission API
  slug: fullcontact-permission-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-permission-api-openapi.yml
- filename: fullcontact-tags-api-openapi.yml
  format: yaml
  label: FullContact Tags API
  slug: fullcontact-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-tags-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: prohibited
    text: all Content available through the Site is owned by FullContact and FullContact’s licensors and providers
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
name: FullContact
output_license: null
provenance_date: '2026-11-09'
provider_name: FullContact
provider_slug: fullcontact
slug: fullcontact-data-license
source_date: '2026-11-09'
source_filename: fullcontact-data-license.yml
source_heading: Data License
source_page: https://www.fullcontact.com/privacy/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: FullContact\naid: fullcontact\nurl: https://www.fullcontact.com/privacy/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: null\n  stance_commercial: prohibited\n  text: all Content available through the Site is owned by FullContact and FullContact’s licensors and providers\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/fullcontact/data-license/fullcontact-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from FullContact's own page on 2026-11-09.
synthetic: false
tags:
- Identity Resolution
- Customer Data
- Data Enrichment
- Person API
- Company API
- Privacy-Safe Identity
- Customer Recognition
---
