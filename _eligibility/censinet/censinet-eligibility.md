---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are intended for use in the United States of America only.
  entity_types:
  - text: you represent and warrant that you have authority to bind to the company, business or other legal entity on whose behalf you are using the Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with laws; no PHI or personal identifiers
    text: you agree, while using the Services or Censinet Content, to comply with all applicable laws and regulations
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
name: Censinet
provenance_date: '2026-11-09'
provider_name: Censinet
provider_slug: censinet
slug: censinet-eligibility
source_date: '2026-11-09'
source_filename: censinet-eligibility.yml
source_heading: Eligibility
source_page: https://censinet.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Censinet\naid: censinet\nurl: https://censinet.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are intended for use in the United States of America only.\nentity_types:\n- type: business\n  text: you represent and warrant that you have authority to bind to the company, business or other legal entity\n    on whose behalf you are using the Services\nrestricted_uses:\n- summary: Compliance with laws; no PHI or personal identifiers\n  text: you agree, while using the Services or Censinet Content, to comply with all applicable laws and regulations\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/censinet/eligibility/censinet-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Censinet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Risk Management
- Cybersecurity
- AI Governance
---
