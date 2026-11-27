---
api_specs:
- filename: uxcam-events-api-openapi.yml
  format: yaml
  label: UXCam Events API
  slug: uxcam-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uxcam/openapi/uxcam-events-api-openapi.yml
- filename: uxcam-sessions-api-openapi.yml
  format: yaml
  label: UXCam Sessions API
  slug: uxcam-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uxcam/openapi/uxcam-sessions-api-openapi.yml
- filename: uxcam-users-api-openapi.yml
  format: yaml
  label: UXCam Users API
  slug: uxcam-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uxcam/openapi/uxcam-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: The Customer retains full ownership of their Users’ Data.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: conditional
    text: for Customer’s own internal business purpose.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: UXCam
output_license: null
provenance_date: '2026-11-10'
provider_name: UXCam
provider_slug: uxcam
slug: uxcam-data-license
source_date: '2026-11-10'
source_filename: uxcam-data-license.yml
source_heading: Data License
source_page: https://help.uxcam.com/en/articles/10222767-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: UXCam\naid: uxcam\nurl: https://help.uxcam.com/en/articles/10222767-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: conditional\n  text: for Customer’s own internal business purpose.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: The Customer retains full ownership of their Users’ Data.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/uxcam/data-license/uxcam-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from UXCam's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Product Analytics
- Session Replay
- Mobile Analytics
- Heatmaps
- User Experience
- Crash Reporting
---
