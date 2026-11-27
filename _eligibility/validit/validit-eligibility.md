---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the user is an eligible legal entity that accepts the obligations associated with performing actions in the Digital Services
    type: business
  - text: holds an identity card
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use of platform content prohibited
    text: Without prior written authorization of the Company, you are not allowed to make any commercial use of the information published in the Digital Services
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
name: Valid.it
provenance_date: '2026-11-10'
provider_name: Valid.it
provider_slug: validit
slug: validit-eligibility
source_date: '2026-11-10'
source_filename: validit-eligibility.yml
source_heading: Eligibility
source_page: https://validit.ai/terms-of-use-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Valid.it\naid: validit\nurl: https://validit.ai/terms-of-use-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the user is an eligible legal entity that accepts the obligations associated with performing actions in\n    the Digital Services\n- type: individual\n  text: holds an identity card\nrestricted_uses:\n- summary: Commercial use of platform content prohibited\n  text: Without prior written authorization of the Company, you are not allowed to make any commercial use of the\n    information published in the Digital Services\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/validit/eligibility/validit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Valid.it's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fraud Prevention
- Identity Verification
- Deepfake Detection
- Deception Detection
- Artificial Intelligence
- KYC
- Security
---
