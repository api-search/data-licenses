---
api_specs:
- filename: podkitapp-com-admin-api-openapi.yml
  format: yaml
  label: podkitapp-com Admin API
  slug: podkitapp-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-admin-api-openapi.yml
- filename: podkitapp-com-episodes-api-openapi.yml
  format: yaml
  label: podkitapp-com Episodes API
  slug: podkitapp-com-episodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-episodes-api-openapi.yml
- filename: podkitapp-com-podcasts-api-openapi.yml
  format: yaml
  label: podkitapp-com Podcasts API
  slug: podkitapp-com-podcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-podcasts-api-openapi.yml
- filename: podkitapp-com-search-api-openapi.yml
  format: yaml
  label: podkitapp-com Search API
  slug: podkitapp-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-search-api-openapi.yml
- filename: podkitapp-com-usage-api-openapi.yml
  format: yaml
  label: podkitapp-com Usage API
  slug: podkitapp-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: Podcast audio, transcripts, and associated metadata remain the property of their respective creators and publishers.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You retain all rights to applications, products, or content you build using data obtained through the Service, subject to the underlying rights of the original podcast creators in that data (see Section 2).
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: podkitapp-com
output_license: custom
provenance_date: '2026-11-10'
provider_name: podkitapp-com
provider_slug: podkitapp-com
slug: podkitapp-com-data-license
source_date: '2026-11-10'
source_filename: podkitapp-com-data-license.yml
source_heading: Data License
source_page: https://podkitapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: podkitapp-com\naid: podkitapp-com\nurl: https://podkitapp.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You retain all rights to applications, products, or content you build using data obtained through the Service,\n    subject to the underlying rights of the original podcast creators in that data (see Section 2).\ndata:\n  license: null\n  stance_commercial: unstated\n  text: Podcast audio, transcripts, and associated metadata remain the property of their respective creators and\n    publishers.\nattribution:\n  required: null\n  text: null\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/podkitapp-com/data-license/podkitapp-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from podkitapp-com's own page on 2026-11-10.
synthetic: false
tags:
- Podcasts
- Data
- Developers
- Audio
---
