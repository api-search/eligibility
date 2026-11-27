---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged 18 years or older.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals aged 18 years or older.
    value: '18'
  restricted_uses:
  - summary: No unauthorized commercial communications
    text: You agree not to, and will not, use the communications systems provided by the Site to send unauthorized commercial communications
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
name: Oligo
provenance_date: '2026-11-10'
provider_name: Oligo
provider_slug: oligo
slug: oligo-eligibility
source_date: '2026-11-10'
source_filename: oligo-eligibility.yml
source_heading: Eligibility
source_page: https://www.oligo.security/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oligo\naid: oligo\nurl: https://www.oligo.security/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged 18 years or older.\nrestricted_uses:\n- summary: No unauthorized commercial communications\n  text: You agree not to, and will not, use the communications systems provided by the Site to send unauthorized\n    commercial communications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is only\
  \ intended for individuals aged 18 years or older.\n"
source_yaml_url: https://artifacts.apis.io/oligo/eligibility/oligo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Oligo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Application Security
- Runtime Security
- Cloud Security
- AI Security
- Vulnerability Management
- CADR
- SBOM
- Software Composition Analysis
---
