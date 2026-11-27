---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual or organization (“Registered User”, “Account Owner”) who registers to use the SKUPlugs Services by creating a SKUPlugs account
    type: individual
  - text: If an individual creates an account on behalf of their employer/organization, then the employer/organization will be deemed to be the Account Owner
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harm to minors
    text: You may not use our integration platform, API, and Website to harm minors in any way
  - summary: Illegal purpose
    text: You may not use the SKUPlugs integration platform for any illegal purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: SKUPlugs may reject your application for an Account, or cancel an existing Account, for any reason, at our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SKUPLUGS
provenance_date: '2026-11-10'
provider_name: SKUPLUGS
provider_slug: skuplugs
slug: skuplugs-eligibility
source_date: '2026-11-10'
source_filename: skuplugs-eligibility.yml
source_heading: Eligibility
source_page: https://skuplugs.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SKUPLUGS\naid: skuplugs\nurl: https://skuplugs.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual or organization (“Registered User”, “Account Owner”) who registers to use the SKUPlugs Services\n    by creating a SKUPlugs account\n- type: business\n  text: If an individual creates an account on behalf of their employer/organization, then the employer/organization\n    will be deemed to be the Account Owner\nrestricted_uses:\n- summary: Harm to minors\n  text: You may not use our integration platform,\
  \ API, and Website to harm minors in any way\n- summary: Illegal purpose\n  text: You may not use the SKUPlugs integration platform for any illegal purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: SKUPlugs may reject your application for an Account, or cancel an existing Account, for any reason, at our\n    sole discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/skuplugs/eligibility/skuplugs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from SKUPLUGS's own page on 2026-11-10.
synthetic: false
tags:
- E-Commerce
- InventorySync
- No-Code
- POS Integration
- Multi-Channel
---
