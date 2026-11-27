---
api_specs:
- filename: findlocal-events-api-openapi.yml
  format: yaml
  label: FindLocal Events API
  slug: findlocal-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findlocal/openapi/findlocal-events-api-openapi.yml
- filename: findlocal-venues-api-openapi.yml
  format: yaml
  label: FindLocal Venues API
  slug: findlocal-venues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findlocal/openapi/findlocal-venues-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Wherever data obtained with a Free-plan key is shown to end users, display a visible text link reading "Event data by FindLocal" (or equivalent wording) pointing to https://findlocal.community . Paid plans are exempt from this requirement.
  data:
    license: custom
    stance_commercial: conditional
    text: You may not resell, sublicense or redistribute the dataset, or a substantial part of it, as a dataset, nor mirror it to build a competing event database.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: You may display, filter and combine the data in your own apps, sites and agents.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: FindLocal
output_license: custom
provenance_date: '2026-11-09'
provider_name: FindLocal
provider_slug: findlocal
slug: findlocal-data-license
source_date: '2026-11-09'
source_filename: findlocal-data-license.yml
source_heading: Data License
source_page: https://findlocal.community/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: FindLocal\naid: findlocal\nurl: https://findlocal.community/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: You may display, filter and combine the data in your own apps, sites and agents.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: You may not resell, sublicense or redistribute the dataset, or a substantial part of it, as a dataset, nor\n    mirror it to build a competing event database.\nattribution:\n  required: true\n  text: Wherever data obtained with a Free-plan key is shown to end users, display a visible text link reading \"\
  Event\n    data by FindLocal\" (or equivalent wording) pointing to https://findlocal.community . Paid plans are exempt from\n    this requirement.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/findlocal/data-license/findlocal-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from FindLocal's own page on 2026-11-09.
synthetic: false
tags:
- Event
- Hyperlocal
- Community
- Data
- Open Data
---
