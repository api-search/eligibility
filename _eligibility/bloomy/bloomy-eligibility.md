---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only adults who are at least 18 years old may create a parent account or purchase a family subscription.
    type: individual
  minimum_age:
    text: Only adults who are at least 18 years old may create a parent account or purchase a family subscription.
    value: '18'
  restricted_uses:
  - summary: Not a substitute for formal schooling or professional services
    text: It is not a substitute for formal schooling, compliance with applicable homeschool or instructional requirements, special education services, professional tutoring, therapy, counseling, medical advice, or legal advice.
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
name: Bloomy
provenance_date: '2026-11-09'
provider_name: Bloomy
provider_slug: bloomy
slug: bloomy-eligibility
source_date: '2026-11-09'
source_filename: bloomy-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomylearning.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomy\naid: bloomy\nurl: https://www.bloomylearning.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only adults who are at least 18 years old may create a parent account or purchase a family subscription.\nrestricted_uses:\n- summary: Not a substitute for formal schooling or professional services\n  text: It is not a substitute for formal schooling, compliance with applicable homeschool or instructional requirements,\n    special education services, professional tutoring, therapy, counseling, medical advice, or legal advice.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Only adults who are at least 18 years old may create a parent account or purchase a family subscription.\n"
source_yaml_url: https://artifacts.apis.io/bloomy/eligibility/bloomy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bloomy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Artificial Intelligence
- Adaptive Learning
- K-12
- E-Learning
- Personalization
- AI Tutor
---
