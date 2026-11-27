---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use our Services.
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful content
    text: You agree not to upload content that is illegal, harmful, infringing, or otherwise violates these Terms.
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
name: Strongkeep
provenance_date: '2026-11-10'
provider_name: Strongkeep
provider_slug: strongkeep
slug: strongkeep-eligibility
source_date: '2026-11-10'
source_filename: strongkeep-eligibility.yml
source_heading: Eligibility
source_page: https://strongkeep.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Strongkeep\naid: strongkeep\nurl: https://strongkeep.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a company or other legal entity, you represent and warrant that\n    you have the authority to bind that entity.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: You agree not to upload content that is illegal, harmful, infringing, or otherwise violates these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years old to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/strongkeep/eligibility/strongkeep-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Strongkeep's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Security
- Small Business
- Malware Protection
- Phishing
- Security Awareness Training
- Compliance
- Human Risk
- 500 Global
---
