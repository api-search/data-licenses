---
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: prohibited
    text: The Platform Content provided within the Services and the Sites are for the use of the Customer and the Users only, and may not be used for any commercial use, except through the use of the Services or otherwise expressly authorized by us.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: Customer may export the content, manage Users and User roles, create integrations, manage permissions, create information types, change settings, adjust privacy, delete all or some of the Content, or share Customer Data.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: BreachLock
output_license: null
provenance_date: '2026-11-09'
provider_name: BreachLock
provider_slug: breachlock
slug: breachlock-data-license
source_date: '2026-11-09'
source_filename: breachlock-data-license.yml
source_heading: Data License
source_page: https://www.breachlock.com/about/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: BreachLock\naid: breachlock\nurl: https://www.breachlock.com/about/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: Customer may export the content, manage Users and User roles, create integrations, manage permissions, create\n    information types, change settings, adjust privacy, delete all or some of the Content, or share Customer Data.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: The Platform Content provided within the Services and the Sites are for the use of the Customer and the\n    Users only, and may not be used for any\
  \ commercial use, except through the use of the Services or otherwise\n    expressly authorized by us.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/breachlock/data-license/breachlock-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from BreachLock's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Penetration Testing
- Attack Surface Management
- Red Team
- Software-as-a-Service
---
