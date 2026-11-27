---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within the United States where the Services are available.
  minimum_age:
    text: The Site and Services are only for persons 18 years or older, or a minor if represented by a parent or legal guardian
    value: '18'
  restricted_uses:
  - summary: Not for medical emergencies
    text: THE SERVICES MAY NOT BE MONITORED IN REAL-TIME BY CLINICAL STAFF AND MUST NOT BE USED FOR MEDICAL EMERGENCIES.
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
name: Pair Team
provenance_date: '2026-11-10'
provider_name: Pair Team
provider_slug: pair-team
slug: pair-team-eligibility
source_date: '2026-11-10'
source_filename: pair-team-eligibility.yml
source_heading: Eligibility
source_page: https://pairteam.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pair Team\naid: pair-team\nurl: https://pairteam.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within\n    the United States where the Services are available.\nentity_types: []\nrestricted_uses:\n- summary: Not for medical emergencies\n  text: THE SERVICES MAY NOT BE MONITORED IN REAL-TIME BY CLINICAL STAFF AND MUST NOT BE USED FOR MEDICAL EMERGENCIES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n \
  \ text: The Site and Services are only for persons 18 years or older, or a minor if represented by a parent or legal\n    guardian\n"
source_yaml_url: https://artifacts.apis.io/pair-team/eligibility/pair-team-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pair Team's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Care Coordination
- Medicaid
- Medicare
- Care Management
- Social Determinants of Health
- Digital Health
---
