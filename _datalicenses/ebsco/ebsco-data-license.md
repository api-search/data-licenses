---
api_specs:
- filename: ebsco-content-api-openapi.yml
  format: yaml
  label: EBSCO Content API
  slug: ebsco-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ebsco/openapi/ebsco-content-api-openapi.yml
- filename: ebsco-publishers-api-openapi.yml
  format: yaml
  label: EBSCO Publishers API
  slug: ebsco-publishers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ebsco/openapi/ebsco-publishers-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: 'All copies must include the following copyright notice: " © 2020 EBSCO Information Services. All rights reserved."'
  data:
    license: custom
    stance_commercial: prohibited
    text: not to reproduce, redistribute, republish, duplicate, copy, display, sell, rent, sub-license, trade or resell any content or other aspect of the Website for any commercial purpose
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
name: EBSCO
output_license: null
provenance_date: '2026-11-09'
provider_name: EBSCO
provider_slug: ebsco
slug: ebsco-data-license
source_date: '2026-11-09'
source_filename: ebsco-data-license.yml
source_heading: Data License
source_page: https://legal.ebsco.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: EBSCO\naid: ebsco\nurl: https://legal.ebsco.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: not to reproduce, redistribute, republish, duplicate, copy, display, sell, rent, sub-license, trade or resell\n    any content or other aspect of the Website for any commercial purpose\nattribution:\n  required: true\n  text: 'All copies must include the following copyright notice: \" © 2020 EBSCO Information Services. All rights\n    reserved.\"'\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/ebsco/data-license/ebsco-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from EBSCO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Research
- Library
- Education
- Information
---
