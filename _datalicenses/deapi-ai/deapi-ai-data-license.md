---
api_specs:
- filename: deapi-ai-client-api-api-openapi.yml
  format: yaml
  label: deapi-ai Client API
  slug: deapi-ai-client-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deapi-ai/openapi/deapi-ai-client-api-api-openapi.yml
- filename: deapi-ai-client-api-v2-api-openapi.yml
  format: yaml
  label: deapi-ai Client API v2 API
  slug: deapi-ai-client-api-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deapi-ai/openapi/deapi-ai-client-api-v2-api-openapi.yml
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
    license: custom
    stance_commercial: conditional
    text: For content generated through our Service, you are responsible for ensuring you have the necessary rights and licences for your intended use.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: deapi-ai
output_license: custom
provenance_date: '2026-11-09'
provider_name: deapi-ai
provider_slug: deapi-ai
slug: deapi-ai-data-license
source_date: '2026-11-09'
source_filename: deapi-ai-data-license.yml
source_heading: Data License
source_page: https://deapi.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: deapi-ai\naid: deapi-ai\nurl: https://deapi.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: For content generated through our Service, you are responsible for ensuring you have the necessary rights\n    and licences for your intended use.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/deapi-ai/data-license/deapi-ai-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from deapi-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Generative AI
- Open Source
- Image Generation
- Text-to-Speech
- Video Transcription
---
