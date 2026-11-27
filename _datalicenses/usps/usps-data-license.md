---
api_specs:
- filename: usps-addresses-api-openapi.yml
  format: yaml
  label: United States Postal Service Addresses API
  slug: usps-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-addresses-api-openapi.yml
- filename: usps-carrier-pickup-api-openapi.yml
  format: yaml
  label: United States Postal Service Carrier Pickup API
  slug: usps-carrier-pickup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-carrier-pickup-api-openapi.yml
- filename: usps-domestic-prices-api-openapi.yml
  format: yaml
  label: United States Postal Service Domestic Prices API
  slug: usps-domestic-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-domestic-prices-api-openapi.yml
- filename: usps-files-api-openapi.yml
  format: yaml
  label: United States Postal Service Files API
  slug: usps-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-files-api-openapi.yml
- filename: usps-listener-url-specification-api-openapi.yml
  format: yaml
  label: United States Postal Service Listener URL Specification API
  slug: usps-listener-url-specification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-listener-url-specification-api-openapi.yml
- filename: usps-resources-api-openapi.yml
  format: yaml
  label: United States Postal Service Resources API
  slug: usps-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-resources-api-openapi.yml
- filename: usps-tracking-api-openapi.yml
  format: yaml
  label: United States Postal Service Tracking API
  slug: usps-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-tracking-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: resell or license for a fee the data from the Services or any derivative thereof;
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: The data You access through the Services may be used for commercial informational purposes solely to provide information regarding Your shipping and mailing transactions using USPS products and services.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: United States Postal Service
output_license: custom
provenance_date: '2026-11-10'
provider_name: United States Postal Service
provider_slug: usps
slug: usps-data-license
source_date: '2026-11-10'
source_filename: usps-data-license.yml
source_heading: Data License
source_page: https://developers.usps.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: United States Postal Service\naid: usps\nurl: https://developers.usps.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: The data You access through the Services may be used for commercial informational purposes solely to provide\n    information regarding Your shipping and mailing transactions using USPS products and services.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: resell or license for a fee the data from the Services or any derivative thereof;\nattribution:\n  required: null\n  text: null\ninterface_license:\n\
  \  url: null\n"
source_yaml_url: https://artifacts.apis.io/usps/data-license/usps-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from United States Postal Service's own page on 2026-11-10.
synthetic: false
tags:
- Government
- Postal Service
- Shipping
- Logistics
- Address Validation
- Package Tracking
---
