---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent and warrant that you are the legal age of majority under applicable law to form a binding contract with DuPont
    type: individual
  minimum_age:
    text: you represent and warrant that you are the legal age of majority under applicable law to form a binding contract with DuPont
    value: age of majority
  restricted_uses:
  - summary: unlawful or Terms-violating use
    text: you may not use this Site for a purpose that is unlawful or violates these Terms
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
name: DuPont
provenance_date: '2026-11-09'
provider_name: DuPont
provider_slug: dupont
slug: dupont-eligibility
source_date: '2026-11-09'
source_filename: dupont-eligibility.yml
source_heading: Eligibility
source_page: https://www.dupont.com/legal-notices-and-terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DuPont\naid: dupont\nurl: https://www.dupont.com/legal-notices-and-terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent and warrant that you are the legal age of majority under applicable law to form a binding\n    contract with DuPont\nrestricted_uses:\n- summary: unlawful or Terms-violating use\n  text: you may not use this Site for a purpose that is unlawful or violates these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n\
  \  text: you represent and warrant that you are the legal age of majority under applicable law to form a binding\n    contract with DuPont\n"
source_yaml_url: https://artifacts.apis.io/dupont/eligibility/dupont-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from DuPont's own page on 2026-11-09.
synthetic: false
tags:
- Fortune 500
- Industrial
- Materials Science
- Chemicals
- Manufacturing
---
