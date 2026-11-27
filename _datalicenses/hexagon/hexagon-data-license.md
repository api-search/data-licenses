---
api_specs:
- filename: developerportal
  format: yaml
  label: Hexagon Nexus API
  slug: nexus-api
  spec_type: OpenAPI
  url: https://nexus.hexagon.com/developerportal
- filename: hexagon-eam-ion-api-openapi.yml
  format: yaml
  label: HxGN EAM REST API
  slug: hxgn-eam-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hexagon/openapi/hexagon-eam-ion-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: the Customer shall give notice that the Hexagon Content is “Copyright 2020 Hexagon” or as adjusted to the then current year
  data:
    license: custom
    stance_commercial: prohibited
    text: the Customer shall not use any Hexagon Content, Hexagon Verified Content and Third Party Content outside of HxDR.
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
name: Hexagon
output_license: null
provenance_date: '2026-11-09'
provider_name: Hexagon
provider_slug: hexagon
slug: hexagon-data-license
source_date: '2026-11-09'
source_filename: hexagon-data-license.yml
source_heading: Data License
source_page: https://geocloud.hexagon.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Hexagon\naid: hexagon\nurl: https://geocloud.hexagon.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: the Customer shall not use any Hexagon Content, Hexagon Verified Content and Third Party Content outside\n    of HxDR.\nattribution:\n  required: true\n  text: the Customer shall give notice that the Hexagon Content is “Copyright 2020 Hexagon” or as adjusted to the\n    then current year\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/hexagon/data-license/hexagon-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from Hexagon's own page on 2026-11-09.
synthetic: false
tags:
- Manufacturing
- Metrology
- Quality Inspection
- Digital Factory
- Production Monitoring
- Industrial IoT
- Smart Manufacturing
- Geospatial
---
