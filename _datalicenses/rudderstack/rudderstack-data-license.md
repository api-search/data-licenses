---
api_specs:
- filename: rudderstack-event-streaming-asyncapi.yml
  format: yaml
  label: RudderStack Webhook Source API
  slug: rudderstack-webhook-source-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/rudderstack/asyncapi/rudderstack-event-streaming-asyncapi.yml
- filename: rudderstack-http-api-api-openapi.yml
  format: yaml
  label: RudderStack HTTP API
  slug: rudderstack-http-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rudderstack/openapi/rudderstack-http-api-api-openapi.yml
- filename: rudderstack-internal-api-api-openapi.yml
  format: yaml
  label: RudderStack Internal API
  slug: rudderstack-internal-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rudderstack/openapi/rudderstack-internal-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Customer hereby grants RudderStack a non-exclusive, non-transferable, non-sublicensable, worldwide, royalty-free license to use, transfer and process the Customer Data for the sole purpose of RudderStack providing the Services
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: Outputs generated for Customer are, as between the parties, Customer Data owned by Customer under §2.3, subject to the licenses granted in §2.3 and this §2.6
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: RudderStack
output_license: custom
provenance_date: '2026-11-10'
provider_name: RudderStack
provider_slug: rudderstack
slug: rudderstack-data-license
source_date: '2026-11-10'
source_filename: rudderstack-data-license.yml
source_heading: Data License
source_page: https://www.rudderstack.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: RudderStack\naid: rudderstack\nurl: https://www.rudderstack.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Outputs generated for Customer are, as between the parties, Customer Data owned by Customer under §2.3,\n    subject to the licenses granted in §2.3 and this §2.6\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Customer hereby grants RudderStack a non-exclusive, non-transferable, non-sublicensable, worldwide, royalty-free\n    license to use, transfer and process the Customer Data for the sole\
  \ purpose of RudderStack providing the Services\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/rudderstack/data-license/rudderstack-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from RudderStack's own page on 2026-11-10.
synthetic: false
tags:
- Customer Data Platform
- CDP
- Data Pipeline
- Open Source
- Event Streaming
- Reverse ETL
- Analytics
- Identity Resolution
---
