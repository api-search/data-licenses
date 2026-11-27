---
api_specs:
- filename: aihcc-cloud-openapi-generated.yml
  format: yaml
  label: AIHCC API
  slug: aihcc-cloud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihcc-cloud/openapi/_ae-authored/aihcc-cloud-openapi-generated.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: 您提交检测的文本内容，其权利仍归您或原权利人所有；
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: 检测生成的标注与修正建议供您自由使用。
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: AIHCC
output_license: custom
provenance_date: '2026-11-09'
provider_name: AIHCC
provider_slug: aihcc-cloud
slug: aihcc-cloud-data-license
source_date: '2026-11-09'
source_filename: aihcc-cloud-data-license.yml
source_heading: Data License
source_page: https://aihcc.cloud/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: AIHCC\naid: aihcc-cloud\nurl: https://aihcc.cloud/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: 检测生成的标注与修正建议供您自由使用。\ndata:\n  license: null\n  stance_commercial: unstated\n  text: 您提交检测的文本内容，其权利仍归您或原权利人所有；\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/aihcc-cloud/data-license/aihcc-cloud-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from AIHCC's own page on 2026-11-09.
synthetic: false
tags:
- AI Safety
- Agent Tools
- Hallucination Detection
- Prompt Injection
- Chinese
---
