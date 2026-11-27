---
api_specs:
- filename: tembo-agents-api-openapi.yml
  format: yaml
  label: Tembo Agents API
  slug: tembo-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-agents-api-openapi.yml
- filename: tembo-api-keys-api-openapi.yml
  format: yaml
  label: Tembo API Keys API
  slug: tembo-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-api-keys-api-openapi.yml
- filename: tembo-artifacts-api-openapi.yml
  format: yaml
  label: Tembo Artifacts API
  slug: tembo-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-artifacts-api-openapi.yml
- filename: tembo-authentication-api-openapi.yml
  format: yaml
  label: Tembo Authentication API
  slug: tembo-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-authentication-api-openapi.yml
- filename: tembo-billing-api-openapi.yml
  format: yaml
  label: Tembo Billing API
  slug: tembo-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-billing-api-openapi.yml
- filename: tembo-insights-api-openapi.yml
  format: yaml
  label: Tembo Insights API
  slug: tembo-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-insights-api-openapi.yml
- filename: tembo-integrations-api-openapi.yml
  format: yaml
  label: Tembo Integrations API
  slug: tembo-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-integrations-api-openapi.yml
- filename: tembo-mcp-connections-api-openapi.yml
  format: yaml
  label: Tembo MCP Connections API
  slug: tembo-mcp-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-mcp-connections-api-openapi.yml
- filename: tembo-messages-api-openapi.yml
  format: yaml
  label: Tembo Messages API
  slug: tembo-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-messages-api-openapi.yml
- filename: tembo-models-api-openapi.yml
  format: yaml
  label: Tembo Models API
  slug: tembo-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-models-api-openapi.yml
- filename: tembo-oauth-api-openapi.yml
  format: yaml
  label: Tembo OAuth API
  slug: tembo-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-oauth-api-openapi.yml
- filename: tembo-organizations-api-openapi.yml
  format: yaml
  label: Tembo Organizations API
  slug: tembo-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-organizations-api-openapi.yml
- filename: tembo-projects-api-openapi.yml
  format: yaml
  label: Tembo Projects API
  slug: tembo-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-projects-api-openapi.yml
- filename: tembo-pull-requests-api-openapi.yml
  format: yaml
  label: Tembo Pull requests API
  slug: tembo-pull-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-pull-requests-api-openapi.yml
- filename: tembo-repositories-api-openapi.yml
  format: yaml
  label: Tembo Repositories API
  slug: tembo-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-repositories-api-openapi.yml
- filename: tembo-runtimes-api-openapi.yml
  format: yaml
  label: Tembo Runtimes API
  slug: tembo-runtimes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-runtimes-api-openapi.yml
- filename: tembo-sessions-api-openapi.yml
  format: yaml
  label: Tembo Sessions API
  slug: tembo-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-sessions-api-openapi.yml
- filename: tembo-skills-api-openapi.yml
  format: yaml
  label: Tembo Skills API
  slug: tembo-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-skills-api-openapi.yml
- filename: tembo-users-api-openapi.yml
  format: yaml
  label: Tembo Users API
  slug: tembo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: Customer grants us a limited license to use Customer Data solely to provide the Service and as described in this Agreement.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: Customer retains all rights in Customer Data and any applications or code Customer develops using the Service, excluding any Tembo IP incorporated therein.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Tembo
output_license: custom
provenance_date: '2026-11-10'
provider_name: Tembo
provider_slug: tembo
slug: tembo-data-license
source_date: '2026-11-10'
source_filename: tembo-data-license.yml
source_heading: Data License
source_page: https://www.tembo.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Tembo\naid: tembo\nurl: https://www.tembo.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: Customer retains all rights in Customer Data and any applications or code Customer develops using the Service,\n    excluding any Tembo IP incorporated therein.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: Customer grants us a limited license to use Customer Data solely to provide the Service and as described\n    in this Agreement.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/tembo/data-license/tembo-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Tembo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- Coding Agents
- Developer Tools
- Sandbox
- MCP
- Automation
---
