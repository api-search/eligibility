---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are located in, or a citizen or resident of, any state, country, territory, or other jurisdiction that is embargoed by the United States or where your use of the Services would be illegal or otherwise violate applicable law.
  entity_types:
  - text: You must be at least 18 years of age to use our Services.
    type: individual
  - text: 'If you use our Services on behalf of another person or entity: All references to “you” throughout these Terms will include that person or entity.'
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use our Services.
    value: '18'
  restricted_uses:
  - summary: No AI training use
    text: Use the Services to train artificial intelligence or machine learning tools.
  - summary: Noncommercial personal use only
    text: for personal, noncommercial use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may contact you by telephone, mail, or email to verify your information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Exowatt
provenance_date: '2026-11-09'
provider_name: Exowatt
provider_slug: exowatt
slug: exowatt-eligibility
source_date: '2026-11-09'
source_filename: exowatt-eligibility.yml
source_heading: Eligibility
source_page: https://www.exowatt.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Exowatt\naid: exowatt\nurl: https://www.exowatt.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are located in, or a citizen or resident of, any state, country, territory,\n    or other jurisdiction that is embargoed by the United States or where your use of the Services would be illegal\n    or otherwise violate applicable law.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use our Services.\n- type: business\n  text: 'If you use our Services on behalf of another person or entity: All references\
  \ to “you” throughout these\n    Terms will include that person or entity.'\nrestricted_uses:\n- summary: No AI training use\n  text: Use the Services to train artificial intelligence or machine learning tools.\n- summary: Noncommercial personal use only\n  text: for personal, noncommercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may contact you by telephone, mail, or email to verify your information.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/exowatt/eligibility/exowatt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Exowatt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Clean Energy
- Solar
- Energy Storage
- Data Center
- Climate Tech
- Hardware
---
