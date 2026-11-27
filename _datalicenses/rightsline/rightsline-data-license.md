---
api_specs:
- filename: overview
  format: yaml
  label: Rightsline Rights API
  slug: rights-api
  spec_type: Postman
  url: https://www.postman.com/kinlaneapi/rightsline/overview
- filename: postman.yaml
  format: yaml
  label: Rightsline Royalties API
  slug: royalties-api
  spec_type: Postman
  url: https://postman.rightsline.com/
- filename: rightsline-availability-api-openapi.yml
  format: yaml
  label: Rightsline Availability API
  slug: rightsline-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-availability-api-openapi.yml
- filename: rightsline-catalog-api-openapi.yml
  format: yaml
  label: Rightsline Catalog API
  slug: rightsline-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-catalog-api-openapi.yml
- filename: rightsline-contacts-api-openapi.yml
  format: yaml
  label: Rightsline Contacts API
  slug: rightsline-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-contacts-api-openapi.yml
- filename: rightsline-lists-api-openapi.yml
  format: yaml
  label: Rightsline Lists API
  slug: rightsline-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-lists-api-openapi.yml
- filename: rightsline-rights-api-openapi.yml
  format: yaml
  label: Rightsline Rights API
  slug: rightsline-rights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-rights-api-openapi.yml
- filename: rightsline-royalties-api-openapi.yml
  format: yaml
  label: Rightsline Royalties API
  slug: rightsline-royalties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-royalties-api-openapi.yml
- filename: rightsline-templates-api-openapi.yml
  format: yaml
  label: Rightsline Templates API
  slug: rightsline-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-templates-api-openapi.yml
- filename: rightsline-workflows-api-openapi.yml
  format: yaml
  label: Rightsline Workflows API
  slug: rightsline-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightsline/openapi/rightsline-workflows-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: For clarity, Usage Data is not Customer Data nor is it otherwise proprietary to Customer.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Customer may not use the AI Features or any Outputs to develop or improve any product or service that competes with the Model Providers or Rightsline.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Rightsline
output_license: custom
provenance_date: '2026-11-10'
provider_name: Rightsline
provider_slug: rightsline
slug: rightsline-data-license
source_date: '2026-11-10'
source_filename: rightsline-data-license.yml
source_heading: Data License
source_page: https://www.rightsline.com/ai-addendum/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Rightsline\naid: rightsline\nurl: https://www.rightsline.com/ai-addendum/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Customer may not use the AI Features or any Outputs to develop or improve any product or service that competes\n    with the Model Providers or Rightsline.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: For clarity, Usage Data is not Customer Data nor is it otherwise proprietary to Customer.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/rightsline/data-license/rightsline-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Rightsline's own page on 2026-11-10.
synthetic: false
tags:
- Content Management
- Entertainment
- Media
- Rights Management
- Royalties
---
