---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are at least 18 years of age and can form a binding contract.
    type: individual
  - text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization's or entity's behalf
    type: other
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age and can form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: You will only use the Services for your own internal, non-commercial use, and not on behalf of or for the benefit of any third party
  - summary: Competitors barred
    text: No competing company or any employee, independent contractor, agent or affiliate acting therefore may download, install, use or access the Services without AfterHour's express written consent.
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
name: AfterHour
provenance_date: '2026-11-09'
provider_name: AfterHour
provider_slug: afterhour
slug: afterhour-eligibility
source_date: '2026-11-09'
source_filename: afterhour-eligibility.yml
source_heading: Eligibility
source_page: https://www.afterhour.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AfterHour\naid: afterhour\nurl: https://www.afterhour.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years of age and can form a binding contract.\n- type: other\n  text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization's or entity's behalf\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You will only use the Services for your own internal,\
  \ non-commercial use, and not on behalf of or for the\n    benefit of any third party\n- summary: Competitors barred\n  text: No competing company or any employee, independent contractor, agent or affiliate acting therefore may download,\n    install, use or access the Services without AfterHour's express written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age and can form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/afterhour/eligibility/afterhour-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AfterHour's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Fintech
- Social Trading
- Investing
- Stock Market
- Community
- Brokerage
- Mobile App
---
