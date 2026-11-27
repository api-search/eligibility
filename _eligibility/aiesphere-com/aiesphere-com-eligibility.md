---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) and legally able to enter into this agreement to create an account directly with us.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Misrepresentation in applications
    text: You may not use the Service to submit applications, credentials, or documents for anyone other than yourself, or to misrepresent your identity, qualifications, work authorisation, or experience to an employer.
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
name: AiESphere
provenance_date: '2026-11-09'
provider_name: AiESphere
provider_slug: aiesphere-com
slug: aiesphere-com-eligibility
source_date: '2026-11-09'
source_filename: aiesphere-com-eligibility.yml
source_heading: Eligibility
source_page: https://aiesphere.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AiESphere\naid: aiesphere-com\nurl: https://aiesphere.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) and legally able to enter\n    into this agreement to create an account directly with us.\nrestricted_uses:\n- summary: Misrepresentation in applications\n  text: You may not use the Service to submit applications, credentials, or documents for anyone other than yourself,\n    or to misrepresent your identity, qualifications, work authorisation,\
  \ or experience to an employer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/aiesphere-com/eligibility/aiesphere-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AiESphere's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Careers
- Education
- Platform
- India
---
