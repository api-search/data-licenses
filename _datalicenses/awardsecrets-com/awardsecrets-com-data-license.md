---
api_specs:
- filename: awardsecrets-com-api-php-api-openapi.yml
  format: yaml
  label: AwardSecrets Api.php API
  slug: awardsecrets-com-api-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardsecrets-com/openapi/awardsecrets-com-api-php-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: 'On Sandbox and Developer plans, where you display Output publicly, attribute it to AwardSecrets in a reasonably visible way (for example, "Award data: AwardSecrets", linked to awardsecrets.com).'
  data:
    license: custom
    stance_commercial: prohibited
    text: You may not resell, sublicense, syndicate, publish as a feed, or otherwise provide the Output to third parties as a data set
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: While your membership is active, we grant you a limited, revocable, non-exclusive, non-transferable licence to use the Output within your own products, services and work.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: AwardSecrets
output_license: custom
provenance_date: '2026-11-09'
provider_name: AwardSecrets
provider_slug: awardsecrets-com
slug: awardsecrets-com-data-license
source_date: '2026-11-09'
source_filename: awardsecrets-com-data-license.yml
source_heading: Data License
source_page: https://awardsecrets.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: AwardSecrets\naid: awardsecrets-com\nurl: https://awardsecrets.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: While your membership is active, we grant you a limited, revocable, non-exclusive, non-transferable licence\n    to use the Output within your own products, services and work.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You may not resell, sublicense, syndicate, publish as a feed, or otherwise provide the Output to third parties\n    as a data set\nattribution:\n  required: true\n  text: 'On Sandbox and Developer plans,\
  \ where you display Output publicly, attribute it to AwardSecrets in a reasonably\n    visible way (for example, \"Award data: AwardSecrets\", linked to awardsecrets.com).'\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/awardsecrets-com/data-license/awardsecrets-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from AwardSecrets's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Awards
- Flights
- Points
- Company
---
