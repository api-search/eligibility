---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Anduin Services are directed to users in the United States
  entity_types:
  - text: You agree that by using the services you are at least 18 years of age and you are legally able to enter into a contract
    type: individual
  - text: If you access or use the Services on behalf of a company, organization, or other entity, then (a) “you” and “your” also refers to that entity
    type: business
  - text: If any contractual obligation in these Terms would result in a violation or breach of legal or regulatory requirements or policies applicable to you as a governmental entity or because you can claim sovereign immunity, such obligation may not apply to you if you notify us of such non-applicability.
    type: government
  minimum_age:
    text: You agree that by using the services you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Embargoed countries and blocked persons
    text: You may not use the Services if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
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
name: Anduin
provenance_date: '2026-11-09'
provider_name: Anduin
provider_slug: anduin
slug: anduin-eligibility
source_date: '2026-11-09'
source_filename: anduin-eligibility.yml
source_heading: Eligibility
source_page: https://anduintransact.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anduin\naid: anduin\nurl: https://anduintransact.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Anduin Services are directed to users in the United States\nentity_types:\n- type: individual\n  text: You agree that by using the services you are at least 18 years of age and you are legally able to enter\n    into a contract\n- type: business\n  text: If you access or use the Services on behalf of a company, organization, or other entity, then (a) “you”\n    and “your” also refers to that entity\n- type: government\n  text: If any contractual obligation in\
  \ these Terms would result in a violation or breach of legal or regulatory\n    requirements or policies applicable to you as a governmental entity or because you can claim sovereign immunity,\n    such obligation may not apply to you if you notify us of such non-applicability.\nrestricted_uses:\n- summary: Embargoed countries and blocked persons\n  text: You may not use the Services if you are a resident of a country embargoed by the United States, or are a\n    foreign person or entity blocked or denied by the United States government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You agree that by using the services you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/anduin/eligibility/anduin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Anduin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Private Markets
- Fund Administration
- Investor Onboarding
- Fund Subscription
- Venture Capital
- Private Equity
- E-Signature
- Fintech
---
