---
api_specs:
- filename: qobuz-albums-api-openapi.yml
  format: yaml
  label: Qobuz Albums API
  slug: qobuz-albums-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-albums-api-openapi.yml
- filename: qobuz-artists-api-openapi.yml
  format: yaml
  label: Qobuz Artists API
  slug: qobuz-artists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-artists-api-openapi.yml
- filename: qobuz-authentication-api-openapi.yml
  format: yaml
  label: Qobuz Authentication API
  slug: qobuz-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-authentication-api-openapi.yml
- filename: qobuz-playlists-api-openapi.yml
  format: yaml
  label: Qobuz Playlists API
  slug: qobuz-playlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-playlists-api-openapi.yml
- filename: qobuz-search-api-openapi.yml
  format: yaml
  label: Qobuz Search API
  slug: qobuz-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-search-api-openapi.yml
- filename: qobuz-tracks-api-openapi.yml
  format: yaml
  label: Qobuz Tracks API
  slug: qobuz-tracks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qobuz/openapi/qobuz-tracks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Your Application must prominently display the following “This application uses the Qobuz API but is not certified by Qobuz.”
  data:
    license: custom
    stance_commercial: prohibited
    text: making the API, Service or Content available to any person who is not a User
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: prohibited
    text: charging the access to the API, the Service or the Content or solicit any income, for example through any advertising, sponsorships or subsidies
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Qobuz
output_license: null
provenance_date: '2026-11-10'
provider_name: Qobuz
provider_slug: qobuz
slug: qobuz-data-license
source_date: '2026-11-10'
source_filename: qobuz-data-license.yml
source_heading: Data License
source_page: http://static.qobuz.com/apps/api/QobuzAPI-TermsofUse.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Qobuz\naid: qobuz\nurl: http://static.qobuz.com/apps/api/QobuzAPI-TermsofUse.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: prohibited\n  text: charging the access to the API, the Service or the Content or solicit any income, for example through any\n    advertising, sponsorships or subsidies\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: making the API, Service or Content available to any person who is not a User\nattribution:\n  required: true\n  text: Your Application must prominently display the following “This application uses the Qobuz API but is not\n\
  \    certified by Qobuz.”\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/qobuz/data-license/qobuz-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Qobuz's own page on 2026-11-10.
synthetic: false
tags:
- Music Streaming
- Hi-Res Audio
- FLAC
- Lossless Audio
- Music Downloads
- Catalog Search
- Streaming URLs
- Music Metadata
- Audiophile
- France
- Music
---
