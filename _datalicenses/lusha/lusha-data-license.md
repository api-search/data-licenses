---
api_specs:
- filename: lusha-search-api-openapi.yml
  format: yaml
  label: Lusha Search API
  slug: lusha-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-search-api-openapi.yml
- filename: lusha-enrich-api-openapi.yml
  format: yaml
  label: Lusha Enrich API
  slug: lusha-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-enrich-api-openapi.yml
- filename: lusha-search-enrich-api-openapi.yml
  format: yaml
  label: Lusha Search & Enrich API
  slug: lusha-search-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-search-enrich-api-openapi.yml
- filename: lusha-prospecting-api-openapi.yml
  format: yaml
  label: Lusha Prospecting API
  slug: lusha-prospecting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-prospecting-api-openapi.yml
- filename: lusha-lookalikes-api-openapi.yml
  format: yaml
  label: Lusha Lookalikes API
  slug: lusha-lookalike-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-lookalikes-api-openapi.yml
- filename: lusha-buying-group-api-openapi.yml
  format: yaml
  label: Lusha Buying Group API
  slug: lusha-buying-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-buying-group-api-openapi.yml
- filename: lusha-signals-api-openapi.yml
  format: yaml
  label: Lusha Signals API
  slug: lusha-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-signals-api-openapi.yml
- filename: lusha-website-visits-api-openapi.yml
  format: yaml
  label: Lusha Website Visitors API
  slug: lusha-website-visits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-website-visits-api-openapi.yml
- filename: lusha-filters-api-openapi.yml
  format: yaml
  label: Lusha Filters API
  slug: lusha-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-filters-api-openapi.yml
- filename: lusha-contacts-tables-api-openapi.yml
  format: yaml
  label: Lusha Contacts Tables API
  slug: lusha-contacts-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-contacts-tables-api-openapi.yml
- filename: lusha-companies-tables-api-openapi.yml
  format: yaml
  label: Lusha Companies Tables API
  slug: lusha-companies-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-companies-tables-api-openapi.yml
- filename: lusha-webhooks-api-openapi.yml
  format: yaml
  label: Lusha Webhooks API
  slug: lusha-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-webhooks-api-openapi.yml
- filename: lusha-account-api-openapi.yml
  format: yaml
  label: Lusha Account API
  slug: lusha-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-account-api-openapi.yml
- filename: lusha-account-management-api-openapi.yml
  format: yaml
  label: Lusha Account Management API
  slug: lusha-account-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-account-management-api-openapi.yml
- filename: lusha-company-filters-api-openapi.yml
  format: yaml
  label: Lusha Company Filters API
  slug: lusha-company-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-company-filters-api-openapi.yml
- filename: lusha-contact-filters-api-openapi.yml
  format: yaml
  label: Lusha Contact Filters API
  slug: lusha-contact-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-contact-filters-api-openapi.yml
- filename: lusha-enrichment-api-openapi.yml
  format: yaml
  label: Lusha Enrichment API
  slug: lusha-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-enrichment-api-openapi.yml
- filename: lusha-prospecting-search-enrich-api-openapi.yml
  format: yaml
  label: Lusha Prospecting - Search & Enrich API
  slug: lusha-prospecting-search-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-prospecting-search-enrich-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: false
    text: disclose the source of Data provided by Lusha unless obligated to do so by law
  data:
    license: custom
    stance_commercial: conditional
    text: Lusha grants to Customer a non-exclusive, non-sublicensable, non-transferable, worldwide, and limited right, throughout the Term (as defined in Section 16.1) solely for the Purpose
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Lusha hereby grants Customer a perpetual, non-exclusive licence to the Output, subject to Customer’s ownership of the relevant Input
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Lusha
output_license: custom
provenance_date: '2026-11-10'
provider_name: Lusha
provider_slug: lusha
slug: lusha-data-license
source_date: '2026-11-10'
source_filename: lusha-data-license.yml
source_heading: Data License
source_page: https://www.lusha.com/legal/terms_and_conditions-2/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Lusha\naid: lusha\nurl: https://www.lusha.com/legal/terms_and_conditions-2/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Lusha hereby grants Customer a perpetual, non-exclusive licence to the Output, subject to Customer’s ownership\n    of the relevant Input\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Lusha grants to Customer a non-exclusive, non-sublicensable, non-transferable, worldwide, and limited right,\n    throughout the Term (as defined in Section 16.1) solely for the Purpose\nattribution:\n  required: false\n\
  \  text: disclose the source of Data provided by Lusha unless obligated to do so by law\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/lusha/data-license/lusha-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Lusha's own page on 2026-11-10.
synthetic: false
tags:
- Sales Intelligence
- B2B
- Data Enrichment
- Contact Data
- Prospecting
- Intents
- Signals
- Lookalikes
- Webhook
- MCP
---
