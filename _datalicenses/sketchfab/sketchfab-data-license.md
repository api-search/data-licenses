---
api_specs:
- filename: sketchfab-download-api-openapi.yml
  format: yaml
  label: Sketchfab Download API
  slug: sketchfab-download-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-download-api-openapi.yml
- filename: sketchfab-bookmarks-api-openapi.yml
  format: yaml
  label: Sketchfab Bookmarks API
  slug: sketchfab-bookmarks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-bookmarks-api-openapi.yml
- filename: sketchfab-categories-api-openapi.yml
  format: yaml
  label: Sketchfab Categories API
  slug: sketchfab-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-categories-api-openapi.yml
- filename: sketchfab-collections-api-openapi.yml
  format: yaml
  label: Sketchfab Collections API
  slug: sketchfab-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-collections-api-openapi.yml
- filename: sketchfab-comments-api-openapi.yml
  format: yaml
  label: Sketchfab Comments API
  slug: sketchfab-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-comments-api-openapi.yml
- filename: sketchfab-likes-api-openapi.yml
  format: yaml
  label: Sketchfab Likes API
  slug: sketchfab-likes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-likes-api-openapi.yml
- filename: sketchfab-models-api-openapi.yml
  format: yaml
  label: Sketchfab Models API
  slug: sketchfab-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-models-api-openapi.yml
- filename: sketchfab-orgs-api-openapi.yml
  format: yaml
  label: Sketchfab Orgs API
  slug: sketchfab-orgs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-orgs-api-openapi.yml
- filename: sketchfab-search-api-openapi.yml
  format: yaml
  label: Sketchfab Search API
  slug: sketchfab-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-search-api-openapi.yml
- filename: sketchfab-tags-api-openapi.yml
  format: yaml
  label: Sketchfab Tags API
  slug: sketchfab-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-tags-api-openapi.yml
- filename: sketchfab-users-api-openapi.yml
  format: yaml
  label: Sketchfab Users API
  slug: sketchfab-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-users-api-openapi.yml
- filename: sketchfab-o-embed-api-openapi.yml
  format: yaml
  label: Sketchfab o Embed API
  slug: sketchfab-o-embed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-o-embed-api-openapi.yml
- filename: sketchfab-oauth-api-openapi.yml
  format: yaml
  label: Sketchfab O Auth API
  slug: sketchfab-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-oauth-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    source: https://sketchfab.com/developers/terms
    text: your app must provide attribution to the original creator. Typically, this includes the creator's username and a link to the Sketchfab model.
  data:
    license: custom
    stance_commercial: prohibited
    text: Any commercial exploitation of the Services or Sketchfab Content without express prior written permission from us or the applicable rights holder is strictly prohibited.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: the authenticated User accessing and downloading the User Content shall be responsible for complying with the terms of the license governing said User Content.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Sketchfab
output_license: custom
provenance_date: '2026-11-10'
provider_name: Sketchfab
provider_slug: sketchfab
slug: sketchfab-data-license
source_date: '2026-11-10'
source_filename: sketchfab-data-license.yml
source_heading: Data License
source_page: https://sketchfab.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Sketchfab\naid: sketchfab\nurl: https://sketchfab.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://sketchfab.com/developers/terms\n  - https://sketchfab.com/terms\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: the authenticated User accessing and downloading the User Content shall be responsible for complying with\n    the terms of the license governing said User Content.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Any commercial exploitation of the Services or Sketchfab Content without express prior written permission\n    from us or the applicable\
  \ rights holder is strictly prohibited.\nattribution:\n  required: true\n  text: your app must provide attribution to the original creator. Typically, this includes the creator's username\n    and a link to the Sketchfab model.\n  source: https://sketchfab.com/developers/terms\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/sketchfab/data-license/sketchfab-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Sketchfab's own page on 2026-11-10.
synthetic: false
tags:
- 3D
- Models
- Marketplace
- Viewer
- WebGL
- glTF
- Augmented Reality
- Virtual Reality
- Creative
- Epic Games
---
