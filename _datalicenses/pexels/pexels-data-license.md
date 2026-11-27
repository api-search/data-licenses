---
api_specs:
- filename: pexels-collections-api-openapi.yml
  format: yaml
  label: Pexels Collections API
  slug: pexels-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexels/openapi/pexels-collections-api-openapi.yml
- filename: pexels-photos-api-openapi.yml
  format: yaml
  label: Pexels Photos API
  slug: pexels-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexels/openapi/pexels-photos-api-openapi.yml
- filename: pexels-videos-api-openapi.yml
  format: yaml
  label: Pexels Videos API
  slug: pexels-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexels/openapi/pexels-videos-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: false
    text: You do not need to credit Pexels or the contributor of Content when you use it
  data:
    license: custom
    stance_commercial: allowed
    text: the CC0 Content can be used for all personal and commercial purposes without attributing the author/ content owner of the CC0 Content or Pexels.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: we grant you an irrevocable, worldwide, perpetual (or as long as allowed by law), non-exclusive and royalty-free right to download, use, copy, modify or adapt the Content for commercial or non-commercial purposes
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Pexels
output_license: custom
provenance_date: '2026-11-10'
provider_name: Pexels
provider_slug: pexels
slug: pexels-data-license
source_date: '2026-11-10'
source_filename: pexels-data-license.yml
source_heading: Data License
source_page: https://www.pexels.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Pexels\naid: pexels\nurl: https://www.pexels.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: we grant you an irrevocable, worldwide, perpetual (or as long as allowed by law), non-exclusive and royalty-free\n    right to download, use, copy, modify or adapt the Content for commercial or non-commercial purposes\ndata:\n  license: custom\n  stance_commercial: allowed\n  text: the CC0 Content can be used for all personal and commercial purposes without attributing the author/ content\n    owner of the CC0 Content or Pexels.\nattribution:\n  required:\
  \ false\n  text: You do not need to credit Pexels or the contributor of Content when you use it\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/pexels/data-license/pexels-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Pexels's own page on 2026-11-10.
synthetic: false
tags:
- Photos
- Stock Media
- Video
---
