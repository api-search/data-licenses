---
api_specs:
- filename: govinfo-collections-api-openapi.yml
  format: yaml
  label: GovInfo Collections API
  slug: govinfo-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govinfo/openapi/govinfo-collections-api-openapi.yml
- filename: govinfo-packages-api-openapi.yml
  format: yaml
  label: GovInfo Packages API
  slug: govinfo-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govinfo/openapi/govinfo-packages-api-openapi.yml
- filename: govinfo-published-api-openapi.yml
  format: yaml
  label: GovInfo Published API
  slug: govinfo-published-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govinfo/openapi/govinfo-published-api-openapi.yml
- filename: govinfo-related-api-openapi.yml
  format: yaml
  label: GovInfo Related API
  slug: govinfo-related-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govinfo/openapi/govinfo-related-api-openapi.yml
- filename: govinfo-search-api-openapi.yml
  format: yaml
  label: GovInfo Search API
  slug: govinfo-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govinfo/openapi/govinfo-search-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: customary credit should be given to the Government department or agency which prepared the material.
  data:
    license: null
    stance_commercial: conditional
    text: public documents can generally be reprinted without legal restriction. However, Government publications may contain copyrighted material which was used with permission of the copyright owner.
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
name: GovInfo
output_license: null
provenance_date: '2026-11-09'
provider_name: GovInfo
provider_slug: govinfo
slug: govinfo-data-license
source_date: '2026-11-09'
source_filename: govinfo-data-license.yml
source_heading: Data License
source_page: https://www.govinfo.gov/about/policies
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: GovInfo\naid: govinfo\nurl: https://www.govinfo.gov/about/policies\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: null\n  stance_commercial: conditional\n  text: public documents can generally be reprinted without legal restriction. However, Government publications\n    may contain copyrighted material which was used with permission of the copyright owner.\nattribution:\n  required: true\n  text: customary credit should be given to the Government department or agency which prepared the material.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/govinfo/data-license/govinfo-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from GovInfo's own page on 2026-11-09.
synthetic: false
tags:
- Federal Government
- Government Publishing
- Documents
- Open Data
---
