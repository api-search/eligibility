---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services are controlled and offered by Chief from its facilities in the United States of America. Chief makes no representations that Services are appropriate or available for use in other locations.
  entity_types:
  - text: you are of legal age in your jurisdiction of residence to form a binding contract with Chief
    type: individual
  - text: you have the authority to enter into this Agreement personally and, if applicable, on behalf of any company, organization or other legal entity
    type: business
  minimum_age:
    text: be at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: Chief grants you a limited, non-transferable license to use the Services solely for your personal, non-commercial purposes.
  - summary: No commercial activities without consent
    text: involves commercial activities and/or sales without Chief's prior written consent
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Once your application is approved, in Chief’s sole discretion, the Membership Agreement will govern the terms and conditions of your Membership.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chief
provenance_date: '2026-11-09'
provider_name: Chief
provider_slug: chief
slug: chief-eligibility
source_date: '2026-11-09'
source_filename: chief-eligibility.yml
source_heading: Eligibility
source_page: https://chief.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chief\naid: chief\nurl: https://chief.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Services are controlled and offered by Chief from its facilities in the United States of America. Chief\n    makes no representations that Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: you are of legal age in your jurisdiction of residence to form a binding contract with Chief\n- type: business\n  text: you have the authority to enter into this Agreement personally and, if applicable, on behalf\
  \ of any company,\n    organization or other legal entity\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: Chief grants you a limited, non-transferable license to use the Services solely for your personal, non-commercial\n    purposes.\n- summary: No commercial activities without consent\n  text: involves commercial activities and/or sales without Chief's prior written consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Once your application is approved, in Chief’s sole discretion, the Membership Agreement will govern the\n    terms and conditions of your Membership.\nminimum_age:\n  value: '18'\n  text: be at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/chief/eligibility/chief-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Chief's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Membership
- Executive Network
- Leadership
- Community
- Coaching
- Women in Leadership
- Professional Network
---
