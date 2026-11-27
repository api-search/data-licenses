---
api_specs:
- filename: indexed-vc-companies-api-openapi.yml
  format: yaml
  label: Indexed Companies API
  slug: indexed-vc-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-companies-api-openapi.yml
- filename: indexed-vc-enrich-api-openapi.yml
  format: yaml
  label: Indexed Enrich API
  slug: indexed-vc-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-enrich-api-openapi.yml
- filename: indexed-vc-industries-api-openapi.yml
  format: yaml
  label: Indexed Industries API
  slug: indexed-vc-industries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-industries-api-openapi.yml
- filename: indexed-vc-investors-api-openapi.yml
  format: yaml
  label: Indexed Investors API
  slug: indexed-vc-investors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-investors-api-openapi.yml
- filename: indexed-vc-reveal-api-openapi.yml
  format: yaml
  label: Indexed Reveal API
  slug: indexed-vc-reveal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-reveal-api-openapi.yml
- filename: indexed-vc-scheduled-exports-api-openapi.yml
  format: yaml
  label: Indexed Scheduled Exports API
  slug: indexed-vc-scheduled-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-scheduled-exports-api-openapi.yml
- filename: indexed-vc-usage-api-openapi.yml
  format: yaml
  label: Indexed Usage API
  slug: indexed-vc-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-usage-api-openapi.yml
- filename: indexed-vc-webhooks-api-openapi.yml
  format: yaml
  label: Indexed Webhooks API
  slug: indexed-vc-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: You are granted a limited, non-exclusive, non-transferable, revocable license to access and use the Service during your active subscription period, subject to these Terms.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: 'Data exported from the Service (including CSV downloads) is provided for your personal or internal business use only, within the limits of your subscription tier. You may not: Redistribute, publish, or share exported data publicly or with third parties'
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Indexed
output_license: custom
provenance_date: '2026-11-09'
provider_name: Indexed
provider_slug: indexed-vc
slug: indexed-vc-data-license
source_date: '2026-11-09'
source_filename: indexed-vc-data-license.yml
source_heading: Data License
source_page: https://indexed.vc/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Indexed\naid: indexed-vc\nurl: https://indexed.vc/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: 'Data exported from the Service (including CSV downloads) is provided for your personal or internal business\n    use only, within the limits of your subscription tier. You may not: Redistribute, publish, or share exported\n    data publicly or with third parties'\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: You are granted a limited, non-exclusive, non-transferable, revocable license to access and use the Service\n    during your active\
  \ subscription period, subject to these Terms.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/indexed-vc/data-license/indexed-vc-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Indexed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Private Company
- Funding
---
