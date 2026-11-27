---
api_specs:
- filename: macadress-healthz-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Healthz API'
  slug: macadress-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-healthz-api-openapi.yml
- filename: macadress-mac-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Mac API'
  slug: macadress-mac-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-mac-api-openapi.yml
- filename: macadress-vendors-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Vendors API'
  slug: macadress-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-vendors-api-openapi.yml
- filename: macadress-vendor-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Vendor API'
  slug: macadress-vendor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-vendor-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: Vendor and address data is synced from IEEE's public registries and reflects their accuracy, not ours
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
name: 'MAC Address Lookup: Find Vendor, OUI & Device Type'
output_license: null
provenance_date: '2026-11-10'
provider_name: 'MAC Address Lookup: Find Vendor, OUI & Device Type'
provider_slug: macadress
slug: macadress-data-license
source_date: '2026-11-10'
source_filename: macadress-data-license.yml
source_heading: Data License
source_page: https://macadress.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: 'MAC Address Lookup: Find Vendor, OUI & Device Type'\naid: macadress\nurl: https://macadress.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: null\n  stance_commercial: unstated\n  text: Vendor and address data is synced from IEEE's public registries and reflects their accuracy, not ours\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/macadress/data-license/macadress-data-license.yml
stated_fields:
- data
summary_line: '1 quoted statement, read from MAC Address Lookup: Find Vendor, OUI & Device Type''s own page on 2026-11-10.'
synthetic: false
tags:
- Networking
- Network Access Control
- Security
- SecOps
- IoT
- Device Fleet Management
- MDM
- Reference Data
- IEEE OUI Lookup
- Developer Tools
- MCP
- Agent-Native
---
