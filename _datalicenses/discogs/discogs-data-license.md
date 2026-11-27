---
api_specs:
- filename: discogs-database-api-openapi.yml
  format: yaml
  label: Discogs Database API
  slug: discogs-database-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-database-api-openapi.yml
- filename: discogs-image-api-openapi.yml
  format: yaml
  label: Discogs Image API
  slug: discogs-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-image-api-openapi.yml
- filename: discogs-inventory-management-api-openapi.yml
  format: yaml
  label: Discogs Inventory Management API
  slug: discogs-inventory-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-inventory-management-api-openapi.yml
- filename: discogs-marketplace-api-openapi.yml
  format: yaml
  label: Discogs Marketplace API
  slug: discogs-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-marketplace-api-openapi.yml
- filename: discogs-user-collection-api-openapi.yml
  format: yaml
  label: Discogs User Collection API
  slug: discogs-user-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-user-collection-api-openapi.yml
- filename: discogs-user-identity-api-openapi.yml
  format: yaml
  label: Discogs User Identity API
  slug: discogs-user-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-user-identity-api-openapi.yml
- filename: discogs-user-lists-api-openapi.yml
  format: yaml
  label: Discogs User Lists API
  slug: discogs-user-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-user-lists-api-openapi.yml
- filename: discogs-user-wantlist-api-openapi.yml
  format: yaml
  label: Discogs User Wantlist API
  slug: discogs-user-wantlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discogs/openapi/discogs-user-wantlist-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: 'You must display the following notice directly next to any data You use from the Discogs API: “Data provided by Discogs.”'
  data:
    license: null
    stance_commercial: unstated
    text: null
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Commercial use of Our API and the Content is generally permitted, but may not be permitted, if, in Our sole discretion we determine the commercial use is prohibited.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Discogs
output_license: custom
provenance_date: '2026-11-09'
provider_name: Discogs
provider_slug: discogs
slug: discogs-data-license
source_date: '2026-11-09'
source_filename: discogs-data-license.yml
source_heading: Data License
source_page: https://support.discogs.com/hc/en-us/articles/360009334593-API-Terms-of-Use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Discogs\naid: discogs\nurl: https://support.discogs.com/hc/en-us/articles/360009334593-API-Terms-of-Use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Commercial use of Our API and the Content is generally permitted, but may not be permitted, if, in Our sole\n    discretion we determine the commercial use is prohibited.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: true\n  text: 'You must display the following notice directly next to any data You use from the Discogs API: “Data provided\n    by Discogs.”'\n\
  interface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/discogs/data-license/discogs-data-license.yml
stated_fields:
- outputs
- attribution
summary_line: 2 quoted statements, read from Discogs's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Marketplace
- Catalog
- Community
- Vinyl
- Public APIs
---
