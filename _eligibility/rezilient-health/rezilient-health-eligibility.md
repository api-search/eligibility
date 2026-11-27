---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Platform for use only by persons located in the United States.
  entity_types:
  - text: at least 18 years old and using the Platform for yourself, or you are the parent or legal guardian of someone who is at least 7 years old
    type: individual
  minimum_age:
    text: at least 13 years old but under age 18 and have your parent’s or legal guardian’s permission to use the Platform
    value: '13'
  restricted_uses:
  - summary: Commercial purposes
    text: Use the Platform (i) for any commercial purpose; (ii) for the benefit of any third party
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Satisfying the above requirements does not guarantee that you will receive access to the Platform or be connected to a Provider through the Platform.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rezilient Health
provenance_date: '2026-11-10'
provider_name: Rezilient Health
provider_slug: rezilient-health
slug: rezilient-health-eligibility
source_date: '2026-11-10'
source_filename: rezilient-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.rezilienthealth.com/legal/platform-tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rezilient Health\naid: rezilient-health\nurl: https://www.rezilienthealth.com/legal/platform-tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Platform for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: at least 18 years old and using the Platform for yourself, or you are the parent or legal guardian of someone\n    who is at least 7 years old\nrestricted_uses:\n- summary: Commercial purposes\n  text: Use the Platform (i) for any commercial purpose; (ii) for the benefit of any third party\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: Satisfying the above requirements does not guarantee that you will receive access to the Platform or be\n    connected to a Provider through the Platform.\nminimum_age:\n  value: '13'\n  text: at least 13 years old but under age 18 and have your parent’s or legal guardian’s permission to use the\n    Platform\n"
source_yaml_url: https://artifacts.apis.io/rezilient-health/eligibility/rezilient-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Rezilient Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Primary Care
- Telehealth
- Employer Benefits
- Hybrid Care
---
