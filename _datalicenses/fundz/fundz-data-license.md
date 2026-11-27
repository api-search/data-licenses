---
api_specs:
- filename: fundz-acquisitions-api-openapi.yml
  format: yaml
  label: Fundz Acquisitions API
  slug: fundz-acquisitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-acquisitions-api-openapi.yml
- filename: fundz-agreements-api-openapi.yml
  format: yaml
  label: Fundz Agreements API
  slug: fundz-agreements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-agreements-api-openapi.yml
- filename: fundz-crowdfundings-api-openapi.yml
  format: yaml
  label: Fundz Crowdfundings API
  slug: fundz-crowdfundings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-crowdfundings-api-openapi.yml
- filename: fundz-executives-api-openapi.yml
  format: yaml
  label: Fundz Executives API
  slug: fundz-executives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-executives-api-openapi.yml
- filename: fundz-fundings-api-openapi.yml
  format: yaml
  label: Fundz Fundings API
  slug: fundz-fundings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-fundings-api-openapi.yml
- filename: fundz-products-api-openapi.yml
  format: yaml
  label: Fundz Products API
  slug: fundz-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-products-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    source: https://app.fundz.net/fundz-data-licensing
    text: Attribution required
  data:
    license: null
    stance_commercial: conditional
    text: Fundz's compiled and entity-resolved datasets, including signals matched to specific companies such as office-expansion permits and trademark filings, are proprietary works of Fundz.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: 'Metered Agent API keys are licensed for internal use only: the licensee''s own agents, workflows and team.'
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Fundz
output_license: custom
provenance_date: '2026-11-09'
provider_name: Fundz
provider_slug: fundz
slug: fundz-data-license
source_date: '2026-11-09'
source_filename: fundz-data-license.yml
source_heading: Data License
source_page: https://www.fundz.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Fundz\naid: fundz\nurl: https://www.fundz.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://app.fundz.net/fundz-data-licensing\n  - https://www.fundz.net/terms\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: 'Metered Agent API keys are licensed for internal use only: the licensee''s own agents, workflows and team.'\ndata:\n  license: null\n  stance_commercial: conditional\n  text: Fundz's compiled and entity-resolved datasets, including signals matched to specific companies such as office-expansion\n    permits and trademark filings, are proprietary works of Fundz.\nattribution:\n\
  \  required: true\n  text: Attribution required\n  source: https://app.fundz.net/fundz-data-licensing\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/fundz/data-license/fundz-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Fundz's own page on 2026-11-09.
synthetic: false
tags:
- Business Intelligence
- Funding
- Private Markets
- Mergers and Acquisitions
- SEC Filings
- Signals
- Sales Intelligence
- MCP
- Agents
---
