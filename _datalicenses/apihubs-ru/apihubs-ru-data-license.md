---
api_specs:
- filename: apihubs-ru-default-api-openapi.yml
  format: yaml
  label: apihubs-ru Агент API
  slug: apihubs-ru-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apihubs-ru/openapi/apihubs-ru-default-api-openapi.yml
- filename: apihubs-ru-llm-api-openapi.yml
  format: yaml
  label: apihubs-ru LLM API
  slug: apihubs-ru-llm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apihubs-ru/openapi/apihubs-ru-llm-api-openapi.yml
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
    stance_commercial: allowed
    text: Оператор не заявляет исключительных прав на Результат. В объеме, допускаемом законодательством, Пользователь вправе использовать Результат по своему усмотрению, в том числе в коммерческих целях.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: apihubs-ru
output_license: custom
provenance_date: '2026-11-09'
provider_name: apihubs-ru
provider_slug: apihubs-ru
slug: apihubs-ru-data-license
source_date: '2026-11-09'
source_filename: apihubs-ru-data-license.yml
source_heading: Data License
source_page: https://apihubs.ru/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: apihubs-ru\naid: apihubs-ru\nurl: https://apihubs.ru/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: Оператор не заявляет исключительных прав на Результат. В объеме, допускаемом законодательством, Пользователь\n    вправе использовать Результат по своему усмотрению, в том числе в коммерческих целях.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/apihubs-ru/data-license/apihubs-ru-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from apihubs-ru's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Russian
- Software-as-a-Service
---
