---
api_specs:
- filename: crea-destination-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Destination API
  slug: crea-destination-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-destination-api-openapi.yml
- filename: crea-lead-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Lead API
  slug: crea-lead-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-lead-api-openapi.yml
- filename: crea-member-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Member API
  slug: crea-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-member-api-openapi.yml
- filename: crea-office-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Office API
  slug: crea-office-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-office-api-openapi.yml
- filename: crea-openhouse-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Open House API
  slug: crea-openhouse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-openhouse-api-openapi.yml
- filename: crea-property-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Property API
  slug: crea-property-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-property-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Display the “Powered by REALTOR.ca” logo (the “Logo”), which shall link directly to the corresponding Listing Content on REALTOR.ca.
  data:
    license: custom
    stance_commercial: conditional
    text: Participating Brokerages that opt-in to any of the listing distribution channels hereby grant CREA a royalty-free, perpetual license to use, reproduce, transmit, distribute, and exhibit the Listing Content for the purposes of the DDF®.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: 'Participants may not use the Listing Content they receive through the DDF® for any purpose other than: i) To display on their National Pool Websites and Member Websites;'
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: CREA (REALTOR.ca)
output_license: custom
provenance_date: '2026-11-09'
provider_name: CREA (REALTOR.ca)
provider_slug: crea
slug: crea-data-license
source_date: '2026-11-09'
source_filename: crea-data-license.yml
source_heading: Data License
source_page: https://www.crea.ca/files/technology/english/DDFR-Policy-and-Rules-February-2024-ENG.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: CREA (REALTOR.ca)\naid: crea\nurl: https://www.crea.ca/files/technology/english/DDFR-Policy-and-Rules-February-2024-ENG.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: 'Participants may not use the Listing Content they receive through the DDF® for any purpose other than:\n    i) To display on their National Pool Websites and Member Websites;'\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Participating Brokerages that opt-in to any of the listing distribution channels hereby grant CREA a royalty-free,\n    perpetual license to use,\
  \ reproduce, transmit, distribute, and exhibit the Listing Content for the purposes\n    of the DDF®.\nattribution:\n  required: true\n  text: Display the “Powered by REALTOR.ca” logo (the “Logo”), which shall link directly to the corresponding Listing\n    Content on REALTOR.ca.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/crea/data-license/crea-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from CREA (REALTOR.ca)'s own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Canada
- Property Listings
- MLS
- IDX
- RESO
- OData
- Industry Body
- PropTech
- Data Syndication
---
