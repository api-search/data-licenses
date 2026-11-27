---
api_specs:
- filename: mireye-ask-api-openapi.yml
  format: yaml
  label: Mireye Ask API
  slug: mireye-ask-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-ask-api-openapi.yml
- filename: mireye-ask-site-api-openapi.yml
  format: yaml
  label: Mireye Ask Site API
  slug: mireye-ask-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-ask-site-api-openapi.yml
- filename: mireye-auth-api-openapi.yml
  format: yaml
  label: Mireye Auth API
  slug: mireye-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-auth-api-openapi.yml
- filename: mireye-authorize-api-openapi.yml
  format: yaml
  label: Mireye Authorize API
  slug: mireye-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-authorize-api-openapi.yml
- filename: mireye-feature-requests-api-openapi.yml
  format: yaml
  label: Mireye Feature Requests API
  slug: mireye-feature-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-feature-requests-api-openapi.yml
- filename: mireye-fetch-api-openapi.yml
  format: yaml
  label: Mireye Fetch API
  slug: mireye-fetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-fetch-api-openapi.yml
- filename: mireye-healthz-api-openapi.yml
  format: yaml
  label: Mireye Healthz API
  slug: mireye-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-healthz-api-openapi.yml
- filename: mireye-mcp-api-openapi.yml
  format: yaml
  label: Mireye Mcp API
  slug: mireye-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-mcp-api-openapi.yml
- filename: mireye-meta-api-openapi.yml
  format: yaml
  label: Mireye Meta API
  slug: mireye-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-meta-api-openapi.yml
- filename: mireye-readyz-api-openapi.yml
  format: yaml
  label: Mireye Readyz API
  slug: mireye-readyz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-readyz-api-openapi.yml
- filename: mireye-register-api-openapi.yml
  format: yaml
  label: Mireye Register API
  slug: mireye-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-register-api-openapi.yml
- filename: mireye-revoke-api-openapi.yml
  format: yaml
  label: Mireye Revoke API
  slug: mireye-revoke-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-revoke-api-openapi.yml
- filename: mireye-sites-api-openapi.yml
  format: yaml
  label: Mireye Sites API
  slug: mireye-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-sites-api-openapi.yml
- filename: mireye-token-api-openapi.yml
  format: yaml
  label: Mireye Token API
  slug: mireye-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-token-api-openapi.yml
- filename: mireye-users-api-openapi.yml
  format: yaml
  label: Mireye Users API
  slug: mireye-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-users-api-openapi.yml
- filename: mireye-well-known-api-openapi.yml
  format: yaml
  label: Mireye .well Known API
  slug: mireye-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-well-known-api-openapi.yml
- filename: mireye-oauth-api-openapi.yml
  format: yaml
  label: Mireye OAUTH API
  slug: mireye-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-oauth-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: Making Licensed Property Data available to your customers, application users or other recipients requires the express authorization described in Schedule A.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: we grant you a limited, nonexclusive, nontransferable right to access the Services and use their authorized outputs for your property research, location analysis and related business activities.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Mireye
output_license: custom
provenance_date: '2026-11-10'
provider_name: Mireye
provider_slug: mireye
slug: mireye-data-license
source_date: '2026-11-10'
source_filename: mireye-data-license.yml
source_heading: Data License
source_page: https://www.mireye.com/legal/earth/2026-10-20-v1
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Mireye\naid: mireye\nurl: https://www.mireye.com/legal/earth/2026-10-20-v1\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: we grant you a limited, nonexclusive, nontransferable right to access the Services and use their authorized\n    outputs for your property research, location analysis and related business activities.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Making Licensed Property Data available to your customers, application users or other recipients requires\n    the express authorization described in Schedule\
  \ A.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/mireye/data-license/mireye-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Mireye's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Geospatial
- Geographic Information System
- Location
- AI Agents
- MCP
- Government Data
- Risk Management
- Insurance
- Data
---
