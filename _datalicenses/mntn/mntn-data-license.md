---
api_specs:
- filename: mntn-reporting-api-openapi.yml
  format: yaml
  label: MNTN Reporting API 3.0
  slug: mntn-reporting-api-30
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-reporting-api-openapi.yml
- filename: mntn-advertisers-api-openapi.yml
  format: yaml
  label: MNTN Advertisers API
  slug: mntn-advertisers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-advertisers-api-openapi.yml
- filename: mntn-attribution-api-openapi.yml
  format: yaml
  label: MNTN Attribution API
  slug: mntn-attribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-attribution-api-openapi.yml
- filename: mntn-audiences-api-openapi.yml
  format: yaml
  label: MNTN Audiences API
  slug: mntn-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-audiences-api-openapi.yml
- filename: mntn-batch-api-openapi.yml
  format: yaml
  label: MNTN Batch API
  slug: mntn-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-batch-api-openapi.yml
- filename: mntn-campaigns-api-openapi.yml
  format: yaml
  label: MNTN Campaigns API
  slug: mntn-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-campaigns-api-openapi.yml
- filename: mntn-creatives-api-openapi.yml
  format: yaml
  label: MNTN Creatives API
  slug: mntn-creatives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-creatives-api-openapi.yml
- filename: mntn-flights-api-openapi.yml
  format: yaml
  label: MNTN Flights API
  slug: mntn-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-flights-api-openapi.yml
- filename: mntn-organizations-api-openapi.yml
  format: yaml
  label: MNTN Organizations API
  slug: mntn-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-organizations-api-openapi.yml
- filename: mntn-pixel-api-openapi.yml
  format: yaml
  label: MNTN Pixel API
  slug: mntn-pixel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-pixel-api-openapi.yml
- filename: mntn-pmp-campaign-deals-api-openapi.yml
  format: yaml
  label: MNTN Pmp Campaign Deals API
  slug: mntn-pmp-campaign-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-pmp-campaign-deals-api-openapi.yml
- filename: mntn-pmp-channels-api-openapi.yml
  format: yaml
  label: MNTN Pmp Channels API
  slug: mntn-pmp-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-pmp-channels-api-openapi.yml
- filename: mntn-pmp-deal-groups-api-openapi.yml
  format: yaml
  label: MNTN Pmp Deal Groups API
  slug: mntn-pmp-deal-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-pmp-deal-groups-api-openapi.yml
- filename: mntn-pmp-deals-api-openapi.yml
  format: yaml
  label: MNTN Pmp Deals API
  slug: mntn-pmp-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-pmp-deals-api-openapi.yml
- filename: mntn-pmp-partners-api-openapi.yml
  format: yaml
  label: MNTN Pmp Partners API
  slug: mntn-pmp-partners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-pmp-partners-api-openapi.yml
- filename: mntn-reference-api-openapi.yml
  format: yaml
  label: MNTN Reference API
  slug: mntn-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-reference-api-openapi.yml
- filename: mntn-apidata-api-openapi.yml
  format: yaml
  label: MNTN Apidata API
  slug: mntn-apidata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-apidata-api-openapi.yml
- filename: mntn-apilist-api-openapi.yml
  format: yaml
  label: MNTN Apilist API
  slug: mntn-apilist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mntn/openapi/mntn-apilist-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    source: https://mountain.com/terms-of-use/
    stance_commercial: prohibited
    text: You may not modify, copy, reproduce, republish, upload, post, transmit or distribute in any way any material from the Site, including without limitation code or software, without MNTN’ express written permission.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: You may use AI Content in your advertising campaigns in the Platform
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: MNTN
output_license: custom
provenance_date: '2026-11-10'
provider_name: MNTN
provider_slug: mntn
slug: mntn-data-license
source_date: '2026-11-10'
source_filename: mntn-data-license.yml
source_heading: Data License
source_page: https://mountain.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: MNTN\naid: mntn\nurl: https://mountain.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://mountain.com/terms-and-conditions/\n  - https://mountain.com/terms-of-use/\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: You may use AI Content in your advertising campaigns in the Platform\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You may not modify, copy, reproduce, republish, upload, post, transmit or distribute in any way any material\n    from the Site, including without limitation code or software, without MNTN’ express written permission.\n\
  \  source: https://mountain.com/terms-of-use/\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/mntn/data-license/mntn-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from MNTN's own page on 2026-11-10.
synthetic: false
tags:
- Connected TV
- ctv-advertising
- Advertising
- Performance Marketing
- Streaming TV
- Media Buying
- Attribution
- Audience Targeting
- Conversion Tracking
- Programmatic Advertising
- Private-Marketplace
- Marketing Reporting
- AdTech
---
