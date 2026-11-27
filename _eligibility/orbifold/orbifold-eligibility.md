---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Site only if you are 18 years or older and capable of forming a binding contract with Orbifold AI
    type: individual
  - text: If you are accessing and using the Site on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Site only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Commercial purpose use
    text: Use the Site, or any portion thereof, for any commercial purpose or for the benefit of any third party or in any manner not permitted by these Terms
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
name: Orbifold
provenance_date: '2026-11-10'
provider_name: Orbifold
provider_slug: orbifold
slug: orbifold-eligibility
source_date: '2026-11-10'
source_filename: orbifold-eligibility.yml
source_heading: Eligibility
source_page: https://www.orbifold.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Orbifold\naid: orbifold\nurl: https://www.orbifold.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Site only if you are 18 years or older and capable of forming a binding contract with Orbifold\n    AI\n- type: business\n  text: If you are accessing and using the Site on behalf of a company (such as your employer) or other legal entity,\n    you represent and warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Commercial purpose use\n  text: Use the\
  \ Site, or any portion thereof, for any commercial purpose or for the benefit of any third party or\n    in any manner not permitted by these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Site only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/orbifold/eligibility/orbifold-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Orbifold's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data
- Infrastructure
- Multi-Modal
---
