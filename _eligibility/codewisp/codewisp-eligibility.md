---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country subject to a U.S. Government embargo and are not on any U.S. Government list of prohibited or restricted parties.
  entity_types:
  - text: Users must be 13 or older.
    type: individual
  - text: Publishers must be at least 18 or have legal parental or guardian consent and the legal right to enter into this Agreement.
    type: individual
  minimum_age:
    text: Users must be 13 or older.
    value: '13'
  restricted_uses:
  - summary: Prohibited AI-generated content
    text: You will not use our AI features to generate (i) child sexual abuse material;
  - summary: Prohibited AI-generated malware or harmful code
    text: (iv) malware, phishing, or other harmful code;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We collect date of birth at signup and will terminate accounts that misrepresent age.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Codewisp
provenance_date: '2026-11-09'
provider_name: Codewisp
provider_slug: codewisp
slug: codewisp-eligibility
source_date: '2026-11-09'
source_filename: codewisp-eligibility.yml
source_heading: Eligibility
source_page: https://codewisp.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codewisp\naid: codewisp\nurl: https://codewisp.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country subject to a U.S. Government embargo and are not on\n    any U.S. Government list of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: Users must be 13 or older.\n- type: individual\n  text: Publishers must be at least 18 or have legal parental or guardian consent and the legal right to enter into\n    this Agreement.\nrestricted_uses:\n- summary: Prohibited AI-generated content\n  text: You will not\
  \ use our AI features to generate (i) child sexual abuse material;\n- summary: Prohibited AI-generated malware or harmful code\n  text: (iv) malware, phishing, or other harmful code;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We collect date of birth at signup and will terminate accounts that misrepresent age.\nminimum_age:\n  value: '13'\n  text: Users must be 13 or older.\n"
source_yaml_url: https://artifacts.apis.io/codewisp/eligibility/codewisp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Codewisp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Game Development
- Artificial Intelligence
- Generative AI
- No-Code
- Games
- Developer Tools
- Y Combinator
---
