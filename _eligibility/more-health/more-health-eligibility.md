---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The product information provided on MORE Health and the Services is intended only for residents of the United States.
  entity_types:
  - text: The Services are for individual personal use.
    type: individual
  - text: Organizations, companies, and businesses may not become registered members or use our Services through individual members.
    type: business
  minimum_age:
    text: Currently, a user must be at least 18 years old to use MORE.
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: The content and Services may not be used for any illegal purpose.
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
name: MORE Health
provenance_date: '2026-11-10'
provider_name: MORE Health
provider_slug: more-health
slug: more-health-eligibility
source_date: '2026-11-10'
source_filename: more-health-eligibility.yml
source_heading: Eligibility
source_page: https://morehealth.com/en/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MORE Health\naid: more-health\nurl: https://morehealth.com/en/termsofuse\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The product information provided on MORE Health and the Services is intended only for residents of the United\n    States.\nentity_types:\n- type: individual\n  text: The Services are for individual personal use.\n- type: business\n  text: Organizations, companies, and businesses may not become registered members or use our Services through individual\n    members.\nrestricted_uses:\n- summary: Illegal purposes\n  text: The content and Services may not be\
  \ used for any illegal purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Currently, a user must be at least 18 years old to use MORE.\n"
source_yaml_url: https://artifacts.apis.io/more-health/eligibility/more-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from MORE Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Telehealth
- Second Opinion
- Medical Records
- Care Coordination
- Employee Benefits
- HIPAA
- Cross-Border Care
---
