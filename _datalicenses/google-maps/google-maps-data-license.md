---
api_specs:
- filename: google-maps-pollen-forecast-api-openapi.yml
  format: yaml
  label: Google Maps Platform Maps Pollen Forecast API
  slug: google-maps-pollen-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-pollen-forecast-api-openapi.yml
- filename: google-maps-address-validation-v1-api-openapi.yml
  format: yaml
  label: Google Maps Platform Address Validation V1 API
  slug: google-maps-address-validation-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-address-validation-v1-api-openapi.yml
- filename: google-maps-air-quality-currentconditions-api-openapi.yml
  format: yaml
  label: Google Maps Platform Air Quality CurrentConditions API
  slug: google-maps-air-quality-currentconditions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-air-quality-currentconditions-api-openapi.yml
- filename: google-maps-air-quality-forecast-api-openapi.yml
  format: yaml
  label: Google Maps Platform Air Quality Forecast API
  slug: google-maps-air-quality-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-air-quality-forecast-api-openapi.yml
- filename: google-maps-air-quality-history-api-openapi.yml
  format: yaml
  label: Google Maps Platform Air Quality History API
  slug: google-maps-air-quality-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-air-quality-history-api-openapi.yml
- filename: google-maps-air-quality-maptypes-api-openapi.yml
  format: yaml
  label: Google Maps Platform Air Quality MapTypes API
  slug: google-maps-air-quality-maptypes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-air-quality-maptypes-api-openapi.yml
- filename: google-maps-area-insights-v1-api-openapi.yml
  format: yaml
  label: Google Maps Platform Area Insights V1 API
  slug: google-maps-area-insights-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-area-insights-v1-api-openapi.yml
- filename: google-maps-pollen-maptypes-api-openapi.yml
  format: yaml
  label: Google Maps Platform Pollen MapTypes API
  slug: google-maps-pollen-maptypes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-pollen-maptypes-api-openapi.yml
- filename: google-maps-solar-buildinginsights-api-openapi.yml
  format: yaml
  label: Google Maps Platform Solar BuildingInsights API
  slug: google-maps-solar-buildinginsights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-solar-buildinginsights-api-openapi.yml
- filename: google-maps-solar-datalayers-api-openapi.yml
  format: yaml
  label: Google Maps Platform Solar DataLayers API
  slug: google-maps-solar-datalayers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-solar-datalayers-api-openapi.yml
- filename: google-maps-solar-geotiff-api-openapi.yml
  format: yaml
  label: Google Maps Platform Solar GeoTiff API
  slug: google-maps-solar-geotiff-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-solar-geotiff-api-openapi.yml
- filename: google-maps-street-view-publish-photo-api-openapi.yml
  format: yaml
  label: Google Maps Platform Street View Publish Photo API
  slug: google-maps-street-view-publish-photo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-street-view-publish-photo-api-openapi.yml
- filename: google-maps-street-view-publish-photos-api-openapi.yml
  format: yaml
  label: Google Maps Platform Street View Publish Photos API
  slug: google-maps-street-view-publish-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-street-view-publish-photos-api-openapi.yml
- filename: google-maps-street-view-publish-photosequence-api-openapi.yml
  format: yaml
  label: Google Maps Platform Street View Publish PhotoSequence API
  slug: google-maps-street-view-publish-photosequence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-street-view-publish-photosequence-api-openapi.yml
- filename: google-maps-street-view-publish-photosequences-api-openapi.yml
  format: yaml
  label: Google Maps Platform Street View Publish PhotoSequences API
  slug: google-maps-street-view-publish-photosequences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-maps/openapi/google-maps-street-view-publish-photosequences-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: Customer will display all attribution that (i) Google provides through the Services (including branding, logos, and copyright and trademark notices)
  data:
    license: custom
    stance_commercial: prohibited
    text: Customer will not export, extract, or otherwise scrape Google Maps Content for use outside the Services.
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
name: Google Maps Platform
output_license: null
provenance_date: '2026-11-09'
provider_name: Google Maps Platform
provider_slug: google-maps
slug: google-maps-data-license
source_date: '2026-11-09'
source_filename: google-maps-data-license.yml
source_heading: Data License
source_page: https://cloud.google.com/maps-platform/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Google Maps Platform\naid: google-maps\nurl: https://cloud.google.com/maps-platform/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Customer will not export, extract, or otherwise scrape Google Maps Content for use outside the Services.\nattribution:\n  required: true\n  text: Customer will display all attribution that (i) Google provides through the Services (including branding,\n    logos, and copyright and trademark notices)\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/google-maps/data-license/google-maps-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from Google Maps Platform's own page on 2026-11-09.
synthetic: false
tags:
- Environment
- Geocoding
- Geolocation
- Maps
- Navigation
- Places
- Routing
- Solar
- Geospatial
---
