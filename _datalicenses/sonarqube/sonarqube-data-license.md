---
api_specs:
- filename: sonarqube-issues-api-openapi.yml
  format: yaml
  label: SonarQube Issues API
  slug: sonarqube-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-issues-api-openapi.yml
- filename: sonarqube-measures-api-openapi.yml
  format: yaml
  label: SonarQube Measures API
  slug: sonarqube-measures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-measures-api-openapi.yml
- filename: sonarqube-projects-api-openapi.yml
  format: yaml
  label: SonarQube Projects API
  slug: sonarqube-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-projects-api-openapi.yml
- filename: sonarqube-quality-gates-api-openapi.yml
  format: yaml
  label: SonarQube Quality Gates API
  slug: sonarqube-quality-gates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-quality-gates-api-openapi.yml
- filename: sonarqube-rules-api-openapi.yml
  format: yaml
  label: SonarQube Rules API
  slug: sonarqube-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-rules-api-openapi.yml
- filename: sonarqube-system-api-openapi.yml
  format: yaml
  label: SonarQube System API
  slug: sonarqube-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-system-api-openapi.yml
- filename: sonarqube-users-api-openapi.yml
  format: yaml
  label: SonarQube Users API
  slug: sonarqube-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonarqube/openapi/sonarqube-users-api-openapi.yml
claim_count: 1
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: null
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: (iii) license to access and use the Results Data.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: SonarQube
output_license: custom
provenance_date: '2026-11-10'
provider_name: SonarQube
provider_slug: sonarqube
slug: sonarqube-data-license
source_date: '2026-11-10'
source_filename: sonarqube-data-license.yml
source_heading: Data License
source_page: https://www.sonarsource.com/legal/sonarqube/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: SonarQube\naid: sonarqube\nurl: https://www.sonarsource.com/legal/sonarqube/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: (iii) license to access and use the Results Data.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: null\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/sonarqube/data-license/sonarqube-data-license.yml
stated_fields:
- outputs
summary_line: 1 quoted statement, read from SonarQube's own page on 2026-11-10.
synthetic: false
tags:
- Code Quality
- Developer Tools
- DevOps
- Security
- Static Analysis
- Code Security
- SAST
---
