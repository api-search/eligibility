---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Limited Warranty is limited to the United States and does not apply to any Products purchased or used outside of the United States. The prices displayed are quoted in U.S. currency and are valid only in the United States.
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  - text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization's or entity's behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 16 years of age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the Services
    value: '16'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You will only use the Services and Products in a manner that complies with all laws that apply to you.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: You may be required to sign up for an account, which may include selecting a password and user name
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ernesta
provenance_date: '2026-11-09'
provider_name: Ernesta
provider_slug: ernesta
slug: ernesta-eligibility
source_date: '2026-11-09'
source_filename: ernesta-eligibility.yml
source_heading: Eligibility
source_page: https://www.ernestarugs.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ernesta\naid: ernesta\nurl: https://www.ernestarugs.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Limited Warranty is limited to the United States and does not apply to any Products purchased or used\n    outside of the United States. The prices displayed are quoted in U.S. currency and are valid only in the United\n    States.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n- type: business\n  text: If you're agreeing to these Terms on behalf of an organization\
  \ or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization's or entity's behalf\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You will only use the Services and Products in a manner that complies with all laws that apply to you.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: You may be required to sign up for an account, which may include selecting a password and user name\nminimum_age:\n  value: '16'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 16 years\n    of age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the\n    Services\n"
source_yaml_url: https://artifacts.apis.io/ernesta/eligibility/ernesta-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Ernesta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Rugs
- Homes
- Interior Design
- E-Commerce
- Retail
- Direct to Consumer
---
