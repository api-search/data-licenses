---
api_specs:
- filename: minubo-auth-api-openapi.yml
  format: yaml
  label: Minubo Auth API
  slug: minubo-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/minubo/openapi/minubo-auth-api-openapi.yml
- filename: minubo-data-api-openapi.yml
  format: yaml
  label: Minubo Data API
  slug: minubo-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/minubo/openapi/minubo-data-api-openapi.yml
- filename: minubo-etl-api-openapi.yml
  format: yaml
  label: Minubo ETL API
  slug: minubo-etl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/minubo/openapi/minubo-etl-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: weiterzuverkaufen, zu vertreiben oder unterlizenzieren, soweit dies über den in diesen AGB oder einem schriftlichen Vertrag zwischen dem Kunden und minubo ausdrücklich zugelassenen Umfang hinausgeht
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: Die aus dieser Verarbeitung hervorgehenden Auswertungen, Kennzahlen, Berichte, KI-Ergebnisse und sonstigen Ergebnisse (im Folgenden „erzeugte Daten“) stehen im Verhältnis der Parteien dem Kunden zu
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Minubo
output_license: custom
provenance_date: '2026-11-10'
provider_name: Minubo
provider_slug: minubo
slug: minubo-data-license
source_date: '2026-11-10'
source_filename: minubo-data-license.yml
source_heading: Data License
source_page: https://www.minubo.com/de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Minubo\naid: minubo\nurl: https://www.minubo.com/de/agb\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Die aus dieser Verarbeitung hervorgehenden Auswertungen, Kennzahlen, Berichte, KI-Ergebnisse und sonstigen\n    Ergebnisse (im Folgenden „erzeugte Daten“) stehen im Verhältnis der Parteien dem Kunden zu\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: weiterzuverkaufen, zu vertreiben oder unterlizenzieren, soweit dies über den in diesen AGB oder einem schriftlichen\n    Vertrag zwischen dem Kunden und minubo ausdrücklich zugelassenen Umfang\
  \ hinausgeht\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/minubo/data-license/minubo-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Minubo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Business Intelligence
- Analytics
- Retail
- Data
- ETL
- Reporting
---
