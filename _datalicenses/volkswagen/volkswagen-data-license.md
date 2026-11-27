---
api_specs:
- filename: volkswagen-catalog-api-openapi.yml
  format: yaml
  label: Volkswagen Catalog API
  slug: volkswagen-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volkswagen/openapi/volkswagen-catalog-api-openapi.yml
- filename: volkswagen-configuration-api-openapi.yml
  format: yaml
  label: Volkswagen Configuration API
  slug: volkswagen-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volkswagen/openapi/volkswagen-configuration-api-openapi.yml
- filename: volkswagen-information-api-openapi.yml
  format: yaml
  label: Volkswagen Information API
  slug: volkswagen-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volkswagen/openapi/volkswagen-information-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: OKAPI and the published Product Data are and remain in the ownership of Volkswagen. Volkswagen grants the User for the duration of this contractual relationship a non-exclusive, non-transferable, revocable and non-sublicensable right for the use of OKAPI
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: The User is entitled to disclose the Product Data from OKAPI or the results and evaluations compiled on the basis of OKAPI to third parties.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Volkswagen
output_license: custom
provenance_date: '2026-11-10'
provider_name: Volkswagen
provider_slug: volkswagen
slug: volkswagen-data-license
source_date: '2026-11-10'
source_filename: volkswagen-data-license.yml
source_heading: Data License
source_page: https://productdata.volkswagenag.com/condition-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Volkswagen\naid: volkswagen\nurl: https://productdata.volkswagenag.com/condition-of-use.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: The User is entitled to disclose the Product Data from OKAPI or the results and evaluations compiled on\n    the basis of OKAPI to third parties.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: OKAPI and the published Product Data are and remain in the ownership of Volkswagen. Volkswagen grants the\n    User for the duration of this contractual relationship a non-exclusive, non-transferable, revocable\
  \ and non-sublicensable\n    right for the use of OKAPI\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/volkswagen/data-license/volkswagen-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Volkswagen's own page on 2026-11-10.
synthetic: false
tags:
- Automobiles
- Cars
- Vehicles
- Automotive
- Vehicle Configuration
---
