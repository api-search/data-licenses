---
api_specs:
- filename: compsniper-com-account-api-openapi.yml
  format: yaml
  label: compsniper-com Account API
  slug: compsniper-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-account-api-openapi.yml
- filename: compsniper-com-best-offer-prices-api-openapi.yml
  format: yaml
  label: compsniper-com Best Offer Prices API
  slug: compsniper-com-best-offer-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-best-offer-prices-api-openapi.yml
- filename: compsniper-com-bulk-search-api-openapi.yml
  format: yaml
  label: compsniper-com Bulk Search API
  slug: compsniper-com-bulk-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-bulk-search-api-openapi.yml
- filename: compsniper-com-cards-api-openapi.yml
  format: yaml
  label: compsniper-com Cards API
  slug: compsniper-com-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-cards-api-openapi.yml
- filename: compsniper-com-depop-api-openapi.yml
  format: yaml
  label: compsniper-com Depop API
  slug: compsniper-com-depop-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-depop-api-openapi.yml
- filename: compsniper-com-grailed-api-openapi.yml
  format: yaml
  label: compsniper-com Grailed API
  slug: compsniper-com-grailed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-grailed-api-openapi.yml
- filename: compsniper-com-mercari-api-openapi.yml
  format: yaml
  label: compsniper-com Mercari API
  slug: compsniper-com-mercari-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-mercari-api-openapi.yml
- filename: compsniper-com-poshmark-api-openapi.yml
  format: yaml
  label: compsniper-com Poshmark API
  slug: compsniper-com-poshmark-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-poshmark-api-openapi.yml
- filename: compsniper-com-psa-api-openapi.yml
  format: yaml
  label: compsniper-com PSA API
  slug: compsniper-com-psa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-psa-api-openapi.yml
- filename: compsniper-com-scrape-api-openapi.yml
  format: yaml
  label: compsniper-com Scrape API
  slug: compsniper-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-scrape-api-openapi.yml
- filename: compsniper-com-shipping-rates-api-openapi.yml
  format: yaml
  label: compsniper-com Shipping Rates API
  slug: compsniper-com-shipping-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-shipping-rates-api-openapi.yml
- filename: compsniper-com-sold-history-api-openapi.yml
  format: yaml
  label: compsniper-com Sold history API
  slug: compsniper-com-sold-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-sold-history-api-openapi.yml
- filename: compsniper-com-summary-api-openapi.yml
  format: yaml
  label: compsniper-com Summary API
  slug: compsniper-com-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-summary-api-openapi.yml
- filename: compsniper-com-tcgplayer-api-openapi.yml
  format: yaml
  label: compsniper-com TC Gplayer API
  slug: compsniper-com-tcgplayer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compsniper-com/openapi/compsniper-com-tcgplayer-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: The data returned by CompSniper is sourced from publicly available eBay listings and completed sales.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: allowed
    text: Commercial use is permitted on every plan, including the free plan. You may build the service into a paid SaaS product, an internal business tool, a client deliverable, or a mobile app.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: compsniper-com
output_license: null
provenance_date: '2026-11-09'
provider_name: compsniper-com
provider_slug: compsniper-com
slug: compsniper-com-data-license
source_date: '2026-11-09'
source_filename: compsniper-com-data-license.yml
source_heading: Data License
source_page: https://compsniper.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: compsniper-com\naid: compsniper-com\nurl: https://compsniper.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: allowed\n  text: Commercial use is permitted on every plan, including the free plan. You may build the service into a paid\n    SaaS product, an internal business tool, a client deliverable, or a mobile app.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: The data returned by CompSniper is sourced from publicly available eBay listings and completed sales.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/compsniper-com/data-license/compsniper-com-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from compsniper-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- E-Commerce
- Data
- Collectibles
---
