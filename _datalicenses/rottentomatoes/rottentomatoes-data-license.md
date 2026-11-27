---
api_specs:
- filename: rottentomatoes-detailed-info-api-openapi.yml
  format: yaml
  label: Rotten Tomatoes Detailed Info API
  slug: rottentomatoes-detailed-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rottentomatoes/openapi/rottentomatoes-detailed-info-api-openapi.yml
- filename: rottentomatoes-dvd-lists-api-openapi.yml
  format: yaml
  label: Rotten Tomatoes DVD Lists API
  slug: rottentomatoes-dvd-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rottentomatoes/openapi/rottentomatoes-dvd-lists-api-openapi.yml
- filename: rottentomatoes-movie-lists-api-openapi.yml
  format: yaml
  label: Rotten Tomatoes Movie Lists API
  slug: rottentomatoes-movie-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rottentomatoes/openapi/rottentomatoes-movie-lists-api-openapi.yml
- filename: rottentomatoes-search-api-openapi.yml
  format: yaml
  label: Rotten Tomatoes Search API
  slug: rottentomatoes-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rottentomatoes/openapi/rottentomatoes-search-api-openapi.yml
- filename: rottentomatoes-top-level-lists-api-openapi.yml
  format: yaml
  label: Rotten Tomatoes Top Level Lists API
  slug: rottentomatoes-top-level-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rottentomatoes/openapi/rottentomatoes-top-level-lists-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    source: https://www.rottentomatoes.com/help_desk/licensing
    text: Brand attribution is required in every location where Rotten Tomatoes content is displayed.
  data:
    license: custom
    stance_commercial: prohibited
    text: Any other use of the Services, including reproduction, modification, distribution, or republication, any form of data extraction or data mining, or other commercial exploitation of any kind, without prior written permission of Fandango is strictly prohibited.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: prohibited
    text: Permission is granted solely to use the Services solely for personal consumer use, and not for commercial exploitation.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Rotten Tomatoes
output_license: null
provenance_date: '2026-11-10'
provider_name: Rotten Tomatoes
provider_slug: rottentomatoes
slug: rottentomatoes-data-license
source_date: '2026-11-10'
source_filename: rottentomatoes-data-license.yml
source_heading: Data License
source_page: https://www.rottentomatoes.com/policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Rotten Tomatoes\naid: rottentomatoes\nurl: https://www.rottentomatoes.com/policies/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://www.rottentomatoes.com/help_desk/licensing\n  - https://www.rottentomatoes.com/policies/terms-of-use\noutputs:\n  license: null\n  stance_commercial: prohibited\n  text: Permission is granted solely to use the Services solely for personal consumer use, and not for commercial\n    exploitation.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Any other use of the Services, including reproduction, modification, distribution, or\
  \ republication, any\n    form of data extraction or data mining, or other commercial exploitation of any kind, without prior written\n    permission of Fandango is strictly prohibited.\nattribution:\n  required: true\n  text: Brand attribution is required in every location where Rotten Tomatoes content is displayed.\n  source: https://www.rottentomatoes.com/help_desk/licensing\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/rottentomatoes/data-license/rottentomatoes-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Rotten Tomatoes's own page on 2026-11-10.
synthetic: false
tags:
- Movies
- Television
- Reviews
- Ratings
- Tomatometer
- Audience Score
- Entertainment
- Media
---
