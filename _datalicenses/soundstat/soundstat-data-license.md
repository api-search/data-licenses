---
api_specs:
- filename: soundstat-genres-api-openapi.yml
  format: yaml
  label: SoundStat Genres API
  slug: soundstat-genres-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soundstat/openapi/soundstat-genres-api-openapi.yml
- filename: soundstat-recommendations-api-openapi.yml
  format: yaml
  label: SoundStat Recommendations API
  slug: soundstat-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soundstat/openapi/soundstat-recommendations-api-openapi.yml
- filename: soundstat-stats-api-openapi.yml
  format: yaml
  label: SoundStat Stats API
  slug: soundstat-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soundstat/openapi/soundstat-stats-api-openapi.yml
- filename: soundstat-track-api-openapi.yml
  format: yaml
  label: SoundStat Track API
  slug: soundstat-track-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soundstat/openapi/soundstat-track-api-openapi.yml
- filename: soundstat-tracks-api-openapi.yml
  format: yaml
  label: SoundStat Tracks API
  slug: soundstat-tracks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soundstat/openapi/soundstat-tracks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: false
    text: Attribution is not required
  data:
    license: null
    stance_commercial: unstated
    text: null
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: incorporating it into commercial products and services
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: SoundStat
output_license: custom
provenance_date: '2026-11-10'
provider_name: SoundStat
provider_slug: soundstat
slug: soundstat-data-license
source_date: '2026-11-10'
source_filename: soundstat-data-license.yml
source_heading: Data License
source_page: https://soundstat.info/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: SoundStat\naid: soundstat\nurl: https://soundstat.info/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: incorporating it into commercial products and services\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: false\n  text: Attribution is not required\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/soundstat/data-license/soundstat-data-license.yml
stated_fields:
- outputs
- attribution
summary_line: 2 quoted statements, read from SoundStat's own page on 2026-11-10.
synthetic: false
tags:
- Music
- Audio Analysis
- Audio Features
- Recommendations
- Track Analysis
- Spotify Alternative
---
