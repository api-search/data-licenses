---
api_specs:
- filename: flexpa-access-tokens-api-openapi.yml
  format: yaml
  label: Flexpa Access Tokens API
  slug: flexpa-access-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-access-tokens-api-openapi.yml
- filename: flexpa-claims-data-api-openapi.yml
  format: yaml
  label: Flexpa Claims Data API
  slug: flexpa-claims-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-claims-data-api-openapi.yml
- filename: flexpa-fhir-api-openapi.yml
  format: yaml
  label: Flexpa FHIR API
  slug: flexpa-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-fhir-api-openapi.yml
- filename: flexpa-link-api-openapi.yml
  format: yaml
  label: Flexpa Link API
  slug: flexpa-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-link-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: The content on the Flexpa Platform belongs to Flexpa or its affiliates. It includes text, graphics, logos, images, videos, audio, downloads, data, and software.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: The use of any content for commercial purposes is expressly prohibited, unless its use is subject to separately negotiated Services Agreement with Flexpa.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Flexpa
output_license: custom
provenance_date: '2026-11-09'
provider_name: Flexpa
provider_slug: flexpa
slug: flexpa-data-license
source_date: '2026-11-09'
source_filename: flexpa-data-license.yml
source_heading: Data License
source_page: https://www.flexpa.com/docs/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Flexpa\naid: flexpa\nurl: https://www.flexpa.com/docs/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: The use of any content for commercial purposes is expressly prohibited, unless its use is subject to separately\n    negotiated Services Agreement with Flexpa.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: The content on the Flexpa Platform belongs to Flexpa or its affiliates. It includes text, graphics, logos,\n    images, videos, audio, downloads, data, and software.\nattribution:\n  required: null\n  text: null\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/flexpa/data-license/flexpa-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Flexpa's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- FHIR
- Patient Access
- Claims Data
- Health Insurance
---
