---
api_specs:
- filename: car-api-account-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Account API
  slug: car-api-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-account-api-openapi.yml
- filename: car-api-auth-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Auth API
  slug: car-api-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-auth-api-openapi.yml
- filename: car-api-bodies-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Bodies API
  slug: car-api-bodies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-bodies-api-openapi.yml
- filename: car-api-colors-exterior-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Colors (Exterior) API
  slug: car-api-colors-exterior-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-colors-exterior-api-openapi.yml
- filename: car-api-colors-interior-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Colors (Interior) API
  slug: car-api-colors-interior-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-colors-interior-api-openapi.yml
- filename: car-api-data-feeds-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Data Feeds API
  slug: car-api-data-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-data-feeds-api-openapi.yml
- filename: car-api-engines-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Engines API
  slug: car-api-engines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-engines-api-openapi.yml
- filename: car-api-makes-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Makes API
  slug: car-api-makes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-makes-api-openapi.yml
- filename: car-api-mileages-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Mileages API
  slug: car-api-mileages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-mileages-api-openapi.yml
- filename: car-api-models-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Models API
  slug: car-api-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-models-api-openapi.yml
- filename: car-api-trims-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Trims API
  slug: car-api-trims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-trims-api-openapi.yml
- filename: car-api-vehicle-attributes-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Vehicle Attributes API
  slug: car-api-vehicle-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-vehicle-attributes-api-openapi.yml
- filename: car-api-vin-decoder-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Vin Decoder API
  slug: car-api-vin-decoder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-vin-decoder-api-openapi.yml
- filename: car-api-years-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Years API
  slug: car-api-years-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-years-api-openapi.yml
- filename: car-api-license-plate-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) License Plate API
  slug: car-api-license-plate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-license-plate-api-openapi.yml
- filename: car-api-obd-codes-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) OBD Codes API
  slug: car-api-obd-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-obd-codes-api-openapi.yml
- filename: car-api-sub-models-api-openapi.yml
  format: yaml
  label: Car API (carapi.app) Sub Models API
  slug: car-api-sub-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/car-api/openapi/car-api-sub-models-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: does not permit redistribution of the Content in bulk or as a standalone dataset
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: CarAPI grants you a limited, non-exclusive, non-transferable, revocable license to access and use the Services in connection with your own applications, websites, and services, in accordance with your applicable subscription plan.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Car API (carapi.app)
output_license: custom
provenance_date: '2026-11-09'
provider_name: Car API (carapi.app)
provider_slug: car-api
slug: car-api-data-license
source_date: '2026-11-09'
source_filename: car-api-data-license.yml
source_heading: Data License
source_page: https://carapi.app/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Car API (carapi.app)\naid: car-api\nurl: https://carapi.app/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: CarAPI grants you a limited, non-exclusive, non-transferable, revocable license to access and use the Services\n    in connection with your own applications, websites, and services, in accordance with your applicable subscription\n    plan.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: does not permit redistribution of the Content in bulk or as a standalone dataset\nattribution:\n  required: null\n  text: null\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/car-api/data-license/car-api-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Car API (carapi.app)'s own page on 2026-11-09.
synthetic: false
tags:
- Automobiles
- Automotive Data
- Cars
- License Plate Decoder
- OBD-II
- Power-Sports
- Vehicle API
- Vehicle Specifications
- Vehicles
- VIN Decoding
---
