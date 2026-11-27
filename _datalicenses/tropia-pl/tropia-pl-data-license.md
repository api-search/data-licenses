---
api_specs:
- filename: tropia-pl-openapi.yml
  format: yaml
  label: tropia.pl API
  slug: tropia-pl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tropia-pl/openapi/tropia-pl-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: Dane z publicznych rejestrów. Zawsze ze źródłem.
  data:
    license: null
    stance_commercial: prohibited
    text: odsprzedaż danych z Serwisu
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
name: tropia-pl
output_license: null
provenance_date: '2026-11-10'
provider_name: tropia-pl
provider_slug: tropia-pl
slug: tropia-pl-data-license
source_date: '2026-11-10'
source_filename: tropia-pl-data-license.yml
source_heading: Data License
source_page: https://tropia.pl/regulamin
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: tropia-pl\naid: tropia-pl\nurl: https://tropia.pl/regulamin\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: null\n  stance_commercial: prohibited\n  text: odsprzedaż danych z Serwisu\nattribution:\n  required: true\n  text: Dane z publicznych rejestrów. Zawsze ze źródłem.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/tropia-pl/data-license/tropia-pl-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from tropia-pl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Poland
- Finance
- Public Records
---
