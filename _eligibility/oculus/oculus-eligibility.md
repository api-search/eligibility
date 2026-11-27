---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: MPT Products are only intended for use in the countries listed on the "Supported Countries" page of the corresponding MPT Product.
  entity_types:
  - text: You must be at least 13 years of age to create one or more accounts supported by a MPT Product, such as a Meta account.
    type: individual
  - text: If you engage in a commercial use, you represent and warrant that you have legal authority to bind your organization to these Supplemental Terms
    type: business
  minimum_age:
    text: You must be at least 13 years of age to create one or more accounts supported by a MPT Product, such as a Meta account. You may create a Meta account on behalf of your child ages 10 to 12.
    value: '13'
  restricted_uses:
  - summary: Commercial use
    text: You may only use MPT Products for personal non-commercial purposes unless otherwise expressly permitted in these Supplemental Terms or authorized by us in writing.
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
name: Oculus
provenance_date: '2026-11-10'
provider_name: Oculus
provider_slug: oculus
slug: oculus-eligibility
source_date: '2026-11-10'
source_filename: oculus-eligibility.yml
source_heading: Eligibility
source_page: https://www.meta.com/legal/supplemental-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oculus\naid: oculus\nurl: https://www.meta.com/legal/supplemental-terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: MPT Products are only intended for use in the countries listed on the \"Supported Countries\" page of the\n    corresponding MPT Product.\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to create one or more accounts supported by a MPT Product, such as\n    a Meta account.\n- type: business\n  text: If you engage in a commercial use, you represent and warrant that you have legal authority to bind your\n    organization\
  \ to these Supplemental Terms\nrestricted_uses:\n- summary: Commercial use\n  text: You may only use MPT Products for personal non-commercial purposes unless otherwise expressly permitted\n    in these Supplemental Terms or authorized by us in writing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to create one or more accounts supported by a MPT Product, such as\n    a Meta account. You may create a Meta account on behalf of your child ages 10 to 12.\n"
source_yaml_url: https://artifacts.apis.io/oculus/eligibility/oculus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Oculus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Virtual Reality
- Augmented Reality
- Mixed Reality
- Gaming
- Developer Platform
- SDK
- Extended Reality
- Meta
---
