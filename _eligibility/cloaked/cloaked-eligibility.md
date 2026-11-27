---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Currently available in 🇺🇸 and 🇨🇦.
  entity_types:
  - text: Cloaked grants to you a non-exclusive, non-transferable, revocable limited license to use the Service for your personal non-commercial use.
    type: individual
  minimum_age:
    text: IF YOU DO NOT AGREE, OR ARE BELOW THE AGE OF MAJORITY IN THE JURISDICTION YOU ARE LOCATED, YOU ARE NOT PERMITTED TO USE THE SERVICES.
    value: age of majority
  restricted_uses:
  - summary: Personal use only for eSIMs and Cloaked Phone
    text: Cloaked eSIMs must only be used for intended personal use
  - summary: No resale of eSIMs
    text: eSIMs are not to be sold, resold, leased, and/or sub-leased.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Cloaked or its vendors may require proof of identity to access or use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cloaked
provenance_date: '2026-11-09'
provider_name: Cloaked
provider_slug: cloaked
slug: cloaked-eligibility
source_date: '2026-11-09'
source_filename: cloaked-eligibility.yml
source_heading: Eligibility
source_page: https://www.cloaked.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cloaked\naid: cloaked\nurl: https://www.cloaked.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Currently available in \U0001F1FA\U0001F1F8 and \U0001F1E8\U0001F1E6.\nentity_types:\n- type: individual\n  text: Cloaked grants to you a non-exclusive, non-transferable, revocable limited license to use the Service for\n    your personal non-commercial use.\nrestricted_uses:\n- summary: Personal use only for eSIMs and Cloaked Phone\n  text: Cloaked eSIMs must only be used for intended personal use\n- summary: No resale of eSIMs\n\
  \  text: eSIMs are not to be sold, resold, leased, and/or sub-leased.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Cloaked or its vendors may require proof of identity to access or use the Service.\nminimum_age:\n  value: age of majority\n  text: IF YOU DO NOT AGREE, OR ARE BELOW THE AGE OF MAJORITY IN THE JURISDICTION YOU ARE LOCATED, YOU ARE NOT PERMITTED\n    TO USE THE SERVICES.\n"
source_yaml_url: https://artifacts.apis.io/cloaked/eligibility/cloaked-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Cloaked's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Privacy
- Identity
- Security
- Data Removal
- Password Manager
- Consumer
- Masked Email
- Virtual Phone
- Identity Theft Protection
---
