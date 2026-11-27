---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are only available for persons in those jurisdictions in which they may be legally sold.
  entity_types:
  - text: Bravely is a platform that connects employees with expert conflict coaches and HR professionals
    type: individual
  minimum_age:
    text: You must be at least 18 years of age in order to use the Services.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: for your own personal, non-commercial (meaning, you may not leverage the Services as a separate business) use
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
name: Bravely
provenance_date: '2026-11-09'
provider_name: Bravely
provider_slug: bravely
slug: bravely-eligibility
source_date: '2026-11-09'
source_filename: bravely-eligibility.yml
source_heading: Eligibility
source_page: https://workbravely.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bravely\naid: bravely\nurl: https://workbravely.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are only available for persons in those jurisdictions in which they may be legally sold.\nentity_types:\n- type: individual\n  text: Bravely is a platform that connects employees with expert conflict coaches and HR professionals\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: for your own personal, non-commercial (meaning, you may not leverage the Services as a separate business)\n    use\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age in order to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/bravely/eligibility/bravely-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bravely's own page on 2026-11-09.
synthetic: false
tags:
- Coaching
- Employee Development
- Training Platform
- Leadership
- Artificial Intelligence
---
