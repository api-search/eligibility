---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you may not access or use the SERVICES or accept theSE Terms if you are not at least 18 years old.
    type: individual
  - text: you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: you may not access or use the SERVICES or accept theSE Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlicensed financial activities
    text: use the Services to carry out any financial activities subject to registration or licensing
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Users will not be required to submit any other personal information to use the Services, but NASD reserves the right to request such information in accordance with applicable law.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Noble
provenance_date: '2026-11-10'
provider_name: Noble
provider_slug: noble-xyz
slug: noble-xyz-eligibility
source_date: '2026-11-10'
source_filename: noble-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://noble.xyz/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Noble\naid: noble-xyz\nurl: https://noble.xyz/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you may not access or use the SERVICES or accept theSE Terms if you are not at least 18 years old.\n- type: business\n  text: you are accepting these Terms (on behalf of yourself or the entity that you represent)\nrestricted_uses:\n- summary: Unlicensed financial activities\n  text: use the Services to carry out any financial activities subject to registration or licensing\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Users will not be required to submit any other personal information to use the Services, but NASD reserves\n    the right to request such information in accordance with applicable law.\nminimum_age:\n  value: '18'\n  text: you may not access or use the SERVICES or accept theSE Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/noble-xyz/eligibility/noble-xyz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Noble's own page on 2026-11-10.
synthetic: false
tags:
- Stablecoins
- Infrastructure
- Payments
---
