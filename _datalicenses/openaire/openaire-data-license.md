---
api_specs:
- filename: openaire-broker-api-openapi.yml
  format: yaml
  label: OpenAIRE Broker API
  slug: openaire-broker-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openaire/openapi/openaire-broker-api-openapi.yml
- filename: openaire-oidc-api-openapi.yml
  format: yaml
  label: OpenAIRE Oidc API
  slug: openaire-oidc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openaire/openapi/openaire-oidc-api-openapi.yml
- filename: openaire-openaire-api-api-openapi.yml
  format: yaml
  label: OpenAIRE OpenAIRE API
  slug: openaire-openaire-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openaire/openapi/openaire-openaire-api-api-openapi.yml
- filename: openaire-skg-if-api-openapi.yml
  format: yaml
  label: OpenAIRE Skg If API
  slug: openaire-skg-if-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openaire/openapi/openaire-skg-if-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: as long as OpenAIRE is acknowledged as content provider.
  data:
    license: custom
    stance_commercial: prohibited
    text: Any authorized User cannot in any circumstance and for any usage redistribute the data or copies thereof
  interface_license:
    url: null
  outputs:
    license: CC-BY
    stance_commercial: allowed
    text: the metadata records returned by the services can be freely re-used by commercial and non-commercial partners under CC-BY license
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: OpenAIRE
output_license: CC-BY
provenance_date: '2026-11-10'
provider_name: OpenAIRE
provider_slug: openaire
slug: openaire-data-license
source_date: '2026-11-10'
source_filename: openaire-data-license.yml
source_heading: Data License
source_page: https://www.openaire.eu/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: OpenAIRE\naid: openaire\nurl: https://www.openaire.eu/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: CC-BY\n  stance_commercial: allowed\n  text: the metadata records returned by the services can be freely re-used by commercial and non-commercial partners\n    under CC-BY license\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Any authorized User cannot in any circumstance and for any usage redistribute the data or copies thereof\nattribution:\n  required: true\n  text: as long as OpenAIRE is acknowledged as content provider.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/openaire/data-license/openaire-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from OpenAIRE's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Open Science
- Research Infrastructure
- Europe
- Services
---
