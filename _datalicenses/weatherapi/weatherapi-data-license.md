---
api_specs:
- filename: weatherapi-alerts-api-openapi.yml
  format: yaml
  label: WeatherAPI Alerts API
  slug: weatherapi-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-alerts-api-openapi.yml
- filename: weatherapi-future-api-openapi.yml
  format: yaml
  label: WeatherAPI Future API
  slug: weatherapi-future-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-future-api-openapi.yml
- filename: weatherapi-geo-api-openapi.yml
  format: yaml
  label: WeatherAPI Geo API
  slug: weatherapi-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-geo-api-openapi.yml
- filename: weatherapi-history-api-openapi.yml
  format: yaml
  label: WeatherAPI History API
  slug: weatherapi-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-history-api-openapi.yml
- filename: weatherapi-marine-api-openapi.yml
  format: yaml
  label: WeatherAPI Marine API
  slug: weatherapi-marine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-marine-api-openapi.yml
- filename: weatherapi-sports-api-openapi.yml
  format: yaml
  label: WeatherAPI Sports API
  slug: weatherapi-sports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-sports-api-openapi.yml
- filename: weatherapi-weather-api-openapi.yml
  format: yaml
  label: WeatherAPI Weather API
  slug: weatherapi-weather-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-weather-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: If you are a Free API user then for all uses of the data, you will credit WeatherAPI.com by name or brand logo as the source of the data.
  data:
    license: custom
    stance_commercial: conditional
    text: You agree not to sell our weather data to any third party.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: allowed
    text: You may access, view and make copies of the data in the API for your personal or commercial use
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: WeatherAPI
output_license: custom
provenance_date: '2026-11-10'
provider_name: WeatherAPI
provider_slug: weatherapi
slug: weatherapi-data-license
source_date: '2026-11-10'
source_filename: weatherapi-data-license.yml
source_heading: Data License
source_page: https://www.weatherapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: WeatherAPI\naid: weatherapi\nurl: https://www.weatherapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: allowed\n  text: You may access, view and make copies of the data in the API for your personal or commercial use\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: You agree not to sell our weather data to any third party.\nattribution:\n  required: true\n  text: If you are a Free API user then for all uses of the data, you will credit WeatherAPI.com by name or brand\n    logo as the source of the data.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/weatherapi/data-license/weatherapi-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from WeatherAPI's own page on 2026-11-10.
synthetic: false
tags:
- Weather
- Forecast
- History
- Marine
- Astronomy
- Geolocation
- Sports
- Alerts
- Public APIs
---
