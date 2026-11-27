---
api_specs:
- filename: zylo-applications-api-openapi.yml
  format: yaml
  label: Zylo Applications API
  slug: zylo-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zylo/openapi/zylo-applications-api-openapi.yml
- filename: zylo-export-jobs-api-openapi.yml
  format: yaml
  label: Zylo Export Jobs API
  slug: zylo-export-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zylo/openapi/zylo-export-jobs-api-openapi.yml
- filename: zylo-import-jobs-api-openapi.yml
  format: yaml
  label: Zylo Import Jobs API
  slug: zylo-import-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zylo/openapi/zylo-import-jobs-api-openapi.yml
- filename: zylo-subscriptions-api-openapi.yml
  format: yaml
  label: Zylo Subscriptions API
  slug: zylo-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zylo/openapi/zylo-subscriptions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: unstated
    text: Customer grants Zylo a worldwide, nonrevocable license to use, host, store, reproduce, and modify Customer Data to provide, support, and improve, and aid Customer’s use of the Services.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: Customer shall have a nonexclusive, nontransferable license to use the Work Product solely in connection with its use of the Services.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Zylo
output_license: custom
provenance_date: '2026-11-10'
provider_name: Zylo
provider_slug: zylo
slug: zylo-data-license
source_date: '2026-11-10'
source_filename: zylo-data-license.yml
source_heading: Data License
source_page: https://zylo.com/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Zylo\naid: zylo\nurl: https://zylo.com/msa\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: Customer shall have a nonexclusive, nontransferable license to use the Work Product solely in connection\n    with its use of the Services.\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: Customer grants Zylo a worldwide, nonrevocable license to use, host, store, reproduce, and modify Customer\n    Data to provide, support, and improve, and aid Customer’s use of the Services.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/zylo/data-license/zylo-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Zylo's own page on 2026-11-10.
synthetic: false
tags:
- Budgets
- SaaS Management
- Spend
---
