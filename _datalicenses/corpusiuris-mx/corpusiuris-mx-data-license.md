---
api_specs:
- filename: corpusiuris-mx-agent-api-openapi.yml
  format: yaml
  label: Corpus Iuris Agent API
  slug: corpusiuris-mx-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiuris-mx/openapi/corpusiuris-mx-agent-api-openapi.yml
claim_count: 3
description: ''
doc:
  attribution:
    required: true
    text: los resultados empleados en respuestas deben atribuirse a «Corpus Iuris (corpusiuris.mx)»
  data:
    license: custom
    stance_commercial: prohibited
    text: Queda prohibido reproducir, distribuir, modificar, hacer ingeniería inversa o crear obras derivadas del software, de la compilación o de sus índices sin autorización expresa por escrito.
  interface_license:
    url: null
  outputs:
    license: custom
    stance_commercial: prohibited
    text: cualquier uso que implique replicar, redistribuir o comercializar el corpus jurídico, los embeddings o los outputs del sistema.
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: Corpus Iuris
output_license: custom
provenance_date: '2026-11-09'
provider_name: Corpus Iuris
provider_slug: corpusiuris-mx
slug: corpusiuris-mx-data-license
source_date: '2026-11-09'
source_filename: corpusiuris-mx-data-license.yml
source_heading: Data License
source_page: https://corpusiuris.mx/terminos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: Corpus Iuris\naid: corpusiuris-mx\nurl: https://corpusiuris.mx/terminos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: custom\n  stance_commercial: prohibited\n  text: cualquier uso que implique replicar, redistribuir o comercializar el corpus jurídico, los embeddings o los\n    outputs del sistema.\ndata:\n  license: custom\n  stance_commercial: prohibited\n  text: Queda prohibido reproducir, distribuir, modificar, hacer ingeniería inversa o crear obras derivadas del\n    software, de la compilación o de sus índices sin autorización expresa por escrito.\nattribution:\n  required: true\n  text: los resultados\
  \ empleados en respuestas deben atribuirse a «Corpus Iuris (corpusiuris.mx)»\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/corpusiuris-mx/data-license/corpusiuris-mx-data-license.yml
stated_fields:
- outputs
- data
- attribution
summary_line: 3 quoted statements, read from Corpus Iuris's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Research
- Artificial Intelligence
- Mexico
- Jurisprudence
- MCP
- Search
---
