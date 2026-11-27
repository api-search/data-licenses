---
api_specs:
- filename: equibles-equibles-api-api-openapi.yml
  format: yaml
  label: Equibles Equibles API
  slug: equibles-equibles-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-equibles-api-api-openapi.yml
- filename: equibles-etfs-api-openapi.yml
  format: yaml
  label: Equibles Etfs API
  slug: equibles-etfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-etfs-api-openapi.yml
- filename: equibles-fda-api-openapi.yml
  format: yaml
  label: Equibles Fda API
  slug: equibles-fda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-fda-api-openapi.yml
- filename: equibles-funds-api-openapi.yml
  format: yaml
  label: Equibles Funds API
  slug: equibles-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-funds-api-openapi.yml
- filename: equibles-investment-advisers-api-openapi.yml
  format: yaml
  label: Equibles Investment Advisers API
  slug: equibles-investment-advisers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-investment-advisers-api-openapi.yml
- filename: equibles-ipos-api-openapi.yml
  format: yaml
  label: Equibles Ipos API
  slug: equibles-ipos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-ipos-api-openapi.yml
- filename: equibles-short-interest-api-openapi.yml
  format: yaml
  label: Equibles Short Interest API
  slug: equibles-short-interest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-short-interest-api-openapi.yml
- filename: equibles-short-volume-api-openapi.yml
  format: yaml
  label: Equibles Short Volume API
  slug: equibles-short-volume-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-short-volume-api-openapi.yml
- filename: equibles-stocks-api-openapi.yml
  format: yaml
  label: Equibles Stocks API
  slug: equibles-stocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-stocks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: you must identify Equibles as the source of that data, clearly and close to the data itself.
  data:
    license: custom
    stance_commercial: conditional
    text: Subject to these Terms, we grant you a limited, non-exclusive, non-transferable, revocable right to use the Service during the applicable plan term.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: While your Pro subscription is active, you may display, share, and otherwise redistribute data obtained from the Service to your end users through a website, software application, or AI agent that you operate, including as part of a paid product.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Equibles
output_license: custom
provenance_date: '2026-11-09'
provider_name: Equibles
provider_slug: equibles
slug: equibles-data-license
source_date: '2026-11-09'
source_filename: equibles-data-license.yml
source_heading: Data License
source_page: https://equibles.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Equibles\naid: equibles\nurl: https://equibles.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: While your Pro subscription is active, you may display, share, and otherwise redistribute data obtained\n    from the Service to your end users through a website, software application, or AI agent that you operate, including\n    as part of a paid product.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Subject to these Terms, we grant you a limited, non-exclusive, non-transferable, revocable right to use\n    the Service during\
  \ the applicable plan term.\nattribution:\n  required: true\n  text: you must identify Equibles as the source of that data, clearly and close to the data itself.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/equibles/data-license/equibles-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Equibles's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Data
- Stocks
---
