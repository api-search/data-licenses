---
api_specs:
- filename: doaj-bulk-api-api-openapi.yml
  format: yaml
  label: DOAJ Bulk API
  slug: doaj-bulk-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doaj/openapi/doaj-bulk-api-api-openapi.yml
- filename: doaj-crud-applications-api-openapi.yml
  format: yaml
  label: DOAJ CRUD Applications API
  slug: doaj-crud-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doaj/openapi/doaj-crud-applications-api-openapi.yml
- filename: doaj-crud-articles-api-openapi.yml
  format: yaml
  label: DOAJ CRUD Articles API
  slug: doaj-crud-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doaj/openapi/doaj-crud-articles-api-openapi.yml
- filename: doaj-crud-journals-api-openapi.yml
  format: yaml
  label: DOAJ CRUD Journals API
  slug: doaj-crud-journals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doaj/openapi/doaj-crud-journals-api-openapi.yml
- filename: doaj-search-api-openapi.yml
  format: yaml
  label: DOAJ Search API
  slug: doaj-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doaj/openapi/doaj-search-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: CC0-1.0
    stance_commercial: unstated
    text: The journal-level metadata is available with a CC0 waiver
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
name: DOAJ
output_license: null
provenance_date: '2026-11-09'
provider_name: DOAJ
provider_slug: doaj
slug: doaj-data-license
source_date: '2026-11-09'
source_filename: doaj-data-license.yml
source_heading: Data License
source_page: https://doaj.org/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: DOAJ\naid: doaj\nurl: https://doaj.org/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: CC0-1.0\n  stance_commercial: unstated\n  text: The journal-level metadata is available with a CC0 waiver\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/doaj/data-license/doaj-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from DOAJ's own page on 2026-11-09.
synthetic: false
tags:
- Open Access
- Journals
- Scholarly Publishing
- Metadata
---
