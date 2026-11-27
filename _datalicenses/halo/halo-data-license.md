---
api_specs:
- filename: halo-h5pc-api-openapi.yml
  format: yaml
  label: Halo H5pc API
  slug: halo-h5pc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo/openapi/halo-h5pc-api-openapi.yml
- filename: halo-h5-api-openapi.yml
  format: yaml
  label: Halo H5 API
  slug: halo-h5-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo/openapi/halo-h5-api-openapi.yml
- filename: halo-hw2-api-openapi.yml
  format: yaml
  label: Halo Hw2 API
  slug: halo-hw2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo/openapi/halo-hw2-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: 'display the following notice prominently (for example, in an "About" section of an application, or at the bottom of the home page of a website): This application is offered by , which is solely responsible for its content.'
  data:
    license: custom
    stance_commercial: conditional
    text: Microsoft collects Game Data pursuant to the Microsoft Services Agreement and Microsoft Privacy Statement.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Microsoft grants you a limited, revocable, nonexclusive, royalty free, non-transferable, non-sublicensable license to reproduce, distribute, publicly display, publicly perform, transmit, and communicate to the public the Game Data by means of a limited commercial Application that you develop.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Halo
output_license: custom
provenance_date: '2026-11-09'
provider_name: Halo
provider_slug: halo
slug: halo-data-license
source_date: '2026-11-09'
source_filename: halo-data-license.yml
source_heading: Data License
source_page: https://developer.haloapi.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Halo\naid: halo\nurl: https://developer.haloapi.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Microsoft grants you a limited, revocable, nonexclusive, royalty free, non-transferable, non-sublicensable\n    license to reproduce, distribute, publicly display, publicly perform, transmit, and communicate to the public\n    the Game Data by means of a limited commercial Application that you develop.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Microsoft collects Game Data pursuant to the Microsoft Services Agreement and\
  \ Microsoft Privacy Statement.\nattribution:\n  required: true\n  text: 'display the following notice prominently (for example, in an \"About\" section of an application, or at the\n    bottom of the home page of a website): This application is offered by , which is solely responsible for its\n    content.'\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/halo/data-license/halo-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Halo's own page on 2026-11-09.
synthetic: false
tags:
- Game Data
- Gaming
- Halo
- Microsoft
- Player Statistics
- Public APIs
- Video Games
- Xbox
---
