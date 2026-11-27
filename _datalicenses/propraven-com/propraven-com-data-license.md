---
api_specs:
- filename: propraven-com-account-api-openapi.yml
  format: yaml
  label: propraven-com Account API
  slug: propraven-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-account-api-openapi.yml
- filename: propraven-com-coverage-api-openapi.yml
  format: yaml
  label: propraven-com Coverage API
  slug: propraven-com-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-coverage-api-openapi.yml
- filename: propraven-com-credits-api-openapi.yml
  format: yaml
  label: propraven-com Credits API
  slug: propraven-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-credits-api-openapi.yml
- filename: propraven-com-deals-api-openapi.yml
  format: yaml
  label: propraven-com Deals API
  slug: propraven-com-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-deals-api-openapi.yml
- filename: propraven-com-distribution-api-openapi.yml
  format: yaml
  label: propraven-com Distribution API
  slug: propraven-com-distribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-distribution-api-openapi.yml
- filename: propraven-com-leads-api-openapi.yml
  format: yaml
  label: propraven-com Leads API
  slug: propraven-com-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-leads-api-openapi.yml
- filename: propraven-com-market-api-openapi.yml
  format: yaml
  label: propraven-com Market API
  slug: propraven-com-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-market-api-openapi.yml
- filename: propraven-com-owners-api-openapi.yml
  format: yaml
  label: propraven-com Owners API
  slug: propraven-com-owners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-owners-api-openapi.yml
- filename: propraven-com-parcels-api-openapi.yml
  format: yaml
  label: propraven-com Parcels API
  slug: propraven-com-parcels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-parcels-api-openapi.yml
- filename: propraven-com-property-intelligence-api-openapi.yml
  format: yaml
  label: propraven-com Property Intelligence API
  slug: propraven-com-property-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-property-intelligence-api-openapi.yml
- filename: propraven-com-search-api-openapi.yml
  format: yaml
  label: propraven-com Search API
  slug: propraven-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-search-api-openapi.yml
- filename: propraven-com-storefront-api-openapi.yml
  format: yaml
  label: propraven-com Storefront API
  slug: propraven-com-storefront-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-storefront-api-openapi.yml
- filename: propraven-com-verify-api-openapi.yml
  format: yaml
  label: propraven-com Verify API
  slug: propraven-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-verify-api-openapi.yml
- filename: propraven-com-watch-api-openapi.yml
  format: yaml
  label: propraven-com Watch API
  slug: propraven-com-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-watch-api-openapi.yml
- filename: propraven-com-webhooks-api-openapi.yml
  format: yaml
  label: propraven-com Webhooks API
  slug: propraven-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-webhooks-api-openapi.yml
- filename: propraven-com-zoning-api-openapi.yml
  format: yaml
  label: propraven-com Zoning API
  slug: propraven-com-zoning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-zoning-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: 'you must give PropRaven reasonable credit as the source, such as "Source: PropRaven" next to the data or in your credits.'
  data:
    license: custom
    stance_commercial: conditional
    text: 'we grant you a non-exclusive, non-transferable license to use the PropRaven Data you receive: for your own personal or business purposes'
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: inside your own products and services, such as reports, analyses, applications, and AI agents, that you provide to your own customers, as long as your customers receive the data as part of your product or service and not as a copy of PropRaven Data itself.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: propraven-com
output_license: custom
provenance_date: '2026-11-10'
provider_name: propraven-com
provider_slug: propraven-com
slug: propraven-com-data-license
source_date: '2026-11-10'
source_filename: propraven-com-data-license.yml
source_heading: Data License
source_page: https://propraven.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: propraven-com\naid: propraven-com\nurl: https://propraven.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: inside your own products and services, such as reports, analyses, applications, and AI agents, that you\n    provide to your own customers, as long as your customers receive the data as part of your product or service\n    and not as a copy of PropRaven Data itself.\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: 'we grant you a non-exclusive, non-transferable license to use the PropRaven Data you receive: for your\n    own\
  \ personal or business purposes'\nattribution:\n  required: true\n  text: 'you must give PropRaven reasonable credit as the source, such as \"Source: PropRaven\" next to the data or\n    in your credits.'\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/propraven-com/data-license/propraven-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from propraven-com's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Data
- Property Intelligence
- US
---
