---
api_specs:
- filename: fred-categories-api-openapi.yml
  format: yaml
  label: FRED Categories API
  slug: fred-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-categories-api-openapi.yml
- filename: fred-observations-api-openapi.yml
  format: yaml
  label: FRED Observations API
  slug: fred-observations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-observations-api-openapi.yml
- filename: fred-regional-data-api-openapi.yml
  format: yaml
  label: FRED Regional Data API
  slug: fred-regional-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-regional-data-api-openapi.yml
- filename: fred-releases-api-openapi.yml
  format: yaml
  label: FRED Releases API
  slug: fred-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-releases-api-openapi.yml
- filename: fred-series-api-openapi.yml
  format: yaml
  label: FRED Series API
  slug: fred-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-series-api-openapi.yml
- filename: fred-series-data-api-openapi.yml
  format: yaml
  label: FRED Series Data API
  slug: fred-series-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-series-data-api-openapi.yml
- filename: fred-series-group-api-openapi.yml
  format: yaml
  label: FRED Series Group API
  slug: fred-series-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-series-group-api-openapi.yml
- filename: fred-shapes-api-openapi.yml
  format: yaml
  label: FRED Shapes API
  slug: fred-shapes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-shapes-api-openapi.yml
- filename: fred-sources-api-openapi.yml
  format: yaml
  label: FRED Sources API
  slug: fred-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-sources-api-openapi.yml
- filename: fred-tags-api-openapi.yml
  format: yaml
  label: FRED Tags API
  slug: fred-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fred/openapi/fred-tags-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: You must include proper attribution with the use of any FRED® Content.
  data:
    license: custom
    stance_commercial: conditional
    text: provided you have not engaged in any prohibited uses, you may use these data series with proper attribution of the source and acknowledgment that you obtained the data from FRED
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: the Bank grants you a non-exclusive, limited right and license to display and reproduce the charts and graphs, and to permit others to, publish, reproduce and distribute the charts and graphs
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: FRED
output_license: custom
provenance_date: '2026-11-09'
provider_name: FRED
provider_slug: fred
slug: fred-data-license
source_date: '2026-11-09'
source_filename: fred-data-license.yml
source_heading: Data License
source_page: https://fred.stlouisfed.org/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: FRED\naid: fred\nurl: https://fred.stlouisfed.org/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: the Bank grants you a non-exclusive, limited right and license to display and reproduce the charts and graphs,\n    and to permit others to, publish, reproduce and distribute the charts and graphs\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: provided you have not engaged in any prohibited uses, you may use these data series with proper attribution\n    of the source and acknowledgment that you obtained the data from\
  \ FRED\nattribution:\n  required: true\n  text: You must include proper attribution with the use of any FRED® Content.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/fred/data-license/fred-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from FRED's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Government
- Economic Data
- Federal Reserve
- Time Series
- Open Data
- Public APIs
- Government Data
---
