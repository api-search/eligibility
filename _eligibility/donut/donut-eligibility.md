---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you access or use the Services in your capacity as an employee, consultant or agent of a company or other entity, you represent that you are an employee, consultant or agent of that company or entity
    type: business
  minimum_age:
    text: The Services are not intended for and should not be used by anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Discriminatory or harmful speech businesses
    text: you agree that you will not use the Services in support of a business that is dedicated to — or focused on facilitating or encouraging — discriminatory, malicious, or harmful speech or actions.
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
name: Donut
provenance_date: '2026-11-09'
provider_name: Donut
provider_slug: donut
slug: donut-eligibility
source_date: '2026-11-09'
source_filename: donut-eligibility.yml
source_heading: Eligibility
source_page: https://www.donut.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Donut\naid: donut\nurl: https://www.donut.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you access or use the Services in your capacity as an employee, consultant or agent of a company or other\n    entity, you represent that you are an employee, consultant or agent of that company or entity\nrestricted_uses:\n- summary: Discriminatory or harmful speech businesses\n  text: you agree that you will not use the Services in support of a business that is dedicated to — or focused\n    on facilitating or encouraging — discriminatory,\
  \ malicious, or harmful speech or actions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Services are not intended for and should not be used by anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/donut/eligibility/donut-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Donut's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Collaboration
- Employee Experience
- Slack
- Microsoft Teams
- Onboarding
- Team Building
- Recognition
- Human Resources
---
