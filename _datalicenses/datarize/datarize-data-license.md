---
api_specs:
- filename: datarize-openapi-generated.yml
  format: yaml
  label: Datarize API
  slug: datarize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datarize/openapi/_ae-authored/datarize-openapi-generated.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: '"회원"이 서비스 이용 과정에서 업로드하거나 생성한 데이터(이하 "고객 데이터")의 소유권은 "회원"에게 있습니다.'
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
name: Datarize
output_license: null
provenance_date: '2026-11-09'
provider_name: Datarize
provider_slug: datarize
slug: datarize-data-license
source_date: '2026-11-09'
source_filename: datarize-data-license.yml
source_heading: Data License
source_page: https://policy.datarize.ai/ko/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Datarize\naid: datarize\nurl: https://policy.datarize.ai/ko/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: '\"회원\"이 서비스 이용 과정에서 업로드하거나 생성한 데이터(이하 \"고객 데이터\")의 소유권은 \"회원\"에게 있습니다.'\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/datarize/data-license/datarize-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from Datarize's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- Analytics
- API Platform
- Enterprise
---
