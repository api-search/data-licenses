---
api_specs:
- filename: crunchbase-data-autocomplete-api-openapi.yml
  format: yaml
  label: Crunchbase Autocomplete API
  slug: crunchbase-data-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-autocomplete-api-openapi.yml
- filename: crunchbase-data-deleted-entities-api-openapi.yml
  format: yaml
  label: Crunchbase Deleted Entities API
  slug: crunchbase-data-deleted-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-deleted-entities-api-openapi.yml
- filename: crunchbase-data-entity-api-openapi.yml
  format: yaml
  label: Crunchbase Entity API
  slug: crunchbase-data-entity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-entity-api-openapi.yml
- filename: crunchbase-data-metadata-api-openapi.yml
  format: yaml
  label: Crunchbase Metadata API
  slug: crunchbase-data-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-metadata-api-openapi.yml
- filename: crunchbase-data-search-api-openapi.yml
  format: yaml
  label: Crunchbase Search API
  slug: crunchbase-data-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-search-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: Proper attribution is provided to Crunchbase (please follow our Attribution Instructions to ensure that you are properly attributing Crunchbase).
  data:
    license: custom
    stance_commercial: conditional
    text: Any other uses of Content require Crunchbase’s prior written consent.
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
name: Crunchbase
output_license: null
provenance_date: '2026-11-09'
provider_name: Crunchbase
provider_slug: crunchbase-data
slug: crunchbase-data-data-license
source_date: '2026-11-09'
source_filename: crunchbase-data-data-license.yml
source_heading: Data License
source_page: https://about.crunchbase.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Crunchbase\naid: crunchbase-data\nurl: https://about.crunchbase.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Any other uses of Content require Crunchbase’s prior written consent.\nattribution:\n  required: true\n  text: Proper attribution is provided to Crunchbase (please follow our Attribution Instructions to ensure that\n    you are properly attributing Crunchbase).\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/crunchbase-data/data-license/crunchbase-data-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from Crunchbase's own page on 2026-11-09.
synthetic: false
tags:
- Company Data
- Web Intelligence
- Funding Data
- Firmographics
- B2B Data
- investor-data
- Reference Data
- Private Markets
- Predictions
- Market Insights
- MCP
- Fortune 1000
- Startups
---
