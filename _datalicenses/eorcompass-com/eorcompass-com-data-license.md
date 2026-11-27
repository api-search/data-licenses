---
api_specs:
- filename: eorcompass-com-dataset-api-openapi.yml
  format: yaml
  label: eorcompass-com Dataset API
  slug: eorcompass-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eorcompass-com/openapi/eorcompass-com-dataset-api-openapi.yml
- filename: eorcompass-com-enquiry-api-openapi.yml
  format: yaml
  label: eorcompass-com Enquiry API
  slug: eorcompass-com-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eorcompass-com/openapi/eorcompass-com-enquiry-api-openapi.yml
- filename: eorcompass-com-mcp-api-openapi.yml
  format: yaml
  label: eorcompass-com MCP API
  slug: eorcompass-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eorcompass-com/openapi/eorcompass-com-mcp-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Quote figures with the vendor name, the date shown, and a link back to the page you took them from.
  data:
    license: custom
    stance_commercial: conditional
    text: The EOR Compass Pricing Index is free to reuse with citation.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Quote figures with the vendor name, the date shown, and a link back to the page you took them from.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: eorcompass-com
output_license: custom
provenance_date: '2026-11-09'
provider_name: eorcompass-com
provider_slug: eorcompass-com
slug: eorcompass-com-data-license
source_date: '2026-11-09'
source_filename: eorcompass-com-data-license.yml
source_heading: Data License
source_page: https://eorcompass.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: eorcompass-com\naid: eorcompass-com\nurl: https://eorcompass.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Quote figures with the vendor name, the date shown, and a link back to the page you took them from.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: The EOR Compass Pricing Index is free to reuse with citation.\nattribution:\n  required: true\n  text: Quote figures with the vendor name, the date shown, and a link back to the page you took them from.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/eorcompass-com/data-license/eorcompass-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from eorcompass-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Employer of Record
- Payroll
- Pricing Comparison
- Human Resources
---
