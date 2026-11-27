---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Altwork will not provide any Products for a User domiciled or doing business from any barred country.
  entity_types:
  - text: You may only purchase Products from the Website if you are at least 18 years old.
    type: individual
  minimum_age:
    text: By accessing, browsing and/or using this Website, the User represents and warrant that he or she is 18 (eighteen) years of age or older
    value: '18'
  restricted_uses:
  - summary: Offensive or illegal content
    text: the use of hateful, offensive, profane, racist, sexist, vulgar or otherwise inappropriate conduct or language on the Website is not permitted
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
name: Altwork
provenance_date: '2026-11-09'
provider_name: Altwork
provider_slug: altwork
slug: altwork-eligibility
source_date: '2026-11-09'
source_filename: altwork-eligibility.yml
source_heading: Eligibility
source_page: https://altwork.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Altwork\naid: altwork\nurl: https://altwork.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Altwork will not provide any Products for a User domiciled or doing business from any barred country.\nentity_types:\n- type: individual\n  text: You may only purchase Products from the Website if you are at least 18 years old.\nrestricted_uses:\n- summary: Offensive or illegal content\n  text: the use of hateful, offensive, profane, racist, sexist, vulgar or otherwise inappropriate conduct or language\n    on the Website is not permitted\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By accessing, browsing and/or using this Website, the User represents and warrant that he or she is 18 (eighteen)\n    years of age or older\n"
source_yaml_url: https://artifacts.apis.io/altwork/eligibility/altwork-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Altwork's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ergonomics
- Workstations
- BioPerformance
- E-Commerce
---
