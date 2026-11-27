---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Agreement governs the relationship between you, a private person or a company, (hereinafter: Licensee)'
    type: individual
  - text: Note that a company-wide license must be obtained especially from the Licensor.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export violating law
    text: export or re-export the Software in violation of any applicable laws or regulations
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
name: autumo
provenance_date: '2026-11-09'
provider_name: autumo
provider_slug: autumo
slug: autumo-eligibility
source_date: '2026-11-09'
source_filename: autumo-eligibility.yml
source_heading: Eligibility
source_page: https://autumo.ch/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: autumo\naid: autumo\nurl: https://autumo.ch/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'Agreement governs the relationship between you, a private person or a company, (hereinafter: Licensee)'\n- type: business\n  text: Note that a company-wide license must be obtained especially from the Licensor.\nrestricted_uses:\n- summary: Export violating law\n  text: export or re-export the Software in violation of any applicable laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/autumo/eligibility/autumo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from autumo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Technology
- Security
- Software
- Finance
---
