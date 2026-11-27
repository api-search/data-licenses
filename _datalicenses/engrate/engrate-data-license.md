---
api_specs:
- filename: engrate-audit-logs-api-openapi.yml
  format: yaml
  label: Engrate Audit Logs API
  slug: engrate-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-audit-logs-api-openapi.yml
- filename: engrate-benachrichtigung-api-openapi.yml
  format: yaml
  label: Engrate Benachrichtigung API
  slug: engrate-benachrichtigung-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-benachrichtigung-api-openapi.yml
- filename: engrate-betrieb-api-openapi.yml
  format: yaml
  label: Engrate Betrieb API
  slug: engrate-betrieb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-betrieb-api-openapi.yml
- filename: engrate-clearing-api-openapi.yml
  format: yaml
  label: Engrate Clearing API
  slug: engrate-clearing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-clearing-api-openapi.yml
- filename: engrate-core-api-openapi.yml
  format: yaml
  label: Engrate Core API
  slug: engrate-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-core-api-openapi.yml
- filename: engrate-cost-of-energy-api-openapi.yml
  format: yaml
  label: Engrate Cost Of Energy API
  slug: engrate-cost-of-energy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-cost-of-energy-api-openapi.yml
- filename: engrate-geo-api-openapi.yml
  format: yaml
  label: Engrate Geo API
  slug: engrate-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-geo-api-openapi.yml
- filename: engrate-holidays-api-openapi.yml
  format: yaml
  label: Engrate Holidays API
  slug: engrate-holidays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-holidays-api-openapi.yml
- filename: engrate-lokationen-api-openapi.yml
  format: yaml
  label: Engrate Lokationen API
  slug: engrate-lokationen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-lokationen-api-openapi.yml
- filename: engrate-lokationsb-ndel-api-openapi.yml
  format: yaml
  label: Engrate Lokationsbündel API
  slug: engrate-lokationsb-ndel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-lokationsb-ndel-api-openapi.yml
- filename: engrate-mabis-api-openapi.yml
  format: yaml
  label: Engrate Mabis API
  slug: engrate-mabis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-mabis-api-openapi.yml
- filename: engrate-netzbetreiberwechsel-api-openapi.yml
  format: yaml
  label: Engrate Netzbetreiberwechsel API
  slug: engrate-netzbetreiberwechsel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-netzbetreiberwechsel-api-openapi.yml
- filename: engrate-nl-settlement-api-openapi.yml
  format: yaml
  label: Engrate Nl Settlement API
  slug: engrate-nl-settlement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-nl-settlement-api-openapi.yml
- filename: engrate-profiles-api-openapi.yml
  format: yaml
  label: Engrate Profiles API
  slug: engrate-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-profiles-api-openapi.yml
- filename: engrate-reference-api-openapi.yml
  format: yaml
  label: Engrate Reference API
  slug: engrate-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-reference-api-openapi.yml
- filename: engrate-schedules-api-openapi.yml
  format: yaml
  label: Engrate Schedules API
  slug: engrate-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-schedules-api-openapi.yml
- filename: engrate-status-request-api-openapi.yml
  format: yaml
  label: Engrate Status Request API
  slug: engrate-status-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-status-request-api-openapi.yml
- filename: engrate-time-series-api-openapi.yml
  format: yaml
  label: Engrate Time Series API
  slug: engrate-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engrate/openapi/engrate-time-series-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: The Client receives a non-exclusive, non-transferable license to use the Product during the subscription term.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Cache Cost of Energy Sweden output data for their own internal use, as long as they are an active paying customer.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Engrate
output_license: custom
provenance_date: '2026-11-09'
provider_name: Engrate
provider_slug: engrate
slug: engrate-data-license
source_date: '2026-11-09'
source_filename: engrate-data-license.yml
source_heading: Data License
source_page: https://engrate.io/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Engrate\naid: engrate\nurl: https://engrate.io/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Cache Cost of Energy Sweden output data for their own internal use, as long as they are an active paying\n    customer.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: The Client receives a non-exclusive, non-transferable license to use the Product during the subscription\n    term.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/engrate/data-license/engrate-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Engrate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Platform
- Integration
- Markets
---
