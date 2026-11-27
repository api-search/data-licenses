---
api_specs:
- filename: vesselfinder-containers-api-openapi.yml
  format: yaml
  label: VesselFinder Containers API
  slug: vesselfinder-containers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-containers-api-openapi.yml
- filename: vesselfinder-distance-api-openapi.yml
  format: yaml
  label: VesselFinder Distance API
  slug: vesselfinder-distance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-distance-api-openapi.yml
- filename: vesselfinder-expected-arrivals-api-openapi.yml
  format: yaml
  label: VesselFinder Expected Arrivals API
  slug: vesselfinder-expected-arrivals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-expected-arrivals-api-openapi.yml
- filename: vesselfinder-list-manager-api-openapi.yml
  format: yaml
  label: VesselFinder List Manager API
  slug: vesselfinder-list-manager-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-list-manager-api-openapi.yml
- filename: vesselfinder-live-data-api-openapi.yml
  format: yaml
  label: VesselFinder Live Data API
  slug: vesselfinder-live-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-live-data-api-openapi.yml
- filename: vesselfinder-master-data-api-openapi.yml
  format: yaml
  label: VesselFinder Master Data API
  slug: vesselfinder-master-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-master-data-api-openapi.yml
- filename: vesselfinder-port-calls-api-openapi.yml
  format: yaml
  label: VesselFinder Port Calls API
  slug: vesselfinder-port-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-port-calls-api-openapi.yml
- filename: vesselfinder-status-api-openapi.yml
  format: yaml
  label: VesselFinder Status API
  slug: vesselfinder-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-status-api-openapi.yml
- filename: vesselfinder-vessels-api-openapi.yml
  format: yaml
  label: VesselFinder Vessels API
  slug: vesselfinder-vessels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-vessels-api-openapi.yml
- filename: vesselfinder-vessels-list-api-openapi.yml
  format: yaml
  label: VesselFinder Vessels List API
  slug: vesselfinder-vessels-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-vessels-list-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: If your plan permits external display of Content (e.g., on your website/app), you must follow the attribution/branding rules in your Order.
  data:
    license: custom
    stance_commercial: prohibited
    text: Free Web Access does not grant any right to use the Content for commercial resale, redistribution, or third-party benefit.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: conditional
    text: 'You may generate Derived Data for internal use only, provided it does not: enable reconstruction of underlying Content (including AIS Data); function as a substitute for providing Content to third parties; or violate these Terms or plan limits.'
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: VesselFinder
output_license: custom
provenance_date: '2026-11-10'
provider_name: VesselFinder
provider_slug: vesselfinder
slug: vesselfinder-data-license
source_date: '2026-11-10'
source_filename: vesselfinder-data-license.yml
source_heading: Data License
source_page: https://www.vesselfinder.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: VesselFinder\naid: vesselfinder\nurl: https://www.vesselfinder.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: conditional\n  text: 'You may generate Derived Data for internal use only, provided it does not: enable reconstruction of underlying\n    Content (including AIS Data); function as a substitute for providing Content to third parties; or violate these\n    Terms or plan limits.'\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Free Web Access does not grant any right to use the Content for commercial resale, redistribution, or third-party\n  \
  \  benefit.\nattribution:\n  required: true\n  text: If your plan permits external display of Content (e.g., on your website/app), you must follow the attribution/branding\n    rules in your Order.\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/vesselfinder/data-license/vesselfinder-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from VesselFinder's own page on 2026-11-10.
synthetic: false
tags:
- AIS
- Maritime
- Vessel Tracking
- Container Tracking
- Geospatial
- Logistics
- Ports
- Supply Chain
---
