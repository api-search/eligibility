---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer may access and use the Services only for its internal business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Attorneys only
    text: ONLY DULY LICENSED ATTORNEYS AND THEIR AGENTS ARE PERMITTED TO USE THE SERVICES.
  - summary: Not HIPAA-compliant use
    text: Customer acknowledges that the Services are not intended to meet any legal obligations for these uses, including HIPAA requirements, and that Briefpoint is not a Business Associate as defined under HIPAA.
  - summary: Export restrictions
    text: (a) represents and warrants that it is not listed on any U.S. government list of prohibited or restricted parties or located in (or a national of) a country that is subject to a U.S. government embargo
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Each registration is for a single individual only, unless specifically designated otherwise on the registration page.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Briefpoint
provenance_date: '2026-11-09'
provider_name: Briefpoint
provider_slug: briefpoint
slug: briefpoint-eligibility
source_date: '2026-11-09'
source_filename: briefpoint-eligibility.yml
source_heading: Eligibility
source_page: https://briefpoint.ai/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Briefpoint\naid: briefpoint\nurl: https://briefpoint.ai/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer may access and use the Services only for its internal business purposes\nrestricted_uses:\n- summary: Attorneys only\n  text: ONLY DULY LICENSED ATTORNEYS AND THEIR AGENTS ARE PERMITTED TO USE THE SERVICES.\n- summary: Not HIPAA-compliant use\n  text: Customer acknowledges that the Services are not intended to meet any legal obligations for these uses, including\n    HIPAA requirements, and that Briefpoint\
  \ is not a Business Associate as defined under HIPAA.\n- summary: Export restrictions\n  text: (a) represents and warrants that it is not listed on any U.S. government list of prohibited or restricted\n    parties or located in (or a national of) a country that is subject to a U.S. government embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Each registration is for a single individual only, unless specifically designated otherwise on the registration\n    page.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/briefpoint/eligibility/briefpoint-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Briefpoint's own page on 2026-11-09.
synthetic: false
tags:
- Legal Tech
- Artificial Intelligence
- Discovery
- Document Automation
- Litigation
---
