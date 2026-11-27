---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: BURST only ships currently to addresses in the United States and Canada.
  entity_types:
  - text: You agree not to register for more than one Account, register for an Account on behalf of an individual other than yourself without such individual’s authorization, or register for an Account on behalf of any group or entity.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age on the date you register for Membership.
    value: '18'
  restricted_uses:
  - summary: Membership not transferable or commercial
    text: You further agree not to sell, transfer, assign, license, or sublicense your Membership to any other person or to use the Membership for any commercial purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require additional verifications or information before accepting any Order.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Burst Oral Care
provenance_date: '2026-11-09'
provider_name: Burst Oral Care
provider_slug: burst-oral-care
slug: burst-oral-care-eligibility
source_date: '2026-11-09'
source_filename: burst-oral-care-eligibility.yml
source_heading: Eligibility
source_page: https://burstoralcare.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Burst Oral Care\naid: burst-oral-care\nurl: https://burstoralcare.com/pages/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: BURST only ships currently to addresses in the United States and Canada.\nentity_types:\n- type: individual\n  text: You agree not to register for more than one Account, register for an Account on behalf of an individual\n    other than yourself without such individual’s authorization, or register for an Account on behalf of any group\n    or entity.\nrestricted_uses:\n- summary: Membership not transferable or commercial\n\
  \  text: You further agree not to sell, transfer, assign, license, or sublicense your Membership to any other person\n    or to use the Membership for any commercial purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require additional verifications or information before accepting any Order.\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age on the date you register for Membership.\n"
source_yaml_url: https://artifacts.apis.io/burst-oral-care/eligibility/burst-oral-care-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Burst Oral Care's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Oral Care
- Consumer Goods
- Health
- E-Commerce
---
