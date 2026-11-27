---
claim_count: 2
description: ''
doc:
  attribution:
    required: null
    text: null
  data:
    license: custom
    stance_commercial: allowed
    text: AIRS may create Anonymized Data and combine it with data from other customers into a new aggregate dataset (“Aggregate Data”), and shall have a right to use, disclose, reproduce, sell, disseminate, publicize or otherwise exploit any such Anonymized Data or Aggregate Data for any purpose.
  interface_license:
    url: null
  outputs:
    license: null
    stance_commercial: conditional
    text: 'You will not: (a) engage in the service of operating the Software on behalf of third parties; (b) engage in the service of operating the Software to analyze MRI datasets that originate from imaging centers or MRI scanners outside of Your facility'
layer: data_license
layer_version: 0.1.0
layout: data-license
method: harvested
model: claude-haiku-5-5
name: AIRS Medical
output_license: null
provenance_date: '2026-11-09'
provider_name: AIRS Medical
provider_slug: airsmedical
slug: airsmedical-data-license
source_date: '2026-11-09'
source_filename: airsmedical-data-license.yml
source_heading: Data License
source_page: https://airsmed.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ndata_license: 0.1.0\nprovider: AIRS Medical\naid: airsmedical\nurl: https://airsmed.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\noutputs:\n  license: null\n  stance_commercial: conditional\n  text: 'You will not: (a) engage in the service of operating the Software on behalf of third parties; (b) engage\n    in the service of operating the Software to analyze MRI datasets that originate from imaging centers or MRI\n    scanners outside of Your facility'\ndata:\n  license: custom\n  stance_commercial: allowed\n  text: AIRS may create Anonymized Data and combine it with data from other customers into a new aggregate dataset\n    (“Aggregate\
  \ Data”), and shall have a right to use, disclose, reproduce, sell, disseminate, publicize or otherwise\n    exploit any such Anonymized Data or Aggregate Data for any purpose.\nattribution:\n  required: null\n  text: null\ninterface_license:\n  url: null\n"
source_yaml_url: https://artifacts.apis.io/airsmedical/data-license/airsmedical-data-license.yml
stated_fields:
- outputs
- data
summary_line: 2 quoted statements, read from AIRS Medical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Imaging
- MRI
- Radiology
- Artificial Intelligence
- Medical Devices
- DICOM
---
