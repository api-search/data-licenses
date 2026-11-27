---
api_specs:
- filename: jobspipe-account-api-openapi.yml
  format: yaml
  label: JobsPipe Account API
  slug: jobspipe-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-account-api-openapi.yml
- filename: jobspipe-billing-api-openapi.yml
  format: yaml
  label: JobsPipe Billing API
  slug: jobspipe-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-billing-api-openapi.yml
- filename: jobspipe-companies-api-openapi.yml
  format: yaml
  label: JobsPipe Companies API
  slug: jobspipe-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-companies-api-openapi.yml
- filename: jobspipe-jobs-api-openapi.yml
  format: yaml
  label: JobsPipe Jobs API
  slug: jobspipe-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-jobs-api-openapi.yml
- filename: jobspipe-labour-market-insights-api-openapi.yml
  format: yaml
  label: JobsPipe Labour Market Insights API
  slug: jobspipe-labour-market-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-labour-market-insights-api-openapi.yml
- filename: jobspipe-monitors-api-openapi.yml
  format: yaml
  label: JobsPipe Monitors API
  slug: jobspipe-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-monitors-api-openapi.yml
- filename: jobspipe-sandbox-api-openapi.yml
  format: yaml
  label: JobsPipe Sandbox API
  slug: jobspipe-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-sandbox-api-openapi.yml
- filename: jobspipe-stack-api-openapi.yml
  format: yaml
  label: JobsPipe Stack API
  slug: jobspipe-stack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-stack-api-openapi.yml
- filename: jobspipe-technologies-api-openapi.yml
  format: yaml
  label: JobsPipe Technologies API
  slug: jobspipe-technologies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-technologies-api-openapi.yml
- filename: jobspipe-contacts-api-openapi.yml
  format: yaml
  label: JobsPipe Contacts API
  slug: jobspipe-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-contacts-api-openapi.yml
- filename: jobspipe-layoffs-api-openapi.yml
  format: yaml
  label: JobsPipe Layoffs API
  slug: jobspipe-layoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-layoffs-api-openapi.yml
- filename: jobspipe-live-api-openapi.yml
  format: yaml
  label: JobsPipe Live API
  slug: jobspipe-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-live-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: When you display a posting, keep the link to the original posting.
  data:
    license: custom
    stance_commercial: unstated
    text: JobsPipe does not claim ownership of job-posting content, which belongs to the employers that published it. We retain rights to our normalized schema, enrichment, and dedup logic.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: conditional
    text: resell, sublicense or redistribute the data in bulk, or as a dataset, feed or API that competes with JobsPipe
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: JobsPipe
output_license: null
provenance_date: '2026-11-09'
provider_name: JobsPipe
provider_slug: jobspipe
slug: jobspipe-data-license
source_date: '2026-11-09'
source_filename: jobspipe-data-license.yml
source_heading: Data License
source_page: https://jobspipe.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: JobsPipe\naid: jobspipe\nurl: https://jobspipe.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://jobspipe.dev/terms\n  - https://jobspipe.dev/terms.md\noutputs:\n  license: null\n  stance_commercial: conditional\n  text: resell, sublicense or redistribute the data in bulk, or as a dataset, feed or API that competes with JobsPipe\ndata:\n  license: custom\n  stance_commercial: unstated\n  text: JobsPipe does not claim ownership of job-posting content, which belongs to the employers that published\n    it. We retain rights to our normalized schema, enrichment, and dedup logic.\nattribution:\n  required:\
  \ true\n  text: When you display a posting, keep the link to the original posting.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/jobspipe/data-license/jobspipe-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from JobsPipe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Job
- Data
- Hiring
- JobsAPI
---
