---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are located in, or a citizen or resident of any state, country, territory or other jurisdiction that is embargoed by the United States or where your use of the Services would be illegal or otherwise violate any applicable law.
  entity_types:
  - text: You must be at least 18 years of age to use our Services.
    type: individual
  - text: If you use our Services on behalf of another person or entity, (a) all references to “you” throughout these Terms will include that person or entity, (b) you represent that you are authorized to accept these Terms on that person’s or entity’s behalf
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use our Services.
    value: '18'
  restricted_uses:
  - summary: Prohibited input data types for AI Services
    text: 'you agree not to input, provide, or submit the following types of User Data in connection with your use of AI Services: Social Security numbers or government-issued identification numbers; Financial account numbers, credit card numbers, or banking information; Passwords or authentication credentials for third-party services'
  - summary: Not medical advice
    text: The Services and Output are not intended to provide any medical advice, opinion, diagnosis, treatment or guarantee
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
name: Imperfect
provenance_date: '2026-11-09'
provider_name: Imperfect
provider_slug: imperfect
slug: imperfect-eligibility
source_date: '2026-11-09'
source_filename: imperfect-eligibility.yml
source_heading: Eligibility
source_page: https://imperfect.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imperfect\naid: imperfect\nurl: https://imperfect.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are located in, or a citizen or resident of any state, country, territory\n    or other jurisdiction that is embargoed by the United States or where your use of the Services would be illegal\n    or otherwise violate any applicable law.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use our Services.\n- type: business\n  text: If you use our Services on behalf of another person or entity, (a) all references\
  \ to “you” throughout these\n    Terms will include that person or entity, (b) you represent that you are authorized to accept these Terms on\n    that person’s or entity’s behalf\nrestricted_uses:\n- summary: Prohibited input data types for AI Services\n  text: 'you agree not to input, provide, or submit the following types of User Data in connection with your use\n    of AI Services: Social Security numbers or government-issued identification numbers; Financial account numbers,\n    credit card numbers, or banking information; Passwords or authentication credentials for third-party services'\n- summary: Not medical advice\n  text: The Services and Output are not intended to provide any medical advice, opinion, diagnosis, treatment or\n    guarantee\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/imperfect/eligibility/imperfect-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Imperfect's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Fitness
- Wellness
- Sports
- Artificial Intelligence
- Coaching
- Wearables
- Consumer App
- Y Combinator
---
