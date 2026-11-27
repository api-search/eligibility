---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: we provide the Platform for use only by persons located in the U.S.
  entity_types:
  - text: Our Platform is offered and available to veterinarians, veterinary professionals and their amazing staff who are authorized by a veterinarian or veterinary professional to use the Platform.
    type: business
  - text: provide veterinary clinics, animal hospitals and veterinary nonprofits with technology that helps them succeed.
    type: nonprofit
  minimum_age:
    text: you must be eighteen (18) years of age or older and reside within the United States of America
    value: '18'
  restricted_uses:
  - summary: Lawful use only; no export violations
    text: You may use the Platform and Services only for lawful purposes and in accordance with these Terms of Use.
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
name: Vetcove
provenance_date: '2026-11-10'
provider_name: Vetcove
provider_slug: vetcove
slug: vetcove-eligibility
source_date: '2026-11-10'
source_filename: vetcove-eligibility.yml
source_heading: Eligibility
source_page: https://shop.vetcove.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vetcove\naid: vetcove\nurl: https://shop.vetcove.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: we provide the Platform for use only by persons located in the U.S.\nentity_types:\n- type: business\n  text: Our Platform is offered and available to veterinarians, veterinary professionals and their amazing staff\n    who are authorized by a veterinarian or veterinary professional to use the Platform.\n- type: nonprofit\n  text: provide veterinary clinics, animal hospitals and veterinary nonprofits with technology that helps them succeed.\nrestricted_uses:\n\
  - summary: Lawful use only; no export violations\n  text: You may use the Platform and Services only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be eighteen (18) years of age or older and reside within the United States of America\n"
source_yaml_url: https://artifacts.apis.io/vetcove/eligibility/vetcove-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vetcove's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Saas
- Veterinary
- Animal Health
- E-Commerce
- Procurement
- Marketplace
- Pets
---
