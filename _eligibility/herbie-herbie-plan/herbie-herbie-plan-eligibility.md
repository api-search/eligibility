---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 18 years of age; if you are a child under 18 years of age, please do not attempt to register for or otherwise use the Services
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use
    text: Unless you have entered into a separate commercial agreement with Herbie, you will only use the Services for your own personal, non-commercial use
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
name: Herbie
provenance_date: '2026-11-09'
provider_name: Herbie
provider_slug: herbie-herbie-plan
slug: herbie-herbie-plan-eligibility
source_date: '2026-11-09'
source_filename: herbie-herbie-plan-eligibility.yml
source_heading: Eligibility
source_page: https://herbieplan.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Herbie\naid: herbie-herbie-plan\nurl: https://herbieplan.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Non-commercial personal use\n  text: Unless you have entered into a separate\
  \ commercial agreement with Herbie, you will only use the Services\n    for your own personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 18 years\n    of age; if you are a child under 18 years of age, please do not attempt to register for or otherwise use the\n    Services\n"
source_yaml_url: https://artifacts.apis.io/herbie-herbie-plan/eligibility/herbie-herbie-plan-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Herbie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Estate Planning
- Legal Tech
- Wills And Trusts
- Artificial Intelligence
- Wealth Management
- Document Automation
---
