---
api_specs:
- filename: ticketmaster-availability-api-openapi.yml
  format: yaml
  label: Ticketmaster Availability API
  slug: ticketmaster-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticketmaster/openapi/ticketmaster-availability-api-openapi.yml
- filename: ticketmaster-offerings-api-openapi.yml
  format: yaml
  label: Ticketmaster Offerings API
  slug: ticketmaster-offerings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticketmaster/openapi/ticketmaster-offerings-api-openapi.yml
- filename: ticketmaster-attractions-api-openapi.yml
  format: yaml
  label: Ticketmaster Attractions API
  slug: ticketmaster-attractions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticketmaster/openapi/ticketmaster-attractions-api-openapi.yml
- filename: ticketmaster-classifications-api-openapi.yml
  format: yaml
  label: Ticketmaster Classifications API
  slug: ticketmaster-classifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticketmaster/openapi/ticketmaster-classifications-api-openapi.yml
- filename: ticketmaster-events-api-openapi.yml
  format: yaml
  label: Ticketmaster Events API
  slug: ticketmaster-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticketmaster/openapi/ticketmaster-events-api-openapi.yml
- filename: ticketmaster-suggestions-api-openapi.yml
  format: yaml
  label: Ticketmaster Suggestions API
  slug: ticketmaster-suggestions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticketmaster/openapi/ticketmaster-suggestions-api-openapi.yml
- filename: ticketmaster-venues-api-openapi.yml
  format: yaml
  label: Ticketmaster Venues API
  slug: ticketmaster-venues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticketmaster/openapi/ticketmaster-venues-api-openapi.yml
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: null
    stance_commercial: unstated
    text: Ticketmaster content (event name, dates, times, venue name, and additional information such as Tickets, Attendees, Orders (“Event Content”) are owned by the organizers and/or Ticketmaster.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: Sell, lease, or sublicense the Ticketmaster API or access thereto or derive revenues from the use or provision of the Ticketmaster API, whether for direct commercial or monetary gain or otherwise, except as set forth below.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Ticketmaster
output_license: custom
provenance_date: '2026-11-10'
provider_name: Ticketmaster
provider_slug: ticketmaster
slug: ticketmaster-data-license
source_date: '2026-11-10'
source_filename: ticketmaster-data-license.yml
source_heading: Data License
source_page: https://developer.ticketmaster.com/support/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Ticketmaster\naid: ticketmaster\nurl: https://developer.ticketmaster.com/support/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: Sell, lease, or sublicense the Ticketmaster API or access thereto or derive revenues from the use or provision\n    of the Ticketmaster API, whether for direct commercial or monetary gain or otherwise, except as set forth below.\ndata:\n  license: null\n  stance_commercial: unstated\n  text: Ticketmaster content (event name, dates, times, venue name, and additional information such as Tickets,\n    Attendees, Orders (“Event\
  \ Content”) are owned by the organizers and/or Ticketmaster.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/ticketmaster/data-license/ticketmaster-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from Ticketmaster's own page on 2026-11-10.
synthetic: false
tags:
- Commerce
- Concerts
- Entertainment
- Event
- Sports
- Ticketing
- Venues
---
