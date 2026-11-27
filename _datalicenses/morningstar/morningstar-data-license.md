---
api_specs:
- filename: morningstar-token-api-openapi.yml
  format: yaml
  label: Morningstar Authentication API
  slug: morningstar-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-token-api-openapi.yml
- filename: morningstar-corporate-actions-api-openapi.yml
  format: yaml
  label: Morningstar Time Series API
  slug: morningstar-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-corporate-actions-api-openapi.yml
- filename: morningstar-screener-api-openapi.yml
  format: yaml
  label: Morningstar Screener APIs
  slug: morningstar-screener-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-screener-api-openapi.yml
- filename: morningstar-aggregates-financials-api-openapi.yml
  format: yaml
  label: Morningstar Investment Details APIs
  slug: morningstar-investment-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-aggregates-financials-api-openapi.yml
- filename: morningstar-investment-list-api-openapi.yml
  format: yaml
  label: Morningstar Investment List API
  slug: morningstar-investment-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-investment-list-api-openapi.yml
- filename: morningstar-esg-api-openapi.yml
  format: yaml
  label: Morningstar Portfolio Analysis APIs
  slug: morningstar-portfolio-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-esg-api-openapi.yml
- filename: morningstar-analyst-highlights-api-openapi.yml
  format: yaml
  label: Morningstar AI Insights API
  slug: morningstar-ai-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-analyst-highlights-api-openapi.yml
- filename: morningstar-scenario-analysis-api-openapi.yml
  format: yaml
  label: Morningstar Scenario Analysis API
  slug: morningstar-scenario-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-scenario-analysis-api-openapi.yml
- filename: morningstar-clients-api-openapi.yml
  format: yaml
  label: Morningstar Risk Profiler API
  slug: morningstar-risk-profiler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-clients-api-openapi.yml
- filename: morningstar-investments-universe-api-openapi.yml
  format: yaml
  label: Morningstar Universe API
  slug: morningstar-universe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-investments-universe-api-openapi.yml
- filename: morningstar-benchmarkfees-api-openapi.yml
  format: yaml
  label: Morningstar Financial Planning APIs
  slug: morningstar-financial-planning-apis
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-benchmarkfees-api-openapi.yml
- filename: morningstar-attribution-api-openapi.yml
  format: yaml
  label: Morningstar Investment Analysis APIs
  slug: morningstar-investment-analysis-apis
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-attribution-api-openapi.yml
- filename: morningstar-accounts-api-openapi.yml
  format: yaml
  label: Morningstar ByAllAccounts API
  slug: morningstar-byallaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-accounts-api-openapi.yml
- filename: morningstar-morningstar-agent-api-openapi.yml
  format: yaml
  label: Morningstar Agent API
  slug: morningstar-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-morningstar-agent-api-openapi.yml
- filename: morningstar-oauth-api-openapi.yml
  format: yaml
  label: Morningstar OAUTH API
  slug: morningstar-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-oauth-api-openapi.yml
- filename: morningstar-datapoints-api-openapi.yml
  format: yaml
  label: Morningstar Datapoints API
  slug: morningstar-datapoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morningstar/openapi/morningstar-datapoints-api-openapi.yml
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
    stance_commercial: prohibited
    text: Except as expressly set forth in this Agreement, you may not modify, copy, distribute, disclose, retransmit, sell, publish, broadcast, or circulate the Service, or any portion of it
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Morningstar
output_license: custom
provenance_date: '2026-11-10'
provider_name: Morningstar
provider_slug: morningstar
slug: morningstar-data-license
source_date: '2026-11-10'
source_filename: morningstar-data-license.yml
source_heading: Data License
source_page: https://www.morningstar.com/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Morningstar\naid: morningstar\nurl: https://www.morningstar.com/user-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: Except as expressly set forth in this Agreement, you may not modify, copy, distribute, disclose, retransmit,\n    sell, publish, broadcast, or circulate the Service, or any portion of it\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/morningstar/data-license/morningstar-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from Morningstar's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Market Data
- Investing
- Stocks
- Fund
- Real-Time
- Reference Data
- Portfolio Analytics
- Research
- Index
- Wealth Management
- Financial Data
---
