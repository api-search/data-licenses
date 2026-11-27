---
api_specs:
- filename: loki-config-api-openapi.yml
  format: yaml
  label: Loki Config API
  slug: loki-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loki/openapi/loki-config-api-openapi.yml
- filename: loki-loki-api-openapi.yml
  format: yaml
  label: Loki API
  slug: loki-loki-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loki/openapi/loki-loki-api-openapi.yml
- filename: loki-metrics-api-openapi.yml
  format: yaml
  label: Loki Metrics API
  slug: loki-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loki/openapi/loki-metrics-api-openapi.yml
- filename: loki-otlp-api-openapi.yml
  format: yaml
  label: Loki Otlp API
  slug: loki-otlp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loki/openapi/loki-otlp-api-openapi.yml
- filename: loki-ready-api-openapi.yml
  format: yaml
  label: Loki Ready API
  slug: loki-ready-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loki/openapi/loki-ready-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: AGPL-3.0
    stance_commercial: conditional
    text: You may charge any price or no price for each copy that you convey, and you may offer support or warranty protection for a fee.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: null
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Loki
output_license: null
provenance_date: '2026-11-09'
provider_name: Loki
provider_slug: loki
slug: loki-data-license
source_date: '2026-11-09'
source_filename: loki-data-license.yml
source_heading: Data License
source_page: https://github.com/grafana/loki/blob/main/LICENSE
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Loki\naid: loki\nurl: https://github.com/grafana/loki/blob/main/LICENSE\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: AGPL-3.0\n  stance_commercial: conditional\n  text: You may charge any price or no price for each copy that you convey, and you may offer support or warranty\n    protection for a fee.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/loki/data-license/loki-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Loki's own page on 2026-11-09.
synthetic: false
tags:
- Logging
- Observability
- Open Source
- Grafana
---
