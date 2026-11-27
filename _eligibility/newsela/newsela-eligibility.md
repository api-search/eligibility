---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access the Newsela Platform from a location outside of the United States, you are responsible for compliance with all local laws and regulations.
  entity_types:
  - text: The Newsela Platform is designed for use by schools, school districts, school administrators, Local Education Agencies, teachers, caregivers, and student users.
    type: other
  minimum_age:
    text: You certify that you are over at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Science content not to be replicated without supervision
    text: SCIENCE CONTENT IS NOT INTENDED TO BE REPLICATED, PERFORMED, OR ATTEMPTED BY ANY INDIVIDUAL WITHOUT (I) THE DIRECT, IN-PERSON SUPERVISION OF A QUALIFIED ADULT
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
name: Newsela
provenance_date: '2026-11-10'
provider_name: Newsela
provider_slug: newsela
slug: newsela-eligibility
source_date: '2026-11-10'
source_filename: newsela-eligibility.yml
source_heading: Eligibility
source_page: https://solutions.newsela.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Newsela\naid: newsela\nurl: https://solutions.newsela.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access the Newsela Platform from a location outside of the United States, you are responsible for\n    compliance with all local laws and regulations.\nentity_types:\n- type: other\n  text: The Newsela Platform is designed for use by schools, school districts, school administrators, Local Education\n    Agencies, teachers, caregivers, and student users.\nrestricted_uses:\n- summary: Science content not to be replicated without supervision\n  text: SCIENCE CONTENT\
  \ IS NOT INTENDED TO BE REPLICATED, PERFORMED, OR ATTEMPTED BY ANY INDIVIDUAL WITHOUT (I)\n    THE DIRECT, IN-PERSON SUPERVISION OF A QUALIFIED ADULT\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You certify that you are over at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/newsela/eligibility/newsela-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Newsela's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- K-12
- Content
- Assessment
- Literacy
- Reading
- OneRoster
- LTI
---
