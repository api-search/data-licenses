---
api_specs:
- filename: slng-account-api-openapi.yml
  format: yaml
  label: SLNG Account API
  slug: slng-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-account-api-openapi.yml
- filename: slng-agents-api-openapi.yml
  format: yaml
  label: SLNG Agents API
  slug: slng-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-agents-api-openapi.yml
- filename: slng-calls-api-openapi.yml
  format: yaml
  label: SLNG Calls API
  slug: slng-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-calls-api-openapi.yml
- filename: slng-catalog-api-openapi.yml
  format: yaml
  label: SLNG Catalog API
  slug: slng-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-catalog-api-openapi.yml
- filename: slng-deepgram-aura-2-api-openapi.yml
  format: yaml
  label: SLNG Deepgram Aura 2 API
  slug: slng-deepgram-aura-2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-deepgram-aura-2-api-openapi.yml
- filename: slng-deepgram-nova-3-api-openapi.yml
  format: yaml
  label: SLNG Deepgram Nova 3 API
  slug: slng-deepgram-nova-3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-deepgram-nova-3-api-openapi.yml
- filename: slng-inworld-max-1-5-api-openapi.yml
  format: yaml
  label: SLNG Inworld Max 1.5 API
  slug: slng-inworld-max-1-5-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-inworld-max-1-5-api-openapi.yml
- filename: slng-orpheus-english-api-openapi.yml
  format: yaml
  label: SLNG Orpheus English API
  slug: slng-orpheus-english-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-orpheus-english-api-openapi.yml
- filename: slng-pronunciation-dictionaries-api-openapi.yml
  format: yaml
  label: SLNG Pronunciation dictionaries API
  slug: slng-pronunciation-dictionaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-pronunciation-dictionaries-api-openapi.yml
- filename: slng-rime-arcana-v2-api-openapi.yml
  format: yaml
  label: SLNG Rime Arcana v2 API
  slug: slng-rime-arcana-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-rime-arcana-v2-api-openapi.yml
- filename: slng-rime-arcana-v3-api-openapi.yml
  format: yaml
  label: SLNG Rime Arcana v3 API
  slug: slng-rime-arcana-v3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-rime-arcana-v3-api-openapi.yml
- filename: slng-rime-coda-api-openapi.yml
  format: yaml
  label: SLNG Rime Coda API
  slug: slng-rime-coda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-rime-coda-api-openapi.yml
- filename: slng-sessions-api-openapi.yml
  format: yaml
  label: SLNG Sessions API
  slug: slng-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-sessions-api-openapi.yml
- filename: slng-speechmatics-api-openapi.yml
  format: yaml
  label: SLNG Speechmatics API
  slug: slng-speechmatics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-speechmatics-api-openapi.yml
- filename: slng-whisper-large-v3-api-openapi.yml
  format: yaml
  label: SLNG Whisper Large v3 API
  slug: slng-whisper-large-v3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-whisper-large-v3-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: You retain ownership of content you submit for processing. By using our services, you grant us a limited license to process your content solely to provide the requested services.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You may use AI-generated outputs subject to these Terms, but we make no representations regarding the intellectual property status of such outputs.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: SLNG
output_license: custom
provenance_date: '2026-11-10'
provider_name: SLNG
provider_slug: slng
slug: slng-data-license
source_date: '2026-11-10'
source_filename: slng-data-license.yml
source_heading: Data License
source_page: https://slng.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: SLNG\naid: slng\nurl: https://slng.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You may use AI-generated outputs subject to these Terms, but we make no representations regarding the intellectual\n    property status of such outputs.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: You retain ownership of content you submit for processing. By using our services, you grant us a limited\n    license to process your content solely to provide the requested services.\nattribution:\n  required: null\n  text: null\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/slng/data-license/slng-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from SLNG's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Speech
- Voice
- Speech-to-Text
- Text-to-Speech
- Voice AI
- Voice Agents
- Transcription
- Speech Recognition
- Artificial Intelligence
- API Gateway
- Real-Time
---
