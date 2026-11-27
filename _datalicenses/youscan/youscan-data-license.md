---
api_specs:
- filename: youscan-data-import-api-openapi.yml
  format: yaml
  label: YouScan Data Import API
  slug: youscan-data-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-data-import-api-openapi.yml
- filename: youscan-history-api-openapi.yml
  format: yaml
  label: YouScan History API
  slug: youscan-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-history-api-openapi.yml
- filename: youscan-mentions-api-openapi.yml
  format: yaml
  label: YouScan Mentions API
  slug: youscan-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-mentions-api-openapi.yml
- filename: youscan-spaces-api-openapi.yml
  format: yaml
  label: YouScan Spaces API
  slug: youscan-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-spaces-api-openapi.yml
- filename: youscan-statistics-api-openapi.yml
  format: yaml
  label: YouScan Statistics API
  slug: youscan-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-statistics-api-openapi.yml
- filename: youscan-tags-api-openapi.yml
  format: yaml
  label: YouScan Tags API
  slug: youscan-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-tags-api-openapi.yml
- filename: youscan-topics-api-openapi.yml
  format: yaml
  label: YouScan Topics API
  slug: youscan-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-topics-api-openapi.yml
- filename: youscan-webhook-api-openapi.yml
  format: yaml
  label: YouScan Webhook API
  slug: youscan-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-webhook-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: YouScan does not claim ownership of, or grant independent licenses to, the Third-Party data (content) accessed through its platform.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: The creation by the Client, through Data Analysis, of commercially valuable information (" Deliverables "), which may be used by the Client for its legitimate business purposes.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: YouScan
output_license: custom
provenance_date: '2026-11-10'
provider_name: YouScan
provider_slug: youscan
slug: youscan-data-license
source_date: '2026-11-10'
source_filename: youscan-data-license.yml
source_heading: Data License
source_page: https://youscan.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: YouScan\naid: youscan\nurl: https://youscan.io/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: The creation by the Client, through Data Analysis, of commercially valuable information (\" Deliverables\n    \"), which may be used by the Client for its legitimate business purposes.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: YouScan does not claim ownership of, or grant independent licenses to, the Third-Party data (content) accessed\n    through its platform.\nattribution:\n  required: null\n  text: null\n\
  interface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/youscan/data-license/youscan-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from YouScan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media Listening
- Social Intelligence
- Consumer Insights
- Sentiment Analysis
- Media Monitoring
- Analytics
- Artificial Intelligence
---
