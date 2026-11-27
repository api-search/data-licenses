---
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: The user is not authorised to sell or offer for sale, to license or to transfer information, in particular the content available on the portal.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: the user shall only use the content provided for professional performance of maintenance and repair of vehicles and motorcycles manufactured by the operator
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: BMW
output_license: custom
provenance_date: '2026-11-09'
provider_name: BMW
provider_slug: bmw
slug: bmw-data-license
source_date: '2026-11-09'
source_filename: bmw-data-license.yml
source_heading: Data License
source_page: https://aos.bmwgroup.com/conditions-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: BMW\naid: bmw\nurl: https://aos.bmwgroup.com/conditions-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: the user shall only use the content provided for professional performance of maintenance and repair of vehicles\n    and motorcycles manufactured by the operator\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: The user is not authorised to sell or offer for sale, to license or to transfer information, in particular\n    the content available on the portal.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/bmw/data-license/bmw-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from BMW's own page on 2026-11-09.
synthetic: false
tags:
- Automobiles
- Cars
- Vehicles
- Automotive
- Connected Vehicles
---
