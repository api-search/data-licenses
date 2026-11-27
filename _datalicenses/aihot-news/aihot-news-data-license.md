---
api_specs:
- filename: aihot-news-agent-api-openapi.yml
  format: yaml
  label: AIHOT Agent API
  slug: aihot-news-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-agent-api-openapi.yml
- filename: aihot-news-dailies-api-openapi.yml
  format: yaml
  label: AIHOT Dailies API
  slug: aihot-news-dailies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-dailies-api-openapi.yml
- filename: aihot-news-hot-topics-api-openapi.yml
  format: yaml
  label: AIHOT Hot Topics API
  slug: aihot-news-hot-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-hot-topics-api-openapi.yml
- filename: aihot-news-items-api-openapi.yml
  format: yaml
  label: AIHOT Items API
  slug: aihot-news-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-items-api-openapi.yml
- filename: aihot-news-monthlies-api-openapi.yml
  format: yaml
  label: AIHOT Monthlies API
  slug: aihot-news-monthlies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-monthlies-api-openapi.yml
- filename: aihot-news-selected-api-openapi.yml
  format: yaml
  label: AIHOT Selected API
  slug: aihot-news-selected-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-selected-api-openapi.yml
- filename: aihot-news-stories-api-openapi.yml
  format: yaml
  label: AIHOT Stories API
  slug: aihot-news-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-stories-api-openapi.yml
- filename: aihot-news-weeklies-api-openapi.yml
  format: yaml
  label: AIHOT Weeklies API
  slug: aihot-news-weeklies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-weeklies-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: 取得书面授权的对外产品，须按授权文件约定展示来源、链接、Logo 或其他声明
  data:
    license: custom
    stance_commercial: conditional
    text: 只有把 AIHOT 用于对外商业产品、收费服务、客户交付、公开镜像或转售时，才需要提前联系我们取得书面授权。
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: 取得书面授权的对外产品，须按授权文件约定展示来源、链接、Logo 或其他声明
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: AIHOT
output_license: custom
provenance_date: '2026-11-09'
provider_name: AIHOT
provider_slug: aihot-news
slug: aihot-news-data-license
source_date: '2026-11-09'
source_filename: aihot-news-data-license.yml
source_heading: Data License
source_page: https://aihot.news/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: AIHOT\naid: aihot-news\nurl: https://aihot.news/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: 取得书面授权的对外产品，须按授权文件约定展示来源、链接、Logo 或其他声明\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: 只有把 AIHOT 用于对外商业产品、收费服务、客户交付、公开镜像或转售时，才需要提前联系我们取得书面授权。\nattribution:\n  required: true\n  text: 取得书面授权的对外产品，须按授权文件约定展示来源、链接、Logo 或其他声明\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/aihot-news/data-license/aihot-news-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from AIHOT's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
