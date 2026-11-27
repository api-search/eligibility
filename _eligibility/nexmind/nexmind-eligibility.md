---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you must be a licensed attorney in good standing with a bar association in a jurisdiction where you intend to practice law and be at least 18 years of age.
    type: individual
  - text: In the case that you agree to these Terms on behalf of a company or another legal entity, you certify that you possess the authority to act as an authorized representative of that entity.
    type: business
  minimum_age:
    text: be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No unlawful or harmful use
    text: Utilize the Services in a manner or for any purpose that (i) violates or encourages the violation of any applicable law, regulation, legal requirement, contractual obligation, or right of any person
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To utilize the NexLaw Services, you must be a licensed attorney in good standing with a bar association in a jurisdiction where you intend to practice law
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NexMind
provenance_date: '2026-11-10'
provider_name: NexMind
provider_slug: nexmind
slug: nexmind-eligibility
source_date: '2026-11-10'
source_filename: nexmind-eligibility.yml
source_heading: Eligibility
source_page: https://www.nexlaw.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NexMind\naid: nexmind\nurl: https://www.nexlaw.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you must be a licensed attorney in good standing with a bar association in a jurisdiction where you intend\n    to practice law and be at least 18 years of age.\n- type: business\n  text: In the case that you agree to these Terms on behalf of a company or another legal entity, you certify that\n    you possess the authority to act as an authorized representative of that entity.\nrestricted_uses:\n- summary: No unlawful\
  \ or harmful use\n  text: Utilize the Services in a manner or for any purpose that (i) violates or encourages the violation of any\n    applicable law, regulation, legal requirement, contractual obligation, or right of any person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To utilize the NexLaw Services, you must be a licensed attorney in good standing with a bar association\n    in a jurisdiction where you intend to practice law\nminimum_age:\n  value: '18'\n  text: be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/nexmind/eligibility/nexmind-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from NexMind's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal
- Legal AI
- Legal Research
- Artificial Intelligence
- Litigation
- Document Analysis
- Software-as-a-Service
---
