---
api_specs:
- filename: aol-openid-connect-api-openapi.yml
  format: yaml
  label: AOL OpenID Connect API
  slug: aol-openid-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aol/openapi/aol-openid-connect-api-openapi.yml
- filename: aol-oauth2-api-openapi.yml
  format: yaml
  label: AOL O Auth2 API
  slug: aol-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aol/openapi/aol-oauth2-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: you must provide attribution to our source website and link to the full article on RSS Feed content.
  data:
    license: null
    stance_commercial: prohibited
    text: Unless you have explicit written permission, you must not reproduce, modify, rent, lease, sell, trade, distribute, transmit, broadcast, publicly perform
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: Unless otherwise expressly stated, you may not access or reuse the Services, or any portion thereof, for any commercial purpose.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: AOL
output_license: custom
provenance_date: '2026-11-09'
provider_name: AOL
provider_slug: aol
slug: aol-data-license
source_date: '2026-11-09'
source_filename: aol-data-license.yml
source_heading: Data License
source_page: https://legal.aol.com/terms/index.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: AOL\naid: aol\nurl: https://legal.aol.com/terms/index.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: Unless otherwise expressly stated, you may not access or reuse the Services, or any portion thereof, for\n    any commercial purpose.\ndata:\n  license: null\n  stance_commercial: prohibited\n  text: Unless you have explicit written permission, you must not reproduce, modify, rent, lease, sell, trade, distribute,\n    transmit, broadcast, publicly perform\nattribution:\n  required: true\n  text: you must provide attribution to our source\
  \ website and link to the full article on RSS Feed content.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/aol/data-license/aol-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from AOL's own page on 2026-11-09.
synthetic: false
tags:
- Digital Media
- News
- Entertainment
- Advertising
- Identity
- OpenID Connect
- Authentication
- Email
- Consumer Internet
- Fortune 1000
---
