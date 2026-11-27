---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing and using this Website, you represent and confirm that you are of legal age under applicable law and therefore legally able to enter into a binding contract with Poka
    type: individual
  minimum_age:
    text: you represent and confirm that you are of legal age under applicable law
    value: legal age
  restricted_uses:
  - summary: Benchmarking or competing products
    text: You may not use the Website, or any content, information, or materials made available through it, for benchmarking, competitive analysis, competitive intelligence, or to develop, support, or market a product or service that competes with Poka.
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
name: Poka
provenance_date: '2026-11-10'
provider_name: Poka
provider_slug: poka
slug: poka-eligibility
source_date: '2026-11-10'
source_filename: poka-eligibility.yml
source_heading: Eligibility
source_page: https://www.poka.io/en/website-terms-and-conditions-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Poka\naid: poka\nurl: https://www.poka.io/en/website-terms-and-conditions-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By accessing and using this Website, you represent and confirm that you are of legal age under applicable\n    law and therefore legally able to enter into a binding contract with Poka\nrestricted_uses:\n- summary: Benchmarking or competing products\n  text: You may not use the Website, or any content, information, or materials made available through it, for benchmarking,\n    competitive analysis, competitive\
  \ intelligence, or to develop, support, or market a product or service that\n    competes with Poka.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: you represent and confirm that you are of legal age under applicable law\n"
source_yaml_url: https://artifacts.apis.io/poka/eligibility/poka-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Poka's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Manufacturing
- Connected Worker
- Frontline Operations
- Industrial
- Workforce Training
- Integration
- Software-as-a-Service
---
