---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are acting on behalf of a company or entity that you have the authority to bind
    type: business
  minimum_age:
    text: You may not use or enroll in or purchase any products or services, and you may not accept this Agreement, if you are not of a legal age to form a binding contract with Supernal.
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: (j) Use the site in any way that violates any applicable law or regulation
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
name: Supernal
provenance_date: '2026-11-10'
provider_name: Supernal
provider_slug: supernal-aero
slug: supernal-aero-eligibility
source_date: '2026-11-10'
source_filename: supernal-aero-eligibility.yml
source_heading: Eligibility
source_page: https://www.supernal.aero/termsofuse/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Supernal\naid: supernal-aero\nurl: https://www.supernal.aero/termsofuse/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are acting on behalf of a company or entity that you have the authority to bind\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: (j) Use the site in any way that violates any applicable law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may not use or enroll in or purchase any products or services, and\
  \ you may not accept this Agreement,\n    if you are not of a legal age to form a binding contract with Supernal.\n"
source_yaml_url: https://artifacts.apis.io/supernal-aero/eligibility/supernal-aero-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Supernal's own page on 2026-11-10.
synthetic: false
tags:
- Advanced Air Mobility
- Aerospace
- Air Taxi
- eVTOL
- Electric Aviation
- FAA Certification
- Hyundai
- Urban Air Mobility
- Vertiports
---
