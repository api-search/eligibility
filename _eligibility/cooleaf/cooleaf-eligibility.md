---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Local Laws; Export Control: User Sites and/or Third Party Content may not be appropriate or available for use outside of the United States of America.'
  entity_types:
  - text: 'Registration and participation on the Site and the Services is restricted to: individuals over 18 years of age; emancipated minors; and users under age 18 who possess legal parental or guardian consent.'
    type: individual
  - text: Administrators can control what privileges are granted to each of its Members
    type: business
  minimum_age:
    text: 'Registration and participation on the Site and the Services is restricted to: individuals over 18 years of age; emancipated minors; and users under age 18 who possess legal parental or guardian consent.'
    value: '18'
  restricted_uses:
  - summary: Personal or internal business use
    text: solely for your personal or internal business use
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
name: Cooleaf
provenance_date: '2026-11-09'
provider_name: Cooleaf
provider_slug: cooleaf
slug: cooleaf-eligibility
source_date: '2026-11-09'
source_filename: cooleaf-eligibility.yml
source_heading: Eligibility
source_page: https://www.cooleaf.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cooleaf\naid: cooleaf\nurl: https://www.cooleaf.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Local Laws; Export Control: User Sites and/or Third Party Content may not be appropriate or available for\n    use outside of the United States of America.'\nentity_types:\n- type: individual\n  text: 'Registration and participation on the Site and the Services is restricted to: individuals over 18 years\n    of age; emancipated minors; and users under age 18 who possess legal parental or guardian consent.'\n- type: business\n  text: Administrators can control what privileges\
  \ are granted to each of its Members\nrestricted_uses:\n- summary: Personal or internal business use\n  text: solely for your personal or internal business use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'Registration and participation on the Site and the Services is restricted to: individuals over 18 years\n    of age; emancipated minors; and users under age 18 who possess legal parental or guardian consent.'\n"
source_yaml_url: https://artifacts.apis.io/cooleaf/eligibility/cooleaf-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cooleaf's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Employee Engagement
- Employee Recognition
- Rewards
- Human Resources
- Employee Experience
- Surveys
- Software-as-a-Service
- Loyalty & Incentives
---
