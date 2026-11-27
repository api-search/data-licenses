---
api_specs:
- filename: oddsrelay-account-api-openapi.yml
  format: yaml
  label: OddsRelay Account API
  slug: oddsrelay-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-account-api-openapi.yml
- filename: oddsrelay-discovery-api-openapi.yml
  format: yaml
  label: OddsRelay Discovery API
  slug: oddsrelay-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-discovery-api-openapi.yml
- filename: oddsrelay-odds-api-openapi.yml
  format: yaml
  label: OddsRelay Odds API
  slug: oddsrelay-odds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-odds-api-openapi.yml
- filename: oddsrelay-service-api-openapi.yml
  format: yaml
  label: OddsRelay Service API
  slug: oddsrelay-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-service-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Reselling the Feed, or supplying the Data to other businesses as data, still needs the Order to allow it.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Under an Order, you may use the Data for your Business, and may also show the Data, or what you make from it, to your End Users, unless the Order says otherwise.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: OddsRelay
output_license: custom
provenance_date: '2026-11-10'
provider_name: OddsRelay
provider_slug: oddsrelay
slug: oddsrelay-data-license
source_date: '2026-11-10'
source_filename: oddsrelay-data-license.yml
source_heading: Data License
source_page: https://oddsrelay.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: OddsRelay\naid: oddsrelay\nurl: https://oddsrelay.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Under an Order, you may use the Data for your Business, and may also show the Data, or what you make from\n    it, to your End Users, unless the Order says otherwise.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Reselling the Feed, or supplying the Data to other businesses as data, still needs the Order to allow it.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/oddsrelay/data-license/oddsrelay-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from OddsRelay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports Betting
- Odds
- Sports Data
- Matched Betting
- Data Feed
---
