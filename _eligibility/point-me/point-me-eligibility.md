---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representations that our Services are appropriate or available for use in other jurisdictions. If you access or use our Services from other jurisdictions, then you do so by your own volition and are solely responsible for compliance with local law.
  entity_types:
  - text: You must be 18 years of age or older to use our Services.
    type: individual
  - text: If you are entering into these Terms on behalf of an entity, such as the company you work for, you represent that you have authority to bind that entity
    type: business
  minimum_age:
    text: You must be 18 years of age or older to use our Services.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You are only entitled to access and use our Services for lawful purposes and pursuant to these Terms.
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
name: POINT.ME
provenance_date: '2026-11-10'
provider_name: POINT.ME
provider_slug: point-me
slug: point-me-eligibility
source_date: '2026-11-10'
source_filename: point-me-eligibility.yml
source_heading: Eligibility
source_page: https://www.point.me/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: POINT.ME\naid: point-me\nurl: https://www.point.me/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representations that our Services are appropriate or available for use in other jurisdictions.\n    If you access or use our Services from other jurisdictions, then you do so by your own volition and are solely\n    responsible for compliance with local law.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older to use our Services.\n- type: business\n  text: If you are entering into these Terms on behalf of an entity, such\
  \ as the company you work for, you represent\n    that you have authority to bind that entity\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You are only entitled to access and use our Services for lawful purposes and pursuant to these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/point-me/eligibility/point-me-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from POINT.ME's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Award Travel
- Loyalty
- Points and Miles
- Flights
- Rewards
- Embedded Finance
- Banking
- Search
- Company
- Loyalty & Incentives
---
