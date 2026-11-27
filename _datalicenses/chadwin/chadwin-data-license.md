---
api_specs:
- filename: chadwin-companies-api-openapi.yml
  format: yaml
  label: Chadwin Companies API
  slug: chadwin-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-companies-api-openapi.yml
- filename: chadwin-company-kpis-api-openapi.yml
  format: yaml
  label: Chadwin Company KPIs API
  slug: chadwin-company-kpis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-company-kpis-api-openapi.yml
- filename: chadwin-company-reports-api-openapi.yml
  format: yaml
  label: Chadwin Company reports API
  slug: chadwin-company-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-company-reports-api-openapi.yml
- filename: chadwin-current-reports-api-openapi.yml
  format: yaml
  label: Chadwin Current reports API
  slug: chadwin-current-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-current-reports-api-openapi.yml
- filename: chadwin-insider-activity-api-openapi.yml
  format: yaml
  label: Chadwin Insider activity API
  slug: chadwin-insider-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-insider-activity-api-openapi.yml
- filename: chadwin-institutional-holdings-api-openapi.yml
  format: yaml
  label: Chadwin Institutional holdings API
  slug: chadwin-institutional-holdings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-institutional-holdings-api-openapi.yml
- filename: chadwin-normalized-financial-statements-api-openapi.yml
  format: yaml
  label: Chadwin Normalized financial statements API
  slug: chadwin-normalized-financial-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-normalized-financial-statements-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: Public facts obtained from SEC filings and other public sources remain public facts. Chadwin and its licensors retain their rights in the service software, documentation, design, brand, and protectable selection, normalization, organization, and compilation of data.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: A Business plan permits internal business use and use of API results in customer-facing websites, applications, and agents operated as part of your business.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Chadwin
output_license: custom
provenance_date: '2026-11-09'
provider_name: Chadwin
provider_slug: chadwin
slug: chadwin-data-license
source_date: '2026-11-09'
source_filename: chadwin-data-license.yml
source_heading: Data License
source_page: https://www.chadwin.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Chadwin\naid: chadwin\nurl: https://www.chadwin.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: A Business plan permits internal business use and use of API results in customer-facing websites, applications,\n    and agents operated as part of your business.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: Public facts obtained from SEC filings and other public sources remain public facts. Chadwin and its licensors\n    retain their rights in the service software, documentation, design, brand, and protectable selection, normalization,\n\
  \    organization, and compilation of data.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/chadwin/data-license/chadwin-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Chadwin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Analytics
- Integration
- Enterprise
---
