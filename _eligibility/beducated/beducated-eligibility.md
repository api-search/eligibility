---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may view the Beducated content primarily within the country in which you have established your account and only in geographic locations where we offer our service and have licensed such content.
  entity_types:
  - text: You must be 18 years of age, or the age of majority in your province, territory or country, to become a member of the Beducated service. Minors may only use the service under the supervision of an adult.
    type: individual
  minimum_age:
    text: You must be 18 years of age, or the age of majority in your province, territory or country, to become a member of the Beducated service.
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: The Beducated service and any content viewed through the service are for your personal and non-commercial use only
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
name: Beducated
provenance_date: '2026-11-09'
provider_name: Beducated
provider_slug: beducated
slug: beducated-eligibility
source_date: '2026-11-09'
source_filename: beducated-eligibility.yml
source_heading: Eligibility
source_page: https://beducated.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beducated\naid: beducated\nurl: https://beducated.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may view the Beducated content primarily within the country in which you have established your account\n    and only in geographic locations where we offer our service and have licensed such content.\nentity_types:\n- type: individual\n  text: You must be 18 years of age, or the age of majority in your province, territory or country, to become a\n    member of the Beducated service. Minors may only use the service under the supervision of an adult.\nrestricted_uses:\n\
  - summary: Non-commercial personal use only\n  text: The Beducated service and any content viewed through the service are for your personal and non-commercial\n    use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age, or the age of majority in your province, territory or country, to become a\n    member of the Beducated service.\n"
source_yaml_url: https://artifacts.apis.io/beducated/eligibility/beducated-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Beducated's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Sexual Health
- E-Learning
- Courses
- AdultEducation
---
