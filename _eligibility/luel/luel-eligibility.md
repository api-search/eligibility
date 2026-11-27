---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the Service, you must be at least 18 years old (or the age of majority in your jurisdiction).
    type: individual
  - text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual's employer (such entity, an “Organization”).
    type: business
  minimum_age:
    text: To use the Service, you must be at least 18 years old (or the age of majority in your jurisdiction).
    value: '18'
  restricted_uses:
  - summary: Biometric identification, surveillance, law enforcement
    text: use purchased User Content for biometric identification, surveillance, or law enforcement purposes unless expressly authorized in a separate written agreement with us
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
name: Luel
provenance_date: '2026-11-09'
provider_name: Luel
provider_slug: luel
slug: luel-eligibility
source_date: '2026-11-09'
source_filename: luel-eligibility.yml
source_heading: Eligibility
source_page: https://www.luel.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Luel\naid: luel\nurl: https://www.luel.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the Service, you must be at least 18 years old (or the age of majority in your jurisdiction).\n- type: business\n  text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual's\n    employer (such entity, an “Organization”).\nrestricted_uses:\n- summary: Biometric identification, surveillance, law enforcement\n  text: use purchased User Content for biometric\
  \ identification, surveillance, or law enforcement purposes unless\n    expressly authorized in a separate written agreement with us\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the Service, you must be at least 18 years old (or the age of majority in your jurisdiction).\n"
source_yaml_url: https://artifacts.apis.io/luel/eligibility/luel-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Luel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Training Data
- Data Marketplace
- Multi-Modal
- Video
- Audio
- Data Licensing
---
