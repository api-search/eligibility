---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are being provided to you on a non-exclusive, non-transferable basis solely for your internal use in the U.S. We make no claims that the Services or any of the content is accessible or appropriate outside of the United States.
  entity_types:
  - text: you are at least the age of legal majority in your place of residence and otherwise legally competent to enter into contracts.
    type: individual
  - text: The information that we make available through the Services is intended for physicians and other healthcare professionals.
    type: other
  minimum_age:
    text: you are at least the age of legal majority in your place of residence and otherwise legally competent to enter into contracts.
    value: age of legal majority
  restricted_uses:
  - summary: Commercial purpose
    text: You may not access or use the Services, any part of the Services, or any materials available through the Services for a commercial purpose, except with written permission from epocrates.
  - summary: AI training or development
    text: unauthorized use of Epocrates Data for training, developing, or improving large language models (LLMs) or any artificial intelligence (AI) systems is strictly prohibited.
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
name: Epocrates
provenance_date: '2026-11-09'
provider_name: Epocrates
provider_slug: epocrates
slug: epocrates-eligibility
source_date: '2026-11-09'
source_filename: epocrates-eligibility.yml
source_heading: Eligibility
source_page: https://www.epocrates.com/discover/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Epocrates\naid: epocrates\nurl: https://www.epocrates.com/discover/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are being provided to you on a non-exclusive, non-transferable basis solely for your internal\n    use in the U.S. We make no claims that the Services or any of the content is accessible or appropriate outside\n    of the United States.\nentity_types:\n- type: individual\n  text: you are at least the age of legal majority in your place of residence and otherwise legally competent to\n    enter into contracts.\n- type: other\n  text: The\
  \ information that we make available through the Services is intended for physicians and other healthcare\n    professionals.\nrestricted_uses:\n- summary: Commercial purpose\n  text: You may not access or use the Services, any part of the Services, or any materials available through the\n    Services for a commercial purpose, except with written permission from epocrates.\n- summary: AI training or development\n  text: unauthorized use of Epocrates Data for training, developing, or improving large language models (LLMs) or\n    any artificial intelligence (AI) systems is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of legal majority\n  text: you are at least the age of legal majority in your place of residence and otherwise legally competent to\n    enter into contracts.\n"
source_yaml_url: https://artifacts.apis.io/epocrates/eligibility/epocrates-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Epocrates's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Reference
- Drug Database
- Clinical Decision Support
- Drug Interactions
- Mobile App
- Athenahealth
---
