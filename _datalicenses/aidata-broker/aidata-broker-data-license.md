---
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: proprietary
    name: Market Data Licence
    open_without_licence: the MCP server (a sample of each table without a key) and the public pages (a selection of records plus counts and figures computed from all of them), and the free valuation
    price:
    - amount: 490
      currency: USD
      term: month
    - amount: 4900
      currency: USD
      term: year
    pricing_url: https://aidata.broker/datasets
    stance_commercial: licensed
    terms_url: https://aidata.broker/legal/terms
    text: Every row of our tables is sold under the Market Data Licence. A licence is taken by one organisation (the licensee) for a term of a month or a year, at the price shown on the data page, paid in advance.
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
model: null
name: AIData.Broker
output_license: null
provenance_date: '2026-11-11'
provider_name: AIData.Broker
provider_slug: aidata-broker
slug: aidata-broker-data-license
source_date: '2026-11-11'
source_filename: aidata-broker-data-license.yml
source_heading: Data License
source_page: https://aidata.broker/legal/terms
source_url: ''
source_yaml: "# Corrected 2026-11-11 from the provider's own pages after their correction email: the tables are no longer CC BY 4.0.\ndata_license: 0.1.0\nprovider: AIData.Broker\naid: aidata-broker\nurl: https://aidata.broker/legal/terms\nsource_date: '2026-11-11'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-11'\n  tool: manual (request aidata-87fd7a6c)\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: proprietary\n  name: Market Data Licence\n  terms_url: https://aidata.broker/legal/terms\n  pricing_url: https://aidata.broker/datasets\n  stance_commercial: licensed\n  text: Every row of our tables is sold under the Market Data Licence. A licence is taken by one organisation (the licensee)\n    for a term of a month or a year, at the price shown on the data page, paid in advance.\n  price:\n  - term: month\n    amount: 490\n    currency: USD\n  - term: year\n    amount: 4900\n    currency: USD\n  open_without_licence:\
  \ the MCP server (a sample of each table without a key) and the public pages (a selection of records\n    plus counts and figures computed from all of them), and the free valuation\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/aidata-broker/data-license/aidata-broker-data-license.yml
stated_fields:
- data
summary_line: 1 quoted statement, read from AIData.Broker's own page on 2026-11-11.
synthetic: false
tags:
- Company
- Data Marketplace
- AI Training
- Pricing
- Buyers
---
