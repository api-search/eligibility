---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using our Services, you confirm that you are at least 18 years old and capable of entering into a legally binding agreement.
    type: individual
  - text: If you use the Services on behalf of an entity, you represent that you are authorized to bind that entity to these Terms.
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old and capable of entering into a legally binding agreement.
    value: '18'
  restricted_uses:
  - summary: Fraudulent, illegal, or unauthorized purposes
    text: Use our Services for fraudulent, illegal, or unauthorized purposes.
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
name: The Bot Company
provenance_date: '2026-11-10'
provider_name: The Bot Company
provider_slug: the-bot-company
slug: the-bot-company-eligibility
source_date: '2026-11-10'
source_filename: the-bot-company-eligibility.yml
source_heading: Eligibility
source_page: https://www.bot.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Bot Company\naid: the-bot-company\nurl: https://www.bot.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By accessing or using our Services, you confirm that you are at least 18 years old and capable of entering\n    into a legally binding agreement.\n- type: business\n  text: If you use the Services on behalf of an entity, you represent that you are authorized to bind that entity\n    to these Terms.\nrestricted_uses:\n- summary: Fraudulent, illegal, or unauthorized purposes\n  text: Use our Services for fraudulent, illegal,\
  \ or unauthorized purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18 years old and capable of entering into a legally binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/the-bot-company/eligibility/the-bot-company-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from The Bot Company's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Robotics
- Household Robots
- Consumer Robotics
- Automation
- Hardware
- Artificial Intelligence
---
