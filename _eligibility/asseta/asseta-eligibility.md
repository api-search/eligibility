---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Asseta does not permit Listings associated with certain countries due to U.S. embargo restrictions.
  entity_types:
  - text: If you accept or agree to these Terms on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms
    type: business
  - text: means a person who completes Asseta’s account registration process
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Counterfeit items
    text: Asseta doesn’t allow counterfeit items, replicas, or unauthorized copies to be listed on Asseta.
  - summary: Export controls
    text: You will comply with all applicable export and import control laws and regulations in its use of Equipment
  - summary: Missiles and weapons
    text: including the development, design, manufacture or production of missiles, or nuclear, chemical or biological weapons.
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
name: Asseta
provenance_date: '2026-11-09'
provider_name: Asseta
provider_slug: asseta
slug: asseta-eligibility
source_date: '2026-11-09'
source_filename: asseta-eligibility.yml
source_heading: Eligibility
source_page: https://www.asseta.com/tos.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asseta\naid: asseta\nurl: https://www.asseta.com/tos.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Asseta does not permit Listings associated with certain countries due to U.S. embargo restrictions.\nentity_types:\n- type: business\n  text: If you accept or agree to these Terms on behalf of a company or other legal entity, you represent and warrant\n    that you have the authority to bind that company or other legal entity to these Terms\n- type: individual\n  text: means a person who completes Asseta’s account registration process\nrestricted_uses:\n- summary: Counterfeit\
  \ items\n  text: Asseta doesn’t allow counterfeit items, replicas, or unauthorized copies to be listed on Asseta.\n- summary: Export controls\n  text: You will comply with all applicable export and import control laws and regulations in its use of Equipment\n- summary: Missiles and weapons\n  text: including the development, design, manufacture or production of missiles, or nuclear, chemical or biological\n    weapons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/asseta/eligibility/asseta-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 6 quoted statements, read from Asseta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Semiconductors
- Equipment
- Secondary Market
- Procurement
- Industrial
- E-Commerce
---
