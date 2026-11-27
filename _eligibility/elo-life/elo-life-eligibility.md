---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may access and use the Site and Materials only if you are legally able to enter into a binding contract with us
    type: individual
  - text: if you represent an entity or organization, that entity or organization (in either case “ you ” or “ your ”)
    type: business
  minimum_age:
    text: The Site and Materials are not directed to or intended for access by anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Use in violation of law or to harm others
    text: (b) use the Site, Materials, or Technology in any unlawful manner or in any other manner that could damage, disable, overburden, or impair the Site or Technology
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
name: Elo Life
provenance_date: '2026-11-09'
provider_name: Elo Life
provider_slug: elo-life
slug: elo-life-eligibility
source_date: '2026-11-09'
source_filename: elo-life-eligibility.yml
source_heading: Eligibility
source_page: https://elolife.com/website-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elo Life\naid: elo-life\nurl: https://elolife.com/website-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may access and use the Site and Materials only if you are legally able to enter into a binding contract\n    with us\n- type: business\n  text: if you represent an entity or organization, that entity or organization (in either case “ you ” or “ your\n    ”)\nrestricted_uses:\n- summary: Use in violation of law or to harm others\n  text: (b) use the Site, Materials, or Technology in any unlawful manner or in any\
  \ other manner that could damage,\n    disable, overburden, or impair the Site or Technology\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Site and Materials are not directed to or intended for access by anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/elo-life/eligibility/elo-life-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Elo Life's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Agriculture
- Food Technology
- Molecular Farming
- Sweeteners
- Gene Editing
- AgTech
---
