---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Teacher Accounts ... in the United States or Canada; Librarian Accounts ... in the United States or Canada
  entity_types:
  - text: School Accounts are only available for use by the Educational Institution and its students.
    type: business
  minimum_age:
    text: Every Account has one designated Adult User who must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: for your personal, noncommercial use only
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Teacher’s employment status must be independently verifiable
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Age of Learning
provenance_date: '2026-11-09'
provider_name: Age of Learning
provider_slug: age-of-learning
slug: age-of-learning-eligibility
source_date: '2026-11-09'
source_filename: age-of-learning-eligibility.yml
source_heading: Eligibility
source_page: https://www.ageoflearning.com/abc-t-and-c-current/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Age of Learning\naid: age-of-learning\nurl: https://www.ageoflearning.com/abc-t-and-c-current/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Teacher Accounts ... in the United States or Canada; Librarian Accounts ... in the United States or Canada\nentity_types:\n- type: business\n  text: School Accounts are only available for use by the Educational Institution and its students.\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: for your personal, noncommercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ Teacher’s employment status must be independently verifiable\nminimum_age:\n  value: '18'\n  text: Every Account has one designated Adult User who must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/age-of-learning/eligibility/age-of-learning-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Age of Learning's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EdTech
- Education
- E-Learning
- Early Childhood Education
- Children
- Consumer
- Learning
---
