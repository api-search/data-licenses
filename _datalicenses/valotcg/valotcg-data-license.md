---
api_specs:
- filename: valotcg-analysis-api-openapi.yml
  format: yaml
  label: Valo.Data Analysis API
  slug: valotcg-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-analysis-api-openapi.yml
- filename: valotcg-cards-api-openapi.yml
  format: yaml
  label: Valo.Data Cards API
  slug: valotcg-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-cards-api-openapi.yml
- filename: valotcg-editions-api-openapi.yml
  format: yaml
  label: Valo.Data Editions API
  slug: valotcg-editions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-editions-api-openapi.yml
- filename: valotcg-games-api-openapi.yml
  format: yaml
  label: Valo.Data Games API
  slug: valotcg-games-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-games-api-openapi.yml
- filename: valotcg-sealed-api-openapi.yml
  format: yaml
  label: Valo.Data Sealed API
  slug: valotcg-sealed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-sealed-api-openapi.yml
- filename: valotcg-usage-api-openapi.yml
  format: yaml
  label: Valo.Data Usage API
  slug: valotcg-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: prohibited
    text: 'Il ne confère aucune licence sur les données : elles ne peuvent être ni revendues, ni redistribuées, ni intégrées à un produit ou à un service, ni extraites massivement.'
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: prohibited
    text: Revendre ou exploiter commercialement les données
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Valo.Data
output_license: null
provenance_date: '2026-11-10'
provider_name: Valo.Data
provider_slug: valotcg
slug: valotcg-data-license
source_date: '2026-11-10'
source_filename: valotcg-data-license.yml
source_heading: Data License
source_page: https://valotcg.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Valo.Data\naid: valotcg\nurl: https://valotcg.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: prohibited\n  text: Revendre ou exploiter commercialement les données\ndata:\n  license: null\n  stance_commercial: prohibited\n  text: 'Il ne confère aucune licence sur les données : elles ne peuvent être ni revendues, ni redistribuées, ni\n    intégrées à un produit ou à un service, ni extraites massivement.'\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/valotcg/data-license/valotcg-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Valo.Data's own page on 2026-11-10.
synthetic: false
tags:
- Trading Card Games
- Pricing Data
- Vision
---
