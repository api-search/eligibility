---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We supply the Software for use by healthcare professionals, related organisations and Patients only
    type: other
  minimum_age:
    text: If you are using our Software or Services on behalf of someone without legal capacity or under the age of consent, you confirm that you have the authority to do so.
    value: null
  restricted_uses:
  - summary: Healthcare and patient use only
    text: We supply the Software for use by healthcare professionals, related organisations and Patients only, in connection with the purposes set out above or in your Agreement with us.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Elephant Healthcare
provenance_date: '2026-11-09'
provider_name: Elephant Healthcare
provider_slug: elephant-healthcare
slug: elephant-healthcare-eligibility
source_date: '2026-11-09'
source_filename: elephant-healthcare-eligibility.yml
source_heading: Eligibility
source_page: https://privacy.elephant.healthcare/software-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elephant Healthcare\naid: elephant-healthcare\nurl: https://privacy.elephant.healthcare/software-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: We supply the Software for use by healthcare professionals, related organisations and Patients only\nrestricted_uses:\n- summary: Healthcare and patient use only\n  text: We supply the Software for use by healthcare professionals, related organisations and Patients only, in\n    connection with the purposes set out above or in your Agreement with us.\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If you are using our Software or Services on behalf of someone without legal capacity or under the age of\n    consent, you confirm that you have the authority to do so.\n"
source_yaml_url: https://artifacts.apis.io/elephant-healthcare/eligibility/elephant-healthcare-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Elephant Healthcare's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Tech
- Electronic Health Records
- Digital Health
- Public Health
- Africa
- Interoperability
- Primary Care
---
