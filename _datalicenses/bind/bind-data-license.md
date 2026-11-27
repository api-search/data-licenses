---
api_specs:
- filename: bind-policies-api-openapi.yml
  format: yaml
  label: Bind Policies API
  slug: bind-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bind/openapi/bind-policies-api-openapi.yml
- filename: bind-quotes-api-openapi.yml
  format: yaml
  label: Bind Quotes API
  slug: bind-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bind/openapi/bind-quotes-api-openapi.yml
- filename: bind-reports-api-openapi.yml
  format: yaml
  label: Bind Reports API
  slug: bind-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bind/openapi/bind-reports-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: You must not use the Content to construct any kind of database without the prior express written permission of BindHQ.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: The Terms permit you to use the Website for your personal, non-commercial use only.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Bind
output_license: custom
provenance_date: '2026-11-09'
provider_name: Bind
provider_slug: bind
slug: bind-data-license
source_date: '2026-11-09'
source_filename: bind-data-license.yml
source_heading: Data License
source_page: https://www.bindhq.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Bind\naid: bind\nurl: https://www.bindhq.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: The Terms permit you to use the Website for your personal, non-commercial use only.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You must not use the Content to construct any kind of database without the prior express written permission\n    of BindHQ.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/bind/data-license/bind-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Bind's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Platform
- Composable
- Specialty
---
