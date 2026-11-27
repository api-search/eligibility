---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity's behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 16; if you are a child under 16, please do not attempt to register for the Services
    value: '16'
  restricted_uses:
  - summary: Not a substitute for clinical judgment
    text: Our software complements good patient care and does not exempt the user from the responsibility to provide supervision, clinically review the patient, and make appropriate clinical decisions.
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
name: Us2.ai
provenance_date: '2026-11-10'
provider_name: Us2.ai
provider_slug: us2ai
slug: us2ai-eligibility
source_date: '2026-11-10'
source_filename: us2ai-eligibility.yml
source_heading: Eligibility
source_page: https://us2.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Us2.ai\naid: us2ai\nurl: https://us2.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization or entity's behalf\nrestricted_uses:\n- summary: Not a substitute for clinical judgment\n  text: Our software complements good patient care and does not exempt the user from the responsibility to provide\n    supervision, clinically review the patient,\
  \ and make appropriate clinical decisions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 16; if you\n    are a child under 16, please do not attempt to register for the Services\n"
source_yaml_url: https://artifacts.apis.io/us2ai/eligibility/us2ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Us2.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Cardiology
- Echocardiography
- Artificial Intelligence
- Medical Imaging
- DICOM
- Diagnostics
---
