---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old.
    type: individual
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No evading restrictions
    text: Do not evade a block, suspension, rate limit or safety control.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: AnonPing is not an identity-verification, emergency-response or professional-advice service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AnonPing
provenance_date: '2026-11-09'
provider_name: AnonPing
provider_slug: anonping-com
slug: anonping-com-eligibility
source_date: '2026-11-09'
source_filename: anonping-com-eligibility.yml
source_heading: Eligibility
source_page: https://anonping.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnonPing\naid: anonping-com\nurl: https://anonping.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old.\nrestricted_uses:\n- summary: No evading restrictions\n  text: Do not evade a block, suspension, rate limit or safety control.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: AnonPing is not an identity-verification, emergency-response or professional-advice service.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/anonping-com/eligibility/anonping-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from AnonPing's own page on 2026-11-09.
synthetic: false
tags:
- Chat
- Anonymous
- Social
- Artificial Intelligence
- Privacy
---
