---
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Display the name of the original publisher for each article and link each article to its original URL
  data:
    license: custom
    stance_commercial: conditional
    text: Your subscription grants you a limited, non-transferable, non-exclusive license to retrieve the data for your internal and external business purposes during the subscription term.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: 'During an active paid subscription, you may use the data for personal and commercial purposes provided that you: Display the name of the original publisher for each article and link each article to its original URL; Display AI-generated summaries only with attribution to the original publisher and a link to the original article'
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: allnewsapi-com
output_license: custom
provenance_date: '2026-11-09'
provider_name: allnewsapi-com
provider_slug: allnewsapi-com
slug: allnewsapi-com-data-license
source_date: '2026-11-09'
source_filename: allnewsapi-com-data-license.yml
source_heading: Data License
source_page: https://allnewsapi.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: allnewsapi-com\naid: allnewsapi-com\nurl: https://allnewsapi.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: 'During an active paid subscription, you may use the data for personal and commercial purposes provided\n    that you: Display the name of the original publisher for each article and link each article to its original\n    URL; Display AI-generated summaries only with attribution to the original publisher and a link to the original\n    article'\ndata:\n  license: custom\n  stance_commercial: conditional\n  text: Your subscription\
  \ grants you a limited, non-transferable, non-exclusive license to retrieve the data for\n    your internal and external business purposes during the subscription term.\nattribution:\n  required: true\n  text: Display the name of the original publisher for each article and link each article to its original URL\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/allnewsapi-com/data-license/allnewsapi-com-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from allnewsapi-com's own page on 2026-11-09.
synthetic: false
tags:
- News
- Data
- Media
- Aggregation
- Company
---
