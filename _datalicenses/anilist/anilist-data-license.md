---
api_specs:
- filename: anilist-oauth2-api-openapi.yml
  format: yaml
  label: AniList O Auth2 API
  slug: anilist-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anilist/openapi/anilist-oauth2-api-openapi.yml
- filename: anilist-graph-ql-api-openapi.yml
  format: yaml
  label: AniList Graph QL API
  slug: anilist-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anilist/openapi/anilist-graph-ql-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: null
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: conditional
    text: The AniList API may be used within commercial applications or services operating at less than $150 of revenue per month free of charge, no express permission is required.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: AniList
output_license: null
provenance_date: '2026-11-09'
provider_name: AniList
provider_slug: anilist
slug: anilist-data-license
source_date: '2026-11-09'
source_filename: anilist-data-license.yml
source_heading: Data License
source_page: https://docs.anilist.co/guide/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: AniList\naid: anilist\nurl: https://docs.anilist.co/guide/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: conditional\n  text: The AniList API may be used within commercial applications or services operating at less than $150 of revenue\n    per month free of charge, no express permission is required.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/anilist/data-license/anilist-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from AniList's own page on 2026-11-09.
synthetic: false
tags:
- Anime
- Manga
- Entertainment
- Media
- Social
- Database
- GraphQL
- OAuth
- Public APIs
- Authentication
---
