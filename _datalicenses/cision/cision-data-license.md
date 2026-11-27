---
api_specs:
- filename: cision-mentions-api-openapi.yml
  format: yaml
  label: Cision Mentions API
  slug: cision-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cision/openapi/cision-mentions-api-openapi.yml
- filename: cision-stream-api-openapi.yml
  format: yaml
  label: Cision Stream API
  slug: cision-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cision/openapi/cision-stream-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Supplier owns all intellectual property rights in the Services and Supplier or its licensors own all intellectual property rights in the Supplier Data.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: sell, resell, license, sublicense, distribute, or otherwise make the Services (or the results of the Services, including Supplier Data) available to anybody other than its Users for their own internal use, unless stated otherwise on an Order
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Cision
output_license: custom
provenance_date: '2026-11-09'
provider_name: Cision
provider_slug: cision
slug: cision-data-license
source_date: '2026-11-09'
source_filename: cision-data-license.yml
source_heading: Data License
source_page: https://www.cision.com/legal/msa/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Cision\naid: cision\nurl: https://www.cision.com/legal/msa/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: sell, resell, license, sublicense, distribute, or otherwise make the Services (or the results of the Services,\n    including Supplier Data) available to anybody other than its Users for their own internal use, unless stated\n    otherwise on an Order\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Supplier owns all intellectual property rights in the Services and Supplier or its licensors own all intellectual\n    property rights in\
  \ the Supplier Data.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/cision/data-license/cision-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Cision's own page on 2026-11-09.
synthetic: false
tags:
- PR Software
- Public Relations
- Earned Media
- Media Monitoring
- Press Release Distribution
- Media Database
- Influencer Identification
- Analytics
---
