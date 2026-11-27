---
api_specs:
- filename: evermuse-ingestion-api-openapi.yml
  format: yaml
  label: Evermuse Ingestion API
  slug: evermuse-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evermuse/openapi/evermuse-ingestion-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: Evermuse will not sell Customer Data or distribute it to any third party except as directed by Customer or as expressly permitted by these Terms and the DPA.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: As between the parties, Customer owns the Outputs derived from its Customer Data.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Evermuse
output_license: custom
provenance_date: '2026-11-09'
provider_name: Evermuse
provider_slug: evermuse
slug: evermuse-data-license
source_date: '2026-11-09'
source_filename: evermuse-data-license.yml
source_heading: Data License
source_page: https://www.evermuse.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Evermuse\naid: evermuse\nurl: https://www.evermuse.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: As between the parties, Customer owns the Outputs derived from its Customer Data.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Evermuse will not sell Customer Data or distribute it to any third party except as directed by Customer\n    or as expressly permitted by these Terms and the DPA.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/evermuse/data-license/evermuse-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Evermuse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Product Management
- Customer Feedback
- Voice of Customer
- Artificial Intelligence
- Data Ingestion
- Product Analytics
- MCP
- Developer Tools
---
