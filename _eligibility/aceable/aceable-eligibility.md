---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: certifies that he or she is at least 18 years old, or if STUDENT is younger than 18 years old, that the legal guardian of STUDENT consents
    type: individual
  minimum_age:
    text: certifies that he or she is at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No resale or commercial use
    text: STUDENT agrees not to sell, resell or exploit for any commercial purposes, any portion of the Mobile App and/or Online course
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: STUDENT understands, agrees, and consents to ACEABLE accessing and using third-party databases
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aceable
provenance_date: '2026-11-09'
provider_name: Aceable
provider_slug: aceable
slug: aceable-eligibility
source_date: '2026-11-09'
source_filename: aceable-eligibility.yml
source_heading: Eligibility
source_page: https://www.aceableagent.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aceable\naid: aceable\nurl: https://www.aceableagent.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: certifies that he or she is at least 18 years old, or if STUDENT is younger than 18 years old, that the\n    legal guardian of STUDENT consents\nrestricted_uses:\n- summary: No resale or commercial use\n  text: STUDENT agrees not to sell, resell or exploit for any commercial purposes, any portion of the Mobile App\n    and/or Online course\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n\
  \  text: STUDENT understands, agrees, and consents to ACEABLE accessing and using third-party databases\nminimum_age:\n  value: '18'\n  text: certifies that he or she is at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/aceable/eligibility/aceable-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Aceable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- E-Learning
- Continuing Education
- Licensing
- Certification
- Drivers Education
- Real Estate
- Insurance
- Mortgage
- Compliance Training
- Austin
---
