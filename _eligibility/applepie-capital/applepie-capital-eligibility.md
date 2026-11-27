---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be eighteen (18) years of age or older and a legal resident of the United States to use this Site.
  entity_types:
  - text: You must be eighteen (18) years of age or older and a legal resident of the United States to use this Site.
    type: individual
  - text: Your User Account is to be used solely by (i) the individual for whom it was created or (ii) on behalf of any entity represented by an authorized individual.
    type: business
  minimum_age:
    text: You must be eighteen (18) years of age or older and a legal resident of the United States to use this Site.
    value: '18'
  restricted_uses:
  - summary: Sanctioned entities or persons
    text: you may not use the Site if you are an entity or foreign person embargoed, blocked, or denied by the United States government.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right to reject any Site registration and/or decline any application for a loan, subject to applicable regulations.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Applepie Capital
provenance_date: '2026-11-09'
provider_name: Applepie Capital
provider_slug: applepie-capital
slug: applepie-capital-eligibility
source_date: '2026-11-09'
source_filename: applepie-capital-eligibility.yml
source_heading: Eligibility
source_page: https://www.applepiecapital.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Applepie Capital\naid: applepie-capital\nurl: https://www.applepiecapital.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be eighteen (18) years of age or older and a legal resident of the United States to use this Site.\nentity_types:\n- type: individual\n  text: You must be eighteen (18) years of age or older and a legal resident of the United States to use this Site.\n- type: business\n  text: Your User Account is to be used solely by (i) the individual for whom it was created or (ii) on behalf of\n    any entity represented by an authorized\
  \ individual.\nrestricted_uses:\n- summary: Sanctioned entities or persons\n  text: you may not use the Site if you are an entity or foreign person embargoed, blocked, or denied by the United\n    States government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right to reject any Site registration and/or decline any application for a loan, subject\n    to applicable regulations.\nminimum_age:\n  value: '18'\n  text: You must be eighteen (18) years of age or older and a legal resident of the United States to use this Site.\n"
source_yaml_url: https://artifacts.apis.io/applepie-capital/eligibility/applepie-capital-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Applepie Capital's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Franchise Financing
- Small Business Loans
- Marketplace Lending
---
