---
api_specs:
- filename: openmenu-analytics-api-openapi.yml
  format: yaml
  label: OpenMenu Analytics API
  slug: openmenu-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmenu/openapi/openmenu-analytics-api-openapi.yml
- filename: openmenu-deals-api-openapi.yml
  format: yaml
  label: OpenMenu Deals API
  slug: openmenu-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmenu/openapi/openmenu-deals-api-openapi.yml
- filename: openmenu-ingredients-api-openapi.yml
  format: yaml
  label: OpenMenu Ingredients API
  slug: openmenu-ingredients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmenu/openapi/openmenu-ingredients-api-openapi.yml
- filename: openmenu-restaurants-api-openapi.yml
  format: yaml
  label: OpenMenu Restaurants API
  slug: openmenu-restaurants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmenu/openapi/openmenu-restaurants-api-openapi.yml
- filename: openmenu-search-api-openapi.yml
  format: yaml
  label: OpenMenu Search API
  slug: openmenu-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmenu/openapi/openmenu-search-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: conditional
    text: may not be redistributed, to include but not limited to an API or data dumps or public URL in any format except rendered for customers, without expressed written permission from Open Menu, LLC.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: Content obtained through the API or connected directly to through the restaurant's OpenMenu URL may be accessed, used and stored locally ("cached" or "caching" - only as outlined in section 3.2.1 on caching) for personal, commercial or non-profit use.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: OpenMenu
output_license: custom
provenance_date: '2026-11-10'
provider_name: OpenMenu
provider_slug: openmenu
slug: openmenu-data-license
source_date: '2026-11-10'
source_filename: openmenu-data-license.yml
source_heading: Data License
source_page: https://www.openmenu.com/tos-api.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: OpenMenu\naid: openmenu\nurl: https://www.openmenu.com/tos-api.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: Content obtained through the API or connected directly to through the restaurant's OpenMenu URL may be accessed,\n    used and stored locally (\"cached\" or \"caching\" - only as outlined in section 3.2.1 on caching) for personal,\n    commercial or non-profit use.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: may not be redistributed, to include but not limited to an API or data dumps or public URL in any format\n    except rendered\
  \ for customers, without expressed written permission from Open Menu, LLC.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/openmenu/data-license/openmenu-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from OpenMenu's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Menus
- Menu Data
- Search
- Nutrition
- Structured Data
---
