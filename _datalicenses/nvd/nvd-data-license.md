---
api_specs:
- filename: nvd-cpe-api-openapi.yml
  format: yaml
  label: NVD CPE API
  slug: nvd-cpe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nvd/openapi/nvd-cpe-api-openapi.yml
- filename: nvd-cpe-match-api-openapi.yml
  format: yaml
  label: NVD CPE Match API
  slug: nvd-cpe-match-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nvd/openapi/nvd-cpe-match-api-openapi.yml
- filename: nvd-cve-api-openapi.yml
  format: yaml
  label: NVD CVE API
  slug: nvd-cve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nvd/openapi/nvd-cve-api-openapi.yml
- filename: nvd-cve-change-history-api-openapi.yml
  format: yaml
  label: NVD CVE Change History API
  slug: nvd-cve-change-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nvd/openapi/nvd-cve-change-history-api-openapi.yml
- filename: nvd-sources-api-openapi.yml
  format: yaml
  label: NVD Sources API
  slug: nvd-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nvd/openapi/nvd-sources-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: true
    text: 'Services which utilize or access the NVD API are asked to display the following notice prominently within the application: "This product uses the NVD API but is not endorsed or certified by the NVD."'
  data:
    license: null
    stance_commercial: unstated
    text: null
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
name: NVD
output_license: null
provenance_date: '2026-11-10'
provider_name: NVD
provider_slug: nvd
slug: nvd-data-license
source_date: '2026-11-10'
source_filename: nvd-data-license.yml
source_heading: Data License
source_page: https://nvd.nist.gov/developers/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: NVD\naid: nvd\nurl: https://nvd.nist.gov/developers/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: true\n  text: 'Services which utilize or access the NVD API are asked to display the following notice prominently within\n    the application: \"This product uses the NVD API but is not endorsed or certified by the NVD.\"'\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/nvd/data-license/nvd-data-license.yml
stated_fields:
- attribution
summary_line: 1 quoted statement, read from NVD's own page on 2026-11-10.
synthetic: false
tags:
- Security
- CVE
- CPE
- Vulnerabilities
- CVSS
- Vulnerability Management
---
