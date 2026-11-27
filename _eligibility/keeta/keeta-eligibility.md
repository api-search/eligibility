---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: By using this Website, you represent and warrant that you are of legal age to form a binding contract with the Company.
    type: individual
  minimum_age:
    text: you are of legal age to form a binding contract with the Company
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.
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
name: Keeta
provenance_date: '2026-11-09'
provider_name: Keeta
provider_slug: keeta
slug: keeta-eligibility
source_date: '2026-11-09'
source_filename: keeta-eligibility.yml
source_heading: Eligibility
source_page: https://keeta.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Keeta\naid: keeta\nurl: https://keeta.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: By using this Website, you represent and warrant that you are of legal age to form a binding contract with\n    the Company.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: you are of legal age to form a binding contract with the Company\n"
source_yaml_url: https://artifacts.apis.io/keeta/eligibility/keeta-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Keeta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Payments
- Fintech
---
