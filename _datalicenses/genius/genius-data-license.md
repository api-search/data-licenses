---
api_specs:
- filename: genius-account-api-openapi.yml
  format: yaml
  label: Genius Account API
  slug: genius-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-account-api-openapi.yml
- filename: genius-albums-api-openapi.yml
  format: yaml
  label: Genius Albums API
  slug: genius-albums-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-albums-api-openapi.yml
- filename: genius-annotations-api-openapi.yml
  format: yaml
  label: Genius Annotations API
  slug: genius-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-annotations-api-openapi.yml
- filename: genius-artists-api-openapi.yml
  format: yaml
  label: Genius Artists API
  slug: genius-artists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-artists-api-openapi.yml
- filename: genius-referents-api-openapi.yml
  format: yaml
  label: Genius Referents API
  slug: genius-referents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-referents-api-openapi.yml
- filename: genius-search-api-openapi.yml
  format: yaml
  label: Genius Search API
  slug: genius-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-search-api-openapi.yml
- filename: genius-songs-api-openapi.yml
  format: yaml
  label: Genius Songs API
  slug: genius-songs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-songs-api-openapi.yml
- filename: genius-users-api-openapi.yml
  format: yaml
  label: Genius Users API
  slug: genius-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-users-api-openapi.yml
- filename: genius-web-pages-api-openapi.yml
  format: yaml
  label: Genius Web Pages API
  slug: genius-web-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genius/openapi/genius-web-pages-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: you agree not to sell, license, rent, modify, distribute, copy, reproduce, transmit, publicly display, publicly perform, publish, adapt, edit or create derivative works from any Genius Content.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: prohibited
    text: The Service is for your personal use and may not be used for direct commercial endeavors without the express written consent of Genius.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Genius
output_license: null
provenance_date: '2026-11-09'
provider_name: Genius
provider_slug: genius
slug: genius-data-license
source_date: '2026-11-09'
source_filename: genius-data-license.yml
source_heading: Data License
source_page: https://genius.com/static/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Genius\naid: genius\nurl: https://genius.com/static/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: prohibited\n  text: The Service is for your personal use and may not be used for direct commercial endeavors without the express\n    written consent of Genius.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: you agree not to sell, license, rent, modify, distribute, copy, reproduce, transmit, publicly display, publicly\n    perform, publish, adapt, edit or create derivative works from any Genius Content.\nattribution:\n  required: null\n  text: null\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/genius/data-license/genius-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Genius's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Lyrics
- Annotation
- Crowdsourced
- Reference Data
- Public APIs
---
