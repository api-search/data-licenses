---
api_specs:
- filename: gravatar-avatars-api-openapi.yml
  format: yaml
  label: Gravatar Avatars API
  slug: gravatar-avatars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gravatar/openapi/gravatar-avatars-api-openapi.yml
- filename: gravatar-experimental-api-openapi.yml
  format: yaml
  label: Gravatar Experimental API
  slug: gravatar-experimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gravatar/openapi/gravatar-experimental-api-openapi.yml
- filename: gravatar-profiles-api-openapi.yml
  format: yaml
  label: Gravatar Profiles API
  slug: gravatar-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gravatar/openapi/gravatar-profiles-api-openapi.yml
- filename: gravatar-qr-code-api-openapi.yml
  format: yaml
  label: Gravatar Qr Code API
  slug: gravatar-qr-code-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gravatar/openapi/gravatar-qr-code-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: You grant us a worldwide, royalty-free, transferable, sub-licensable, and non-exclusive license to use, reproduce, modify, distribute, adapt, publicly display, and publish the Content for the purpose of providing and improving our products and Services and promoting your profile (including via the API ).
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
name: Gravatar
output_license: null
provenance_date: '2026-11-09'
provider_name: Gravatar
provider_slug: gravatar
slug: gravatar-data-license
source_date: '2026-11-09'
source_filename: gravatar-data-license.yml
source_heading: Data License
source_page: https://automattic.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Gravatar\naid: gravatar\nurl: https://automattic.com/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: You grant us a worldwide, royalty-free, transferable, sub-licensable, and non-exclusive license to use,\n    reproduce, modify, distribute, adapt, publicly display, and publish the Content for the purpose of providing\n    and improving our products and Services and promoting your profile (including via the API ).\nattribution:\n  required: null\n  text: null\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/gravatar/data-license/gravatar-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Gravatar's own page on 2026-11-09.
synthetic: false
tags:
- Avatars
- Identity
- Profiles
- Social
- Image
- GraphQL
- REST
---
