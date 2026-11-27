---
api_specs:
- filename: citedtravel-com-billing-api-openapi.yml
  format: yaml
  label: CitedTravel Billing API
  slug: citedtravel-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-billing-api-openapi.yml
- filename: citedtravel-com-entry-api-openapi.yml
  format: yaml
  label: CitedTravel Entry API
  slug: citedtravel-com-entry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-entry-api-openapi.yml
- filename: citedtravel-com-facts-api-openapi.yml
  format: yaml
  label: CitedTravel Facts API
  slug: citedtravel-com-facts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-facts-api-openapi.yml
- filename: citedtravel-com-meta-api-openapi.yml
  format: yaml
  label: CitedTravel Meta API
  slug: citedtravel-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-meta-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: When you display facts, you must show the attribution strings returned with each response.
  data:
    license: null
    stance_commercial: unstated
    text: Facts come from third-party sources under their own licenses (CC0, public domain, Open Government Licence v3, Japan's Public Data License 1.0, MIT, the Unicode License and attributed CC BY).
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Subject to these Terms and your plan, we grant you a non-exclusive, worldwide, non-transferable licence, while you use the Service, to use, cache and display API outputs in your own products and agents.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: CitedTravel
output_license: custom
provenance_date: '2026-11-09'
provider_name: CitedTravel
provider_slug: citedtravel-com
slug: citedtravel-com-data-license
source_date: '2026-11-09'
source_filename: citedtravel-com-data-license.yml
source_heading: Data License
source_page: https://citedtravel.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: CitedTravel\naid: citedtravel-com\nurl: https://citedtravel.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Subject to these Terms and your plan, we grant you a non-exclusive, worldwide, non-transferable licence,\n    while you use the Service, to use, cache and display API outputs in your own products and agents.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: Facts come from third-party sources under their own licenses (CC0, public domain, Open Government Licence\n    v3, Japan's Public Data License 1.0, MIT, the Unicode License\
  \ and attributed CC BY).\nattribution:\n  required: true\n  text: When you display facts, you must show the attribution strings returned with each response.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/citedtravel-com/data-license/citedtravel-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from CitedTravel's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Data
- TravelFacts
- Open Data
---
