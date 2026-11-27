---
api_specs:
- filename: apitube-news-api-openapi.yml
  format: yaml
  label: APITube News API
  slug: apitube-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-news-api-openapi.yml
- filename: apitube-account-api-openapi.yml
  format: yaml
  label: APITube Account API
  slug: apitube-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-account-api-openapi.yml
- filename: apitube-fact-check-api-openapi.yml
  format: yaml
  label: APITube Fact Check API
  slug: apitube-fact-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-fact-check-api-openapi.yml
- filename: apitube-reference-api-openapi.yml
  format: yaml
  label: APITube Reference API
  slug: apitube-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-reference-api-openapi.yml
- filename: apitube-suggest-api-openapi.yml
  format: yaml
  label: APITube Suggest API
  slug: apitube-suggest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-suggest-api-openapi.yml
- filename: apitube-system-api-openapi.yml
  format: yaml
  label: APITube System API
  slug: apitube-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-system-api-openapi.yml
- filename: apitube-utilities-api-openapi.yml
  format: yaml
  label: APITube Utilities API
  slug: apitube-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-utilities-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: As part of the APITube Service, APITube collects and generates certain Data by aggregating information regarding publicly available web pages, utilizing APITube proprietary technology.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: unstated
    text: 'Unless applicable by law or expressly permitted by the owner, you will not, and will not permit your end users or others acting on your behalf to, do any of the following with the Data returned from the API: Misrepresent the ownership or the source;'
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: APITube
output_license: custom
provenance_date: '2026-11-09'
provider_name: APITube
provider_slug: apitube
slug: apitube-data-license
source_date: '2026-11-09'
source_filename: apitube-data-license.yml
source_heading: Data License
source_page: https://apitube.io/terms/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: APITube\naid: apitube\nurl: https://apitube.io/terms/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: unstated\n  text: 'Unless applicable by law or expressly permitted by the owner, you will not, and will not permit your end\n    users or others acting on your behalf to, do any of the following with the Data returned from the API: Misrepresent\n    the ownership or the source;'\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: As part of the APITube Service, APITube collects and generates certain Data by aggregating information regarding\n    publicly\
  \ available web pages, utilizing APITube proprietary technology.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/apitube/data-license/apitube-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from APITube's own page on 2026-11-09.
synthetic: false
tags:
- News
- Media Monitoring
- News API
- Fact Check
- Journalists
---
