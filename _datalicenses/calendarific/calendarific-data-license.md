---
api_specs:
- filename: calendarific-countries-api-openapi.yml
  format: yaml
  label: Calendarific Countries API
  slug: calendarific-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendarific/openapi/calendarific-countries-api-openapi.yml
- filename: calendarific-holidays-api-openapi.yml
  format: yaml
  label: Calendarific Holidays API
  slug: calendarific-holidays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendarific/openapi/calendarific-holidays-api-openapi.yml
- filename: calendarific-languages-api-openapi.yml
  format: yaml
  label: Calendarific Languages API
  slug: calendarific-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendarific/openapi/calendarific-languages-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: You must include a visible attribution credit as described in Section 4.1(b);
  data:
    license: custom
    stance_commercial: conditional
    text: All right, title, and interest in and to the Product, Data, Services, and all intellectual property rights therein (including but not limited to patents, copyrights, trademarks, trade secrets, database rights, and all other proprietary rights) are and shall remain the exclusive property of the Company.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Reproduce Data returned from our API in your applications, provided you include a visible attribution credit stating "Powered by Calendarific"
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Calendarific
output_license: custom
provenance_date: '2026-11-09'
provider_name: Calendarific
provider_slug: calendarific
slug: calendarific-data-license
source_date: '2026-11-09'
source_filename: calendarific-data-license.yml
source_heading: Data License
source_page: https://calendarific.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Calendarific\naid: calendarific\nurl: https://calendarific.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Reproduce Data returned from our API in your applications, provided you include a visible attribution credit\n    stating \"Powered by Calendarific\"\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: All right, title, and interest in and to the Product, Data, Services, and all intellectual property rights\n    therein (including but not limited to patents, copyrights, trademarks, trade secrets, database rights, and all\n   \
  \ other proprietary rights) are and shall remain the exclusive property of the Company.\nattribution:\n  required: true\n  text: You must include a visible attribution credit as described in Section 4.1(b);\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/calendarific/data-license/calendarific-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Calendarific's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Public APIs
- Holidays
- Worldwide
- Localization
---
