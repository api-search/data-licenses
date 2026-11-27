---
api_specs:
- filename: iplocate-openapi.yml
  format: yaml
  label: IPLocate API
  slug: iplocate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iplocate/openapi/iplocate-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: Using the free databases requires attribution.
  data:
    license: null
    stance_commercial: unstated
    text: null
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Subject to your continuing compliance with this Agreement and timely payment of any applicable fees, we grant you a non‑exclusive
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: IPLocate (formerly GeoIPs)
output_license: custom
provenance_date: '2026-11-09'
provider_name: IPLocate (formerly GeoIPs)
provider_slug: iplocate
slug: iplocate-data-license
source_date: '2026-11-09'
source_filename: iplocate-data-license.yml
source_heading: Data License
source_page: https://www.iplocate.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: IPLocate (formerly GeoIPs)\naid: iplocate\nurl: https://www.iplocate.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Subject to your continuing compliance with this Agreement and timely payment of any applicable fees, we\n    grant you a non‑exclusive\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: true\n  text: Using the free databases requires attribution.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/iplocate/data-license/iplocate-data-license.yml
stated_fields:
- outputs
- attribution
summary_line: 2 quoted statements, read from IPLocate (formerly GeoIPs)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- IP Geolocation
- Threat Detection
- Privacy
- Data
---
