---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Digital Services is limited exclusively to users located in states within the United States where the Digital Services are available. Services are not available to users located outside the United States.
  entity_types:
  - text: You represent that you are not a person barred from enrolling for or receiving the Digital Services under the laws of the United States or other applicable jurisdictions
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you do not provide this information in the manner requested within 14 days of the request, we reserve the right to suspend, discontinue, or deny your access
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Synapticure
provenance_date: '2026-11-10'
provider_name: Synapticure
provider_slug: synapticure
slug: synapticure-eligibility
source_date: '2026-11-10'
source_filename: synapticure-eligibility.yml
source_heading: Eligibility
source_page: https://www.synapticure.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Synapticure\naid: synapticure\nurl: https://www.synapticure.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Digital Services is limited exclusively to users located in states within the United\n    States where the Digital Services are available. Services are not available to users located outside the United\n    States.\nentity_types:\n- type: individual\n  text: You represent that you are not a person barred from enrolling for or receiving the Digital Services under\n    the laws of the United States or other applicable jurisdictions\n\
  restricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you do not provide this information in the manner requested within 14 days of the request, we reserve\n    the right to suspend, discontinue, or deny your access\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/synapticure/eligibility/synapticure-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Synapticure's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Healthcare
- Telehealth
- Neurology
- Digital Health
- Virtual Care
- Patient Care
---
