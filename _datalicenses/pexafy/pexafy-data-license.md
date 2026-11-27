---
api_specs:
- filename: pexafy-collections-api-openapi.yml
  format: yaml
  label: Pexafy Collections API
  slug: pexafy-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-collections-api-openapi.yml
- filename: pexafy-facets-api-openapi.yml
  format: yaml
  label: Pexafy Facets API
  slug: pexafy-facets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-facets-api-openapi.yml
- filename: pexafy-photos-api-openapi.yml
  format: yaml
  label: Pexafy Photos API
  slug: pexafy-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-photos-api-openapi.yml
- filename: pexafy-search-api-openapi.yml
  format: yaml
  label: Pexafy Search API
  slug: pexafy-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-search-api-openapi.yml
- filename: pexafy-usage-api-openapi.yml
  format: yaml
  label: Pexafy Usage API
  slug: pexafy-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: You may not reproduce, distribute, or create derivative works without explicit written permission.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Pexafy provides license metadata (type, source URL) in API responses to help you identify usage rights.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Pexafy
output_license: custom
provenance_date: '2026-11-10'
provider_name: Pexafy
provider_slug: pexafy
slug: pexafy-data-license
source_date: '2026-11-10'
source_filename: pexafy-data-license.yml
source_heading: Data License
source_page: https://pexafy.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Pexafy\naid: pexafy\nurl: https://pexafy.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Pexafy provides license metadata (type, source URL) in API responses to help you identify usage rights.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You may not reproduce, distribute, or create derivative works without explicit written permission.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/pexafy/data-license/pexafy-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Pexafy's own page on 2026-11-10.
synthetic: false
tags:
- Image
- Photos
- Stock Photos
- Image Search
- Semantic Search
- Computer Vision
- Embeddings
- MCP
- Agent-Native
- Content Licensing
---
