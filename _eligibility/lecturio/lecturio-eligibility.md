---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Section 10(1) through (3) apply to Users and Organizations in Germany. Section 18(2) and 24(3) apply to Users and Organizations in the United States.
  entity_types:
  - text: The Registration of an Organization, such as a legal entity, a company, or a special fund under public law, may only be carried out by a natural person with unlimited legal capacity who is authorized to represent the Organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Clinical or diagnostic use
    text: The Services are not intended to substitute for the exercise of professional judgment by the user, including with respect to any clinical or diagnostic uses.
  - summary: Prohibited sensitive data
    text: including without limitation use of the electronic content or the Services in a clinical or diagnostic setting
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Some functions and features may not be available to an Organization or User without proof of identity or other requirements that will be stated on the applicable website.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lecturio
provenance_date: '2026-11-09'
provider_name: Lecturio
provider_slug: lecturio
slug: lecturio-eligibility
source_date: '2026-11-09'
source_filename: lecturio-eligibility.yml
source_heading: Eligibility
source_page: https://www.lecturio.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lecturio\naid: lecturio\nurl: https://www.lecturio.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Section 10(1) through (3) apply to Users and Organizations in Germany. Section 18(2) and 24(3) apply to\n    Users and Organizations in the United States.\nentity_types:\n- type: business\n  text: The Registration of an Organization, such as a legal entity, a company, or a special fund under public law,\n    may only be carried out by a natural person with unlimited legal capacity who is authorized to represent the\n    Organization\nrestricted_uses:\n\
  - summary: Clinical or diagnostic use\n  text: The Services are not intended to substitute for the exercise of professional judgment by the user, including\n    with respect to any clinical or diagnostic uses.\n- summary: Prohibited sensitive data\n  text: including without limitation use of the electronic content or the Services in a clinical or diagnostic setting\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Some functions and features may not be available to an Organization or User without proof of identity or\n    other requirements that will be stated on the applicable website.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lecturio/eligibility/lecturio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Lecturio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- Education
- EdTech
- Medical Education
- Nursing Education
- E-Learning
- Healthcare
- Exam Preparation
- Simulation
---
