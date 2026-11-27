---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website is operated by us in the United States. Those who choose to access the Website from locations outside the United States do so at their own initiative and are responsible for compliance with applicable local laws.
  entity_types:
  - text: You must be at least 18 years of age to access the Website.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to access the Website.
    value: '18'
  restricted_uses:
  - summary: Illegal, harassing or unethical use
    text: (k) use the Website for illegal, harassing, offensive, unethical, or disruptive purposes
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
name: Erasca
provenance_date: '2026-11-09'
provider_name: Erasca
provider_slug: erasca
slug: erasca-eligibility
source_date: '2026-11-09'
source_filename: erasca-eligibility.yml
source_heading: Eligibility
source_page: https://www.erasca.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Erasca\naid: erasca\nurl: https://www.erasca.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website is operated by us in the United States. Those who choose to access the Website from locations\n    outside the United States do so at their own initiative and are responsible for compliance with applicable local\n    laws.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to access the Website.\nrestricted_uses:\n- summary: Illegal, harassing or unethical use\n  text: (k) use the Website for illegal, harassing, offensive, unethical,\
  \ or disruptive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to access the Website.\n"
source_yaml_url: https://artifacts.apis.io/erasca/eligibility/erasca-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Erasca's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Precision Oncology
- Cancer Therapeutics
- RAS/MAPK Pathway
- Clinical Stage
- Life Sciences
---
