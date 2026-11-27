---
api_specs:
- filename: clinical-trials-gov-stats-api-openapi.yml
  format: yaml
  label: ClinicalTrials.gov Stats API
  slug: clinical-trials-gov-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clinical-trials-gov/openapi/clinical-trials-gov-stats-api-openapi.yml
- filename: clinical-trials-gov-studies-api-openapi.yml
  format: yaml
  label: ClinicalTrials.gov Studies API
  slug: clinical-trials-gov-studies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clinical-trials-gov/openapi/clinical-trials-gov-studies-api-openapi.yml
- filename: clinical-trials-gov-version-api-openapi.yml
  format: yaml
  label: ClinicalTrials.gov Version API
  slug: clinical-trials-gov-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clinical-trials-gov/openapi/clinical-trials-gov-version-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: Attribute the source of the data as ClinicalTrials.gov
  data:
    license: null
    stance_commercial: unstated
    text: The ClinicalTrials.gov data carry an international copyright outside the United States and its Territories or Possessions.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: unstated
    text: These Terms and Conditions apply to all data obtained from ClinicalTrials.gov, independent of format and method of acquisition.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: ClinicalTrials.gov
output_license: null
provenance_date: '2026-11-09'
provider_name: ClinicalTrials.gov
provider_slug: clinical-trials-gov
slug: clinical-trials-gov-data-license
source_date: '2026-11-09'
source_filename: clinical-trials-gov-data-license.yml
source_heading: Data License
source_page: https://clinicaltrials.gov/about-site/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: ClinicalTrials.gov\naid: clinical-trials-gov\nurl: https://clinicaltrials.gov/about-site/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: These Terms and Conditions apply to all data obtained from ClinicalTrials.gov, independent of format and\n    method of acquisition.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: The ClinicalTrials.gov data carry an international copyright outside the United States and its Territories\n    or Possessions.\nattribution:\n  required: true\n  text: Attribute the source of the data as ClinicalTrials.gov\n\
  interface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/clinical-trials-gov/data-license/clinical-trials-gov-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from ClinicalTrials.gov's own page on 2026-11-09.
synthetic: false
tags:
- Clinical Trials
- Government
- Health
- NIH
- Open Data
- Public Health
- Research
---
