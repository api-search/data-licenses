---
api_specs:
- filename: scryfall-bulk-data-api-openapi.yml
  format: yaml
  label: Scryfall Bulk Data API
  slug: scryfall-bulk-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-bulk-data-api-openapi.yml
- filename: scryfall-cards-api-openapi.yml
  format: yaml
  label: Scryfall Cards API
  slug: scryfall-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-cards-api-openapi.yml
- filename: scryfall-catalogs-api-openapi.yml
  format: yaml
  label: Scryfall Catalogs API
  slug: scryfall-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-catalogs-api-openapi.yml
- filename: scryfall-migrations-api-openapi.yml
  format: yaml
  label: Scryfall Migrations API
  slug: scryfall-migrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-migrations-api-openapi.yml
- filename: scryfall-rulings-api-openapi.yml
  format: yaml
  label: Scryfall Rulings API
  slug: scryfall-rulings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-rulings-api-openapi.yml
- filename: scryfall-sets-api-openapi.yml
  format: yaml
  label: Scryfall Sets API
  slug: scryfall-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-sets-api-openapi.yml
- filename: scryfall-symbology-api-openapi.yml
  format: yaml
  label: Scryfall Symbology API
  slug: scryfall-symbology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-symbology-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: true
    text: Users should be able to identify the artist and source of the image somehow.
  data:
    license: null
    stance_commercial: unstated
    text: null
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
name: Scryfall
output_license: null
provenance_date: '2026-11-10'
provider_name: Scryfall
provider_slug: scryfall
slug: scryfall-data-license
source_date: '2026-11-10'
source_filename: scryfall-data-license.yml
source_heading: Data License
source_page: https://scryfall.com/docs/api
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Scryfall\naid: scryfall\nurl: https://scryfall.com/docs/api\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: true\n  text: Users should be able to identify the artist and source of the image somehow.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/scryfall/data-license/scryfall-data-license.yml
stated_fields:
- attribution
summary_line: 1 quoted statement, read from Scryfall's own page on 2026-11-10.
synthetic: false
tags:
- Magic The Gathering
- Card Data
- Open Data
- Free
- Community Funded
- Public APIs
- Gaming
- Card Games
---
