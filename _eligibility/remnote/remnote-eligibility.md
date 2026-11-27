---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Service is intended for users who are at least 18 years old.
    type: individual
  minimum_age:
    text: The Service is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated data (HIPAA, FISMA, GLBA)
    text: RemNote is not tailored to comply with industry-specific regulations, such as the Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), and so on. If your interactions would be subjected to such laws, you may not use the Service.
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
name: Remnote
provenance_date: '2026-11-10'
provider_name: Remnote
provider_slug: remnote
slug: remnote-eligibility
source_date: '2026-11-10'
source_filename: remnote-eligibility.yml
source_heading: Eligibility
source_page: https://www.remnote.com/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Remnote\naid: remnote\nurl: https://www.remnote.com/terms_of_service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is not intended for distribution to or use by any person or entity in any jurisdiction or country\n    where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Service is intended for users who are at least 18 years old.\nrestricted_uses:\n- summary: Industry-regulated data (HIPAA, FISMA, GLBA)\n  text: RemNote is not tailored to comply with industry-specific regulations, such as the Health Insurance\
  \ Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), and so on. If your interactions\n    would be subjected to such laws, you may not use the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/remnote/eligibility/remnote-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Remnote's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Note Taking
- Knowledge Management
- Spaced Repetition
- Flashcards
- Education
- Productivity
- Plugin SDK
- Artificial Intelligence
- Learning
---
