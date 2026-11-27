---
api_specs:
- filename: musicbrainz-areas-api-openapi.yml
  format: yaml
  label: MusicBrainz Areas API
  slug: musicbrainz-areas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-areas-api-openapi.yml
- filename: musicbrainz-artists-api-openapi.yml
  format: yaml
  label: MusicBrainz Artists API
  slug: musicbrainz-artists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-artists-api-openapi.yml
- filename: musicbrainz-collections-api-openapi.yml
  format: yaml
  label: MusicBrainz Collections API
  slug: musicbrainz-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-collections-api-openapi.yml
- filename: musicbrainz-events-api-openapi.yml
  format: yaml
  label: MusicBrainz Events API
  slug: musicbrainz-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-events-api-openapi.yml
- filename: musicbrainz-genres-api-openapi.yml
  format: yaml
  label: MusicBrainz Genres API
  slug: musicbrainz-genres-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-genres-api-openapi.yml
- filename: musicbrainz-identifiers-api-openapi.yml
  format: yaml
  label: MusicBrainz Identifiers API
  slug: musicbrainz-identifiers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-identifiers-api-openapi.yml
- filename: musicbrainz-instruments-api-openapi.yml
  format: yaml
  label: MusicBrainz Instruments API
  slug: musicbrainz-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-instruments-api-openapi.yml
- filename: musicbrainz-labels-api-openapi.yml
  format: yaml
  label: MusicBrainz Labels API
  slug: musicbrainz-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-labels-api-openapi.yml
- filename: musicbrainz-places-api-openapi.yml
  format: yaml
  label: MusicBrainz Places API
  slug: musicbrainz-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-places-api-openapi.yml
- filename: musicbrainz-recordings-api-openapi.yml
  format: yaml
  label: MusicBrainz Recordings API
  slug: musicbrainz-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-recordings-api-openapi.yml
- filename: musicbrainz-release-groups-api-openapi.yml
  format: yaml
  label: MusicBrainz Release Groups API
  slug: musicbrainz-release-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-release-groups-api-openapi.yml
- filename: musicbrainz-releases-api-openapi.yml
  format: yaml
  label: MusicBrainz Releases API
  slug: musicbrainz-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-releases-api-openapi.yml
- filename: musicbrainz-series-api-openapi.yml
  format: yaml
  label: MusicBrainz Series API
  slug: musicbrainz-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-series-api-openapi.yml
- filename: musicbrainz-submission-api-openapi.yml
  format: yaml
  label: MusicBrainz Submission API
  slug: musicbrainz-submission-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-submission-api-openapi.yml
- filename: musicbrainz-urls-api-openapi.yml
  format: yaml
  label: MusicBrainz URLs API
  slug: musicbrainz-urls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-urls-api-openapi.yml
- filename: musicbrainz-works-api-openapi.yml
  format: yaml
  label: MusicBrainz Works API
  slug: musicbrainz-works-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/musicbrainz/openapi/musicbrainz-works-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: as long as MusicBrainz is given credit
  data:
    license: custom
    stance_commercial: conditional
    text: The remaining portions of the database are released under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 license. This allows for non-commercial use of the data as long as MusicBrainz is given credit
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
name: MusicBrainz
output_license: null
provenance_date: '2026-11-10'
provider_name: MusicBrainz
provider_slug: musicbrainz
slug: musicbrainz-data-license
source_date: '2026-11-10'
source_filename: musicbrainz-data-license.yml
source_heading: Data License
source_page: https://musicbrainz.org/doc/About/Data_License
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: MusicBrainz\naid: musicbrainz\nurl: https://musicbrainz.org/doc/About/Data_License\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://metabrainz.org/social-contract\n  - https://musicbrainz.org/doc/About/Data_License\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: The remaining portions of the database are released under the Creative Commons Attribution-NonCommercial-ShareAlike\n    3.0 license. This allows for non-commercial use of the data as long as MusicBrainz is given credit\nattribution:\n  required: true\n  text:\
  \ as long as MusicBrainz is given credit\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/musicbrainz/data-license/musicbrainz-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from MusicBrainz's own page on 2026-11-10.
synthetic: false
tags:
- Music
- Metadata
- Encyclopedia
- Open Data
- Catalog
- Identifiers
- ISRC
- ISWC
- MBID
- DiscID
- Artists
- Releases
- Recording
- Works
- Labels
- CoverArt
- Open Source
- Non-Profit
---
