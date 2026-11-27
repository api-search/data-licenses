---
api_specs:
- filename: algoum-de-common-api-openapi.yml
  format: yaml
  label: algoum-de Common API
  slug: algoum-de-common-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-common-api-openapi.yml
- filename: algoum-de-events-api-openapi.yml
  format: yaml
  label: algoum-de Events API
  slug: algoum-de-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-events-api-openapi.yml
- filename: algoum-de-insider-api-openapi.yml
  format: yaml
  label: algoum-de Insider API
  slug: algoum-de-insider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-insider-api-openapi.yml
- filename: algoum-de-institutional-api-openapi.yml
  format: yaml
  label: algoum-de Institutional API
  slug: algoum-de-institutional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-institutional-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Upon publication, redistribution, or public display of evaluations, analyses, or applications based on data provided via the service, stating the source is mandatory.
  data:
    license: custom
    stance_commercial: conditional
    text: Redistribution, dissemination, publication, or provision of the content as an independent data service, data feed, API, download portal, or in any other format aimed at granting third parties direct access to the data as a standalone service
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: Commercial use of the content provided via the interface and web portal within the user's own products and services is permitted.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: algoum-de
output_license: custom
provenance_date: '2026-11-09'
provider_name: Algoum
provider_slug: algoum-de
slug: algoum-de-data-license
source_date: '2026-11-09'
source_filename: algoum-de-data-license.yml
source_heading: Data License
source_page: https://algoum.de/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: algoum-de\naid: algoum-de\nurl: https://algoum.de/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: Commercial use of the content provided via the interface and web portal within the user's own products and\n    services is permitted.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Redistribution, dissemination, publication, or provision of the content as an independent data service,\n    data feed, API, download portal, or in any other format aimed at granting third parties direct access to the\n    data as a standalone service\n\
  attribution:\n  required: true\n  text: Upon publication, redistribution, or public display of evaluations, analyses, or applications based on data\n    provided via the service, stating the source is mandatory.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/algoum-de/data-license/algoum-de-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from algoum-de's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- SEC
- Insider Trading
---
