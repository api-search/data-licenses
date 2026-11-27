---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Sigstore Rekor API (consumed)
  slug: rekor-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/sigstore/rekor/main/openapi.yaml
- filename: fulcio.swagger.json
  format: json
  label: Sigstore Fulcio API (consumed)
  slug: fulcio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/sigstore/fulcio/main/fulcio.swagger.json
claim_count: 2
description: ''
doc:
  attribution:
    required: true
    text: You must cause any modified files to carry prominent notices stating that You changed the files
  data:
    license: Apache-2.0
    stance_commercial: unstated
    text: Apache License Version 2.0, January 2004
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
name: Cosign
output_license: null
provenance_date: '2026-11-09'
provider_name: Cosign
provider_slug: cosign
slug: cosign-data-license
source_date: '2026-11-09'
source_filename: cosign-data-license.yml
source_heading: Data License
source_page: https://github.com/sigstore/cosign/blob/main/LICENSE
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Cosign\naid: cosign\nurl: https://github.com/sigstore/cosign/blob/main/LICENSE\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: unstated\n  text: null\ndata:\n  license: Apache-2.0\n  stance_commercial: unstated\n  text: Apache License Version 2.0, January 2004\nattribution:\n  required: true\n  text: You must cause any modified files to carry prominent notices stating that You changed the files\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/cosign/data-license/cosign-data-license.yml
stated_fields:
- data
- attribution
summary_line: 2 quoted statements, read from Cosign's own page on 2026-11-09.
synthetic: false
tags:
- Apache 2.0
- Attestation
- CLI
- Code Signing
- Containers
- Fulcio
- Go
- Keyless
- OCI
- OpenID Connect
- Open Source
- Rekor
- Sigstore
- Supply Chain
- Transparency Log
- Verification
---
