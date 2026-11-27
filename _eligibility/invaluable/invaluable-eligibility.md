---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using any Services, you affirm that you are over 18 years of age and are otherwise capable of forming legally binding contracts
    type: individual
  minimum_age:
    text: If you are under 18 years of age, or are otherwise incapable of forming legally binding contracts, or do not agree with any part of this Agreement, YOU MUST NOT ACCESS OR USE THE SERVICES.
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: The Services may be used only for lawful purposes and in a lawful manner.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Each AH that conducts a live or timed auction will have its own eligibility requirements that must be met in order for you to participate in that auction. You may be required to apply for and obtain approval in order to participate in a specific live or timed auction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Invaluable
provenance_date: '2026-11-09'
provider_name: Invaluable
provider_slug: invaluable
slug: invaluable-eligibility
source_date: '2026-11-09'
source_filename: invaluable-eligibility.yml
source_heading: Eligibility
source_page: https://www.invaluable.com/inv/agreements/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Invaluable\naid: invaluable\nurl: https://www.invaluable.com/inv/agreements/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By accessing or using any Services, you affirm that you are over 18 years of age and are otherwise capable\n    of forming legally binding contracts\nrestricted_uses:\n- summary: Lawful use only\n  text: The Services may be used only for lawful purposes and in a lawful manner.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Each AH that conducts a live or timed auction\
  \ will have its own eligibility requirements that must be met\n    in order for you to participate in that auction. You may be required to apply for and obtain approval in order\n    to participate in a specific live or timed auction\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, or are otherwise incapable of forming legally binding contracts, or do\n    not agree with any part of this Agreement, YOU MUST NOT ACCESS OR USE THE SERVICES.\n"
source_yaml_url: https://artifacts.apis.io/invaluable/eligibility/invaluable-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Invaluable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Auctions
- Marketplace
- Art
- Antiques
- Collectibles
- E-Commerce
- Bidding
---
