---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site and Services are not available to users located outside the United States.
  entity_types:
  - text: Access to and use of the Services is limited exclusively to users who are 18 years of age or older and that are located in States within the United States where the Services are available.
    type: individual
  - text: We do not accept orders from dealers, wholesalers, or other customers who intend to resell items offered via the Services.
    type: business
  minimum_age:
    text: Access to and use of the Services is limited exclusively to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Personal use of prescriptions
    text: You agree that any prescriptions that you acquire from a Provider will be solely for your personal use.
  - summary: No access from unavailable jurisdictions
    text: Accessing the Site or Services from jurisdictions where content is illegal, or where we do not offer Site or Services, is prohibited.
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
name: Plume Health
provenance_date: '2026-11-10'
provider_name: Plume Health
provider_slug: plume-health
slug: plume-health-eligibility
source_date: '2026-11-10'
source_filename: plume-health-eligibility.yml
source_heading: Eligibility
source_page: https://getplume.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plume Health\naid: plume-health\nurl: https://getplume.co/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site and Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: Access to and use of the Services is limited exclusively to users who are 18 years of age or older and that\n    are located in States within the United States where the Services are available.\n- type: business\n  text: We do not accept orders from dealers, wholesalers, or other customers who intend to resell items offered\n\
  \    via the Services.\nrestricted_uses:\n- summary: Personal use of prescriptions\n  text: You agree that any prescriptions that you acquire from a Provider will be solely for your personal use.\n- summary: No access from unavailable jurisdictions\n  text: Accessing the Site or Services from jurisdictions where content is illegal, or where we do not offer Site\n    or Services, is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Access to and use of the Services is limited exclusively to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/plume-health/eligibility/plume-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Plume Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Gender-Affirming Care
- Mental Health
- HIPAA
- Consumer Health
---
