---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    type: individual
  minimum_age:
    text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Acceptable use restrictions on user content
    text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content
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
name: o1 Labs
provenance_date: '2026-11-10'
provider_name: o1 Labs
provider_slug: o1-labs
slug: o1-labs-eligibility
source_date: '2026-11-10'
source_filename: o1-labs-eligibility.yml
source_heading: Eligibility
source_page: https://www.o1labs.org/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: o1 Labs\naid: o1-labs\nurl: https://www.o1labs.org/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\nrestricted_uses:\n- summary: Acceptable use restrictions on user content\n  text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the\
  \ Site or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/o1-labs/eligibility/o1-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from o1 Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Crypto Infrastructure
- Blockchain
- Zero Knowledge
- Cryptography
- zkApps
- Developer Tools
- SDK
---
