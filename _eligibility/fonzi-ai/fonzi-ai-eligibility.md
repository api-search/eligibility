---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are not a resident of the United States of America, you acknowledge and agree that your information, including your Candidate Materials, will be transmitted to and processed in the United States.
  entity_types:
  - text: 'you represent: (i) that you are at least eighteen (18) years old (and in some jurisdictions, if required to enter into a contract, twenty-one (21) years old)'
    type: individual
  - text: If you are a Government end user, please consult first with your relevant legal department prior to use
    type: government
  minimum_age:
    text: 'you represent: (i) that you are at least eighteen (18) years old'
    value: '18'
  restricted_uses:
  - summary: Unlawful or harassing use
    text: 'you shall not use the Services: (i) for any unlawful purpose'
  - summary: Decisions with legal or material impact on a person
    text: you must not use any output relating to a person for any purpose that could have a legal or material impact on that person, such as making credit, educational, employment, housing, insurance, legal, medical, or other important decisions about them
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
name: fonzi-ai
provenance_date: '2026-11-09'
provider_name: fonzi-ai
provider_slug: fonzi-ai
slug: fonzi-ai-eligibility
source_date: '2026-11-09'
source_filename: fonzi-ai-eligibility.yml
source_heading: Eligibility
source_page: https://fonzi.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fonzi-ai\naid: fonzi-ai\nurl: https://fonzi.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are not a resident of the United States of America, you acknowledge and agree that your information,\n    including your Candidate Materials, will be transmitted to and processed in the United States.\nentity_types:\n- type: individual\n  text: 'you represent: (i) that you are at least eighteen (18) years old (and in some jurisdictions, if required\n    to enter into a contract, twenty-one (21) years old)'\n- type: government\n  text: If you are a Government end user, please\
  \ consult first with your relevant legal department prior to use\nrestricted_uses:\n- summary: Unlawful or harassing use\n  text: 'you shall not use the Services: (i) for any unlawful purpose'\n- summary: Decisions with legal or material impact on a person\n  text: you must not use any output relating to a person for any purpose that could have a legal or material impact\n    on that person, such as making credit, educational, employment, housing, insurance, legal, medical, or other\n    important decisions about them\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'you represent: (i) that you are at least eighteen (18) years old'\n"
source_yaml_url: https://artifacts.apis.io/fonzi-ai/eligibility/fonzi-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from fonzi-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Hiring
- Talent Marketplace
- Startups
---
