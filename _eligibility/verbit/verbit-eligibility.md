---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Customer” refers to you or the legal entity on behalf of whom you accept this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing content
    text: use the Services in violation of applicable laws or regulations, including to submit Files comprising unlawful, infringing, libelous, or other tortious content
  - summary: Sensitive information in Files
    text: submit Files containing sensitive information such as social security numbers, bank information, credit card information, or (except where the Parties have executed a Business Associate Agreement) protected health information
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
name: VerbIT
provenance_date: '2026-11-10'
provider_name: VerbIT
provider_slug: verbit
slug: verbit-eligibility
source_date: '2026-11-10'
source_filename: verbit-eligibility.yml
source_heading: Eligibility
source_page: https://verbit.ai/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VerbIT\naid: verbit\nurl: https://verbit.ai/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Customer” refers to you or the legal entity on behalf of whom you accept this Agreement\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: use the Services in violation of applicable laws or regulations, including to submit Files comprising unlawful,\n    infringing, libelous, or other tortious content\n- summary: Sensitive information in Files\n  text: submit Files containing sensitive information such\
  \ as social security numbers, bank information, credit\n    card information, or (except where the Parties have executed a Business Associate Agreement) protected health\n    information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/verbit/eligibility/verbit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from VerbIT's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- Transcription
- Captioning
- Speech Recognition
- Accessibility
- Artificial Intelligence
- Media
---
